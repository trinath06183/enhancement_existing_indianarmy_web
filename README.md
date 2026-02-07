# enhancement_existing_indianarmy_web
Modern Indian Army Landing Page

# 🇮🇳 Indian Army - Tactical Landing Page

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)
![Tech](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-orange?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

> A modern, high-performance tribute landing page for the Indian Army, featuring a "Glassmorphism" UI, tactical dark mode, and 3D interactive elements.

## 📖 Overview

This project is a redesign of a standard military website into a modern, immersive experience. It moves away from blocky, dated layouts and introduces current web design trends like **Glassmorphism (Frosted Glass)**, **Parallax Scrolling**, and **Masonry Grid Layouts**, all while maintaining a respectful and professional military aesthetic.

The entire project is built in a **single file structure** (HTML + Internal CSS + Internal JS) for easy portability and zero dependencies.

## ✨ Key Features

### 🎨 UI/UX Design
* **Glassmorphism Cards:** Uses `backdrop-filter: blur()` to create a premium frosted glass look for information cards.
* **Tactical Dark Mode:** A toggleable "Night Ops" mode that switches the color palette from standard official colors to a high-contrast dark camo theme using CSS Variables.
* **Masonry Gallery:** A mosaic-style image gallery using CSS Multi-column layout, moving away from rigid grid structures.
* **Parallax Hero:** A fixed background attachment in the header creates a depth effect while scrolling.

### ⚡ Interactivity & Animation
* **Scroll Reveal:** Elements fade in and slide up as the user scrolls down, powered by the **Intersection Observer API** (No heavy scroll event listeners).
* **3D Tilt Effect:** A custom JavaScript physics script that tilts the Recruitment cards in 3D space based on the mouse cursor position.
* **Glitch Effect:** A CSS-only text glitch animation on the main headline for a modern, digital-warfare feel.

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5
* **Styling:** CSS3 (Variables, Flexbox, Grid, Transforms, Transitions)
* **Logic:** Vanilla JavaScript (ES6+)
* **Fonts:** Google Fonts ('Rajdhani' for headers, 'Playfair Display' for titles)
* **Dependencies:** None (0 external libraries)

## 🚀 How to Run

1.  **Clone the repository** (or download the file):
    ```bash
    git clone [https://github.com/your-username/indian-army-site.git](https://github.com/your-username/indian-army-site.git)
    ```
2.  **Open the file:**
    Simply double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

## 🎨 Customization

The entire site is controlled by **CSS Variables** in the `:root` of the `<style>` section. You can easily change the theme colors here:

```css
:root {
  /* Light Mode Colors */
  --primary: #0F3D2E;      /* Change Primary Color */
  --accent: #FF9933;       /* Change Accent Color */
  
  /* Glass Effect Settings */
  --bg-card: rgba(255, 255, 255, 0.85);
  --border-card: rgba(255, 255, 255, 0.6);
}
