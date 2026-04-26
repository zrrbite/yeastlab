# Coffee roasting on the Aillio Bullet R2

The Bullet R2 is the **first commercial induction-heated drum coffee roaster** — a 1 kg-capacity small-batch machine that's become the dominant home and small-cafe roaster globally since its release. This file is **Bullet-specific**: how the machine works, how to think about roast profiles on induction heating, and recipes / approaches for common bean styles.

If you don't have a Bullet, much of this still applies in spirit (drum roasting is drum roasting), but the specific numbers, charge temperatures, and software notes are Bullet-only.

## What makes the Bullet different

Most home / small-cafe coffee roasters use **gas burners** (commercial sample roasters, larger production roasters) or **electric resistance heating** (most home roasters under $1500 — Behmor, Hottop, etc.).

The Bullet uses **electromagnetic induction**:

- **Coils underneath the drum** generate an alternating magnetic field
- The **steel drum itself becomes the heating element** — induced eddy currents heat the metal directly
- Beans are heated by **drum contact + airflow** (no flame, no IR lamp, no resistance coil)

What this means in practice:

- **Extremely energy-efficient** — 100% of the input power goes into the drum
- **Very precise heat control** — induction responds to power changes in seconds
- **Clean** — no combustion byproducts, no electric coil dust
- **Even heating** — the entire drum surface heats uniformly
- **Quiet** — no fan/burner roar, just the bean tumble sound
- **Plug-and-roast** — 220V wall outlet (most regions); no gas line or special venting

The induction approach was novel when the Bullet R1 launched (around 2015); the R2 (released 2022) refined the design with improved drum, control, and software integration.

## Bullet specs and controls

### Hardware

- **Capacity:** 1 kg max batch; ~500 g sweet spot for most users; 700–800 g for production
- **Drum material:** steel (induction-compatible)
- **Cooling tray:** built-in, with separate fan
- **Trier (sample sniffer):** for pulling samples mid-roast
- **Voltage:** typically 220V (single-phase); some regions get 110V variant with reduced power

### Controls (front panel)

- **Power (P0–P9):** drum heat output, 0% to 100%
- **Drum speed (D0–D9):** RPM control of the drum rotation; affects bean tumble and contact time
- **Fan speed (F0–F4):** airflow through the drum, affects convection heating and chaff/smoke removal
- **Cool / Cancel / Charge buttons** for batch management

### Sensors

- **BT (Bean Temperature):** thermocouple probe in the drum, measures bean mass temp
- **IBTS (Infrared Bean Temperature Sensor):** infrared sensor reading bean *surface* temp through a small port. Faster response than BT.
- **ET (Exhaust Temperature):** measures air leaving the drum

These three readings together give you a complete picture of what's happening:

- **BT** is your primary roast curve
- **IBTS** anticipates BT changes (surface heats first, then mass)
- **ET** tells you about the heat in the air going through

### Software

- **RoasTime** (desktop app, Mac/Windows/Linux) — primary interface, displays curves, captures profiles, replays them
- **Roast.world** (web platform) — community profile sharing, roast logs, social
- **RoasterDude** (mobile-friendly alternative) — third-party but well-supported

You roast with **at least RoasTime running** to see your curves in real time. Roasting blind on the Bullet is technically possible but throws away most of the machine's value.

## Understanding roast profiles

A **roast profile** is the time-temperature curve of a roast. The standard view:

```
Temp (°C)
 220 ┤                                    ╭─── 2nd crack zone
 210 ┤                              ╭─────╯
 200 ┤                       ╭──────╯  ←── First Crack (FC)
 190 ┤               ╭───────╯
 180 ┤        ╭──────╯  ←── browning starts
 170 ┤    ╭───╯
 160 ┤  ╭─╯
 150 ┤ ╭╯
 140 ┤╭╯  ←── turning point
 130 ┤│   (TP, ~1:30 in)
 120 ┤│
 110 ┤│
 100 ┤╰── charge (drop beans into hot drum)
       └────────────────────────────────────
         0   2   4   6   8   10  12  14  Time (min)
```

