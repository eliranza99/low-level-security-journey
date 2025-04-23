
# 🛡️ 6-Month Low-Level Security Study Plan

This is a structured 6-month self-study plan focusing on low-level bug bounty, binary exploitation, reverse engineering, and Linux-based security research.

---

## 📅 Overview

Each week includes:
- **📘 Learning:** Curated resources (TryHackMe, YouTube, Docs)
- **🛠️ Practice:** Hands-on scripting, reversing, exploitation
- **🧾 Summary:** Documented insights and results

---

## 📆 Monthly Breakdown

### 🧩 Month 1: Python for Low-Level Work

| Week | Topic                        | Practice                                                             |
|------|------------------------------|----------------------------------------------------------------------|
| 1    | Reading/Writing Binary Files | Read first 64 bytes of ELF, print hex + ASCII, save to file         |
| 2    | Struct and Memory Formats    | Unpack 16 bytes from ELF, print in decimal/hex                      |
| 3    | Sockets and Binary Protocols | Build client to send struct-packed data and log response            |
| 4    | pwntools Basics              | Send 40 bytes padding + 0xdeadbeef to local process (GDB testing)   |

### 🧩 Month 2: Cryptography, Hashing & Digital Signatures

| Week | Topic                        | Practice                                                             |
|------|------------------------------|----------------------------------------------------------------------|
| 5    | Hashing & Encoding           | Hash file with hashlib, compare values                              |
| 6    | Symmetric Encryption         | Encrypt/decrypt text + files using AES (CBC, ECB)                   |
| 7    | Digital Signatures           | Sign file with private key, verify with public key in Python        |
| 8    | Ghidra Introduction          | Reverse binary, find password check, patch                          |

### 🧩 Month 3: Stack Overflow Exploitation

| Week | Topic                        | Practice                                                             |
|------|------------------------------|----------------------------------------------------------------------|
| 9    | GDB Basics & Stack Analysis  | Inspect parameters, modify values                                   |
| 10   | Stack Overflow 1 (Protostar) | Exploit Stack0–Stack2, find offset to return address                |
| 11   | Stack Overflow 2 (Protostar) | Inject shellcode, use nop sled if needed                            |
| 12   | Protections: ASLR + DEP      | Analyze ASLR effect, test shellcode with/without protections        |

### 🧩 Month 4: Heap, Format Strings & Low-Level Tools

| Week | Topic                        | Practice                                                             |
|------|------------------------------|----------------------------------------------------------------------|
| 13   | Heap Overflow                | Exploit Heap0–Heap2, observe memory layout                           |
| 14   | Format String Attacks        | Exploit to leak memory using printf and format string tricks        |
| 15   | IDA Free & AIDA Usage        | Reverse small binary, map control flow                              |
| 16   | Linux Permissions & Internals| List setuid binaries, test privilege escalation                     |

### 🧩 Month 5: Exploit Mitigations & Bypasses

| Week | Topic                        | Practice                                                             |
|------|------------------------------|----------------------------------------------------------------------|
| 17   | Stack Canaries               | Detect canaries, crash binary with/without                          |
| 18   | NX / DEP & Return-to-libc    | Build ret2libc payload with pwntools                                |
| 19   | PIE + ASLR Bypass            | Leak address, compute base, hijack control flow                     |
| 20   | Full Exploit Chain           | Solve protected binary with full chain (CTF-style)                  |

### 🧩 Month 6: Final Projects, Portfolio & Bug Bounty

| Week | Topic                        | Practice                                                             |
|------|------------------------------|----------------------------------------------------------------------|
| 21   | CrackMe + Writeup            | Solve and document reverse challenge                                |
| 22   | Exploit + Automation         | Automate exploit chain (offset, leak, shell)                        |
| 23   | GitHub + Portfolio           | Document everything, organize weekly folders                        |
| 24   | Bug Bounty Prep              | Submit binary report or apply to internship                         |

---

## ✅ Goal

Build a strong, practical understanding of Linux binary exploitation and prepare for bug bounty programs or low-level security internships.

