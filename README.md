# Meipaly — Smart Web Design Agency

Meipaly is a responsive, single-page landing website for a fictional digital design agency. It is built with plain HTML, CSS, and jQuery, and showcases services, a portfolio gallery, animated statistics, an embedded video, and a contact section with an embedded map.

[Live Demo](https://dat532006.github.io/Meipaly/)

This project was built with **Nguyễn Đức Đạt**.

## Demo Sections

- **Header / Navigation** — Brand logo and main menu (Home, Service, Showcase, Blog, About us, Contact).
- **Hero Carousel** — Welcome banner with a call-to-action button.
- **Services** — A Slick-powered carousel of agency services.
- **Blog / Showcase** — A metro-style image grid with Fancybox lightbox previews.
- **Statistics** — Animated number counters using CountUp.
- **Digital Experience** — Embedded YouTube video section.
- **Contact** — Google Maps embed alongside a contact form.
- **Footer** — Copyright and social icons.
- **Back-to-Top** — Floating button that appears on scroll.

## Tech Stack

- **HTML5** — Semantic page structure.
- **CSS3** — Custom styling (`css/style.css`).
- **jQuery** — DOM manipulation and plugin wiring.
- **Slick Carousel** — Service slider.
- **Fancybox** — Image lightbox gallery.
- **CountUp + Waypoints** — Animated statistics counters.
- **WOW.js + Animate.css** — Scroll-triggered animations.
- **Font Awesome** — Iconography.
- **Google Fonts (Oswald)** — Typography.

## Project Structure

```
meipaly/
├── index.html          # Main page
├── css/
│   ├── style.css       # Custom styles
│   └── style.min.css   # Minified styles
├── images/             # Photos, slider, and video assets
└── libs/
    ├── back-to-top/    # Back-to-top button script
    ├── countup/        # Animated counter plugin
    ├── slick/          # Slick carousel
    └── wowjs/          # Scroll animation library
```

## Getting Started

No build tools or package managers are required.

1. Clone or download this repository.
2. Open `index.html` directly in a modern web browser, **or** serve the folder with any static server, for example:
   ```bash
   # Python 3
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

> Tip: Serving via a local web server (rather than opening the file directly) ensures that all third-party CDN scripts, fonts, and embedded iframes load correctly.

## Browser Support

Tested on the latest versions of Chrome, Edge, and Firefox. A modern browser with ES6 and CSS Grid/Flexbox support is recommended.

## License & Disclaimer

This project is created for **learning and academic purposes only**. It is **not intended for commercial use**. All third-party assets (fonts, icons, sample images, libraries) belong to their respective owners.
