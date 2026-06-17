# Core Feature 1
## Feature Name
Password Length Analysis
## Description
This feature checks the length of the password entered by the user.
Rules:
Less than 6 characters → Weak
6 to 10 characters → Medium
More than 10 characters → Strong
## Manual Testing
Test Case 1: Input: abc Output: Weak
Test Case 2: Input: password Output: Medium
Test Case 3: Input: Password123 Output: Strong
Test Case 4: Input: Welcome@2025 Output: Strong
Test Case 5: Input: hello12 Output: Medium
## Edge Cases
Empty Input Output: Please enter a password.
Invalid Input Type Output: Password must be a text string.
## Comment Block
This feature analyzes the password length and classifies it as weak, medium, or strong based on the number of characters entered by the user.
