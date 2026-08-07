# Zine Studio

A single-file web app for making **8-page mini-zines** from one sheet of 8.5×11 paper —
printed on one side, folded, with a single cut.

## Use it

Open `index.html` in a browser. That's it — no build step, no server, no dependencies.
Everything (editor, autosave, print layout) runs locally in one HTML file.

- **Edit** the 8 pages directly: add text boxes and images, drag to move,
  handles to resize/rotate, double-click text to type.
- **Images**: drag & drop files onto a page, paste with Ctrl+V, or use the *+ image* button.
- **📖 Flip through** animates the finished booklet so you can page through it before printing.
- **Preview sheet / Print** imposes the 8 pages onto a single landscape US-letter sheet
  (top row rotated 180°) with fold guides and a ✂ mark for the cut. Print at 100% scale,
  single-sided.
- Work autosaves in the browser; *Save file / Open…* exports and imports a portable `.json`.

## The format

The classic one-cut mini-zine: fold the sheet into eighths, slit the center crease across
the middle two panels, refold lengthwise, push the ends together, and flatten into a
booklet. Eight pages, each 2.75″ × 4.25″. Page imposition on the landscape sheet:

```
top row (printed upside-down):  5  4  3  2
bottom row:                     6  7  8  1     (1 = front cover, 8 = back cover)
```

Full folding instructions are in the app's help dialog (the **?** button).
