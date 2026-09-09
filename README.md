# Hello World

A small static site built with plain HTML and CSS, styled to look modern and creative.

## Pages

- `index.html` — the "Hello, World" landing page
- `about.html` — a short about blurb
- `contact.html` — a contact form that responds in the browser

All three share a fixed pill navigation that links them together.

## Features

- Glassmorphism card with backdrop blur over a dark background
- Three animated aurora blobs drifting behind the card
- Gradient shimmer heading with a waving hand
- Card rise-in on load and pulsing loader dots
- Respects `prefers-reduced-motion` (all animation disabled)
- Fully responsive; no build step or dependencies

## Usage

Open `index.html` in any modern browser.

```sh
open index.html
```

## Customize

Edit `index.html`:

- Colors live in the `:root` CSS variables (`--accent`, `--accent-2`, `--bg`, ...).
- Heading and subtext are in the `<main class="card">` block.
