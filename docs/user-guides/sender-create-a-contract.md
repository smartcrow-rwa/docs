---
sidebar_position: 2
---

# Sender - Create a Contract

1. Make sure you've followed the steps in [Requirements](./requirements).

2. Open the [mainnet](https://smartcrow.co/) or [testnet](https://smartcrow.xyz/) website. Make sure your wallet is **connected to the right network**

3. Click on **Create Contract**.

4. Enter your wallet address from Metamask and paste it on Sender's wallet address. Similary, paste your Receiver's wallet address below.

5. Enter the formatted Address of the Real estate and click on the Google API's pop up to make sure it is available. 

6. Click on **Check Address**. It will show the if the APN is available. 

7. You should be able to click on **New Contract**, leading to a new page with a form. If it doesn't allow it, there must be an existing contract for Sender->Receiver->PropertyAddress combination active. You can check [existing](./sender-check-existing-contract) contract for further options in such case.

8. Select the token you want to setup for the Bonus and the amount.

9. **Start By** date and **Sold By** date is the time period for your Receiver to Sell the real estate within the timeframe. For example, lets assume that we want the house to be sold within a month starting from 01/10/2023, we can set the date as 10/01/2023 and 11/01/2023.

10. **Contract Cancellation Lockout** refers to the lockout period. Sometimes the Real Estate API doesn't record the sales date in time, which could be updated within 15-45 days depending on the place. For this reason, we have a lockout period which will disallow the Sender to withdraw funds if the sales conditions aren't met for either 30 or 60 days.

11. **Add Sales Price and Condition** will let you add condition based on the Sales Price of the house. For example, if we want the house to be sold **at or above** $500000, we can enable this condition and set the price. You can explore other conditions as well.

12. Now you can enter the email addresses and check the data and click on **Create Contract**.

13. If you have set up any other tokens that MATIC, you will get **2-3 metamask pop-ups**. One for **allowing the token usage** for your wallet, another for **allowing token to the SmartCrow** Contract and the last one for **creating the contract**.  

14. Your contract is now created, you can now check it on [existing](./sender-check-existing-contract.md) contract.