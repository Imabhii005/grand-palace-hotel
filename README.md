# Grand Palace Hotel — Static Website

Production-ready luxury hotel website. Pure HTML, CSS, JavaScript. No build tools, no npm, no server required.

## Folder Structure

```
grand-palace-hotel/
├── index.html               ← Open this in any browser — works immediately
├── style.css                ← All CSS (variables, grid, animations, responsive)
├── script.js                ← All JavaScript (scroll-reveal, nav, form)
├── assets/
│   ├── images/
│   │   ├── hero.jpg         ← Hero fullscreen background
│   │   ├── lobby.jpg        ← About section — hotel lobby
│   │   ├── signature.jpg    ← About section — signature
│   │   ├── room1.jpg        ← Deluxe King Room
│   │   ├── room2.jpg        ← Executive Suite
│   │   ├── room3.jpg        ← The Royal Penthouse
│   │   ├── gallery1.jpg     ← Gallery — hotel entrance
│   │   ├── gallery2.jpg     ← Gallery — infinity pool
│   │   ├── gallery3.jpg     ← Gallery — fine dining
│   │   └── gallery4.jpg     ← Gallery — suite
│   └── icons/               ← (reserved for custom icon assets)
└── README.md
```

## Deploy to GitHub Pages (3 steps)

1. Create a new repository on GitHub and upload this folder's contents.
2. Go to **Settings → Pages → Source** → select `Deploy from a branch` → `main` → `/` (root).
3. Click **Save**. Your site is live at `https://<username>.github.io/<repo-name>`.

No build step. No npm install. No environment variables.

## Local Preview

Double-click `index.html` — it opens directly in any browser.

## Sections

| Section | Description |
|---|---|
| Sticky Navigation | Glassmorphism on scroll, mobile hamburger |
| Hero | Fullscreen image, animated headline, CTA |
| About | Heritage story, lobby photo, decorative badge |
| Rooms & Suites | 3 cards with hover zoom and price |
| Amenities | Spa, Pool, Dining, Transfer, WiFi, Concierge |
| Gallery | Responsive masonry grid (4 images) |
| Testimonials | 3 guest reviews with star ratings |
| Contact | Form + address, phone, email |
| Footer | Quick links, social links, copyright |

## Tech Stack

- Pure **HTML5** — semantic, accessible, SEO-friendly
- Pure **CSS3** — custom properties, CSS grid, flexbox, keyframe animations
- Pure **JavaScript** — IntersectionObserver, smooth scroll, sticky nav, hamburger, form
- **Google Fonts** (CDN) — Cormorant Garamond + Inter
- All **images bundled locally** in `assets/images/`

## Customise

| What | Where |
|---|---|
| Gold color / palette | `:root` block at top of `style.css` |
| Hotel name | Search "Grand Palace" in `index.html` |
| Room prices | Room card sections in `index.html` |
| Contact details | Contact section in `index.html` |
| Replace an image | Swap the file in `assets/images/` — keep the same filename |
