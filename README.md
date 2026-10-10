# Pablo Zúñiga — academic website

Source for https://pabzun.github.io, built with Quarto and the Cosmo theme.

## Update content

- `index.qmd`: biography, education, experience, recognition, and highlighted events.
- `research.qmd`: research projects and software.
- `publications.qmd`: manuscripts and thesis; preserve their actual publication status.
- `teaching.qmd`: teaching experience.
- `posts/`: academic news and events, listed in `posts.qmd`.
- `contact.qmd`: contact links.
- `_quarto.yml`: navigation, site metadata, and render targets.

Run `quarto render` from the repository root. Commit the updated source and generated `docs/` folder. GitHub Pages serves the generated site from `docs/` on the `main` branch.

The website content is based on the author’s CV and recent workshop and recognition documents. The original private documents are not included in the public repository.

Adapted from [Gang He's Quarto Academic Website Template](https://github.com/drganghe/quarto-academic-website-template). See `LICENSE` for the template license.
