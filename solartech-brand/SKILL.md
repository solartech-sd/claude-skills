---
name: solartech-brand
description: Apply SolarTech's official brand guidelines (colors, typography, logo usage, voice, writing rules) when building or styling any web page, landing page, component, README, or other visual/written deliverable for SolarTech. Use this skill automatically any time you are creating or editing HTML/CSS, React components, markdown pages, or marketing/UI copy in a SolarTech repo — even if the user just says "build a page," "make a landing page," "style this," or "write copy" without explicitly mentioning "brand" or "SolarTech guidelines." Always consult this before choosing colors, fonts, logo treatment, or tone for SolarTech work.
---

# SolarTech Brand Skill

Use this skill whenever building, styling, or writing copy for anything SolarTech-facing: web pages, landing pages, components, dashboards, README banners, ad creative, or marketing copy. It encodes SolarTech's 2026 Brand Guidelines so output is on-brand by default, without the user needing to repeat instructions every time.

Read `references/visual-spec.md` before writing any CSS/design tokens. Read `references/voice-and-writing.md` before writing any user-facing copy.

## Quick Reference

### Colors (use as CSS variables / design tokens)
| Name | Hex | Use |
|---|---|---|
| SolarTech Blue (primary) | `#183E6D` | Primary brand color — headers, backgrounds, primary UI |
| Blue Highlight | `#1886D1` | Links, secondary accents, interactive states |
| Blue Undertone | `#0C1F37` | Dark backgrounds, footers, high-contrast sections |
| SolarTech Orange (accent) | `#F58026` | CTAs, buttons, key accents — use sparingly for emphasis |
| Secondary Orange | `#EF8B22` | Secondary accent/hover states |
| Yellow Highlight | `#EDA726` | Tertiary accent, small highlights only |

Full palette must stay WCAG AA compliant. Blue is the dominant color; orange is the accent — do not flip this ratio (i.e., don't make pages orange-dominant).

### Typography
- **Primary font:** Roboto (Light, Regular, Medium, Bold) — use for body and most UI text
- **Secondary font:** Agenda One (Regular, Medium, Bold) — use for headlines/display text when available
- If neither is loadable (e.g., no Google Fonts access), fall back to a clean geometric sans (e.g., system-ui, Inter, or Helvetica Neue) rather than a serif or decorative font

### Logo
- Always default to the **horizontal logo with tagline** ("Solar That Works For You™") unless space is too tight, then drop to the icon+wordmark without tagline
- Use the **white/reversed logo variant** on any background that isn't white
- Never place the full-color logo over a dark or busy photo background — use the white variant instead
- Never recolor, tilt, crop, or stretch the logo
- Maintain a minimum clear space of 25px on all sides of the logo — no text, graphics, or layout edges inside that buffer

### Photography / imagery
- Real installs, real team members, real customers, natural lighting — not generic stock
- SoCal flavor is a plus (palm trees, coastline) since SolarTech is based there
- Clean, high-definition, free of clutter/trash in frame
- Vector illustrations are fine in brand colors; avoid overly stylized or low-quality stock photography
- Circular/curved masking elements on images are a recognizable SolarTech design motif — use them for photo treatments when appropriate
- Give generous spacing between elements and screen/artboard edges — nothing should feel cramped

## Voice & Tone (short version — see references/voice-and-writing.md for full detail)

Brand voice: **authentic, reliable, mission-driven.** Attributes: professional yet accessible, values-driven, customer-first. Tagline: **"Solar That Works For You™"**

Tone shifts by context but stays optimistic, empowering, reassuring, or inspirational depending on where it's used (see reference file for the full context table).

## Writing Rules (always apply to copy)
- Oxford comma, active voice
- Spell out numbers one–nine; use numerals for 10+
- No hype, no over-promising, no exaggerated claims — every statement must be accurate and verifiable
- Short paragraphs: 2–3 sentences max
- Use bullets to organize multiple points
- CTAs must be clear and calm, e.g. "Get a Free Quote," "Schedule Your Consultation," "See If Your Home Qualifies" — never gimmicky/pressure language like "Don't miss out!" or "Tap here for a crazy deal"

## Non-negotiables
- Only approved logo files/colors/fonts — no off-brand variations
- No hype or misleading claims, ever
- If content doesn't educate, build trust, or strengthen the brand, don't ship it

When in doubt on a specific visual or copy decision not covered above, check `references/visual-spec.md` or `references/voice-and-writing.md` for the full guideline text before improvising.
