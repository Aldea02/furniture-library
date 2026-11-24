# Furniture library

3D furniture models for a floor-plan editor's object library, served as static
files through GitHub Pages.

## Layout

- `index.json` lists the brands.
- `brands/<brand>/catalog.json` lists a brand's models with their sizes.
- `brands/<brand>/models/*.glb` are the models; `thumbnails/*.webp` are previews.

## Licences

Every model is free to use under its own licence, recorded in its brand's
`catalog.json` (`license`, `author`, `url`). Models under CC BY must keep their
author's credit, which the app shows with each model.
