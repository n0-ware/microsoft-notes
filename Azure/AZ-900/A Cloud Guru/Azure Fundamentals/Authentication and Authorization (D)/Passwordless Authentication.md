---
tags:
topic: "auth_and_auth"
subTopic: "passwordless"
source: "guru"
family: "Azure"
imageNameKey: "Azure_passwordless"
cert: "AZ-900"
---
# Passwordless Authentication
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- Passwords can cause user frustration
- That and MFA create multiple steps for login
- User frustration is a reality 

> The objective of passwordless authentication is to increase convenience while maintaining high levels of security

- Main goal is removing passwords from system logins as the main requirement
- This replaces it with two single factor methods of authentication that are secure in their own right
	- Something you have such as a phone or key fob or other one time password device.
	- Something you know or are, such as your fingerprint or face or unlock PIN on a device that you have.
![[1_Azure_passwordless.png]]

## Methods

1. MS Authenticator Mobile App
	1. Authenticate in the app with either biometrics of the pin
2. Windows Hello
	1. Facial recognition in windows
3. FIDO2 Security Key
	1. Hardware key

## Scenario

1. M365 requires username
2. Then prompted to check authenticator app
3. Use a biometric or pin to unlock the app
4. Confirm the numerical challenge in the authenticator app



