---
description: Learn how to use the Easy Borrow Flow to borrow Dai.
---

# Borrowing Dai

On the Borrow page, you can borrow Dai, by depositing crypto assets as collateral. If you wish to borrow other assets than Dai, navigate to the “Dashboard” page and follow the [deposit assets](deposit-assets.md) and [borrowing assets](borrow-assets.md) steps instead.

1.  Navigate to the "Borrow" page (which is also the landing page).\


    <figure><img src="../../.gitbook/assets/landing (1).png" alt=""><figcaption><p>The Borrow Page</p></figcaption></figure>


2.  Under “Deposit required” you can select the crypto asset in the dropdown menu you wish to deposit as collateral for the loan.\


    <figure><img src="../../.gitbook/assets/borrow-1-col (1).png" alt=""><figcaption><p>Easy Borrow Flow for Dai</p></figcaption></figure>


3. In the input bar on the left you specify the amount of collateral you wish to deposit, denominated in the asset. The dollar value is displayed below.\

4.  Above in the “Add more +” you can add more crypto assets to be used as collateral, which will generate another deposit bar, where you can select the asset and amount.\


    <figure><img src="../../.gitbook/assets/easy-borrow-2-col-3.png" alt=""><figcaption><p>Depositing multiple collateral assets</p></figcaption></figure>


5. On the right side under “Borrow”, you specify the Dai amount you wish to borrow.\

6.  Below you are able to see the simulated state of the borrow position based on the current price of the collateral assets and the Dai borrow amount. It displays:

    * **Loan to Value (LTV):** The percentage value of the borrow amount in USD in respect to the collateral amount in USD.
    * **The LTV slider:** Shows the current LTV percentage and its associated risk level ranging from Conservative to Moderate to Aggressive. You can drag the slider to adjust the borrow amount to specify an LTV percentage, which will adjust the Dai borrow amount above accordingly.
    * **Liquidation Indicator**: The LTV slider also shows the LTV at which the position can be liquidated. The different collateral assets have a different liquidation LTV. Creating a position with multiple collateral assets will use an aggregate liquidation LTV based on the amount of each collateral.
    * **Max LTV:** The maximum allowed percentage value of the borrow amount in USD in respect to the collateral amount in USD.
    * **Borrow rate:** The annual percentage rate (APR) for borrowing Dai. For Dai specifically, this rate is set by Maker Governance.

    **Note:** Crypto assets are volatile so even conservative borrow positions should be monitored on an ongoing basis to prevent unwanted liquidations.\

7. Once the parameters for the borrow position has been set, you click “Borrow”.\

8.  This will showcase the Health Factor, the liquidation price and the current collateral pricing for the position.\


    <figure><img src="../../.gitbook/assets/health-factor.png" alt=""><figcaption><p>The Health Factor Overview</p></figcaption></figure>

    * The **Health Factor** is a measure of how close the position is to liquidation based on the current LTV. A Health Factor **below 1** means the position can be liquidated. Users are responsible for keeping a Health Factor above 1, in order to avoid liquidation. The LTV of the position can change over time if the underlying collateral changes in value, and as debt accrues due to interest rates.
    * **Current Price** shows the current market price of the collateral asset.
    * If the price of the collateral asset reaches the **Liquidation Price**, the position can be liquidated.

    **Note:** If you are using more than one collateral type, the current price and liquidation price information is not displayed.\

9.  The **“Actions”** section below shows the transactions necessary to create the borrow position. You must click the buttons to sign each transactions with the connected wallet.\


    <figure><img src="../../.gitbook/assets/actions-borrow-1-col.png" alt=""><figcaption><p>Actions Window</p></figcaption></figure>

    * **Token Permit/Approval:** You must approve the deposit of the collateral token.
    * **Deposit:** You deposit the collateral tokens into the borrow position.
    * **Borrow:** You borrow the specified amount of Dai.\

10. Once every step is done, you will have received the borrowed Dai in your wallet, and a confirmation and overview of the actions. You can click on “View in dashboard” to view your new position.\


    <figure><img src="../../.gitbook/assets/finished-borrow.png" alt=""><figcaption><p>Confirmation Window</p></figcaption></figure>
