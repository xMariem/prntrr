# The Printr Stack

Printr is primitively a token launchpad with interoperability at the epicenter. Unlike other traditional chain-centric models, **we’re putting tokens at the center of the experience** through secure and battle-tested infrastructure and tooling that hide cross-chain complexity.

**The Printr stack includes contracts and functionality for token creation and trading.**

<figure><img src="https://3159715523-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FBqgUMNkX5OgdF7BaqREa%2Fuploads%2FCuxJhtOz5KtxLPEZ7WZj%2FPrintr%20docs%20visual%201_3.21.png?alt=media&#x26;token=567a3e29-f864-42d5-a2a6-23cef9cfe4d4" alt=""><figcaption><p>The Printr Architecture</p></figcaption></figure>

### Printr's Modular Contracts

Printr is built on a modular smart contract system designed for efficient token creation, trading, and liquidity management. The core **Printr contract** is divided into specialized modules for storage, bonding curve logic, trade execution, administration, and cross-chain interoperability.

* The **Treasury Contract** securely holds all protocol funds and manages fees.
* The **CreatorNFT module** allows the token creator to receive different fees.
* The **Liquidity Module** connects with decentralized exchanges to create pools and deploy liquidity efficiently based on price ranges. Each integrated AMM on Printr has its own liquidity module.
* The **Printr Curve** module creates token curves with virtual reserves and supports cross-chain deployments.
* **Printr Trade** handles buy/sell operations on the curve, applying fees routed to the Treasury.
* The Token Factory deploys tokens with unique, deterministic addresses and enables token deployment on every chain, even where curve was not created.

These components make Printr a comprehensive cross-chain token infrastructure and liquidity operations solution.

{% hint style="success" %}
Printr utilizes [GoPlus lockers](https://lock.gopluslabs.io/) to lock in liquidity permanently after graduation while routing LP fees to the Treasury Contract.
{% endhint %}

### Printr's Axelar Integration

Printr has native contracts on each chain for creating tokens across specified chains.  When a creator creates a token, Printr's contract executes the action on the specified chains and claims token ownership.

Printr uses a virtual reserve to **set an initial price,** preventing price manipulation from an early large buy. Creators can buy an initial allocation but cannot mint additional tokens to dump on others.

The bonding process begins independently on the specified chains without price interoperability mechanisms. After the token has graduated across chains, Axelar unifies with the Axelar Interchain Token Service (ITS) for 1:1 fungibility.&#x20;

ITS preserves native token qualities while allowing you to manage token features and supply easily. The great part is that they'd have the same token address.

Learn more about the [chain agnostic bonding curve](https://printr.gitbook.io/printr-docs/how-printr-works/the-bonding-curve) and how Printr handles interoperability and bridging.

{% hint style="warning" %}
LayerZero OFTs will soon be integrated to further enhance Printr's cross-chain capabilities,
{% endhint %}

### Printr's Squid Integration

We have integrated SquidRouter for cross-chain bridging and swapping from the Printr app.&#x20;

Squid uses **intent-based routing to allow** users to specify their desired outcome, with the system handling the complexities. It aggregates liquidity by routing trades to the most efficient liquidity pools across chains.

When a token has graduated, it is automatically available on the ['Swap'](https://app.squidrouter.com/) modal at the best rates across chains.

These are just a chip off the iceberg that makes the Printr protocol you use and enjoy. The system allows tokens to launch independently on different chains, activating interoperability mechanisms after tokens reach maturity ("graduation").
