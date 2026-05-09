# Agents Guide

## Repository Purpose

This repo hosts single-file HTML tools deployed via GitHub Pages at https://paultio.github.io/html-tools.

## Rules for Creating / Updating Tools

- **No React.** No frontend frameworks at all. Plain HTML, CSS, and vanilla JavaScript only.
- Each tool is a **single `.html` file** in the repo root.
- Tools must be **self-contained** — no external build steps, no npm, no bundlers.
- External CDN dependencies (e.g. Chart.js, Sortable.js) are allowed when they add meaningful value.
- All files must work correctly when served from GitHub Pages (relative paths only, no server-side code).

## File Naming

- Use lowercase kebab-case: `my-tool.html`
- Keep names short and descriptive

## Index Page

After adding or removing a tool, update `index.html`:
- Add a card in the tools grid with the tool's name, description, and link.
- Keep the list alphabetically sorted.

## Style Guidelines

- Tools should be responsive (mobile-friendly).
- Prefer a clean, minimal UI — no heavy styling frameworks required, but lightweight CSS (e.g. inline `<style>`) is fine.
- Include a back link to `index.html` at the top of every tool page.

## GitHub Pages

- Deployed from the `main` branch, root directory.
- No `_config.yml` needed — plain static files.
- Changes pushed to `main` are live within ~1 minute.
