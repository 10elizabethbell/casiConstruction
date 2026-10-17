---
name: Casi Construction LLC
description: A carpenter's business card laid over a deck being sanded back to fresh wood.
colors:
  card-paper: "#f4f0e8"
  card-paper-band: "#ebe4d6"
  card-ink: "#1f2a31"
  card-ink-soft: "#47535c"
  pencil-rule: "#d6ccba"
  field-white: "#fffdf8"
  control-edge: "#8a806e"
  carpenters-pencil-red: "#b23a22"
  fresh-wood: "#9a5a22"
  weathered-board: "#8c867c"
  board-gap: "#221d19"
typography:
  display:
    fontFamily: "\"Avenir Next Condensed\", \"Helvetica Neue Condensed\", \"Roboto Condensed\", \"Arial Narrow\", sans-serif-condensed, system-ui, sans-serif"
    fontSize: "clamp(2.75rem, min(13.2vw, 15svh), 5.6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "\"Avenir Next Condensed\", \"Helvetica Neue Condensed\", \"Roboto Condensed\", \"Arial Narrow\", sans-serif-condensed, system-ui, sans-serif"
    fontSize: "clamp(2.3rem, 9vw, 3.6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
  title:
    fontFamily: "\"Avenir Next Condensed\", \"Helvetica Neue Condensed\", \"Roboto Condensed\", \"Arial Narrow\", sans-serif-condensed, system-ui, sans-serif"
    fontSize: "26px"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  numeral:
    fontFamily: "\"Avenir Next Condensed\", \"Helvetica Neue Condensed\", \"Roboto Condensed\", \"Arial Narrow\", sans-serif-condensed, system-ui, sans-serif"
    fontSize: "46px"
    fontWeight: 800
    lineHeight: 1
  body:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  body-lead:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.55
  list-item:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 650
    lineHeight: 1.55
  label:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: 1.55
  button:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1
  note:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  check: "4px"
  control: "10px"
  panel: "12px"
  deck: "18px"
  circle: "50%"
spacing:
  gutter: "16px"
  gutter-wide: "32px"
  control-gap: "10px"
  stack: "22px"
  grid-gap: "40px"
  section: "64px"
components:
  button-primary:
    backgroundColor: "{colors.card-ink}"
    textColor: "{colors.card-paper}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.carpenters-pencil-red}"
    textColor: "{colors.card-paper}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.card-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  button-line-hover:
    textColor: "{colors.carpenters-pencil-red}"
  chip:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.card-ink}"
    rounded: "{rounded.control}"
    padding: "0 16px"
    height: "46px"
  chip-checked:
    backgroundColor: "{colors.card-ink}"
    textColor: "{colors.card-paper}"
  text-field:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.card-ink}"
    rounded: "{rounded.control}"
    padding: "13px 14px"
    height: "52px"
  service-row:
    textColor: "{colors.card-ink}"
    typography: "{typography.list-item}"
    padding: "10px 0"
    height: "64px"
  row-arrow:
    textColor: "{colors.card-ink}"
    rounded: "{rounded.circle}"
    size: "40px"
  row-arrow-active:
    backgroundColor: "{colors.carpenters-pencil-red}"
    textColor: "{colors.card-paper}"
  link-card:
    backgroundColor: "{colors.card-paper}"
    textColor: "{colors.card-ink}"
    rounded: "{rounded.panel}"
    padding: "12px 18px"
    height: "64px"
  status-panel:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.card-ink}"
    rounded: "{rounded.panel}"
    padding: "20px"
  footer:
    backgroundColor: "{colors.card-ink}"
    textColor: "{colors.card-paper}"
---

# Design System: Casi Construction LLC

## Overview

**Creative North Star: "The Business Card on the Deck"**

Everything printed is the owner's business card: warm white card stock, charcoal-blue ink, the hammer-in-a-circle mark, condensed uppercase lettering. Everything alive is a deck: real top-down boards drawn on canvas (butt joints, screw pairs over 16-inch joists, knots that bend the grain), a silver weathered layer masked over fresh honey wood, and a palm sander that sands that weathering away along the grain and throws sawdust. The two never blend. The card is flat, quiet, and legible; the deck is the one place with texture, colour, and motion.

