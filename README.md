# 🌐 DecodeLabs — Project 1: Static Webpage Design

> **Frontend Development Industrial Training Kit — Batch 2026**  
> Powered by [DecodeLabs](https://www.decodelabs.tech)

---

## 📌 About The Project

This project is the **first milestone** of the DecodeLabs Frontend Development training program. It focuses on the structural foundation of web development: building a clean, semantic, and visually consistent **static webpage** using only HTML and CSS.

The goal is not visual complexity — it is **Semantic Integrity**: mastering the fundamental relationship between content and style before moving into dynamic, JavaScript-driven applications.

---

## 🎯 Project Objective

Design and build a fully static, multi-section webpage for **DecodeLabs** — a coding education platform — that demonstrates:

- Proper use of semantic HTML structure
- CSS layout engineering with Flexbox and CSS Grid
- Clean, readable visual design
- Separation of concerns (HTML for structure, CSS for appearance)

---

## 🗂️ Project Structure

```
project-1/
│
├── index.html          # Main HTML file — full page structure
├── style.css           # External stylesheet — all visual styling
└── assets/
    ├── photos/         # Page images (main.jpg, pic1–pic6.jpg)
    └── icons/          # SVG icons (logo, social media, contact)
```

---

## 🧱 Page Architecture

The page is built following a logical **Information Architecture (IA)** with clear landmark regions:

| Section | HTML Element | Description |
|---|---|---|
| **Header / Nav** | `<header>` | Logo + navigation bar with 4 links |
| **Hero** | `<section>` | Full-viewport banner with background image and CTA button |
| **Subtitle** | `<div>` | Colored band with section heading |
| **Content Grid** | `<main>` | 6 cards laid out in a CSS Grid (4 columns × 2 rows) |
| **Footer** | `<footer>` | Contact info, navigation links, and about text |

---

## ✨ Key Features

- **Semantic HTML5** — uses `<header>`, `<nav>`, `<section>`, `<main>`, `<footer>` for machine-readable structure
- **CSS Grid layout** — 4-column, 2-row grid with intentional card spanning (cards n1 and n6 span 2 columns)
- **Flexbox** — used inside the header, footer columns, and card content for micro-alignment
- **Fixed background parallax** — hero section uses `background-attachment: fixed` for a depth effect
- **Hover transitions** — buttons and cards have smooth `0.3s linear` transitions
- **External CSS only** — strict separation of concerns, zero inline styles
- **Responsive-ready color system** — consistent brand color `#275971` throughout all components

---

## 🃏 Content Cards

The main grid features 6 learning topic cards:

1. **Learn How To Code Step By Step** — beginner-friendly curriculum
2. **Setup Your Coding Environment** — local workspace and developer tools
3. **Learn How To Debug** — troubleshooting and error solving
4. **Team Up With People** — collaboration and team workflows
5. **Dive Into Web Development** — building and deploying web apps
6. **Build Real-World Applications** — production-ready project development

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary color | `#275971` (teal-blue) |
| Accent (button hover) | `#ff2c84` / `#ff5722` |
| Background light | `#eaeaea` |
| Text on dark | `whitesmoke` / `floralwhite` |
| Font family | Franklin Gothic Medium, Arial Narrow, Arial |
| Card border radius | `5px` |
| Card shadow | `2px 1px 6px 0.5px gray` |
| Transition | `0.3s linear` |

---

## ✅ Requirements Checklist (DecodeLabs Flight Checklist)

- [x] **IA** — Logical sitemap defined before coding
- [x] **HTML** — Semantic tags (`<header>`, `<main>`, `<footer>`), single `<h1>`
- [x] **CSS** — External file only, DRY principle applied (reusable `.card`, `.card-description`, `.img-frame` classes)
- [x] **Layout** — CSS Grid for macro page structure, Flexbox for component alignment
- [x] **Assets** — Photos and SVG icons properly referenced
- [x] **Separation of concerns** — No inline styles, HTML and CSS fully decoupled

---

## 🚀 How To Run

No build tools or dependencies required. Simply open the project in your browser:

```bash
# Clone or download the project
git clone https://github.com/your-username/decodelabs-project1.git

# Open in browser
open index.html
# or just double-click index.html in your file explorer
```

> ⚠️ Make sure the `assets/` folder is present alongside `index.html` for images and icons to load correctly.

---

## 📚 Concepts Practiced

| Concept | Application in this project |
|---|---|
| Semantic HTML | `<header>`, `<nav>`, `<section>`, `<main>`, `<footer>` |
| CSS Grid | Card layout with `grid-column` / `grid-row` spanning |
| Flexbox | Header, footer columns, card content alignment |
| Box Model | Margins, paddings, and borders on all components |
| CSS Selectors | ID selectors for layout, class selectors for reusable components |
| Pseudo-elements | `::before` on hero section for overlay effect |
| CSS Transitions | Hover states on buttons and cards |
| Background properties | `background-attachment: fixed`, `background-size: cover` |

---

## 🏅 Badge

> Completing this project earns the **Project 1: Static Webpage Design** badge from DecodeLabs and unlocks access to the next training projects.

---

## 👤 Author

Built as part of the **DecodeLabs Frontend Development Industrial Training Program — Batch 2026**.

- 🌐 [www.decodelabs.tech](https://www.decodelabs.tech)
- 📧 decodelabs.tech@gmail.com
- 📞 +91 89330 06408
- 📍 Greater Lucknow, India

---

*"Build it well, for the frontend is the only part of the system the world will ever see." — DecodeLabs*
