# PhishGuard

PhishGuard is an AI-powered phishing detection and browser protection system designed to help users identify malicious websites, fake login pages, dangerous redirects, and suspicious links before they become security threats.

The project combines browser-level protection, real-time URL analysis, phishing pattern detection, and optional AI-assisted scanning into a single security-focused platform. The goal of the system is to provide lightweight but powerful protection against modern phishing attacks while keeping the experience simple and user-friendly.

This repository is a public preview version of the project created to showcase the concept, interface, workflow, and architecture of the system. The actual production implementation and private internal files are not included in this repository.

---

## Project Overview

PhishGuard currently consists of two major parts:

- A showcase/download website with a live URL checking interface
- A Chrome extension with advanced phishing detection and browser protection features

The extension is designed to classify websites into categories such as:

- Safe
- Suspicious
- Dangerous

Instead of only checking URLs, the system also analyzes page behaviour, login forms, redirects, brand impersonation patterns, suspicious domain structures, risky links, and phishing-related page content.

---

## Core Features

- Real-time phishing URL detection
- Chrome extension protection system
- Dangerous website blocking
- Suspicious page warning banners
- Popup-based URL checking
- AI-assisted phishing analysis
- Dynamic phishing page rechecking
- Fake login page detection
- Risky link interception
- Page-content analysis
- Local QA testing environment
- Dashboard and website preview
- Security-focused browser workflow

---

## Detection System

PhishGuard uses multiple layers of phishing analysis instead of relying on only one detection method.

The system checks for:

- Brand impersonation
- Typosquatting domains
- Homoglyph attacks
- Punycode and IDN spoofing
- Fake login pages
- Suspicious redirects
- Embedded credential traps
- Risky form actions
- URL shorteners
- Raw IP-based domains
- High-risk hosting patterns
- Deep subdomains and encoded URLs
- Fake payment and OTP pages

The extension can also recheck websites dynamically if suspicious login forms or credential fields appear later after the page initially loads.

---

## How It Works

When a user visits or checks a website, PhishGuard first runs a lightweight local detector to quickly analyze the URL structure and phishing indicators.

If stronger analysis is needed, the system can combine results with the optional AI-powered backend service. Based on the final risk score, the extension either:

- Allows the page normally
- Displays a warning banner
- Blocks the website completely

The system is designed to prioritize fast detection while minimizing unnecessary interruptions for safe websites.

---

## Example Detection Flow

```text
URL Checked:
https://faceb00k-login-security.example.com

Detection Results:
- Brand impersonation detected
- Suspicious login keywords found
- Dangerous domain structure
- Fake credential targeting indicators

Final Verdict:
DANGEROUS

Action:
Website blocked and warning page displayed.
```

---

## Screenshots

The screenshots included in this repository demonstrate different parts of the project including the extension workflow, phishing detection interface, warning system, dashboard previews, testing environment, and overall user experience.

They are added only to showcase the design direction and functionality preview of the system.

---

## Tech Stack

- JavaScript
- Python
- Chrome Extension APIs
- React
- FastAPI
- SQLite
- Local AI service integration
- Browser security workflows

---

## Repository Note

This repository is only intended as a preview and showcase version of PhishGuard.

The actual source code, backend logic, AI models, security rules, API keys, private workflows, and production implementation remain private.

The purpose of this repository is to present the project concept, screenshots, architecture direction, and feature overview.

---

## Future Scope

- Stronger AI phishing analysis
- Cloud reputation integration
- Browser-wide protection system
- Real-time threat intelligence
- Advanced dashboard analytics
- Safer email and link scanning
- Enterprise security support
- Multi-browser extension support
- Live phishing threat monitoring

---

## Author

**Rayan Qamar**
