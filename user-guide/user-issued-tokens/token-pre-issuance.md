# Token pre-issuance

Generally, there are two ways to pre-issue tokens.  When making a token creation request a user defines how the pre-issuance of tokens will be provided – **with** or **without additional issuance later.**

### One-time pre-issuance <a id="one-time-pre-issuance"></a>

_**Example:** a corporate user has created the token with the 1000 **max issuance amount.**_

If a user selected the **I want to make additional issuance later** check box [during the token creation](token-creation.md), then all the 1000 tokens will be pre-issued automatically after admin approved the token creation request.

### Pre-issuance by several stages <a id="pre-issuance-by-several-stages"></a>

_**Example:** a corporate user has created the token with the 1000 **max issuance amount.**_

If a user cleared the **I want to make additional issuance later** check box during the [token creation](token-creation.md), then the tokens will be pre-issued by the user manually. Manual token pre-issuance implies the following process:

Step 1. User creates the asset pre-issuance file with the help of an offline application _\(to learn more, check_ [_offline application_](../offline-application/overview.md)_\)_  
Step 2. [User uploads the pre-issuance file to the platform](pre-issuance-file-upload.md)  
Step 3. User waits for the [admin approval](../../admins/user-issued-tokens-management/review-the-token-pre-issuance-request.md) _\(the flow on the part of admin is described in_ [_user tokens management_](../../admins/user-issued-tokens-management/overview.md)_\)_

