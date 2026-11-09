---
name: unslop
description: Use when building, redesigning, or fixing any frontend UI that looks generic or "AI made". Derives the design from the brief instead of from a default recipe, applies 20 concrete unslop fixes, then verifies by rendering screenshots and linting. Replaces the overlapping ban-list skills as the single driver for UI work.
---

# unslop

Slop is not a style. It is what happens when a design decision was never made and the
model's default filled the gap. Every rule below is a way of forcing a real decision
back into the work.

Two failure modes to avoid:

1. **Shipping the default.** Filler badges, three icon cards, a gradient, a vague headline.
2. **Shipping the anti-default as a new default.** If you always reach for the same
   "premium" recipe (pill buttons, glass nav, rounded-[2rem] everywhere, an eyebrow on every
   heading), that recipe is now the tell. Do not copy a look from this file. Derive it.

This skill contains no approved font list, no approved palette, no layout recipe.

## Workflow

### 1. Brief, in writing, before any code

Write these five lines. If you cannot, ask the user one question.

- **Who and where:** who uses this, on what device, in what light and mood.
- **Job:** the one thing the page or screen must make easy.
- **Three voice words:** physical-object words, not "modern" or "clean". For example
  "warm, mechanical, opinionated" or "calm, clinical, careful".
- **Named reference:** one real product, publication or object this should feel closer to
  than average. If the user supplied none, pick one and say so.
- **Real content:** the actual product name, features, numbers and screenshots available.
  List what is missing. Never invent it silently (see rule 6).

### 2. Derive tokens from the brief

Type, color, radius, density and motion all come from the lines above.

- If the brief names a known system or brand, read `design-systems/brand-systems/<name>/`
  and take real tokens from it.
- If the repo already has tokens, components or a DESIGN.md, those win. Rule 5.
- Choose fonts by browsing for the voice words, not by recalling favorites. If the font you
  first thought of is one you have used before, discard it.
- Pick one accent (rule 11), one radius system (rule 14), one icon family (rule 12).

### 3. Build with the 20 rules below

### 4. Render and look (mandatory)

Text checklists cannot catch a visual problem. After building:

```bash
node core-design/unslop/scripts/shoot.mjs <file-or-url> <outdir>
```

It writes mobile (390), tablet (820) and desktop (1440) full-page screenshots. Open them
with the Read tool and actually look. Then run the lint:

```bash
node core-design/unslop/scripts/lint.mjs <file.html|dir>
```

Fix everything it flags or write down why it is intentional. Then critique the screenshots
against the named reference from step 1, fix, and re-shoot. Do at least one fix loop.

### 5. Report

Say what you derived (voice words, reference, accent, fonts), what you could not get
(real screenshots, copy), and anything the lint flagged that you kept on purpose.

---

## The 20 rules

### Remove what carries no information

**1. Delete filler badges.**
Pills like "New", "Beta", "v2.0", "AI-powered", "Now in early access", status dots, and
tags laid over images are decoration. Keep a badge only when it states something the
reader must act on (a real state, a real count) and appears once. Test: if you delete it,
does anyone lose information? If no, delete it.

**2. Drop redundant labels.**
Do not label what is already obvious: a "Pricing" eyebrow above a pricing heading, a
"Features" kicker above a features grid, a caption that repeats the image alt, a
placeholder that repeats its label, a unit repeated on every row of a column that already
has it in the header. If the heading says it, the label goes. Never put a tiny uppercase
tracked eyebrow above every section.

**3. Unitalicize random words.**
No single italic word dropped into a headline for flavor, and no serif word injected into
a sans headline. Emphasis comes from weight or size within one family, used on a word that
is actually the point. Italics are for titles, foreign terms and real stress.

**4. Mono only where needed.**
Monospace is for code, identifiers, keyboard keys and aligned data. It is not a
"technical" costume for labels, nav links or captions. If the brand is not a developer
tool, mono should be nearly absent.

**13. Remove embellishments.**
Cut decoration that explains nothing: gradient text, glow, blobs, mesh orbs, grain over
everything, crosshair lines, corner ticks, rotated side text, decorative dividers, scroll
cues, locale or clock strips, version footers, "01 / 02 / 03" section numbering that is
not a real sequence. When in doubt, take it out and see if the page got worse.

### Make the content real

**6. Show the actual product.**
Use a real screenshot, a real component rendered live, or a generated image of the real
thing. Never a fake dashboard built from styled divs, and never a hero that is only text
over a gradient. If no real asset exists, leave a labeled placeholder slot and tell the
user exactly which assets are needed. Photography should come from the brand's physical
world ("hand-cut pasta on a scratched oak table"), not the category ("Italian food").

**9. Make headlines specific.**
A headline must say what the product does, for whom, with a concrete noun and verb. Fail
tests: it could sit on a competitor's page unchanged; it contains streamline, empower,
supercharge, seamless, unleash, elevate, next-generation, all-in-one; it is a
statement-then-negation ("Not just X. Y."). Rewrite until a stranger could say what you
sell. Use real, messy, plausible numbers and names, never 99.9%, Acme, or John Doe, and
label anything unverified as sample data.

