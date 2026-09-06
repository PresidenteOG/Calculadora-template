# Architecture

Built a working calculator — digits, the four basic operations, percentage, sign change, decimal
input, backspace, clear — that runs from a single file with nothing to install: open it, use it.
No framework, just HTML, CSS and JavaScript.

## Structure

Everything lives in `index.html`. One file, three parts, in order:

- **Markup**: the calculator's buttons and the display.
- **Styling**: plain CSS, scoped to this page.
- **Logic**: a small set of functions that track the current input, the pending operation and the
  running total, and re-render the display after every button press.

## Language / framework breakdown

| Part | Technology |
|---|---|
| UI | HTML + CSS |
| Behavior | Vanilla JavaScript (no framework) |

## Data and external services

None. There is no database, no API call, and no external dependency of any kind — the whole
thing runs entirely in the browser from a single static file. This template doesn't need a
"local database instead of external" step because there was never anything external to begin
with.

## Running it

Open `index.html` in any browser.
