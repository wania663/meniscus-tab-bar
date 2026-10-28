# Meniscus Tab Bar

A liquid tab bar built with vanilla HTML, CSS and JavaScript. The bar doesn't slide a highlight: it melts around the active button.

## How it works
- **One SVG path** draws the whole bar, including the socket for the button.
- Each shoulder of the notch is a circle tangent to both the top edge and the socket circle, so the curve is always smooth.
- The button (bead) moves with **spring physics**. Faster movement makes the shoulders lean with the speed.
- No libraries, no build step.

## Run it
Open `index.html` in any modern browser.

## Customize
Edit these constants in the script:

| Constant | What it does |
|---|---|
| `COL` | Accent color per tab |
| `NAME` / `ICON` | Tab labels and icons |
| `S` | Shoulder radius |
| `R` | Socket radius |

## License
MIT
