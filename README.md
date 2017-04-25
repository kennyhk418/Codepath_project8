# Project 8 - Pentesting Live Targets

Time spent: 5 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection (SQLi). We can put ' OR SLEEP(5)=0--' at the salesperson page after id = .

Vulnerability #2: Session Hijacking/Fixation


## Green

Vulnerability #1: User Enumeration. If we use a non-existing username to login, the error message will not be bold, whereas it will be bold for the span class = "failed" if the username exists.

Vulnerability #2: Cross-Site Scripting (XSS)


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR). We can access to id=10. Other websites have added in user authorization to allow access to id=10.

Vulnerability #2: Cross-Site Request Forgery (CSRF). We can make a simple copy of the form and submit to the edit user page and change the user information.


## Notes

Describe any challenges encountered while doing the work
