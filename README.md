# STUDENT PORTFOLIO PROJECT

## Project Description

<img width="1713" height="1023" alt="image" src="https://github.com/user-attachments/assets/ebe9babb-68fb-489f-aabb-eeba154bd094" />

### Introduction
This project is a multi-page personal student portfolio built to showcase technical skills, featured programming languages, academic background, and contact details. You can view the live project here: Kakarl's Portfolio.

### Problem and Its Setting
The portfolio provides an interactive and structured platform for presenting software engineering concepts and web development progress.
- Responsive sticky header navigation across all pages
- Dynamic skill card routing to dedicated language detail pages
- Clean typography and custom CSS variable theme styling
- Cross-device layout adaptation for desktop and mobile viewports
- C++ Programming language deep-dive
- HTML5 structural web standards
- CSS3 styling and responsive layout techniques
-Dedicated About Me and Contact pages

## Tech Stack

|Front-End|Back-End|Incharge|
|---------|--------|--------|
|HTML|-|Karlynn Lorah A. Ballenas|
|CSS|-|Karlynn Lorah A. Ballenas|

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Karlynn Lorah Ballenas | Student Portfolio </title>
    <link rel="stylesheet" href="global.css">
</head>
```

```css
:root {
  --primary-color: #ff6d91;
  --primary-hover: #e02454;
  --bg-body: #ffcbcb;
  --bg-card: #fff6e1;
  --text-main: #4b0c1c;
  --text-muted: #64748b;
  --font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  --spacing-unit: 1rem;
}

.img {
  border-radius: 50px
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}
```
## Features
- **Sticky Responsive Header Navigation:** A top navigation bar (.site-header) that remains fixed while scrolling across all pages with adaptive fluid scaling for mobile screens.
- **Multi-Page Web Architecture:** Organized across dedicated pages including index.html, about.html, contact.html, cpp.html, html.html, and css.html.
- **Interactive Skill Cards:** Clickable grid cards on the home page that trigger JavaScript routing (openPage()) to redirect visitors directly to language detail pages.
- **Section Jump Navigation:** Uses hash links (index.html#skills) with scroll-margin-top CSS offsets to jump cleanly to specific sections without being obscured by the sticky header.
- **Responsive Mobile-First Fluid Design:** Built with Flexbox, CSS clamp(), and @media (max-width: 768px) queries to fit desktop monitors and narrow mobile phone aspect ratios.
- **Custom Color Palette & Theme System:** Powered by CSS custom properties (:root variables) driving a cohesive rose theme with high contrast.
- **Centered Action Controls:** Styled navigation buttons (.back-btn) featuring hover transitions (translateY) for effortless returning to the landing page.

## Installation/Setup
### Setup & Local Development

1. **Clone the Repository:**
```
https://rvyei.github.io/MY-PORTFOLIO/
```
2. **Navigate into the Project Folder:**
```
cd MY-PORTFOLIO
```
3. **Run Locally:**
Open index.html in any web browser or use VS Code Live Server.

## Usage
1. Open https://rvyei.github.io/MY-PORTFOLIO/ in any desktop or mobile browser.
2. Use the sticky header navigation to jump between Home, About, Skills, and Contact pages.
3. Click on any language card (C++, HTML, or CSS) on the skills section to view dedicated code details and documentation.
4. Click the centered ← Back to Home button on sub-pages to return to the main dashboard.

## Challenges & Key Learnings