### Key milestones

- **Charge:** dropping beans into the preheated drum. Charge temp typically **180–220 °C** depending on style.
- **Turning point (TP):** the lowest BT reading, when bean mass equals drum heat input. ~1:30 in. Critical reference point.
- **Yellowing:** beans transition from green to yellow (~150 °C). Drying phase ending.
- **Browning / Maillard:** beans turn brown (~165 °C+). Aromatic development phase.
- **First Crack (FC):** audible "popping" as moisture inside beans flashes to steam, breaking the cell walls. ~196–202 °C. **The most important roast milestone.**
- **Development phase:** the time between FC and drop. Determines acidity-vs-body balance.
- **Second Crack (2C):** smaller, faster cracks at ~225 °C+. Beans are getting dark. Most filter coffees are dropped before 2C.

### Rate of Rise (RoR)

The **rate at which BT is increasing** at any moment (°C/min). Crucial roast metric.

Healthy RoR shape:

- High at start (15+ °C/min after TP)
- Gradually declining throughout
- **No flick or stall** through FC (a steady decline is the goal)
- **Final RoR at drop:** 4–8 °C/min

If RoR **flicks up** at FC (sudden spike): "underdeveloped" risk → dark, papery, sour coffee
If RoR **stalls** before FC (drops to near zero): "baked" coffee → flat, papery, sweetness lost

## A reference Bullet profile — light-medium filter roast

For **500 g of green coffee**, light-medium filter roast (think Ethiopian, Kenyan, modern washed):

| Time   | BT     | RoR    | Settings (P, D, F)              | Notes                                  |
|--------|--------|--------|----------------------------------|----------------------------------------|
| 0:00   | 200 °C | —      | Charge 500g, P9, D5, F1          | Max heat, max drum, low fan            |
| 1:30   | 105 °C (TP) | (negative, then climbing) | Drop to P7 at TP            | Heat drops as beans absorb energy     |
| 2:30   | 130 °C | 14 °C/min | P7, D5, F2                    | Increase fan slightly                  |
| 4:00   | 150 °C (yellow) | 10 °C/min | P5, F3                  | Browning starting; reduce heat         |
| 6:00   | 175 °C | 8 °C/min | P4, F3                         | Maillard development                   |
| 8:00   | 195 °C | 7 °C/min | P3, F4                         | Approaching FC                         |
| 8:30   | 200 °C (FC) | 6 °C/min | P2 at FC                  | Reduce heat at FC for clean development|
| 9:45   | 207 °C | 5 °C/min | P2, F4                         | Development phase                      |
| 10:15  | 210 °C | drop! | Cool                              | Drop into cooling tray                 |

**Total roast time: 10:15** • **Development time: 1:45** (17% of total) • **Drop temp: 210 °C**

## Profile principles

### "Drying phase" (charge → yellow, ~3–4 min)

- Beans absorb heat, lose moisture
- Heat input should be high to get the beans up to temp efficiently
- Want this phase **3–4 minutes** for 500g; 4–5 min for 800g
- **Too long → baked / flat coffee**

### "Browning phase" (yellow → start of FC, ~3–4 min)

- Maillard reactions happen here
- Aromatic precursors form
- Want gradual heat reduction; smooth declining RoR
- **Too fast → underdeveloped sourness**
- **Too slow → muted, baked, flat**

### "Development phase" (FC → drop, 1:30–2:30)

- Determines the **balance between acidity (low devo time) and body / sweetness (longer devo time)**
- Modern light filter: **15–20% of total roast** in development
- Modern espresso: **20–25% of total roast**
- Dark roast: 30%+

## Roast levels — guide

### Light filter (Nordic / Scandinavian style)

- **Drop temp:** 200–205 °C
- **Drop just at or shortly after FC**
- **Development time:** ~1:30
- Total roast time: ~9–11 min
- **Beans:** light brown, no oil on surface
- **Cup:** maximum acidity, complex aromatics, lighter body, "true to the bean"

