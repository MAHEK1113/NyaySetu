# NyaySetu
**NyaySetu** is a Hindi legal service app that makes legal help simple and accessible. It offers easy-to-understand legal information, answers common queries, and connects users with verified lawyers, ensuring quick, reliable, and affordable support for everyday legal needs.

<div align="center">

# ⚖️ NyaySetu— न्याय से

### *A Bridge to Justice for Every Indian Citizen*

**Hindi Legal Help Portal | निःशुल्क कानूनी सहायता पोर्टल**

---

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)
[![Made for India](https://img.shields.io/badge/Made%20for-🇮🇳%20India-orange?style=for-the-badge)](https://github.com/your-username/nyaysetu)

---

> **NyaySetu (न्याय सेतु)** means *"Bridge to Justice"* in Hindi.  
> A fully functional, single-file legal aid website built to make Indian law accessible to every citizen — in their own language.



</div>

---

## 📸 Preview

```
┌─────────────────────────────────────────────────────────────────┐
│  ⚖️ न्याय सेतु  |  सेवाएं  AI सहायक  अधिकार  अपराध  हेल्पलाइन  │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│         आपका अधिकार, हमारी जिम्मेदारी                          │
│   Free Legal Aid | AI Chat | Rights | Helplines | Complaint     │
│                                                                 │
│  [ 🤖 AI से पूछें ]    [ 📋 सेवाएं देखें ]                     │
│                                                                 │
├───────────────┬───────────────┬───────────────┬────────────────┤
│  50,000+ लोग  │  200+ विशेषज्ञ │    28 राज्य   │  100% निःशुल्क │
└───────────────┴───────────────┴───────────────┴────────────────┘
```

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Feature Breakdown](#-feature-breakdown)
- [Offence Finder Categories](#-offence-finder-categories)
- [Legal Helplines Covered](#-legal-helplines-covered)
- [Contributing](#-contributing)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Disclaimer](#-disclaimer)
- [Acknowledgements](#-acknowledgements)

---

## 🎯 About the Project

**NyaySetu** was built with one mission: *no Indian citizen should be denied justice because they don't know the law or can't afford a lawyer.*

India has robust legal frameworks — IPC, BNS, Consumer Protection Act, NALSA, DV Act, POCSO, and many more — but most citizens, especially in rural areas, have no idea how to access them. NyaySetu bridges this gap by providing:

- **Plain-Hindi explanations** of complex legal concepts
- **An AI-powered legal assistant** that answers questions in Hindi instantly
- **An Offence Finder tool** — select what happened and instantly know which legal case applies, which IPC/BNS sections are relevant, and what punishment is prescribed
- **Emergency helpline numbers** for all major legal situations
- **A complaint registration form** to initiate the process

This is a **zero-dependency, single-HTML-file** website — it runs anywhere: local browser, GitHub Pages, Netlify, any web server, or even offline.

---

## ✨ Key Features

### 🤖 AI Legal Assistant (Hindi Chat)
- Conversational chatbot interface fully in Hindi
- Answers questions on FIR filing, bail procedure, domestic violence, divorce, consumer rights, and more
- Quick-reply buttons for most common legal queries
- Typing animation for a natural conversation feel

### 🔍 Offence Finder — *The Centerpiece Feature*
- **35+ offences** mapped to their exact legal case types
- **Live search** — type in Hindi or English to filter instantly
- **7 category tabs**: Criminal, Civil, Consumer, Family, Cyber, Property, Labour
- Each offence card shows:
  - Applicable IPC / BNS section numbers
  - Whether the case is Criminal, Civil, Consumer, or a combination
  - Plain-Hindi description of the offence
  - Prescribed punishment / penalty
- Color-coded badges: 🔴 Criminal | 🔵 Civil | 🟢 Consumer | 🟡 Both

### 📋 6 Legal Service Areas (with Modal Details)
Each service category opens a detailed modal with step-by-step guidance:

| Service | Coverage |
|---|---|
| 👨‍👩‍👧 परिवार कानून | Divorce, custody, domestic violence, alimony |
| 🏠 संपत्ति विवाद | Land disputes, rent, will, RERA |
| 🛒 उपभोक्ता अधिकार | Consumer forum, insurance, e-commerce |
| 👷 श्रम कानून | Wrongful termination, wages, PF/ESI |
| 👮 पुलिस व FIR | FIR process, arrest rights, bail |
| 💻 साइबर क्राइम | Online fraud, hacking, cyberbullying |

### ⚖️ Fundamental Rights Section
Constitutional articles explained in plain Hindi:
- Article 14 (Equality), 19 (Freedom), 21 (Right to Life), 32 (Constitutional Remedies), 39A (Free Legal Aid), 44 (UCC)

### 📞 Emergency Helplines (Clickable)
6 national helplines with one-tap calling:
`112` · `1091` · `1098` · `15100` · `1930` · `14567`

### 📝 Online Complaint Registration
- Form with full validation (name, phone, state, category, details)
- Generates a unique ticket number on submission
- Ready to be connected to a real backend

### 🎨 Design Highlights
- Deep Navy + Saffron + Gold — inspired by the Indian Tricolour
- Noto Sans Devanagari — optimized for Hindi text rendering
- Fully responsive (mobile, tablet, desktop)
- Smooth animations, scroll-to-top, sticky header
- Dark theme throughout — easy on the eyes

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | Vanilla CSS3 (CSS Variables, Grid, Flexbox, Animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Noto Sans Devanagari |
| Icons | Unicode Emoji |
| Dependencies | **Zero** — no frameworks, no libraries, no build step |

> **Why no framework?** NyaySetu is designed to work everywhere — including areas with slow internet, on old browsers, and even saved offline. A single HTML file is the most portable and accessible format possible.

---

## 🚀 Getting Started

### Option 1 — Open Directly (Fastest)
```bash
# Just open it in any browser
# No installation, no server, no build step needed
open remarkable-raindrop-5548e2.netlify.app
```

### Option 2 — Clone the Repository
```bash
git clone https://github.com/your-username/nyaysetu.git
cd nyaysetu
open index.html
```

### Option 3 — GitHub Pages (Free Hosting)
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://your-username.github.io/nyaysetu`

### Option 4 — Netlify / Vercel Drop
1. Go to [netlify.com/drop](https://app.netlify.com/drop) or [vercel.com](https://vercel.com)
2. Drag and drop the `nyaysetu.html` file
3. Live in 30 seconds — free


---

## 📁 Project Structure

```
nyaysetu/
│
├── index.html              ← Entire website (single file)
│
├── README.md               ← This file
├── LICENSE                 ← MIT License
├── CONTRIBUTING.md         ← Contribution guidelines

```

> **Note:** The entire website lives in a single `index.html` file. CSS and JavaScript are both embedded inline. This is intentional — it maximizes portability and works without a web server.

---

## 🔍 Feature Breakdown

### Offence Finder — How It Works

```
User selects a category OR types in search bar
         ↓
JavaScript filters the offences[] array
         ↓
Matching offence cards render dynamically
         ↓
Each card shows:
  • Offence name (Hindi + English)
  • Case type badge (Criminal / Civil / Consumer / Both)
  • IPC / BNS section numbers
  • Plain-Hindi description
  • Punishment details
```

### AI Chat — Flow

```
User types question / clicks quick-reply button
         ↓
getReply() matches keywords in the message
         ↓
Simulated typing delay (1.4–2.2 seconds)
         ↓
Legal guidance returned in Hindi
         ↓
(Ready for real AI API integration — see Roadmap)
```

---

## ⚖️ Offence Finder Categories

### 🔴 आपराधिक (Criminal — IPC/BNS)
| Offence | Section | Punishment |
|---|---|---|
| हत्या (Murder) | IPC 302 / BNS 101 | Death / Life imprisonment |
| मारपीट (Assault) | IPC 323-325 / BNS 115-118 | 1–7 years |
| चोरी (Theft) | IPC 378-382 / BNS 303-307 | Up to 3 years |
| डकैती (Dacoity) | IPC 390-395 / BNS 309-310 | 7–10 years / Life |
| दहेज उत्पीड़न (Dowry) | IPC 498A | 3 years |
| बलात्कार (Rape) | IPC 375-376 / POCSO | 7 years to Death |
| जालसाज़ी (Forgery) | IPC 463-471 / BNS 336-342 | 2–7 years |
| आगजनी (Arson) | IPC 435-436 / BNS 329 | 7 years–Life |

### 🔵 दीवानी (Civil)
Divorce, child custody, alimony, property disputes, rent, will contests

### 🟢 उपभोक्ता (Consumer)
Defective products, builder fraud, insurance rejection, e-commerce fraud, utility negligence

### 🟡 पारिवारिक (Family)
Domestic violence, senior neglect, guardianship, dowry

### 🟣 साइबर (Cyber — IT Act)
Online fraud, hacking, morphing/MMS, phishing, fake profiles, cyberbullying

### 🟠 संपत्ति (Property)
Encroachment, will disputes, rent disputes, property registration fraud

### ⚪ श्रम (Labour)
Wrongful termination, wage theft, workplace harassment, PF/ESI default

---

## 📞 Legal Helplines Covered

| Number | Service | Availability |
|---|---|---|
| **112** | National Emergency (Police, Ambulance, Fire) | 24×7 |
| **1091** | Women's Helpline | 24×7 |
| **1098** | Childline India | 24×7 |
| **15100** | NALSA — Free Legal Aid | 24×7 |
| **1930** | Cyber Crime Helpline | 24×7 |
| **14567** | Senior Citizens Helpline | 24×7 |

---

## 🗺 Roadmap

### v1.0 — Current (Single-file MVP)
- [x] Hindi UI with Devanagari typography
- [x] 6 legal service areas with modal guidance
- [x] AI chat with keyword-based responses
- [x] Offence Finder with 35+ offences
- [x] Fundamental rights section
- [x] Emergency helplines
- [x] Complaint registration form
- [x] Fully responsive design

### v1.1 — Planned
- [ ] Real AI API integration (Gemini / Claude / GPT) for dynamic Hindi responses
- [ ] Lawyer directory with state/district filter
- [ ] RTI (Right to Information) guide and template generator
- [ ] PWA support (installable, offline-first)

### v1.2 — Future
- [ ] Backend integration (Node.js / Firebase) for real complaint submission
- [ ] Multi-language support (Urdu, Tamil, Bengali, Marathi, Gujarati)
- [ ] Document template generator (FIR draft, legal notice, consumer complaint)
- [ ] Case status tracker
- [ ] NALSA integration for live free legal aid requests

### v2.0 — Vision
- [ ] Mobile app (React Native / Flutter)
- [ ] Voice-based legal Q&A in Hindi
- [ ] District-level court information
- [ ] Video consultations with empanelled lawyers

---

## 🤝 Contributing

Contributions are what make open-source powerful. We welcome contributions of all kinds:

### Ways to Contribute
- 🐛 **Bug reports** — Found something broken? Open an issue
- 💡 **Feature suggestions** — Have an idea? We'd love to hear it
- 🌐 **Translations** — Help add regional languages (Telugu, Tamil, Bengali, etc.)
- ⚖️ **Legal content** — Are you a lawyer? Help us verify and expand our legal guidance
- 🎨 **Design improvements** — Better UI/UX suggestions welcome
- 📖 **Documentation** — Help improve the README or add a wiki

### How to Contribute

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/add-telugu-support

# 3. Make your changes
# 4. Commit with a clear message
git commit -m "feat: add Telugu language support for helpline section"

# 5. Push to your fork
git push origin feature/add-telugu-support

# 6. Open a Pull Request
```

### Contribution Guidelines
- Keep the single-file architecture intact unless proposing a major v2 refactor
- All legal information must be accurate and cite specific Acts/Sections
- Hindi text must be reviewed by a native speaker before merging
- New features should be responsive and work without internet if possible

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full text.

```
MIT License — Copyright (c) 2024 NyaySetu Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, subject to the following conditions: The above copyright notice and
this permission notice shall be included in all copies.
```

---

## ⚠️ Disclaimer

> **NyaySetu is an informational resource, not a legal practice.**

- The information provided is for **general awareness only** and does not constitute legal advice.
- Laws vary by state and are subject to amendment. Always verify with the latest official gazette.
- For any actual legal proceeding, **consult a qualified advocate** licensed with the Bar Council of India.
- The AI chat responses are **keyword-based guides**, not professional legal opinions.
- In an emergency, always call **112** first.

---

## 🙏 Acknowledgements

- **NALSA (National Legal Services Authority)** — For inspiring free legal aid for all
- **Ministry of Law and Justice, India** — For digitizing legal resources
- **Google Fonts** — For Noto Sans Devanagari, making Hindi beautiful on the web
- **All open-source contributors** who believe justice should be accessible to everyone
- **The Indian Constitution** — For Article 39A, which makes free legal aid a directive principle

---

<div align="center">

**Built with ❤️ for 1.4 billion Indians**

**From Mahek Agnihotri**

*"Equal Justice Under Law — समान न्याय, कानून के तहत"*

⚖️ **NyaySetu — न्याय सेतु** ⚖️

[⬆ Back to Top](#️-nyaysetu--न्याय-सेतु)

</div>
