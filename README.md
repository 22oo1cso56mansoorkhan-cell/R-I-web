# Robotics & Innovation Club (R&I) — CBIT Website

Official, modern, and visually impressive static website for the **Robotics & Innovation (R&I) Club** of **Chaitanya Bharathi Institute of Technology (CBIT)**.

---

## 🚀 Key Features

- **Pure Static Stack**: Built strictly using **HTML5, CSS3, and Vanilla JavaScript**. No frameworks (No React, Next.js, Vue, Angular, Bootstrap, or Tailwind CSS).
- **Technical & Robotics Aesthetics**: Dark slate color palette (`#080B12`), electric cyan accents (`#00F0FF`), glowing neon highlights, clean typography (`Space Grotesk` & `Inter`), and subtle robotics grid visual accents.
- **Interactive Canvas & Animations**: Dynamic background hero particle network, smooth scroll reveals via `IntersectionObserver`, and animated numerical counters for achievements and stats.
- **Flagship Showcase — ROBOVANZA 10.0**: Dedicated feature section highlighting the 10th decennial edition, historical legacy timeline, and event categories.
- **Lightweight Lightbox & Dynamic Modals**: Pure Vanilla JS gallery lightbox with next/previous navigation and dynamic popup modals for project specs & competition rules.
- **Mobile Responsive**: Custom hamburger menu and responsive media query breakdowns for desktop, laptop, tablet, and mobile displays.
- **Accessibility & Motion Controls**: Respects system preferences (`prefers-reduced-motion`) and uses semantic HTML5 tags with proper ARIA attributes.

---

## 📁 File & Project Structure

```text
rni-club/
│
├── index.html              # Main HTML5 Document & Structure
│
├── css/
│   └── style.css           # Pure CSS Design System & Layouts
│
├── js/
│   └── script.js           # Vanilla JS Logic (Canvas, Modals, Lightbox, Scrollspy)
│
├── assets/
│   ├── images/
│   │   ├── logo.png        # R&I Emblem Logo
│   │   ├── hero.jpg        # Combat Robotics Hero Visual
│   │   ├── robovanza.jpg   # ROBOVANZA Flagship Arena Banner
│   │   ├── projects/       # Technical Project Images
│   │   ├── team/           # Executive & Team Vector Avatars (SVG)
│   │   └── gallery/        # Competition & Lab Photos
│   └── icons/
│
└── README.md               # Website Documentation
```

---

## 📌 Sections Included

1. **Header & Navigation**: Sticky blur glass bar, active scrollspy highlighting, mobile hamburger menu, and CTA button.
2. **Hero Section**: `ROBOTS. INNOVATION. IMPACT.`, subheadings, project links, combat bot visual, interactive particle canvas.
3. **About R&I**: Club background, core hands-on learning philosophy, combat robotics focus, and "What We Do" 6-card grid.
4. **Vision, Mission & Values**: Feature cards for Vision, Mission, and Core Values (Teamwork, Integrity, Determination, Collaborative Learning, Work Ethic).
5. **Projects**: Reusable card layout showcasing robotics domain projects with tech tags and modal popups.
6. **Achievements**: Medals & intercollegiate fests (Vasavi College Acumen 2026, GITAM Havana 2025, IIT Guwahati Techniche, BITS ATMOS, SNIST).
7. **ROBOVANZA 10.0**: 10th decennial celebration banner, statistics, and 2018–2026 legacy timeline.
8. **Events**: 6 main ROBOVANZA competitions (Robo Wars, Robo Soccer, Robo Sumo, Robo Rover, Line Follower, FPV Racing).
9. **Our Team**: Executive leadership (President Bhuvan Balaji, Vice President Yeshwanth Pullur, Treasurer M. Pranav) and subteam categories.
10. **Gallery & Lightbox**: Masonry image grid with category filter tabs and interactive lightbox modal.
11. **Outreach & Impact**: Footfall counters, colleges reached, prize worth, and 70%/30% demographic distribution bars.
12. **Why R&I**: 6 key value cards for prospective members.
13. **Contact**: Official email (`roboticscbit@gmail.com`), Instagram (`@robotics_cbit`), direct leadership phone contacts, and static contact form UI.
14. **Footer**: Brand links, quick navigation, social channels, and copyright notice.

---

## 💻 How to Run Locally

Since this is a 100% static website:
1. Double-click `index.html` to open directly in any modern Web Browser (Chrome, Firefox, Edge, Safari).
2. Alternatively, serve via a simple local server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser.

---

© 2026 Robotics & Innovation Club (R&I), CBIT. All Rights Reserved.
