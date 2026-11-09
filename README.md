# SenseLab: Resistive Sensors

An accessible, responsive, interactive undergraduate companion to SCT 491–2 Lesson 2. Covers electrical basics, potentiometers, loading, strain gauges, Wheatstone bridges, temperature compensation, calibration and assessment.

## Publish on GitHub Pages

1. Create a GitHub repository, for example `senselab`.
2. Upload **all the files in this folder** to its root. `index.html` must be at the root, not inside another folder.
3. Open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**.
4. Select **main** and **/ (root)**, then Save.
5. GitHub will show the website address when deployment finishes, usually `https://YOUR-USERNAME.github.io/senselab/`.

Keep the `assets/` folder beside index.html: it contains the diagrams, photos, animations and posters.

No Node.js, build command, API key or paid service is required. Do not upload the ZIP itself as the website: extract it first. For a private repository, GitHub Pages availability depends on your GitHub plan. Use a public repository for the usual free public course website.

## Lesson navigation

The site shows one lesson part at a time. Select a numbered tab, use Previous/Next, or use the arrow keys within the tab list. URL hashes link directly to a part. Parts 1–7 cover Basics, Potentiometric Displacement Sensor, Loading Effect, Strain Gauges, Wheatstone Bridge, Practical and Assessment. Quick Reference is a separate resource tab. Print all notes prints every part.

The explanations follow the supplied Part 2 reference: everyday example, physical principle, symbols, worked calculation, experiment, summary and self-check.

## Use and edit

Open index.html directly in a modern browser. Edit lesson text in index.html, colours/layout in style.css, and simulations/questions in app.js. Relative asset links work under a GitHub project path. Google Fonts are optional; system fonts work offline. All lesson interactions run locally. The supplied source ZIP link is intended for the hosted preview; to retain that link on GitHub, upload the original ZIP alongside the extracted files, or remove the footer link.

Progress is stored only in browser localStorage where available. Quiz answers and lab records are held in memory and reset on refresh. The lab can export CSV. Print notes uses the browser's print dialog.

## Teaching and model notes

Based on the user-provided `SCT491 Lec2 Lesson Plan.docx`. The document is a content source; classroom directions were adapted into student-facing activities. The listed lesson segments actually total 130 minutes, despite the document's stated 120 minutes. This website is self-paced.

The potentiometer model uses a uniform track and resistive load. Bridge sign conventions and resistor assignments appear next to the simulator. Half/full sensitivity assumes equal tension and compression arranged to add. The virtual load lab uses an explicitly illustrative ideal model, not physical cantilever geometry. The optional offset models a zero shift, not a full thermal model. For a physical lab, follow the instructor's rig-specific limits and calibration procedure.

External reference links are included for further reading and can change. This is a learning aid, not a substitute for equipment documentation.

## Images, animation and maths

The site includes credited hardware photographs, four original SVG teaching diagrams, and three local silent MP4 animations with PNG posters, text descriptions and downloadable GIF versions. Playback is user-controlled. An optional Engineering Mindset YouTube player loads only when selected; a TI amplifier video opens on its official website. External videos need internet access; local lesson media works offline. See MEDIA-CREDITS.md for licences and source links.

Displayed equations use semantic native MathML for proper fractions, subscripts and accessible descriptions without an online typesetting dependency. Original length/resistance and bridge polarity are defined beside the equations. The quarter-bridge exact result is distinguished from the small-strain approximation.
