# Jiaming Feng — Personal Homepage

Source for my personal academic homepage, served via **GitHub Pages** at
**<https://jarm1ng.github.io>**.

I am a researcher in medical image analysis and surgical computer vision at the
University of Leeds (AI in Medicine & Surgery Group, under Dr Sharib Ali),
working on geometry-aware 3D–2D registration, anatomical landmark segmentation,
and augmented-reality guidance for image-guided liver intervention.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The entire site — a single self-contained file (HTML, CSS and JS inline). |
| `og-image.png` | Social-share preview card. |
| `Jiaming_Feng_CV.pdf` | Downloadable CV. |

## Notes

The page is a dependency-free static site (only Google Fonts is loaded
externally). It features light/dark themes with system-preference detection,
a scroll-driven research timeline, full keyboard accessibility, reduced-motion
support, responsive layout from mobile to desktop, and JSON-LD structured data.

To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
