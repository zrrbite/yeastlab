# NEIPA — New England IPA

A hop-forward, low-bitterness, hazy, juicy IPA that tastes like fresh tropical fruit and citrus instead of pine and grapefruit. Born in Vermont in the early 2010s (The Alchemist's Heady Topper, Hill Farmstead, Tree House, Trillium), it became the dominant American craft beer style in the late 2010s and the most-cloned style in homebrewing.

## Defining traits

- **Hazy, opaque, often glowing.** Not a flaw — the haze comes from suspended yeast, polyphenol-protein complexes, and hop polyphenols. It's structural to the style.
- **Soft, pillowy mouthfeel.** Wheat and oats in the grist, chloride-forward water, often a touch of lactose (modern interpretations vary on this).
- **Hop aroma forward, low-to-moderate bitterness.** Dominated by aromatic hop oils — tropical fruit, citrus, stone fruit — not bittering compounds. IBUs typically 30–55, but perceived bitterness lower.
- **Massive late and dry hopping.** Whirlpool/hopstand additions and **multiple dry hop charges** during and after fermentation. Total hopping rate is often **5–10× a traditional West Coast IPA**.
- **Biotransformation-driven flavor.** Yeast enzymatically modifies hop oils during active fermentation — geraniol → β-citronellol, glycoside cleavage liberates bound thiols. The "juicy" character is partly a yeast-hop conversation, not just hop oils.
- **Drink fresh.** A NEIPA peaks at **2–4 weeks** post-package. By 8–12 weeks it's a different beer, and rarely in a good way.

## Vital stats

| Parameter            | Typical range          |
|----------------------|------------------------|
| OG                   | 1.060–1.075            |
| FG                   | 1.012–1.018            |
| ABV                  | 6.0–8.5% (DIPA: 8–10%) |
| IBU (calculated)     | 30–55                  |
| IBU (perceived)      | Low–medium             |
| Color (SRM)          | 3–7 (pale gold to pale orange) |
| Mash pH              | 5.2–5.4 (5.4 typical)  |
| Final beer pH        | 4.2–4.5                |

## Grain bill — the soft pillow

NEIPA grist is intentionally engineered for **mouthfeel and protein-haze potential**.

| Grain                  | %       | Why                                                    |
|------------------------|---------|--------------------------------------------------------|
| 2-row pale malt or pilsner | 60–70% | Base. Pilsner gives a softer, slightly more delicate beer. |
| Flaked oats            | 10–20%  | β-glucans and proteins → mouthfeel and haze            |
| Flaked or malted wheat | 10–20%  | Proteins for haze, lighter mouthfeel than oats         |
| Carapils / dextrin malt | 0–5%   | Optional — extra body                                  |
| Honey malt / Munich    | 0–5%    | Optional — touch of sweetness, careful: too much fights hops |

Total non-base adjuncts: **30–40% is typical**. This is a *very* high adjunct ratio compared to most styles.

> **Avoid:** crystal malts > 60L, roasted malts, anything that adds caramel or color depth. They'll fight the hop character and dull the perceived freshness.

## Hop bill — what makes it juicy

The interesting question isn't what bittering hops to use — it's how to spend your aroma hop budget across the whirlpool and dry-hop windows. NEIPA recipes typically use **3–5 hop varieties** in combination, leaning into varieties that complement each other across **citrus, tropical, and stone fruit** descriptors.

See [`../hops/varieties.md`](../hops/varieties.md) for a hop-by-hop reference and [`../hops/dry-hopping.md`](../hops/dry-hopping.md) for how to actually use them.

Classic NEIPA hop combinations:

- **Citra + Mosaic + Galaxy** — the foundational triplet. Stone fruit + dank + passionfruit.
- **Citra + Nelson Sauvin + Riwaka** — bright, vinous, gooseberry, grapefruit.
- **Mosaic + Strata + Sabro** — dank, pineapple, coconut-cream.
- **Citra + El Dorado + Idaho 7** — candy-like tropical with peach and resin.
- **Galaxy + Nelson + Vic Secret** — Antipodean tropical bomb.

Bittering: a small clean addition (5–15 IBUs) at 60 min from a neutral high-alpha hop (Magnum, Warrior, CTZ for bittering). Most of the IBUs will come from whirlpool isomerization anyway.

## Water — chloride forward

The classic NEIPA water profile is **soft and chloride-forward**, the opposite of a West Coast IPA's sulfate-forward profile.

| Ion                | Target (ppm)            |
|--------------------|--------------------------|
| Calcium (Ca²⁺)     | 80–110                   |
| Magnesium (Mg²⁺)   | 5–15                     |
| Sodium (Na⁺)       | 10–30                    |
| Chloride (Cl⁻)     | 130–180 (sometimes 200+) |
| Sulfate (SO₄²⁻)    | 50–90                    |
| **Cl : SO₄ ratio** | **~2:1 (sometimes 3:1)** |

The chloride pushes mouthfeel toward soft and round; sulfate is kept low because it sharpens and dries out hop bitterness — exactly what you don't want in a NEIPA. See [`../water.md`](../water.md).

## Yeast — the biotransformation engine

Pick a yeast that:

- **Throws plenty of esters** (juicy fruit complement to hops)
- **Has high biotransformation activity** (cleaves glycosides, modifies geraniol)
- **Stays in suspension** (low-to-medium flocculation = haze-friendly)
- **Tolerates the heavy dry-hop load** without total cleanup

Top picks:

- **London Ale III** (Wyeast 1318 / WLP066 / Imperial A38 Juice) — the original NEIPA workhorse. Soft, fruity, hazy.
- **Vermont Ale / "Conan"** (Imperial A04 Barbarian / GY054) — peach esters, the yeast behind Heady Topper and Focal Banger.
- **WLP095 Burlington Ale** — close cousin to Conan, brewery-traceable to The Alchemist.
- **Lallemand Verdant IPA** — dry equivalent, very approachable, modern favorite.
- **Kveik (Voss, Hornindal, Espe)** — fast, warm-fermenting, citrus/tropical esters of their own. Sometimes called the "modern NEIPA shortcut" — under-rated for hop-forward beers.

See [`../yeast-strains.md`](../yeast-strains.md).

## Process — the DO obsession

This is the part that separates good NEIPAs from haze-gimmicks.

NEIPAs **oxidize fast**. Hop polyphenols, hop oils, and the haze-stabilizing compounds are all sensitive to dissolved oxygen. A NEIPA brewed by a competent brewer with sloppy DO control at packaging will go from juicy + bright to muddy + cardboard in 2–3 weeks. A NEIPA brewed by the same brewer with disciplined low-DO transfer can stay great for 8–10 weeks.

**The pipeline:**

1. **Mash low-ish.** 5.2–5.4 mash pH for soft profile and good hop-character preservation.
2. **Bittering charge at 60 min.** Small, clean — 5–15 IBUs.
3. **Whirlpool / hopstand at ~170 °F (77 °C).** Most of your aroma load. Below 80 °C, isomerization slows dramatically — you get the oils without much added bitterness. See [`../process/whirlpool.md`](../process/whirlpool.md).
4. **Cool fast, oxygenate wort, pitch a healthy yeast load** at 18–20 °C.
5. **Free rise during fermentation** to 20–22 °C for ester development.
6. **Active-fermentation dry hop** when gravity is at ~50–70% attenuation (typically 24–48 hr in). This is the **biotransformation window** — yeast enzymes convert hop precursors and bound aromatics. Janish goes deep on this. See [`../hops/dry-hopping.md`](../hops/dry-hopping.md).
7. **Post-fermentation (or cold-side) dry hop** at FG. Lower hop-creep risk, brighter aroma. Optional but most NEIPAs use both.
8. **Diacetyl rest** if needed (usually not for NEIPA strains, but check).
9. **Spund or carbonate naturally** under pressure to avoid CO₂ stripping aromatics.
10. **Cold-crash and closed-transfer to keg under CO₂.** Never expose finished beer to air. See [`../process/packaging.md`](../process/packaging.md).
11. **Drink within 4–6 weeks.** Best at 2–4 weeks.

## What "good" looks and tastes like

**Visual:** opaque, pale-orange to pale-gold, glowing under light. The haze should be **stable** — not flocculating in the glass and not muddy/sedimenty. A well-made NEIPA's haze is silky and uniform.

**Aroma:** **forward, juicy, fresh.** You should smell it across the room. Pineapple, mango, papaya, peach, tangerine, white grape, dank pine resin (depending on hop selection). Should *not* smell like onion, garlic, or cardboard — those are warning signs (over-oxidized hops, hop creep, oxidation respectively).

**Flavor:** matches the aroma — fruit-forward, with a soft round mouthfeel and a finish that's clean but **not sharp**. Bitterness should be there but in the background. Should *not* taste astringent (over-extraction from too much dry hop or too long contact), grassy (over-aged dry hops), or sour-twang (oxidation, infection).

**Mouthfeel:** **soft, pillowy, full**. Not syrupy. Not thin. The chloride-forward water and the oat/wheat grist combine to make this signature. A thin NEIPA is usually a recipe error (not enough adjuncts) or a fermentation error (over-attenuation from hop creep).

**Finish:** clean, with lingering hop fruit. Dry but not arid. No diacetyl (butter), no acetaldehyde (green apple), no DMS (cooked corn — common in pilsner-base recipes if you skipped the long boil).

## Common failure modes

| Symptom                              | Likely cause                                                  |
|--------------------------------------|---------------------------------------------------------------|
| Cardboard, paper, sherry             | Oxidation. Almost always at packaging or transfer.            |
| Onion, garlic, sweat                 | Old/degraded hops, especially Citra or Simcoe past their date |
| Astringent, harsh tannin             | Too much dry hop, too long, too warm. Or polyphenol overload from total hop load. |
| Beer attenuated past your target     | Hop creep. Diastatic enzymes from dry hops continue fermentation. |
| Mud-thick, sediment-heavy haze       | Over-flocculated yeast in suspension, or polyphenol crash from too much sulfate |
| Vegetal, grassy                      | Old dry hops, or contact too long (>5 days post-FG)           |
| Thin, watery body                    | Not enough oats/wheat, or hop creep ate the dextrins          |
| Diacetyl (slick, butter)             | Hop creep + insufficient yeast cleanup; raise to 22 °C for 2 days |
| Bright, clean, but boring            | Whirlpool too hot (>180 °F isomerized too much), or single-hop gone wrong |

## The freshness clock

A core mental model for NEIPA is that **the beer is decaying from the moment it's finished fermenting**. Your job as a brewer is to slow the decay clock. Specifically:

- **Hop oils volatilize.** Even sealed, hop aroma compounds slowly degrade. Cold storage helps a lot.
- **Hop polyphenols oxidize.** This is the cardboard/sherry off-flavor pathway. DO is the enemy.
- **The haze can crash.** Over-aged NEIPAs sometimes "drop bright" — the protein-polyphenol haze flocculates out. Visually you've lost half the style.

This is why pros target **2 weeks from grain to glass** and homebrewers should target **3 weeks** at most. It's also why kegging (under pressure, cold) is dramatically better than bottling for NEIPA.

## Sub-styles to know

- **Hazy IPA / Modern IPA** — basically NEIPA after it spread west. Same playbook.
- **DIPA / TIPA / Hazy DIPA** — bigger ABV (8–10%), proportionally bigger hop loads. Same techniques, more of everything.
- **Cold IPA / India Pale Lager** — the West Coast pushback against NEIPA. *Not* hazy, very different style.
- **"Smoothie" or fruit-loaded hazy** — NEIPA + pureed fruit. Often with lactose. Polarizing.
- **Brut IPA** — opposite of NEIPA: very dry, no haze, glycoamylase added. Brief mid-2010s fad.

## Cross-references

- [`../hops/varieties.md`](../hops/varieties.md) — hop-by-hop reference
- [`../hops/dry-hopping.md`](../hops/dry-hopping.md) — Janish synthesis on dry hopping
- [`../water.md`](../water.md) — soft, chloride-forward water profile
- [`../yeast-strains.md`](../yeast-strains.md) — strain selection for biotransformation
- [`../process/fermentation.md`](../process/fermentation.md) — fermentation schedule and biotransformation timing
- [`../process/packaging.md`](../process/packaging.md) — low-DO closed transfers and spunding
- [`../recipes/neipa-template.md`](../recipes/neipa-template.md) — base recipe to plug hops into
