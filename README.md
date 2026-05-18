# PhishGuard

PhishGuard is an AI-powered phishing detection and browser protection system designed to help users identify malicious websites, fake login pages, dangerous redirects, and suspicious links before they become security threats.

**Live Demo:** https://phish-guard-site.vercel.app/  
**Source Code:** Private  
**Preview Repository:** Documentation and project showcase only

---

# Project Overview

PhishGuard is designed as a browser-level security assistant that helps users detect risky websites before they enter sensitive information such as passwords, OTPs, payment details, or login credentials.

The project combines a public showcase website, Chrome extension workflow, real-time URL analysis, page-content scanning, and optional AI-assisted analysis into one security-focused platform.

This repository is a public preview of the project. It is created to show the concept, interface, workflow, screenshots, and planned architecture. The actual production code, backend logic, AI models, private security rules, API keys, and internal implementation files are not included here.

---

# Key Features

- Real-time phishing URL detection
- Chrome extension-based browser protection
- Dangerous website blocking
- Suspicious page warning banners
- Popup-based URL checking
- AI-assisted phishing analysis
- Fake login page detection
- Risky link interception
- Page-content analysis
- Suspicious redirect detection
- Local testing environment
- Public showcase website
- Security-focused project preview

---

# Detection Workflow

```text
User opens or checks a website
        |
PhishGuard analyzes the URL
        |
Page behaviour and visible signals are checked
        |
Suspicious forms, redirects, and risky links are detected
        |
Optional AI-assisted analysis can support the result
        |
Website is classified as Safe, Suspicious, or Dangerous
        |
Safe sites continue normally
        |
Suspicious sites show a warning banner
        |
Dangerous sites are blocked before user interaction
```

---

# How It Works

PhishGuard first runs a fast detection process to analyze the website URL and visible phishing indicators. It checks whether the website shows signs of brand impersonation, fake login pages, suspicious redirects, risky forms, or phishing-style content.

The extension classifies websites into three safety levels:

- `Safe`
- `Suspicious`
- `Dangerous`

If a website is safe, browsing continues normally. If the page is suspicious, PhishGuard shows a warning banner. If the page is highly risky, the system can block the website completely before the user interacts with it.

The goal is to protect users without disturbing normal browsing on trusted websites.

---

# Detection System

PhishGuard uses multiple detection layers to catch different phishing techniques, including:

- Brand impersonation
- Typosquatting
- Homoglyph attacks
- Punycode spoofing
- Suspicious redirects
- Risky form actions
- URL shorteners
- Raw IP domains
- Fake payment pages
- OTP traps
- Fake login forms
- Deep suspicious subdomains
- Risky outgoing links
- Suspicious page content

The extension can also recheck a page dynamically if login forms, credential fields, or risky content appear after the page has already loaded.

---

# Core System Modules

PhishGuard includes planned and previewed modules such as:

- Showcase website
- Chrome extension workflow
- URL scanning system
- Page-content analyzer
- Fake login detector
- Risky link interceptor
- Warning banner system
- Dangerous page blocker
- Optional AI-assisted analysis service
- Local testing environment
- Security preview dashboard

---

# Tech Stack

## Frontend And Extension

- JavaScript
- React
- Chrome Extension APIs

## Backend And AI

- Python
- FastAPI
- SQLite
- Local AI service integration

## Deployment

- Vercel
- Environment-based configuration
- Public showcase deployment

---

# Demo Workflow

1. Open the live deployment
2. Review the PhishGuard project showcase
3. Check the URL scanning and detection flow
4. View the browser protection workflow
5. Understand the warning and blocking system
6. Review screenshots showing the extension and testing process

---

# Screenshots

Screenshots are included in this repository to showcase the project preview, extension workflow, detection interface, warning screens, dashboard-style pages, and testing flow.

They are included to give a clear idea of how PhishGuard looks, works, and protects users from a browser-security perspective.

---

# Current Limitations

- This repository is only a public preview and showcase version
- Actual production source code is not included
- Backend logic, AI models, API keys, and private security rules remain private
- Detection examples are shown for project demonstration
- Browser protection behaviour depends on the final extension implementation
- Real-world phishing detection requires continuous testing and rule updates

This repository exists for recruiter showcase, workflow explanation, and technical project presentation.

---

# What This Project Demonstrates

- Browser security project planning
- Chrome extension-based protection workflow
- Phishing URL detection logic
- Fake login and risky page analysis
- Warning and blocking system design
- AI-assisted security analysis concept
- Full-stack security product thinking
- User-focused cyber safety workflow
- Public project presentation and documentation

---

# Future Scope

- Stronger AI phishing analysis
- Cloud reputation integration
- Real-time threat intelligence
- Advanced dashboard analytics
- Safer email and link scanning
- Multi-browser extension support
- Improved phishing pattern detection
- Larger safe and malicious URL testing dataset
- Browser extension store publication

---

# Current Status

PhishGuard is deployed as a public project preview and showcase platform.

The public repository is intended for project presentation, architecture overview, screenshots, feature explanation, and workflow demonstration. The actual production code, private backend files, AI logic, security rules, API keys, and internal implementation are not included here.

---

# Author

Rayan Qamar
