# Test Suite: User Registration - Password Validation

**Feature:** Sign Up Page
**Module:** Authentication


---

## TC-001: Positive Test - Valid Password Requirements
**Description:** Verify that the system accepts a password that meets the minimum length (8) and includes at least one number.

**Steps:**
1. Navigate to the Sign Up page.
2. Enter a valid email address.
3. Enter 'Example1' in the Password field.
4. Click the "Sign Up" button.

**Expected Result:** - The system should accept the input.
- User should be redirected to the "Registration Successful" page or see a success alert.


---

## TC-002: Negative Test - Missing Numeric Character.
**Description:** Verify that the system rejects a password that is 8 characters long but contains no numbers.

**Steps:**
1. Navigate to the Sign Up page.
2. Enter a valid email address.
3. Enter `myExample` in the Password field.
4. Click the "Sign Up" button

**Expected Result:** - The system should reject the input.
- An error message should appear: "Password must contain at least one number."
- User should remain on the Sign Up page.
