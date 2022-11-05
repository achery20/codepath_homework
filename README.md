# Pen Testing Live Targets

Time spent: **5** hours spent in total

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

Description: To exploit using SQL Injection, click on "find a salesperson" and pick any person on the list. Then, replace the id number of the user found in the url to a SQL code that always returns true. The message when you submit this url request will say "database query failed."

<img src="blue-vuln1.gif">


## Green

Vulnerability #1: Username Enumeration and Cross-Site Scripting

Description: To perform the Cross-Site Scripting exploit, you must go to the feedback page without logging in. Fill out the form by inputting any name, email address, and a javascript code message into the "feedback" area. Next, log into the website and click on "feedback." The javascript code will run once you click on that page. To perform Username Enumeration, you must first attempt to log into the site using an existing username with an incorrect password. The website will return the message "log 

<img src="green-vuln1.gif">


## Red

Vulnerability #1: __________________

Description:

<img src="red-vuln1.gif">


## Notes

Describe any challenges encountered while doing the work

