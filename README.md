# SecInterview — AI-Powered Cybersecurity Interview Simulator

<p align="center">
  <!-- Replace with your actual logo path -->
  <img src="assets/logo.png" alt="SecInterview Logo" width="180"/>
</p>

<p align="center">
  <strong>Simulate real cybersecurity interviews with a multi-agent AI system. Get role-specific technical questioning, instant CISO-level feedback, and a detailed performance report.</strong>
</p>

<p align="center">
  <a href="https://app.secinterview.dev">
    <img src="https://img.shields.io/badge/Status-Public%20Beta-brightgreen?style=for-the-badge" alt="Public Beta">
  </a>
  <img src="https://img.shields.io/badge/Source-Closed%20%2F%20Commercial-red?style=for-the-badge" alt="Closed Source">
  <img src="https://img.shields.io/badge/Architecture-Multi--Agent%20AI-orange?style=for-the-badge" alt="Multi-Agent">
</p>

---

## What is SecInterview?

SecInterview is a SaaS platform built for cybersecurity professionals, penetration testers, and security engineers preparing for technical interviews.

The core problem it solves: most candidates study theory but have no way to practice under real interview pressure. Static question banks go stale. Generic AI tools don't understand the domain.

SecInterview addresses this through a **multi-agent AI architecture** — each agent handles a distinct layer of the simulation, from scenario generation and real-time questioning to response analysis and report generation. The result is a dynamic, technically rigorous interview experience tailored to your specific role and seniority level.

---

## Key Features

**Multi-Agent Interview Engine**  
A coordinated system of AI agents simulates a live technical interview. One agent drives the CISO interrogator persona, another evaluates response quality in real time, and a third synthesizes the final performance report.

**Agentic Search & Live Threat Intelligence**  
The platform uses agentic web search to stay current with the threat landscape. Interview scenarios are informed by recent CVEs, newly published attack techniques, 0-day disclosures, and updated defensive frameworks — not a frozen dataset. As the full version ships, this pipeline will continuously pull from sources like NVD, MITRE ATT&CK, and security research feeds.

**Role-Specific Simulation**  
Tracks are tailored by domain — Penetration Testing, Cloud Security, Application Security, SOC/Blue Team, Red Team — and further adjusted by seniority level (Junior, Mid-Level, Senior).

**JD Matching**  
Paste a job description and the system adapts scenario difficulty and question focus to match the specific role requirements.

**CISO-Level Feedback Report**  
After each session, a structured report is generated covering: technical accuracy, methodology gaps, communication quality, MITRE ATT&CK alignment, strengths, and prioritized improvement areas.

**Multilingual Support**  
Currently available in English, Turkish, and [third language]. Designed for candidates preparing for global and remote roles.

---

## Architecture Overview

```
User Input (Role + Level + Optional JD)
        │
        ▼
┌─────────────────────┐
│  Scenario Agent     │  ← Generates interview context, selects question vectors
└────────┬────────────┘
         │
         ▼
┌─────────────────────┐     ┌──────────────────────┐
│  CISO Agent         │ ←── │  Agentic Search Layer │  ← CVEs, ATT&CK, threat feeds
│  (Interrogator)     │     └──────────────────────┘
└────────┬────────────┘
         │
         ▼
┌─────────────────────┐
│  Evaluation Agent   │  ← Scores responses: accuracy, depth, terminology
└────────┬────────────┘
         │
         ▼
┌─────────────────────┐
│  Report Agent       │  ← Generates structured performance report
└─────────────────────┘
```

---

## Demo

<!-- Add demo GIF or video thumbnail here -->
> Demo video and screenshots coming soon. Beta is live at [app.secinterview.dev](https://app.secinterview.dev)

---

## Current Status & Roadmap

| Milestone | Status |
|---|---|
| Private Beta Launch | ✅ Done |
| Multi-agent architecture | ✅ Done |
| Agentic search integration | ✅ Done |
| Public Beta | 🔄 Active |
| User dashboard & session history | 🔜 Next |
| CVE/0-day live feed integration | 🔜 Next |
| Enterprise / Team modules | 📋 Planned |
| Mobile support | 📋 Planned |

---

## Try the Beta

The beta is free to use. No credit card required.

- **Landing Page:** [secinterview.dev](https://secinterview.dev)
- **App:** [app.secinterview.dev](https://app.secinterview.dev)
- **Early Access:** [secinterview.dev/early-access](https://secinterview.dev/early-access)

Bug reports and feature requests are welcome via the [Issues](../../issues) tab.

---

## About

Built by [Onur Civan](https://linkedin.com/in/YOUR_LINKEDIN) as a solo technical project.

For partnership, investment, or enterprise inquiries, reach out via LinkedIn or open a Discussion in this repository.

---

<p align="center">
  If this project is useful or interesting to you, a ⭐ helps with visibility.
</p>
