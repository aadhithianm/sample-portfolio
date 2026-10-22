# ⚡ Ultra-Modern Developer Portfolio Template

A high-performance, single-file developer portfolio template featuring rich dark-mode aesthetics, fluid Lenis smooth scrolling, GSAP scroll triggers, an interactive particle constellation canvas, dynamic 3D card tilt, an interactive bash terminal CLI, and comprehensive responsiveness across all mobile, tablet, and desktop devices.

---

## ✨ Features & Architecture

- **Single-File Simplicity (`index.html`)**: Everything runs out-of-the-box with zero build steps or bundlers required. Simply double-click `index.html` or serve with any web server.
- **Buttery Smooth Inertia Scroll**: Integrated with **Lenis 1.1** for physics-based 60/120fps scrolling synchronized with **GSAP ScrollTrigger**.
- **Interactive Background**: HTML5 dynamic canvas rendering glowing star particles with real-time distance-based constellation networking.
- **Aesthetic Dark Mode & Glassmorphism**: Tailored HSL color palette with electric neon accents (`brand-500`, `cyan-400`, `emerald-400`, `purple-400`), backdrop blurs, and luminous borders.
- **3D Card Perspective Tilt**: Interactive physics tilt effect on mouse movement for cards and hero visuals.
- **Interactive Developer Console / Terminal**: Built-in interactive CLI with working commands (`whoami`, `skills`, `projects`, `contact`, `stack`, `clear`) and quick-run buttons.
- **Animated Metrics**: GSAP-driven numeric counters that count up smoothly upon entering viewport.
- **Project Filter & Modal Previews**: Filter projects by categories (SaaS, Web3/Fintech, AI) and click into interactive modal case studies with detailed technical milestones.
- **Functional Contact Form & Clipboard Integration**: Simulated transmission with loading spinner, validation, and a custom toast notification system. One-click "Copy Email" with instant toast feedback.
- **Mobile First & Fully Responsive**: Sleek slide-down glass navigation, touch-optimized interactions, and adaptive grid typography.

---

## 🛠️ Tech Stack & Dependencies

All dependencies are loaded via high-speed CDNs:

| Library | Version / Source | Purpose |
| :--- | :--- | :--- |
| **Tailwind CSS** | CDN + Custom Script Configuration | Utility-first styling, color tokens, animations & responsive classes |
| **GSAP 3** | 3.12.5 (cdnjs) | High-performance animation timelines and ScrollTrigger triggers |
| **Lenis Scroll** | 1.1.20 (unpkg) | Modern momentum / inertia smooth scrolling |
| **Lucide Icons** | Latest (unpkg) | Clean, lightweight SVG icons |
| **Google Fonts** | Plus Jakarta Sans, Space Grotesk, JetBrains Mono | Modern typography pairing |

---

## 🚀 Quick Start

### Option 1: Open Directly in Browser
Double-click `index.html` in your file explorer, or drag it into any web browser (Chrome, Edge, Safari, Firefox).

### Option 2: Run with Local Server
```bash
# Using Node.js
npm start

# OR using Python
npm run preview
# (Opens on http://localhost:3000)
```

---

## 🎨 How to Customize

1. **Personal Information**:
   - Open `index.html` and search for `Alex Carter` to replace with your own name.
   - Update your title, bio, email (`alex.carter.engineer@gmail.com`), and social links.
2. **Avatar & Project Images**:
   - Replace the files in the `assets/` directory:
     - `assets/avatar.jpg` (Hero profile photo / avatar)
     - `assets/project-1.jpg` (Project 1 case study screenshot)
     - `assets/project-2.jpg` (Project 2 case study screenshot)
     - `assets/project-3.jpg` (Project 3 case study screenshot)
3. **Projects & Skills**:
   - Edit the cards in `<section id="projects">` and `<section id="skills">`.
   - Update `projectDetails` in the `<script>` section to customize the interactive modal popups.
4. **Terminal Commands**:
   - Modify the `terminalCommands` object in `<script>` to add custom commands or easter eggs.

---

## 📄 License
MIT License. Free to use and customize for your personal and commercial portfolios!
