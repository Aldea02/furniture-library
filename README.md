# Furniture library

3D furniture models for a floor-plan editor's object library, served as static
files through GitHub Pages.

## Layout

- `index.json` lists the brands.
- `brands/<brand>/catalog.json` lists a brand's models with their sizes.
- `brands/<brand>/models/*.glb` are the models; `thumbnails/*.webp` are previews.

## Licences

| Brand | Source | Licence |
| --- | --- | --- |
| Poly Haven | <https://polyhaven.com> | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain) |

The Poly Haven models were converted to self-contained `.glb` files, placed on
the floor at the origin and measured. Their geometry and 1K textures are
otherwise unchanged.