### Light-medium (modern specialty filter — most third-wave coffee)

- **Drop temp:** 207–212 °C
- **Drop ~1:30–2:00 after FC**
- **Development time:** 1:30–2:00
- Total roast time: ~10–12 min
- **Beans:** medium brown, no oil
- **Cup:** balanced acidity and sweetness, full aromatic complexity, medium body

### Medium (American / older specialty)

- **Drop temp:** 213–218 °C
- **Drop 2:00–2:30 after FC**
- **Development time:** 2:00–2:30
- Total roast time: ~11–13 min
- **Beans:** medium-dark brown, faint oil starting on surface
- **Cup:** less acidity, more chocolate / nut character, fuller body

### Medium-dark (espresso traditional)

- **Drop temp:** 218–222 °C, before / at start of 2nd crack
- **Development time:** 2:30–3:00
- Total roast time: ~12–14 min
- **Beans:** dark brown, oily surface
- **Cup:** smoky, chocolatey, classic Italian espresso character

### Dark (French / Italian / dark roasts)

- **Drop temp:** 222–230 °C, well into 2nd crack
- **Development time:** 3:00+
- **Beans:** very dark, oily
- **Cup:** smoky, bittersweet, low acidity, dominant roast character

## Recipes for specific bean origins (Bullet starting points)

### Light Ethiopian washed (Yirgacheffe / Sidamo)

- **500 g charge, charge temp 200 °C**
- **Drying:** 3:30 (ends at 150 °C)
- **Browning:** 4:00 (ends at FC, ~199 °C)
- **Development:** 1:30 (drop at 207 °C)
- **Total time:** ~9 minutes
- **Goal:** preserve floral / citrus / tea character

### Brazilian natural (medium / espresso)

- **500 g charge, charge temp 195 °C**
- **Drying:** 4:00
- **Browning:** 4:30
- **Development:** 2:30 (drop at 215 °C)
- **Total time:** ~11 minutes
- **Goal:** chocolate, nut, balanced espresso character

### Anaerobic Colombian (modern process)

- **500 g charge, charge temp 195 °C**
- **Drying:** 4:00
- **Browning:** 4:00
- **Development:** 1:45 (drop at 209 °C)
- **Total time:** ~9:45
- **Goal:** preserve fermentation character (often very specific notes — strawberry, kombucha, wine)

### Sumatra Mandheling (wet-hulled / Giling Basah)

- **500 g charge, charge temp 200 °C**
- **Slower overall, more aggressive in browning** — Sumatran beans are dense
- **Drying:** 4:30
- **Browning:** 4:30
- **Development:** 2:30 (drop at 215 °C)
- **Total time:** ~11:30
- **Goal:** rich earthy / smoky character; classic Sumatran cup

### Dark roast for milk-drink espresso

- **500 g charge, charge temp 195 °C**
- **Drying:** 4:00
- **Browning:** 5:00
- **Development:** 3:00+ (drop at 222 °C, into 2nd crack)
- **Total time:** ~13 minutes
- **Goal:** bittersweet, chocolatey, cuts through milk

## Profile design checklist

For every roast, before you charge:

- [ ] Bean is **rested** (~3 weeks post-harvest minimum for green)
- [ ] **Charge weight set** (500 g typical)
- [ ] **Charge temp set** (180–210 °C depending on bean)
- [ ] **RoasTime running** and recording
- [ ] **Cooling tray ready** (clean, fan tested)
- [ ] **Profile in mind** (or load a reference profile in RoasTime to guide manually)
- [ ] **Notebook open** — log charge temp, bean origin, anything unusual

After the roast:

- [ ] **Save the profile** with descriptive name (e.g., "Ethiopia_Yirgacheffe_500g_2024-04-26")
- [ ] **Note any deviations** from plan
- [ ] **Cup the coffee** in 24–72 hours
- [ ] **Annotate the profile** with cupping notes

This builds your personal Bullet roasting library over time.

## Cupping your roasts

The standard SCAA/SCA cupping protocol:

