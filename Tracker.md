# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-152-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--09--04-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-55.7%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 45 of 61
- **Practitioner**: 101 of 174
- **Expert**: 6 of 39

## Categories Covered

- **Authentication vulnerabilities**: 12/14 lab
- **SQL injection**: 18/18 lab 
- **Access control**: 13/14 lab
- **Path traversal**: 6/6 lab
- **Command injunction**: 5/5 lab
- **File upload vulnerability**: 13/14 lab
- **OAuth authentication**: 5/6 lab
- **Cross-site scripting**: 13/14 lab
- **Race condition**: 13/14 lab
- **Clickjacking**:4/6
- **API testing**:4/6
- **Information disclosure**:5/6
- **Business logic vulnerability**:11/12
- **CSRF**:10/10
- **SSTI**:5/6
- **HTTP Host header attacks**:3/6


  
## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic          | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-15 |  SQL Injuction   |  SQL injection UNION attack, retrieving multiple values in a single column  | Practitioners |https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-retrieving-multiple-values-within-a-single-column/sql-injection/union-attacks/lab-retrieve-multiple-values-in-single-column#
| 2  | 2026-06-15 |  SQL Injuction   | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | Apprentice | https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-retrieving-hidden-data/sql-injection/lab-retrieve-hidden-data#|
| 3  | 2026-06-16 | SQL Injuction    | SQL injection vulnerability allowing login bypass  |  Apperentice|https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-subverting-application-logic/sql-injection/lab-login-bypass#  |
| 4  | 2026-06-16 |SQL Injuction     | SQL injection UNION attack, determining the number of columns returned by the query | Practitioners  | https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-determining-the-number-of-columns-required/sql-injection/union-attacks/lab-determine-number-of-columns# |
| 5  | 2026-06-17 |  SQL Injunction  |Blind SQL injection with conditional responses  | Practitioner| https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-exploiting-blind-sql-injection-by-triggering-conditional-responses/sql-injection/blind/lab-conditional-responses# |
| 6  | 2026-06-17 |  SQL Injunction  | SQL injection attack, listing the database contents on non-Oracle databases |  Practitioner|https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-examining-the-database-in-sql-injection-attacks/sql-injection/examining-the-database/lab-listing-database-contents-non-oracle#  |
| 7  | 2026-06-18 | SQL Injuction    | SQL injection attack, querying the database type and version on MySQL and Microsoft |  Practitioner| https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-examining-the-database-in-sql-injection-attacks/sql-injection/examining-the-database/lab-querying-database-version-mysql-microsoft# |
| 8  | 2026-06-18 | SQL Injuctiion    |SQL injection UNION attack, retrieving data from other tables  |Practitioner  | https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-using-a-sql-injection-union-attack-to-retrieve-interesting-data/sql-injection/union-attacks/lab-retrieve-data-from-other-tables# |
| 9  | 2026-06-19 |  SQL Injunction   | Blind SQL injection with conditional errors | Practitioner| https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-error-based-sql-injection/sql-injection/blind/lab-conditional-errors# |
| 10  | 2026-06-19 | SQL Injunction    |Visible error-based SQL injection  | Practitioner | https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-error-based-sql-injection/sql-injection/blind/lab-sql-injection-visible-error-based# |
| 11  | 2026-06-20 | SQL Injuction    | Blind SQL injection with time delays and information retrieval |Practitioner  | https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-exploiting-blind-sql-injection-by-triggering-time-delays/sql-injection/blind/lab-time-delays-info-retrieval# |
| 12  | 2026-06-20 | SQL Injuction    | SQL injection UNION attack, finding a column containing text  | Practitioner | https://portswigger.net/web-security/learning-paths/sql-injection/sql-injection-finding-columns-with-a-useful-data-type/sql-injection/union-attacks/lab-find-column-containing-text# |
| 13  | 2026-06-23 |  Authentication vulnerabilities   | Username enumeration via different responses | Apprentice | https://portswigger.net/web-security/learning-paths/authentication-vulnerabilities/password-based-vulnerabilities/authentication/password-based/lab-username-enumeration-via-different-responses# |
| 14  | 2026-06-23 |  Authentication vulnerabilities | Username enumeration via subtly different responses | Practitioner | https://portswigger.net/web-security/learning-paths/authentication-vulnerabilities/password-based-vulnerabilities/authentication/password-based/lab-username-enumeration-via-subtly-different-responses# |
| 15  | 2026-06-25 | Authentication vulnerabilities  | Username enumeration via response timing | Practitioner | N/A |
| 16  | 2026-06-25 |  Authentication vulnerabilities   | Broken brute-force protection, IP block | Practitioner | N/A |
| 17  | 2026-06-25 |  Authentication vulnerabilities   | Username enumeration via account lock | Practitioner | N/A |
| 18  | 2026-06-25 |  Authentication vulnerabilities   | 2FA simple bypass | Practitioner | N/A |
| 19  | 2026-06-26 |   Authentication vulnerabilities  | 2FA broken logic | Practitioner | N/A |
| 20  | 2026-06-26 |  Authentication vulnerabilities   | Brute-forcing a stay-logged-in cookie | Practitioner | N/A |
| 21  | 2026-06-26 | Authentication vulnerabilities    | Offline password cracking | Practitioner | N/A |
| 22  | 2026-06-27 |  Authentication vulnerabilities  | Password reset broken logic | Apprentice | N/A |
| 23  | 2026-06-27 |  Authentication vulnerabilities   | Password reset poisoning via middleware  | Practitioner | N/A |
| 24  | 2026-06-30 |  Command injunction  | OS command injection, simple case | Apprentice | N/A |
| 25  | 2026-06-30 |  Command injunction  | Blind OS command injection with time delays | Practitioner | N/A |
| 26  | 2026-07-01 |  Command injunction  | Blind OS command injection with output redirection | Practitioner | N/A |
| 27  | 2026-07-01 |  Command injunction  | Blind OS command injection with out-of-band interaction | Practitioner | N/A |
| 28  | 2026-07-01 |  Command injunction  | Blind OS command injection with out-of-band data exfiltration| Practitioner | N/A |
| 29  | 2026-07-02 |  Path traversal  |  File path traversal, simple case | Apprentice | N/A |
| 30  | 2026-07-02 |  Path traversal | File path traversal, traversal sequences blocked with absolute path bypass | Practitoner | N/A |
| 31  | 2026-07-02 |  Path traversal  | File path traversal, traversal sequences stripped non-recursively | Practitioner | N/A |
| 32  | 2026-07-03 | Path traversal  | File path traversal, traversal sequences stripped with superfluous URL-decode | Practitioner | N/A |
| 33  | 2026-07-03 |  Path traversal  | File path traversal, validation of start of path | Practitioner | N/A |
| 34  | 2026-07-03 |  Path traversal  | File path traversal, validation of file extension with null byte bypass | Practitioner | N/A |
| 35  | 2026-07-04 |  SQL Injuction  | SQL injection attack, listing the database contents on Oracle | Practitioner | N/A |
| 36  | 2026-07-04 |  SQL Injuction  | SQL injection attack, querying the database type and version on Oracle | Practitioner | N/A |
| 37  | 2026-07-04 |  SQL Injuction  | Blind SQL injection with time delays | Practitioner | N/A |
| 38  | 2026-07-07 |  Access control | User role controlled by request parameter  | Apprentice | N/A |
| 39  | 2026-07-07 |  Access control | Unprotected admin functionality with unpredictable URL | Apprentice | N/A |
| 40  | 2026-07-07 | Access control | Unprotected admin functionality | Apprentice | N/A |
| 41  | 2026-07-08 | Access control | User role can be modified in user profile | Apprentice | N/A |
| 42  | 2026-07-08 |  Access control | User ID controlled by request parameter | Apprentice  | N/A |
| 43  | 2026-07-08 | Access control | User ID controlled by request parameter, with unpredictable user IDs | Apprentice | N/A |
| 44  | 2026-07-09 |  Access control  |  URL-based access control can be circumvented | Practitioner | N/A |
| 45  | 2026-07-09 |  Access control  | Method-based access control can be circumvented | Practitioner | N/A |
| 46  | 2026-07-10 | Access control | User ID controlled by request parameter with data leakage in redirect | Apprentice | N/A |
| 47  | 2026-07-10 | Access control  | User ID controlled by request parameter with password disclosure | Apprentice | N/A |
| 48  | 2026-07-10 | Access control  | Insecure direct object references | Apprentice | N/A |
| 49  | 2026-07-10 | Access control  | Multi-step process with no access control on one step | Practitioner | N/A |
| 50  | 2026-07-10 | Access control  | Referer-based access control | Practitioner | N/A |
| 51  | 2026-07-14 | SQL Injunction  | Blind SQL injection with out-of-band interaction | Practitioner | N/A |
| 52  | 2026-07-14 | SQL Injunction  | Blind SQL injection with out-of-band data exfiltration | Practitioner | N/A |
| 53  | 2026-07-14 | SQL Injunction  | SQL injection with filter bypass via XML encoding | Practitioner | N/A |
| 54  | 2026-07-14 | File upload vulnerability  | Remote code execution via web shell upload | Apprentice | N/A |
| 55  | 2026-07-14 |  File upload vulnerability | Web shell upload via Content-Type restriction bypass | Apprentice | N/A |
| 56  | 2026-07-14 | File upload vulnerability  | Web shell upload via path traversal | Practitioner | N/A |
| 57  | 2026-07-14 |  File upload vulnerability | Web shell upload via extension blacklist bypass | Practitioner | N/A |
| 58  | 2026-07-14 | File upload vulnerability  | Web shell upload via obfuscated file extension | Practitioner | N/A |
| 59  | 2026-07-14 | File upload vulnerability  | Remote code execution via polyglot web shell upload | Practitioner | N/A |
| 60  | 2026-07-15 | File upload vulnerability | Web shell upload via race condition | Expert | N/A |
| 61  | 2026-07-15 | Authentication vulnerabilities  | Password brute-force via password change | Practitoner | N/A |
| 62  | 2026-07-15 | Authentication vulnerabilities  |2FA bypass using a brute-force attack | Expert | N/A |
| 63  | 2026-07-16 | OAuth authentication | Authentication bypass via OAuth implicit flow | Apprentice | N/A |
| 64  | 2026-07-16 | OAuth authentication  | SSRF via OpenID dynamic client registration | Practitioner | N/A |
| 65  | 2026-07-16 |  OAuth authentication | Forced OAuth profile linking | Practitioner | N/A |
| 66  | 2026-07-16 |  OAuth authentication | OAuth account hijacking via redirect_uri | Practitioner | N/A |
| 67  | 2026-07-16 | OAuth authentication  | Stealing OAuth access tokens via an open redirect | Practitioner | N/A |
| 68  | 2026-07-17 | Cross-site scripting  | Reflected XSS into HTML context with nothing encoded | APPRENTICE | N/A |
| 69  | 2026-07-17 | Cross-site scripting  | Stored XSS into HTML context with nothing encoded | APPRENTICE | N/A |
| 70  | 2026-07-17 | Cross-site scripting  |  DOM XSS in document.write sink using source location.search | APPRENTICE | N/A |
| 71  | 2026-07-17 | Cross-site scripting  | DOM XSS in innerHTML sink using source location.search | APPRENTICE | N/A |
| 72  | 2026-07-17 | Cross-site scripting  | DOM XSS in jQuery anchor href attribute sink using location.search source | APPRENTICE | N/A |
| 73  | 2026-07-19 | Cross-site scripting  | DOM XSS in jQuery selector sink using a hashchange event | APPRENTICE | N/A |
| 74  | 2026-07-19 |  Cross-site scripting | Reflected XSS into attribute with angle brackets HTML-encoded | APPRENTICE | N/A |
| 75  | 2026-07-19 |  Cross-site scripting | Stored XSS into anchor href attribute with double quotes HTML-encoded | APPRENTICE | N/A |
| 76  | 2026-07-19 |  Cross-site scripting | Reflected XSS into a JavaScript string with angle brackets HTML encoded | APPRENTICE | N/A |
| 77  | 2026-07-19 |  Cross-site scripting | DOM XSS in document.write sink using source location.search inside a select element | Practitioner | N/A |
| 78  | 2026-07-21 | Race condition  |  Multi-endpoint race conditions | Practitioner | N/A |
| 79  | 2026-07-21 | Race condition  |Limit overrun race conditions | apprentice  | N/A |
| 80  | 2026-07-22 | Race condition  | Bypassing rate limits via race conditions | Practitioner | N/A |
| 81  | 2026-07-22 | Race condition  | Single-endpoint race conditions | Practitioner | N/A |
| 82  | 2026-07-22 | Race condition  | Exploiting time-sensitive vulnerabilities | Practitioner | N/A |
| 83  | 2026-07-23 | Cross-site scripting  |DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded | Practitioner | N/A |
| 84  | 2026-07-23 | Cross-site scripting  | Reflected DOM XSS | Practitioner | N/A |
| 85  | 2026-07-23 | Cross-site scripting  | Stored DOM XSS | Practitioner | N/A |
| 86  | 2026-07-24 | Cross-site scripting | Reflected XSS into HTML context with most tags and attributes blocked | Practitioner  | N/A |
| 87  | 2026-07-24 | Cross-site scripting | Reflected XSS into HTML context with all tags blocked except custom ones | Practitioner | N/A |
| 88  | 2026-07-24 | Cross-site scripting | Reflected XSS with some SVG markup allowed | Practitioner | N/A |
| 89  | 2026-07-26 |  Cross-site scripting | Reflected XSS in canonical link tag | Practitioner | N/A |
| 90  | 2026-07-26 |  Cross-site scripting | Reflected XSS into a JavaScript string with single quote and backslash escaped | Practitioner | N/A |
| 91  | 2026-07-26 |  Cross-site scripting | Reflected XSS into a JavaScript string with angle brackets and double quotes HTML-encoded and single quotes escaped | Practitioner | N/A |
| 92  | 2026-07-28 | SSRF  | Basic SSRF against the local server | Apprentice | N/A |
| 93  | 2026-07-28 |  SSRF | Basic SSRF against another back-end system | Apprentice | N/A |
| 94  | 2026-07-28 | SSRF  | SSRF with blacklist-based input filter | Practitioner | N/A |
| 95  | 2026-07-28 | SSRF  | SSRF with filter bypass via open redirection vulnerability | Practitioner | N/A |
| 96  | 2026-07-29 | SSRF | Blind SSRF with out-of-band detection | Practitioner | N/A |
| 97  | 2026-07-29 | SSRF  | Blind SSRF with Shellshock exploitation | Expert | N/A |
| 98  | 2026-07-30 | Cross-site scripting  | Stored XSS into onclick event with angle brackets and double quotes HTML-encoded and single quotes and backslash escaped | Practitioner | N/A |
| 99  | 2026-07-30 | Cross-site scripting  | Reflected XSS into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped | Practitioner | N/A |
| 100  | 2026-07-30 | Cross-site scripting  | Exploiting cross-site scripting to steal cookies | Practitioner | N/A |
| 101  | 2026-07-31 | Cross-site scripting  | Exploiting cross-site scripting to capture passwords | Practitioner | N/A |
| 102  | 2026-07-31 | Cross-site scripting  | Exploiting XSS to bypass CSRF defenses | Practitioner | N/A |
| 103  | 2026-07-31 | Cross-site scripting  | Reflected XSS protected by very strict CSP, with dangling markup attack | Practitioner | N/A |
| 104  | 2026-08-01 | SSRF | Blind SSRF with Shellshock exploitation | Expert | N/A |
| 105  | 2026-08-01 |  Cross-site scripting | Reflected XSS with AngularJS sandbox escape without strings | Expert | N/A |
| 106  | 2026-08-04 | Cross-site scripting  | Reflected XSS protected by CSP, with CSP bypass | Expert | N/A |
| 107  | 2026-08-04 | Clickjackjng  | Basic clickjacking with CSRF token protection | Apprentice | N/A |
| 108  | 2026-08-04 | Clickjacking  | Clickjacking with form input data prefilled from a URL parameter | Apprentice | N/A |
| 109  | 2026-08-05 |  API testing | Exploiting an API endpoint using documentation | Apprentice | N/A |
| 110  | 2026-08-05 | API testing  | Exploiting server-side parameter pollution in a query string
 | Practitioner | N/A |
