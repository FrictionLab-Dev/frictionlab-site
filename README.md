# Friction Lab — Website

Public website for [frictionlab.dev](https://frictionlab.dev).

Friction Lab is an independent software studio building local-first developer tools around AI-assisted software engineering, reusable architecture, and native developer productivity.

## Website

This repository contains the static website for Friction Lab.

The site introduces the Friction Lab product portfolio, highlights the current public status of each tool, and provides a foundation for future writing, product updates, and release notes.

## Products

Friction Lab currently includes:

- **Relay** — flagship, in development. A local-first AI-assisted software engineering workflow platform.
- **Wayfinder** — RC 1 available. A fast terminal navigator for developers.
- **Code Atlas** — in development. A local-first, Markdown-native developer knowledge workspace.
- **Space Buddy** — in development. Native macOS workspace automation.
- **Cleanroom** — public repository, in development. A local cleanup utility for development artifacts.
- **Faultline** — planned. Captures and condenses terminal error output.
- **Env Doctor** — planned. Diagnoses Python environment and `.env` issues.

## Structure

```text
Website/
├── index.html
├── products/
│   └── wayfinder/
├── blog/
├── about/
├── assets/
│   ├── css/
│   ├── js/
│   └── img/
└── README.md
```

## Local preview

This is a dependency-free static site. No build step is required.

```sh
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deployment

The site can be deployed directly to Cloudflare Pages, GitHub Pages, or any static hosting provider.

For Cloudflare Pages:

- Framework preset: `None`
- Build command: leave blank
- Output directory: `/` or `.`
- Production branch: `main`

## Links

- Website: [frictionlab.dev](https://frictionlab.dev)
- GitHub: [github.com/FrictionLab-Dev](https://github.com/FrictionLab-Dev)
- Contact: [contact@frictionlab.dev](mailto:contact@frictionlab.dev)
