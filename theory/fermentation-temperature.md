# Fermentation temperature — playbook across crafts

Temperature is the **fastest dial** you can turn on any fermentation. The same yeast at 18 °C and 28 °C produces different beer, bread, and even different coffee. This file maps temperature ranges across all the crafts in this repo, showing **what each temperature does** to fermentation chemistry and final product.

## The universal principle

For all yeast and LAB:

- **Warmer = faster** fermentation — yeast metabolism speeds up
- **Warmer = more esters** — yeast produces more aromatic compounds at higher temps
- **Warmer = more fusel alcohols** — at very high temps, harsh "hot alcohol" character
- **Cold = slower, cleaner** — less ester production, sharper acid profile (LAB favored)
- **Cold = better preservation** — once fermentation finishes, cold extends quality

Each craft has its **target window** — the temperature band where the specific yeast/microbe behaves the way the craft wants.

## The temperature map across crafts

```
0 °C ─┬─ Lagering / cold conditioning (beer)
      │   Cold-side dry hop NEIPA (13 °C)
      │   Wine cold stabilization
 10 °C─┤── Lager fermentation (8–14 °C)
      │   Cold IPA fermentation (12–15 °C)
      │   Wine fermentation (varies)
 20 °C─┤── Standard ale fermentation (18–22 °C)
      │   Modern WCIPA fermentation
      │   Sourdough cold rest enzymes (bench)
      │   Coffee anaerobic processing (some)
 25 °C─┤── Active ale free-rise
      │   Saison fermentation (warm)
      │   Sourdough room temp bulk
      │   Coffee fermentation (typical)
 30 °C─┤── Saison free-rise (28–32 °C)
      │   Kveik fermentation (28–40 °C)
      │   Bread bulk (warm kitchen)
      │   Brett fermentation (varies; warmer better)
 40 °C─┤── Kveik max
      │   Bread proofing (sometimes)
      │
 50 °C─┤
      │   Coffee mashing analog (none — different chemistry)
      │
 60 °C─┴── Bread proofing approaches gluten denaturation
      │
 65 °C─── BEER MASH (β-amylase)
 67 °C─── BEER MASH (α-amylase)
 100 °C── Boiling (denaturation)
```

## Detailed temperature ranges by craft

### Sourdough

| Phase                      | Temperature        | What's happening                              |
|----------------------------|--------------------|------------------------------------------------|
| Starter feeding (active)   | 22–28 °C           | Active LAB + yeast; warmer = faster              |
| Starter cold storage       | 4 °C               | Slows yeast 10×; enzymes still active            |
| Bulk fermentation (DEAM)   | 22–24 °C           | Optimal yeast + LAB balance                     |
| Cold rest (early, primary) | 4 °C               | Amylase frees sugar; protease nearly inactive   |
| Cold proof (late, before bake) | 4 °C            | Slows fermentation; develops surface character   |
| Oven (bake)                | 200–245 °C         | Fermentation stops; Maillard / caramelization    |

**Key principle:** sourdough exploits the fact that **enzymes (amylase, protease) work at fridge temperatures while yeast is dormant.** Most other crafts don't have this trick.

### Beer — ale

| Phase                      | Temperature        | What's happening                              |
|----------------------------|--------------------|------------------------------------------------|
| Mash                       | 64–67 °C           | Enzymatic conversion of starch to sugar         |
| Boil                       | 100 °C             | Sterilize, isomerize hops, denature proteins    |
| Whirlpool                  | 80–85 °C (NEIPA Janish) | Hop oil extraction without harsh isomerization |
| Pitch                      | 18 °C              | Yeast lag phase                                 |
| Active fermentation        | 18–22 °C           | Most ester / alcohol production happens here    |
| Active-ferm dry hop (NEIPA) | 19–21 °C          | Biotransformation                                |
| Free-rise                  | 20–22 °C           | Fermentation finish                              |
| Cold-side dry hop          | **13 °C** (Janish) | Aroma extraction without hydrocarbon over-extraction |
| Cold conditioning          | 0–4 °C             | Yeast drop, clarity, flavor integration         |

### Beer — lager

| Phase                      | Temperature        | What's happening                              |
|----------------------------|--------------------|------------------------------------------------|
| Pitch                      | 9–10 °C            | Cold pitch for clean fermentation               |
| Active fermentation        | 10–14 °C           | Slow, clean lager fermentation                  |
| Diacetyl rest              | 18–20 °C           | Yeast cleanup of diacetyl                       |
| Lagering                   | 0–2 °C             | The long sleep; weeks to months                 |

### Beer — saison

| Phase                      | Temperature        | What's happening                              |
|----------------------------|--------------------|------------------------------------------------|
| Pitch                      | 22 °C              | Warm pitch for saison yeast                     |
| Free-rise                  | **28–32 °C**       | Saison yeast loves heat; produces character     |
| Final                      | 22 °C              | Cool down only at the very end                  |

### Coffee — processing

