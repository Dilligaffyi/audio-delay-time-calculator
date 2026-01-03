# Audio Delay Time Calculator

A browser-based calculator for estimating audio delay (ms) based on distance and temperature.
Includes optional humidity adjustment and optional digital delay.

Made with ❤️ by **DILLIGAF.FYI**.

## Use it

### Option 1: Run locally
1. Download the repo (Code → Download ZIP)
2. Open `index.html` in your browser

### Option 2: Use it online (GitHub Pages)
If the repo has GitHub Pages enabled, open the Pages link and use it directly in your browser.

## Formula
Speed of sound estimate:
`speed (m/s) = 331.4 + 0.6 × T(°C)`

Delay:
`delay (ms) = distance(m) / speed(m/s) × 1000 + digitalDelay`

## Humidity note
If humidity is enabled, the tool applies a simple adjustment:
`effectiveTemp = temp + (humidity-50)/10`

---

Made with ❤️ by [DILLIGAF.FYI](https://dilligaf.fyi)
