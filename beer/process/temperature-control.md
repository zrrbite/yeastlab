# Temperature control & fermentation chambers

The single most underappreciated piece of brewing equipment is the **fermentation chamber** — a temperature-controlled space where your fermenter lives. With one, you can ferment any style at any time of year regardless of ambient kitchen temperature. Without one, you're limited to whatever your kitchen happens to be.

This file covers fermentation chamber options (with KegLand specifics), the temperatures that matter for different beer styles, and how to use a chamber effectively across the brewing pipeline.

## Why temperature control matters

Beer fermentation is **temperature-driven chemistry**. A few degrees swing in fermentation temp produces:

- **Different ester profiles** (warmer = more banana/clove, often unwanted)
- **Different attenuation** (warmer = more attenuation, drier finish)
- **Different fusel alcohol production** (warmer = more "hot alcohol" character)
- **Different fermentation speed** (warmer = faster, sometimes too fast)

For NEIPA specifically:

- **18 °C pitch then free-rise to 21 °C** is the sweet spot for biotransformation
- **A warm kitchen (24+ °C)** would push esters into too-fruity territory and accelerate hop creep
- **A cold kitchen (15 °C)** would stall fermentation and never reach biotransformation potential

For Cold IPA:

- **12–15 °C** is the lager-yeast target
- **Without a chamber, you can't ferment Cold IPA properly** in most kitchens

For all NEIPA dry hopping:

- **13 °C cold-side dry hop** per Janish — needs a chamber to hit reliably

A fermentation chamber **unlocks every style** at the right temperature regardless of season or kitchen.

## KegLand fermentation chambers

KegLand makes several fermentation temperature-control products:

### KegLand Fermentation Fridge (the basic chamber)

A **modified upright or chest freezer/fridge** with a temperature controller (Inkbird, STC-1000, or similar) wired to either chill or heat. Most affordable serious option.

Variants:

- **Conversion kits** — buy any chest freezer, add a KegLand controller and (often) a heat element
- **Pre-built chambers** — purpose-built fermentation refrigerators at multiple capacities

### KegLand Series X / Apex (compact dedicated chambers)

Purpose-built upright fermentation chambers designed for FermZilla-sized fermenters. Smaller footprint than a chest freezer; designed to fit a 30L FermZilla comfortably.

### Glycol chillers (for serious setups)

For multi-fermenter operations or precise temperature control:

- **KegLand glycol chillers** circulate cold glycol through cooling coils on each fermenter
- Allows independent temperature control per fermenter
- Significantly more expensive ($500+) but enables semi-pro brewing

### What you have (likely)

If you got a KegLand fermentation chamber from your brother, it's likely either the **Series X** (purpose-built fermentation cabinet) or a **standard chest freezer / upright** with KegLand temperature control. Both work great. The Series X is more compact; the chest-freezer-style is more flexible (room for multiple fermenters or kegs).

## Temperature control basics

A fermentation chamber needs:

1. **A cold source** (refrigerator or chest freezer)
2. **A heat source** (small ceramic heater or heat belt for warming above ambient)
3. **A temperature controller** (Inkbird ITC-308 is the standard) that switches both sources based on a probe attached to the fermenter

The controller works like this:

- **Probe taped to the fermenter** (with insulation over it to read fermenter temp, not air temp)
- Set point: e.g. **18 °C**
- **Differential:** ±0.5 °C (controller turns on cooling/heating only when temp drifts beyond)
- Cooling on if temp >18.5; off when back to 18
- Heating on if temp <17.5; off when back to 18

This produces **rock-solid temperature control** within ±0.5 °C — far better than ambient kitchen swings.

## Chamber temperature profiles by style

### NEIPA / Hazy IPA

| Phase                | Chamber temp     | Duration       |
|----------------------|------------------|----------------|
| Pitch                | 18 °C            | Day 0          |
| Active fermentation  | 18–19 °C         | Days 1–2       |
| Active-ferm dry hop  | 19 °C            | Day 2–3        |
| Free-rise            | 20–21 °C         | Days 3–7       |
| Cold-side dry hop    | **13 °C**        | Days 7–10      |
| Cold crash           | 4 °C             | Days 10–11     |
| Closed transfer      | 4 °C             | Day 12         |

The chamber needs to **swing from 21 °C → 13 °C** for the cold-side dry hop — a 8 °C drop. Most fridges handle this in 2–4 hours; allow time.

### West Coast IPA

