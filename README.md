```markdown
# 🛡️ VoiceShield AI — Enterprise Voice Clone & Deepfake Defense Platform

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.10%2B-brightgreen)](https://www.python.org/)
[![SIH 2026 Qualified](https://img.shields.io/badge/Hackathon-SIH%202026-orange)](#)

**VoiceShield AI** is a real-time cybersecurity platform engineered to detect synthetic voice clones, AI-generated speech, and audio deepfakes during high-stakes communications, corporate financial transfers, and security verifications.

Designed with a modern Glassmorphism Dark UI and powered by a serverless Flask backend, VoiceShield AI delivers multi-feature spectral forensic analysis with zero infrastructure latency on Vercel.

---

## 🔥 Key Highlights & Features

* **🔬 40-Coefficient MFCC & Spectral Engine:** Extracts Mel-Frequency Cepstral Coefficients (MFCCs), Spectral Centroids, and RMS Energy variance to catch pitch anomalies unique to synthetic TTS (Text-to-Speech) algorithms.
* **📊 ISO-Standard Clone Risk Index (0–100%):** Replaces binary True/False outputs with a dynamic risk spectrum, precisely identifying borderline and suspicious vocal payloads.
* **📄 Automated Forensic Evidence Pack (PDF):** Compiles forensic metadata, audit timestamps, and cryptographic verification QR codes into an exportable ISO/IEC 27001-compliant PDF report.
* **📱 Ultra-Responsive Glassmorphism UI:** Modern cyberpunk dark dashboard built with zero external framework bloat for instantaneous rendering on both mobile and desktop screens.
* **⚡ Vercel Serverless Architecture:** Optimized with native Python WSGI routing (`vercel.json`) for seamless deployment without persistent server costs.

---

## 🏗️ Repository Architecture

```text
VoiceShield-AI/
├── api/
│   └── index.py            # Flask Serverless WSGI Backend & Risk Engine
├── templates/
│   └── index.html          # Cyberpunk Glassmorphism UI Dashboard
├── vercel.json             # Vercel Serverless Deployment & Route Config
├── requirements.txt        # Production Dependencies
└── README.md               # Enterprise Documentation

```

---

## 🚀 Local Development Setup

### Prerequisites

* Python 3.10 or higher
* Standard `pip` package manager

### Installation Steps

1. **Clone the Repository:**
```bash
git clone [https://github.com/Madhankumar-cse/VoiceShield--AI.git](https://github.com/Madhankumar-cse/VoiceShield--AI.git)
cd VoiceShield--AI

```


2. **Install Core Dependencies:**
```bash
pip install -r requirements.txt

```


3. **Launch the Local Micro-Server:**
```bash
python api/index.py

```


4. Open your browser and navigate to `http://127.0.0.1:5000`

---

## ☁️ Deployment Guide (Vercel)

This application is fully pre-configured for Vercel Serverless Functions:

1. Push your repository to **GitHub**.
2. Visit [Vercel Dashboard](https://vercel.com) and click **"Add New Project"**.
3. Import your repository (`Madhankumar-cse/VoiceShield--AI`).
4. Click **Deploy** — Vercel will automatically parse `vercel.json` and host your live application!

---

## 🔬 Risk Scoring Matrix

| Risk Level | Status Badge | Acoustic Profile |
| --- | --- | --- |
| **0% – 39.9%** | 🟢 AUTHENTIC VOICE | High vocal pitch dynamics, natural spectral centroid jitter. |
| **40% – 74.9%** | 🟡 SUSPICIOUS MODULATION | Moderate acoustic flattening, room reverb, or ambient noise. |
| **75% – 100%** | 🔴 CRITICAL HIGH RISK | Monotone frequency spectrum, low variance — AI Clone flagged. |

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for details.

```

```
