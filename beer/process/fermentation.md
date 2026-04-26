# Fermentation

The fermentation schedule for a NEIPA is **the playing field where biotransformation happens**. Get the timing, temperatures, and oxygen handling right and your hops repay you with depth and juice. Get them wrong and you've got expensive hop tea.

## Pre-pitch: oxygenation

Healthy yeast needs oxygen — but only **once**, at pitch.

For a typical 23 L NEIPA at OG 1.065:

- **Aerate the chilled wort** by pouring vigorously, splashing into the fermenter, or running pure O₂ through an oxygenation stone for 30–60 seconds.
- **Target dissolved oxygen: 8–12 ppm.**
- **Pitch yeast immediately after oxygenation** — don't let O₂-saturated wort sit, it'll oxidize.

After this initial dose, **never** intentionally introduce O₂ again. Yeast uses the dissolved O₂ in the first few hours to build cell membranes and reproduce; after that, fermentation is anaerobic.

## Pitch and lag

Pitch a healthy yeast load at **18 °C / 64 °F**.

- **Liquid yeast:** make a starter (1.5–2 L from 1 vial / pack for a 23 L NEIPA).
- **Dry yeast:** 11–14 g (one and a half packs of Verdant IPA or equivalent) for 23 L. Rehydrate per manufacturer instructions.

**Lag time** to visible activity should be 6–18 hours. If you don't see krausen by 24 hours, your yeast is underpitched, too cold, or low-viability — consider a re-pitch.

## Active fermentation: the biotransformation window

Day 1–3 is where the magic happens.

| Day | Approx attenuation | Temp     | What's going on                                                       |
|-----|--------------------|----------|------------------------------------------------------------------------|
| 0   | 0%                 | 18 °C    | Pitch, oxygenate, lag                                                  |
| 1   | 10–30%             | 18–19 °C | Yeast multiplying, krausen rising                                      |
| 2   | 40–60%             | 19–20 °C | Peak fermentation. **Active-ferm dry hop drops here** at 50–70% attenuation |
| 3   | 60–75%             | 20–21 °C | Free-rise, ester development, biotransformation                        |
| 4   | 75–85%             | 20–21 °C | Slowing, late ferm                                                     |
| 5–6 | 85–95%             | 20 °C    | Approaching FG                                                         |
| 7   | FG reached         | Crash to 13 °C | Cold-side dry hop drops                                          |

### The active-ferm dry hop drop

Per Janish (2021) and supported by Sapwood Cellars' procedures: **drop the active-ferm dry hop when fermentation has reached ~50–70% attenuation.** This is typically:

- **24–36 hours after pitch** for a vigorous fermentation
- **36–48 hours after pitch** for a slower start

How to know:

- **Gravity check:** if your OG was 1.065, target dropping the dry hop at gravity ~1.030–1.020.
- **Visual check:** krausen should be at full peak or just starting to fall. Active CO₂ production.
- **Time check:** typically 36 hours post-pitch is a safe default.

**Why this window:**

- Yeast is actively producing CO₂ → scrubs O₂ that gets introduced with the dry hop.
- Yeast still has high enzyme activity (β-glucosidase) → liberates thiols from glycoside precursors.
- Ester production is active → hop-yeast interaction effects are at their strongest.
- Earlier (< 50%): yeast is still in growth phase, may produce off-flavors; some compound classes are scrubbed by very active fermentation.
- Later (post-FG): biotransformation activity drops sharply, yeast settles out.

### Free-rise vs controlled temp

Two schools:

- **Controlled temp (18 °C throughout):** Tighter ester profile, slightly cleaner. Sapwood and many pro brewers do this.
- **Free-rise to 20–22 °C around day 3:** More ester development, slightly more "warm fermentation" character. Common in homebrew.

For a NEIPA, **a moderate free-rise (cap at 21 °C) is fine**. Don't go above 22 °C — fusel alcohols and harsh esters start to dominate.

## End of fermentation: terminal gravity and diacetyl

### Reaching terminal gravity (FG)

For a NEIPA at OG 1.065 with 75–80% attenuation, expect FG ~1.013–1.016.

- **Take gravity readings on days 5, 6, and 7.** Stable for 2–3 consecutive days = FG reached.
- **Don't crash early.** Crashing before FG locks in residual sugar that can re-ferment with hop creep.

### Diacetyl rest

Diacetyl (slick butter / butterscotch character) forms during fermentation and is normally cleaned up by yeast at the end. Heavy dry hopping can interfere with this.

- **At end of primary fermentation, hold at 20 °C for 2 days** before crashing. This is the "diacetyl rest."
- **Sensory check:** warm a sample to room temp, stir to release CO₂, smell. No butter = clean.
- If diacetyl is still present, hold warm for another 1–2 days.

For most NEIPA strains (London III, Verdant IPA), diacetyl is rarely an issue — they clean up well. **Hop creep** is the more likely cause of late-appearing diacetyl: the secondary fermentation from dry hop enzymes can regenerate diacetyl in beer that was already clean.

## Dry hopping during fermentation

See [`../hops/dry-hopping.md`](../hops/dry-hopping.md) for the full Janish-grounded treatment. Operationally for the active-ferm drop:

