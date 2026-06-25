# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-0-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--00--00-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-0%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 3 of 61
- **Practitioner**: 14 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 5/14 lab
- **SQL injection**: 12/18 lab
- **Access control**: 0/13 lab

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
| 18  | 2026-06-25 |  Authentication vulnerabilities   |  |  | N/A |
| 19  | 2026-00-00 |     |  |  | N/A |
| 20  | 2026-00-00 |     |  |  | N/A |
| 21  | 2026-00-00 |     |  |  | N/A |
| 22  | 2026-00-00 |     |  |  | N/A |
| 23  | 2026-00-00 |     |  |  | N/A |
| 24  | 2026-00-00 |     |  |  | N/A |









