# Packaging — closed transfers and FermZilla low-DO

This is the most important file in the whole NEIPA pipeline. **More NEIPAs are ruined at packaging than at any other stage.** The hops are great, the fermentation is clean, the recipe is dialed — and then a sloppy keg transfer introduces 50–100 ppb of dissolved oxygen, and 10 days later the beer tastes like wet cardboard.

The good news: with pressure-rated fermenters (FermZilla All Rounders fit this perfectly), closed transfers are achievable at homebrew scale. This file is the playbook.

## Why DO matters so much for NEIPA

Hop polyphenols, hop oils, and the haze-stabilizing compounds in NEIPA are **all sensitive to oxygen**. Specifically:

- **Hop polyphenols** oxidize into **quinones** → cardboard / sherry / brown character
- **Hop oils** oxidize → loss of citrus/tropical character, increase in onion/garlic
- **The haze-stabilizing protein-polyphenol matrix** can crash → "drops bright" prematurely
- **Color shifts** from pale orange → brownish

A single packaging-side oxidation event will undo months of careful upstream work. **NEIPA is the most DO-sensitive style in modern brewing.**

The numbers (rough orders of magnitude):

| DO at packaging | NEIPA shelf life      | Sensory impact at week 2 |
|------------------|-----------------------|---------------------------|
| < 30 ppb         | 8–10 weeks of quality | Negligible                |
| 30–100 ppb       | 4–6 weeks             | Slight — detectable in side-by-side |
| 100–300 ppb      | 2–3 weeks             | Significant — cardboard, color shift |
| 300+ ppb         | < 2 weeks             | Severe — beer is "off"   |

Pro brewers target **< 30 ppb at packaging**. Homebrewers can reasonably aim for **< 100 ppb** with careful technique.

## The FermZilla All Rounder advantage

FermZilla All Rounders are PET pressure fermenters rated to ~2.5 bar (~35 PSI). Critically, they enable:

- **Spunding** during fermentation → natural carbonation, no CO₂ stripping at packaging
- **Closed transfers under CO₂ pressure** to a counter-pressure-purged keg
- **Pre-purged dry hop additions** via hop port adapters
- **Bottom-valve dump ports** for spent hops and yeast without opening the lid
- **No headspace exposure** at any point in the process

If your fermenter is a bucket, glass carboy, or non-pressure stainless conical, **you cannot achieve true low-DO packaging.** You can mitigate (closed siphon, CO₂ blanket, etc.) but you'll always introduce more DO than a closed-pressure transfer.

This is the equipment investment that makes NEIPA quality possible.

## The closed-transfer pipeline

End-to-end, here's the process for moving fermenter → keg → glass with minimal O₂.

### Step 1: Spunding during fermentation

The defining move. Before active fermentation finishes, **install a spunding valve** on the FermZilla pressure lid:

- Set the spunding valve to your **target serving pressure** (typically 10–15 PSI at 4 °C, depending on the carbonation level you want).
- As fermentation continues, CO₂ accumulates in the headspace. When pressure exceeds the spunding valve setting, excess CO₂ vents.
- **Net result: the beer self-carbonates** during fermentation. You don't need to force-carbonate later.

Timing:

- **Start spunding when fermentation has reached ~80% attenuation** (gravity ~1.025 for an OG 1.065 NEIPA). Earlier = beer over-carbonates; later = beer under-carbonates.
- Some homebrewers spund even earlier (50–70% attenuation) at lower pressure (5–8 PSI) and let pressure rise gradually as fermentation continues.

For a NEIPA, target carbonation around **2.4–2.6 vol CO₂** — slightly lower than a West Coast IPA. Too much carbonation can scrub hop aromatics and feel "spritzy" rather than soft.

### Step 2: Cold crash under pressure

When fermentation is complete and the cold-side dry hop is done:

- **Crash to 4 °C / 39 °F** while the fermenter is still under pressure.
- Pressure prevents **suckback** (the headspace contraction that pulls outside air through airlocks during a non-pressurized cold crash). This is a classic NEIPA-killer in non-pressure setups.

Hold cold for 1–2 days to drop yeast and remaining hop debris.

### Step 3: Drop spent hops and yeast

The FermZilla bottom valve / collection container makes this easy:

- **Open the bottom valve briefly** to dump spent dry hops and yeast slurry.
- **Close immediately** — don't let pressure equalize with atmosphere.
- A standard FermZilla collection cup catches a few hundred mL of slurry.

You can repeat this 1–2 times before transferring, removing as much trub as possible. Cleaner transfer = clearer beer eventually.

### Step 4: Purge the receiving keg

This is critical. **A keg full of air will give you all the DO you tried to avoid upstream.**

Method 1 — **CO₂ flush via dip tube** (acceptable):

- Empty, sanitized keg with the lid loosely on.
- Connect CO₂ via gas post.
- Let CO₂ flow at low pressure (5–10 PSI) for 30–60 seconds.
- Tighten lid.
- Pressurize to 30 PSI, vent through PRV. Repeat 3–5 times.
- This gets you to maybe 70–90% CO₂ in the keg headspace. **Acceptable but not great.**

Method 2 — **Sanitizer flush** (best):

