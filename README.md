![Calculator banner](./docs/banner.png)

# Calculator

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

A single-file calculator built as a self-contained web page.

**Live:** https://presidenteog.github.io/web-calculator/ — deployed straight from `main` by
GitHub Actions on every push.

## Showcase

![Calculator running in a browser, mid-calculation: 8 times 4 shown as 32](./docs/screenshot.png)

*Real screenshot — the buttons were actually pressed (8 × 4 =) and this is the actual result on
screen, not a mockup.*

## What's here

- `index.html` — the whole app: markup, styling and logic in one file. No build step, no
  dependencies, no server.

## Running it

Open `index.html` in any browser. That's it.

## Architecture

![Calculator architecture: the buttons in index.html feed the inline script, which updates the display in the DOM](./docs/architecture.png)

See [ARCHITECTURE.md](./ARCHITECTURE.md) for how it's structured and what it demonstrates.

## License

PolyForm Noncommercial 1.0.0 — see [LICENSE](./LICENSE). Use it, learn from it, fork it for
anything that isn't commercial.
