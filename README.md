# web-chrishelsel-com

Minimalist landing page for **chrishelsel.com**, hosted via GitHub Pages.

This repo contains a single static HTML file that renders a clean, centered wordmark:

> `chris helsel`

All lowercase, no navigation, no email link, no tracking — just a quiet, intentional personal mark.

---

## Overview

- **Domain:** `chrishelsel.com`
- **Hosting:** GitHub Pages (deployed from this repository)
- **Stack:** Plain HTML & CSS (no build tools, no JavaScript)
- **Design goals:**
  - Minimalist and understated
  - Centered content that scales with screen size
  - Respect system light/dark mode where supported
  - No interactive elements or contact links

---

## Page Design

The page consists of:

- A full-height viewport layout using flexbox for vertical and horizontal centering
- Single line of text: `chris helsel` in all lowercase
- White background with black text in light mode
- Near-black background with soft off-white text in dark mode
- Typography that scales with the viewport using `clamp()` so it looks good on:
  - Desktop monitors
  - Tablets (portrait and landscape)
  - Mobile phones (portrait and landscape)

Additional styling:

- `white-space: nowrap` keeps `chris helsel` on a single line, reinforcing the wordmark feel.
- All styles are defined directly in `index.html` to keep the project self-contained and low maintenance.

---

## Project Structure

```text
/
└── index.html   # Single-page static site for chrishelsel.com
