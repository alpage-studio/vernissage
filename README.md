# Vernissage

A small installable web app (PWA) that turns 2–10 photos into a gallery-style Instagram carousel.

- **Panorama**: one composition that flows across the slides, so each swipe reveals the next part.
- **Series**: one photo per slide with wide, mat-like margins.
- **Backgrounds**: topographic lines, grain aura, blurred photo, crumpled or marbled paper, risograph, gingham, graph paper, linen, or plain tones.
- **Print** (optional): original, pigment, silver B&W, chromogenic, cyanotype, applied to the whole series.
- Exports 1080 × 1440 (3:4) or 1080 × 1350 (4:5) JPEGs, numbered in carousel order.

Everything runs in the browser. Photos never leave the device.

## Use it

Open the GitHub Pages URL on your phone, then *Share → Add to Home Screen*. "Save images" opens the share sheet, where you can save to Photos or send straight to Instagram.

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Files

- `index.html`: the whole app (HTML, CSS and JS in one file)
- `manifest.webmanifest`, `sw.js`, `icons/`: what makes it installable and usable offline
