# quanyan8.github.io

Personal research homepage of Quanyan Zhu, served by GitHub Pages at https://quanyan8.github.io.

## Files

- `index.html`: homepage (bio, news, research, books, group, teaching, contact)
- `publications.html`: full publication list, **generated**; don't edit it by hand
- `assets/style.css`: shared styles (light and dark mode)
- `assets/cv.pdf`: public abridged CV (activities since 2022, no funding); regenerate with `MyCV 2026 Summer/CVs/make_web_cv.py`
- `agentic-ai/`: Agentic AI book site (single page with interactive error–recovery reliability lab, Prop. 2.13); edit directly
- `tokenomics/`: AI Tokenomics book site (single page with interactive context-replay cost calculator); edit directly
- `deception/`: Game Theory for Deception site (home with primer and interactive honeypot game, publications by theme, book, events); plain HTML sharing `deception/style.css`, edit directly
- `tools/build_publications.py`: rebuilds `publications.html` from the LaTeX list

## Updating

Publications: edit `MyCV 2026 Summer/quanyan_zhu_publications.tex`, then run

    python3 tools/build_publications.py

CV: run `python3 make_web_cv.py` in `MyCV 2026 Summer/CVs`, then copy `Web - Abridged/quanyan_zhu_cv_web.pdf` over `assets/cv.pdf`.

News and everything else: edit `index.html` directly.

Photo: `assets/photo.jpg` (800px JPEG made from `zhu31.png`, which is kept out of git).

Then commit and push; the site updates within a minute or two.

## Search

`index.html` and `publications.html` carry meta descriptions, Open Graph tags, and schema.org
JSON-LD (Person, Book, CollectionPage). When adding a new page or PDF, list it in `sitemap.xml`.
