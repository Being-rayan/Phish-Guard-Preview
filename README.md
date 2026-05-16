# PhishGuard

PhishGuard is an AI-powered phishing detection and browser protection system designed to help users identify malicious websites, fake login pages, dangerous redirects, and suspicious links before they become security threats.

The project combines a showcase website, Chrome extension, real-time URL analysis, and optional AI-assisted scanning into one security-focused platform. This repository is only a public preview of the project, created to show the concept, interface, workflow, and planned architecture. The actual production code and private implementation files are not included here.

---

## Project Overview

PhishGuard has two main parts: a showcase/download website with a live URL checker and a Chrome extension that provides browser-level phishing protection.

The extension classifies websites as:

- Safe
- Suspicious
- Dangerous

Instead of only checking the URL, PhishGuard also looks at page behaviour, fake login forms, redirects, brand impersonation, risky links, suspicious domains, and phishing-related content.

---

## Core Features

- Real-time phishing URL detection
- Chrome extension protection
- Dangerous website blocking
- Suspicious page warning banners
- Popup-based URL checking
- AI-assisted analysis
- Fake login page detection
- Risky link interception
- Page-content analysis
- Local testing environment

---

## Detection System

PhishGuard uses multiple detection layers to catch different phishing tricks. It checks for brand impersonation, typosquatting, homoglyph attacks, punycode spoofing, suspicious redirects, risky form actions, URL shorteners, raw IP domains, fake payment pages, OTP traps, and deep suspicious subdomains.

The extension can also recheck a page dynamically if login forms, credential fields, or risky content appear after the page has already loaded.

---

## How It Works

When a user opens or checks a website, PhishGuard first runs a fast local detector to analyze the URL and visible phishing signals. If deeper analysis is needed, the system can combine the result with an optional AI-powered backend service.

Based on the final risk level, PhishGuard can:

- Allow the website normally
- Show a warning banner
- Block the website completely

The goal is to keep users protected without disturbing normal browsing on safe websites.

---

## Screenshots

The screenshots added in this repository show the project preview, including the extension workflow, detection interface, warning screens, dashboard-style pages, and testing flow. They are included only to give a clear idea of how the system looks and works from a user perspective.

---

## Tech Stack

- JavaScript
- Python
- Chrome Extension APIs
- React
- FastAPI
- SQLite
- Local AI service integration

---

## Repository Note

This repository is only a preview and showcase version of PhishGuard. The actual source code, backend logic, AI models, security rules, API keys, and production-level implementation remain private.

The purpose of this repo is to present the project concept, screenshots, feature overview, and architecture direction.

---

## Future Scope

- Stronger AI phishing analysis
- Cloud reputation integration
- Real-time threat intelligence
- Advanced dashboard analytics
- Safer email and link scanning
- Multi-browser extension support

---

## Author

**Rayan Qamar**
