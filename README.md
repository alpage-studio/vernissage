# Vernissage

An art director for photo series. Vernissage turns 1–10 photos into a coherent Instagram carousel (3:4 or 4:5), entirely in the browser: photos never leave the device.

## Four steps

1. **Photos**: import, then drag to set the order. The first photo is the cover, the last one closes the series. Give each photo a place, and the series a title, signature, year and an optional sentence.
2. **Story**: pick an intention (an editorial series, a living memory, a graphic statement). Vernissage reads your photos (count, orientation, palette, calm areas, horizon, places and dates) and recommends three layouts, each with the reason.
3. **Finish**: try another variation, choose a treatment, text on/off, format, paper and location data. Every change can be undone.
4. **Export**: the series in publishing order, then the share sheet (Save images, or straight to Instagram).

Each photo can carry a place and a short note, and a Small print field replaces the fixed labels some layouts print (Field notes, All photographs...).

The project, photos included, is kept in this browser and comes back after a reload. Reset starts a new series.

## The signature range

| Family | Layout | Promise |
|---|---|---|
| Editorial | Gallery | A calm series that lets each image speak; the background comes from each photo's own edges. |
| | Suite | One continuous composition across the slides. |
| | Book | Double pages, the gutter on every other seam. |
| | Index | A numbered archive, the title running across. |
| | Twin | Each photo beside a drawing computed from itself: skyline, bars, constellation, contours. |
| Story | Route | Places and moments joined by a trail. |
| | Journal | Handwritten notes around your prints. |
| | Correspondence | A short note, two prints, an annotated card. |
| Material | Contact sheet | Strips of frames, the best ones circled. |
| | Print | Each photo printed on paper, with wide margins. |
| | Sketch | The photo is real in the middle and turns into a pencil drawing of itself towards the edges. |
| Signal | Poster | Half as shot, half halftone, cut through the subject. |
| | Diptych | Two photos trading squares across the seam; the lower half in colour or one of eight duotones (ochre by default). |
| | Detail | A framed close-up of the subject (or the next photo), a red line across. |
| | Window | The first photo becomes the wall, the others open in it. |
| | Fault | One colour plane crosses the photo and the image slips along it; the fault closes on the last slide. |
| | Slats | Vertical slats show the scene a moment later, a little closer; they close into one view at the end. |

Treatments apply to every photo and are independent of the layout: none, soft grain, pigment, chromogenic, silver B&W, cyanotype, halftone, 1-bit.

The **Lab** keeps the experiments (glitch, HUD, holo glass, neon, stamps, newspaper, engraving, polaroid, mirror, tiles, orbit, strata, vellum, salon, ripple, measure, burst and more). Fun to try, but there the photo is no longer the star.

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Files

- `index.html`: the whole app (HTML, CSS and JS in one file)
- `manifest.webmanifest`, `sw.js`, `icons/`: what makes it installable and usable offline
