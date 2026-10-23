# B/INK — Blood & Ink

> A dark, editorial anime exhibition website built with pure HTML5 and CSS3.

---

## Overview

*Blood & Ink (B/INK)* is a single-page digital exhibition celebrating iconic figures in modern anime—including Son Goku, Monkey D. Luffy, Itachi Uchiha, Gojo Satoru, Levi Ackerman, Ryomen Sukuna, and Roronoa Zoro.

Styled with the aesthetics of an editorial art gallery, the site pairs an obsidian and charcoal backdrop with stark ivory typography and deep crimson ink accents. Originally conceived as a visual concept on Wix, the project was rebuilt from the ground up using clean, handcrafted *HTML5* and *CSS3*—completely free of frameworks, libraries, and JavaScript.

---

## Design System

The visual identity relies on a high-contrast palette and deliberate typographic rhythm to evoke an atmospheric, museum-grade aesthetic.

### Palette

| Role | Color | Hex | Description |
|:-----|:------|:----|:------------|
| *Canvas* | Obsidian | #0d0d0f | Primary background canvas |
| *Surface* | Charcoal | #17171b | Cards, panels, and alternate sections |
| *Accent* | Crimson | #b3122b | Branding, borders, tags, and highlights |
| *Primary Text* | Ivory | #f3ecdc | Headings, titles, and high-emphasis body text |
| *Muted Text* | Ash Grey | #b5ad9c | Subtitles, character lore, and timestamps |

### Typography & Styling
- *Typeface:* Georgia (editorial serif) for a timeless, book-bound exhibition tone.
- *Tracking:* Generous letter-spacing (up to 3px) across uppercase labels, badge tags, and subheaders.
- *Interactions:* Subtle card elevations (translateY(-6px)), smooth native scrolling, and color transitions on hover.

---

## Exhibition Sections

1. *Fixed Header (B/INK)* — Minimalist sticky bar with quick-navigation anchor links.
2. *Hero Feature (Son Goku)* — Full-viewport hero banner spotlighting The Saiyan Spirit with layered image contrast and exhibition index numbering (01 / 12).
3. *The Vanguard* — Gallery grid displaying featured protagonists and anti-heroes:
   - *Monkey D. Luffy* (Dream On)
   - *Itachi Uchiha* (Witness)
   - *Gojo Satoru* (Infinity)
   - *Levi Ackerman* (Salute)
4. *Domain Expansion* — Typographic roster spotlighting signature powers and character titles across Gojo Satoru, Ryomen Sukuna, and Roronoa Zoro.
5. *Collective Arc & Archive* — Dual-image visual spread, exhibition call-to-action, and curator contact index.
6. *Footer* — Global directory links and social media channels.

---

## Project Structure


B-INK/
├── index.html     # Semantic document structure and content
├── style.css      # Design tokens, layout rules, and media queries
└── README.md      # Repository overview


---

## Running Locally

Because this project uses vanilla web standards with zero dependencies or build pipelines, running it requires no package managers.

### 1. Clone the repository
bash
git clone https://github.com/OPTIMUS1002/B-INK.git
cd B-INK


### 2. View the site
Open index.html directly in your browser of choice:
- *Direct:* Double-click index.html or drag it into Chrome / Firefox / Edge / Safari.
- *VS Code:* Right-click index.html and select *Open with Live Server*.
- *Terminal (npx):*
  bash
  npx serve .
  

> Note: Image assets are served via high-resolution CDN links; an active internet connection is required for external artwork to display.

---

## Responsive Breakpoints

The layout uses CSS Flexbox with fluid widths and a responsive media breakpoint at 700px:
- Desktop: Full multi-column card displays, side-by-side gallery archive, and inline navigation.
- Mobile (<= 700px): Collapsed vertical navigation, responsive headline typography scaling (42px), and single-column image stacks.

---

## Credits & Disclaimer

- *Author:* [Atharv Singh](https://github.com/OPTIMUS1002)
- *Concept:* Conceived on Wix; engineered in HTML5/CSS3.
- *Disclaimer:* Blood & Ink is an educational, non-commercial fan tribute. All characters, names, and artwork are the intellectual property of their respective creators and animation studios (Toei Animation, MAPPA, Wit Studio, Studio Pierrot, and respective authors).
