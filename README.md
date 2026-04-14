[README.md](https://github.com/user-attachments/files/26696537/README.md)
# Ambiguous Case of the Sine Law — Interactive Explorer

An interactive visualization that demonstrates when the Side-Side-Angle (SSA) configuration produces 0, 1, or 2 valid triangles using the Sine Law.

## Live Demo

👉 **[Open the app]((https://gary-gui.github.io/Ambiguous-Sine-Interactive-App/))**

## Features

- **Interactive sliders** to adjust angle A, side a (opposite), and side b (adjacent)
- **Real-time visualization** showing the compass-arc construction
- **Automatic case detection** — see instantly whether the values give 0, 1, or 2 triangles
- **Preset buttons** for each case type
- **Math panel** showing h = b sin A and the governing condition

## How It Works

Given angle A and sides a and b, the app draws a compass arc of radius *a* from vertex C. The number of times this arc intersects the base line determines how many valid triangles exist:

| Condition | Result |
|---|---|
| a < h (= b sin A) | No triangle |
| a = h | One right triangle |
| h < a < b | **Two triangles** (the ambiguous case) |
| a ≥ b | One triangle |

## Setup

This is a single HTML file — no build tools or dependencies needed.

1. Clone the repo
2. Open `index.html` in a browser

Or just visit the GitHub Pages link above.

## License

MIT
