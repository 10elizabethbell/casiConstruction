---
name: Casi Construction LLC
description: A one-man carpenter's site in Forked River, NJ, set in calm full-bleed bands of paper and navy with one fresh-cut pine accent.
colors:
  paper: "#f4f6fb"
  card-white: "#ffffff"
  field-tint: "#e6ecf5"
  ink: "#14263f"
  body-slate: "#2b3a4d"
  soft-slate: "#4b5869"
  hammer-navy: "#1f3b5e"
  deep-navy: "#14263f"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c8d4e4"
  pine: "#f0b552"
  pine-light: "#f6c876"
  pine-ink: "#8a5200"
  hairline: "rgba(20,38,63,.12)"
  tint-on-light: "rgba(20,38,63,.07)"
  tint-on-dark: "rgba(255,255,255,.07)"
  tint-on-dark-strong: "rgba(255,255,255,.12)"
  ghost-edge: "rgba(244,247,251,.7)"
  focus-blue: "#1f5fa8"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(44px, 12.5vw, 88px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-.005em"
  headline:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-.005em"
  title:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(26px, 7vw, 34px)"
    fontWeight: 400
    lineHeight: 1.08
  row-title:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  button:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  field-label:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  note:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  field: "10px"
  row: "20px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter: "20px"
  gutter-desktop: "40px"
  band: "64px"
  band-desktop: "96px"
  tight: "12px"
  base: "16px"
  loose: "20px"
  block: "28px"
  column-gap: "64px"
  card-padding: "clamp(20px, 5vw, 32px)"
components:
  button-primary:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.pine-light}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  input-field:
    backgroundColor: "{colors.field-tint}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field-tint}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card-white}"
  form-card:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.body-slate}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-padding}"
  service-row:
    backgroundColor: "{colors.tint-on-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.row-title}"
    rounded: "{rounded.row}"
    padding: "12px 14px 12px 22px"
    height: "72px"
  link-row:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.ink}"
    typography: "{typography.row-title}"
    rounded: "{rounded.row}"
    padding: "14px 16px 14px 22px"
    height: "72px"
  arrow-circle:
    backgroundColor: "{colors.tint-on-light}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  arrow-circle-hover:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
  step-number:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
---

# Design System: Casi Construction LLC

## Overview

**Creative North Star: "The Business Card, Banded"**

Casimiro's black-on-white business card, opened out into full-bleed bands: off-white paper, a hammer-head navy, a deeper navy laid with faint diagonal lines, and one warm accent the colour of fresh-cut pine. This is Ellie's house "calm band style" (after lpmr.co.uk) applied without photos. The page earns trust through order, not decoration: each band is one idea, bands alternate light and dark so a new section is obvious at a glance, and the only warmth on screen is the pine accent marking what to press.

Density is low and phone-first. One column on a phone, splitting into two or three columns only on wide screens; generous band padding; large tap targets (44px minimum, 56px for buttons). Shapes are soft and borderless: pill buttons, 20px rows, a 24px form card, circles for anything that is a single mark (arrows, step numbers, the floating text button, the hammer logo). Motion is two moments and no more: the hero H1 bounces in letter by letter, and content below the first screen rises 12px into place once.

The world's own materials come from the card: the hammer-in-a-circle mark and the "CASI CONSTRUCTION" name set on an arch. Those are the only illustrations. No photos ship because none were supplied that show his own work.

**Key Characteristics:**
- Full-bleed bands alternating paper and navy; the deep band carries a faint 135deg line texture.
- One warm accent (pine), used as a fill; dark navy text sits on it.
- Cal Sans for every heading and every interactive label; the system stack for running text at 16/1.7.
- Soft, borderless shapes: pills, 20px rows, a 24px card, circles.
- Flat surfaces. The only shadow belongs to the floating text circle.
- Two motions: the hero H1 bounce-in and one 12px fade-up.

## Colors

Cool paper and two navies carry the page; a single warm pine is the only colour that asks to be pressed.

