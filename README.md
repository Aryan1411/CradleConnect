# KindPath Surrogacy — Demo Web App

MIT-licensed, client-side demo for a secure, compassionate, and compliant platform connecting intended parents, surrogate mothers, and trusted hospitals/clinics. Focused on trust, transparency, medical safety, and emotional sensitivity.

Important: This is an educational demo. It is not a medical or legal service. Do not enter sensitive personal or health information. Consult licensed professionals.

## Overview

This single-page web app demonstrates:

- Intended Parents
  - Local, privacy-first profile (identity and eligibility attestation demo)
  - Search/filter verified surrogate profiles
  - Consent-based matching and privacy-protected chat (AES-GCM encryption in-browser)
  - Hospital/clinic comparison (success rates, technology, certifications)
  - Educational guides

- Surrogate Mothers
  - Simple onboarding with eligibility checklist
  - Transparent compensation fields
  - Anonymous until mutual consent
  - Consent request inbox

- Hospitals & Clinics
  - Directory with filters, success rates, certifications
  - Side-by-side comparison (up to 3)
  - Appointment scheduling (stored locally)

- Pricing & Transparency
  - Estimate builder with clear breakdown
  - “No hidden costs” policy
  - Downloadable estimate via browser PDF (Print)
  - Legal/consent template downloads (educational only)

- Trust, Safety & Compliance
  - Compliance badges and ethics-first messaging
  - Legal framework overview with disclaimers
  - Privacy by design: no tracking, no servers in this demo

- Additional Features
  - AI-assisted match scoring (heuristic demo)
  - Anonymous Q&A community with basic moderation
  - Multilingual headings (English/Spanish toggle)
  - Accessible, minimalist design (keyboard focus, labels)

## Setup

- No build required.
- Download or clone this repository.
- Files:
  - index.html
  - README.md

License: MIT (see License section below).

## Usage

1. Open index.html in a modern browser.
2. Select your role using the top-right Role selector:
   - Intended Parent: create a profile, search surrogates, request consent, compare hospitals, build pricing estimates, and use secure messaging once consented.
   - Surrogate: create a profile, review consent requests, control anonymity and what is shared.
   - Hospital/Clinic: this demo focuses on directory view; in a full build, this role would manage listings, certifications, pricing, and appointments.

Key flows:
- Consent-based matching:
  - As Intended Parent, click “Request Consent” on a surrogate profile.
  - Switch Role to Surrogate to approve/deny in “Consent Requests”.
  - Once approved, messaging unlocks for that surrogate in the parent role.
- Secure messaging:
  - Enter a shared passphrase (agreed by both parties) to unlock a conversation.
  - Messages are encrypted in your browser using AES-GCM and stored locally.
  - Clear chat deletes the local history.
- Hospitals:
  - Filter by location and price.
  - Select up to 3 hospitals to compare side-by-side.
  - Book consultations (stored locally).
- Pricing:
  - Fill in line items and calculate.
  - Use “Download PDF” to print the estimate as a PDF via your browser’s Print dialog.
- Community:
  - Post anonymous questions; moderation enforces basic civility and no PII.

Notes:
- All data is stored in localStorage only. No network requests are made.
- This is a demo; do not enter real personal or medical information.
- For legal or medical decisions, consult licensed professionals.

## License

MIT License

Copyright (c) 2025 KindPath Surrogacy

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.