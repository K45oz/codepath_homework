# Pen Testing Live Targets

Time spent: 10 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injection

Description:Specific URL for person blue/public/salesperson.php?id=%27%20OR%20SLEEP(5)=0--%27

<img src="SQL Injection.gif">


## Green

Vulnerability #1: Username Enumeration

Description:The CSS can tell wheter a person exist or not

<img src="Username Enumeration.gif">


## Red

Vulnerability #1:Insecure Direct Object Reference

Description:A number can swap to another salesperson

<img src="Insecure Direct Object Reference.gif">


## Notes

Describe any challenges encountered while doing the work
