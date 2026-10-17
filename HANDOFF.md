# Casi Construction LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/casiConstruction/ · **Repo:** https://github.com/10elizabethbell/casiConstruction · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Facebook group ad)

## What's built
- One page, `index.html` (single file, ~45 KB, no images except the icon and the Facebook preview `og.jpg`). Phone first.
- **World:** his business card (warm white paper, charcoal-blue ink, condensed caps, hammer-in-a-circle mark) plus a deck being sanded. Carpenter's-pencil red shows only on hover and focus.
- **Signature element:** the hero is weathered silver deck boards (butt joints, screw pairs over the joists, knots that bend the grain). A palm sander works across them on its own, in full passes along the grain, one board at a time, leaving fresh pine and sawdust. A finger or mouse takes it over in any direction; the hero deck uses `touch-action:none`, so a drag sands instead of scrolling. The gray creeps back after a few seconds (`REGROW`).
- **Carried through the page:** a single board between sections, whose sander is driven by scrolling (sands as you scroll past), and a deck strip above the footer. The hero, planks and footer share one animation loop, and each pauses when it's off screen.
- **Sections:** header (mark, CASI/CONSTRUCTION, tap-to-call number top-right) → hero (headline "I build it like it's mine.", promise, Get a free estimate / What I do) → What I do (9 short rows) → How a job goes (3 steps) → You deal with me (Casimiro, Forked River, licensed and insured, Facebook link) → "No job is to small." estimate form → footer (arched logo, phone, email, Facebook).
- **Contact wiring:** on phones each service row opens a pre-written text to 848-525-7973. On computers, which can't send texts, the rows jump to the form with that service ticked. The form checks for missing fields and shows errors, then opens a text with everything filled in, with copy and call fallbacks. Email appears only in the footer.
- **Checks run:** headless Chrome at 360, 390, 414, 430 and 1440 wide. No sideways scroll, no text under 16px, tap targets 44px+, the buttons sit in the first screen, and the motion frames differ. Touch and mouse sweeps both move the sander and sand the wood. The text bodies decode correctly. An Impeccable sub-agent also ran WebKit/Playwright at 360–1440 and landscape.
- **Impeccable:** every mode except `live` and `onboard` (no first-run flow) ran: critique, audit, harden, clarify, adapt, optimize, polish, bolder, quieter, distill, animate, colorize, typeset, layout, delight, overdrive, extract. The finish reviewer and the detector ran too; the detector was not in degraded mode. Fixes are applied. The detector ignores I recorded are in `.impeccable/config.json`, each with its reason: Roboto (system-stack fallback), cream ground (from his card), the list rule line, the deck fallback stripes, and the body-size steps.

## Assumptions I made
- **Logo:** Muse found none, but his Facebook profile picture is his **business card**: "CASI CONSTRUCTION" arched over a black circle with a claw hammer and a nail each side, with (848)525-7973. The mark on the site, the favicon and the iPhone icon are my vector **redraw** of that card. The card photo stays in `src-assets/` and isn't committed. At 40px the hammer still leans toward a "T"; worth one more pass.
- **Colors:** black on white is all the brand has. I warmed the white to card stock and softened the black to charcoal-blue (no black grounds). The red accent and the pine/silver wood are mine.
- **Voice:** first person "I", because Casimiro posts the ads from his personal profile and it reads like a one-man business. The brief marks the name-to-business link as unverified but consistent.
- **Copy I wrote that he should approve:** "I build it like it's mine.", the promise line, "You deal with me … from the estimate to the last screw", and the three steps ("I look at the job and give you a straight price before anything starts"). None of them claims a fact beyond the brief, but they are promises in his name.
- **"No job is to small."** is kept verbatim, with his spelling, as the brief asks. Easy to fix to "too" if he wants.
- **Area:** only "Forked River, NJ" is stated. I removed "Ocean County" because it was inferred from the groups he posts in, so the page has no service-area section.
- **Audience:** I treated it as the general homeowner audience with motion on. Lacey Township skews older, though; if Ellie sees this as a 40+ audience, `older-audience.md` says go still (draw the deck once, no sander).

## Placeholders and gaps
- **No work photos at all,** and no before/after pairs or reviews, so there is no proof section. The Facebook link reads "Find me on Facebook." rather than "Click to see more of my work.", because his profile only shows the same ad. Switch the wording back once he posts jobs.
- **Email** `casiconstructionllc@gmail.com` comes from Muse's OCR of the flyer, and I could not fetch the flyer to verify it. It's footer-only. Confirm it before handover.
- **Texting:** the brief says "Accepts texts: unknown", yet the service rows, step 1 and the form all hand off by text. The top-right number and the call fallback after sending cover calls. Confirm he takes texts.
- No hours, prices, years in business or insurance details on the page (none known).
- The flyer image (`photo.php?fbid=1073262155769320`) wasn't fetchable without a login.

## Questions for the owner
1. Do you take texts at 848-525-7973?
2. Is casiconstructionllc@gmail.com right?
3. Which towns do you cover? (We'd add a short plain-text list.)
4. Can you send 6–10 photos of finished jobs, and any before/afters? Bathrooms, decks and stucco would carry the page.
5. Is it just you, or a crew? (This sets "I" vs "we".)
6. Hours? NJ HIC registration number to show? (NJ contractors usually display it.)
7. Any customer you'd ask for a short review?

## Ideas not built (yours to pick)
- **Runner-up world:** a blueprint whose pencil lines draw the house as you scroll (graph-paper ground, carpenter's-pencil red marks).
- **Photos:** once he sends them, show them as "boards" laid into the deck (each photo a plank-shaped frame), with the Facebook link right under them as "Click to see more of my work."
- **Before/after sliders** with a plain divider in the accent color, if pairs come in.
- Wood type: the fresh layer is pale pine. It could become cedar or ipe to match what he actually builds decks with.
- A one-time "drag to sand" hint near the deck, if Ellie finds people don't realize they can take over.
- `book.html` booking page in the same world; a Spanish toggle (unknown whether useful; ask him).
- Tuning knobs at the top of the script: `SAND` (sanding strength), `REGROW` (gray return speed), `GHOST_DELAY` (ms before the sander resumes on its own), `DUST_MAX`, `PLANK` (board width).

## Not verified
- Real-device touch on iPhone/Android, especially whether `touch-action:none` on the hero strip feels right, or blocks scrolling too much when a thumb lands on it.
- The real SMS handoff on iOS and Android (`sms:+1…?&body=` format), and inside Facebook's in-app browser.
- Frame rate on older phones (four canvases at most 1.5x DPR, each paused off screen).
- How the Facebook link preview looks; check with the Sharing Debugger after Pages caches `og.jpg`.
- The **concept was hand-picked** from six trade worlds; the Impeccable concept roll wasn't run, so there is no seed key.
