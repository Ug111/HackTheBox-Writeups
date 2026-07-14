# 💃 HackTheBox — Dancing Writeup

**Machine:** Dancing
**Difficulty:** Very Easy
**Category:** SMB Exploitation
**XP Earned:** 150
**Pwn Date:** 14 July 2026

---

## 🎯 Objective
Exploit misconfigured SMB shares to retrieve the flag.

---

## 🔍 Step 1 — Reconnaissance
Ran Nmap to identify open ports and services:
```bash
nmap -sV <target_ip>
