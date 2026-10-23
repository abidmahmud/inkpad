# Inkpad

I wanted a note-taking app for my tablet that does the basics well, with no account and no subscription. I also wanted it to be quick to send my handwritten notes to an AI assistant when I get stuck on something. This is what came out of that: a notebook that runs in the browser and installs like a normal app.

## What it can do

- Write with a stylus using a ballpoint, fountain pen, brush pen, pencil, felt marker or highlighter
- Erase whole strokes or just the bit you rub over
- Lasso anything to move it, resize it, change its colour, copy it or delete it
- Draw lines, arrows and shapes, add text boxes and pictures
- Pick your paper: blank, ruled, grid, dotted, Cornell notes, checklist, music staff, isometric, or a dark board
- Open a PDF and write right on top of it (lecture slides, worksheets, homework)
- Share a page or a whole notebook as an image or PDF, for example to Claude or Gemini to explain or check my work

## How to use it

Open https://abidmahmud.github.io/inkpad/ in Chrome on the tablet and choose **Install app** from the menu. After that it opens from the home screen and works without internet.

Once it notices a stylus, your fingers scroll and zoom instead of drawing. A quick two-finger tap undoes, a three-finger tap redoes, and the S Pen side button works as an eraser.

## Good to know

Everything saves automatically and stays on the tablet. Nothing is uploaded unless you export or share it yourself. Because the notes live in the browser's storage, clearing the site data would delete them, so make a backup every now and then (notebook list → ⋯ → Back up all notebooks).

Built with plain HTML, CSS and JavaScript. PDF support uses pdf.js (Apache 2.0) and pdf-lib (MIT).
