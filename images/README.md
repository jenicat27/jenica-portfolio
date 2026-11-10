# Images for the site

Add these files to this folder (same names, lowercase):

| File | Where it appears |
|---|---|
| `headshot.jpg` | Chapter 01, inside the lavender origami frame (cropped to a diamond, so keep your face centered) |
| `sketches.jpg` | Chapter 02, "Where it all started." (shown 4:3, landscape) |
| `origami/cinnamon-roll.jpg` … `origami/origami-6.jpg` | Chapter 03 photo stack (6 square photos, see below) |
| `max.jpg` | Chapter 04, "Max, 10 years old." (shown 4:5, portrait) |

All photos are in place. If a file is ever missing, its frame shows a soft placeholder such as "max.jpg goes here".
Photos are cropped to fit their frame, so any size works; around 1200px on the long side keeps the page fast.

## Chapter 03 origami stack

Six square photos in `images/origami/`: `cinnamon-roll.jpg`, then `origami-2.jpg` … `origami-6.jpg`.
To swap one, upload a new photo with the same name. To change a caption or alt text, open `index.html`,
search for `data-file="origami-2.jpg"` (or the card you want), and edit its `data-caption` and `alt`.

## Contact page cranes

The hanging cranes use `crane-lilac.png`, `crane-peach.png`, `crane-mint.png`, `crane-sky.png`,
`crane-butter.png`, `crane-sage.png` and `crane-pink.png` (transparent PNGs, kept in this folder).
Crane #N uses the colour at position (N - 1) % 7 in that order, so the pink one appears from crane #7.
