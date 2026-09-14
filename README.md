# ConstraintMirror
> **Financial Solutions That Only Exist Because of What You Refuse**  
> *Theme: Financial Inclusion & Sovereign Open LLMs*

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)
![Status: Prototype Ready](https://img.shields.io/badge/Status-Prototype%20Ready-blue.svg)
![Constraint Respect](https://img.shields.io/badge/Constraint%20Respect-100%25%20Inviolable-success.svg)

---

## 📌 1. Introduction & Problem Statement

### The Problem: The Exclusion Paradox
Over 1.4 billion people in underserved, rural, and informal communities remain excluded from the formal financial system. When they face critical capital needs (seeds, equipment, medical emergencies), they operate under deep, sacred **refusals**:
* ⛔ **"Never mortgage ancestral land"** — belongs to lineage and heritage.
* ⛔ **"Never borrow from relatives"** — triggers devastating social shame and family fracture.
* ⛔ **"Never take interest-bearing loans (Riba)"** — strict faith and moral boundaries.
* ⛔ **"Never migrate away"** — sole caregiver for aging parents or young children.
* ⛔ **"Never take informal loans"** — village loan sharks charging 120%+ APR and physical coercion.

Conventional financial advisory tools and algorithmic banking apps treat these boundaries as **friction to be negotiated away or compromised**. Advisors demand farmers mortgage their title deeds or push women into high-interest revolving credit. 

The result is advice that feels **culturally alien, unsafe, and hostile**—causing users to distrust and abandon formal finance.

### The Solution: "Designing by Absence"
**ConstraintMirror completely inverts the optimization paradigm:**
Instead of asking *"How do we persuade the user to compromise their boundaries to qualify for credit?"*, ConstraintMirror asks:
> *"What resilient financial pathways become possible **precisely because** of what the user refuses?"*

By treating refusals as primary creative material and mathematically removing standard debt vectors, the system surfaces latent non-debt solutions: **pre-harvest forward crop contracts, equipment-sharing pools (PACS), communal grain-credit floats, and ethical profit-and-loss partnerships (Mudarabah)**.

---

## 🌟 2. Key Features & Experiences

The repository contains two connected experiences designed in an **Editorial Light Mode**:

### A. The Client Portal Studio (`portal.html`)
A working, 4-step interactive application for end-users and community banking facilitators:
1. **Stated Financial Need:** Enter amount, urgency, and livelihood with simulated **vernacular voice dictation** and dialect switching (English, Hindi, Tamil, Telugu, Swahili).
2. **Declaration of Refusals:** Natural language input with interactive sacred boundary chips.
3. **The Inviolable Constraint Vault:** Visual lockdown ceremony confirming **0.00% Breach Risk** backed by grammar logit masking.
4. **Solutions Studio & Copilot:**
   * Actionable pathways tagged with `✨ Enabled by your refusal of: [Constraint]`.
   * **Multi-Turn Constraint-Safe Copilot:** Test "What if" shocks (delayed monsoons, price spikes) with real-time zero-breach verification.
   * **1-Click Action Kit Export:** Download or print a verified summary card for local cooperatives.

### B. The 5-Pillar Project Showcase (`index.html`)
An executive presentation site featuring:
* **Interactive Persona Switcher:** Pre-loaded with Ramesh (Farmer), Fatima (Weaver), and Elena (Caregiver).
* **The Contrast Engine:** Side-by-side comparison between standard bank advice vs. ConstraintMirror.
* **Syntax-Highlighted Code Inspector:** Tabbed viewer for extraction, counterfactual engine, auditor, and JSON schema.
* **Open LLM Innovation Analysis & 3-Horizon Roadmap.**

---

## 🔬 3. Open LLM Novelty & Architecture

ConstraintMirror utilizes open foundation models (**Llama 3, Gemma 2, Mistral, DeepSeek**) across a 4-stage verification pipeline:

```
[User Vernacular Speech/Text]
            │
            ▼
┌──────────────────────────────────────┐
│ 1. Refusal Extractor (Pydantic JSON) │
└──────────────────────────────────────┘
            │
            ▼
┌──────────────────────────────────────┐
│ 2. Deterministic Grammar Logit Mask  │ ──► Violating tokens forced to P = 0.00
└──────────────────────────────────────┘
            │
            ▼
┌──────────────────────────────────────┐
│ 3. Constrained Counterfactual Engine │ ──► Explores non-debt latent space (FPOs/PACS)
└──────────────────────────────────────┘
            │
            ▼
┌──────────────────────────────────────┐
│ 4. Adversarial Red-Team Auditor      │ ──► Rejects any subtle coercion or compromise
└──────────────────────────────────────┘
            │
            ▼
[Dignified Actionable Pathway]
```

### Why Open-Source LLMs Are Mandatory:
1. **Sovereign Privacy:** Vulnerable family debt secrets and cultural red lines are processed locally or on regional cooperative servers, never sent to commercial third-party cloud APIs.
2. **Deterministic Logit Masking:** In closed APIs, negative constraints are soft prompt hints prone to hallucinations. Open weights allow Context-Free Grammar (CFG) decoding (via Outlines / SGLang) to mathematically zero out prohibited tokens.
3. **QLoRA Cultural Adaptation:** Parameter-efficient fine-tuning on regional agrarian vernaculars and informal community savings mechanisms (Chits, Tontines, Hawala, Kudumbashree).
4. **Offline Edge Execution:** 4-bit quantized 3B models run offline on $80 battery-backed micro-nodes in remote village kiosks without internet.

---

## 📂 4. Repository Structure

```
constraint-mirror-web/
├── index.html       # 5-Pillar Project Showcase, Code Inspector & Presentation
├── portal.html      # Working 4-Step Client Portal & Multi-Turn Copilot
├── vercel.json      # Vercel deployment configuration & routing rewrites
└── README.md        # Documentation, problem statement, and deployment guide
```

---

## 🚀 5. How to Run Locally

This is a **zero-dependency, zero-install** project. You do not need Node.js, npm, or any external runtimes:

1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/constraint-mirror.git
   cd constraint-mirror
   ```
2. Open either file directly in your favorite browser:
   * **Portal:** Double-click `portal.html`
   * **Showcase:** Double-click `index.html`

---

## 🌐 6. How to Deploy to Vercel

### Method 1: Via GitHub (Recommended)
1. Push this repository to your GitHub account (see instructions below).
2. Go to [vercel.com](https://vercel.com) and log in.
3. Click **"Add New..."** $\to$ **"Project"**.
4. Select your `constraint-mirror` repository.
5. In **Framework Preset**, leave it as **"Other"** (it is a static website).
6. Click **"Deploy"**.
7. Vercel will provide your live URL (e.g. `https://constraint-mirror.vercel.app`).

### Method 2: Via Vercel CLI
If you have Vercel CLI installed:
```bash
npm install -g vercel
vercel
```
Follow the interactive prompts to deploy in seconds!

---

## 📤 7. How to Push to GitHub

Run the following commands in your terminal:

```bash
# 1. Initialize git inside the folder
git init

# 2. Add all files
git add .

# 3. Commit the files
git commit -m "Initial commit: ConstraintMirror Portal and Project Showcase"

# 4. Set default branch to main
git branch -M main

# 5. Connect your remote GitHub repository (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/constraint-mirror.git

# 6. Push to GitHub
git push -u origin main
```

---

## 🔮 8. Future Scope & Roadmap

* **Phase 1 (Q3–Q4 2026):** Voice-First WhatsApp & USSD Bot in 12 regional languages.
* **Phase 2 (2027):** Direct institutional API integration with Primary Agricultural Credit Societies (PACS) and state Self-Help Groups (SHGs).
* **Phase 3 (2028):** National Sovereign Edge Nodes deployed to 50,000 rural panchayat centers as Digital Public Infrastructure (DPI).

---

## 📜 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
