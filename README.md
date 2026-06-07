# Friction Lab — Website

Public website for [frictionlab.dev](https://frictionlab.dev).

Friction Lab builds local-first developer tools for reducing everyday workflow friction across terminal navigation, AI-assisted development, safe cleanup, workspace management, and codebase memory.

## Website

This repository contains the static website for Friction Lab.

The site introduces the Friction Lab product portfolio, highlights released and in-development tools, and provides a foundation for future writing, product updates, and release notes.

## Products

Friction Lab currently includes:

- **Wayfinder** — a Rust terminal navigator for macOS with shell-integrated `cd`, open, copy, and reveal actions.
- **Relay** — a local-first macOS mission-control app for AI-assisted software development workflows.
- **Cleanroom** — safe, explainable cleanup for generated developer artifacts.
- **Code Atlas** — repo-native smart documentation and memory for codebases and AI-assisted development.
- **Space Buddy** — a macOS workspace companion for task-focused desktops and app/window anchors.
- **Folder Sense** — Finder folder icon suggestions using lightweight rules and ML-assisted classification.

## Structure

```text
Website/
├── index.html
├── products/
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
