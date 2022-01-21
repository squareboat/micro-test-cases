#Forgot Password

#### While adding a "Forgot Password?" feature in your app or website, please check the following cases:

1. Text should be “Forgot password?” and not “Forget password”
1. Password validation rules applied on signup should also apply during password reset
1. Forgot password link should expire after 24 hours.
1. It should not be possible for me to reset another user’s password by passing any kind of wrong values in the URL.
1. Users must be asked to login again after password reset.
1. [Optional] All previously logged in sessions of the user must expire at the time of password reset.
1. Setting up the Similar password should not be allowed in the financial/banking systems.
1. Requesting a forgotten password link multiple times should block the user's attempts for the next 30 minutes.
1. Updating the password from multiple systems at the same time by using the same link should be handled.
1. After updating the password, the link should not work to reset the password.
1. Forget password link should be sent for verified email/phone number only.
1. Password reset links should not be flagged as spam.
1. On page and server side validation should be implemented for forgetting and reset password pages.
1. After restoring the password site should be navigated to the login page.
1. After resetting the password via the forgotten password link, the user should not be able to sign-in to the system with the old password.
1. Password reset/forgot history logs should be maintained in database/admin.
