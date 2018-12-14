# Overview - fm

TokenD is provided with a flexible and feature-rich set of tools for fees management, which allows creating custom fees imposition rules by choosing and combining the following parameters:

* Account \([types of accounts](../../user-guide/types-of-accounts/overview.md), any specific account, or all\)
* Asset \(any specific asset-backed token on the platform issued both [by admins](../system-assets-management/lifecycle-of-system-assets.md) and [by users](https://tokend.gitbook.io/product-guide/user-guide/user-issued-tokens/overview)\)
* Operation type \(withdrawal, invest, issuance, payment \(outgoing, incoming\), and order match\)
* Flat fee \(a fixed fee\)
* Percentage fee 
* Boundaries \(define the boundaries that apply the imposition of different fee-charging scenarios. **Example:** you can specify that a 2% fee will be imposed exclusively on the USD withdrawals in the range between $100 and $3000.\)