1. **Purge the dry hop port / vessel with CO₂.**
2. **Add hops** through the closed port (or via a pre-purged hop addition vessel).
3. **Reseal immediately.**
4. **Don't open the lid.**
5. **Optional: brief CO₂ burp from bottom valve** to rouse hops into suspension.

For a FermZilla All Rounder under spunding, this is straightforward — the hop port adapter (sock-style) lets you drop hops without breaking pressure. See [`packaging.md`](packaging.md).

## Cold-side dry hop and crash

After FG (~day 7):

1. **Crash the fermenter to 13 °C / 55 °F** over a few hours.
2. **Drop the cold-side dry hop** at this temperature (cool dry hop per Janish 2021).
3. **Hold at 13 °C for 3 days.**
4. **Optional: brief once-daily CO₂ burp** from the bottom valve to rouse hops.
5. **After 3 days: drop spent hops** through the bottom valve / dump port.
6. **Crash to 4 °C / 39 °F** for clarification.
7. **Hold cold for 1–2 days** — drops yeast and remaining hop debris.
8. **Closed transfer to keg** under CO₂ pressure.

## Hop creep monitoring

After dropping the cold-side dry hop, **continue monitoring gravity** for 3–5 days. If hop creep is happening, you'll see gravity continue to drop:

- 1–2 point drop over 3 days → normal, manageable
- 3–5 point drop → hop creep is real, let it finish
- 5+ point drop → significant creep, hold longer, expect more carbonation

**Don't keg until gravity is stable for 2 consecutive days.** Premature kegging with active hop creep = over-carbonated keg, possibly stressed yeast contributing diacetyl to the package.

If you're using a pressure fermenter (FermZilla), you can spund through hop creep — capture the CO₂, naturally carbonate the beer, monitor pressure rise. See [`packaging.md`](packaging.md).

## Temperature schedules by yeast strain

### London Ale III / Vermont Ale (mesophilic)

| Day | Temp           |
|-----|----------------|
| 0   | 18 °C (pitch)  |
| 1–2 | 18–19 °C       |
| 3–5 | 20 °C (free-rise) |
| 6   | 20 °C (D-rest, optional) |
| 7   | Crash to 13 °C |
| 7–10 | 13 °C (cold-side DH) |
| 10–11 | 4 °C         |
| 11+ | Package        |

### Hornindal Kveik (warm)

Compresses the schedule:

| Day | Temp           |
|-----|----------------|
| 0   | 27 °C (pitch warm) |
| 1   | 28–30 °C       |
| 2   | 28 °C (active-ferm DH at ~36 hr) |
| 3   | 26 °C          |
| 4   | FG approached, crash to 13 °C |
| 5–7 | 13 °C (cold-side DH) |
| 8   | 4 °C           |
| 9+  | Package        |

Kveik can shave a week off the schedule. Useful if you want fast turnaround.

### Verdant IPA / dry yeast

Similar to London III schedule but ferments slightly faster — can shave a day off the active fermentation window.

## What to monitor

For each batch, log:

- **Pitch temp**
- **Lag time to visible activity**
- **OG**
- **Gravity at active-ferm DH drop** (should be 50–70% attenuation)
- **Krausen behavior** (height, color, dropping)
- **Final gravity** and date stable
- **Dry hop drop dates and temps**
- **Hop creep** (gravity drop after cold-side DH)
- **Time at each temperature**
- **Anything unusual** (off-aromas, slow fermentation, foam-overs)

A small notebook beats memory. Pattern recognition across batches is how you get good at this.

## Common fermentation mistakes

- **Underpitching.** Slow start = O₂ exposure window, weak biotransformation, off-flavors. Use enough yeast.
- **Pitching too cold.** < 16 °C and lag stretches significantly. Pitch at 18 °C, let free-rise.
- **Pitching too warm.** > 22 °C at pitch and you'll get banana / fusel character. Pitch cool, free-rise after.
- **Active-ferm DH too early.** < 50% attenuation and yeast is still in growth phase, may produce off-flavors. Wait for it.
- **Active-ferm DH too late.** Past FG and biotransformation has dropped sharply. You've turned an active-ferm DH into an early cold-side DH.
- **Skipping the active-ferm DH.** All-cold-side dry hop will give you a beer that smells fresh but lacks depth. The biotransformation contribution is real.
- **Crashing before FG.** Locks in residual sugar that re-ferments later with hop creep. Wait for stable FG.
- **Kegging with active hop creep.** Over-carbonates the keg, stresses yeast, can regenerate diacetyl in the package.
- **Opening the fermenter for "a quick peek."** Real, measurable O₂ damage. Use a port adapter.

## Cross-references

- **[`../hops/dry-hopping.md`](../hops/dry-hopping.md)** — Janish synthesis on dry-hop technique and biotransformation
- **[`../hops/varieties.md`](../hops/varieties.md)** — variety selection
- **[`whirlpool.md`](whirlpool.md)** — what feeds into fermentation
- **[`packaging.md`](packaging.md)** — what comes after fermentation
- **[`../yeast-strains.md`](../yeast-strains.md)** — strain-specific fermentation behavior
