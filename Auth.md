## Sign up

The user should be able to sign up with providing the following data:
|Data | Description |
| ------ | ------ |
| Full name | Mandatory, char 64, otherwise error "The full name should be less then 64 characters"|
| Email |The email should be register insensitive|
||Mandatory field|
||It should be unique. If the user provided already used email the system should not send verification link to the email| 
||It should have email format, otherwise error "Please use email format for the filed|
|Password | Mandatory field|
||The password should be more than 8, otherwise the error "Please provide password that contains 8 symbols or more"|
||The user should be able to view/hide the provided password|
|Privacy Policy and Tems of Use|The user must confirm Privacy Policy and Terms of Use. The system should open them as a separate page|

The system should verify the provided data as soon as the user confirms the registration. As soon as the system confirms the provided data the system should sent verification link to the email AND show message "The verification link has been sent to provied address. Please follow it to confirm your email and start your servers tracking.The link should be valid (AND-logic):
- 24 h
- one-click
- new link sending (see Sign In description)
If the user follows invalid link the system should show error "It seems the lins has been expired. Please sign up once more or try to log in with your credential if you've already followed this link"

If the user has not confirmed email within 24h the system should:
- delete user account
- allow to user email for registration once more

The user should be able to sign up with Google SSO.
**TBD** The system, should allow to use one option from sign up: basic sign up via email or sign up via Google SSO, otherwise the error "The user with provided email already exists"


## Sign in
The user should be able to log in with providing:
- email
- password

The user should be able to view/hide password.
The system should verify the correctness of the data:
- if the email has not been confirmed the system should show error "It seems your account has not been confirms yet. Please confirm it to log in." The user should be able to inititate new link sending. As soon as the system sends the link the system should:
-- make the previous link inactive
-- send new link
- if the data is incorrect the system should show error "Please review the provided data"
- if the data is correct the system should allow acces to the system

The user should be able to view/hide password.

## Restore password
The user should be able to restore password by providing email. 
As soon as the user confirmas the provided email the system should verify if there is user with such email in the system AND show message "We've sent restore password link to the provided email. Please follow it to provide new one":
- if the user with provided email existis in the system the system should send EMAL TBD
- if there is no the user with provided email within the system the system should not sent email

The link rules see above within Sign Up
