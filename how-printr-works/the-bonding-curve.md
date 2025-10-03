# The Bonding Curve

Bonding curves establish a clear relationship between **token supply and price**. As more tokens are bought or sold in the bonding curve, the price per token adjusts according to a predefined mathematical function. This provides clarity and predictability for the user.

Printr’s chain-agnostic bonding curve establishes a clear relationship between supply and price, **independent of the specific blockchain.**

### Curve Expression

The expression for the curve is:

$$
f(x) = \frac{MP(x + a)}{M - (x + a)}
$$

where:

* **M** = Maximum token supply
* **P** = Base price factor
* **x** = New supply added
* **a** = Virtual reserve (used to smooth pricing)

The function applies within this range:

$$
0 \leq x < M - a
$$

### How It Works

#### Price Calculation

* The **numerator** `MP(x + a)` represents the virtual reserve multiplied by the new supply.
* The **denominator** `M - (x + a)` prevents the price function from exceeding the total supply limit.
* The **result** is a dynamically increasing price curve that rises as supply nears its maximum.

#### Properties of the Curve

* **Supply-Driven Price Increases**: Prices rise as users mint more tokens, following the supply curve.
* **Liquidity Smoothing**: The virtual reserve `a` reduces sudden price jumps when users add new tokens.
* **Supply Constraints**: The function only works within valid supply limits, maintaining ecosystem stability.

The expression provides us a reliable pricing model for printed tokens while providing stability through the token's lifecycle.

### Implications

The implications of using this bonding curve expression are:

* Once the specified token supply is sold, the contract graduates the token and moves it to the DEX by creating a liquidity pool.
* Each chain operates **independently**, meaning tokens may graduate at different times.
* If a token is deployed across multiple chains, its supply is **split evenly**.
* The price volatility is higher based on demand due to the reduced per-chain supply.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FRDNhaJ1zWhbAbMzo8XWR%2FPrintr%20docs%20visual%202_3.21.png?alt=media&#x26;token=bad81494-dcc7-4f3a-8a4b-9085f61b112c" alt=""><figcaption></figcaption></figure>

***

### Common Questions

**Since the bonding is chain-agnostic, what happens when a token graduates on a chain faster than others?**

* Nothing exceptional really happens. The token on that chain becomes tradable on DEXs but is still tradable through our contract as it routes trades to DEXs under the hood.
* Graduation on one chain might trigger graduation on the other as a chain reaction. If a token is graduated, it means its price is higher. So it's profitable to buy it where it hasn't graduated yet, bridge, and sell where it's graduated already.
* This model's effect is cross-chain liquidity flow for the token. Price consistency is an important aspect of liquidity unification, and our chain-agnostic bonding curve model would help achieve that.
