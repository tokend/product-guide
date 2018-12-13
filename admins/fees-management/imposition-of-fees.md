# Imposition of fees

Only available to admins with the **fees manager** [right](../admin-account-management/rights-of-admins-on-the-platform.md).

**Example:** you need to impose a $0.5 fixed fee + 1% \(percentage\) fee on all outgoing USD payment operations performed by verified individual accounts and apply the configured rules to the operations in the range from $5 to $20. To do this, you:

Step 1. In the navigation bar, go to **Fees**  
Step 2. On the **Fee management** page, in the **Scope** box, select the scope: account type  
Step 3. In the **Type** box, select the type of operation: payment  
Step 4. In the **Direction** box, select the direction of the payment: outgoing  
Step 5. In the **Account type** box, select the type of account: general \(verified individual\)  
Step 6. In the **Asset** box, select the asset: USD  
Step 7. In the **Lower bound** box, enter the lower boundary of operation: 5  
Step 8. In the **Upper bound** box, enter the upper boundary of operation: 20  
Step 9. In the **Percent fee** box, enter the percentage fee: 1  
Step 10. In the **Fixed fee** box, enter the fixed fee: 0.5  
Step 11. In the **Fee asset** box, select the asset in which the fees will be imposed: USD \(**Note:** in the case of outgoing payments, the **fee asset** can be different from the **operation asset** \(USD, in our case\)\)  
Step 12. Click **Create**  
Step 13. Click **Submit**

As a result, you collect the specified fees from all **verified individual** accounts that perform USD payments in the range of $5-10.

**A case example**: If a user has sent a payment in the amount of $18, he/she will be charged with a $0.68 fee \($0.5 fixed fee + \($18 × 1% = $0.18\) percentage fee\). **Note**: The sender can optionally pay the recipient’s fee as well.

