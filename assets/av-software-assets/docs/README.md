# AV Software & Operations — Website Asset Library

**Edition:** 2026-11-20 · **Visual direction:** Silver + champagne / balanced premium tech.

## What is inside

- **121** original SVG icon files across 8 folders (**105 unique names**).
- Vector approximation of the selected interlocking AV monogram; transparent PNG extracted from your uploaded reference.
- Dark/light horizontal and stacked wordmarks; small favicons and platform app icons.
- 10 background SVGs; 8 system illustrations; 8 product emblems.
- 5 banner layouts, each in SVG and PNG.
- CSS tokens, icon manifest, HTML integration example, and original reference files.

## Important logo accuracy notice

`brand/master/av-monogram-vector-approx.svg` is an **algorithmic vector approximation** of the uploaded image, NOT the original source vector artwork. Its shape was threshold-traced. Fine metallic highlights and precise geometry may differ; inspect it against `brand/references/image(20261120-121517).png` before publishing as the official logo. The more faithful **transparent raster extraction** is `brand/png/av-monogram-metallic-transparent.png`.

Some wordmark exports reference **Manrope** and **Inter** by font name; these fonts are **not bundled**. Download them from the official licensed source if needed, or use your own licensed copies. On machines without them, SVG text uses Arial fallback. For exact branding, outline approved text in your vector editor after final approval.

The SVG icon collection is an independent, manually authored starter library—not an official Lucide distribution. Some filled versions are simple filled treatments of outline paths and should be inspected before use. OAuth/social provider logos are **not included**; retrieve official brand assets from each vendor and follow their trademark rules.

## Suggested placement on your site

Copy this whole folder to `public/assets` or to your HTML site's `assets/` folder.

```html
<link rel="icon" href="/assets/favicons/favicon.svg" type="image/svg+xml">
<link rel="stylesheet" href="/assets/tokens/brand.css">
<img src="/assets/brand/svg/av-horizontal-dark-tagline.svg" alt="AV Software & Operations">
<img src="/assets/icons/auth/lock.svg" width="24" height="24" alt="">
```

Use `<img>` for external SVGs. CSS `color` does **not** change an SVG loaded through `<img>`. For CSS `currentColor`, inline SVG markup or use the SVG as a CSS mask.

## Usage priorities

1. Confirm logo geometry against original supplied reference.
2. Use monochrome logo on light backgrounds and metallic logo on dark backgrounds.
3. Start with navigation + auth icon categories, add SaaS icons as needed.
4. Check 16px favicon visually; reduced detail may be preferable at small sizes.
5. Optimize images with your build system and add responsive versions where needed.

## Trademark, accessibility and licensing

- These generated AV assets originate from the user's supplied brand concepts; confirm rights to any externally commissioned/image-generated source art before trademark registration.
- Do not mistake conceptual system icons for official security provider badges.
- Decorative icons should have `alt=""`; icon-only buttons require accessible names.
- Check color contrast in both themes.
- No font files or official third-party brand marks are included.
