# Asset pair creation

Only available to admins with the **asset manager** [rights](../admin-account-management/rights-of-admins-on-the-platform.md).

**Example:** you want to add the EUR/USD trading pair on the internal exchange and set the 1.16 price on it \(it means that the buyer would need 1.16 USD to buy 1 EUR\). To do this, you:

Step 1. In the navigation bar, go to **System assets**  
Step 2. Go to the **Asset pair index** tab  
Step 3. Click **Create pair** and you will be redirected to the **Create asset pair** page  
Step 4. In the **Base** box, type the base asset: EUR  
Step 5. In the **Quote** box, type the quote asset: USD  
Step 6. In the **Price** box, type the price of an asset pair: 1.16 \(this means that the buyer will need 1.16 USD to buy 1 EUR\)  
Step 7. In the **Physical price correction** box, enter the minimum value for which the pair can be traded: 1.10 \(to learn more, check [physical price correction](physical-price-correction.md)\)  
Step 8. In the **Max price step** box, enter the percent range in which the price of a trading pair can possibly fluctuate: 10 \(to learn more, check [max price step](max-price-step.md)\)  
Step 9. Select/clear the **Is tradable** checkbox \(you add/remove the trading pair on/from the internal exchange by enabling/disabling this property. To learn more, check [asset pair policies](asset-pair-policies.md).\)  
Step 10. Select/clear the **Physical price restriction** check box \(select to enable the **physical price correction** rule that you’ve specified above. If you clear the check box, the rule won’t be applied.\)  
Step 11. Select/clear the **Current price restriction** check box \(select to enable the **max price step** rule that you’ve specified above. If you clear the check box, the rule won’t be applied.\)  
Step 12. Click **Create**  
Step 13. Click **Confirm**

Let’s repeat the rules that we have specified for the EUR/USD trading pair:

* The price of the trading pair is 1.16 \(this is the default amount of USD a buyer needs to buy 1 EUR\)
* The price can only fluctuate in the range of 10% of the default price of a trading pair – 1.16 \(we’ve specified this rule in the **max price step** field and enabled it by selecting the **current price restriction** check box\)
* A user won’t be able to buy 1 EUR for less than 1.10 USD \(we’ve specified this rule in the **physical price correction** field and enabled it by selecting the **physical price restriction** check box\)

**Note**: the physical and the current price restriction rules can secure the internal exchange from the pump and dump schemes. It is highly recommended to enable these rules especially if you have just launched the internal exchange and it is temporary illiquid.  


