# Reveal.js slide template (Quarto)

Starter deck for Quarto `revealjs` presentations.

## Files

- `template.qmd` – the slides
- `references.bib` – sample bibliography (replace with your own)
- `custom.scss` – theme (fonts, font size)
- `images/` – placeholder images

## Use

1. Copy this folder and rename it.
2. Rename `template.qmd`, then edit the title, author and date in the YAML header.
3. Render:

   ```bash
   quarto render template.qmd
   ```

## Slides included

Blank slide, body text with speaker notes (press `S` to open speaker view), footnotes, one image, two images, incremental bullets, citations, and a references slide.

## Notes

- Cite with `[@key]` (parenthetical) or `@key` (narrative); keys come from `references.bib`.
- Hover footnotes are commented out in the YAML. To enable them, uncomment `footnotes-hover` and `reference-location: document`.
- For a specific citation style, add `csl: your-style.csl` to the YAML.