- Fill the keg completely with **Star San or PBW solution**.
- Push the sanitizer out with **CO₂ pressure** (15–20 PSI through gas post, sanitizer exits liquid post into a bucket / drain).
- The keg is now **filled with CO₂ at the top of the liquid as sanitizer drains**.
- When the keg is empty, you have a CO₂-purged keg with **< 5 ppb of headspace O₂.**
- This is the **gold standard** for keg purging.

### Step 5: Closed transfer

Now move the beer.

Setup:

- **Beer-out line** from the FermZilla bottom valve (with butterfly valve or threaded fitting) to the keg's **liquid post**.
- **Gas line** from the FermZilla pressure lid PRV / gas port to a CO₂ tank — OR the FermZilla's own CO₂ pressure pushes the beer over.
- **Keg's gas post** vents to atmosphere through a PRV or vent tube into a bucket of sanitizer (so you can see when CO₂ is venting).

Procedure:

- **Equalize pressure** between FermZilla and keg by venting the keg briefly.
- **Open the FermZilla bottom valve** slowly. Beer flows through the line into the keg via the liquid post.
- **The displaced gas in the keg vents through the gas post** — pure CO₂ at this point.
- Beer fills the keg from the bottom up. **No splashing, no air contact.**
- When beer reaches the keg's gas post (= keg full), close everything.
- The keg is now **full of beer, naturally carbonated, with a CO₂ headspace and minimal DO.**

### Step 6: Cold storage and serving

- Store the keg cold (4 °C / 39 °F) at all times.
- Serve under CO₂ pressure (10–15 PSI typical for a NEIPA).
- **Use beer-line and dip-tube setups designed for low-DO serving** — older worn-out lines can leak O₂.
- Drink the beer **within 4–6 weeks** for full quality.

## What about bottling?

Bottling NEIPA is **dramatically harder** than kegging from a DO perspective. Each bottle introduces some headspace air; bottle-conditioning fermentation only partially scrubs it.

If you have to bottle:

- **Counter-pressure bottle filler** from a kegged, carbonated beer. Best option.
- **Beer Gun** style — purge bottle with CO₂, fill from the bottom, cap immediately. Workable but slower.
- **Priming sugar method** — gives you secondary fermentation in the bottle, helps scrub a little O₂. Acceptable for non-NEIPA beers, suboptimal for NEIPA.

**Drink bottled NEIPA within 2–3 weeks.** Bottled NEIPA past 4 weeks is rarely good.

## Common packaging mistakes

- **Bottling NEIPA at all.** It works but it's hard. Keg if you can.
- **Cold-crashing in a non-pressure fermenter.** Suckback through the airlock pulls in atmospheric air. Beer is oxidized before you even transfer.
- **Transferring to a non-purged keg.** The keg air dissolves into the beer over 24–48 hours and you've negated all upstream work.
- **Force-carbonating after transfer instead of spunding.** Force-carb introduces some O₂ via the gas line; also some CO₂ stripping of aromatics during the carbonation period. Spunding avoids both.
- **Transferring at room temperature.** Warm beer holds less CO₂ in solution, more goes to headspace, more O₂ exchange when you open lines. Always transfer cold.
- **Long beer lines with bad fittings.** Each connection is a potential O₂ leak. Inspect fittings; use stainless quick-disconnects.
- **"It's just one little exposure, it'll be fine."** It won't. NEIPA is unforgiving.

## A practical homebrew low-DO checklist

For each NEIPA brew, run through this:

- [ ] FermZilla pressure-rated and inspected for leaks
- [ ] Spunding valve set up and ready by ~70% attenuation
- [ ] Dry hop added via hop port adapter under CO₂ purge
- [ ] Cold crash under pressure (10+ PSI maintained)
- [ ] Spent hops dropped through bottom valve, valve closed immediately
- [ ] Receiving keg purged with sanitizer-push method (or 3–5 cycle CO₂ purge minimum)
- [ ] Closed transfer fittings tight, beer line short, no splashing
- [ ] Keg sealed, pressurized, transferred to cold storage immediately
- [ ] Drink within 4–6 weeks

## A note on kegging vs canning at homebrew scale

Pro NEIPA brewers can their beer because it's the best balance of low-DO packaging and consumer convenience. At homebrew scale:

- **Kegging is dramatically easier than canning.** A 19 L keg is a single packaging event; canning 50 cans is 50 events with 50 chances for O₂ pickup.
- **Cans require specialized equipment** (counter-pressure can fillers, seamers) that's expensive and finicky.
- **Cans are great for distribution.** If you just want to drink it yourself or share with a few friends, kegs win.

If you do want to can at home, products like the **Beer Gun + manual seamer** workflow are workable but require practice. Keg first, master that, then consider canning.

## Cross-references

- **[`../hops/dry-hopping.md`](../hops/dry-hopping.md)** — DO matters all the way through, not just at packaging
- **[`../hops/storage-oxidation.md`](../hops/storage-oxidation.md)** — recognizing oxidation in hops vs in finished beer
- **[`fermentation.md`](fermentation.md)** — what feeds into packaging
- **[`../styles/neipa.md`](../styles/neipa.md)** — the freshness clock from a style perspective