The page is phone-first and plain-spoken. Density is low: one column on a phone, wide gutters, 64px between sections, every tap target at least 44px tall. Hierarchy comes from heavy condensed uppercase headings against plain sentence-case body, not from colour. Colour is almost entirely ink on paper; the single accent, carpenter's-pencil red, is reserved for the moment a visitor touches something.

The deck recurs at three scales: the hero (a full run of boards, sanded by an autonomous "ghost" pass until a finger or mouse takes the sander over), single-plank dividers between sections (one board, sanded left to right as the page scrolls), and a short run of boards above the footer.

**Key Characteristics:**
- Two-material world: flat ink-on-card for type and controls, painted wood for the living element.
- Restrained palette: ink, paper, a darker paper band, pencil-rule lines; red only on hover and focus.
- Heavy condensed uppercase display over a plain system body stack.
- Rules, not boxes: lists and steps separate with 1px pencil rules rather than cards.
- One interactive signature (the sanding deck), repeated at hero, divider, and footer scale.

## Colors

Black-on-white business card, warmed: one ink, one paper, one pencil red that only answers the visitor.

### Primary
- **Card Ink** (card-ink): all text, primary button fill, checked chip fill, footer ground, the logo mark. The brand has no colour beyond its ink; this is it.

### Secondary
- **Carpenter's Pencil Red** (carpenters-pencil-red): hover and focus only. Primary button hover fill, line-button and link hover text, the filled service-row arrow, every focus outline (3px global, 2px on form controls), input caret, and form error text and borders.

### Tertiary
- **Fresh Wood** (fresh-wood): the large step numerals in "How a job goes". It echoes the sanded wood in the deck; it is the only place outside the canvas where wood colour appears.

### Neutral
- **Card Paper** (card-paper): page ground, button text on ink, the `theme-color`, and the cut-out fill inside the hammer mark.
- **Card Paper Band** (card-paper-band): alternating section bands ("How a job goes", the estimate form) so sections read as separate without borders.
- **Soft Ink** (card-ink-soft): secondary text: notes, step descriptions, "(optional)", the arrow-circle stroke, the checkbox outline.
- **Pencil Rule** (pencil-rule): 1px rules above and below service rows and above each step.
- **Field White** (field-white): input, chip, and status-panel fill, a touch lighter than the paper so fields read as writable.
- **Control Edge** (control-edge): 2px borders on inputs and unchecked chips, chosen to hold 3:1 against paper.
- **Weathered Board** and **Board Gap** (weathered-board, board-gap): the static striped fallback painted behind every deck canvas before it draws (44px board, 4px gap in the hero; 40px and 4px at the footer). The canvas itself paints procedural HSL wood; these two values are the deck's resting state, not UI colours.

On the ink footer the red would fail contrast, so link hover there lifts to a pale pencil red (#ffb39f) and the fine print uses a cool grey (#bcc5cb). Both are footer-only and stay out of the token set.

### Named Rules
**The Pencil Only Answers Rule.** Carpenter's-pencil red never appears at rest. It shows up only on hover, focus, the caret, or an error. If a screen shows red with nobody touching it, something is wrong (error state excepted).

**The No Brand Colour Rule.** The business has no colours beyond black on white. Don't add a brand blue, a safety orange, or a wood-tone UI accent; wood colour lives in the deck and the step numerals.

## Typography

**Display Font:** system condensed sans ("Avenir Next Condensed", then "Helvetica Neue Condensed", "Roboto Condensed", "Arial Narrow", sans-serif-condensed, falling back to system-ui)
**Body Font:** system-ui stack (-apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial)

**Character:** The display face is the lettering on the business card: heavy (800), condensed, uppercase, set tight (-0.01em, line-height 0.95) and balanced. The body is the phone's own UI font in plain sentence case, so it reads like the owner talking. No web fonts are loaded; this is a house rule (fast on cellular, inside Facebook's in-app browser).

### Hierarchy
- **Display** (800, clamp 2.75rem to 5.6rem on phones, sized against both width and viewport height so the hero fits the first screen; clamp 3.6rem to 6rem from 900px; 0.95): the hero headline only.
- **Headline** (800, clamp 2.3rem to 3.6rem, 0.95): section headings ("What I do", "How a job goes", "No job is to small.").
- **Title** (800, 26px, 1.05): step titles; the status panel heading runs at 28px.
- **Numeral** (800, 46px, 1, fresh wood): step numbers.
- **Body** (400, 17px, 1.55): running text; owner paragraph steps up to clamp 18px to 22px. Measure capped at 32 to 38ch.
- **Body Lead** (400, clamp 17px to 20px): the hero promise, max 32ch.
- **List Item** (650, 20px): service rows.
- **Label** (700, 17px): form legends and labels; optional markers drop to 500 in soft ink.
- **Button** (700, 18px, 1): every button.
- **Note** (400, 16px, soft ink): helper lines, error messages (650, red), footer fine print.

