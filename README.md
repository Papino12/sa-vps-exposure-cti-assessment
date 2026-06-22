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

0 / 91 Security Vendors Flagged

Assessment:

No malicious reputation was identified during the review period.

Important:

A clean reputation does not mean a system is secure.

Exposure and vulnerability risks still require remediation.

---

# Findings Summary

## Finding 1

### Public RDP Exposure

Risk:

High

Reason:

Internet-facing remote administration services increase attack surface.

Recommendation:

Remove direct public exposure and require secure access methods.

---

## Finding 2

### Remote Access Hardening Issue

Risk:

Medium / High

Potential concerns:

- Weak access controls
- Default configurations
- External attack attempts

Recommendation:

Implement:

- MFA
- VPN access
- Strong authentication controls

---

## Finding 3

### Vulnerability Management Gap

Risk:

High

Issue:

Legacy vulnerabilities can remain exploitable if systems are not patched.

Recommendation:

Maintain:

- Patch management
- Continuous monitoring
- External exposure reviews

---

# Evidence

Screenshots included in this repository are:

- Redacted
- Privacy protected
- Prepared for public release

Sensitive information removed:

- IP addresses
- Hostnames
- Organisation names
- Identifying details

Evidence sources:

- Shodan
- IPinfo
- VirusTotal
- abuse.ch

---

# Risk Assessment

## Overall Risk Level

# HIGH

Reasons:

- Internet exposure
- Remote access service visibility
- Vulnerability history
- Increased attack surface

---

# Recommendations

## Immediate Actions

1. Remove RDP exposure from the public internet

2. Restrict remote access through:

- VPN
- Jump host
- Secure gateway

3. Apply security updates

---

## Short-Term Improvements

Implement:

- Multi-factor authentication
- Strong password policies
- Account monitoring
- Security logging

---

## Long-Term Improvements

Establish:

- Continuous vulnerability management
- External attack surface monitoring
- Threat intelligence monitoring
- Security review processes

---

# Responsible Disclosure Statement

This project follows responsible cybersecurity research principles.

The assessment was performed using publicly available intelligence only.

No systems were:

- Accessed
- Exploited
- Modified
- Disrupted

Sensitive information was removed before publication.

---

# Repository Contents

Result:

SA-VPS-Exposure-CTI-Assessment

|

|-- README.md

|-- Report

| |-- CTI_Assessment_Report.pdf

|

|-- Evidence

| |-- Shodan_Redacted.png

| |-- IPinfo_Redacted.png

| |-- VirusTotal_Redacted.png

| |-- ThreatFox_Redacted.png

|

|-- Notes

|-- Methodology.md

---

# Skills Demonstrated

This project demonstrates:

- Cyber Threat Intelligence
- OSINT Investigation
- Vulnerability Analysis
- Risk Assessment
- MITRE ATT&CK Mapping
- Security Reporting
- Responsible Disclosure

---

# Analyst

**Neo NL**

Cyber Threat Intelligence Portfolio

Focus Areas:

- Threat Intelligence
- OSINT
- Vulnerability Research
- Security Analysis
- Risk Reporting

---

# Disclaimer

This repository is for educational and portfolio purposes only.

All technical identifiers have been redacted.

No unauthorised testing was performed.


