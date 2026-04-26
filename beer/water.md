# Water — NEIPA profile

For a NEIPA, water chemistry is **chloride-forward and soft**, the opposite of a West Coast IPA's sulfate-forward profile. The water is one of the three legs of the hop / yeast / water triangle (see [`hops/README.md`](hops/README.md)).

## NEIPA target profile

| Ion                | Target (ppm)            | Role                                              |
|--------------------|--------------------------|---------------------------------------------------|
| Calcium (Ca²⁺)     | 80–110                   | Yeast health, mash pH, gluten-equivalent in beer (protein/polyphenol coagulation in boil) |
| Magnesium (Mg²⁺)   | 5–15                     | Yeast enzyme cofactor; over ~30 ppm tastes metallic |
| Sodium (Na⁺)       | 10–30                    | Mouthfeel roundness; over 100 ppm tastes salty    |
| Chloride (Cl⁻)     | 130–180 (sometimes 200+) | The headline ion for NEIPA — softness, mouthfeel  |
| Sulfate (SO₄²⁻)    | 50–90                    | Hop bitterness sharpness — keep low for NEIPA     |
| **Cl : SO₄ ratio** | **~2:1 (sometimes 3:1)** | The defining NEIPA characteristic                 |

Total hardness (Ca + Mg) target: **~150–200 ppm CaCO₃ equivalent**. Lower than a West Coast IPA, higher than a German pilsner.

## Why chloride-forward

**Chloride** in the **130–200 ppm range** does several things to a NEIPA:

- **Roundness and softness in mouthfeel.** Chloride pushes flavor perception toward "fuller" and "smoother" — exactly the NEIPA character.
- **Slight sweetness perception.** Chloride amplifies malt sweetness without actually adding sugar.
- **Doesn't sharpen hop bitterness** the way sulfate does. The hop character feels juicy, not piney/sharp.
- **Compatible with high adjunct (oats, wheat) recipes** — the soft mouthfeel from chloride harmonizes with the soft mouthfeel from β-glucans.

**Sulfate** in NEIPA territory should be **low (50–90 ppm)**. Higher sulfate would push the hop bitterness toward "drier, sharper, more piney" — not what the style wants. (This is why a West Coast IPA targets the inverse: 200–300 ppm sulfate, 50–80 ppm chloride.)

The **Cl : SO₄ ratio** is the headline number. NEIPA targets **roughly 2 : 1**, sometimes pushed to **3 : 1** for very soft examples. West Coast IPA does the opposite (~1 : 4).

## Why low total hardness

Above ~250 ppm total hardness:

- Mash pH gets harder to control (more buffering)
- Hop bitterness can taste mineral / metallic
- Mouthfeel can feel "heavy" rather than soft

NEIPA targets **soft to moderately-soft** water. Pilsen (very soft, ~25 ppm hardness) is too soft; Burton-on-Trent (~700 ppm hardness) is way too hard. Aim for the **150–200 ppm CaCO₃** band.

## Mash pH

Target mash pH: **5.2–5.4** (5.4 is common for NEIPA).

A slightly higher mash pH (toward 5.4) helps:

