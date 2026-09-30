# Convex optimization study notes

A single-file Korean study book, prepared as `index.html` for static hosting. No build step or backend is required.

## Contents

- `index.html`: unchanged, byte-for-byte copy of the supplied `convex-course.html`
- Embedded scripts, KaTeX, fonts, and 401 lecture-slide images
- Client-side hash navigation and interactive exercises
- Study answers and notes stored in the visitor’s browser local storage; use the in-app progress export/import when moving to another origin or device

## Before public publication

The file includes third-party lecture-slide images and references to textbook/solutions material. Its existing notice describes the images as provided for personal study. Confirm permission for public redistribution before publishing. Public hosting exposes the complete HTML and all embedded materials to visitors. This package does not grant or establish redistribution rights.

## Validation

- All six inline JavaScript blocks passed syntax checks (`node --check`)
- Static inspection found no external asset dependencies or network-request calls
- Browser rendering and interactive behavior have not been tested
- Hosted HTTPS should support the client-side behavior, but a deployed browser test is still needed
- Original HTML size: 20,009,444 bytes
- Original and `index.html` SHA-256: `fad367b1f8bae786d2ee056e777c439d13ebbab6f649683000d4282a0714c9a2`

Only publish the contents of this folder after authorizing the destination and public access. No repository or deployment has been created by preparing this folder.
