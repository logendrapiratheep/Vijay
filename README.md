# MERSAL — Cinematic Portfolio

Complete HTML, CSS, JavaScript and image assets for the latest version.

## Run on Windows
1. Extract this ZIP.
2. Open the extracted folder in VS Code.
3. Use the Live Server extension and select Open with Live Server on index.html.
Alternatively, with Python installed, run `python -m http.server 8000` in this folder and open http://localhost:8000.
No npm install or build step is needed.

## Edit the site
- index.html: headings, cinema skills, section content and email links.
- style.css: black/gold colors, fonts, layout, mobile styling. Later CSS rules override earlier ones.
- app.js: scroll animations and hyena petting loop.
- assets/: generated animation sheets, mobile background and embedded fonts.

## Animations
The hero uses a 3-by-2 sprite sheet. The eyes use a 2-by-2 sprite sheet. The final petting loop uses a 3-by-2 sprite sheet. JavaScript draws one frame at a time to canvas, without crossfading. These are AI-generated frame sequences, not actual video footage or 3D models. Eye/hand motion is frame-based and can appear stepped.

## Useful changes
- Hero speed: .sequence height in style.css; smoothing is delta*.38 in app.js.
- Eye speed: .awakening-sequence height in style.css (185vh).
- Petting speed: the 4400ms cycle in petLoop in app.js.
- Hire Me email: change both mailto links in index.html.

## Hosting
Upload the contents of this folder to a static host such as GitHub Pages or Netlify. Keep assets alongside index.html. This export does not include the original host account configuration or credentials.

## Notes
Hire Me opens the visitor's email application; there is no backend email form. Some secondary body fonts use Google Fonts; title fonts are embedded locally. Skills shown are customizable concept content and should be adjusted to accurately represent the portfolio owner. Generated portraits are approximations based on the supplied references. Confirm rights to reference imagery and likenesses before commercial use.
