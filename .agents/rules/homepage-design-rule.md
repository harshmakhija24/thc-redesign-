# Homepage Design Rule — The Healthtech Collective

**Scope:** Homepage only. 3 versions. Nothing else built yet.

---

## The Brand (locked — use only this, never invent)

**Full name:** The Healthtech Collective (THC)
**Founded:** December 2024 by Parul Aggarwal
**Mission (Parul's words):** "How do we accelerate the adoption of technology and innovation in Indian healthcare?"
**Origin:** "It started with a fairly simple idea — everyone in Indian healthcare was operating in their own circles."
**Closing line:** "The best of THC is still ahead of us." — Parul, Founder

**Real stats (use exactly):**
| Stat | Value |
|---|---|
| Members | 7,000+ |
| Events | 80+ |
| City chapters | 5 — Delhi, Mumbai, Bengaluru, Hyderabad, Ahmedabad |
| Cities coming | Chennai, Kochi, Jaipur |

**Audience:** Founders · Clinicians · Investors · Pharma · Hospitals · Operators

**The 3 official pillars (nav words):**
- **Signals** — Newsletter, podcasts, white papers, thought leadership
- **Meet** — Curated in-person events, city chapters, smaller rooms
- **Scale** — Orbyt: AI-enabled networking platform (waitlist open)

**Nav:** `[THC Logo] | Signals ↓  Meet ↓  Scale ↓ | [Join Community]`

**Community channels:** WhatsApp + LinkedIn
**Primary CTA:** `Join the Community` → WhatsApp
**Secondary CTA:** `Join Orbyt Waitlist` → orbyt.club

---

## THE CORE DESIGN PROBLEM (read this before building anything)

The current THC site uses `#FAFAF8` cream — it looks bland, corporate, subdued.
A community of 7,000 healthtech founders, doctors, and investors does NOT feel like `#FAFAF8`.
It feels like energy, momentum, belonging, urgency.

**The reference that felt alive:** theproductfolks.com
Why it felt alive — NOT because of cream. Because of:
- Bold editorial typography with high contrast
- Community photography that fills real estate
- Strong visual hierarchy — one thing demands attention per section
- The "Join Community" CTA stands out because everything else is deliberately muted
- Alternating dark/light sections create rhythm and energy

**Directive:** Each version must have a strong, opinionated color identity.
The days of safe cream are over for this project. Every version should feel like something.

---

## 3 Versions — Each Has Its Own Complete Color Identity

### Version 1 — "Editorial Warm" (closest to TPF reference)
**Mood:** Human, editorial, community-first. Feels like a magazine for builders.
**Hero bg:** Rich warm white `#FAF7F2` — NOT bland, because everything else is bold
**Hero text:** Near-black `#0F0E0D` — heavy, editorial weight
**Accent:** THC pink `#E30071` — used ONLY for Join Community nav + 1 CTA
**Key move:** FULL-WIDTH bold typography. H1 at 72-80px. Italic Playfair Display on emphasis word + hand-drawn SVG underline (like TPF). Large community event photos bleeding edge-to-edge. Alternating DARK NAVY `#0D1B3E` sections break the warmth.
**Energy source:** Typography scale + photography + ink-dark section contrast
**This version is warm cream DONE RIGHT — bold content, not bland layout**

### Version 2 — "Dark Builder" (energetic, premium, high contrast)
**Mood:** This is where serious builders live. Dark, focused, kinetic.
**Hero bg:** Deep navy `#0D1B3E` — full bleed, commanding
**Body bg:** `#080C18` near-black with subtle navy tint
**Hero text:** Pure white `#FFFFFF`
**Accent:** Gradient `#E30071 → #7F30D0` — used generously in this version (dark bg earns it)
**Key move:** Glowing orb atmosphere in bg (CSS radial gradients, no JS). Large stat numbers in gradient text. Glass cards on dark surface. The Orbyt section blends naturally — dark to dark, feels like one product family.
**Energy source:** High contrast + gradient accents + glowing depth
**This version feels like Orbyt's parent community — premium, ambitious**

### Version 3 — "Vibrant Community" (the most alive — builder energy)
**Mood:** Loud, celebratory, kinetic. This is a 7,000-person community, not a startup.
**Hero bg:** White `#FFFFFF` with a dramatic full-bleed GRADIENT MESH hero — pink to purple to deep blue
**Body bg:** Alternates between white sections and bold colored sections
**Accent:** Both pink `#E30071` AND purple `#7F30D0` used actively — this version has permission
**Key move:** Full-bleed gradient hero (like Vercel / Linear homepage energy). Bold pill badges. City chapter grid with colored accent borders. The live activity ticker from Orbyt (CSS marquee: "a founder from Bengaluru requested access...") runs just below hero. This is the most kinetic.
**Energy source:** Gradient hero + live ticker + colored section accents + badge system
**This version is the most different from any "safe" design**

---

## Shared Design Rules (apply to all 3 versions)

### Nav (identical across all versions)
- Pill-shaped nav container (TPF-style, 8px border-radius, border: 1px solid rgba())
- `[THC Logo] | Signals ↓  Meet ↓  Scale ↓ | [Join Community]`
- "Join Community" = the ONLY pink element in nav. No hover transform. Color isolation only.
- Frosted glass: `backdrop-filter: blur(20px)`. Fixed top.

### Fonts
| Role | Font | Where |
|---|---|---|
| Hero emphasis word | Playfair Display italic | The one word per headline that gets emphasis |
| Headings | Outfit 700–800 | All section H2s |
| Body / nav | Inter 400–500 | All body copy, nav links |

### Copy (locked — no invented text)
**H1 per version:**
- v1: `Where India's Healthtech Future Gets *Built*` (Playfair italic on "Built")
- v2: `Bridging the gap between ideas and *implementation*` (Playfair italic)
- v3: `It started with a fairly simple idea.` (plain — founder voice, editorial)

**Subtext:** "7,000+ founders, clinicians, and investors — building the future of healthcare in India."
**Primary CTA:** `Join the Community`
**Secondary CTA:** `Join Orbyt Waitlist`

### Sections (all versions must include these, order may vary)
1. **Hero** — H1 + subtext + CTAs + trust signal
2. **Social proof strip** — "Join 7,000+ healthtech leaders" + CSS logo marquee
3. **3 Pillars** — Signals · Meet · Scale cards
4. **Impact stories** — 4 real quotes (founder / clinician / investor / hospital leader)
5. **Orbyt teaser** — dark section, "Meet Orbyt", waitlist CTA → orbyt.club
6. **Final CTA** — Parul's quote + Join Community

### Orbyt Teaser Section (dark, always — all versions)
This section is ALWAYS dark (navy or near-black) regardless of the version's overall palette.
- Label: `scale`
- H2: `Meet Orbyt.`
- Sub: `Our AI-enabled networking platform — built for healthcare ecosystem builders.`
- Body: `"Ambition is common. Consistency is rare." The people, accountability, and access that keep you moving.`
- Scarcity: `100 founding places · 77 remaining`
- CTA: `Join the Waitlist → orbyt.club`

### Live Activity Ticker (CSS marquee — use in v3 hero, optional in v1/v2)
Items separated by `·` dot:
- "a founder from bengaluru got their first hospital introduction"
- "a clinician found a co-founder through the network"
- "a VC discovered a company they had never heard of"
- "a hospital leader found the solution they were looking for"
- "a deep-tech startup closed their seed round"
- "a founder landed their first enterprise customer"

---

## Stack & Constraints (Ponytail)

- HTML + Vanilla CSS only. No JS libraries unless strictly required.
- One `index.html` per version: `v1/`, `v2/`, `v3/`. Shared base in `styles/main.css`.
- No lorem ipsum. No made-up stats. Only content from this rule.
- Logo marquee: CSS `animation: scroll linear infinite` only — no JS.
- Live ticker: CSS marquee only.

---

## Customer Journey Map (HTML comment at top of every file)

```html
<!--
  CUSTOMER JOURNEY — THC Homepage

  ABOVE FOLD (0-3s — earn attention or lose them)
  → H1: clear identity for Indian healthtech professionals
  → Must feel ALIVE — not a brochure
  → Trust: 7,000+ members visible in fold or immediately below
  → Primary CTA: Join the Community

  FIRST SCROLL (curious)
  → Logo/org marquee: "Join 7,000+ healthtech leaders"
  → Recognize peer organizations = "these are my people"

  SECOND SCROLL (considering)
  → 3 pillars: Signals · Meet · Scale
  → What does membership actually give me?

  THIRD SCROLL (validating)
  → 4 real impact stories — founder/clinician/investor/hospital leader
  → Real moments, not testimonials

  FOURTH SCROLL (excited)
  → Orbyt dark section — the future of the network
  → Scarcity: 77 founding places remaining

  FINAL (warm and low friction)
  → Parul's quote: "The best of THC is still ahead of us."
  → Join Community CTA
-->
```

---

## Emil Kowalski Motion Rules

1. Buttons: `scale(0.97)` on `:active`, `transition: transform 160ms ease-out`
2. Cards hover: `translateY(-4px)` max. Never scale.
3. Entries: `opacity 0→1` + `translateY(8px→0)`. Never `scale(0)`.
4. Easing: `cubic-bezier(0.23, 1, 0.32, 1)`. Never `ease-in`.
5. Stagger: 40ms between items. Max 4 staggered.
6. Duration: UI ≤ 250ms. Hero intro ≤ 400ms.
7. `transition: all` banned. Exact properties only.
8. Hover: `@media (hover: hover) and (pointer: fine)` gate always.
9. Reduced motion: `prefers-reduced-motion: reduce` on every animated element.
10. Marquee/ticker: CSS animation only. No JS.
11. "Join Community" nav: NO hover transform. Color isolation only.

---

## Version Review Checklist

- [ ] Version has a STRONG, opinionated color identity — not default cream
- [ ] Customer journey map as HTML comment at top
- [ ] H1 from approved list — real copy, not invented
- [ ] Real stats: 7,000+, 80+ events, 5 city chapters
- [ ] Nav: TPF pill style, Signals/Meet/Scale, "Join Community" isolated right
- [ ] Logo/org marquee below hero with fade edges
- [ ] Signals · Meet · Scale pillar section
- [ ] 4 real impact story cards
- [ ] Orbyt section is dark regardless of version palette
- [ ] Live ticker present (at minimum in v3, optional v1/v2)
- [ ] All buttons: `:active` scale feedback
- [ ] `transition: all` nowhere in CSS
- [ ] `prefers-reduced-motion` present
- [ ] Responsive: single-column at 375px
- [ ] No lorem ipsum, no invented content

---

## Orbyt Full Intelligence (orbyt.club)

**Tagline:** "The network that moves you forward"
**Core insight:** "Ambition is common. Consistency is rare."
**Product flow:** Share trajectory → Map network → Create right path → Keep moving
**Scarcity:** 100 founding places, 77 remaining
**Who:** Founders · Operators · Investors · Healthcare professionals
**Design:** Pure black bg, `#FF4500` orange-red + `#E8146E` pink accents, DM Sans + Google Sans Flex
**Live ticker:** CSS marquee of network activity — creates FOMO and proof of life
**Key quote:** "Knowing a guy who knows a guy will take you farther in life than any degree ever would."
