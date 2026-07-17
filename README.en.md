# 3D Product Card Effect

![Preview](assets/preview.svg)

A product card with 3D tilt, layered depth, dynamic glare, and spring-like return.

## Features

- Perspective derived from cursor position.
- Synchronized glare and spring return curve.
- Touch-friendly button to demonstrate the tilt.
- Fine-pointer and reduced-motion safeguards.
- Object, content, and controls visible in one shot.

## Live demo

[card3d.ntdesweb.dev](https://card3d.ntdesweb.dev/)

## More effect demos

- [Before/After Image Slider](https://fxpreview.ntdesweb.dev/)
- [Hacker Text](https://hacker.ntdesweb.dev/)
- [Magnetic Button](https://magnetic.ntdesweb.dev/)

## Installation

Clone the repository, enter `3d-product-card-effect`, and open `index.html`.

## Project structure

The interface is in `index.html`, depth in `style.css`, the compact shot in `capture.css`, geometry in `script.js`, and previews in `assets/`.

## Customization

Change rotation limits, `perspective`, `translateZ` layers, and color tokens.

## Accessibility

Information remains stable without 3D, controls are native, and movement is removed when requested.

## Performance

Uses accelerated transforms, a single pending frame, and no external resources.

## License and credits

[MIT](LICENSE). Created by [Nacho Torres](https://github.com/NachoTorresRD) for [NTDESWEB](https://www.ntdesweb.com) with [NT-SKILL SUPREME](https://github.com/NachoTorresRD/nt-skill-supreme).

[View on GitHub](https://github.com/NachoTorresRD/3d-product-card-effect) · [Work with NTDESWEB](https://www.ntdesweb.com)
