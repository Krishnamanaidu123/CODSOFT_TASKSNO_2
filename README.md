# CODSOFT_TASKSNO_2

# Phishing Awareness Training Module

A self-contained, interactive web training module that teaches employees how to recognize and avoid phishing attacks. Built as a single HTML file — no build step, no dependencies, no backend required.

**[View the module](./phishing-training-module.html)** — open directly in any browser.

## Overview

The module is framed around a "case file" concept: instead of static bullet-point slides, learners examine real-looking phishing emails and fake login pages as pieces of evidence, click to reveal what gives them away, and test their instincts with a scored quiz at the end.

## What's covered

- **Identifying suspicious emails** — an annotated, click-to-reveal example highlighting spoofed sender domains, urgency tactics, mismatched links, and generic greetings
- **Spotting fake login pages & fraudulent websites** — how to read a URL correctly, why HTTPS padlocks aren't proof of legitimacy, and other visual/behavioral tells
- **Social engineering techniques** — authority impersonation, pretexting, baiting, Business Email Compromise (BEC), vishing, and smishing
- **Practical security tips** — hovering before clicking, verifying through a second channel, MFA, password hygiene, and reporting procedures
- **Case studies** — three real-world-style incidents (BEC invoice fraud, a cloned SSO portal, gift-card baiting) with expandable detail and takeaways
- **Knowledge check quiz** — six scenario-based multiple-choice questions with instant feedback and a live score

## Tech stack

- Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build tools, no external JS libraries
- Google Fonts (Oswald, Source Serif 4, IBM Plex Mono) loaded via CDN
- Fully responsive (desktop, tablet, mobile)
- No data is collected or transmitted anywhere — quiz scoring happens entirely client-side and resets on reload

## Usage

### Option 1 — Open locally
Download `phishing-training-module.html` and open it in any modern browser.

### Option 2 — Host with GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set the source branch (e.g. `main`) and root folder
4.link to it directly at:
   `https://krishnamanaidu123.github.io/CODSOFT_TASKSNO_2`

### Option 3 — Embed in an LMS / intranet
The file is fully self-contained and can be uploaded as-is to most learning management systems (SCORM wrappers, Confluence, SharePoint, internal wikis, etc.) or embedded via `<iframe>`.

## Customizing

- **Content**: all copy (email examples, tips, case studies, quiz questions) lives directly in the HTML/JS — search for the relevant section and edit in place
- **Branding/colors**: CSS custom properties are defined at the top of the `<style>` block under `:root` — update the hex values there to match your organization's palette
- **Quiz questions**: edit the `quizData` array near the bottom of the file to add, remove, or change questions

## License

Feel free to adapt this module for internal security awareness training at your organization.

## Feedback

Suspicious emails, near-misses, or anything unclear in this training should be reported to your organization's security/IT team.
