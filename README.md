# Project 8 - Pentesting Live Targets

Time spent: 6 hours spent in total

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

Vulnerability #1: SQL Injection (SQLI.gif)
<img src='https://github.com/okmoorejr/Week8PentensingLiveTargets/blob/master/SQLI.gif' width='' alt='SQLI gif' />

Vulnerability #2: Session Hijacking/Fixation (SessionHijackingFixation.gif)
<img src='https://github.com/okmoorejr/Week8PentensingLiveTargets/blob/master/SessionHijackingFixation.gif' width='' alt='SessionHijackingFixation gif' />


## Green

Vulnerability #1: Username Enumeration (Username Enumeration.gif)
<img src='https://github.com/okmoorejr/Week8PentensingLiveTargets/blob/master/UsernameEnumeration.gif' width='' alt='UsernameEnumeration gif' />

Vulnerability #2: Cross-Site Scripting (XSS.gif)
<img src='https://github.com/okmoorejr/Week8PentensingLiveTargets/blob/master/XSS.gif' width='' alt='XSS gif' />


## Red

Vulnerability #1: Cross-Site Request Forgery (CrossSiteRequestForgery.gif)
<img src='https://github.com/okmoorejr/Week8PentensingLiveTargets/blob/master/CrossSiteRequestForgery.gif' width='' alt='CSRF gif' />

Vulnerability #2: Insecure Direct Object Reference (InsecureDirectObjectReference.gif)
<img src='https://github.com/okmoorejr/Week8PentensingLiveTargets/blob/master/InsecureDirectObjectReference.gif' width='' alt='IDOR gif' />


## Notes

Difficulty Screencapturing. Mouse wouldn't be shown, couldn't capture while highlighting text. Hadn't used SQL Sleep command before so hadn't considered using it. Cross-Site Request Forgery also took a try or two to get it right. Used an online gif maker for the animations. Had to toggle around with Firefox and Burp after Firefox updated to get burp running properly again.