### Primary
- **Fresh-cut Pine** (pine): the one accent. A fill colour: primary buttons, step numbers, the floating text circle, the arrow circle on hover, selection highlight, the eyebrow dot. As text it appears only on navy bands (the accent phrase of a heading, the phone icon, link hover in the footer and close band), where it holds 6.2:1 on hammer navy.
- **Pine, lifted** (pine-light): primary button hover only.
- **Pine Ink** (pine-ink): pine when it has to be text or an icon on a light ground (header phone icon and hover, the claim icons, the accent phrase on paper). 5.9:1 on paper.

### Neutral
- **Cool Paper** (paper): the page ground, the header, the light bands, the theme colour. Never black.
- **Card White** (card-white): the form card and the Facebook link row on paper; also the hero H1 and selected-chip text.
- **Field Tint** (field-tint): inputs and chips on the white card. A tint (about 1.2:1 against white), not a contrast boundary; the Cal Sans label above each field identifies it.
- **Ink** (ink): headings on light, text on pine, the selected chip fill, the outlined button edge.
- **Body Slate** (body-slate): running text on light grounds.
- **Soft Slate** (soft-slate): ledes, step descriptions, helper and after-form notes, placeholders.
- **Hammer Navy** (hammer-navy): the hero band and the closing band.
- **Deep Navy** (deep-navy): the services band and the footer, always with the line texture. Same value as ink by design: the darkest navy is both a ground and the heading colour.
- **On Dark** (on-dark) and **On Dark Soft** (on-dark-soft): headings and running text on the navy bands (soft text holds 7.6:1 on hammer navy).
- **Hairline** (hairline): the 1px divider between claim rows. The only line on a light band.
- **Tints** (tint-on-light, tint-on-dark, tint-on-dark-strong): translucent navy or white washes for rows and resting arrow circles; they let a shape exist without a border.
- **Ghost Edge** (ghost-edge): the outline of the secondary button on navy.

### Functional
- **Focus Blue** (focus-blue): hover and focus outline on form controls and the 3px focus ring on light bands; deliberately not pine, so focus never reads as "selected".
- **Error Red** (error-red): field error border and plain-sentence error text.

### Named Rules
**The Pine Is a Fill Rule.** Pine is a surface, not a text colour, on light grounds. Text on pine is ink; pine as text on paper or white is always pine-ink. On navy bands pine may be text.

**The One Warm Colour Rule.** Pine is the only warm hue on the page. Everything else is paper, white, slate or navy.

**The Separate Focus Rule.** Focus and form hover use focus-blue on light grounds and pine on navy bands; never the same colour as the thing being focused.

## Typography

**Display Font:** Cal Sans (with "Avenir Next", "Segoe UI", system-ui, sans-serif)
**Body Font:** the system stack (-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif)

**Character:** Cal Sans is rounded, sturdy and friendly at size, a geometric voice for a tradesman who talks plainly; the system body keeps running text native, fast and familiar on a phone in Facebook's in-app browser.

### Hierarchy
- **Display** (400, clamp(44px, 12.5vw, 88px), 1.02): the hero H1 only, max 11ch, white on hammer navy, last phrase in pine.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): one section heading per band.
- **Title** (400, clamp(26px, 7vw, 34px)): the form card heading.
- **Row title** (400, clamp(20px, 5.4vw, 24px), 1.15): claim rows, service rows, the link row, step titles (21px).
- **Button** (400, 18px, 1): every button label, in Cal Sans.
- **Field label** (400, 17px, 1.2): form labels and legends, in Cal Sans.
- **Lede** (400, clamp(17px, 4.6vw, 19px), 1.7, max 38ch): the sentence under a headline; the hero promise is the same voice at up to 20px, line-height 1.5, max 32ch (40ch on desktop).
- **Body** (400, 16px, 1.7): running text, inputs and chips. Never below 16px on an input.
- **Note** (400, 15px): error sentences and the line under the submit button. Helper hints are 14px.