- More **β-amylase activity** → more fermentable sugars → more attenuation (good for hop creep tolerance)
- Slightly softer perceived character
- Better extraction of polyphenols **into the wort** (where they're somewhat managed during boil), reducing extraction in the dry hop later

A slightly lower mash pH (toward 5.2) helps:

- Sharper hop character (counter to the soft NEIPA goal)
- Better protein coagulation
- More acidic wort → faster yeast acidification → less window for off-flavors

For NEIPA: **5.4 is the comfortable choice.** Use phosphoric or lactic acid in the mash if needed to bring water with elevated alkalinity into range.

## Final beer pH and dry hop pH rise

Per Janish (2021) and Lafontaine & Shellhammer (2018), heavy dry hopping raises beer pH by **~0.036 per 3 lb/bbl** of hops. At standard NEIPA hop loads, this can push final beer pH from a healthy 4.4 to **4.7–5.0**, which:

- Tastes more bitter than the IBU implies (Meilgaard & Trolle 1957)
- Hurts foam retention
- Can taste flabby / lacks definition

**Sapwood Cellars approach** (per Janish 2021):

- Mash pH: **5.2–5.3**
- Phosphoric acid added to kettle as collected → **post-boil pH 4.8–4.9**
- Optional: post-fermentation acid to **4.2–4.4**

For homebrewers: phosphoric acid (10% food-grade) is cheap and easy to dose. Add it to the kettle during boil collection if your post-boil pH is creeping over 5.0. For post-fermentation, you can add phosphoric to taste at packaging — go slow, taste as you go.

## Building NEIPA water from RO/distilled

If you start with **reverse osmosis (RO) or distilled water**, you can build a NEIPA water profile from scratch. This is the cleanest, most predictable approach.

For a 30 L batch (5 gal mash + sparge):

| Salt                          | Add to mash | Add to kettle | Total grams | Adds (per L)              |
|-------------------------------|-------------|---------------|-------------|----------------------------|
| Calcium chloride (CaCl₂·2H₂O) | 6 g         | 4 g           | 10 g        | ~110 ppm Cl, ~60 ppm Ca   |
| Calcium sulfate (gypsum)      | 2 g         | 1 g           | 3 g         | ~50 ppm SO₄, ~25 ppm Ca   |
| Sodium chloride (table salt)  | 1 g         | 0.5 g         | 1.5 g       | ~20 ppm Na, ~30 ppm Cl    |
| Magnesium sulfate (Epsom)     | 0.5 g       | —             | 0.5 g       | ~5 ppm Mg, ~10 ppm SO₄    |

This produces approximately:

- Ca: ~85 ppm
- Mg: ~5 ppm
- Na: ~20 ppm
- Cl: ~140 ppm
- SO₄: ~60 ppm
- **Cl : SO₄ ≈ 2.3 : 1**

Adjust to taste. If you want a softer profile, drop the gypsum. If you want more drying finish, raise gypsum slightly. **Don't go above 100 ppm SO₄** for a NEIPA.

## Building from tap water

If your tap water is moderate-hardness, low-chlorine, and you have a water report, you can adjust *up* with calcium chloride and gypsum without going through RO.

Steps:

1. **Get a water report** — Ward Labs or your local utility's annual report. You need: Ca, Mg, Na, Cl, SO₄, HCO₃, pH, alkalinity.
2. **Plug into a water calculator** (Bru'n Water, Brewer's Friend Water Tool, BeerSmith).
3. **Aim for the targets above.**
4. **Treat for chlorine/chloramine first** — campden tablets (potassium metabisulfite), 1 tablet per 20 gal, dissolved in water and added before brewing. Skipping this step can produce **chlorophenols** — band-aid / medicinal off-flavors that will ruin a beer.

If your tap water is very hard or has high alkalinity (HCO₃ > 100 ppm), consider:

- **Diluting with RO water** (50/50 cuts most issues)
- **Acidifying mash water** with lactic or phosphoric acid to drop alkalinity

## What about water from the keg-line?

Carbonated water has dissolved CO₂ → carbonic acid → slightly acidic. Doesn't matter for brewing water, but it's why beer doesn't taste "watery" the way still water at the same temperature does.

## A cautionary note: don't over-engineer

Water chemistry is a real lever, but it's the **third-most-important variable** in NEIPA quality after hop freshness and DO control. A perfect water profile can't save a NEIPA brewed with old hops or oxidized in transfer. Get the recipe and process right first; **then** dial in the water.

The "I made a perfect NEIPA water profile and the beer is still mediocre" problem is almost always: hops or DO. Look there first.

## Cross-references

- **[`../theory/water-minerals.md`](../theory/water-minerals.md)** — the chemistry of brewing salts (also applies to bread)
- **[`hops/dry-hopping.md`](hops/dry-hopping.md)** — how dry hopping interacts with beer pH
- **[`process/whirlpool.md`](process/whirlpool.md)** — boil/whirlpool pH considerations
- **[`recipes/neipa-template.md`](recipes/neipa-template.md)** — water salts in the recipe template
