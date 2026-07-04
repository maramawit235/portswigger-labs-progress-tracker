# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-34-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--02-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-12.4%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 7 of 61
- **Practitioner**: 27 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 9/14 lab
- **SQL injection**: 14/18 lab
- **Path traversal**: 6/15 lab
- **OS command injection**: 5/5 lab

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

| No | Date       | Topic                         | Lab Title                                                                     | Difficulty   | Writeup Link |
|---|------------|-------------------------------|-------------------------------------------------------------------------------|--------------|--------------|
| 1  | 2026-06-16 | SQL injection                 | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | Apprentice   | N/A          |
| 2  | 2026-06-16 | SQL injection                 | SQL injection vulnerability allowing login bypass                             | Apprentice   | N/A          |
| 3  | 2026-06-20 | SQL injection                 | SQL injection attack, querying the database type and version on Oracle         | Practitioner | N/A          |
| 4  | 2026-06-20 | SQL injection                 | SQL injection attack, querying the database type and version on MySQL and Microsoft | Practitioner | N/A          |
| 5  | 2026-06-20 | SQL injection                 | SQL injection attack, listing the database contents on non-Oracle databases   | Practitioner | N/A          |
| 6  | 2026-06-20 | SQL injection                 | SQL injection attack, listing the database contents on Oracle                 | Practitioner | N/A          |
| 7  | 2026-06-20 | SQL injection                 | SQL injection UNION attack, determining the number of columns returned by the query | Practitioner | N/A          |
| 8  | 2026-06-20 | SQL injection                 | SQL injection UNION attack, finding a column containing text                 | Practitioner | N/A          |
| 9  | 2026-06-20 | SQL injection                 | SQL injection UNION attack, retrieving data from other tables                 | Practitioner | N/A          |
| 10 | 2026-06-20 | SQL injection                 | SQL injection UNION attack, retrieving multiple values in a single column     | Practitioner | N/A          |
| 11 | 2026-06-20 | SQL injection                 | Blind SQL injection with conditional responses                                | Practitioner | N/A          |
| 12 | 2026-06-20 | SQL injection                 | Blind SQL injection with conditional errors                                   | Practitioner | N/A          |
| 13 | 2026-06-21 | SQL injection                 | Visible error-based SQL injection                                             | Practitioner | N/A          |
| 14 | 2026-06-21 | SQL injection                 | Blind SQL injection with time delays                                          | Practitioner | N/A          |
| 15 | 2026-06-25 | Authentication vulnerabilities | Username enumeration via different responses                                  | Apprentice   | N/A          |
| 16 | 2026-06-25 | Authentication vulnerabilities | 2FA simple bypass                                                             | Apprentice   | N/A          |
| 17 | 2026-06-25 | Authentication vulnerabilities | Password reset broken logic                                                  | Apprentice   | N/A          |
| 18 | 2026-06-25 | Authentication vulnerabilities | Username enumeration via subtly different responses                           | Practitioner | N/A          |
| 19 | 2026-06-25 | Authentication vulnerabilities | Username enumeration via response timing                                      | Practitioner | N/A          |
| 20 | 2026-06-28 | Authentication vulnerabilities | Broken brute-force protection, IP block                                       | Practitioner | N/A          |
| 21 | 2026-06-28 | Authentication vulnerabilities | Username enumeration via account lock                                         | Practitioner | N/A          |
| 22 | 2026-06-28 | Authentication vulnerabilities | 2FA broken logic                                                              | Practitioner | N/A          |
| 23 | 2026-06-28 | Authentication vulnerabilities | Brute-forcing a stay-logged-in cookie                                         | Practitioner | N/A          |
| 24 | 2026-07-01 | Path traversal                | File path traversal, simple case                                              | Apprentice   | N/A          |
| 25 | 2026-07-01 | Path traversal                | File path traversal, traversal sequences stripped non-recursively             | Practitioner | N/A          |
| 26 | 2026-07-01 | Path traversal                | File path traversal, traversal sequences stripped recursively                 | Practitioner | N/A          |
| 27 | 2026-07-02 | Path traversal                | File path traversal, traversal sequences blocked with absolute path bypass    | Practitioner | N/A          |
| 28 | 2026-07-02 | Path traversal                | File path traversal, traversal sequences stripped Superfluously (URL-decoded) | Practitioner | N/A          |
| 29 | 2026-07-02 | Path traversal                | File path traversal, validation of file extension bypass with null byte        | Practitioner | N/A          |
| 30 | 2026-07-02 | OS command injection          | OS command injection, simple case                                             | Apprentice   | N/A          |
| 31 | 2026-07-02 | OS command injection          | Blind OS command injection with time delays                                    | Practitioner | N/A          |
| 32 | 2026-07-02 | OS command injection          | Blind OS command injection with output redirection                            | Practitioner | N/A          |
| 33 | 2026-07-02 | OS command injection          | Blind OS command injection with out-of-band interaction                        | Practitioner | N/A          |
| 34 | 2026-07-02 | OS command injection          | Blind OS command injection with out-of-band data exfiltration                  | Practitioner | N/A          |
