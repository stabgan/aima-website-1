# AIMA Exercises — Website v1

Static website for exercises from *Artificial Intelligence: A Modern Approach* (AIMA) by Stuart Russell and Peter Norvig.

## What It Does

Presents all chapter exercises from the AIMA textbook in a browsable, styled web interface. Each chapter has its own page with formatted exercise questions covering topics from search algorithms to reinforcement learning.

## Architecture

A Jekyll-powered static site using a custom HTML/CSS theme ("Road Trip" by Templated). Exercise content is rendered as standalone HTML pages with shared navigation, footer, and JS-driven scroll effects.

## 🛠 Tech Stack

| | Technology | Purpose |
|---|---|---|
| 🏗️ | Jekyll | Static site generator |
| 🎨 | HTML / CSS | Page structure and styling |
| ⚡ | jQuery | DOM manipulation and scroll effects |
| 🔤 | Font Awesome | Icon set |
| 💎 | Ruby / Bundler | Jekyll dependency management |

## Getting Started

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.

## Project Structure

```
├── index.html              # Landing page
├── exercises.html          # Chapter listing
├── info.html               # About / contribute page
├── *_exercise.html         # Individual chapter exercises (27 files)
├── _config.yml             # Jekyll configuration
├── assets/
│   ├── css/main.css        # Main stylesheet
│   ├── js/                 # jQuery, scroll plugins, main.js
│   └── fonts/              # Font Awesome webfonts
└── images/                 # Banners, backgrounds, GIFs
```

## ⚠️ Known Issues

- The site uses legacy jQuery plugins (Skel, Scrollex, Scrolly) that are no longer maintained.
- MathJax is not integrated — LaTeX notation in exercises renders as raw `$...$` text.
- The `_site/` directory is committed to the repo; ideally it should be in `.gitignore`.
- Exercise content references figures and page numbers from the textbook that are not included.

## License

MIT — © Peter Norvig. Design by Kaustabh Ganguly.
