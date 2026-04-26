# Adjusting your tap water for brewing

The companion to [`water.md`](water.md). That file describes the **target NEIPA water profile** — chloride-forward, soft, ~150 ppm hardness — assuming you start from RO. **This file is for everyone whose water doesn't come from RO** — i.e., everyone who wants to skip the cost and hassle of a reverse osmosis system but still produce great beer.

The short version: **most municipal tap water can be adjusted to NEIPA spec with a few salts and a small amount of acid**, but you need a water report to know what you're starting with.

## Step 1: Get your water report

Three ways to get an accurate water profile:

### Free: your municipal water provider

US public water utilities are required to publish **annual water quality reports** (CCR — Consumer Confidence Report). Your local utility's website will have it.

Look for:

- **Calcium (Ca)** — usually in mg/L = ppm
- **Magnesium (Mg)**
- **Sodium (Na)**
- **Chloride (Cl)** — different from chlorine
- **Sulfate (SO₄)**
- **Bicarbonate (HCO₃)** or **alkalinity** (often expressed as CaCO₃ equivalent)
- **pH**
- **Total hardness** (CaCO₃ equivalent)
- **Chlorine / chloramine** treatment

Limitation: **municipal reports are averaged across the year**. Your tap water can vary seasonally, and exact composition at your specific tap may differ.

### Paid: Ward Labs water test

**Ward Laboratories** (US) — the standard brewing community lab. Send them a water sample, ~$30, get a comprehensive report in 1–2 weeks.

- **Test kit:** Ward Labs "Brewer's Test (W-6)" — $35, includes shipping vials and instructions
- **Results:** PDF with all the relevant ions, plus pH and alkalinity, expressed in ppm

For brewers who care about water quality: do this once. Your tap water profile is unlikely to change much over time (unless your municipality changes water sources).

### Cheap and quick: TDS pen + alkalinity strips

A $20 TDS (total dissolved solids) pen + $10 alkalinity strips give you **rough indicators**:

- TDS = total mineral content (no detail on which minerals)
- Alkalinity strips = bicarbonate/carbonate buffering capacity

Useful for **diluting decisions** (high TDS = more dilution needed) but not for precise recipe building.

## Common municipal water profiles

Until you have your own report, these are typical profiles to compare against:

### "Soft mountain" water (Pacific Northwest, parts of Northern Europe)

Typical Portland, OR profile:

- Ca: ~5 ppm
- Mg: ~2 ppm
- Na: ~3 ppm
- Cl: ~5 ppm
- SO₄: ~5 ppm
- HCO₃: ~10 ppm
- Hardness: ~17 ppm
- TDS: ~30 ppm

**Conclusion:** This water is **almost RO-equivalent**. Add salts directly to NEIPA spec; no dilution needed.

### "Moderate" water (US Midwest, parts of UK)

Typical Chicago / Cleveland profile:

- Ca: ~35 ppm
- Mg: ~10 ppm
- Na: ~10 ppm
- Cl: ~25 ppm
- SO₄: ~25 ppm
- HCO₃: ~110 ppm
- Hardness: ~125 ppm
- TDS: ~200 ppm

**Conclusion:** Workable but **alkalinity needs reduction with acid**. Salt additions must account for what's already there.

### "Hard" water (US Southwest, much of Continental Europe)

Typical Phoenix / Munich profile:

- Ca: ~80 ppm
- Mg: ~25 ppm
- Na: ~20 ppm
- Cl: ~60 ppm
- SO₄: ~80 ppm
- HCO₃: ~200 ppm
- Hardness: ~300 ppm
- TDS: ~450 ppm

**Conclusion:** **Too hard for most styles unless diluted with RO**. Acid addition essential. NEIPA difficult without dilution.

### "Very hard / Burton-style" (Burton-on-Trent, parts of Texas)

- Ca: ~200 ppm
- SO₄: ~600 ppm
- HCO₃: ~250 ppm

**Conclusion:** Built for English bitter / pale ale styles. Need significant RO dilution for NEIPA; works as-is for English IPAs.

