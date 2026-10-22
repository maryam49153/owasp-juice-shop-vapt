# owasp-juice-shop-vapt
This project documents a basic, non-destructive Vulnerability Assessment and Penetration Testing (VAPT) exercise performed against OWASP Juice Shop in a local training environment.
Objectives

Understand basic web application security testing.

Test login and registration validation.

Observe password validation and logout behavior.

Check access to the administration route while logged out.

Test product-search input handling.

Document results with screenshots and recommendations.

Tools and Technologies

OWASP Juice Shop

Web Browser

Manual Security Testing

Windows Screenshot Utility

Tests Performed

Homepage and login page access

Invalid credentials and empty login fields

Email-format input test

Registration form review

Password-length validation

Password-confirmation mismatch

Security-question review

Registration and successful login

Logout behavior

Administration-route access while logged out

Normal product search

Script-like search input

Results

The recorded tests showed expected behavior for several validation and access-control checks. The script-like search input returned “No results found,” and no JavaScript alert was observed.

These observations do not prove that the application is free of vulnerabilities. Further authorized testing would be needed to evaluate session management, authorization, and input handling.

Project Files

VAPT-Report.pdf – Assessment report

screenshots/ – Evidence collected during the lab

Disclaimer

This project was conducted for educational purposes in a local training environment. Testing was limited to the stated scope and does not represent a comprehensive penetration test.

References

OWASP Juice Shop

OWASP Web Security Testing Guide

OWASP Top 10
