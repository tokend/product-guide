# Max price step

**Max price step** is the percent range in which the price of a trading pair will be able to fluctuate.

**Example:** If you have created the ETH/USD pair and specified the **price** of a trading pair as 250 and **max price step** as 10, then the range in which the price per 1 ETH will be able to fluctuate is +- $25 \(25 is 10 percent of 250\).

You can enable/disable this rule by selecting/clearing the **current price restriction**check box when you [create the asset pair](https://cryptofund.software/resources/product-guide/admins/internal-exchange-management/asset-pair-creation/) or [update the asset pair policies](https://cryptofund.software/resources/product-guide/admins/internal-exchange-management/update-the-asset-pair-policies/).

**Note:** the [physical price correction](https://cryptofund.software/resources/product-guide/admins/internal-exchange-management/physical-price-correction/) value is of the higher priority than the **max price step** value. This means that if the price of a trading pair is 250 and you specified the **physical price correction** value as 230, then the price won’t go lower this point even despite that **max price step** rule states that price can fluctuate +- $25.  


