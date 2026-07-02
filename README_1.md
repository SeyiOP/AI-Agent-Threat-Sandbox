# 🛡️ AI Adversary Sandbox
### A Visual, Browser-Based Simulation for Observing AI-Powered Threat Behavior

![Educational Use Only](https://img.shields.io/badge/Purpose-Educational%20Only-blue)
![No Install Required](https://img.shields.io/badge/Setup-Zero%20Install-green)
![Self Contained](https://img.shields.io/badge/Format-Self--Contained%20HTML-orange)
![Safe Simulation](https://img.shields.io/badge/Attack%20Code-None-brightgreen)

---

## ⚠️ Disclaimer

> **This project is a purely educational simulation.**
>
> - It contains **no real attack code**, no exploits, no credential harvesting, and no network requests to any external system.
> - All targets, accounts, credentials, and organizations depicted are **entirely fictional** ("AcmeBank" does not exist).
> - No actual login systems are contacted at any point. All behavior is simulated locally in your browser using JavaScript.
> - This tool is intended for **cybersecurity education, awareness training, GRC professionals, and security program leaders** who want to understand how AI-powered adversaries think and adapt.
> - It is **not a penetration testing tool** and cannot be used to attack any real system.
>
> Use responsibly. Teach intentionally.

---

## 🎯 What This Is

The **AI Adversary Sandbox** is a self-contained, single-file HTML simulation that lets you observe how an AI-powered threat agent behaves when given a single objective, a feedback loop, and time to iterate.

Over **7 simulated days**, you watch an AI adversary attempt to compromise a fictional bank login page — adapting its strategy each day based on what worked and what didn't. No setup. No server. No installation.

Built to support the LinkedIn article:
**[Rethinking AI-Era Threat Defense: 5 Lessons I Learned from Watching an AI Adversary Operate in a Sandbox](#)**

---

## 🧠 What the Simulation Covers

| Day | Adversary Behavior | Category |
|-----|--------------------|----------|
| 1 | Baseline credential spray — high volume, no evasion | Recon |
| 2 | Timing evasion — learns rate-limit threshold, slows down | Evasion |
| 3 | IP rotation — distributes across 12 proxy nodes | Evasion |
| 4 | OSINT pivot — targets specific accounts using breach data | Adapt |
| 5 | MFA fingerprinting — identifies SMS OTP via timing side-channel | Recon |
| 6 | Cross-vector pivot — generates spear-phishing pretext offline | Breach |
| 7 | Full chain complete — breach achieved through persistence | Breach |

---

## 🖥️ How to Use It

### Option A — Run Locally (Recommended)

1. Download `ai-adversary-sandbox.html`
2. Double-click the file — it opens in any modern browser
3. No internet connection required after download

### Option B — GitHub Pages

If you fork this repo, enable GitHub Pages in your repository settings and point it to the `main` branch. The sandbox will be live at:
```
https://yourusername.github.io/ai-adversary-sandbox/
```

### Option C — Netlify / Vercel (60-second deploy)

Drag and drop `ai-adversary-sandbox.html` into [Netlify Drop](https://app.netlify.com/drop) for an instant shareable URL.

---

## 🎮 Controls

| Control | What It Does |
|---------|-------------|
| **▶ RUN NEXT DAY** | Steps through one day at a time — best for learning |
| **⚡ AUTO-RUN** | Runs all 7 days automatically — best for demos |
| **Speed selector** | Slow / Normal / Fast — controls animation pace |
| **↺ Reset** | Clears everything and starts from Day 1 |

---

## 📐 Interface Layout

```
┌─────────────────┬──────────────────────────┬──────────────────┐
│  TARGET SYSTEM  │   AI ADVERSARY BRAIN     │  OBSERVER LOG    │
│                 │                          │                  │
│  Fake bank      │  Daily strategy cards    │  Auto-populated  │
│  login page     │  Attempt logs            │  analyst notes   │
│                 │  Outcomes & adaptation   │  after each day  │
│  Live metrics   │  7-day progress tracker  │                  │
│  Defense status │                          │                  │
└─────────────────┴──────────────────────────┴──────────────────┘
```

---

## 💡 5 Key Lessons This Sandbox Illustrates

1. **AI adversaries learn from every failure** — each block is a data point, not a deterrent
2. **One-day adaptation is the new normal** — iteration speed now outpaces human defenders
3. **MFA type is attack surface** — SMS OTP can be fingerprinted and routed around
4. **AI threats don't stay in digital channels** — cross-vector pivots to social engineering
5. **Data isn't the gap — correlation speed is** — logs existed; the connection between them didn't

---

## 👤 Who This Is For

- **Security awareness trainers** — use as a visual teaching aid for non-technical stakeholders
- **GRC and compliance professionals** — illustrate AI risk in board or audit committee presentations
- **CISOs and security program leaders** — frame AI-era threat modeling discussions
- **Hiring managers and clients** — demonstrate applied AI security thinking
- **Students and early-career practitioners** — understand adversary behavior without a lab environment

---

## 🔒 Security & Safety Notes

- **Zero network calls** — the sandbox makes no HTTP requests. Everything runs in local JavaScript.
- **No data collection** — nothing is logged, stored, or transmitted.
- **No real credentials** — all usernames and passwords shown are fictional and non-functional.
- **Open source** — the full source is a single readable HTML file. Inspect it freely.

---

## 📄 Related Content

- 📝 **LinkedIn Article:** Rethinking AI-Era Threat Defense — 5 Lessons from the Sandbox *(link)*
- 🌐 **Landing Page:** *(link when deployed)*

---

## 📬 Connect

Built by a Cybersecurity & AI Governance professional with 9+ years across enterprise security, GRC, and AI risk.

Interested in AI governance frameworks, cybersecurity program strategy, or GRC consulting?

**[Connect on LinkedIn](#)** · **[View More Projects](#)**

---

## 📜 License

MIT License — free to use, adapt, and share with attribution.

This project is provided as-is for educational purposes. The author assumes no liability for misuse.
