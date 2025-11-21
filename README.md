# 🌟 Estelle’s Astro Bento Portfolio

A modern, animated portfolio website built with **Astro**, inspired by and adapted from the original **Astro Bento** template by **Gianmarco Cavallo**.

**Live site:** *(add your final Vercel URL here once deployed)*

---

## 🚀 Features

- Fully responsive **bento-style** portfolio layout  
- Custom-designed cards for:
  - **Experience**
  - **Projects**
  - **Now / Time Zone**
  - **About Me**
- Individual content pages:
  - `/experience` — detailed internship + leadership breakdown  
  - `/projects` — research work + personal projects  
  - `/travel` — interactive 3D globe  
- Auto-updating **local time** clock  
- Fast, automatic deployment with **Vercel**

---

## 📁 Project Structure
## 📁 Project Structure

```plaintext
/
├── public/                     # Static assets (favicon, images, fonts)
│   ├── favicon.ico
│   ├── Estelle.jpg
│   └── globe_preview.webp
│
├── src/
│   ├── components/             # UI components
│   │   ├── Card/
│   │   ├── IntroCard.astro
│   │   ├── ExperienceCard.astro
│   │   ├── ProjectsCard.astro
│   │   ├── TimeZoneCard.astro
│   │   ├── Now.astro
│   │   ├── AboutMe.astro
│   │   ├── ContactsCard.astro
│   │   └── Globe/
│   │
│   ├── layouts/                # Page layouts
│   │   ├── Layout.astro
│   │   └── BasicLayout.astro
│   │
│   ├── pages/                  # Website pages / routes
│   │   ├── index.astro
│   │   ├── experience.astro
│   │   ├── projects.astro
│   │   ├── travel.astro
│   │   └── blog/
│   │       ├── index.astro
│   │       └── [id].astro
│   │
│   ├── lib/                    # Helper functions
│   │   ├── helpers.ts
│   │   └── constants.ts
│   │
│   └── data/                   # Static or JSON-like data sources
│
├── astro.config.mjs            # Astro configuration
├── package.json
├── tsconfig.json
└── README.md
---

## 🧑‍💻 Local Development

Install dependencies:

```bash
npm install

