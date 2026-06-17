# Core Feature 3
## Feature Name
Password Strength Scoring and Suggestions
## Description
This feature combines password length analysis and password complexity evaluation to calculate the overall password strength score.

Strength Levels:
 •Weak Password
 •Medium Password
 •Strong Password
Suggestions are provided to help users improve weak passwords.
# End-to-End Testing
## Test Case 1
Input: abc
Length Analysis: Weak
Complexity Analysis: Weak
Final Score: Weak
Suggestion: Increase password length and add numbers, uppercase letters, and special characters.
## Test Case 2
Input: Password
Length Analysis: Medium
Complexity Analysis: Medium
Final Score: Medium
Suggestion: Add numbers and special characters.
## Test Case 3
Input: Password123
Length Analysis: Strong
Complexity Analysis: Strong
Final Score: Strong
Suggestion: No improvement needed.
## Test Case 4
Input: Welcome@2025
Length Analysis: Strong
Complexity Analysis: Strong
Final Score: Strong
Suggestion: No improvement needed.
## Test Case 5
Input: 123456
Length Analysis: Medium
Complexity Analysis: Weak
Final Score: Weak
Suggestion: Add uppercase letters, lowercase letters, and special characters.
## Sample Output
Password: Welcome@2025
Length Status: Strong
Complexity Status: Strong
Overall Strength: Strong Password
Suggestion: No improvement needed.
## Debugging Logs
Print statements can be used to display:
 •Password Length
 •Character Type Counts
 •Complexity Result
 •Final Strength Score
These logs help identify errors during development and testing.
