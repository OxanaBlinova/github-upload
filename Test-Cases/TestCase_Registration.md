# Test Case: Registration with valid data

**Test Case ID:** TC_REG_01  
**Module:** Registration  
**Priority:** High  
**Type:** Functional

## Preconditions:
- User is not logged in
- Registration page is available

## Steps:
1. Navigate to https://example.com/register
2. Enter valid first name in the “First Name” field
3. Enter valid last name in the “Last Name” field
4. Enter a valid email in the “Email” field
5. Enter a valid password in the “Password” field
6. Confirm the password in the “Confirm Password” field
7. Click on the “Sign Up” button

## Expected Result:
New account is created and user is redirected to the welcome/dashboard page.  
Confirmation message is shown: “Your account has been created.”

## Postconditions:
User remains logged in as a newly registered user.

## Test Data:
- First Name: Oxana  
- Last Name: Blinova  
- Email: new_user@example.com  
- Password: StrongPassword123  

## Actual Result:
(Will be filled during real testing)

## Status:
(Pass / Fail)