## How to know what to do with YOUR water

After you have your report:

### 1. Identify your profile

- **Soft (TDS < 50, hardness < 50):** treat as RO; add salts to spec
- **Moderate (TDS 100–250, alkalinity 50–150):** workable; need acid to manage alkalinity, careful salt additions
- **Hard (TDS > 300, alkalinity > 150):** likely need to **dilute with RO** before adjusting

### 2. Decide on dilution

**Calculate dilution ratio:** if your water is 2× harder than the NEIPA target hardness:

$$
\text{RO ratio} = 1 - \frac{\text{target hardness}}{\text{tap hardness}}
$$

Example: tap water at 300 ppm hardness, NEIPA target 150 ppm:

$$
\text{RO ratio} = 1 - \frac{150}{300} = 0.5
$$

= use **50% RO + 50% tap** for your batch.

Then add salts to the diluted water as if it were RO (since the dilution roughly matches RO + your tap-water minerals).

### 3. Calculate acid for mash pH

If your alkalinity is high, the bicarbonate will push your mash pH up — needs acid to bring it back down:

- **Phosphoric acid (10% food-grade)** is cheap and easy
- **Lactic acid** works but adds a slight sourness flavor
- Use a **water calculator** (Bru'n Water, Brewer's Friend Water Tool, BeerSmith) to compute exact dose

Rough rule of thumb: for **moderate alkalinity** (~110 ppm HCO₃), about **2–4 mL of 10% phosphoric acid** per 30 L of water gets mash pH to 5.4 from a typical pale-malt grain bill.

For **high alkalinity** (200+ ppm HCO₃), much more acid is needed — and at that point dilution with RO is usually easier than acid management.

### 4. Add salts to spec

Now compute what you need to add to reach NEIPA spec from your starting profile.

For example, your tap water is the "moderate" profile above (Ca: 35, Mg: 10, Na: 10, Cl: 25, SO₄: 25, HCO₃: 110).

**NEIPA target:** Ca: 90, Mg: 10, Na: 20, Cl: 140, SO₄: 60, HCO₃: <30 (after acid).

**Deficits to add:**

- Ca: +55 ppm (add via CaCl₂)
- Mg: 0 (already at target)
- Na: +10 ppm
- Cl: +115 ppm (CaCl₂ adds chloride too)
- SO₄: +35 ppm

**For 30 L brewing water:**

- **CaCl₂·2H₂O (calcium chloride):** ~6 g (adds ~55 ppm Ca and ~115 ppm Cl)
- **Sodium chloride (table salt):** ~1 g (adds ~10 ppm Na, small Cl boost)
- **Calcium sulfate (gypsum):** ~2 g (adds ~25 ppm Ca, but gets us to ~80 SO₄)
- **Phosphoric acid:** ~3 mL (drops alkalinity, mash pH to 5.4)

This is roughly the workflow for any moderate-water tap brewing.

## Worked example — moderate tap water for NEIPA

Starting water: Ca 35, Mg 10, Na 10, Cl 25, SO₄ 25, HCO₃ 110
Batch: 30 L total brewing water (mash + sparge)
Target: NEIPA spec

### Pre-brew

1. **Treat for chlorine/chloramine first:** add **1 campden tablet (potassium metabisulfite)** to 30 L of water. Stir, wait 5 min. **Chloramine reaction is fast.**
2. **Wait** 5–10 min before adding any salts (they need to react first).

### Salt additions

Add to the brewing water (whether you split mash/sparge or treat all at once):

- **Calcium chloride (CaCl₂·2H₂O):** 6 g
- **Calcium sulfate (gypsum):** 1 g (adds slight sulfate)
- **Sodium chloride:** 0.5 g
- **Phosphoric acid (10%):** 3 mL → drops pH and alkalinity

### Mash pH check

After mashing in, check mash pH with a meter:

- **Target:** 5.4
- **If high (>5.5):** add 1–2 mL more phosphoric to mash water for next batch
- **If low (<5.3):** add slightly less acid next time

