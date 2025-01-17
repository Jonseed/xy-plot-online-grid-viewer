**Lastest update:** added `Space` hotkey for instant switching between non-adjacent cells/images.  
Also press Ctrl+\* (or Shift+\*) to alternate between 512\*512 and 768\*768 and 1024\*1024!

### [DEMO VIDEO](https://klimaleksus2.ucoz.ru/waifu/xy-plot-online-grid-viewer-v1.mp4)
# Run or download: [https://klimaleksus.github.io/xy-plot-online-grid-viewer/xy-plot-online-grid-viewer-v1.htm](https://klimaleksus.github.io/xy-plot-online-grid-viewer/xy-plot-online-grid-viewer-v1.htm)

Contributions/PRs are not accepted.  
Discussion thread: https://github.com/AUTOMATIC1111/stable-diffusion-webui/discussions/3819

## Load some "xy_grid-…" images made by [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Features#xy-plot) "X/Y plot" feature:

- Drag-and-drop local files to this page (in-browser app, no server connection)
- Copy and paste files with Ctrl+V (works in Chrome)
- Copy and paste images (as pixel data) with Ctrl+V
- Copy and paste a link to image as URL (cross-domain is OK)
- Drag-and-drop a link to image or the image itself from other browser tabs (pasted as URL)
- Paste with context menu / right mouse button: (autofocus)
- Open files via modal winodow: (also by Insert hotkey)

## Hotkeys / Controls:

- Up-Left-Down-Right / WASD = change cell, navigate; Home / End = first / last cell
- Ctrl + arrows = change size by 8 pixels; Shift + arrows = double size; Ctrl+Shift + arrows = by pixels
- PageDown-PageUp / Q-E = change image (previous-next); 1-9 = select image by index; 0 = select last
- \+ or - = change scale; \* or /, \\, | = reset scale. (You may use browser scaling also, but it's not recommended)
- Ctrl \+ \*, /, \\, | (or Shift \+ \*, /, \\, |) = reset size to 512\*512 or quickly change it to 768\*768 or 1024\*1024
- Space = switch between two sets of image/position/scale; Shift+Space = copy current values to other set
- Delete = remove current image from queue; Escape = remove all, return to main screen
- Ctrl+V or drag-and-drop = add more images; Insert = trigger image selection modal window
