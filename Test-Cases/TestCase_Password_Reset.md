# Test Case: Password reset with valid email

**Test Case ID:** TC_PWRESET_01  
**Module:** Password Recovery  
**Priority:** High  
**Type:** Functional

## Preconditions:
- User has a registered account
- User knows the email address

## Steps:
1. Navigate to https://example.com/login
2. Click on the “Forgot password?” link
3. Enter registered email in the “Email” field
4. Click on the “Reset password” button
5. Open the email inbox for this address
6. Open the password reset email and click the reset link
7. Enter a new valid password and confirm it
8. Click “Save” or “Change password”

## Expected Result:
Password reset email is sent.  
After following the link and setting a new password, user can log in with the new password.

## Postconditions:
User can log in with the new password. Old password is no longer valid.

## Test Data:
- Email: valid_user@example.com  
- New Password: NewStrongPassword123  

## Actual Result:
(Will be filled during real testing)

## Status:
(Pass / Fail)
