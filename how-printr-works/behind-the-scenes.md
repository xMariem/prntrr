# Behind the Scenes

We've abstracted the complexities of creating, managing, and trading tokens across 70+ exchanges. It’s a lot of heavy lifting, and you must be deep in the trenches if you care about how it all works.

Underneath the hood, we’re automating and orchestrating interoperability, smart contracts, DeFi, and trenches magic to provide the fantastic experience you experience on the app.

### When you Create Tokens On Printr

We've carefully designed the token creation process to be fast, permissionless, and simple, while offering powerful customization options for more advanced operations.

{% stepper %}
{% step %}

### Input the token's details

You can specify your token details through the Launch UI including the chains you want to deploy on and set other configurations.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2F40uKa1glym0qdkFYCRdG%2FFrame%201597880474.png?alt=media&#x26;token=3ebe293a-69e8-4fff-bc8a-27a2aabb8867" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}

### Advanced Customizations

Currently, you can only configure the initial buy. In the future, we'll enable more functionalities like staking, vested tokens, customizing bonding curve sizes etc.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FFixLkJ4HkfnQJBdoCA8Z%2FFrame%201597880475.png?alt=media&#x26;token=b99df69a-8fdc-4b50-8cc3-7ef2d4aa7c3a" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}

### We deploy the token across the chains.

We manage asset transfers via our smart contract using **Axelar's Interchain Token Service (ITS)**. We will soon integrate LayerZero's OFTs for enhanced cross-chain functionality.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FEFfkzaGo9R6sR6p0Ilba%2FFrame%201597880472.png?alt=media&#x26;token=040a9b49-1285-4bc1-9891-493c06b8eb9a" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}

### Graduating to DEXs

Once your token reaches the market cap threshold on a bonding curve, it will automatically "graduate" and the liquidity will be migrated to our partnered DEXs.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FYL4a8SEprd4YXWhuFcRf%2FFrame%201597880473.png?alt=media&#x26;token=87c5b04e-f6a4-4952-9455-2ead91f6f7ae" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

Upon graduation, our contract automatically revokes token ownership and securely locks the LP position permanently on-chain, preventing any removal of liquidity.

### When you Trade Tokens on Printr

Trade across over 70 supported blockchains directly within the app using our integrated DEX. Once your tokens graduate, you can effortlessly trade them on Printr.

{% stepper %}
{% step %}

### Trading on Bonding Curve

When you buy or sell tokens on a bonding curve, the price adjusts predictably based on the curve’s predefined parameters.&#x20;

Participating in bonding curves from any chain using any asset is possible. Printr’s infrastructure ensures that your funds are routed seamlessly across chains.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2F6UF5YA4JmbNUbPnfsn2R%2FFrame%201597880471.png?alt=media&#x26;token=ec423e2b-29a5-40f3-af1c-d41bf4375111" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}

### Trade any token anywhere.

We've integrated **Squid Router** to enable cross-chain swaps in a single transaction. Whether you’re on Solana, Base, or any other supported chain, you can buy or sell tokens from any other chain without manually bridging assets.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FnFruwnkSmD6FwJ5itgsC%2FFrame%201597880472.png?alt=media&#x26;token=1d1fcee3-8668-4388-b8d5-f85acdd4a6bb" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}

### Trading on External DEXs

You can also trade graduated tokens on DEXs in the token's home chain. We recommend using Printr, particularly, so you get the best rates and access to deep liquidity.

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FxutS16DXWJUpkP1K7DOE%2FFrame%201597880473.png?alt=media&#x26;token=f6243a3e-849e-4aac-9937-effaa863cb0d" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

Integrating cross-chain trading into the Printr app transforms it into the ultimate meme platform, offering all the features every trader desires: the best rates and deep liquidity.
