# Multi-factor Authentication

## About MFA

TBT Engineering uses multi-factor authentication (MFA) to secure our accounts. This means when you login you use a password plus a second factor. The most secure second factor is your mobile device configured through an app. This is the method we use at our company.

In order to login to your account, a person must have both your password and your mobile device under this scheme. Once your mobile device has been configured as a second factor, you will receive a notification that you are required to approve upon signing in. If you get a notification but have not signed in, deny the request and reset your password because it means someone has discovered your password.

If your mobile device does not have an Internet connection, you can still sign in using MFA. The Microsoft Authenticator generates a one-time code every 30 seconds regardless of Internet connection status. When you receive the MFA challenge upon sign in, you can click "Sign in another way" and you will be offered the opportunity to select the "Use a verification code from my mobile app". You can use the one-time code from the Microsoft Authenticator app to login.

## Setting up MFA

1. If you haven't already installed the Microsoft Authenticator app on your mobile device, Go [here](https://www.microsoft.com/en-ca/account/authenticator) and install it.

2. If you already have the Microsoft Authenticator app, make sure that any previous setups for TBT Engineering are deleted.

3. From an internet-connected computer, visit [My Security Info](https://aka.ms/mysecurityinfo) and sign in with the username and password provided by IT. Do not do this from the mobile device you're setting up with Microsoft Authenticator.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/browser-1.png">
</p>

4. After you've signed in, you will receive a message indicating that more information is required. This is the where the the MFA setup workflow begins.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/browser-2.png">
</p>

5. You will be prompted to setup the Microsoft Authenticator App. Since you've already downloaded the app, you can just click "Next".

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/browser-3.png">
</p>

6. The browser on the computer will now tell you to open the Microsoft Authenticator app and add
a new Work or School account.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/browser-4.png">
</p>

7. In the App on your mobile device, touch the "+" button on the top right of the screen.

<p align="center">
  <img width="400px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/iOS-1.png">
</p>

8. Touch "Work or school account". If prompted, click "OK" to Allow camera access.

<p align="center">
  <img width="400px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/iOS-2.png">
  <img width="400px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/iOS-3.png">
</p>

9. Back on the computer, click "Next". A QR code is displayed in the browser. This will be used to pair the App on your mobile device to your account.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/browser-5.png">
</p>

10. From your mobile device, scan the QR code on your computer screen.

<p align="center">
  <img width="400px" src="https://github.com/stamler/tbte-docs/blob/master/MFA-images/iOS-4.png">
</p>

11. Once you've successfully scanned the QR code the setup is complete. The MFA setup workflow will then ask you to do a test. Follow the instructions on your computer and approve the notification on your phone to finish up.