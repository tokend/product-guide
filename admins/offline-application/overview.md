# Overview

Offline application is an indispensable tool for token pre-issuance used by both admins and [corporate users](../../user-guide/types-of-accounts/corporate-account.md).

In the context of admins, it is essential as an extra safety precaution.

**Example:** one admin is responsible for the operation with an offline application \([create token pre-issuance files](pre-issuance-file-generation.md), for example\), the other – for [uploading this files](../system-assets-management/system-asset-pre-issuance.md) to the platform. In this way, the risk of unauthorized token issuance on the platform is diversified due to the correct allocation of admin duties.

### How to use an offline application

It’s an application an admin opens on their computer. The operation with an offline application is as follows:

Step 1. Run the offline application software  
Step 2. [Log in to the offline application](log-in-to-the-offline-application.md)  
Step 3. Carry out all the required operations  
Step 4. Log out

### Basic features

An offline application includes four basic features:

* [Generate a pre-issuance file ](pre-issuance-file-generation.md)\(this file contains a transaction for token pre-issuance. An admin will later upload this file to the platform to actually pre-issue the tokens.\)
* [View the existing pre-issuance files data](pre-issuance-file-review.md)
* [Generate a change-asset-issuer file](../system-assets-management/change-asset-issuer.md) \(this operation is essential if the previous admin responsible for the creation of pre-issuance files – is no longer trusted due to any reason and you have to prevent him/her from being able to create the pre-issuance files\)
* [Generate a keyfile](keyfile-generation.md) \(this file contains a **seed** that you will use to log in to the offline application and sign the transactions\)

