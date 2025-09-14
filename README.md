# Command Injection — DVWA Lab

**Author:** Lokeshwar V 
**Course / Module:** ETHICAL HACKING INTERN
**Date:** 14-09-2025
---

## Overview
This repository documents a hands-on lab demonstrating **command injection** vulnerabilities using DVWA (Damn Vulnerable Web Application). The lab covers basic and blind command injection techniques, captures evidence (screenshots and timings), and provides mitigation recommendations.

> ⚠️ **Ethics & Safety:** All testing in this repository was performed only on isolated lab VMs that I own / have explicit permission to test. Do **not** run these techniques on third-party sites or production systems.

---

## Objectives
- Understand how command injection works in web applications.  
- Demonstrate basic and blind command injection in DVWA.  
- Capture evidence: screenshots, Burp Repeater captures, and timing measurements.  
- Produce a short report and mitigation recommendations.

---

## Lab Environment
- **Attacker VM:** Kali Linux — IP: `<KALI_IP>`  
- **Target VM:** DVWA — IP: `<DVWA_IP>`  
- **Tools used:** Browser (with Burp proxy), Burp Suite (Proxy & Repeater), `curl`, `nc` (netcat) — reverse shell attempted only in isolated lab if applicable.  
- **DVWA Security Levels tested:** Low, High

---

## Repository Structure
