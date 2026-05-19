# PiP — Leaf & Amber Design System
> Children's nature journal on sage paper — warm green canvas with amber accents, where evidence-based parenting feels approachable and trustworthy.

**Theme:** light

PiP lands like a calm, expert guide — sage canvas (#f4f8f4, a barely-perceptible green tint) paired with deep forest green (#1a8030) for CTAs and warm amber (#c87a08) as a genuinely contrasting accent from a different colour family. Plus Jakarta Sans at 68px with tight -0.031em tracking carries the hero weight, with progressively tighter letter-spacing as sizes increase throughout all UI text. Cards use an inset sage border (a single 1px shadow at #c8dcc8) instead of drop shadows, keeping surfaces flat and tactile. The primary CTA pill in forest green (#1a8030) is the single vivid moment of contrast in an otherwise light, airy layout. Illustrations are provided as PNG files and appear as grey placeholders during the design phase; photography may be used in select sections, also as grey placeholders until final assets are placed.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sage Canvas | `#f4f8f4` | `--color-sage-canvas` | Page background, nav background, light button fill |
| Sage Surface | `#e5f0e5` | `--color-sage-surface` | Panel backgrounds, secondary button background, subtle dividers |
| Sage Panel | `#edf4ed` | `--color-sage-panel` | Feature card backgrounds, recessed containers |
| Timber | `#162016` | `--color-timber` | Body text, nav links, card body copy — the dominant text colour across the entire page |
| Forest Primary | `#1a8030` | `--color-forest-primary` | Primary CTA button fill, success indicators, primary brand green |
| Deep Forest | `#0d5020` | `--color-deep-forest` | Hyperlinks, dark green accents — AAA contrast 8.9:1 on canvas |
| Amber | `#c87a08` | `--color-amber` | Decorative accent — icon fills, card border accents, callout highlights. Never used as body text. |
| Amber Text | `#986008` | `--color-amber-text` | Amber in text contexts — callout labels, badge text on white (AA 4.9:1) |
| Amber Wash | `#fdf3e0` | `--color-amber-wash` | Amber background fills — callout boxes, badge/tag backgrounds |
| Timber Muted | `#4e6456` | `--color-timber-muted` | Captions, metadata, secondary labels — strong AA at 6.0:1 |
| Ash | `#6a7a6a` | `--color-ash` | Muted body text, secondary nav labels |
| Fog | `#a8bca8` | `--color-fog` | Footer text, inactive borders, dividers |
| Smoke | `#8ca08c` | `--color-smoke` | Disabled states, placeholder text, tertiary labels |
| Pepper | `#2a3828` | `--color-pepper` | Dark nav overlay text, deep secondary labels |
| Midnight | `#0d1610` | `--color-midnight` | Darkest text, near-black for high-contrast elements |
| Obsidian | `#000000` | `--color-obsidian` | True black — dark card backgrounds, icon fills |
| Lime | `#8cd422` | `--color-lime` | Badge and tag backgrounds only — always paired with dark text (AAA 9.2:1) |
| Lime Wash | `#d4f0cc` | `--color-lime-wash` | Success state backgrounds, positive card washes |
| Graphic Green | `#1a9030` | `--graphic-green` | Illustration and icon fills — vivid green |
| Graphic Amber | `#c87a08` | `--graphic-amber` | Illustration and icon fills — vivid amber |
| Graphic Lime | `#8cd422` | `--graphic-lime` | Illustration fills — vivid lime |
| Coral Red | `#c02818` | `--color-coral-red` | Error state indicator, destructive action colour |
| Valid Green | `#1a8030` | `--color-valid-green` | Success/valid input state — same as Forest Primary |

## Tokens — Typography

### Plus Jakarta Sans — The single typeface for the entire site. 68px/500 with -0.031em tracking for hero headlines, scaling through all UI text: nav (14px/500), body copy (15-17px/400), card labels (13px/500), buttons (14-15px/500-600), captions (12px/400). Letter-spacing tightens with size. · `--font-sans`
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 19px, 23px, 44px, 68px
- **Line height:** 1.00–1.58
- **Letter spacing:** -2.11px at 68px, -1.14px at 44px, -0.44px at 23px, -0.25px at 19px, -0.22px at 17px, -0.16px at 16px, -0.20px at 15px, -0.18px at 14px, -0.17px at 13px, -0.12px at 12px
- **OpenType features:** `normal`
- **Role:** All text across the site — from 68px display headlines to 12px captions. A single geometric sans-serif that feels warm and approachable without needing a separate display face.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.58 | -0.14px | `--text-caption` |
| body | 15px | 1.47 | -0.2px | `--text-body` |
| heading-sm | 19px | 1.38 | -0.25px | `--text-heading-sm` |
| heading | 23px | 1.2 | -0.44px | `--text-heading` |
| heading-lg | 44px | 1.09 | -1.14px | `--text-heading-lg` |
| display | 68px | 1.09 | -2.11px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 92 | 92px | `--spacing-92` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 6px |
| cards | 10px |
| icons | 40px |
| inputs | 10px |
| buttons | 32px |
| cardsLarge | 24px |
| buttonsPill | 32px |
| illustrations | 72px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `color(display-p3 0.94902 0.941176 0.929412) 0px 0px 0px 1...` | `--shadow-subtle` |
| subtle-2 | `color(display-p3 0.94902 0.941176 0.929412) 0px 0px 0px 0...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.04) 0px 0px 0px 1px` | `--shadow-subtle-3` |
| lg | `rgba(0, 0, 0, 0.15) 0px 0px 24px 0px` | `--shadow-lg` |
| sm | `rgba(0, 0, 0, 0.04) 0px 1px 6px 0px, rgba(0, 0, 0, 0.05) ...` | `--shadow-sm` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 120-180px
- **Card padding:** 32px
- **Element gap:** 8-12px

## Components

### Primary CTA Button (Pill Dark)
**Role:** Main conversion action — 'Get Started', 'Find your program'

Background #1a8030, text #ffffff, border-radius 32px, padding 0px 14px. Inter 14px weight 500-600. The forest green pill floats against #f4f8f4 canvas as the site's primary action. Hover state darkens to #0d5020 via 0.2s ease transition.

### Secondary CTA Button (Pill Light)
**Role:** Alternative actions — 'Log In', 'Learn more'

Background #e5f0e5 (sage), text #162016, border-radius 32px, padding 0px 14px. Inter 14px weight 500. Creates a paired hierarchy with the green pill without competing — same shape, lighter sage surface.

### Ghost Text Link Button
**Role:** Inline navigation links — 'Learn more', section CTAs

Background transparent, text color #0d5020 (Deep Forest), border-radius 0px, padding 4px 0px. No border. Inter 14-15px weight 500. The deep green text link is the signature inline action — dark forest on sage canvas reads as calm confidence without a button shell.

### Outlined Navigation Button
**Role:** Tertiary actions in nav or contextual contexts

Background transparent, text #162016 (Timber), border 1px solid #162016, border-radius 12px, padding 12px 32px 12px 12px. Inter 14px weight 500. Used for modal-adjacent actions that need definition without weight.

### Feature Card (White)
**Role:** Primary content cards — feature descriptions, testimonials

Background white (display-p3 1 1 1), border via inset box-shadow: color(display-p3 0.784 0.863 0.784) 0px 0px 0px 1px inset (sage border, ~#c8dcc8), border-radius 10px, padding 32px all sides. The inset shadow technique keeps borders off-layout-flow — cards look hand-placed on the canvas.

### Feature Card (Warm Cream)
**Role:** Secondary content panels — screenshot containers, demo previews

Background #edf4ed (display-p3 0.929 0.957 0.929), no box-shadow, border-radius 12px, padding 0px 22.8px 14px 22.8px. Slightly sunken into the page — the sage tint against #f4f8f4 creates a 1-level depth shift without any shadow.

### Dark Phone Mockup Card
**Role:** Product screenshot showcase — wallet UI demonstrations

Background #000000, border-radius 24px (top) 0px 0px 24px (bottom), box-shadow rgba(0,0,0,0.15) 0px 0px 24px 0px, padding 4px 0px 4px 4px. The only true drop shadow on the page — reserved for the product hero moment, making the dark phone pop off the cream background.

### Testimonial Card
**Role:** Social proof — Twitter/X quotes in 'Friends of Family' section

Background white, border via inset sage shadow (same as Feature Card White), border-radius 10px, padding 32px. Contains avatar (circular, ~40px), handle in Inter 13px #4e6456, body in Inter 15px #162016, icon in top-right. Horizontally scrolling or grid-arranged.

### Illustration / Image Placeholder
**Role:** Illustrations (PNG) and photography used in context — hero, feature sections, editorial moments

During design, all illustrations and images are represented as solid grey (#d4d4d4) placeholder boxes at the intended dimensions. Final PNG illustrations and photography are dropped in after the layout is approved. No sizing or border-radius constraint is fixed — each section determines what fits its composition.

### Navigation Bar
**Role:** Sticky top navigation

Background #f4f8f4 (canvas), height ~64px, box-shadow rgba(0,0,0,0.04) 0px 0px 0px 1px (barely-there outline). Logo left, nav links center in Inter 14px #162016 weight 500, 'Log In' light sage pill and 'Get Started' forest green pill right. Dropdown chevrons on nav items.

### Section Heading
**Role:** Page section titles

Plus Jakarta Sans 500 at 68px with -2.11px letter-spacing and line-height 1.09 for hero. Plus Jakarta Sans 600 at 44px with -1.14px letter-spacing for sub-section heads. Color #162016. Always left-aligned or centered — no right-aligned headlines.

### Colored Action Badge
**Role:** Transaction type labels inside wallet UI mockups — Send, Receive, Purchase

Circular icon badge: background in brand color (Meadow Green for Receive, Flamingo for Purchase), icon in white, border-radius 40px, ~40px diameter. Acts as the only iconographic navigation within the dark phone card context.

## Do's and Don'ts

### Do
- Use #f4f8f4 as page background — never pure white (#ffffff) at canvas level; the barely-perceptible sage cast is the foundation of the site's feel.
- Apply the inset sage border (box-shadow: color(display-p3 0.784 0.863 0.784) 0px 0px 0px 1px inset) on all white cards instead of a CSS border property — keeps cards off-layout-flow.
- Use border-radius 32px for all pill buttons (both #1a8030 green and #e5f0e5 sage light variants) — the pill shape is non-negotiable for interactive elements.
- Apply tight negative letter-spacing to all large text: -2.11px at 68px display, -1.14px at 44px heading-lg, scaling to near-zero at body sizes.
- Use Plus Jakarta Sans for all text across the site — from 68px display headlines to 12px captions.
- Use Amber (#c87a08) exclusively for decorative accents, icon fills, and callout highlights — never as body text or button background fill. Use Deep Forest (#0d5020) for all hyperlinks.
- Use grey placeholder boxes (#d4d4d4) at intended dimensions for all illustrations and images during design — finalize asset placement after layout is approved.

### Don't
- Don't use drop shadows on content cards — the inset sage border is the only surface definition mechanism; shadows appear only on dark shell cards and hover-elevated states.
- Don't use pure #ffffff as a page background — it breaks the sage canvas identity; #f4f8f4 is the minimum threshold.
- Don't use Plus Jakarta Sans weight 700+ — the site uses max weight 600; heavier weights break the light, approachable feel.
- Don't apply Amber (#c87a08) to more than one prominent UI element per viewport — its rarity as the contrasting accent is what gives it visual impact; overuse collapses the hierarchy.
- Don't use border-radius below 10px on cards — the minimum card radius is 10px; anything sharper breaks the soft-edged system.
- Don't use Lime (#8cd422) or Coral Red (#c02818) as text or link colours — Lime is for badge/tag backgrounds only (always with dark text), Coral Red for error states only.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#f4f8f4` | Page background — barely perceptible green-white, the site's clean foundation |
| 2 | Card Surface | `#ffffff` | Pure white card faces with a light sage inset border — floats above canvas |
| 3 | Recessed Panel | `#edf4ed` | Screenshot and demo container backgrounds — light sage, sits below card level |
| 4 | Sage Tint | `#e5f0e5` | Secondary button backgrounds, inset border reference, hover states on canvas |
| 5 | Dark Shell | `#000000` | Dark card backgrounds — reserved for high-contrast showcase moments |

## Elevation

- **Feature Card (White):** `color(display-p3 0.784 0.863 0.784) 0px 0px 0px 1px inset`
- **Dark Phone Mockup Card:** `rgba(0, 0, 0, 0.15) 0px 0px 24px 0px`
- **Navigation Bar:** `rgba(0, 0, 0, 0.04) 0px 0px 0px 1px`
- **Elevated Card (hover/active):** `rgba(0, 0, 0, 0.04) 0px 1px 6px 0px, rgba(0, 0, 0, 0.05) 0px 0px 24px 0px`

## Imagery

Illustrations are supplied as PNG files and placed into the layout after design is complete. Photography may be used in select sections (editorial moments, team, lifestyle). During the design phase, all illustration and image slots are represented by solid grey (#d4d4d4) placeholder boxes at the intended dimensions and aspect ratio — no fake content, no lorem images. Each section determines its own composition and image treatment; there is no fixed illustration density or placement rule. Product screenshots appear inside dark rounded mockups (border-radius 24px) where needed. Icons are filled monochrome at small sizes.

## Layout

Max-width ~1200px centered on the warm canvas. Hero is full-viewport with headline text in Plus Jakarta Sans 500 at 68px. Below hero: alternating sections with generous vertical gaps (120-180px). Each section has design flexibility in its layout and card treatment — consistency comes from the shared color palette, type scale, and spacing tokens, not from repeating the same card pattern. Illustration and image placeholders (grey boxes) sit at the intended dimensions within each section's composition. Navigation is a fixed top bar with logo left, links center, actions right. Footer is minimal — link grid on canvas background. No sidebar, no mega-menu.

## Agent Prompt Guide

**Quick Color Reference**
- Page background: #f4f8f4 (sage canvas, barely perceptible green tint)
- Primary text: #162016 (Timber)
- Heading text: #162016 (Timber)
- CTA button (primary): #1a8030 background, #ffffff text
- CTA button (light): #e5f0e5 background, #162016 text
- Hyperlinks: #0d5020 (Deep Forest) — AAA 8.9:1
- Decorative accent: #c87a08 (Amber) — icons, callout borders, highlights
- Card border: box-shadow inset ~#c8dcc8 (sage) 1px
- Muted text: #4e6456 (Timber Muted)

**Example Component Prompts**

1. **Hero Section**: Background #f4f8f4. Headline in Plus Jakarta Sans 500 at 68px, color #162016, letter-spacing -2.11px, line-height 1.09. Subtext at 16px Plus Jakarta Sans 400, color #162016, max-width 480px. Two pill buttons: primary (#1a8030 background, #ffffff text, 32px radius, 0px 14px padding) and light (#e5f0e5 background, #162016 text, 32px radius, 0px 14px padding). Illustration/image area: grey placeholder (#d4d4d4) at intended dimensions — final PNG or photo drops in after layout approval.

2. **Testimonial Card**: Background #ffffff, inset sage border (box-shadow color(display-p3 0.784 0.863 0.784) 0px 0px 0px 1px inset), border-radius 10px, padding 32px. Top-right: X/Twitter icon in #162016. User row: circular avatar 40px, name in Plus Jakarta Sans 500 14px #162016, handle in Plus Jakarta Sans 400 13px #4e6456. Quote in Plus Jakarta Sans 400 15px #162016 letter-spacing -0.20px.

3. **Navigation Bar**: Background #f4f8f4, height 64px, box-shadow rgba(0,0,0,0.04) 0px 0px 0px 1px. Logo (square icon + wordmark) at left in #162016 Plus Jakarta Sans 500 15px. Center links: Plus Jakarta Sans 500 14px #162016 with dropdown chevrons. Right: 'Log In' light pill + 'Get Started' primary pill (#1a8030, 32px radius).

4. **Section Heading Block**: Plus Jakarta Sans 600 at 44px, color #162016, letter-spacing -1.14px, line-height 1.09. Optional amber accent word in same size but color #c87a08. Supporting body text below at Plus Jakarta Sans 400 17px #162016, letter-spacing -0.22px, max-width 560px. Section gap above: 120-180px.

5. **Content Section (flexible)**: Each section defines its own layout — no fixed card pattern required. Use shared tokens (color, type scale, spacing, border-radius) to maintain consistency. Image/illustration areas: grey (#d4d4d4) placeholders at intended dimensions. Cards may use #ffffff with inset sage border, #edf4ed recessed panels, or full-bleed color bands — chosen per section to suit the content.

## Illustration & Image Placeholders

Illustrations are final PNG assets placed after the layout is approved. Photography may be used in select sections. During the design phase, all visual asset slots — whether illustration or photo — are represented as solid grey (#d4d4d4) placeholder boxes at the intended dimensions and aspect ratio.

**Placeholder color:** `#d4d4d4`
**Rule:** Size and shape the placeholder to match the intended asset. No fake images, no stock fillers.
**CSS token reference for illustration accent colors (when tinting or bordering containers):** `--graphic-green`, `--graphic-amber`, `--graphic-lime`

## Motion Philosophy

Motion personality is 'expressive' with 0.2s ease as the base duration (123 instances). Key patterns:

**Micro-interactions**: 0.1-0.2s ease for hover states on buttons (background color, box-shadow). Buttons likely scale or lighten slightly.

**Illustration animation**: 1s duration with cubic-bezier(0.19, 1, 0.22, 1) — the 'snappy overshoot' easing suggests characters bounce or spring into position on scroll entry.

**Transition properties**: Transform (103×) and opacity (44×) dominate — elements slide or fade in rather than recoloring. Box-shadow transitions (33×) animate card hover elevations.

**Named animation 'hdKGda'**: Custom keyframe animation, likely the floating/bobbing motion on hero illustration characters.

**Rule**: Never use linear easing on visible UI — the brand is expressive, and linear motion reads as mechanical. Default to ease or the cubic-bezier(0.19, 1, 0.22, 1) spring curve.

## Similar Brands

- **Lunchbox** — Same warm off-white canvas with flat illustrated characters as primary brand expression — both use illustration density to make a transactional product feel playful
- **Linear** — Shares the tight negative letter-spacing system and custom display typeface approach, though Linear goes dark where Family stays cream
- **Notionforms** — Same inset-border card technique (1px warm-toned inner ring) and Inter-based UI text system on warm-white backgrounds
- **Superhuman** — Pill buttons in near-black paired with a secondary cream pill — identical button pairing strategy and tight tracking on Inter headings
- **Raycast** — Tight negative letter-spacing on geometric sans-serif across all scales — same single-typeface approach

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sage-canvas: #f4f8f4;
  --color-sage-surface: #e5f0e5;
  --color-sage-panel: #edf4ed;
  --color-timber: #162016;
  --color-forest-primary: #1a8030;
  --color-deep-forest: #0d5020;
  --color-amber: #c87a08;
  --color-amber-text: #986008;
  --color-amber-wash: #fdf3e0;
  --color-timber-muted: #4e6456;
  --color-ash: #6a7a6a;
  --color-fog: #a8bca8;
  --color-smoke: #8ca08c;
  --color-pepper: #2a3828;
  --color-midnight: #0d1610;
  --color-obsidian: #000000;
  --color-lime: #8cd422;
  --color-lime-wash: #d4f0cc;
  --color-coral-red: #c02818;
  --color-valid-green: #1a8030;
  --graphic-green: #1a9030;
  --graphic-amber: #c87a08;
  --graphic-lime: #8cd422;

  /* Typography — Font Families */
  --font-sans: 'Plus Jakarta Sans', system-ui, sans-serif;
  --font-mono: 'Geist Mono';

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.58;
  --tracking-caption: -0.14px;
  --text-body: 15px;
  --leading-body: 1.47;
  --tracking-body: -0.2px;
  --text-heading-sm: 19px;
  --leading-heading-sm: 1.38;
  --tracking-heading-sm: -0.25px;
  --text-heading: 23px;
  --leading-heading: 1.2;
  --tracking-heading: -0.44px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.09;
  --tracking-heading-lg: -1.14px;
  --text-display: 68px;
  --leading-display: 1.09;
  --tracking-display: -2.11px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-92: 92px;
  --spacing-96: 96px;
  --spacing-104: 104px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 120-180px;
  --card-padding: 32px;
  --element-gap: 8-12px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 17px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 72px;

  /* Named Radii */
  --radius-tags: 6px;
  --radius-cards: 10px;
  --radius-icons: 40px;
  --radius-inputs: 10px;
  --radius-buttons: 32px;
  --radius-cardslarge: 24px;
  --radius-buttonspill: 32px;
  --radius-illustrations: 72px;

  /* Shadows */
  --shadow-subtle: color(display-p3 0.784 0.863 0.784) 0px 0px 0px 1px inset;
  --shadow-subtle-2: color(display-p3 0.784 0.863 0.784) 0px 0px 0px 0px inset;
  --shadow-subtle-3: rgba(0, 0, 0, 0.04) 0px 0px 0px 1px;
  --shadow-lg: rgba(0, 0, 0, 0.15) 0px 0px 24px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 1px 6px 0px, rgba(0, 0, 0, 0.05) 0px 0px 24px 0px;

  /* Surfaces */
  --surface-canvas: #f4f8f4;
  --surface-card-surface: #ffffff;
  --surface-recessed-panel: #edf4ed;
  --surface-sage-tint: #e5f0e5;
  --surface-dark-shell: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sage-canvas: #f4f8f4;
  --color-sage-surface: #e5f0e5;
  --color-sage-panel: #edf4ed;
  --color-timber: #162016;
  --color-forest-primary: #1a8030;
  --color-deep-forest: #0d5020;
  --color-amber: #c87a08;
  --color-amber-text: #986008;
  --color-amber-wash: #fdf3e0;
  --color-timber-muted: #4e6456;
  --color-ash: #6a7a6a;
  --color-fog: #a8bca8;
  --color-smoke: #8ca08c;
  --color-pepper: #2a3828;
  --color-midnight: #0d1610;
  --color-obsidian: #000000;
  --color-lime: #8cd422;
  --color-lime-wash: #d4f0cc;
  --color-coral-red: #c02818;
  --color-valid-green: #1a8030;
  --graphic-green: #1a9030;
  --graphic-amber: #c87a08;
  --graphic-lime: #8cd422;

  /* Typography */
  --font-sans: 'Plus Jakarta Sans', system-ui, sans-serif;
  --font-mono: 'Geist Mono';

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.58;
  --tracking-caption: -0.14px;
  --text-body: 15px;
  --leading-body: 1.47;
  --tracking-body: -0.2px;
  --text-heading-sm: 19px;
  --leading-heading-sm: 1.38;
  --tracking-heading-sm: -0.25px;
  --text-heading: 23px;
  --leading-heading: 1.2;
  --tracking-heading: -0.44px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.09;
  --tracking-heading-lg: -1.14px;
  --text-display: 68px;
  --leading-display: 1.09;
  --tracking-display: -2.11px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-92: 92px;
  --spacing-96: 96px;
  --spacing-104: 104px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 17px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 72px;

  /* Shadows */
  --shadow-subtle: color(display-p3 0.784 0.863 0.784) 0px 0px 0px 1px inset;
  --shadow-subtle-2: color(display-p3 0.784 0.863 0.784) 0px 0px 0px 0px inset;
  --shadow-subtle-3: rgba(0, 0, 0, 0.04) 0px 0px 0px 1px;
  --shadow-lg: rgba(0, 0, 0, 0.15) 0px 0px 24px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 1px 6px 0px, rgba(0, 0, 0, 0.05) 0px 0px 24px 0px;
}
```
