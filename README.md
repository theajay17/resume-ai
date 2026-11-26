<div align="center">

# Resume Build 🚀

### AI-powered resume builder for smarter job applications

Build professional resumes, check ATS readiness, generate cover letters and export print-ready PDFs — from one Android app.

[![Google Play](https://img.shields.io/badge/Google_Play-Live-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.resumeai.resume_ai)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

</div>

---

## ✨ Features

- 📄 **Step-by-step resume builder** — personal details, education, experience, skills, certifications and projects
- 🎨 **Multiple templates** — clean, executive, creative and ATS-friendly layouts; switch anytime without losing data
- 🎯 **ATS score checker** — upload an existing PDF/DOCX resume and get a compatibility score, keyword analysis and suggestions
- 🤖 **AI writing assistant** — polish summaries, rewrite bullet points with action verbs, tailor to a job role
- ✍️ **Cover letter generator** matched to your resume
- 📤 **A4 PDF export & sharing** — download or share via email, WhatsApp, LinkedIn or Drive
- ☁️ **Google sign-in & cloud sync** across devices

## 🧱 Tech stack

| Area | Tech |
|---|---|
| App | Flutter, Dart, Provider |
| AI | Anthropic Claude API, OpenRouter |
| Document parsing | Syncfusion Flutter PDF, `archive` (DOCX) |
| PDF generation | `pdf`, `printing` |
| Backend | Firebase Auth (Google Sign-In), Cloud Firestore, Crashlytics |
| Monetization | Google Mobile Ads (AdMob) — banner + interstitial with cooldown and fail-safe loading |
| Platform | Targets Android 16 (API 36), 16 KB page-size compliant |

## ✅ Engineering notes

- 67 automated tests (`flutter test`) covering AI resume flow, ad service and key screens
- Static analysis clean (`flutter analyze`)
- Test ads gated to debug builds to avoid invalid-traffic policy issues
- Regular versioned releases on Google Play (currently 2.3.x)

## 🔒 Source code

This repository is a **public product showcase**. Production source, credentials, API keys and signing files are kept private.

---

<div align="center">

Built by [Ajay Kumar Saw](https://github.com/theajay17) · AJAY LABs · [LinkedIn](https://www.linkedin.com/in/ajay-kumar-saw-775aa832a)

</div>
