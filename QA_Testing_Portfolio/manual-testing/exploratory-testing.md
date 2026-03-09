# Exploratory Testing Notes

Module tested: Login

Testing approach:
Freestyle exploration of login functionality.

Scenarios explored:

• Invalid email format  
• Empty password  
• SQL injection attempts  
• Multiple failed login attempts  

Findings:

Bug 1:
Error message not displayed when password field is empty.

Bug 2:
Login accepts email with trailing spaces.