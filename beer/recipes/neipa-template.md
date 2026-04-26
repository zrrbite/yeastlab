# NEIPA template

A parameterized base recipe you can plug your hop choices into. Built for **23 L (6 gal) into the fermenter** on a simple boiler + immersion chiller setup, fermented in a FermZilla All Rounder under spunding.

This is a **framework, not a fixed recipe.** Pick your hops from [`../hops/varieties.md`](../hops/varieties.md), confirm your yeast from [`../yeast-strains.md`](../yeast-strains.md), and dial water from [`../water.md`](../water.md). Process notes link to the relevant files.

## Vital stats

| Parameter        | Target            |
|------------------|-------------------|
| OG               | 1.062–1.066       |
| FG               | 1.013–1.016       |
| ABV              | 6.5–7.0%          |
| IBU (calculated) | 35–45             |
| Color (SRM)      | 4–6               |
| Mash pH          | 5.4               |
| Boil pH (post-acidified) | 4.8–4.9   |
| Final beer pH    | 4.4–4.6           |
| Carbonation      | 2.4–2.6 vol CO₂   |

## Grain bill

For a **23 L into fermenter** at OG 1.064 (~75% mash efficiency, adjust to yours):

| Grain                         | Bakers % | Grams |
|-------------------------------|---------:|------:|
| Pilsner malt (or 2-row pale)  | 65%      | 4000  |
| Flaked oats                   | 15%      | 925   |
| Flaked wheat (or malted wheat)| 15%      | 925   |
| Carapils / dextrin malt       | 5%       | 310   |

**Total grain:** ~6.16 kg / 13.6 lb

Notes:

- **Pilsner base** gives a slightly softer, more delicate beer. **2-row pale** is fine and slightly cheaper. Avoid Maris Otter or anything with deeper malt character — it'll fight the hops.
- **Oats + wheat together at 30%** is the haze backbone. You can swap proportions (20/10, 10/20) to taste — more wheat = drier mouthfeel, more oats = silkier.
- **Carapils** is optional. Adds a touch of body without color or sweetness. Skip if you want a drier finish.

## Water

Target: **soft, chloride-forward, Cl:SO₄ ≈ 2:1.**

For a 30 L total water volume (mash + sparge), starting from RO:

| Salt                          | Add to mash | Add to kettle | Total grams |
|-------------------------------|-------------|---------------|-------------|
| Calcium chloride (CaCl₂·2H₂O) | 6 g         | 4 g           | 10 g        |
| Calcium sulfate (gypsum)      | 2 g         | 1 g           | 3 g         |
| Sodium chloride               | 1 g         | 0.5 g         | 1.5 g       |
| Magnesium sulfate (Epsom)     | 0.5 g       | —             | 0.5 g       |

**Acid:** phosphoric acid (10% food-grade), enough to hit:

- Mash pH **5.4** — typically 1–2 mL in mash water
- Post-boil pH **4.8–4.9** — typically 1–3 mL added to kettle as it boils

Use a pH meter. Strips are too imprecise for this style.

See [`../water.md`](../water.md) for the full water explanation and tap-water adjustments.

## Mash

- **Mash temp:** 67 °C / 152 °F
- **Mash time:** 60 min
- **Mash thickness:** ~3 L/kg (1.4 qt/lb)
- **Sparge:** batch or fly to collect ~30 L of pre-boil wort. Sparge water at 76 °C / 168 °F.

Some brewers use a step mash (lower-temp protein rest) to manage haze stability — overkill for this style with this much wheat/oats. Single-infusion at 67 °C is plenty.

## Boil

- **60 min boil**
- **60 min:** Bittering hop addition (~10–15 IBU) — Magnum, Warrior, CTZ, or just a small Citra/Mosaic addition. ~15–20 g of a high-alpha hop.
- **0 min (flameout):** Stop boil, begin cooling toward whirlpool temp.

## Whirlpool / hopstand

- **Cool to 82 °C / 180 °F** (~5–8 minutes with immersion chiller).
- **Add whirlpool hops** — your aroma load.
- **Stand 25 minutes**, covered, no further chilling.
- After 25 min, resume chilling to fermentation temp.

**Whirlpool hop dose:** ~6 g/L = **~140 g** of your chosen aroma hops.

Example whirlpool combos (pick one or design your own from [`../hops/varieties.md`](../hops/varieties.md)):

- 70 g Citra + 50 g Mosaic + 20 g Galaxy
- 70 g Citra + 50 g Idaho 7 + 20 g El Dorado
- 60 g Citra + 60 g Mosaic + 20 g Strata
- 60 g Galaxy + 50 g Nelson Sauvin + 30 g Riwaka

Per Janish, prefer **survivable-compound hops** for the whirlpool: Citra, Mosaic, Idaho 7, Bravo, Ekuanot, Simcoe, Mount Hood. See [`../process/whirlpool.md`](../process/whirlpool.md).

## Fermentation

- **Pitch yeast at 18 °C / 64 °F** into oxygenated wort (8–12 ppm DO).
- **Yeast pitch:**
  - Liquid: 1.5–2 L starter from 1 vial/pack of London Ale III, Conan, or A24
  - Dry: 11–14 g of Verdant IPA (one and a half packs)
