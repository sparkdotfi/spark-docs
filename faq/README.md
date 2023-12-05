# 🦣 FAQ

## Spark

### What is Spark?

**Spark** is on a mission to empower the DAI ecosystem. As part of the MakerDAO community, Spark builds and manages DeFi infrastructure.

### Are there any risks?

No platform can be considered entirely risk-free. The risks related to the SparkLend platform are the smart contract risk (risk of a bug within the protocol code) and liquidation risk (risk on the collateral liquidation process). Every possible step has been taken to minimise the risk as much as possible, the protocol code is public and open source and it has been audited. Additionally, you can find additional security-related information in the [security and audits](https://devs.spark.fi/security-and-audits) sections.

### Scams and fake accounts

Be careful, it is common for scammers to create social media accounts and websites that are intended to steal your funds. While the blockchain provides users with self-sovereignty, it also means that nothing can be done when a scammer steals user funds.&#x20;



Spark legitimate domains are:

* spark.fi
* sparkprotocol.io (this is the initial domain used, it currently redirects to the above)

Any subdomain based on the above domains will also be legitimate, such as docs.spark.fi



Beware of the following:

* Domains that look similar but are not **exactly** the same, it can be a single character or different top-level domain (.com, .net, .scam)
* Clickable domains on social media, these can look legitimate on the platform, such as Twitter, but once clicked the user is redirected to a different domain.
* People who contact you via social media, including Twitter, Telegram and LinkedIn claiming to be a contributor of Spark. Always verify their identity by asking on the public discord or with someone that you trust.
* Websites without https (http does not provide encryption nor verification)
* Any Spark mobile application
* Any website asking you for your seed passphrase (you should not share this with anyone)&#x20;
* Spark does not advertise on social media (e.g. tweets with "Ad" on the top right), on websites or search engines.

## SparkLend

### What is SparkLend?

SparkLend is a decentralised non-custodial liquidity market protocol where users can participate as suppliers or borrowers. Suppliers provide liquidity to the market to earn a passive income, while borrowers are able to borrow in an overcollateralised (perpetually) or undercollateralised (one-block liquidity) fashion. Please join the [SparkDAO Discord](https://discord.gg/sparkdao), the community looks forward to helping you understand and use SparkLend.

### Why SparkLend?

SparkLend has been audited and secured. The protocol is completely open source, which allows anyone to interact with a user interface client, API or directly with the smart contracts on the Ethereum network. Being open source means that you are able to build any third-party service or application to interact with the protocol and enrich your product.

### How do I interact with SparkLend?

In order to interact with SparkLend, you simply supply your preferred asset and amount. After supplying, you will earn passive income based on the market borrowing demand. Additionally, supplying assets allows you to borrow by using your supplied assets as a collateral. Any interest you earn by supplying funds helps offset the interest rate you accumulate by borrowing.

### What is the cost of interacting with SparkLend?

Interacting with the protocol requires transactions and so transaction fees for Ethereum Blockchain usage, which depend on the network status and transaction complexity.

### Where are my supplied funds stored?

Your funds are allocated in a smart contract. The code of the smart contract is public, open source, formally verified and audited by third party auditors. You can withdraw your funds from the pool on-demand or export a tokenised (aTokens) version of your lender position. spTokens can be moved and traded as any other cryptographic asset on Ethereum.

### Address Screening

**Why is my wallet blocked?** We receive blockchain intelligence provided by [TRM Labs](https://www.trmlabs.com/). TRM combines on-chain data and real-world investigations to identify financial crime and other prohibited activities. This data blocks wallets from app.spark.fi that are associated with certain legally prohibited conduct.If you believe your address has been incorrectly flagged, please contact [contact@marsfoundation.xyz](mailto:contact@marsfoundation.xyz).

**What information is shared with TRM Labs?** Your address is shared with TRM, but no metadata is tracked or shared. The request from the UI is routed to the SparkLend hosted API, which is used as a proxy endpoint, and the address is passed directly through to the TRM service. Users' IP addresses are not shared with TRM.

## sDAI

### What is sDAI? <a href="#what-is-sdai" id="what-is-sdai"></a>

Savings Dai (sDAI) is a yield bearing stablecoin, representing DAI in the Dai Savings Rate (DSR) module, which distributes revenue from the Maker protocol to DAI holders. It is an ERC-4626 representation (wrapper) of DAI in the DSR. sDAI allows users to deposit DAI to receive the yield generated by the Maker protocol while still being able to transfer, stake, lend, and use it in any way you want.“Swapping” between DAI and sDAI does not need to be done via a DEX but can be achieved by depositing and withdrawing from the DSR module.You can interact with sDAI through the frontend at [SparkLend](https://app.spark.fi/sdai/).

## SparkConduits

### What are SparkConduits?

SparkConduits are a technical component that enables Maker to provide liquidity directly to an external protocol, they are part of the wider Maker Allocation System.

## SparkDAO

### What is SparkDAO?

SparkDAO is a Maker Allocator subDAO. A decentralised, autonomous organisation that owns and manages Spark.

\
subDAOs are currently in bootstrapping phase and will be officially launched around May 2024.

