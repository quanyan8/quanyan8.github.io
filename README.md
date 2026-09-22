# quanyan8.github.io

Personal research homepage of Quanyan Zhu, served by GitHub Pages at https://quanyan8.github.io.

## Files

- `index.html`: homepage (bio, news, research, books, group, teaching, contact)
- `publications.html`: full publication list, **generated**; don't edit it by hand
- `assets/style.css`: shared styles (light and dark mode)
- `assets/cv.pdf`: public CV (the "No Funding History" variant)
- `tools/build_publications.py`: rebuilds `publications.html` from the LaTeX list

## Updating

Publications: edit `MyCV 2026 Summer/quanyan_zhu_publications.tex`, then run

    python3 tools/build_publications.py

CV: copy the new PDF over `assets/cv.pdf`.

News and everything else: edit `index.html` directly.

Photo: `assets/photo.jpg` (800px JPEG made from `zhu31.png`, which is kept out of git).

Then commit and push; the site updates within a minute or two.