| Phase                      | Temperature        | What's happening                              |
|----------------------------|--------------------|------------------------------------------------|
| Cherry harvest             | Ambient            | Just-picked cherries                            |
| Washed fermentation        | 18–28 °C ambient    | LAB + yeast in mucilage; 12–48h                |
| Natural / dry fermentation | Ambient            | Continuous, weeks-long fermentation in cherry   |
| Anaerobic (controlled)     | 18–25 °C           | Sealed vessel; can be temp-controlled            |
| Drying                     | 25–35 °C ambient    | Slow dehydration; fermentation continues slowly |
| Roasting                   | 200–250 °C         | All microbial activity stops; chemistry changes |

### Coffee — brewing

| Phase                      | Temperature        | What's happening                              |
|----------------------------|--------------------|------------------------------------------------|
| Boil for brewing           | 90–96 °C           | Optimal coffee extraction temp                  |
| Cold brew                  | 4–22 °C            | 12–24 hour slow extraction                      |
| Cupping (SCAA)             | ~95 °C → cool      | Standardized evaluation temp                    |

## What temperature does to esters

Yeast produces **more esters at higher temperatures**. This is universal:

- **Bread at 18 °C:** mild, slightly fruity
- **Bread at 28 °C:** more aromatic, more banana/clove (esters from S. cerevisiae)
- **Beer at 18 °C:** clean lager territory
- **Beer at 22 °C:** mild ester production
- **Beer at 28 °C:** banana/clove (Belgian / saison territory)
- **Beer at 35 °C+:** hot, fusel alcohols (off-flavor)

Each yeast strain has a **window where it produces wanted esters without unwanted ones.** Saison yeast at 22 °C makes a different beer than at 30 °C; both are fine; choose based on goal.

## What temperature does to acids

LAB produces **more acid at warmer temperatures** — but the **type** of acid shifts:

- **Warm + LAB:** more lactic acid (smooth, creamy)
- **Cool + LAB:** more acetic acid (sharp, vinegary)

This is why **a sourdough fermented warm tastes more like yogurt** while a **sourdough fermented cool (in fridge) tastes more like vinegar**.

In coffee processing:

- **Warm fermentation (28+ °C):** more lactic, faster overall fermentation
- **Cool fermentation (15–18 °C):** more acetic, slower, more complex

## What temperature does to enzymes

Enzymes (amylase, protease, β-glucosidase) have **optimal temperature windows** independent of yeast activity:

- **α-amylase optimum:** ~70 °C (during beer mash; during bread bake)
- **β-amylase optimum:** ~63–65 °C
- **β-glucosidase (yeast-derived):** ~30–35 °C — biotransformation in NEIPA happens at fermentation temp
- **Protease optimum:** varies, generally 40–55 °C for malt protease

In sourdough, enzymes are **active even at fridge temperatures** — the foundation of DEAM. Amylase doesn't need heat; it just slows down. Yeast slows MORE than amylase, so the cold rest exploits the difference.

## Cold storage is universal

Across all crafts, **once fermentation is "done," cold storage is the preservation strategy**:

- **Sourdough:** baked bread → counter (3 days) → frozen (months)
- **Beer:** kegged beer → 2–4 °C cold storage → drink within weeks (NEIPA) to months (lager)
- **Coffee:** roasted beans → cool, dry, dark storage → 4–6 weeks for peak

The **freshness clock** for each craft:

- **NEIPA:** peak at 2–4 weeks
- **WCIPA:** peak at 2–6 weeks
- **Cold IPA:** peak at 4–10 weeks
- **Lager:** peak at 1–3 months
- **Sour beer:** improves over months/years
- **Bread:** peak at hours, freshness 1–3 days
- **Coffee (roasted):** peak at 1–2 weeks post-roast, fading by 4–6 weeks

## Chamber-controlled cross-craft brewing

If you have a **fermentation chamber** (see [`../beer/process/temperature-control.md`](../beer/process/temperature-control.md)), you can use it across crafts:

- **Beer fermentation** at any specific temperature for any style
- **Bread bulk fermentation** at a specific temperature (usually 22–24 °C)
- **Bread proofing** in the chamber when your kitchen is cold (set to 26–28 °C)
- **Cold-fermenting bread doughs** for DEAM-style cold rests at 4 °C
- **Yogurt / kimchi making** at 35–40 °C
- **Coffee cherry anaerobic fermentation** at 22 °C for hobby-scale processing

A single chamber unlocks temperature control across multiple crafts. Worth thinking about as a **multi-purpose tool**.

## Cross-references

- **[`fermentation.md`](fermentation.md)** — the underlying biology
- **[`enzymes.md`](enzymes.md)** — temperature optimums for amylase, protease
- **[`yeast-strains.md`](yeast-strains.md)** — strain-specific temperature ranges
- **[`flavor-chemistry.md`](flavor-chemistry.md)** — esters, lactic vs acetic, all temperature-driven
- **[`../beer/process/temperature-control.md`](../beer/process/temperature-control.md)** — fermentation chamber operations
- **[`../sourdough/methods/double-enzymatic-activation.md`](../sourdough/methods/double-enzymatic-activation.md)** — DEAM exploits the temperature differential between yeast and enzymes
