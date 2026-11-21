# The Nexus Initiative

A multi-page website for The Nexus Initiative, an education advocacy organisation working for out-of-school and underprivileged children in Nigeria, built with HTML, CSS, and JavaScript.

## Preview
![The Nexus Initiative preview](./assets/preview.png)

## Links

Solution link: [https://github.com/DevAdeh/nexus-initiative]

Live link: [https://nexus-initiative.vercel.app/]

## Features
- Seven pages: Home, About, Projects, Executives, Gallery, Articles, Volunteer, and Contact
- Animated impact counters on the home page that count up when scrolled into view
- Executives page with portraits, names, and titles
- Project write-ups with photo galleries
- Newsletter subscription and comment forms on the Articles page
- Volunteer and contact forms that send messages by email
- Responsive layout with a mobile-friendly menu, and reduced-motion support

## How it works
Each page is a static HTML file that shares one stylesheet. The impact counters use an `IntersectionObserver` to start counting when they scroll into view, and are skipped for visitors who prefer reduced motion. The forms submit with `fetch` to Formspree and show a status message without reloading the page.

## Tech used
- HTML
- CSS (grid, flexbox, custom properties)
- JavaScript (IntersectionObserver, fetch, form handling)

## How to use
1. Clone or download this repo
2. Open `index.html` in a browser to browse the site
3. Deploy the folder to Vercel (`vercel.json` enables clean URLs)

## Project structure

nexus-initiative/
├── index.html
├── about.html
├── projects.html
├── executives.html
├── gallery.html
├── articles.html
├── get-involved.html
├── contact.html
├── styles.css
├── count.js
├── forms.js
├── favicon.png
├── vercel.json
├── images/
├── assets/
└── README.md

## Author
Adeola Ejikunle — [GitHub](https://github.com/DevAdeh)