- **Days 1–2:** 18–19 °C, active fermentation begins.
- **Day 2–3 (~50–70% attenuation, gravity ~1.030–1.020):** Drop the **active-fermentation dry hop** under CO₂ purge.
  - **~90 g** of biotransformation-friendly hops
  - Example: 50 g Citra + 40 g Galaxy
- **Days 3–6:** Free-rise to 20–21 °C. Fermentation completes.
- **Day 6–7:** FG reached and stable for 2 days.
- **Day 7:** Crash to **13 °C / 55 °F**, drop spent yeast through bottom valve.

## Cold-side dry hop (Janish-recommended cool dry hop)

- **At 13 °C** drop the cold-side dry hop under CO₂ purge.
- **~90 g** of aromatic finishers.
- Example: 35 g Citra + 35 g Mosaic + 20 g Amarillo
- **Hold 3 days** at 13 °C.
- Optional: **once-daily gentle agitation** (CO₂ burp from bottom valve, or rock the fermenter).

After 3 days:

- Drop spent dry hops through bottom valve.
- Crash to **4 °C / 39 °F** for 1–2 days.

## Total hop bill

For a standard intensity NEIPA at this OG:

| Stage          | Grams | Rate    | Notes                               |
|----------------|-------|---------|--------------------------------------|
| Bittering (60 min) | 15  | ~0.6 g/L | Clean high-alpha hop                |
| Whirlpool (180 °F, 25 min) | 140 | 6.0 g/L | Survivable compounds + main aroma  |
| Active-ferm DH | 90    | 4.0 g/L | Biotransformation-active hops       |
| Cold-side DH (13 °C, 3 days) | 90 | 4.0 g/L | Aromatic finishers              |
| **Total**      | **335** | **~14 g/L** | Standard NEIPA intensity         |

### Heavy DIPA variant

Bump to 18–20 g/L total. Use **Cryo Hops®** for the cold-side to manage polyphenol load:

- Whirlpool: 8 g/L
- Active-ferm DH: 5 g/L
- Cold-side DH: 5–6 g/L (mostly Cryo)

### Soft sessionable variant

Drop to 8–10 g/L total. Skip the active-ferm DH. Lower OG to ~1.052.

## Packaging

- **Spunding:** install spunding valve at ~70% attenuation, set to **12 PSI** for ~2.5 vol carbonation at 4 °C.
- **Closed transfer to a sanitizer-purged keg** (see [`../process/packaging.md`](../process/packaging.md)).
- **Cold storage at 4 °C.**
- **Drink within 4–6 weeks**, ideally **2–4 weeks**.

## Total timeline

| Day  | Activity                                  |
|------|-------------------------------------------|
| 0    | Brew day. Mash, boil, whirlpool, cool, transfer, pitch. |
| 0    | Set up spunding valve target (set later). |
| 2    | Active-fermentation dry hop drop          |
| 7    | FG reached, crash to 13 °C, cold-side DH drop |
| 10   | Spent hops dropped, crash to 4 °C         |
| 11–12 | Closed transfer to keg                   |
| 13–17 | Conditioning at 4 °C (carbonation finishing) |
| 18+  | Drink                                     |

About **2.5 weeks** from brew day to first pour. **3 weeks for peak.**

## Variables to log per batch

- OG and FG (calculate apparent attenuation)
- pH at: mash, post-boil, post-acid, FG, in keg
- Whirlpool temp (verify with thermometer — your kettle thermometer may lie)
- Active-ferm DH gravity at drop (target 1.020–1.030)
- Time at each temp
- Hop variety, harvest year, supplier per addition
- Hop creep delta (gravity drop after cold-side DH)
- Sensory notes at: kegging, week 1, week 2, week 4

A spreadsheet across batches is the fastest way to learn what works in *your* system.

## When something's off — first-look diagnostics

- **Lacks aroma:** likely DO at packaging, or hops are old. Check both.
- **Cardboard / sherry:** DO. Almost always packaging-side.
- **Onion / garlic:** old Citra or Simcoe. Check harvest year.
- **Astringent / harsh:** too much hop polyphenol — try Cryo for cold-side, drop dry hop temp, or reduce total load.
- **Diacetyl (slick butter):** hop creep + insufficient yeast cleanup. Hold warmer 2 days, or accept it next batch.
- **Dropping bright (loss of haze):** over-flocculated yeast, or hop crash from sulfate. Switch yeast or recheck water.
- **Over-carbonated keg:** hop creep didn't finish before kegging. Wait longer next time.

See style failure-modes in [`../styles/neipa.md`](../styles/neipa.md) for more.

## Cross-references

- **[`../styles/neipa.md`](../styles/neipa.md)** — what you're aiming for
- **[`../hops/varieties.md`](../hops/varieties.md)** — pick your hops
- **[`../hops/dry-hopping.md`](../hops/dry-hopping.md)** — Janish synthesis on the dry hop strategy
- **[`../yeast-strains.md`](../yeast-strains.md)** — pick your yeast
- **[`../water.md`](../water.md)** — water profile details
- **[`../process/whirlpool.md`](../process/whirlpool.md)** — whirlpool details
- **[`../process/fermentation.md`](../process/fermentation.md)** — fermentation details
- **[`../process/packaging.md`](../process/packaging.md)** — closed-transfer playbook
- **[`single-hop-experiments.md`](single-hop-experiments.md)** — variant of this template for single-hop learning
