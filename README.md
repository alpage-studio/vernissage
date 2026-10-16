# Vernissage

A small installable web app (PWA) that turns 2–10 photos into a gallery-style Instagram carousel.

Eight layouts:

- **Panorama**: one composition that flows across the slides, so each swipe reveals the next part.
- **Series**: one photo per slide with wide, mat-like margins.
- **Letters**: the title in giant letters, each cut out of your photos.
- **Route**: prints joined by a dotted trail, with time and (optionally) GPS from the photo metadata.
- **Fragments**: the first photo scattered in strips, whole again on the last slide.
- **Film strip**: a 35 mm strip winding through the slides, with perforations and light leaks.
- **Windows**: the first photo is the wall; the others appear as arched, round or square openings.
- **Scrapbook**: torn prints, masking tape and pencil notes.

Six "future" layouts that bring their own background:

- **Glitch**: RGB split, displaced slices, pixel streaks and scanlines.
- **Holo glass**: frosted glass cards on iridescent foil, chrome title.
- **HUD**: viewfinder brackets, grid and ruler, with real camera data (aperture, shutter, ISO, focal length) read from the photos.
- **Dither**: 1-bit ordered dithering in two inks.
- **Float**: isometric prints hovering over their shadows.
- **Kaleidoscope**: each photo mirrored into a mandala, with the original at its centre.

Tap a photo to give it a place name; it shows up in the captions of Route, Scrapbook, HUD and the future layouts.
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
