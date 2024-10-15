---
description: Find answers to Frequently Asked Questions.
hidden: true
---

# FAQ

## Spark

### What is Spark?

**Spark** is on a mission to empower the USDS ecosystem. As part of the Sky Ecosystem, Spark builds and manages DeFi infrastructure.

Spark consists of three main product categories:

* **Savings**: Earn savings on your stablecoin holdings
* **Borrow**: The USDS centric money market protocol. Combining the best liquidity directly from Sky and vertically integrating with the best DeFi protocols.
* **Liquidity Layer:** Direct liquidity provision into DeFi markets.

## Savings

### What is Savings?

Spark enables users to easily deposit stablecoins into savings, and receive Savings USDS (sUSDS) tokens in return. The sUSDS tokens represents your share of USDS in the Sky Savings Rate. As savings accrue, sUSDS increases in value over time. The Sky Savings Rate is set by Sky Governance.&#x20;

Learn how to use Savings here:

{% content-ref url="user-guides/earning-savings/" %}
[earning-savings](user-guides/earning-savings/)
{% endcontent-ref %}



{% hint style="info" %}
**Note:** Savings USDS and the Sky Savings Rate are non-custodial and permissionless smart contracts offered by Sky, and is not issued or deployed by Spark. Spark never has custody of funds deposited into or any control of the Sky Savings Rate or sUSDS token.
{% endhint %}

### What is sUSDS? <a href="#what-is-sdai" id="what-is-sdai"></a>

Savings USDS (sUSDS) is the upgraded version of sDAI, which offers higher yield than sDAI. sUSDS is a tokenized representation of USDS deposited in the Sky Savings Rate (SSR) offered by Sky. The sUSDS token enables users to receive returns on their SSR deposits while still being able to transfer, stake, lend and use it in any way they want.

### How do I acquire sUSDS?

To acquire sUSDS and earn savings you can deposit USDS and other stablecoins using the [Spark App](user-guides/earning-savings/).

