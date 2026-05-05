# recto-verso

A minimal browser tool for composing two-sided document scans — front and back — into a single JPEG sheet.

Drag and drop (or click to upload) two images, choose your layout, and export. No server, no upload, no dependencies. Everything runs locally in the browser.

## Use

1. Load the front (recto) image
2. Load the back (verso) image
3. Choose layout: side by side or stacked
4. Set gap and output quality
5. Compose → Download

## Options

| Setting | Options |
|---|---|
| Layout | Horizontal (side by side) / Vertical (stacked) |
| Gap | 0 / 8 / 16 / 32 px |
| Quality | 80% / 95% / 100% |

Images are normalized to a common height (horizontal) or width (vertical) before compositing. Output is JPEG.

## Notes

- Runs entirely client-side — no data leaves your browser
- Works with any image format the browser supports (JPEG, PNG, WEBP, HEIC on supported devices)
- On mobile, long-press the preview to save directly to photos
- Made with Claude

## License

MIT