- **Coarse grind 11 g of beans** per 200 ml cup
- **Pour 200 ml of just-off-boil water** over grounds
- **Wait 4 minutes** while crust forms
- **"Break" the crust** with a spoon (smell deeply as you break — this is "fragrance" evaluation)
- **Skim off floating debris**
- **Wait until cool enough to slurp** (~10 min)
- **Slurp aggressively** to spray the coffee across your palate

Evaluate:

- **Fragrance** (dry grounds smell)
- **Aroma** (wet grounds + crust break)
- **Acidity** (intensity and quality)
- **Body** (mouthfeel, viscosity)
- **Sweetness** (balance, desirability)
- **Aftertaste** (length, character)
- **Overall** (your personal preference + balance)

Cup at **least 24 hours after roast**, ideally **3 days post-roast** when the beans have had time to off-gas and the flavors integrate.

## Common Bullet-specific issues

### Underdeveloped flick at FC (sour, papery cup)

- Reduce heat input earlier (P5 → P4 by browning)
- Slow the approach to FC
- Increase fan slightly through browning
- Or: simply extend development phase to 1:45+

### Roast stalls (RoR drops to zero before FC)

- Heat input too low through Maillard
- Bump P up by 1 in browning phase
- Or: charge temp was too low

### Tipping (dark spots on bean surfaces)

- Charge temp too high
- Drum speed too low (insufficient bean rotation)
- Reduce charge temp 5–10 °C
- Bump drum speed (D5 → D6)

### Scorching (dark patches, broken bean surfaces)

- Heat too aggressive at start
- Reduce P from 9 to 7 in first 1–2 minutes after charge
- Increase D for better rotation

### Roast too long (pre-FC > 8 minutes for 500g)

- Charge temp too low
- Heat input too low through drying
- Bump P higher in drying phase

### Smoke / chaff buildup mid-roast

- Increase F earlier (F3 by browning)
- Clean out chaff catcher between roasts
- Smoke is normal; if excessive, ventilation is needed (especially for dark roasts)

## Maintenance

- **After every 2–3 roasts:** empty chaff collector, brush out drum
- **Weekly (if roasting often):** wipe down cooling tray, check for chaff buildup
- **Monthly:** open the back, clean fan, check for chaff in airflow paths
- **Yearly:** check seals, lubricate drum bearings if needed (manual specifies)

A Bullet that's well-maintained roasts identically year 5 as year 1.

## Sourcing green coffee

For the Bullet (500g+ batches, regular roasting):

- **Sweet Maria's** (US) — broad selection, good education, smaller bag sizes
- **Royal Coffee** (US) — bigger bags, more cafe-grade
- **Bodhi Leaf Coffee** (US/online) — smaller specialty selections
- **Cafe Imports** (US) — wholesale-leaning but home roasters can buy
- **Coffee Bean Shop** (UK/EU) — UK-based with good European bean selection
- **Various NZ / AU specialty importers** for Antipodean availability

Buy in **5–10 kg quantities** when you find a coffee you love — green coffee stores well for 6+ months in cool, dry conditions.

## What roasting teaches you

Roasting on the Bullet teaches:

- **Heat transfer at small scale** — thermal mass, conduction, convection
- **Time-and-temperature precision** — most demanding food-craft you can do at home
- **Sensory → process feedback** — cup it, change profile, cup again
- **Patience and discipline** — every variable change → 24-hour wait for results
- **Coffee's chemistry intimately** — Maillard, caramelization, Strecker degradation, all happening in front of you

It's the most rewarding home-craft skill that connects directly to a daily ritual (the cup of coffee).

## Cross-references

- **[`README.md`](README.md)** — coffee section overview
- **[`processing/`](processing/)** — what's in the green bean before you roast it (matters enormously)
- **[`brewing/`](brewing/)** — what to do with the roasted beans
- **[`water/`](water/)** — water for cupping, brewing, and tasting your roasts
- **[`../theory/flavor-chemistry.md`](../theory/flavor-chemistry.md)** — Maillard reaction details (same chemistry as bread crust + beer Maillard)
