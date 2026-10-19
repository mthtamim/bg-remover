# BG Remover

Professional AI background remover that runs entirely in the browser.
Unlimited use — no API key, no sign-up, no per-image cost. Images are
processed locally on the visitor's device and are never uploaded.

**Live:** https://bg.mthtamim.bond

## Features

- Three quality levels — Best (full precision, default), Balanced, Fast
- GPU (WebGPU) with automatic CPU fallback
- Batch processing with a sequential queue
- Magic Brush editor: erase / restore with undo & redo
- Backgrounds: transparent, colours, gradients, background blur,
  or your own photo
- Shadow effect, output-size presets (original, 1:1, 9:16, 16:9)
- PNG / WebP export at full resolution, before–after compare slider,
  ZIP download of all results
- Bangla / English interface, dark / light theme

## Tech

Single static `index.html`. The AI engine
([@imgly/background-removal](https://www.npmjs.com/package/@imgly/background-removal) v1.7.0)
and model weights load lazily from CDN on first use and are cached by
the browser afterwards.

## License

MIT
