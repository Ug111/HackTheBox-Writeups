# 🐾 HackTheBox — Fawn Writeup

**Machine:** Fawn
**Difficulty:** Very Easy
**Category:** FTP Exploitation
**XP Earned:** 150
**Pwn Date:** 13 July 2026

---

## 🎯 Objective
Exploit a misconfigured FTP server to retrieve the flag.

---

## 🔍 Step 1 — Reconnaissance
Ran Nmap service scan to identify open ports:
```bash
nmap -sV 192.168.56.101
Result: Port 21 (FTP -vsFTPd 3.0.5) and Port (SSH) discovered.
