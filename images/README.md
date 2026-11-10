# Images for the site

Add these files to this folder (same names, lowercase):

| File | Where it appears |
|---|---|
| `headshot.jpg` | Chapter 01, inside the lavender origami frame (cropped to a diamond, so keep your face centered) |
| `sketches.jpg` | Chapter 02, "Where it all started." (shown 4:3, landscape) |
| `origami/cinnamon-roll.jpg` … `origami/origami-6.jpg` | Chapter 03 photo stack (6 square photos, see below) |
| `max.jpg` | Chapter 04, "Max, 10 years old." (shown 4:5, portrait) |

Until a file is added, its frame shows a soft placeholder such as "max.jpg goes here".
Photos are cropped to fit their frame, so any size works; around 1200px on the long side keeps the page fast.

## Chapter 03 origami stack

Put six square-ish photos in `images/origami/`. The first is `cinnamon-roll.jpg`.
Cards 2–6 currently expect `origami-2.jpg` … `origami-6.jpg` with placeholder alt text and captions.
To change a card, open `index.html`, search for `TODO: replace file name`, and edit that card's
`src` (and the `ph-note` file name below it), `alt`, and `data-caption`.

## Contact page cranes

The hanging cranes use `crane-lilac.png`, `crane-peach.png`, `crane-mint.png`, `crane-sky.png`,
`crane-butter.png`, `crane-sage.png` and `crane-pink.png` (transparent PNGs, kept in this folder).
Crane #N uses the colour at position (N - 1) % 7 in that order, so the pink one appears from crane #7.
