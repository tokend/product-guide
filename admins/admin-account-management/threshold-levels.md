# Threshold levels

Each operation on the platform \([set fees](../fees-management/imposition-of-fees.md), [review KYC requests](../kyc-management/review-the-kyc-request.md), [manage assets](../user-issued-tokens-management/overview.md), etc\) has its threshold level. Threshold level defines how much admins weight is required to fulfill a certain operation. On the platform, there are 3 threshold levels [that can be specified](threshold-levels-management.md): low, medium, and high. _To get the full list of operation requirements, check your **signing rule list.**_

**Case example:** Let’s suppose you’ve specified the **high** level as **20**. In such case, in order to have accomplished an operation with the threshold level of **20**, there should either be one admin with the minimal weight of 20, or two admins with the minimal weights of 10, or any other number of admins the total signature weight of which would be **20** _\(for example: 7, 7, 1, 5_\)_._

Correct adjustment of this mechanism in combination with a sufficient number of administrators \(with the different scope of responsibilities\) directly contributes to creating a sustainable tokenization ecosystem with objective decision-making. _**Note:** the objectivity of decisions is a very important parameter which directly influences the robustness of the entire system._  


