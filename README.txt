# Quarto project — IV Jornadas de Medicina Intensiva de Braga

Files:
- `index.qmd`: your supplied slide content, preserved as provided.
- `_quarto.yml`: Reveal.js configuration.
- `theme.scss`: conference-inspired styling.
- `template-content-bg.png` and `template-title-bg.png`: extracted artwork from the supplied conference template.

Render with:
    quarto render index.qmd

Notes:
- The PPTX template is 16:9. The project retains a 1280 × 720 Reveal.js canvas.
- This recreates the supplied template's visual style in Reveal.js; it does not create slides based on the original PowerPoint master layouts.
- The source content contains an unfinished list item `- Falênci` and English placeholder text under “Indicações”. These were intentionally preserved rather than silently edited.
- If the conference requires the actual PPTX master/layouts, this Reveal.js theme is not a substitute for editing the original PPTX.
