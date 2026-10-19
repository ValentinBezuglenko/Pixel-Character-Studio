# Pixel Character Studio

[English](README.md) · [Русский](README.ru.md) · [Español](README.es.md) · [中文](README.zh-CN.md)

A standalone browser-based editor for drawing 16×16 pixel characters and creating frame-by-frame sprite animations. It works locally, requires no account or server, and is not tied to any game.

![Pixel Character Studio editor](assets/editor-preview.png)

## Features

- 16×16 pixel editor with grid, eraser, undo and redo
- sprite and frame creation, duplication, deletion and reordering
- adjustable frame duration and live animation preview at 1×, 2×, 4×, 8× or 10×
- onion-skin preview of the previous frame
- built-in palette plus custom colors
- project search and grouping
- automatic local saving and up to five manual versions
- project import and export as JSON
- 16×16 PNG import and current-frame PNG export
- spritesheet ZIP export with PNG and JSON atlas
- interface languages: English, Spanish, Russian and Simplified Chinese
- three editable character-animation examples

## Run locally

No build step is required. Download the repository and open `index.html` in a modern browser.

For a local web server, run one of these commands in the project directory:

```bash
python -m http.server 8000
```

```bash
npx serve .
```

Then open `http://localhost:8000` or the address printed by the server.

## Publish with GitHub Pages

1. Push the project to GitHub.
2. Open **Settings → Pages** in the repository.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder.

The editor stores projects in the browser's `localStorage`. Export a project JSON file to move work between browsers or computers.

## Third-party examples

The bundled editable examples and their terms are documented in [THIRD_PARTY_ASSETS.md](THIRD_PARTY_ASSETS.md).

## Project license

No license has been selected for the editor source code yet. Add a `LICENSE` file before inviting outside contributors or granting reuse rights.
