# 📰 Asia Post — News Portal

A responsive, high-fidelity replica of the **[Asia Post](https://www.asia-post.com/)** digital news portal. This project reproduces high-density editorial layouts, asymmetric news grids, dedicated category feeds, and video gallery components using standard web technologies.

🔗 **Live Demo:** [https://naima006.github.io/Asia-Post/](https://naima006.github.io/Asia-Post/)

---

## 🎯 Architectural Overview

Digital publication platforms require consistent alignment across complex, dynamic layouts. This project focuses on:

- **Asymmetric Grid Composition:** 12-column editorial structure balancing primary breaking news, nested category columns, and sidebar widgets.
- **Multi-Page Workflows:** Independent templates for the main homepage, dynamic daily feed, and modular article detail views.
- **Multimedia Integration:** Dedicated video feature banners and responsive media card decks with hover-state overlays.
- **Layout Stability:** Fixed image aspect ratios and structured flexbox wrappers to prevent Cumulative Layout Shifts (CLS).

---

## 📂 Project Structure

```text
AsiaPost/
├── images/
│   ├── favicon-AP.png       # Application favicon
│   ├── logo.png             # Portal branding asset
│   ├── video-feature.jpg    # Lead video showcase thumbnail
│   ├── video1.jpg           # Secondary multimedia asset
│   ├── video2.jpg           # Secondary multimedia asset
│   └── video3.jpg           # Secondary multimedia asset
├── index.html               # Main homepage layout
├── todays-news.html         # Daily aggregated news feed
├── news-001.html            # Article detail template
└── style.css                # Custom CSS variables, resets & overrides

```

---

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
| --- | --- | --- |
| **Markup** | HTML5 | Semantic content structure (`<header>`, `<nav>`, `<article>`, `<section>`, `<footer>`) |
| **Styling** | CSS3, Bootstrap | Grid system, responsive utility classes, and custom layout design tokens |
| **Scripting** | Vanilla JavaScript | Dynamic navigation interactions, dropdown states, and DOM utilities |
| **Assets** | Custom Media & Assets | Editorial images, icon sets, and branding vector graphics |

---

## ⚡ Getting Started

### Prerequisites

A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

---

## 📄 License & Attribution

This codebase is developed for **educational and portfolio demonstration purposes**. All original news content, multimedia assets, and trademarks belong to the respective owners of **[Asia Post](https://www.asia-post.com/?utm_source=gemini)**.
