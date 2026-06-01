# Ishan Rastogi — Personal Portfolio

A modern, dark-themed personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. No frameworks. No build tools. Just clean, hand-crafted frontend code.

**Live Site:** [https://ishan2608.netlify.app/](https://ishan2608.netlify.app/)

## Preview

> Dark glassmorphism aesthetic with animated ember particles, gradient typography, frosted glass cards, and smooth scroll-reveal animations.


## Features

- **Ember Particle System** — Canvas-based particle engine with glowing ember trails that rise from the bottom and burst on mouse movement
- **Glassmorphism UI** — Frosted glass cards with backdrop blur, gradient borders, and shimmer highlights
- **Gradient Typography** — Headings rendered with animated orange-to-magenta gradients using CSS `background-clip: text`
- **Custom Cursor** — Gradient dot with a trailing ring that reacts to hover states
- **Scroll Reveal Animations** — IntersectionObserver-powered staggered fade-up transitions on every section
- **Animated Background Mesh** — Slow-drifting radial gradient blobs with hue-rotation
- **Skill Matrix HUD** — Animated progress bars in the hero panel
- **Responsive Design** — Fully mobile-optimised with graceful layout adjustments
- **Zero Dependencies** — No npm, no bundler, no framework

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, backdrop-filter) |
| Scripting | Vanilla JavaScript (Canvas API, IntersectionObserver) |
| Fonts | Montserrat, Instrument Sans, JetBrains Mono via Google Fonts |
| Hosting | GitHub Pages |

## Project Structure


Portfolio-Website/
├── index.html       # Entire site — markup, styles, and scripts
└── README.md


The entire site lives in a single `index.html` file. Styles are in a `<style>` block in the `<head>`, and scripts are in a `<script>` block before `</body>`.


## Sections

| # | Section | Description |
|---|---|---|
| 01 | About | Background, skills, and tech stack grouped by domain |
| 02 | Experience | Epidise Healthcare and GeeksForGeeks |
| 03 | Projects | Artha, NextRoom, Epidise website, Rooms |
| 04 | Writing | Selected GeeksForGeeks articles (100,000+ views) |
| 05 | Certifications | 7 certifications from Google, IBM, AWS, and Udemy |
| 06 | Contact | Email, phone, and social profile links |



## Running Locally

No installation required. Clone the repo and open the file directly in a browser.

```bash
git clone https://github.com/Ishan2608/Portfolio-Website.git
cd Portfolio-Website
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or serve it with any static file server:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## Deploying to GitHub Pages

1. Push `index.html` to the `main` branch of your repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`

---

## Customisation

All content is in plain HTML inside `index.html`. To update:

- **Name / bio / contact** — edit the hero and contact sections directly
- **Projects** — find the `proj-grid` div and update the `proj-card` blocks
- **Certifications** — find the `certs-grid` div and add or remove `cert-card` divs
- **Color palette** — all colors are CSS custom properties in `:root` at the top of the `<style>` block
- **Ember colors** — edit the `COLORS` array in the `<script>` block
- **Particle count** — adjust the `MAX` constant in the script

---

## Author

**Ishan Rastogi**
Full Stack Developer · AI Agent Architect

- Email: [ishanrastogi26@gmail.com](mailto:ishanrastogi26@gmail.com)
- LinkedIn: [linkedin.com/in/ishan-rastogi-672a5a195](https://www.linkedin.com/in/ishan-rastogi-672a5a195/)
- GitHub: [github.com/Ishan2608](https://github.com/Ishan2608)
- GeeksForGeeks: [auth.geeksforgeeks.org/user/ishanrastogi26](https://auth.geeksforgeeks.org/user/ishanrastogi26)

---

## License

This project is open source under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use it as inspiration or a template — credit appreciated but not required.
