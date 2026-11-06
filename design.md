---
version: alpha
name: brittanychiang.com
description: Dark, minimalist portfolio homepage with a two-column editorial layout, strong typographic hierarchy, muted slate text, and restrained accent use for links, tags, and emphasis.
colors:
  background: "#0f172a"
  surface: "#111827"
  on-surface: "#e2e8f0"
  primary: "#eab308"
  secondary: "#14b8a6"
  tertiary: "#94a3b8"
  neutral: "#64748b"
  accent: "#14b8a6"
  text: "#94a3b8"
  link: "#e2e8f0"
  border: "#334155"
  card: "#0f172a"
  card-border: "#1e293b"
typography:
  fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji'"
  headline-display:
    fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif"
    fontSize: 48px
    lineHeight: 48px
    fontWeight: 700
    letterSpacing: -1.2px
  headline-lg:
    fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif"
    fontSize: 36px
    lineHeight: 43px
    fontWeight: 700
    letterSpacing: 1.4px
  headline-md:
    fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif"
    fontSize: 28px
    lineHeight: 34px
    fontWeight: 500
    letterSpacing: 0px
  body-lg:
    fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif"
    fontSize: 16px
    lineHeight: 26px
    fontWeight: 400
    letterSpacing: 0px
  body-md:
    fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif"
    fontSize: 14px
    lineHeight: 22px
    fontWeight: 400
    letterSpacing: 0px
  body-sm:
    fontFamily: "__inter_20b187, __inter_Fallback_20b187, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif"
    fontSize: 12px
    lineHeight: 18px
    fontWeight: 500
    letterSpacing: 0.04em
  label-lg:
    fontFamily: "Times New Roman, serif"
    fontSize: 14px
    lineHeight: 20px
    fontWeight: 700
    letterSpacing: 0px
  label-md:
    fontFamily: "Times New Roman, serif"
    fontSize: 14px
    lineHeight: 18px
    fontWeight: 500
    letterSpacing: 0px
  label-sm:
    fontFamily: "Times New Roman, serif"
    fontSize: 12px
    lineHeight: 16px
    fontWeight: 500
    letterSpacing: 0.08em
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px
spacing:
  xs: 2px
  sm: 12px
  md: 20px
  lg: 48px
  xl: 96px
components:
  button:
    primary:
      backgroundColor: "{colors.primary}"
      color: "#0f172a"
      border: "0px solid {colors.border}"
      borderRadius: "{rounded.sm}"
      padding: "12px 16px"
      minWidth: "181px"
      minHeight: "44px"
      fontFamily: "{typography.label-lg.fontFamily}"
      fontSize: "{typography.label-lg.fontSize}"
      fontWeight: "{typography.label-lg.fontWeight}"
      textDecoration: "none"
      boxShadow: "none"
    secondary:
      backgroundColor: "transparent"
      color: "{colors.tertiary}"
      border: "1px solid {colors.tertiary}"
      borderRadius: "{rounded.sm}"
      padding: "12px 16px"
      minWidth: "181px"
      minHeight: "44px"
      fontFamily: "{typography.label-lg.fontFamily}"
      fontSize: "{typography.label-lg.fontSize}"
      fontWeight: "{typography.label-lg.fontWeight}"
      textDecoration: "none"
      boxShadow: "none"
    link:
      backgroundColor: "transparent"
      color: "{colors.on-surface}"
      border: "0px solid transparent"
      borderRadius: "{rounded.none}"
      padding: "0px"
      minWidth: "0px"
      minHeight: "0px"
      fontFamily: "{typography.label-md.fontFamily}"
      fontSize: "{typography.label-md.fontSize}"
      fontWeight: "{typography.label-md.fontWeight}"
      textDecoration: "none"
      boxShadow: "none"
  card:
    backgroundColor: "{colors.surface}"
    color: "{colors.text}"
    border: "1px solid {colors.card-border}"
    borderRadius: "{rounded.md}"
    padding: "16px"
    boxShadow: "none"
---
# Overview

brittanychiang.com is a dark, content-first portfolio with a two-column layout, generous vertical rhythm, and understated visual ornament. The page prioritizes a clear personal introduction on the left and long-form biography plus experience entries on the right.

The tone is polished, technical, and confident. Typography does most of the work; color is restrained and used mainly for hierarchy, links, tags, and subtle emphasis.

# Colors

The palette is intentionally muted against a deep navy background. The visual hierarchy depends on contrast between soft slate text and near-white headings.

