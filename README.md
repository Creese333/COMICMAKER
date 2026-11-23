# Cooper's Comic Maker

A web app for drawing your own comic book and bringing it to life. It works on iPad, iPhone and desktop.

- **Cover and end page:** you can edit the title, tagline, issue number and credits, and pick from 10 title styles.
- **Pages:** 3 to 10 per comic, with comic panel layouts.
- **Drawing:** pen, eraser, rainbow colors plus a color wheel, brush sizes, and shapes (line, circle, square, hexagon).
- **Words:** speech and thought bubbles, captions, and sound effects.
- **Animation:** turn a drawing into a character and give it moves: jump, run, kick, punch, spin, fly, shake, dance, slide in, or go to the next panel.
- **Play:** acts out the whole comic like a cartoon.
- **Saving:** comics are kept in the browser and in My comics.
- **Exporting:** save as PDF or video, or make share links.

It's a single `index.html` with no build step. Open it in a browser to use it.
Account saving, file downloads and share links use Claude artifact capabilities (`db`, `user`, `downloads`), so they work only when the page is hosted as a Claude artifact. PDF and video export load html2canvas and jsPDF from cdnjs.
