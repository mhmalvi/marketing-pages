# Marketing Pages

A collection of static landing pages built with HTML, CSS, and JavaScript. Each subdirectory contains a self-contained, responsive landing page ready for deployment.

## Included Landing Pages

| Page | Directory | Description |
|------|-----------|-------------|
| ATR Landing Page | `atr-landing-page/` | Corporate/service landing page with testimonials and FAQ |
| ITEC Landing Page | `itec-landing-page/` | Technology/education service landing page |
| NTA Landing Page | `nta-landing-page/` | Organization landing page |
| UCT Landing Page | `uct-landing-page/` | Institutional landing page |

## Tech Stack

- **HTML5** with semantic markup
- **CSS3** — Bootstrap, custom styles, animations (Animate.css, WOW.js)
- **JavaScript** — jQuery, Bootstrap JS, smooth scrolling, magnific popup
- **Icons** — Font Awesome, Pe-icon-7-stroke
- **PHP** — Lightweight contact form and registration handlers

## Features

- Fully responsive, mobile-friendly layouts
- Smooth scroll navigation
- Animated sections on scroll (WOW.js / Animate.css)
- Testimonial sections
- Contact and registration forms with PHP backend
- Image lightbox popups (Magnific Popup)

## Usage

Each landing page is self-contained. To use one:

```bash
# Clone the repository
git clone https://github.com/mhmalvi/marketing-pages.git

# Open any landing page directly in a browser
open marketing-pages/atr-landing-page/index.html
```

For contact form functionality, deploy to a PHP-enabled web server.

## Project Structure

```
marketing-pages/
├── atr-landing-page/
│   ├── index.html
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── php/          # Contact & registration handlers
│   └── webfonts/
├── itec-landing-page/
├── nta-landing-page/
└── uct-landing-page/
```

## License

MIT
