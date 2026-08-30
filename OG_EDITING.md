# Editing the social-preview image

The editable master is `og-editable.svg`. It is a 1200 × 630 RGB design that can be opened directly in Adobe Illustrator.

1. Open `og-editable.svg` in Adobe Illustrator while keeping the `figures` folder beside it.
2. Use the Layers panel to edit the portrait, color panels, title, research direction, divider, or URL separately.
3. To use another portrait, replace `figures/og-profile-crop.jpg` with a new image of the same name, or relink the image from Illustrator's Links panel.
4. Export with **File → Export → Export As… → PNG** at 1200 × 630 pixels in RGB.
5. Name the exported file `og.png` and replace the existing `og.png` in the repository.

The website already points to `https://yyucuhk.github.io/og.png`, so no HTML change is needed after replacing the PNG.
