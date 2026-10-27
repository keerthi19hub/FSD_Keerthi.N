# 🌐 Full-Stack Web Engineering — Modern Frontend, Backend APIs & Responsive Applications

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1E1E2E,4C4F69,7287FD&height=220&section=header&text=Full-Stack%20Web%20Engineering&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Modern%20Frontend%2C%20Backend%20APIs%20%26%20Responsive%20Applications&descSize=18&descAlignY=60&descAlign=50" width="100%" alt="Full Stack Web Engineering Banner" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Language-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Language-JavaScript%20(ES6+)-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Scope-35+%20Interactive%20Modules-7287FD?style=for-the-badge" alt="35+ Modules" />
  <img src="https://img.shields.io/badge/Focus-DOM%20Manipulation%20%26%20UI%20Design-1E1E2E?style=for-the-badge" alt="DOM & UI" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

---

## 📌 Table of Contents

- [📖 Executive Summary](#-executive-summary)
- [🧩 Laboratory Curriculum & Exercise Taxonomy](#-laboratory-curriculum--exercise-taxonomy)
- [✨ Key Technical Domains Explored](#-key-technical-domains-explored)
- [🏗️ Client-Side Web Architecture](#️-client-side-web-architecture)
- [🛠️ Tech Stack Matrix](#️-tech-stack-matrix)
- [⚙️ Reproducible Quickstart & Setup](#️-reproducible-quickstart--setup)
- [📁 Project Structure](#-project-structure)
- [👩‍💻 Author & Academic Context](#-author--academic-context)

---

## 📖 Executive Summary

The **Full-Stack Development (FSD) Laboratory** documents an extensive hands-on web engineering journey comprising **35+ production-oriented practical exercises** developed at **Alliance University**. Tracing the evolution from semantic HTML5 markup and responsive CSS3 layouts (Flexbox, Grid, Media Queries) to modern dynamic JavaScript (ES6+), DOM manipulation, client-side state handling, event-driven calculators, and authentication UI clones, this repository demonstrates foundational and applied web engineering craftsmanship.

---

## 🧩 Laboratory Curriculum & Exercise Taxonomy

| Module Category | Source Files | Key Concepts & Techniques |
| :--- | :--- | :--- |
| **Authentication & Portals** | `Alliance_Login_Form.html`, `Facebook_Login_Form.html`, `Instagram_Login_Page.html` | Semantic form controls, input grouping, floating labels, CSS shadow layers |
| **DOM & Dynamic Rendering** | `DOM in js.html`, `Digital Clock using js.html`, `tables using js.html` | `document.querySelector`, `setInterval`, dynamic table node creation |
| **Event-Driven Calculators** | `calcii_marriage_js.html`, `calculator_page.html` | Keyboard/mouse click event handlers, arithmetic expression evaluation |
| **Data Modeling in JS** | `arrays & objects in js.html`, `Fruits(array)_company(obj) in js.html` | ES6 Array methods (`map`, `filter`), object literal serialization |
| **Control Flow & Logic** | `loops in js.html`, `Switch statements in js.html`, `conditions in js.html` | Multi-conditional branching, loop iterations, truthy/falsy evaluation |
| **Responsive Web Layouts** | `RWD.html`, `navbar.html`, `Netflix.html` | Mobile-first CSS media queries, responsive navbar toggle, hero landing banners |
| **Foundational Concepts** | `Basics and variables in js.html`, `Functions.html`, `Eligibility for voting.html` | Variable scoping (`let`, `const`, `var`), arrow functions, closure basics |

---

## ✨ Key Technical Domains Explored

- **🎨 Modern Responsive UI Design:** Engineered responsive page clones (Netflix hero page, university timetable, multi-tier login portals) utilizing Flexbox and CSS media queries.
- **⚡ Reactive DOM Manipulation:** Constructed real-time digital clocks (`Date` objects, `setInterval`), reactive calculators, and dynamic table generation without third-party frameworks.
- **🔒 Form Validation & Input Sanitization:** Client-side input validation, password field toggling, and boundary checks for voting eligibility.

---

## 🏗️ Client-Side Web Architecture

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    Client-Side Web Engineering Layers                       │
└─────────────────────────────────────────────────────────────────────────────┘
                                       │
     ┌─────────────────────────────────┼────────────────────────────────┐
     ▼                                 ▼                                ▼
┌─────────────────────────┐ ┌─────────────────────────┐ ┌───────────────────────────┐
│ Structure Layer (HTML5) │ │ Presentation Layer(CSS3)│ │ Behavioral Layer (JS ES6) │
│ - Semantic Tagging      │ │ - Responsive Media Query│ │ - Event Listeners (DOM)   │
│ - Accessible Form Con.  │ │ - Flexbox / CSS Grid    │ │ - State & Timers          │
└─────────────────────────┘ └─────────────────────────┘ └───────────────────────────┘
```

---

## 🛠️ Tech Stack Matrix

| Domain | Technology | Implementation Details |
| :--- | :--- | :--- |
| **Markup** | HTML5 | Semantic elements (`<header>`, `<nav>`, `<main>`, `<form>`, `<input>`) |
| **Styling** | CSS3 | Responsive Web Design (RWD), Flexbox, Box Model, Transitions |
| **Scripting** | JavaScript (ES6+) | DOM traversal, event listeners, timer APIs, closures, object literals |
| **Tooling** | Modern Web Browsers | Chrome DevTools, responsive viewport debugging |

---

## ⚙️ Reproducible Quickstart & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/keerthi19hub/FSD_Keerthi.N.git
cd FSD_Keerthi.N
```

### 2. View in Browser
Every exercise is fully self-contained with embedded styles and scripts. Open any file directly in Google Chrome, Firefox, or Edge:
```bash
# On Windows
start "Alliance_Login_Form.html"
start "Digital Clock using js.html"
start "Netflix.html"

# On macOS
open "Alliance_Login_Form.html"

# On Linux
xdg-open "Alliance_Login_Form.html"
```

---

## 📁 Project Structure

```text
FSD_Keerthi.N/
├── Alliance_Login_Form.html        # Institutional student login portal clone
├── Facebook_Login_Form.html        # Social authentication layout
├── Instagram_Login_Page.html       # Responsive mobile auth design
├── Netflix.html                    # Video streaming platform landing hero layout
├── Digital Clock using js.html     # Real-time interval digital clock
├── DOM in js.html                  # DOM tree selection and manipulation demo
├── Event handlers in js.html       # Click, mouseover, and keypress listeners
├── calcii_marriage_js.html         # Interactive calculator with event handling
├── calculator_page.html            # Grid-based mathematical calculator
├── Fruits(array)_company(obj)...   # JS object structures and array operations
├── RWD.html                        # Responsive Web Design demonstration
├── navbar.html                     # Flexbox navigation bar
└── README.md                       # Production technical documentation
```

---

## 👩‍💻 Author & Academic Context

**Keerthi N**  
- **GitHub:** [@keerthi19hub](https://github.com/keerthi19hub)  
- **Portfolio:** [keerthi19hub.github.io](https://keerthi19hub.github.io)  
- **Course:** Full-Stack Development (FSD) · Alliance University, Bengaluru  
- **Role:** Designed, coded, and tested all 35+ HTML5/CSS3/JavaScript web modules.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1E1E2E,4C4F69,7287FD&height=100&section=footer" width="100%" alt="Footer Banner" />
</p>
