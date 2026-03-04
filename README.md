# 🏢 WorkerHub MY — Smart Foreign Worker Compliance System

> **A UI/UX Mockup demonstrating the Dify AI Architecture for Malaysian HR Compliance**

![WorkerHub MY Preview](https://img.shields.io/badge/Status-Mockup%20%2F%20Prototype-teal?style=flat-square) ![Built With](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-navy?style=flat-square) ![Dify](https://img.shields.io/badge/Powered%20By-Dify%20AI-blue?style=flat-square)

---

## 🎯 What is This?

This is a **working UI/UX prototype** for a Foreign Worker HR Compliance SaaS platform targeted at Malaysian companies. It demonstrates how the full Dify AI agent architecture would look and function **before** building the actual backend.

This mockup is designed to:
- Show clients / investors what the product feels like
- Validate user flows before Dify development begins
- Be easily shared via GitHub Pages

---

## 🚀 Live Demo

**Deploy instantly with GitHub Pages — no setup required:**

1. Fork this repo
2. Go to **Settings → Pages → Source → `main` branch → `/root`**
3. Your demo is live at `https://yourusername.github.io/workerhub-my/`

Or just open `index.html` directly in any browser — no server needed.

---

## ✨ Features Demonstrated

| Feature | Description | Dify Component |
|---|---|---|
| 📊 **Dashboard** | Live KPIs: expiring permits, FOMEMA due, compliance % | Frontend |
| 👷 **Worker Database** | Search, filter, view 142 workers with permit status | Database + API |
| 🤖 **AI Chat Assistant** | Ask about PLKS, FOMEMA, Employment Act — gets real answers | Dify Main Agent + RAG |
| 📎 **Document Upload** | Drag & drop passport/permit — triggers OCR extraction | Dify Workflow Tool |
| 🔔 **Alerts Panel** | Automated expiry warnings, FOMEMA due, insurance renewals | Dify Scheduled Workflow |
| 🌐 **BM/EN Toggle** | Language switching for Malaysian HR teams | UI Feature |
| ➕ **Add Worker Modal** | Full form with passport upload + AI auto-extraction | Dify OCR Workflow |

---

## 🏗️ The Real Dify Architecture (Post-Prototype)

```
┌─────────────────────────────────────┐
│         Frontend (This UI)          │
│     React/HTML → Dify API embed     │
└────────────────┬────────────────────┘
                 │
┌────────────────▼────────────────────┐
│       Dify Main Agent (Brain)       │
│  System Prompt: HR Compliance Bot   │
│  Routes: Direct → KB → Workflow     │
└──────┬──────────────────┬───────────┘
       │                  │
┌──────▼──────┐  ┌────────▼────────────┐
│ Knowledge   │  │   Dify Workflows    │
│ Base (RAG)  │  │  (Muscle)           │
│             │  │                     │
│ • JIM       │  │ 📎 Document OCR     │
│   Policies  │  │ 💾 Data Entry       │
│ • Empl. Act │  │ 📅 Permit Renewal   │
│ • FOMEMA    │  │ 🔔 Scheduled Alerts │
│   Guidelines│  │    (WhatsApp/Email) │
└─────────────┘  └─────────────────────┘
```

---

## 📁 File Structure

```
workerhub-my/
├── index.html          ← Single-file prototype (open this!)
└── README.md           ← This file
```

---

## 🧠 AI Knowledge Base (Planned for Dify)

The AI Assistant in this mockup simulates responses based on:
- **Jabatan Imigresen Malaysia** circular and policies (2024)
- **Employment Act 1955** (including 2022 amendments)
- **FOMEMA Guidelines** — annual medical requirements
- **FWHS Insurance Scheme** requirements under Employment Act Section 60K
- **JTK (Jabatan Tenaga Kerja)** submission procedures

---

## 🎯 Target Users

- HR Managers at Malaysian manufacturing, construction & plantation companies
- Foreign worker recruitment agencies
- Compliance officers managing Jabatan Imigresen renewals

---

## 📍 Roadmap (Full Dify Build)

- [ ] Connect Dify Agent via API
- [ ] Real Knowledge Base with JIM/JTK PDFs
- [ ] OCR Workflow for passport & permit extraction
- [ ] WhatsApp integration (via Twilio / WhatsApp Business API)
- [ ] Email alerts via scheduled Dify workflow
- [ ] MySQL/Supabase database integration
- [ ] Multi-company / multi-tenant support

---

## 🛠️ Built With

- Pure **HTML / CSS / JavaScript** — zero dependencies
- **Google Fonts**: Syne + DM Sans
- Designed to connect to **Dify AI** (dify.ai)
- Ready for **GitHub Pages** deployment

---

*Built as a mockup to demonstrate the WorkerHub MY architecture concept. For demo purposes only.*
