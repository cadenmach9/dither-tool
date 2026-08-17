# Dither Lab

A browser-based image dithering tool in a single HTML file. No build step, no dependencies — open `index.html` and go.

![status](https://img.shields.io/badge/dependencies-none-brightgreen)

## Features

- **Dithering algorithms**: Floyd–Steinberg and Atkinson error diffusion (with optional serpentine scanning), ordered Bayer matrix, random, and plain threshold
- **Color modes**: monochrome with customizable ink/paper colors, or custom palettes (nearest-color, luminance-mapped, or random assignment) with an inline palette editor
- **Image adjustments**: brightness, contrast, gamma, saturation, levels, invert, and dither strength
- **Pixelation** control for chunky low-res looks
- **Zoom & pan** viewport with fit-to-screen, plus crisp pixelated rendering
- **Drag & drop** image loading and one-click PNG download

## Usage

Open `index.html` in any modern browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then drop an image onto the page, pick an algorithm, tweak the sliders, and hit **Download**.

## License

MIT
