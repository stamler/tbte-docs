# Passwordless Authentication

## About Passwordless Login

Passwords are a security issue. If somebody gets your password, they can access your accounts. MFA helps us quite a bit by ensuring that a person can't login without having something else in addition to your password. But good passwords are still hard to remember and, critically, bad actors trick us into giving away our passwords with incredible frequency. This is called phishing. Wouldn't it be great if you didn't have to use your password at all? That way, when someone sends you a suspicious email and you are asked for your password, you'll know every time that something is wrong. Great news! We can now do this now!

After setting up [MFA](https://github.com/tbt-eng/docs/blob/master/MFA.md) on your TBT Engineering acccount using the Microsoft Authenticator app, you should enable passwordless login. Passwordless login replaces the need to use a password by leveraging your existing mobile device and making both the possession of your device and the knowledge of its PIN or biometric security an integral part of the login process.

Under the passwordless scheme, in order to login to your account, a person must have your mobile device in their possession and also either know your mobile device PIN or be able to access it via biometric authentication (for example TouchID or FaceID). Using passwordless authentication is very similar to using MFA except for a key difference: after you enter your username you are not asked for a password! Instead, you are presented with a challenge in the form of a two-digit number. Your mobile device will then present you three choices of two-digit numbers. To login, you must choose the correct one. In this manner you prove that the owner of the mobile device is approving the login, completing the process.

## When you'll use a password

Once enabled, you'll only be required to use your password when logging onto your computer directly. If you use the L2TP VPN (the one that requires your username), you'll also be required to type your password. You will not use your password in a web browser.

## Setting up Passwordless

1. You must have already completed the setup of MFA using the Microsoft Authenticator app. If you haven't, follow the instructions [here](https://github.com/tbt-eng/docs/blob/master/MFA.md)

2. In the Microsoft Authenticator app on your mobile device, select the entry for TBT Engineering Ltd. by touching it.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-1.png">
</p>

3. Touch the area on the screen that says "Enable phone sign-in".

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-2.png">
</p>

4. Instructions will be provided to you within the app at this point. Follow them carefully. The first step is to register your device. Touch continue.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-3.png">
</p>

5. If you use your TBT Engineering email address with a personal Microsoft account as well, you will need to select the option for "Work or School account". Most people won't see this choice.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-4.png">
</p>

6. In most cases you'll be asked to enter your existing password prior to registration.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-5.png">
</p>

7. You can then complete the registration.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-6.png">
</p>

8. You're done! You can verify that you've completed the setup when the TBT Engineering Ltd. Entry now shows the option "Disable phone sign-in" rather than the message shown in Step 3.

<p align="center">
  <img width="600px" src="https://github.com/stamler/tbte-docs/blob/master/Passwordless-images/iOS-7.png">
</p>
