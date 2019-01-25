# Verification code

2-factor authentication is an additional layer of security on top of user name and password. When a user or admin signs in, they will be prompted for their [admin account name](./) or [user’s email](../../user-guide/user-account/) and password \(the first factor\) and a verification code \(the second factor\).

### **How to get a verification code?**

Step 1. Install an authenticator application:

1. [Google Authenticator for iOS](https://itunes.apple.com/us/app/google-authenticator/id388497605)
2. [Google Authenticator for Android](%20https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2)
3. [Microsoft Authenticator for Windows Phone](https://www.microsoft.com/en-us/store/p/microsoft-authenticator/9nblgggzmcj6?rtc=1)
4. [Extension for Google Chrome](https://chrome.google.com/webstore/detail/gauth-authenticator/ilgcnhelpchnceeipipijaljkblbcobl)
5. Another solution with the Time-based One-Time Password algorithm \(TOTP\) support

Step 2: Backup a **16-Digit Secret Key** or QR-code and put it in a safe place. If you lose a mobile phone or extension crashed you will lose access to the account. And you will need to [recover a user account](../../user-guide/user-account/account-recovery.md) or [create a new administrator account](sign-up.md).

Step 3. Add an account in an authenticator application. Scan the QR-code or manually enter the 16-Digit Secret Key and an account name.

1. Enter an **account name**. \(**Example**, _testadmin tokend.io_\)
2. Enter a **16-Digit Secret Key**. \(**Example**, _LBOC5TT22REC4YDO_\)
3. Select “**Time based**” option. \(Optionally, if this option is enabled in the authenticator app.\)

Step 4. An authenticator app will **generate a new 6-digit verification code every 30 seconds**. Enter an actual verification key in a **verification code** box on a corresponding webpage.

