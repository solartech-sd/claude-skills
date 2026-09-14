# SolarTech Visual Spec (Full Detail)

Source: SolarTech Branding Guidelines 2026

## Color Palette (full values)

| Name | HEX | RGB | CMYK |
|---|---|---|---|
| SolarTech Blue | #183E6D | (24, 62, 109) | 77.98%, 43.12%, 0%, 57.25% |
| Blue Highlight | #1886D1 | (24, 134, 209) | 88.52%, 35.89%, 0%, 18.04% |
| Blue Undertone | #0C1F37 | (12, 31, 55) | 78.18%, 43.64%, 0%, 78.43% |
| SolarTech Orange | #F58026 | (245, 128, 38) | 0%, 47.76%, 84.49%, 3.92% |
| Secondary Orange | #EF8B22 | (239, 139, 34) | 0%, 41.84%, 85.77%, 6.27% |
| Yellow Highlight | #EDA726 | (237, 167, 38) | 0%, 29.54%, 83.97%, 7.06% |

Rationale: Blue = trust, reliability, technical strength (core/dominant color, deep tone for contrast). Orange = warmth, energy, connection to solar power (accent color for hierarchy). All pairings must remain WCAG AA compliant.

CSS variable suggestion:
```css
:root {
  --st-blue: #183E6D;
  --st-blue-highlight: #1886D1;
  --st-blue-undertone: #0C1F37;
  --st-orange: #F58026;
  --st-orange-secondary: #EF8B22;
  --st-yellow-highlight: #EDA726;
}
```

## Typography

- **Primary: Roboto** — weights Light, Regular, Medium, Bold
- **Secondary: Agenda One** — weights Regular, Medium, Bold (use for headline/display treatments)
- Both are used across brand collateral; Roboto is the workhorse font, Agenda One adds character to headlines.

## Logo Rules

- Always default to the **newest horizontal logo** (the one with the tagline "Solar That Works For You™") unless spacing makes it infeasible, in which case drop the tagline.
- Use the **white logo variant** whenever the background isn't white (including photos, dark colors, brand blue backgrounds).
- **Clear space:** minimum 25px buffer on all four sides of the logo. Nothing — no text, image, or layout edge — may enter that buffer. This applies to every logo variation (color, monochrome, reversed).

### Incorrect usage (never do these)
- Never recolor the logo outside the approved palette
- Never tilt/rotate the logo
- Never crop the logo
- Never place the full-color logo over a photo with a dark background (use white variant instead)

## Photography Direction

SolarTech photography should feel **authentic, professional, and people-focused**: real installations, real team members, real customers, natural lighting, real environments.

- SoCal setting (palm trees, ocean, hillside homes) is a plus — reinforces the brand's regional identity
- Use real installs and real customers over staged/generic stock
- Use conceptual imagery sparingly
- Clean vector illustrations in brand colors are acceptable
- Avoid low-quality or overly stylized stock images
- Images/backgrounds must be high-definition and free of clutter or trash in frame

## Layout & Design System Notes

- SolarTech frequently uses **circular/curved elements to mask images** — a recognizable design motif worth reusing in page/component design
- All elements must be properly aligned per standard design practice, with clean, consistent spacing between elements
- Maintain generous space between text blocks and the edge of the canvas/viewport/artboard — avoid cramped layouts
