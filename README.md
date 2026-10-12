# Jenica — Fold to Discover

My personal portfolio: a hand-drawn, origami-inspired site where an interactive paper fortune teller opens into each section.

**Pages:** Landing (fortune teller) · About · Projects · EcoLoop / Nexus Edge — Google AI Micro-Intern · Real Quest · Final Presentation · Experience · Contact

---

## How this project is built

The whole site is **one file: `index.html`**. It's plain HTML, CSS and JavaScript, with no framework, no packages to install and no build step.

- **Styles** live in the `<style>` blocks at the top of `index.html`.
- **Illustrations** (fortune teller, origami cat, envelope, icons, phone mockups) are drawn in code with inline SVG and CSS. There are no image files to keep track of.
- **Fonts** (Patrick Hand and Nunito) load from Google Fonts, so the handwritten look needs an internet connection. Offline, the page falls back to similar system fonts and still works.
- **Navigation** is handled by a small script at the bottom of `index.html`. Each page has its own web address ending, such as `#about`, `#projects`, `#project-realquest` or `#contact`, so the browser's back and forward buttons work.

| File | What it is |
|---|---|
| `index.html` | The entire website: markup, styles, illustrations and scripts |
| `README.md` | This guide |
| `.gitignore` | Tells Git to skip Mac and editor clutter, such as `.DS_Store` |

No environment variables, API keys or secrets are used, so there is no `.env` file.

---

## Run it on your Mac

### Option A: just open it (easiest)
1. Unzip the download. You'll get a folder called `jenica-portfolio`.
2. Double-click `index.html`. It opens in your browser and the whole site works.

### Option B: run a local web server (closest to a real website)
1. Open **Terminal** (press `⌘ + Space`, type *Terminal*, press Enter).
2. Go to the folder. Type `cd `, with a space after it, then drag the `jenica-portfolio` folder into the Terminal window and press Enter.
3. Start a server:
   ```bash
   python3 -m http.server 8000
   ```
   If your Mac asks to install "command line developer tools", click **Install**, wait for it to finish, then run the command again.
4. Open your browser and go to **http://localhost:8000**
5. When you're done, go back to Terminal and press `Control + C` to stop the server.

---

## Editing content

All the text is inside `index.html`. Search for these to find things quickly:

- `const CONTACT` — your email and LinkedIn
- `const EXPERIENCE` — the Experience timeline notes
- `const CARDS` — the project cards on the Projects page
- `id="page-about"`, `id="page-nexus"`, `id="page-rq"` — the About, Nexus Edge/EcoLoop and Real Quest pages
- `id="page-presentation"` — the presentation page (add your slides here when they're ready)

Save the file and refresh the browser to see your changes.
