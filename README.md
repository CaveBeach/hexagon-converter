# HexagonConverter

Desktop video conversion tool built with Python and ffmpeg.

<img width="973" height="817" alt="image" src="https://github.com/user-attachments/assets/98ebaa29-dfca-4c22-bcd3-2c409943a32b" />

---

## Features

### Video converter
- Output to H.264, H.265, AV1, VP9 (with and without alpha) simultaneously
- Per-format CRF sliders and frame offsets
- Keyframe forcing with configurable padding — set target frames manually, converter handles the rest
- Keyframe inspector — scan output files and see exactly where keys landed
- Drag & drop files and folders from Explorer
- Sequence support (PNG / EXR / TIFF) — detects sequences automatically from folder
- Subfolder output per format (`/h264`, `/h265`, `/av1`)
- Filenames without suffixes in output

### Image converter
- Convert images and sequences to JPEG, PNG, WebP, AVIF
- Per-format quality sliders
- Resize by width (height scales automatically)
- Checkbox queue — select which files to process
- Rename output with templates: `{name}`, `{n}`
- Sequence support — converts full image sequences frame by frame

### Auto-update
- Checks for updates on launch via GitHub
- Green dot in header when update is available
- Downloads and launches new version automatically

---

## vibecoding by george adamia