| Phase                | Chamber temp     | Duration       |
|----------------------|------------------|----------------|
| Pitch                | 18 °C            | Day 0          |
| Active fermentation  | 18–20 °C         | Days 1–6       |
| Diacetyl rest        | 22 °C            | Days 6–8       |
| Cold-side dry hop    | 18 °C            | Days 8–13      |
| Cold conditioning    | 0–2 °C           | Days 13–24     |
| Closed transfer      | 0 °C             | Day 25         |

The cold conditioning at 0–2 °C is what makes WCIPA brilliant — needs the chamber.

### Cold IPA / Pilsner

| Phase                | Chamber temp     | Duration       |
|----------------------|------------------|----------------|
| Pitch                | 10 °C            | Day 0          |
| Active fermentation  | 12–13 °C         | Days 1–10      |
| Free-rise            | 14 °C            | Days 10–13     |
| Diacetyl rest        | 18–20 °C         | Days 13–16     |
| Crash + dry hop (Cold IPA) | 12 °C       | Days 16–21     |
| Cold lagering        | 0–1 °C           | Days 21–60+    |

Lager fermentation is **impossible** in most kitchens without a chamber. This is the style that most justifies the equipment investment.

### Saison

Saisons benefit from temperature control to **encourage warm fermentation**:

| Phase                | Chamber temp     | Duration       |
|----------------------|------------------|----------------|
| Pitch                | 22 °C            | Day 0          |
| Free-rise            | **28–32 °C**     | Days 1–14      |
| Crash                | 4 °C             | After FG       |

Saison wants to stay warm for the full ferment; the chamber holds the temperature without letting your house get hot.

## Chamber operations

### Probe placement

**Don't measure air temperature.** The chamber is full of cold air; the fermenter is at a different temperature.

Best practice:

- **Tape the probe** to the side of the fermenter, ~1/3 from the bottom
- **Cover with insulation** (small piece of foam, packing material) to prevent the probe from reading air temp
- This produces accurate fermenter temperature readings

### Differential / hysteresis

Set the controller's differential to **0.5–1.0 °C**. Tighter differentials make the chamber cycle constantly (wear on the compressor); wider differentials let temperature drift more.

### Avoiding rapid temperature swings

When changing setpoints:

- **Don't drop 10 °C instantly.** Modern fermenters can handle it but the yeast doesn't like it.
- **Drop in stages** — 21 °C → 17 °C → 13 °C over 8–12 hours, not all at once
- **Same for warming** — diacetyl rest from 18 → 22 should take a few hours, not minutes

### Multi-fermenter chambers

If you're fermenting multiple batches:

- **They have to share temperature.** You can't ferment a NEIPA and a saison at the same time in the same chamber.
- **Plan your brewing schedule** so chamber occupants want the same temp range
- **Or invest in glycol** for independent control

## What to look for in chamber quality

If you're evaluating fermentation chambers (your KegLand or shopping for another):

- **Capacity** — does your fermenter fit? With airlock clearance? With dry-hop port access?
- **Temperature range** — can it hit 0–2 °C reliably? Can it heat to 30+ °C for saisons?
- **Insulation quality** — better insulation = less compressor cycling = longer life
- **Door / lid access** — can you open it without disrupting fermentation?
- **Power consumption** — fermentation chambers run 24/7
- **Drainage** — needed for chest freezers (condensation pools)

## Why this matters for IPA specifically

For NEIPAs, a chamber unlocks:

- **Cold-side dry hop at 13 °C** — Janish's recommended temperature for less polyphenol extraction, less hydrocarbon over-extraction, better foam, less hop creep
- **Consistent fermentation temperature** — eliminates warm-kitchen ester variability
- **Reliable cold-crash to 4 °C** before transfer — drops yeast and hop debris properly

For WCIPA:

- **Cold conditioning at 0–2 °C for 7–10 days** — the clarity step
- **Without this, you have a hazy WCIPA** — which is functionally a worse NEIPA

For Cold IPA:

- **The whole style** — impossible without chamber

For DIPA fermentation:

- **High-gravity ferments need warmer temps** to avoid stalling at FG
- A chamber lets you free-rise to 22 °C reliably

## Cross-references

- **[`fermentation.md`](fermentation.md)** — the fermentation pipeline, with temperature-specific notes
- **[`packaging.md`](packaging.md)** — closed-transfer at the right temperature
- **[`../styles/cold-ipa.md`](../styles/cold-ipa.md)** — the style most justifying chamber investment
- **[`../styles/saison.md`](../styles/saison.md)** — saison's warm fermentation benefits
- **[`../yeast-strains.md`](../yeast-strains.md)** — strain-specific temperature ranges
