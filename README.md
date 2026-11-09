# 卡诺图草稿本 (Karnaugh Map Notebook)

A single-page tool for filling in Karnaugh maps. Open `index.html` in a browser; it needs no build step and no server.

- **Fill cells**: pick 1, 0 or X, then click cells or drag across them. Clicking a cell that already has that value clears it. You can also focus a cell and type `1`, `0` or `x`, and move with the arrow keys.
- **Corner numbers**: hide them, show the standard minterm numbers, or fill them in yourself. Any number you enter twice is marked red.
- **Corner label**: the top-left cell has a diagonal line, with the row variables (AB) below it and the column variables (CD) above it. Click either label to edit it.
- **Pens**: pick a color, then use **框** to drag a rounded loop over cells, **手绘** to draw freehand, or **擦圈** to erase one loop.
- **More**: 2, 3 or 4 variables per map, quick fill by minterm list (`0,2,6,8` and `10-15`), a line for the simplified expression, undo (Ctrl/⌘+Z), and autosave in the browser.
