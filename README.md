# SA VPS Exposure CTI Assessment

## External Cyber Threat Intelligence Risk Assessment

**Analyst:** Neo NL  
**Role:** Cyber Threat Intelligence Analyst (Portfolio Project)  
**Assessment Date:** 17 April 2026  
**Report Type:** External Risk Assessment  
**Classification:** Public Portfolio Version (Redacted)

---

# Project Overview

This repository contains a Cyber Threat Intelligence (CTI) assessment analysing an externally exposed South African VPS environment.

The objective of this assessment was to demonstrate a professional CTI workflow using publicly available intelligence sources to identify:

- Internet-facing services
- Potential attack surface
- Vulnerability exposure
- Threat intelligence indicators
- Security risks
- Recommended remediation actions

All information has been redacted before publication to protect privacy and follow responsible disclosure practices.

---

# Assessment Scope

## Environment Assessed

**Target Type:**

South African VPS / Cloud Hosting Infrastructure

**Assessment Approach:**

Passive OSINT (Open Source Intelligence)

**No active testing performed.**

This assessment did not include:

- Exploitation
- Authentication attempts
- Password attacks
- Vulnerability scanning
- System access

The assessment was limited to publicly available information.

---

# Tools Used

## Intelligence Collection

### Shodan

Used for:

- Internet-facing service discovery
- Open port identification
- Banner information
- Vulnerability tags

---

### IPinfo

Used for:

- IP enrichment
- Geographic information
- ASN information
- Hosting provider context

---

### VirusTotal

Used for:

- Reputation checking
- Malware intelligence review
- Security vendor analysis

---

### abuse.ch ThreatFox

Used for:

- Threat intelligence checking
- Abuse indicator review

---

# Frameworks Used

## MITRE ATT&CK

Techniques referenced:

| Technique | Description |
|---|---|
| T1133 | External Remote Services |
| T1190 | Exploit Public-Facing Application |
| T1110.001 | Password Guessing |

---

# Executive Summary

An external assessment identified an internet-accessible Remote Desktop Protocol (RDP) service associated with a South African VPS environment.

The service was reviewed for:

- Exposure risks
- Vulnerability intelligence
- Threat reputation
- Attack possibilities

The assessment identified risk associated with:

- Public RDP exposure
- Remote access availability
- Legacy vulnerability concerns

---

# Key Finding

## Internet Exposed Remote Desktop Service

A publicly accessible Microsoft Remote Desktop Protocol (RDP) service was identified.

### Service Details

| Category | Information |
|---|---|
| Service | Remote Desktop Protocol |
| Port | TCP/3389 |
| Platform | Microsoft Windows Server |
| Location | South Africa |
| Risk Rating | High |

---

# Vulnerability Assessment

## CVE-2019-0708 (BlueKeep)

**Severity:** Critical

**CVSS Score:** 9.8

BlueKeep is a Remote Desktop Protocol vulnerability affecting vulnerable Windows systems.

Potential impact includes:

- Remote code execution
- System compromise
- Malware propagation
- Unauthorised access risk

---

# Threat Intelligence Review

## VirusTotal Analysis

Result:

