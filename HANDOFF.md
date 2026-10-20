# Casi Construction LLC — handoff at ~60% (calm revamp)

**Live:** https://10elizabethbell.github.io/casiConstruction/ · **Repo:** https://github.com/10elizabethbell/casiConstruction · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Facebook group ad) · **Revamped:** 2026-10-19 to the calm band style

## What changed in the revamp (2026-10-19)
- **Whole look replaced.** The sanding-deck world (canvas deck boards, a palm sander that worked by itself and under your finger, scroll-driven planks, card-stock cream, condensed caps, red pencil accent) is gone. It's still in git history at `036a01c` if Ellie ever wants it back as an opt-in signature.
- **Now the house calm band style** (`calm-photo-style.md`), copied from the DPG reference build: paper header → navy hero with the faint line texture → paper "You deal with me." → deep-navy "What I do." service rows → paper "No job is to small." with the three steps and the estimate form → navy close with the big number → deep-navy footer.
- **Palette** mapped from his card (black ink on white, no colours): paper `#f4f6fb`, hammer-head navy `#1f3b5e`, deep navy `#14263f`, one warm accent **pine `#f0b552`** (fresh-cut wood) used only as a fill with navy text on it; `#8a5200` when it has to be text on light. Form hover/focus outline is a separate blue `#1f5fa8`.
- **Type:** Cal Sans headings (Google Fonts, the only external resource), system body 16/1.7.
- **Motion:** the hero H1 bounces in letter by letter (then the plain heading is restored), a 12px fade-up on things below the first screen, and the 60px floating text circle (shows after the hero, hides while the form is on screen). All content shows at once with reduced motion and with JS off. One switch, `CONFIG.MOTION`, turns the motion off.
- **H1 now names the place:** "Built right in Forked River." (was "I build it like it's mine.").
- **Service rows** now all go to the form with that job's chip ticked, on phones too. Before, phones opened a separate text per service. One path is simpler, and the form still ends in a text, with call and copy fallbacks.
- **Form:** job chips (required, unless the description is filled in), "Tell me about it" (optional), town, name → opens a pre-written text to 848-525-7973. If no messages app opens, it shows the message with "Open in Messages", "Copy message" and the number.
- **New** `og.png` (1200×630) and home-screen icon in the new palette; `og.jpg` removed. Favicon is the same hammer mark recoloured.
- **Fixed by hand** (the DPG reference gets these wrong): fields have their own `--field` fill on the white card, the red error edge survives focus, selected-chip focus is an outline with an offset, and the phone number doesn't split.
- **Impeccable:** every mode except `live` and `onboard` (no first-run flow), plus the finish reviewer. Applied:
  - the number no longer clips at 320px
  - a 3×3 desktop service grid (no dead column, no orphan row)
  - service rows scroll to the form itself, so the ticked chip is visible
  - step 2 is "A straight price." so "Free estimate" isn't said three times in a row
  - the owner line is softened (see assumptions)
  - the job error is announced
  - the footer phone link is dropped because the close band right above it shows the number (both reviewers flagged "number twice on one screen")
  - the fallback message is long-press selectable
  - a no-JS contact line
  - reduced motion keeps colour feedback on buttons
- **Checked** in Chrome and WebKit at 320, 360, 390, 414, 430, 1024 and 1440: no sideways scroll, the first phone screen shows header, number, eyebrow, H1, promise and both buttons. Bounce-in is offset early and settled by ~2.6s with the same line breaks. Float hidden on the hero, shown below it, hidden over the form. Form errors, the pre-ticked chip, and the encoded SMS body all checked.

## Assumptions I made
- **Logo:** my vector redraw of his business card (Facebook profile picture): hammer in a circle in the header and favicon, the arched "CASI CONSTRUCTION" with nails in the footer. Card photo stays in `src-assets/`, not committed.
- **Accent colour is mine.** His card has none; pine was chosen for wood/carpentry and to stay warm per the house style.
- **Hero is the plain navy band** because there are no work photos. The only image is the business card, which isn't hero material (a photo of a card on a towel).
- **Voice:** first person "I", one-man business (he posts the ads from his personal profile). The finish reviewer pointed out "from the estimate to the last screw" claimed he does every job himself; it's now "Call Casi Construction and you talk to Casimiro Diaz about your job, big or small."
- **Copy he should approve:** "Built right in Forked River.", the promise ("From one sticking door to a whole new bathroom, I treat your house like it's mine."), the three steps.
- **"No job is to small."** kept verbatim with his spelling, as the brief asks.
- **Audience:** treated as general homeowners, motion on. The brief doesn't flag 40+, but Lacey Township skews older. If Ellie decides it's a 40+ audience, set `CONFIG.MOTION = false` and apply `older-audience.md` (18–20px body, shorter page).
- **Footer** has no phone link: the close band right above it shows the number big, and two reviewers flagged it twice on one screen. The footer line still names the business, town and licensing, then the email and Facebook.

## Placeholders and gaps
- **No work photos, before/afters or reviews,** so there's no proof section. The Facebook link sits under "You deal with me." as "Find me on Facebook" (his profile only shows the ad). When he posts jobs, add work photo cards and move the link under them as "Click to see more of my work."
- **Texting is unconfirmed.** The brief says "Accepts texts: unknown; preferred: call", yet the form and floating circle both send a text. The number top-right and the close band cover calls. If he doesn't take texts: `CONFIG.FLOAT = false` and change the form button to a call.
- **Email** `casiconstructionllc@gmail.com` is from Muse's OCR of the flyer, unverified. Footer only.
- **Business name ↔ Casimiro Diaz** is consistent but unverified (brief).
- No hours, prices, years, insurance details or towns beyond Forked River.

## Questions for the owner
1. Do you take texts at 848-525-7973?
2. Is casiconstructionllc@gmail.com right?
3. Is it just you, or a crew? ("I" vs "we", and whether "you deal with me" holds.)
4. Which towns do you cover? (A short plain-text line, never pills.)
5. Can you send 6–10 photos of finished jobs, and any before/afters?
6. Hours? NJ HIC registration number to show?
7. Any customer you'd ask for a short review?

## Open questions for Ellie
- 40+ audience or not? (one switch, see above)
- Keep the footer without a phone link, or put it back as the kit says?
- The pine accent is invented; OK, or prefer something else?

## Ideas not built (yours to pick)
- **Impeccable findings kept on purpose (Ellie's calm-style choices):** the craft floor bans eyebrows outright and flags the band texture; the finish reviewer noted the eyebrow conflict. The three eyebrows (hero, "Repairs to renovations", "Free estimate"), the H1 bounce-in, the floating circle, Cal Sans and the texture all stay. Detector ignores for the texture and body type steps are in `.impeccable/config.json` with reasons.
- **Opt-in signature (runner-up worlds):** the old sanding deck (in history), a blueprint whose pencil lines draw the house as you scroll, tile being laid, stucco troweled smooth. Sanding deck is the strongest.
- Header that gets a shadow once you scroll past the hero (kit item 1). Not sticky, so not built.
- Chip labels could match the row names exactly ("Flooring and tile" vs "Flooring / tile").
- A short highlight on the chip a service row ticks.
- Atkinson Hyperlegible body if it goes 40+.
- `book.html` booking page; Spanish toggle (ask him).

## Not verified
- Real-device SMS handoff on iOS and Android, and inside Facebook's in-app browser (`sms:+1…?&body=`).
- Real iPhone rendering of Cal Sans loading on cellular (falls back to Avenir Next / system).
- The Facebook link preview with the new `og.png` (Sharing Debugger after Pages caches it).