### Named Rules
**The Card Lettering Rule.** Every h1, h2, and h3 uses the condensed display stack at 800, uppercase, tight. Body, labels, and buttons never go uppercase.

**The Lockup Exception Rule.** Wide letterspacing (0.16em) exists only in the "CONSTRUCTION" line of the header lockup and the arched footer logo. It is part of the mark, not a style for headings or labels.

## Layout

Single column on phones with a 16px gutter, widening to 32px from 700px; content is capped at 1240px and centred. Sections sit 64px apart vertically; inside forms and stacks the rhythm is 22px, with 10 to 12px between sibling controls and 40px column gaps on desktop grids.

- **Hero:** text then deck on phones (deck 220 to 330px tall, at most about a third of the viewport). From 900px the hero becomes two columns (text 1fr, deck 1.1fr), up to 820px tall, and the deck bleeds to the right edge of the window with its left corners rounded; the text column aligns to the 1240px content edge.
- **Services:** one stacked list on phones, three columns from 900px.
- **Steps:** stacked, each a 52px numeral column beside title and text; three columns from 900px.
- **Estimate:** heading over form on phones; from 900px a 0.8fr / 1.6fr split with the heading left and the form right (max 640px). Town and name fields pair up from 700px.
- **Breakpoints:** 700px (gutter, paired fields, inline buttons), 760px (plank divider height and the script's phone/desktop switch at 759px), 900px (multi-column layouts).
- Section bands alternate paper and paper band; a single-plank deck divider sits directly above each band.

## Elevation & Depth

The interface is flat. No surface casts a CSS shadow; separation comes from tonal bands (paper vs. paper band), 1px pencil rules, and 2px ink outlines on cards and controls. All depth lives inside the deck canvas: each board has a light top edge and a darker bottom edge, butt joints and board gaps are near-black, and the palm sander casts a soft, offset drop shadow onto the wood (blur 12px, offset 4px by 7px, warm brown at 38%). That shadow belongs to the tool on the boards, not to UI.

### Named Rules
**The Flat Card Rule.** UI elements (buttons, chips, inputs, panels) never take a box-shadow. If something needs to stand out, give it an ink outline or the ink fill.

## Shapes

Gently rounded, hand-tool friendly corners: 10px on buttons, chips, and inputs; 12px on the larger link card and status panel; 8px on the message preview inside it; 4px on the custom checkbox square; full circles for the service-row arrow and the hammer mark. Borders are 2px on interactive controls and cards (ink or control edge), 1.5px on the arrow circle, 1px for pencil rules. The desktop hero deck rounds only its left corners (18px) where it meets the page. The recurring silhouette is the circle: the hammer mark, the arrow cue, the sander's motor dome.

## Components

### Buttons
Heavy, full-width on phones, honest.
- **Shape:** gently rounded (10px), 2px ink border, 56px tall, 0 22px padding; an optional 20px inline SVG icon leads the label.
- **Primary:** ink fill, paper text.
- **Line (secondary):** transparent with ink border and ink text, same size and border as primary, so a pair always matches.
- **Hover / Focus:** primary fills pencil red; line turns border and text pencil red (0.2s colour transitions). Focus is a 3px red outline at 3px offset; inside the form the submit button uses a 2px red outline on hover and focus.
- **Layout:** stacked full width on phones; side by side, auto width, from 900px in the hero and 700px in the form and status panel.

### Chips
- **Style:** checkbox chips: field-white fill, 2px control-edge border, 10px radius, 46px tall, 600 weight 16px, with a 16px square check box (4px radius, soft-ink border) leading the label.
- **State:** checked inverts to ink fill and paper text with a paper-filled box and an ink tick. Hover and keyboard focus draw a 2px red outline at 2px offset.

### Cards / Containers
- **Link card (Facebook):** paper fill, 2px ink border, 12px radius, 12px 18px padding, 64px tall, max 440px; text and trailing arrow turn red on hover.
- **Status panel ("Almost done"):** field-white fill, 2px ink border, 12px radius, 20px padding; holds the composed message in an 8px-radius paper block and two line buttons.
- **Shadow Strategy:** none (see Elevation & Depth).

### Inputs / Fields
- **Style:** field-white fill, 2px control-edge border, 10px radius, 13px 14px padding, 52px minimum height (textarea 110px, vertical resize), 500 weight 17px, placeholder in a warm grey (#6d6658).
- **Focus:** 2px red outline at 1px offset and a red caret; hover shows the same outline on pointer devices.
- **Error:** border turns red and a 16px red message appears beneath; the first bad field scrolls into view and takes focus.

### Navigation
- **Header bar:** the hammer mark (40px) with a stacked "CASI / CONSTRUCTION" condensed lockup on the left, the phone number as a tap-to-call link (700, 17px, tabular numerals, phone icon) on the right. It is not sticky. The number turns red on hover.
- **Service rows as navigation:** each service is a whole-row link (64px, 1px pencil rules) with a 40px circular arrow at the end. Only the arrow lights up (red fill, paper arrow) on hover or focus; the row itself never highlights. On phones a row opens a pre-filled text; on pointer devices it jumps to the form and ticks the matching chip.

### Footer
Ink ground, paper text. Holds the arched "CASI CONSTRUCTION" logo (the business card mark, nails either side), a contact list of 44px icon links (phone, email, Facebook; icons at 80% opacity), and fine print. Three columns from 900px.

### The Sanding Deck (signature)
A canvas that paints the same procedural boards twice from one seed, fresh honey wood beneath and silver weathered wood above, and reveals the fresh layer through a mask the sander erases. Board width is PLANK (40px phone, 50px desktop) with a 4px gap.
- **Sander:** a top-down palm sander (square pad with paper edges, yellow motor dome, rubber palm cap, dust bag, cord) that leaves square, slightly feathered strips. Each frame removes SAND (0.2) of weathering; weathering creeps back at REGROW (0.0035) per frame, so the deck never stays finished.
- **Hero and footer decks:** a ghost pass sands full lengths along the grain, one board at a time, stepping down and back up. A finger or mouse takes over the sander; GHOST_DELAY (2600ms) after release the ghost resumes. The hero starts already partly sanded so the first frame shows both woods. The hero deck captures touch; the footer deck lets the page scroll.
- **Plank dividers:** a single board at 0.7 tool scale; scroll position drives the sander from left to right, and it only sands while the page is moving.
- **Sawdust:** up to DUST_MAX particles (200 phone, 480 desktop; 60 per plank) in three pale wood tones; they skid, slow, get shoved by the sander, and fade.
- **Behaviour:** one shared animation loop runs only for decks in view; reduced motion stops the loop and leaves a still, partly sanded deck. Decks are decorative (aria-hidden).
- **Tunables:** SAND, REGROW, GHOST_DELAY, DUST_MAX, and PLANK live at the top of the script. Change the feel there, not inside the drawing code.

## Do's and Don'ts

### Do:
- **Do** keep the page ink on card paper and save carpenter's-pencil red (#b23a22) for hover, focus, caret, and errors.
- **Do** set every heading in the condensed display stack at 800, uppercase, line-height 0.95, and keep body and controls in sentence case on the system stack.
- **Do** separate list items and steps with 1px pencil rules (#d6ccba) and separate sections with the paper band, not with boxes or shadows.
- **Do** build primary and secondary buttons as a matched pair: same 56px height, 10px radius, and 2px border; only the fill differs.
- **Do** keep every tap target at least 44px tall (buttons 56px, rows 64px, chips 46px).
- **Do** reuse the sanding deck for new texture or dividers, tuned through SAND, REGROW, GHOST_DELAY, DUST_MAX, and PLANK, and paint the striped weathered-board fallback behind its canvas.
- **Do** inline icons as SVG symbols drawn in currentColor.

### Don't:
- **Don't** load web fonts; the system stack is the house rule.
- **Don't** show red at rest, and don't add brand colours the business card doesn't have.
- **Don't** put box-shadows on UI elements; the only shadow in the system is the sander's on the wood.
- **Don't** use wide letterspacing outside the logo lockup.
- **Don't** wrap services or steps in icon cards; a service is a ruled row with an arrow cue.
- **Don't** highlight a whole service row on hover; only its arrow fills.
