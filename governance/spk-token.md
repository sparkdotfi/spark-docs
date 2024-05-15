# SPK Token & Airdrop FAQ

{% hint style="warning" %}
The SPK token is not released yet, please beware of scammers.
{% endhint %}

{% hint style="info" %}
SPK airdrop is ongoing, see current stats at [BlockAnalitica's website](https://spark.blockanalitica.com/v1/ethereum/airdrop/).
{% endhint %}

## What is SPK?

SPK is the governance token of the Spark Maker SubDAO. [Learn more about this here.](https://forum.makerdao.com/t/makerdao-endgame-launch-season/23857)

## Has SPK been launched yet?

The SPK token has not yet been launched. Please beware of scammers and false SPK tokens.

When the token is launched, announcements will be made from the official X accounts of [MakerDAO (@makerdao)](http://x.com/MakerDAO) and [Spark (@sparkdotfi)](https://x.com/sparkdotfi) once the launch date arrives. No official launch date has been determined yet.

## What is the SPK pre-farming airdrop?

Spark is running a pre-farming airdrop campaign based on usage of its lending platform. Users of the platform will receive an airdrop, depending on how much and how long they have used the platform during specific periods, also known as seasons. Users will continue to be able to farm the SPK token after it has launched. See further details on [how to qualify](spk-token.md#how-do-i-qualify-for-the-spk-airdrop) for the airdrop, and the [different seasons](spk-token.md#season-1-aug-20-2023-may-20-2024) below.

## How many SPK tokens are distributed?

### Season 1 (Aug 20, 2023 - May 20, 2024)

In season 1 30M SPK will be allocated to users who qualify for the airdrop.

* 80 % (24M) is allocated to users borrowing DAI
* 20 % (6M) is allocated to users supplying ETH.

Season 1 is a pre-farming period of 9 months active from Aug 20 2023 14:25 UTC (Ethereum block 17956537) to May 20 2024 14:25 UTC.

### Season 2 (May 20, 2024 - SubDAO Launch TBD)

In season 2 3.33M SPK will be rewarded per month to users who qualify for the airdrop.

* 80 % is allocated to users borrowing DAI
* 20 % is allocated to users supplying ETH.

Season 2 is an additional pre-farming period, which runs until the Spark SubDAO launches as part of Maker Endgame launch season.

## How do I qualify for the SPK airdrop?

Users of [Spark](http://app.spark.fi) who borrow DAI or supply ETH qualify for the SPK airdrop. You can see the formula for calculating the SPK amount in the [following section](spk-token.md#how-many-spk-tokens-are-distributed).

**Note**: Attempting to game the airdrop by lending sDAI while borrowing DAI or lending and borrowing ETH on the same account will forfeit your inclusion in the airdrop.

For clarity here are some **valid examples:**

* Supply wstETH, Borrow DAI - DAI amount is included ✅
* Supply rETH, Borrow DAI - DAI amount is included ✅
* Supply wstETH, Borrow DAI, Swap DAI for sDAI - DAI amount is included ✅
* Supply ETH, Borrow DAI - Both ETH and DAI amounts are included in the airdrop ✅
* Supply rETH, Supply ETH, Borrow DAI - Both ETH and DAI amounts are included in the airdrop ✅
* Supply GNO, Borrow DAI - DAI amount is included ✅
* Supply ETH - ETH amount is included ✅
* Supply ETH, Borrow wstETH - ETH amount is included ✅

**Invalid examples:**

* Supply sDAI, Borrow DAI - FORFEIT AIRDROP ❌
* Supply ETH, Borrow ETH - FORFEIT AIRDROP ❌
* Supply wstETH, Borrow DAI, Deposit sDAI as Collateral - FORFEIT AIRDROP ❌

**Note:** Borrowing DAI and depositing it into sDAI using the Cash and Savings feature of Spark is accepted and does not count against the airdrop. It is only penalized if you supply sDAI as collateral to borrow against.

## How much SPK will I earn?

The SPK Airdrop is calculated using the following formula:

`Airdrop = 80% * DAI Borrows in USD + 20% * ETH Supplies in USD`

Please note all supplies and borrows are denominated in USD and will use the on-chain oracle price at that block to determine the conversion.

To calculate the final airdrop, the formula will be computed for every account on each block within the valid time range, and the Airdrop value will be summed over every included block to produce a final number for each account. The relative weight of this number will then be converted to the allocated SPK token supply. See the [seasons sections](spk-token.md#season-1-aug-20-2023-may-20-2024) for the different time frames.

### Anti-cheat formula

As noted in the “[How do I qualify for the airdrop?](spk-token.md#how-do-i-qualify-for-the-spk-airdrop)” section, there are certain actions that count against the airdrop. The full airdrop formula including the anti-cheat measure is as follows:

Full anti-cheat formula (don’t worry about this if you are using the system legitimately:

`Airdrop = 80% * (DAI Borrows - sDAI Supplies * sDAI Liquidation Threshold) + 20% * (ETH Supplies - ETH Borrows / ETH Liquidation Threshold)`

## Which geographies qualify for the pre-farming airdrop?

The pre-farming airdrop is not available to users with IPs flagged by the [Location Resilience in MIP108: Accessibility Scope Bounded Mutable Alignment Artifact.](https://mips.makerdao.com/mips/details/MIP108#8-location-resilience)

## Which networks qualify for the airdrop?

You are only able to earn SPK tokens using Spark lending markets on Ethereum mainnet. Spark lending markets on other networks do not qualify for the SPK airdrop.

## Where can I see accrued SPK tokens?

On the [Spark App](https://app.spark.fi/), once you have connected your wallet, you are able to see your accumulated SPK tokens in the top right corner.

You can also find your accumulated SPK tokens by navigating to [https://spark.blockanalitica.com/v1/ethereum/airdrop/](https://spark.blockanalitica.com/v1/ethereum/airdrop/) and searching for your wallet address.

## When is SPK released?

The SPK token will be released when the Spark SubDAO launches as part of the Maker Endgame launch season. The exact date has not yet been determined.

## How do I claim SPK?

Details on how to claim SPK will be announced on the official X accounts of [MakerDAO (@makerdao)](http://x.com/MakerDAO) and [Spark (@sparkdotfi)](https://x.com/sparkdotfi) once the launch date arrives.

\
