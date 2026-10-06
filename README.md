# Friction Lab — Website

Public website for [frictionlab.dev](https://frictionlab.dev).

Friction Lab is an independent software studio building local-first developer tools around AI-assisted software engineering, reusable architecture, and native developer productivity.

## Website

This repository contains the static website for Friction Lab.

The site introduces the Friction Lab product portfolio, highlights the current public status of each tool, and provides a foundation for future writing, product updates, and release notes.

## Products

Friction Lab is focused on three products:

- **Relay** (build) — flagship, in development. A local-first autonomous software development platform.
- **Wayfinder** (navigate) — CLI RC 1 available. Local-first navigation for files, folders, and working contexts. The Rust CLI is the released part; Wayfinder for Alfred and unified contextual search are in development, and wider destinations (windows, browser tabs, history, bookmarks, saved workspaces) are planned. Actions on destinations are still being explored.
- **Code Atlas** (understand) — in development. A local-first, Markdown-native developer knowledge workspace.

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