### Named Rules
**The Cal Sans Speaks Rule.** Anything you read as a heading or press as a control (headings, row titles, buttons, field labels, phone numbers) is Cal Sans at weight 400. Explanatory text is the system stack. No third face.

**The Balanced Heading Rule.** Headings use `text-wrap: balance`; ledes, the promise and step descriptions use `text-wrap: pretty`.

## Layout

A single 1160px max-width container with a 20px gutter on phones and 40px from 760px. Each section is a full-bleed band with 64px vertical padding on phones and 96px from 760px; the hero runs 56/64px and 96/112px. Content blocks inside a band stack on a small rhythm of 12, 16, 20 and 28px; 64px is the column gap on wide screens.

Breakpoints are 760px (two-column service grid, side-by-side hero buttons at least 240px wide, desktop gutter and band padding) and 1024px (the "You deal with me" band, the estimate band and the closing band split into two columns; services go to three; the estimate band's heading and steps stick at 40px from the top beside the form). Below 380px and 340px a few labels tighten so the header phone number and chips never wrap.

Text blocks are measured: headline blocks max 640px, ledes 38ch, the form card max 600px, the link row max 440px. The header is slim (64px, 76px on desktop) and respects the safe-area insets, as do the footer and the floating circle.

**The Band Per Idea Rule.** Every section is one full-bleed band, and adjacent bands differ in ground (paper, navy, paper, navy...). Never stack two same-ground bands.

## Elevation & Depth

Flat. Depth comes from the ground changing between bands and from translucent tints on rows and arrow circles, never from shadows. The deep band and the footer (and the hero) carry the line texture, a repeating 135deg gradient of transparent 22px and 1px white at 3.5% opacity, faint enough that it never reads as lines through text.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,20,38,.3)`): the floating text circle only, because it sits over every band.

### Named Rules
**The Flat Band Rule.** Cards, rows and buttons have no shadow at rest or on hover. Only an element fixed above the page may lift.

**The Faint Texture Rule.** The line texture stays at about 4% white or fainter, on navy grounds only.

## Shapes

Soft and borderless. Containers are rounded tints rather than outlined boxes: inputs at 10px, rows at 20px, the form card at 24px, buttons and chips as full pills, and anything that is one mark (arrows, step numbers, the floating text button, the logo) as a circle. Borders appear only where a control needs an edge to be read: the outlined buttons (2px), the input hover/focus/error edge (2px, transparent at rest), and the single hairline between claim rows. Icons are inline line drawings with round caps and joins (stroke 2.2 to 2.6).

## Components

### Buttons
Big, round and plain; the label does the work.
- **Shape:** full pill (999px), 56px tall, 26px side padding, 2px border, Cal Sans 18px. Icons inside are 20px with a 10px gap.
- **Primary:** pine fill, ink text. One per view: the hero estimate action and the form submit.
- **Hover / Focus:** primary lifts to pine-light (pointer devices only). Press scales to 0.98. Focus is a 3px outline offset 3px (focus-blue on light, pine on navy); in the form the submit gets a 2px focus-blue outline on hover and focus.
- **Ghost:** transparent on navy with the ghost-edge outline and on-dark text; hover turns the edge white over a 10% white wash. The hero's secondary action.
- **Line:** transparent with an ink outline and ink text, for fallback actions on light grounds (Open in Messages, Copy message).

### Chips
- **Style:** field-tint pill, 48px tall, 18px side padding, body 16px in ink, transparent 2px border. The checkbox is visually hidden behind its label.
- **State:** hover draws a focus-blue border; keyboard focus a 3px focus-blue outline offset 3px; selected fills ink with white text. Tapping a service row pre-selects its chip.

### Cards / Containers
- **Corner Style:** 24px (the form card); 20px for rows.
- **Background:** card-white on paper.
- **Shadow Strategy:** none (see Elevation & Depth).
- **Border:** none.
- **Internal Padding:** clamp(20px, 5vw, 32px), 20px between fields.

### Inputs / Fields
- **Style:** field-tint fill, 10px radius, 2px transparent border, 52px min height, 13px 14px padding, body 16px in ink, soft-slate placeholder, hammer-navy caret. Textareas start at 110px. Each field has a Cal Sans label above it and an optional 14px "(optional)" hint.
- **Focus:** the border turns focus-blue; no glow. Hover does the same on pointer devices.
- **Error:** the border turns error-red and stays red while focused; a plain sentence in error-red appears under the field.

### Navigation
A slim paper header: the hammer mark (38px, 44px on desktop) with the CASI / CONSTRUCTION lockup on the left, the tap-to-call number in Cal Sans with a pine-ink phone icon on the right. No menu. The footer's contact links are plain on-dark text at 44px tap height, turning pine on hover.

### Link Rows
The page's list-of-links pattern. A whole row is the link: Cal Sans row title on the left, a 44px arrow circle on the right.
- **Service row:** on deep navy, a tint-on-dark row (20px radius, 72px tall); the arrow circle rests on tint-on-dark-strong.
- **Link row:** on paper, a card-white row (the Facebook link).
- **Hover / Focus:** only the arrow circle changes, filling pine with ink arrow. The row itself never changes colour or lifts. Keyboard focus outlines the arrow circle.

### Claim List
Short Cal Sans statements (licensed and insured, free estimates, the town), each led by a 40px pine-ink line icon, separated by a single hairline.

### Numbered Steps
An ordered list whose numbers are 48px pine circles with ink Cal Sans numerals; a 21px Cal Sans step title over a soft-slate sentence.

### Floating Text Circle (signature)
A 60px pine circle, ink chat icon, fixed bottom-right inside the safe area with the float lift shadow. It opens a pre-written text. It slides in (0.35s, cubic-bezier(.2,.8,.2,1)) once the hero has scrolled away and hides while the estimate form is on screen, taking itself out of the tab order and the accessibility tree when hidden. One circle, never a bottom bar.

### Hero H1 Bounce-in (signature motion)
The hero H1 only. JS splits it into letters inside no-wrap word spans; each letter slides in from 50px right and fades up over 1s on cubic-bezier(.34,1.56,.64,1), 20ms apart. The H1 keeps an aria-label while split and the plain heading is restored when the last letter lands. Skipped without JS, under reduced motion, or with the motion switch off.

### Fade-up
Blocks marked to rise that start below the first screen move up 12px and fade in over 0.4s ease-out as they enter, once. Everything is visible at rest, without JS and under reduced motion.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed paper and navy bands, one idea per band, with 64px (96px desktop) band padding.
- **Do** use pine as a fill with ink text on it; switch to pine-ink whenever pine must be text or an icon on paper or white.
- **Do** set every heading, row title, button label, field label and phone number in Cal Sans 400, and running text in the system stack at 16/1.7.
- **Do** keep shapes borderless and soft: 999px pills, 20px rows, a 24px card, 10px inputs, circles for single marks.
- **Do** make a whole row the link and let only its 44px arrow circle change on hover, filling pine.
- **Do** keep tap targets at 44px or larger and inputs at 16px or larger.
- **Do** outline form controls in focus-blue on hover and focus, and keep the error-red edge when an invalid field is focused.
- **Do** keep the line texture on navy grounds at about 4% white or fainter.

### Don't:
- **Don't** use pine (#f0b552) as text on paper or white; it fails contrast. Use pine-ink.
- **Don't** add a second warm colour, a black ground, or a third typeface.
- **Don't** put shadows on cards, rows or buttons; the float lift belongs to the floating text circle alone.
- **Don't** animate any heading but the hero H1, and never leave content waiting at opacity 0 at rest.
- **Don't** replace the floating text circle with a bottom bar, or show it while the estimate form is on screen.
- **Don't** change a row's background or lift it on hover; only the arrow circle responds.
- **Don't** add eyebrow pills to new surfaces from this file. The three shipped ones are a house-style exception Ellie chose (calm-photo-style.md item 5) that Impeccable flags; they are not part of this system.
