# The Lone Wolf Cafe

A modern, responsive multi-page cafe website built with HTML, Tailwind CSS (CDN), and JavaScript.

## Live Project

GitHub Repo: `https://github.com/Viceroy05/lone-wolf-cafe`

## Features

- Multi-page website:
  - Home
  - Menu
  - Gallery
  - About
  - Reservation
  - Contact
- Responsive navigation with animated mobile menu
- Premium dark cafe theme + light mode toggle (saved in `localStorage`)
- Hero section, testimonial carousel, Instagram section
- Menu category filtering (Coffee / Food / Desserts)
- Gallery lightbox with keyboard navigation
- Reservation and contact forms with JavaScript validation
- Floating WhatsApp order button
- Scroll animations using AOS
- Loading screen animation
- SEO enhancements:
  - Meta titles/descriptions
  - Open Graph tags
  - Restaurant structured data (JSON-LD)

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript

## Project Structure

```text
lone-wolf-cafe/
├── index.html
├── menu.html
├── gallery.html
├── about.html
├── reservation.html
├── contact.html
├── README.md
├── .gitattributes
├── css/
│   └── styles.css
├── js/
│   ├── script.js
│   └── script.min.js
├── images/
└── assets/
```

## Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/Viceroy05/lone-wolf-cafe.git
   ```
2. Open the project folder:
   ```bash
   cd lone-wolf-cafe
   ```
3. Open `index.html` in your browser.

You can also run with VS Code Live Server for a smoother dev workflow.

## Git Notes

- Line endings are controlled via `.gitattributes` to keep files consistent.
- Main branch tracks `origin/main`.

## Future Improvements

- Replace placeholder Instagram/WhatsApp/map links with production links
- Add backend integration for reservation/contact forms
- Add real optimized local images (`WebP/AVIF`)
- Add CI checks (HTML validation / Lighthouse audit)
