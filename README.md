# 🌐 HashHorizon — Responsive Landing Page Design

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive Design](https://img.shields.io/badge/Responsive-Design-28a745?style=for-the-badge&logo=responsive&logoColor=white)](#responsive-design)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

> **From hash to horizon, chart the future of trustless tech.**  
> A sleek, modern, and fully responsive Web3 & Blockchain landing page built purely with semantic **HTML5** and custom **CSS3**.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Page Sections](#-page-sections)
- [Responsive Design](#-responsive-design)
- [Tech Stack](#-tech-stack)
- [Folder Structure](#-folder-structure)
- [Getting Started](#-getting-started)
- [How to Customize](#-how-to-customize)
- [Roadmap & Enhancements](#-roadmap--enhancements)
- [Author](#-author)
- [License](#-license)

---

## 🚀 Overview

**HashHorizon** is a modern landing page designed to showcase blockchain infrastructure, Web3 innovation, decentralized networks, and digital transformation services. 

Built with clean, lightweight vanilla code without external CSS frameworks or heavy dependencies, this project demonstrates best practices in semantic HTML structuring, modern CSS Flexbox layouts, interactive UI elements, and responsive cross-device compatibility.

---

## ✨ Key Features

- **📱 Fully Responsive**: Flawless display across desktops, laptops, tablets, and smartphones using CSS media queries.
- **🎨 Modern UI/UX**: Clean color palette, modern typography, card hover states, and smooth transition effects.
- **⚡ High Performance**: Fast load times powered by lightweight vanilla HTML/CSS and optimized modern image formats (`.svg`, `.webp`, `.avif`).
- **🧩 100% Pure CSS Layouts**: Structured using CSS Flexbox for fluid alignment and adaptive wrap behavior without bloated frameworks.
- **📬 Interactive Elements**:
  - Hover animations on buttons and navigation links.
  - Interactive cards with dynamic shadow and transform effects.
  - Functional contact form layout with input fields and message area.
  - Newsletter subscription form in the footer.

---

## 📑 Page Sections

1. **Navigation Bar**: Clean header with brand logo, quick navigation links (*Home*, *Blog*, *Community*, *Services*), and a prominent *"Register Now"* call-to-action (CTA) button.
2. **Hero / Banner**: Eye-catching headline, product value proposition, primary action button, and a thematic hero illustration.
3. **Clients / Social Proof**: Trusted partner showcase displaying client logos in a clean row.
4. **Blockchain Sectors (Features)**: Three-column highlight cards showcasing key impact sectors:
   - *Creator Communities* (NFTs & direct audience engagement)
   - *Financial Institutions* (Decentralized, secure transactions)
   - *Supply Chain Management* (Global traceability & transparency)
5. **Impact & Metrics (Stats)**: Dynamic counters highlighting milestone metrics:
   - 120+ Blockchain Networks
   - 420,000+ Smart Contracts
   - $150 Billion+ Total Value Locked (TVL)
   - 1,245,000+ Active Wallets
6. **Future of Blockchain (Insights)**: Media card grid exploring trends, banking solutions, transparency, and Web3 applications with *"Read more"* links.
7. **Contact Us**: Two-column contact section featuring an illustrative visual paired with an inquiry form (Name, Email, Message).
8. **Footer**:
   - Company branding, social media handles (Facebook, Instagram, Twitter/X, LinkedIn), and copyright statement.
   - Quick navigation links for *Company* and *Support*.
   - Inline email newsletter subscription field.

---

## 📱 Responsive Design

The stylesheet includes dedicated `@media (max-width: 768px)` breakpoints ensuring optimal accessibility on mobile and tablet screens:

- **Navbar**: Transitions from a horizontal bar into an aligned column layout with mobile-friendly button sizing.
- **Hero & Content Sections**: Flex containers automatically wrap into vertical flows to prevent horizontal scrolling.
- **Cards & Stats**: Multi-column grids and cards stack vertically with comfortable spacing for touch targets.
- **Contact Form & Footer**: Column widths expand to full width (`100%`) for smooth reading and easy tapping on small screens.

---

## 🛠 Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure and accessibility |
| **CSS3** | Custom styling, Flexbox layout, animations, and media queries |
| **Vector Graphics (SVG)** | Crisp, scalable icons and brand logos |
| **Modern Image Formats (WebP / AVIF / PNG)** | High-resolution, lightweight visuals |

---

## 📁 Folder Structure

```text
Responsive-Landing-Page-Design/
├── card image/          # Images used for feature and blog cards (.webp, .png)
│   ├── ca-1.webp
│   ├── ca-2.png
│   └── ca-3.webp
├── icon/                # Section feature icons (.svg)
│   ├── i-1.svg
│   ├── i-2.svg
│   └── i-3.svg
├── img/                 # Partner and client logos (.svg)
│   ├── c-1.svg - c-6.svg
├── logo/                # Statistics and metric icons (.svg)
│   ├── l-1.svg - l-4.svg
├── media/               # Footer icons & social links (.svg)
│   ├── face.svg, insta.svg, twi.svg, link.svg, plane.svg, logo.svg
├── photo/               # Main hero graphic, contact photo, and main logo
│   ├── png-1.png
│   ├── cont.avif
│   └── logo.svg
├── index.html           # Main HTML document
├── style.css            # Primary stylesheet
└── README.md            # Project documentation
```

---

## 🚀 Getting Started

No build tools, package managers, or compilers are required. You can run this project locally in seconds:

### 1. Clone the repository
```bash
git clone https://github.com/Maruf-Ahmed-11/Responsive-Landing-Page-Design.git
```

### 2. Navigate to the project directory
```bash
cd Responsive-Landing-Page-Design
```

### 3. Open in your browser
- Simply double-click `index.html` to open it in your default web browser.
- **Or** if you use **Visual Studio Code**, right-click `index.html` and select **"Open with Live Server"**.

---

## 🎨 How to Customize

- **Color Scheme**: Update primary colors (e.g. `#EAEFEF`, `#F1EFEC`, and accent blues `rgb(10, 168, 221)`) inside [style.css](style.css).
- **Typography**: Modify `font-family: Arial, sans-serif;` in `style.css` to link custom fonts (such as Google Fonts: *Inter*, *Poppins*, or *Roboto*).
- **Content & Images**: Replace placeholder texts, stats, and images in [index.html](index.html) and their corresponding folders (`/photo`, `/img`, `/card image`).

---

## 🔮 Roadmap & Enhancements

- [ ] Add a hamburger menu toggle with JavaScript for mobile navigation.
- [ ] Implement smooth scroll behavior for anchor links.
- [ ] Add client-side validation to the Contact and Newsletter forms.
- [ ] Include Dark/Light mode theme toggle.
- [ ] Add scroll-triggered animations (e.g., AOS or CSS Intersection Observer).

---

## 👨‍💻 Author

**Maruf Ahmed**
- GitHub: [@Maruf-Ahmed-11](https://github.com/Maruf-Ahmed-11)
- Repository: [Responsive-Landing-Page-Design](https://github.com/Maruf-Ahmed-11/Responsive-Landing-Page-Design)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it for personal and commercial projects.