| 111  | 2026-08-07 | API testing  | Finding and exploiting an unused API endpoint | Practitioner | N/A |
| 112  | 2026-08-07 | API testing  | Exploiting a mass assignment vulnerability | Practitioner| N/A |
| 113  | 2026-08-07 | Clickjacking  |Clickjacking with a frame buster script  |Apprentice  | N/A |
| 114  | 2026-08-07 | Clickjacking  | Exploiting clickjacking vulnerability to trigger DOM-based XSS | Practitioner | N/A |
| 115  | 2026-08-08 | Clickjacking  | Multistep clickjacking | Practitioner | N/A |
| 116  | 2026-08-08 | Information disclosure | Information disclosure in error messages | Apprentice | N/A |
| 117  | 2026-08-11 | Information disclosure | Information disclosure on debug page | Apprentice | N/A |
| 118  | 2026-08-11 | Information disclosure  | Source code disclosure via backup files  | Apprentice | N/A |
| 119  | 2026-08-11 | Information disclosure  | Authentication bypass via information disclosure  | Apprentice | N/A |
| 120  | 2026-08-12 | Business logic vulnerability  | Excessive trust in client-side controls | Apprentice | N/A |
| 121  | 2026-08-12 | Business logic vulnerability  | High-level logic vulnerability | Apprentice | N/A |
| 122  | 2026-08-12 | Business logic vulnerability  | Inconsistent security controls | Apprentice | N/A |
| 123  | 2026-08-14 | Business logic vulnerability  | Flawed enforcement of business rules | Apprentice | N/A |
| 124  | 2026-08-14 | Business logic vulnerability  | Low-level logic flaw | Practitioner | N/A |
| 125  | 2026-08-14 | Business logic vulnerability  | Inconsistent handling of exceptional input | Practitioner | N/A |
| 126  | 2026-08-14 | Business logic vulnerability  | Weak isolation on dual-use endpoint | Practitioner | N/A |
| 127  | 2026-08-15 | Business logic vulnerability  | Insufficient workflow validation | Practitioner | N/A |
| 128  | 2026-08-15 | Business logic vulnerability  | Authentication bypass via flawed state machine | Practitioner  | N/A |
| 129  | 2026-08-15 | Business logic vulnerability  | Infinite money logic flaw | Practitioner | N/A |
| 130  | 2026-08-15 |  Business logic vulnerability | Authentication bypass via encryption oracle
 | Practitioner | N/A |
