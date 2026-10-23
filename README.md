# Blood & Ink

### A dark, cinematic anime tribute website built with pure HTML and CSS

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-None-b3122b?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-2ea44f?style=for-the-badge)

---

## Table of Contents

1. [Overview](#overview)
2. [Preview](#preview)
3. [Features](#features)
4. [Tech Stack](#tech-stack)
5. [Project Structure](#project-structure)
6. [Getting Started](#getting-started)
7. [Design System](#design-system)
8. [Responsive Design](#responsive-design)
9. [Page Sections](#page-sections)
10. [What I Learned](#what-i-learned)
11. [Future Improvements](#future-improvements)
12. [Credits and Disclaimer](#credits-and-disclaimer)
13. [Author](#author)

---

## Overview

**Blood & Ink** is a one-page website that celebrates some of the most iconic characters in anime, including Goku, Luffy, Itachi, Gojo, Levi, Sukuna and Zoro. The site is styled like a digital art exhibition: a black canvas, ivory text and crimson "ink" accents.

The project was designed first on Wix and then rebuilt from scratch in clean, hand-written **HTML5** and **CSS3**. It uses no frameworks, no libraries and no JavaScript, to show how much can be achieved with core web fundamentals alone.

**Goals of the project**

- Practise semantic HTML and a clean, readable code structure
- Build a consistent visual identity using a limited colour palette
- Create layouts with Flexbox
- Make a page that works on both desktop and mobile screens

---

## Preview

> Add a screenshot of your website here before submitting.
> Save it as `screenshot.png` in the project folder, then replace this line with:
>
> `![Blood & Ink Preview](screenshot.png)`

---

## Features

- **Fixed navigation bar** that stays visible while scrolling
- **Full-screen hero banner** with an image overlay and character introduction
- **Character cards** with images, titles and descriptions
- **Hover animations** on cards, buttons and navigation links
- **"Domain Expansion" section** with a clean vertical list layout
- **Archive section** with a call-to-action button
- **Smooth scrolling** between sections
- **Fully responsive layout** using a media query
- **Zero dependencies**: no frameworks, no JavaScript, no build tools

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, Flexbox layout, hover effects, media queries |
| Visual Studio Code | Code editor |
| Live Server / Browser | Local testing |

---

## Project Structure

```
blood-and-ink/
│
├── index.html     # Page structure and content
├── style.css      # All styling and responsive rules
└── README.md      # Project documentation
```

---

## Getting Started

No installation is needed.

**Option 1: Open directly**

1. Download or clone the project folder.
2. Double-click `index.html`.
3. The website opens in your default browser.

**Option 2: Using VS Code with Live Server**

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and choose **Open with Live Server**.

**Clone with Git**

```bash
git clone https://github.com/your-username/blood-and-ink.git
cd blood-and-ink
```

> **Note:** The character images are loaded from online links, so an internet connection is required for them to appear.

---

## Design System

**Colour palette**

| Colour | Hex | Usage |
|--------|-----|-------|
| Ink Black | `#0d0d0f` | Main background |
| Charcoal | `#17171b` | Cards and alternate sections |
| Ivory | `#f3ecdc` | Main text |
| Ash Grey | `#b5ad9c` | Secondary text |
| Blood Red | `#b3122b` | Accents, buttons, highlights |

**Typography**

- Font family: Georgia (serif), chosen for a dramatic, editorial feel
- Wide letter spacing on headings for an exhibition-style look
- Uppercase labels for names and section titles

---

## Responsive Design

The layout adapts to different screen sizes:

- **Desktop:** horizontal navbar, multi-column card layout
- **Tablet:** cards wrap automatically using `flex-wrap`
- **Mobile (below 700px):** navbar stacks vertically, hero heading shrinks, archive images stack in a single column

---

## Page Sections

| Section | Description |
|---------|-------------|
| **Navbar** | Fixed menu with Home, Exhibition, About and Portfolio links |
| **Banner** | Full-screen introduction featuring Son Goku |
| **The Vanguard** | Four character cards: Luffy, Itachi, Gojo and Levi |
| **Domain Expansion** | Gojo, Sukuna and Zoro in a vertical showcase |
| **Archive** | Image gallery, heading and "Enter the Archive" button |
| **Footer** | Quick links, social links and site name |

---

## What I Learned

- Structuring a web page with semantic HTML elements
- Building flexible layouts with Flexbox
- Positioning elements with `fixed`, `relative` and `absolute`
- Layering an image with a gradient overlay for readability
- Writing a media query for mobile-friendly design
- Keeping a project organised with separate HTML and CSS files
- Documenting a project professionally with a README

---

## Future Improvements

- [ ] Add a working image slider for the hero banner using JavaScript
- [ ] Create separate Exhibition, About and Portfolio pages
- [ ] Add a hamburger menu for mobile navigation
- [ ] Store images locally for offline use
- [ ] Add a dark/light theme toggle
- [ ] Add a contact form
- [ ] Improve accessibility with ARIA labels and keyboard focus styles
- [ ] Deploy the site using GitHub Pages

---

## Credits and Disclaimer

Blood & Ink is a **non-commercial fan tribute** created for learning and portfolio purposes. All anime characters, names and related artwork belong to their respective creators, studios and rights holders. This project claims no ownership over them.

- Original concept and first version designed on Wix
- Rebuilt in HTML and CSS by the author
- Typography: Georgia (system font)

---

## Author

**Atharv Singh**
B.Tech Computer Science and Engineering (First Year)

- GitHub: [your-username](https://github.com/your-username)
- Email: your-email@example.com

---

<p align="center">Made with HTML, CSS and a love for anime.</p>
