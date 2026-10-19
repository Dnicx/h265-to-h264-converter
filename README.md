# H.265 to H.264 converter

Browser-based video converter (FFmpeg.wasm). Videos are processed on the user's device and never uploaded.

Equivalent to `ffmpeg -i in.mp4 -c:v libx264 -crf 18 -pix_fmt yuv420p -c:a copy out.mp4`.

## Files
- `index.html` — the page
- `ffmpeg-core.js`, `ffmpeg-core.wasm` — FFmpeg engine from `@ffmpeg/core@0.12.6` (single-threaded build, GPL)

## Hosting
Enable GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
