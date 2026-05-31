# DJS01: Vanilla JS Podcast App

## Overview
This is a responsive web app that lets users **browse podcast shows** on a landing page and **view more details** in a pop-up modal. The previews show the key info for each show, and clicking one opens a modal with the full details — **all without leaving the page**. It's built with HTML, Tailwind CSS, and vanilla JavaScript.

---

## What It Does

### 1. Landing Page – Podcast Previews
Each podcast card on the landing page shows:
- Cover image (grey placeholder, since no images were provided)
- Show title
- Number of seasons
- Genre names
- Last updated date (in a readable format, e.g. "Updated 3 November 2022")

### 2. Modal View – Show Details
Clicking a card opens a modal that shows:
- Larger cover image
- Podcast title
- Description of the show
- Genre tags
- Last updated date
- List of season titles
- Number of episodes in each season

The modal can be closed by clicking the **×** button, clicking outside the modal, or pressing the **Escape** key.

### 3. Extra Features
- **Filter by genre** dropdown
- **Sort** dropdown (Recently Updated, Most Popular, Newest)
- Hover effects on the cards
- Fully responsive on desktop, tablet, and mobile

---

## Built With
- **HTML**
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript** (no page reloads — all rendering and the modal are handled in JS)

---

## How to Run
1. Download the project files.
2. Open `index.html` in your browser (or use the Live Server extension in VS Code).

---

## Deliverables
- A fully functional, responsive podcast preview web app.
- Clean, commented source code (HTML, CSS, JS).
