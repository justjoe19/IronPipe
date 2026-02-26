# Ironpipe Plumbing Co. — Website

A responsive, single-page website for **Ironpipe Plumbing Co.**, a fictional plumbing company. Built with plain HTML, CSS, and vanilla JavaScript — no frameworks or build tools required.

---

## 🚀 Getting Started

Just open `index.html` in any modern web browser. No installation, no dependencies, no build step.

```bash
# If you have Python installed, you can serve it locally:
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## 📄 File Structure

```
/
├── index.html      # The entire website (HTML + CSS + JS in one file)
└── README.md       # This file
```

Everything lives in a single `index.html` file for simplicity and portability.

---

## 🗂 Sections

| Section | Description |
|---|---|
| **Nav** | Fixed header with smooth-scroll links and a mobile hamburger menu |
| **Hero** | Headline, CTA buttons, rotating pipe SVG graphic, and stat strip |
| **Ticker** | Auto-scrolling service highlights banner |
| **Services** | 6-card grid covering core plumbing offerings |
| **Why Us** | Numbered value propositions with a same-day call-to-action panel |
| **Testimonials** | Three customer review cards |
| **Contact** | Company details + quote request form with success feedback |
| **Footer** | Logo, copyright, license number, and nav links |

---

## 🎨 Design

- **Palette:** Dark iron (`#1c1c1e`), rust red (`#c0392b`), steel grey (`#2c2c2e`), cream (`#f5f0e8`)
- **Fonts:** [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) (headings) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body) via Google Fonts
- **Theme:** Industrial / utilitarian — dark steel tones with rust accents

---

## ✏️ Customization

All key details are in `index.html` and easy to swap out:

**Company info**
- Name: search for `Ironpipe` and replace throughout
- Phone: `(555) 123-4567` → your number (appears in nav CTA, hero, and contact section)
- Email: `hello@ironpipeplumbing.com`
- Address: `4812 Ironworks Blvd, Suite 100, Springfield, IL 62701`
- License number: `#PL-88421` (footer)
- Founded year: `1987` (hero tag), `38+` years (stats + why section)

**Colors** — edit the CSS variables at the top of the `<style>` block:
```css
:root {
  --iron: #1c1c1e;
  --rust: #c0392b;
  --steel: #2c2c2e;
  --cream: #f5f0e8;
  /* ... */
}
```

**Services** — edit the `.service-card` blocks in the Services section to change names, icons, or descriptions.

---

## ⚙️ Features

- **Fully responsive** — adapts to mobile, tablet, and desktop
- **Mobile nav** — hamburger menu with fullscreen overlay on small screens
- **Scroll animations** — sections and cards fade in as they enter the viewport (IntersectionObserver)
- **Staggered card reveals** — service and testimonial cards animate in sequence
- **Form feedback** — submit button turns green and resets after 3 seconds
- **No dependencies** — zero npm packages, zero build tools, works offline

---

## 🌐 Deployment

This is a static HTML file and can be hosted anywhere:

- **GitHub Pages** — push to a repo and enable Pages in settings
- **Netlify / Vercel** — drag and drop the folder into their dashboard
- **Any web host** — upload `index.html` via FTP/SFTP to your public root

---

## 📝 Notes

- The contact form does **not** submit data anywhere — you'll need to wire it up to a backend service (e.g. [Formspree](https://formspree.io), [Netlify Forms](https://docs.netlify.com/forms/setup/), or your own server) for real form submissions.
- Google Fonts are loaded from an external CDN — the site requires an internet connection to display the correct typography.
- The rotating SVG pipe graphic is purely CSS-animated and requires no JavaScript.

---

*Ironpipe Plumbing Co. is a fictional business created for demonstration purposes.*