A **good pH meter** ($30–60) is one of the most useful brewing tools. Strip tests are too imprecise for this.

## Worked example — hard water for NEIPA (Phoenix/Munich)

Starting water: Ca 80, Mg 25, Na 20, Cl 60, SO₄ 80, HCO₃ 200, hardness 300
Batch: 30 L total

This water is **2× too hard for NEIPA target** (300 vs 150). Recommended:

### Step 1: dilute

- Use **50% RO + 50% tap** = 15 L RO + 15 L tap
- Effective starting profile: Ca ~40, Mg ~12, Na ~10, Cl ~30, SO₄ ~40, HCO₃ ~100

### Step 2: salt additions

Now treat this diluted water like the moderate example above:

- **CaCl₂·2H₂O:** 5 g
- **NaCl:** 0.5 g
- **Phosphoric acid:** 3 mL

Result: NEIPA-compatible water from a hard starting source.

### Skip dilution for WCIPA?

A hard tap water profile happens to be **closer to WCIPA spec** (sulfate-forward, hard) than NEIPA. For WCIPA you might skip dilution entirely:

- Add minimal salts (already mostly in spec)
- Heavy phosphoric acid to manage alkalinity
- Bake-at-the-WCIPA-style spec

## Skipping the calculator: a rough heuristic

For most moderate municipal water:

- **Treat for chlorine first** (campden tablet)
- **Add 5–7 g CaCl₂** per 30 L for NEIPA
- **Add 2–3 g gypsum** per 30 L for NEIPA (more for WCIPA)
- **Add 1 g NaCl** per 30 L
- **Add 2–3 mL of 10% phosphoric acid** per 30 L
- **Check mash pH**, adjust acid for next batch

This is "close enough" for most starting tap water profiles. Refine with calculator + meter as you brew more.

## Why this matters

A bad water profile produces:

- **Off-flavors:** chlorine → chlorophenols (band-aid medicine taste); high alkalinity → harsh bitterness; wrong sulfate → muddy hop character
- **Mash inefficiency:** wrong pH → poor enzymatic conversion → low gravity, off-style fermentation
- **Style mismatch:** NEIPA water on a WCIPA grain bill (or vice versa) → beer that fights itself

A good water profile lets every other brewing decision do its job. **Water is the foundation.**

## Common mistakes

- **Skipping the chlorine treatment.** Single biggest tap-water mistake. Always treat with campden first.
- **Using municipal report numbers without verification.** Your tap may differ; especially after a water source change.
- **Trusting TDS alone.** TDS doesn't distinguish between different ion compositions.
- **Adding salts without measuring.** "A pinch" is not a unit. Use a 0.01 g scale.
- **Not checking mash pH.** The single number that tells you if your water/grain bill combination is working.
- **Using softeners.** Home water softeners exchange Ca for Na, producing high-sodium water that's bad for brewing. Bypass softeners for brewing water.
- **Ignoring the source.** Well water, surface water, and recycled water have different starting profiles even within the same municipality.

## When to invest in RO

If your tap water requires significant dilution (>50% RO) routinely:

- A countertop RO system: $200–400, makes 50 L/day
- An under-sink RO system: $300–600, plumbed-in
- The math: at $0.20 per 30 L of RO from kiosks, that's $50–100/year for serious brewing
- A home RO system pays back in 2–3 years for a frequent brewer

For occasional brewing or moderate tap water: **RO from a grocery kiosk** ($0.30 per gallon) is fine.

## Cross-references

- **[`water.md`](water.md)** — NEIPA water target profile and the why behind it
- **[`../theory/water-minerals.md`](../theory/water-minerals.md)** — chemistry of brewing salts (cross-craft)
- **[`recipes/neipa-template.md`](recipes/neipa-template.md)** — recipe-level water salt amounts
- **[`recipes/west-coast-ipa.md`](recipes/west-coast-ipa.md)** — WCIPA water (inverted from NEIPA)
- **[`recipes/cold-ipa.md`](recipes/cold-ipa.md)** — Cold IPA water (mild SO₄-leaning)
