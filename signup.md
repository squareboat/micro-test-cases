# Signup

#### While adding a Signup feature in your app or website, please check the following cases:

1. Required fields must have red asterisk sign
1. Placeholder text in all fields must be clearly mentioned
1. While signup button is responding, a loader should clearly show
1. It should not be possible to click on Signup twice quickly
1. Fields must have proper validation (10 digit phone number, email format, min character length etc.)
1. TnC checkbox label must be clickable and take the user to the TnC page in a new tab
1. Signup should trigger a email/mobile/OTP verification message (As per designs)
1. Post signup, users should be automatically logged in and should not be asked to login again.
1. Welcome email should be sent to the user immediately after signup
1. Welcome/verification email should not be flagged as spam.
1. If the form reloads after a server error of any kind, field values should be retained
1. Hitting the “Tab” key on the keyboard should properly navigate all the fields in the correct order.
1. Users should not be able to sign up with a duplicate email id/phone number.
1. Insensitive fields should be autofilled.
1. All fields should be cleaned up when the page refreshes.
1. All server side validations should be implemented.
1. Spell of fields should be correct.
1. Unique usernames should be suggested by the system.
1. [Optional] For sensitive signup pages, Captcha implementation is mandatory.
1. Passwords should be stored in the database in hashed bcrypt format only.
1. All text fields must have a maximum input limit
1. Blank spaces should not be considered as a valid input
1. Validation rules on the frontend and backend should match.
1. Field specific cases:
1. DOB cannot be a date of the future
1. DOB should enforce some minimum age (ex. a 1 year old baby cannot sign up)
