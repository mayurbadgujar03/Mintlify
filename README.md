# Mintlify Landing Page Clone 🍃

A high-fidelity recreation of the [Mintlify.com](https://mintlify.com) landing page, built entirely with raw **HTML & CSS**. This project demonstrates precision in layout, semantic markup, and modern CSS techniques (Grid & Flexbox) to capture the clean, dark-mode aesthetic of modern developer tools.

## 🔗 Live Demo & Walkthrough

- **🟢 Live Website:** [https://mintlifyclonemay.netlify.app/](https://mintlifyclonemay.netlify.app/)
- **🎥 Video Walkthrough:** [VIDEO LINK HERE]

---

## 📝 Project Details

**Goal:** Recreate the visual hierarchy, structure, and responsiveness of the Mintlify documentation platform landing page.
**Constraints:** Desktop-first design, no JavaScript, no AI-generated code, no CSS frameworks (Tailwind/Bootstrap).

### 🏗️ Sections Recreated
I successfully cloned the following sections:
1.  **Sticky Navigation Bar:** Fixed position with glass-like transparency and hover effects.
2.  **Hero Section:** Centered typography, "New" badge pill, and background image overlay.
3.  **Partners Grid:** A responsive grid layout displaying logos of companies like Anthropic and Coinbase.
4.  **Intelligence & Assistant:** Feature blocks using Flexbox for alignment and card-based layouts.
5.  **Enterprise Section:** Complex layout combining vertical stacks, horizontal grids, and testimonials.
6.  **Customer Stories:** A horizontal scrollable card section (using `overflow: scroll`) to display case studies.
7.  **Documentation CTA:** Final call-to-action block with pricing and quickstart cards.
8.  **Footer:** extensive 5-column navigation layout with social links and copyright details.

---

## 🎨 Design System

### Fonts
- **Primary Font:** `Arial / Helvetica` (Sans-serif) - Clean, readable typography suitable for documentation tools.

### Color Palette
Focused on a high-contrast dark theme with Mintlify's signature green accents:

| Color | Hex Code | Usage |
| :--- | :--- | :--- |
| **Deep Background** | `#08090b` | Main body background |
| **Card Border** | `#79797938` | Subtle borders for feature cards |
| **Mint Green** | `#0c8c5e` | "New" badges, primary accents |
| **Bright Green** | `#13e198` | Section labels, highlights |
| **Text White** | `#ffffff` | Primary Headings |
| **Text Muted** | `#b4b6b6` | Paragraphs, footer links |
| **Button White** | `#ffffff` | Primary CTA buttons |

---

## 💻 Technical Highlights

- **Semantic HTML5:** Used `<header>`, `<main>`, `<section>`, `<nav>`, `<form>`, and `<footer>` for proper document structure.
- **Modern CSS Layouts:**
  - **CSS Grid:** Used extensively for the `partners` logo section and the `footer-container` (5-column layout).
  - **Flexbox:** Used for the `navbar`, `hero` alignment, and internal card structures.
  - **Positioning:** Used `position: sticky` for the header and `position: absolute` for background layers.
  - **Styling Details:** Custom scrollbar hiding (`scrollbar-width: none`), border-radius on cards, and transparency using RGBA/Hex-alpha values.

---
