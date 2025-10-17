# Hello Space

A tiny, beautiful, single-file HTML page that says "Hello Space" — fully responsive and built with Tailwind CSS.

This project is intentionally small and self-contained. Open `index.html` in any modern browser to see a responsive greeting with subtle animations, accessible controls, and handy share/copy actions.

## Features

- Single-file HTML app (index.html) — no build step or server required
- Responsive layout that looks great on phones, tablets, and desktops
- Built with Tailwind CSS (via CDN) for compact, modern styling
- Decorative starfield and planet graphic (CSS + SVG) for a polished look
- Accessible UI: semantic markup, aria attributes, and reduced-motion respect
- Interactive controls:
  - Copy the greeting to clipboard
  - Share via the Web Share API (with graceful fallback)
  - Toggle light/dark theme (persisted to localStorage)
- Works offline after download — just open the file locally

## Usage

1. Download the repository or copy the three files (`index.html`, `README.md`, `LICENSE`).
2. Open `index.html` in your browser (double-click or use your browser's "Open File" option).
3. Use the Copy or Share buttons to share the greeting. Toggle the theme to switch between light and dark appearances.

Notes:
- The Web Share API works on mobile browsers and some desktop browsers; if unavailable, the Share button copies the greeting and URL to the clipboard as a fallback.
- If JavaScript is disabled, the core message ("Hello Space") remains visible but interactive features will not function.

## Development

No development environment is required. If you wish to customize styles, you can edit the inline Tailwind configuration at the top of `index.html` or modify classes directly.

For more advanced customization (e.g., using a local Tailwind build or custom fonts), set up a standard Tailwind project and extract the markup from `index.html`.

## License

This project is licensed under the MIT License — see the LICENSE file for details.