For technical documentation on the sUSDS implementation please refer to the [Developer docs](https://devs.spark.fi/savings/susds-token).

### What is the Sky Savings Rate? <a href="#what-is-dsr" id="what-is-dsr"></a>

Sky Savings Rate (SSR) is a feature of the Sky Protocol that enables any USDS holder to earn a savings rate on their USDS. The SSR is paid out in USDS.

The Sky Savings Rate is funded by the borrowing fees accrued by the Sky Protocol. You can always find the current Sky Savings Rate on the [Savings page in the Spark App](http://app.spark.fi/savings).

The Sky Savings Rate offers higher yield than the Dai Savings Rate.

The Sky Savings Rate is set by Sky Governance and is subject to change. Spark has no control over the Sky Savings Rate.

## Borrow

### What is SparkLend

SparkLend is a decentralized non-custodial liquidity market protocol that powers the **Spark Borrow** product where users can participate as lenders or borrowers. Lenders provide liquidity to the market to earn a passive income, as their assets are lent out, while borrowers are able to borrow in an overcollateralized and perpetual fashion.

Learn more about Borrow here:

{% content-ref url="user-guides/using-sparklend/" %}
[using-sparklend](user-guides/using-sparklend/)
{% endcontent-ref %}

### How do I interact with SparkLend?

Get started using SparkLend using this guide:

{% content-ref url="user-guides/using-sparklend/easy-borrow-flow.md" %}
[easy-borrow-flow.md](user-guides/using-sparklend/easy-borrow-flow.md)
{% endcontent-ref %}

### What is the cost of interacting with Borrow?

Interacting with the protocol requires transactions and so transaction fees for Ethereum Blockchain usage, which depend on the network status and transaction complexity.

### Is there a minimum or maximum deposit amount?

You can deposit any amount you want, there is no minimum or maximum limit. However, it's important to note that for low amounts it is possible that the transaction cost of the process is higher than the expected earnings. It is recommended that you consider this when depositing low amounts.

### Where are my deposited funds stored?

Funds are deposited in a non-custodial smart contract. The code of the smart contract is public, open source, formally verified and audited by third party auditors. No centralized entity can access deposited funds.

### How much will I earn?

Depositors receive continuous yield that fluctuates due to market conditions based on:

* **The interest rate payment on loans:** Depositors share the interests paid by borrowers. The higher the utilization of a reserve the higher the yield for depositors.

Each asset has its own market of supply and demand with its own APY (Annual Percentage Yield) which fluctuates over time. You can find the average annual rate over the past 30 days to evaluate the rate evolution, and you can also find more data on the reserve overview of each asset in the home section on the app.

### Can I opt-out my asset from being used as a collateral?

Yes. After depositing your assets, you are able to unselect the asset so that it will not be used as collateral. The opt-out is available in the **Deposit** section within your dashboard. Simply switch the **Collateral** toggle on the asset you would prefer to opt-out from being used as a collateral.\
\
You can withdraw your assets without opting out of using them as collateral, as long as those funds are not actively being lent out or the withdrawal would cause a liquidation on your loans.

### Why would I borrow instead of selling my assets?

By borrowing you are able to obtain liquidity without selling your assets. Users are mainly borrowing to leverage their holdings or for new investment opportunities.

### How much I can borrow?

The maximum amount you can borrow depends on the value of the collateral you have deposited and the available liquidity. For example, you cannot borrow an asset if there is not enough liquidity or if your health factor does not allow you to.

### What asset do I need to repay?

You repay your loan in the same asset you borrowed. For example, if you borrow 1000 DAI you will pay back 1000 DAI + interest accrued.

### What is the difference between predictable and variable rate?

Predictable rates act as a fixed rate in the short-term, but will change based on Sky Governance. The variable rate is the rate based on the supply and demand in SparkLend, and will constantly change.

### How much will I pay in interest?

The interest rate you pay for borrowing assets depends on the borrowing rate which is derived from the supply and demand ratio of the asset in the case of the variable rate; for predictable rate assets (DAI), the borrowing rate is defined by Sky Governance. The interest rate of a variable rate changes constantly. You can find your current borrowing rate at any time in the Borrow section of your Dashboard.

### What is the health factor?

The health factor is the ratio of your collateralization ratio (the value of your collateral vs the value of your debt) and the liquidation loan to value. The higher Health Factor value is, the safer the state of your funds are against a liquidation scenario. If the health factor goes below 1, a liquidation of your collateral deposits will be triggered.

### What happens when my health factor is reduced?

Depending on the value fluctuation of your collateral deposits, the health factor will increase or decrease. If your health factor increases, it will improve your borrow position by making the liquidation threshold more unlikely to be reached. In the case that the value of your collateral assets against the borrowed assets decreases, the health factor is reduced, causing the risk of liquidation to increase.

### When do I need to pay back the loan?

There is no fixed time period to pay back the loan. As long as your position is safe, you can borrow for an undefined period. However, as time passes, the accrued interest will grow making your health factor decrease, which might result in your deposited assets becoming more likely to be liquidated.

### How do I payback the loan?

In order to payback the loan you simply go to the Borrowings section of your dashboard and click on the repay button for the asset you borrowed and want to repay. Select the amount to pay back and confirm the transaction.

### How do I avoid liquidation?

In order to avoid the reduction of your health factor leading to liquidation, you can repay the loan or deposit more collateral assets in order to increase your health factor. Learn more about liquidations here:

{% content-ref url="user-guides/using-sparklend/liquidations.md" %}
[liquidations.md](user-guides/using-sparklend/liquidations.md)
{% endcontent-ref %}

## Spark Liquidity Layer

### What is the Spark Liquidity Layer?

The Spark Liquidity Layer consists of technical components that enable Spark to provide stablecoin liquidity directly to external protocols such as Aave or Morpho.

## Spark Sky Star

### What is Spark Sky Star? <a href="#what-is-spark-subdao" id="what-is-spark-subdao"></a>

Spark is a Sky Star, a part of the Sky Ecosystem. [You can read more about the Sky Star here.](https://forum.makerdao.com/t/sky-has-arrived/24959#p-98600-spark-the-first-sky-star-14)

Sky Stars are currently in bootstrapping phase and will be officially launched in late 2024.

Spark.fi is a front-end that gives access to the products offered by the Spark Sky Star.