- Use `background` for the page canvas and broad section surfaces.
- Use `surface` for elevated content areas only when a distinct panel is needed.
- Use `on-surface` for primary headings, key labels, and high-emphasis text.
- Use `text` and `tertiary` for body copy and secondary metadata.
- Use `primary` sparingly for chips, focus states, and occasional accents.
- `secondary` can support interactive or brand-adjacent accents, but it should remain subordinate to the primary accent.

The screenshot shows a dark theme even though the extracted styleguide reports a light mode baseline. Treat the dark palette as the page’s actual presentation and keep saturation low.

# Typography

Inter is the primary text face for the page body and main headings. A serif face appears in small interface labels and button treatment, giving the site a subtle editorial contrast.

## Token guidance

- `headline-display`: hero name/title treatment, large and bold.
- `headline-lg`: section-style labels and navigational anchors.
- `headline-md`: role titles and prominent content headings.
- `body-lg`: standard paragraph copy.
- `body-md`: smaller body and metadata text.
- `body-sm`: section navigation labels and caps-like utility text.
- `label-lg`: button text and strong inline labels.
- `label-md`: compact UI labels and link-like controls.
- `label-sm`: all-caps or microcopy patterns.

## Usage notes

- Keep headings tight and measured; the homepage uses compact leading for the main name.
- Body text should stay readable at 16px with 26px line height.
- Uppercase micro-labels should use wider tracking and reduced visual weight.
- Avoid mixing too many font families; the serif utility face should remain limited to labels and buttons.

# Layout

The page is structured as a wide two-column composition with substantial negative space.

- Left column: identity, short bio, section navigation, and social links.
- Right column: stacked prose and chronological experience entries.
- The layout reads top-to-bottom, but the visual weight stays anchored by the hero and the first experience item.
- Spacing is generous: use `xl` to separate major regions, `lg` between blocks, `md` for internal grouping, `sm` for tighter item spacing, and `xs` for very fine adjustments.

Implementation guidance:
- Preserve the airy editorial feel; do not collapse the left rail into dense navigation.
- Keep the main content width constrained enough for comfortable paragraph measure.
- Maintain clear alignment between the date column and the experience content.

# Elevation & Depth

Depth is nearly flat throughout the interface.

- Shadows are absent across buttons, cards, and panels.
- Use contrast, spacing, and borders instead of elevation to indicate grouping.
- Any card-like treatment should remain subtle and lightweight.

# Shapes

Corners are small and restrained.

- `rounded.sm` is the default interactive radius.
- `rounded.md` is appropriate for content cards.
- `rounded.full` is reserved for pill tags and chips.
- Avoid large or playful radii; the site’s personality is crisp and controlled.

# Components

## Buttons

Primary and secondary buttons share the same footprint and text treatment, differing mainly in fill and border.

- Use `button.primary` for strongest calls to action.
- Use `button.secondary` for lower-emphasis actions or external links that should still look deliberate.
- Use `button.link` for minimalist navigation or inline controls.

Do not add shadows, gradients, or icon-heavy button chrome unless the interaction truly requires it.

## Cards

Cards are simple bordered containers used for content blocks.

- Keep padding at 16px.
- Use the card border to separate content from the background.
- Do not add elevation or decorative overlays.

## Experience entries

Experience items should follow the screenshot pattern:
- date in a narrow left column
- role/company title on the right
- supporting description beneath
- technology tags in a compact row below

Tags should remain pill-shaped, tightly padded, and low-contrast.

## Navigation and links

The left-side section nav uses understated horizontal markers and uppercase labels. Links should feel editorial, not button-like.

- Default link color should stay muted until hover or focus.
- External-link indicators may be appended to experience titles.
- Social icons should remain small and monochrome.

# Do's and Don'ts

## Do

- Do preserve the dark, minimal, high-contrast editorial feel.
- Do use typography hierarchy before introducing additional color or decoration.
- Do keep body copy at 16px/26px for comfort.
- Do keep experience content in a clear date/title/description/tag structure.
- Do use pill tags with full rounding and compact spacing.
- Do keep shadows off unless a future pattern explicitly needs depth.

## Don't

- Don't introduce bright gradients, glassmorphism, or heavy neon accents.
- Don't use large rounded corners on primary layout blocks.
- Don't turn text links into prominent buttons.
- Don't compress the layout into a generic centered landing page.
- Don't add multiple competing accent colors; keep the palette disciplined.
- Don't over-style cards or introduce unnecessary elevation.