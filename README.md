# K-map Notebook

A single-page tool for filling in Karnaugh maps. Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000.

- **Fill cells**: pick 1, 0 or X, then click cells or drag across them. Clicking a cell that already has that value clears it. You can also focus a cell and type `1`, `0` or `x`, and move with the arrow keys.
- **Corner numbers**: Hide, Auto (standard minterm numbers) or Manual (type your own). Any number entered twice turns red.
- **Corner label**: the top-left cell has a diagonal line, with the row variables (AB) below it and the column variables (CD) above it. Click either label to edit it.
- **Pens**: pick a color, then use **Loop** to drag a rounded loop over cells, **Free** to draw freehand, or **Erase** to remove one loop.
- **More**: 2, 3 or 4 variables per map, quick fill by minterm list (`0,2,6,8` and `10-15`), a line for the simplified expression, undo (Ctrl/⌘+Z), and autosave in the browser.