**16. Wrap headlines properly.**
`text-wrap: balance` on headings, `text-wrap: pretty` on prose, body measure 60 to 75ch.
No single-word last lines, no 4-line hero headline (a long headline is a font-size
error: lower the size). Check every breakpoint in the screenshots. Buttons stay on one
line. Never let a heading overflow its container.

### Hierarchy and composition

**7. Enlarge the main feature.**
Decide the one thing the viewer should see first and make it dominant by size, not just
weight. Identical tiles imply identical importance, which is almost never true. Use one
large primary element and smaller supporting ones. Three equal icon cards in a row is the
default to avoid; if a grid is right, vary the cell sizes by importance and fill every
cell with real content.

**8. Group with spacing.**
Use space before lines and boxes. Related things sit close, unrelated things sit far, and
the ratio is obvious. Remove cards that only exist to hold text, and never nest cards. A
divider is allowed when it separates real groups, not under every row. Use a small spacing
scale (for example 4, 8, 12, 16, 24, 40, 64) and vary rhythm between sections.

**10. Emphasize the CTA.**
One primary action per view, visually unmistakable: highest contrast fill, largest hit
area, clear verb plus object ("Start free trial", not "Learn more" or "Submit"). Secondary
actions are quieter. Two CTAs with the same intent ("Contact us" and "Get in touch") become
one label used everywhere. Check contrast of the label on the button (rule 15).

**17. Align by eye, not pixels.**
Mathematically centered is often visually wrong. Nudge optically: icons next to text,
play triangles, rotated or round shapes, text in buttons with an icon, large type whose
side bearings make the left edge look indented. Align baselines across side-by-side
items, pin card buttons to the same row, and start repeated lists at the same y. Look at
the screenshot and trust it over the numbers.

### Color, type and shape systems

**5. Use a design system.**
Work inside one system, not ad hoc values. If the project has tokens or components, use
them. If it is a known ecosystem (Material, Fluent, Carbon, Radix, shadcn, GOV.UK), use the
official package and customize it, never ship default state. If it is new, define tokens
first (color roles, type scale, spacing, radius, shadow, motion) as CSS variables, then
build only from them. No raw hex values or one-off sizes in components.

**11. Add an accent colour.**
Neutrals plus exactly one deliberate accent, used for the primary action, links and key
emphasis, and nowhere else. The accent should come from the brand or brief, not from
"blue" or from the AI purple to blue gradient. Tint neutrals very slightly toward the
accent hue instead of pure gray. Lock it for the whole page, including charts and states.
A page with no accent has no hierarchy; a page with five has no meaning.

**12. Keep icons consistent.**
One icon family, one stroke weight, one size per role, one corner style. Never mix filled
and outlined, never hand-draw an SVG icon, never use an emoji as an icon. If a glyph is
missing, pick it from the same family or use a word. Icons that only restate adjacent text
(a rocket next to "Fast") go away (rule 2).

**14. Inner radius = outer radius minus padding.**
For nested rounded shapes, `inner = outer - padding`. A 24px card with 8px padding holds a
16px inner image or button. Mismatched radii make the corner gap uneven and instantly read
as unrefined. Pick one radius scale for the whole page and write down the rule; do not mix
sharp, soft and pill without a stated logic.

**15. Improve text contrast.**
Body text 4.5:1 or better, large text 3:1, and placeholders and helper text meet the same
bar. The common failure is pale gray body copy on a tinted near-white "for elegance". Move
body color toward the ink end. On colored backgrounds use a darker shade of the background
hue rather than gray. Check buttons, form labels, footer links and text over photos (use a
scrim). Test in both themes if dark mode exists.

**18. Use tabular nums.**
Any column or stack of numbers (prices, tables, stats, timers, counters) gets
`font-variant-numeric: tabular-nums` so digits align and do not jitter as they change.
Right-align numeric columns. Use consistent decimals and units. This replaces the habit of
switching to mono for numbers (rule 4).

### States and motion

**19. Add loading states.**
Every async surface has loading, empty and error states, not only the happy path. Loading
uses skeletons shaped like the final layout, not a lone spinner. Empty states say what the
thing is and how to fill it, with an action. Errors say what happened and how to fix it,
near the field. Disabled, focus and hover states exist for every control, with a visible
focus ring.

**20. Animate useful feedback.**
Motion must answer "what does this communicate?": a press registered, something was added
or removed, a state changed, attention should go here. Use transform and opacity, 120 to
250ms for feedback, ease-out curves, no bounce. Do not fade every section in on scroll
with the same animation, do not loop things forever, and always honor
`prefers-reduced-motion`. If you cannot say what an animation tells the user, delete it.

---

## Pre-ship checks (short, on purpose)

- Screenshots viewed at 390, 820 and 1440, and a fix loop done.
- `lint.mjs` clean or each hit justified.
- You could name the reference and the three voice words and point to where they show.
- One accent, one icon family, one radius rule, one font decision per role.
- No em dashes or invented stats in the copy.
- Loading, empty and error states exist where data exists.

If another design skill is also loaded, this one is the driver. Use the others only as
lookups (`brand-systems/`, `ui-ux-pro-max`) or for motion detail (`motion/*`).
