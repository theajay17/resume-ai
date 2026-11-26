<p align="center"><img src="assets/banner.svg" alt="Resume Builder — AI resume builder with ATS score checker & cover letters" width="100%"/></p>
<p align="center"><a href="https://play.google.com/store/apps/details?id=com.resumeai.resume_ai"><img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="72"/></a></p>
<p align="center"><img src="https://img.shields.io/badge/status-live_on_Google_Play-22c55e?style=flat-square" alt="status"/> <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android"/> <img src="https://img.shields.io/badge/source-private-555?style=flat-square&logo=github" alt="source private"/> <img src="https://img.shields.io/badge/by-Wushang_Labs-111?style=flat-square" alt="Wushang Labs"/></p>
---

## ✨ Overview

Resume Builder is an all-in-one resume builder and CV maker for freshers and professionals. It combines a step-by-step builder, ATS-friendly templates, an **ATS score checker** for existing resumes, and **AI writing assistance** — then exports a print-ready A4 PDF in one tap.

## 🚀 Features

<table>
<tr>
<td width="50%" valign="top"><h3>📝 Step-by-step builder</h3>Personal details, education, experience, skills, certifications, projects</td>
<td width="50%" valign="top"><h3>🎯 ATS score checker</h3>Upload a PDF/DOCX resume → compatibility score, keywords, suggestions</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>🎨 Templates</h3>Clean, executive, creative and ATS-friendly — switch without losing data</td>
<td width="50%" valign="top"><h3>🤖 AI writing assistant</h3>Polish summaries, action-verb bullets, tailor to a role</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>✍️ Cover letter generator</h3>Matched to your resume template</td>
<td width="50%" valign="top"><h3>📤 A4 PDF export & share</h3>Email, WhatsApp, LinkedIn, Drive or device files</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>☁️ Google sign-in & cloud sync</h3>Drafts saved locally or synced across devices</td>
<td width="50%" valign="top"><h3>📣 Ad-supported</h3>Banner + interstitial ads with cooldown and fail-safe loading</td>
</tr>
</table>

## 📱 Screenshots

<p align="center">
  <img src="https://play-lh.googleusercontent.com/P11kOPyAPYAk-bYHgPGZqCOTu4o-Apy1lu0aDkAambWEOjUlEVMURcSy3YMA1vxEXTG2qIki5J0RjiAtUSJHhg=w400" width="200" alt="Resume Builder screenshot 1"/>
  <img src="https://play-lh.googleusercontent.com/E5Gy2umXDqXh5Lh2xSp37Mo8bm42D_DgpxpYHvXmb4Llq-fcjt5dZQ-suSSpG55CapQq7FnVCTA4aAlFGwI521o=w400" width="200" alt="Resume Builder screenshot 2"/>
  <img src="https://play-lh.googleusercontent.com/ldp8-sjCtODBQdnnadftnR0-oCm5slIpsX4enS8dcWUe0d00RLGqf2jrQ7jBTiajSzMwdKPhSFpCoExKKW5z=w400" width="200" alt="Resume Builder screenshot 3"/>
  <br/>
  <img src="https://play-lh.googleusercontent.com/fCnVy3Y4-GS5UJ2_zWKiYx3TnjdlpdBCIHUFwpCZ8LUDnCheBYzPH-0dCun42AVp3oMx5RtDm_J69ID5ps6dVA=w400" width="200" alt="Resume Builder screenshot 4"/>
  <img src="https://play-lh.googleusercontent.com/MAc2Zlqd5nbuLCk2UD0HaN19ripJyEJ9Mi4JaGtpPAXIKPQRgelGpIqM3QyonAzjhzwifIrROU74Jldvy2cHBg=w400" width="200" alt="Resume Builder screenshot 5"/>
  <img src="https://play-lh.googleusercontent.com/w6BiIFHYUjh4V7DmcoWsjCoDU5fJ17pxu2VepDrGwrIboZebMxmhN4uexP9i8_7MhsyHaKxnn0-f-0RJdAav=w400" width="200" alt="Resume Builder screenshot 6"/>
</p>

## 🧱 Tech stack

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API"/>
  <img src="https://img.shields.io/badge/OpenRouter-6566F1?style=for-the-badge" alt="OpenRouter"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Syncfusion_PDF-FF6F00?style=for-the-badge" alt="Syncfusion PDF"/>
  <img src="https://img.shields.io/badge/AdMob-EA4335?style=for-the-badge&logo=googleads&logoColor=white" alt="AdMob"/>
</p>

## 🏗️ Architecture

<p align="center"><img src="assets/architecture.svg" alt="Resume Builder architecture diagram" width="100%"/></p>

## 🔍 Engineering highlights

- Parses uploaded **PDF and DOCX** resumes on-device for ATS scoring (Syncfusion PDF + archive)
- Pluggable AI layer over **Anthropic Claude** and **OpenRouter**
- Multiple resume templates rendered to print-ready A4 PDFs
- **67 automated tests** (AI resume flow, ad service, key screens); `flutter analyze` clean
- Targets **Android 16 (API 36)** with 16 KB page-size alignment verified
- Test ads gated to debug builds to avoid invalid-traffic policy strikes; regular versioned releases (2.3.x)

## 🔒 About this repository

This is a **product showcase**. The source code, credentials and signing keys are private. Happy to walk through the architecture and code in an interview — reach out below.

---

<p align="center">
  Designed & built by <a href="https://github.com/theajay17"><b>Ajay Kumar Saw</b></a> · Wushang Labs<br/><br/>
  <a href="https://www.linkedin.com/in/ajay-kumar-saw-775aa832a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sawajay303@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://play.google.com/store/apps/dev?id=4822433550844528613"><img src="https://img.shields.io/badge/All_apps-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play"/></a>
</p>
