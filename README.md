# MEAN Stack Launchpad 2026

A single page, fully responsive landing page for the **MEAN Stack Developer Roadmap 2026**, built around a terminal inspired "stack visualizer" hero, layered card sections, and live outbound links to real courses, bootcamps and the full roadmap article.

No build tools, no dependencies, no framework. Open `index.html` and it just works.

## Preview

The page walks a visitor through four sections in order: what each layer of the MEAN stack actually does, the real learning sequence, project ideas worth building, honest salary numbers for India, and finally a resource grid linking out to the actual courses and bootcamps behind the roadmap.

## Features

- Terminal style hero with an animated, staggered "stack" of MongoDB, Express, Angular and Node, each layer hoverable
- Scroll triggered reveal animations using `IntersectionObserver`, no external animation library
- Fully responsive layout, tested down to small mobile widths, with a dedicated breakpoint set for tablets and phones
- Dark, teal and amber duotone theme with a dot grid texture background, distinct from typical templated AI generated layouts
- Six fully clickable outbound links woven contextually through the page (in cards, inline copy, the footer, and the primary call to action), not dumped at the bottom
- Sticky, blurred navigation bar with smooth scroll anchor links
- Accessible focus states and full support for `prefers-reduced-motion`
- Zero dependencies beyond Google Fonts, deploys instantly on GitHub Pages

## Tech Stack

Plain HTML5, CSS3 (custom properties, grid, flexbox), and vanilla JavaScript. Fonts loaded from Google Fonts: Space Grotesk for display type, Inter for body copy, JetBrains Mono for labels and data.

## File Structure

```
mean-stack-launchpad-2026/
├── index.html      # the entire page, markup + styles + script
└── README.md
```

## Run It Locally

Clone the repository and open the file directly, no server required.

```bash
git clone https://github.com/your-username/mean-stack-launchpad-2026.git
cd mean-stack-launchpad-2026
open index.html
```

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to the `main` branch and the `/root` folder.
4. Save, and the page will be live at `https://your-username.github.io/mean-stack-launchpad-2026/` within a minute or two.

## Linked Resources

The page links out to the following, each placed in context rather than stacked together:

- MEAN Stack Developer Bootcamp, Mumbai
- MERN Stack Developer Bootcamp, Mumbai
- Angular Training, Mumbai
- JavaScript Training, Mumbai
- Python Training, Mumbai
- The full MEAN Stack Developer Roadmap 2026 article

## License

Free to use, adapt and extend for JustAcademy related projects.