| 131  | 2026-08-25 | CSRF | CSRF vulnerability with no defenses | Apprentice | N/A |
| 132  | 2026-08-25 | CSRF  | CSRF where token validation depends on request method | Practitioner | N/A |
| 133  | 2026-08-25| CSRF  | CSRF where token validation depends on token being present| Practitioner | N/A |
| 134  | 2026-08-27 | CSRF  | CSRF where token is not tied to user session | Practitioner | N/A |
| 135  | 2026-08-27 | CSRF  | CSRF where token is tied to non-session cookie | Practitioner | N/A |
| 136  | 2026-08-27 | CSRF  | CSRF where token is duplicated in cookie | Practitioner | N/A |
| 137  | 2026-08-27 | CSRF  | SameSite Lax bypass via method override | Practitioner | N/A |
| 138  | 2026-08-27 | CSRF  | SameSite Strict bypass via client-side redirect | Practitioner | N/A |
| 139  | 2026-08-28 | CSRF  | SameSite Strict bypass via sibling domain | Practitioner | N/A |
| 140  | 2026-08-28 | CSRF  | CSRF where Referer validation depends on header being present | Practitioner | N/A |
| 141  | 2026-08-28 | CSRF  | CSRF with broken Referer validation | Practitioner | N/A |
| 142  | 2026-09-01 | SSTI  | Basic server-side template injection  | Practitioner | N/A |
| 143  | 2026-09-01 | SSTI  | Basic server-side template injection (code context) | Practitioner  | N/A |
| 144  | 2026-09-01 | SSTI  | Server-side template injection using documentation | Practitioner | N/A |
| 145  | 2026-09-02 | SSTI  | Server-side template injection in an unknown language with a documented exploit | Practitioner | N/A |
| 146  | 2026-09-02 | SSTI  | Server-side template injection with information disclosure via user-supplied objects | Practitioner | N/A |
| 147  | 2026-09-03 | HTTP Host header attacks | Basic password reset poisoning | Apprentice | N/A |
| 148  | 2026-09-03 | HTTP Host header attacks  | Host header authentication bypass | Apprentice | N/A |
| 149  | 2026-09-03 |  HTTP Host header attacks | Web cache poisoning via ambiguous requests | Practitioner | N/A |
| 150  | 2026-09-04 | HTTP Host header attacks | Routing-based SSRF | Practitioner | N/A |
| 151  | 2026-09-04 | HTTP Host header attacks  | SSRF via flawed request parsing  | Practitioner | N/A |
| 152  | 2026-09-04 | HTTP Host header attacks  | Host validation bypass via connection state attack | Practitioner | N/A |
| 100  | 2026-08-01 |   | |  | N/A |
| 100  | 2026-08-01 |   | |  | N/A |
| 100  | 2026-08-01 |   | |  | N/A |
| 100  | 2026-08-01 |   | |  | N/A |

