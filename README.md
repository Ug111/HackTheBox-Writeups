# Hack The Box Writeups
Welcome to my Hack The Box portfolio.
This respository documents my p[ractical cybersecurity labs, focusing onenumeration, exploitation, post -exploitation, and defensive lessons learned.

## Objectives
- Develop hands-on penetration testing skills
- Improve enumeration methodolgy
- Document lessons learned
- Translate technical findings into business security insights

## Machines Completed 
| Machine | Difficulty | Skills |
|---------|------------|--------|
| Fawn    | Very Easy  | FTP    |
| Dancing | Very Easy  | SMB    | 
| Redeemer| Very Eady  | Redis  |

# HackTheBox-Writeups
Machine:Fawn
Difficulty: Very Easy
Category: FTP Exploitation
XP Earned: 150
Pwn Date: 13 July 2026

What i did:
Ran Nmap to discover open FTP port 21
Tested anonymous FTP login
Successfully authenticated and retrieved the flag

What i learned:
How misconfigured FTP servers allow anonymous access
How to enumerate files via FTP
How this connects to real SOC detection Event ID for failed/successful FTP logins
