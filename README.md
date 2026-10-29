# Dental Website

A French-language dental practice website with service pages, team sections, and a contact form.

[Open the demo](https://dental-website-vert.vercel.app) · [Browse the code](https://github.com/hamzaxbella/dental-website)

## Overview

The interface includes home, about, service, contact, sitemap, and legal pages. Reusable sections present the team, opening hours, testimonials, services, and before/after imagery.

Built with React, Vite, React Router, Tailwind CSS, and EmailJS.

## Run locally

```bash
git clone https://github.com/hamzaxbella/dental-website.git
cd dental-website
npm ci
npm run dev
```

Open <http://localhost:5173> (or the address printed in the terminal).

```bash
npm run build
```

Use the build script to generate production output.

## Configure and explore

`src/App.jsx` defines the routes. `src/pages/` composes pages, `src/sections/` holds content sections, and `src/constants/` supplies shared content. The contact implementation is in `src/sections/ContactForm.jsx`; configure your own EmailJS service before enabling submissions.

For SPA hosting, configure a fallback to `index.html`. This is a frontend website project; it does not provide patient accounts, clinical records, or a booking backend. Brand material and media retain their original ownership.
