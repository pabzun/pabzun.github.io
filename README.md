# Pablo Zúñiga — personal website

Source for https://pabzun.github.io, built with Quarto and the Cosmo theme.

## Update content

- `index.qmd`: personal introduction, research overview, academic background, and highlighted events.
- `files/images/pablo-zuniga.jpeg`: homepage portrait.
- `research.qmd`: current questions, research interests, earlier projects, and scientific communication.
- `teaching.qmd`: teaching.
- `posts/`: event details, listed in `posts.qmd`.
- `contact.qmd`: contact links.
- `_quarto.yml`: navigation, metadata, and explicit render targets.

Run `quarto render` from the repository root. Commit the updated source and generated `docs/` folder. GitHub Pages serves `docs/` on the `main` branch.

## Temporarily hidden material

The previous publications and manuscripts page is preserved in `_archive/publications.qmd`, marked as a draft and excluded from the render targets. It is not deployed or included in search or the sitemap. To reactivate it intentionally, move it back to the root, remove its draft flag, and add it to the render targets and navigation.

The original CV and supporting private documents are not included in the public repository.

Adapted from [Gang He's Quarto Academic Website Template](https://github.com/drganghe/quarto-academic-website-template). See `LICENSE` for the template license.
