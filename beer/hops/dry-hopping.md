# Dry hopping

Dry hopping is where NEIPA beers are made or broken. It looks simple — drop hops into the fermenter — but every variable interacts: timing, temperature, contact time, hop product format, agitation, oxygen, yeast viability, residual sugar, polyphenol load.

This file is a working synthesis of Scott Janish's published work, primarily:

> **Janish, S. 2021.** "Dry Hop Best Practices: Using Science as a Guide for Process and Recipe Development." *MBAA Technical Quarterly* 58(1):59–65. [DOI: 10.1094/TQ-58-1-0402-01](https://doi.org/10.1094/TQ-58-1-0402-01). PDF in [`../../doc/TQ-58-1-0402-01.pdf`](../../doc/TQ-58-1-0402-01.pdf).

> **Janish, S. 2019.** *The New IPA: Scientific Guide to Hop Aroma and Flavor.* Self-published.

> **Janish, S.** [scottjanish.com](https://scottjanish.com) — ongoing blog research.

Numbers and recipe-level recommendations below cite this work where load-bearing. See [`../references.md`](../references.md) for the full reference list.

## What we're actually extracting

Janish (2021) groups hop-derived compounds extracted during dry hopping into four categories:

### Hydrocarbons (myrcene, caryophyllene, farnesene)

The largest fraction of hop oil. Described as **spicy, herbal, woody, green, resinous** — and increasingly so when oxygenated. The **most volatile** during brewing — myrcene is reduced 50% by 10 min of boiling and gone after 60 min.

But: hazy IPAs **retain much higher concentrations of hydrocarbons** than West Coast IPAs because the haze itself acts as a carrier for these nonpolar compounds (Maye & Smith 2018). At excessive concentrations these can dominate the palate with green/resinous character.

- **Myrcene-rich hops:** HBC 492, Pahto, Centennial, Citra, Sabro, Bravo, Mosaic
- **Caryophyllene-rich hops:** Talus, Brewer's Gold, HBC 492, Centennial, Sabro, Motueka, Chinook
- **Farnesene-rich hops:** GR Tettnang, GR Spalt, Czech Spalt, Santiam, Sterling, GR Huell Melon, NZ Waimea, Saaz, NZ Green Bullet

### Monoterpene alcohols (linalool, geraniol, nerol)

The **oxygenated** fraction — about 30% of total oil. **Floral, fruity, citrus.** These have **10–100× the solubility** of the hydrocarbons (because of polar oxygen groups) so they're more likely to remain in beer through the brewing process. The reliable fruit-and-floral backbone.

- **Linalool-rich hops:** Bramling Cross, Crystal, Citra, GR Tradition, UK Progress, Liberty, Loral, Ultra, GR Hallertau Mittelfrüh, Nugget, NZ Dr. Rudi, Brewer's Gold
- **Geraniol-rich hops:** Talus, Brewer's Gold, HBC 492, Centennial, Sabro, Motueka, Chinook

Geraniol is also **biotransformable** by yeast → β-citronellol (softer, rosier citrus).

### Polyfunctional thiols (3MH, 4MMP, 3MHA)

Sulfur compounds. Less than 1% of hop oil but **extremely low taste thresholds** — 4MMP detectable at **1.5 ng/L** in beer. The "juicy passionfruit/blackcurrant/grapefruit" character of modern IPAs is largely thiol-driven.

- **4MMP** — blackcurrant, catty (at high concentrations). Threshold 1.5 ng/L.
  - Hops high in 4MMP: **Citra, Simcoe, Eureka!, Summit, Apollo, Topaz, Mosaic, Ekuanot, Galaxy, Nelson Sauvin** (Hieronymus 2017)
- **3MH** — grapefruit, rhubarb. Threshold 55 ng/L.
  - Hops high in 3MH: **Pahto (very high), Columbus, Centennial, Millennium, Comet, Idaho 7, Mosaic, Bravo, Sabro, Chinook, Palisade**
- **3MHA** — passionfruit. Converted from 3MH (yeast-mediated). Threshold 4 ng/L.

Most thiols exist in hops as **bound precursors** that yeast must liberate — see "Active-fermentation dry hop" below.

### Hop-derived esters (isoamyl isobutyrate, methyl geranate, 2MIB)

Fruity apple/apricot character. Survive brewing reasonably well. **2MIB is likely the most dominant component ester.**

- **Isoamyl isobutyrate-rich hops:** Ekuanot, Mosaic, Simcoe, Talus, Idaho 7, HBC 640, Sabro
- **Methyl geranate-rich hops:** Centennial (very high), Citra, Mosaic, Simcoe, Chinook, Idaho 7
- **2MIB-rich hops:** Idaho 7 (very high), Ekuanot (very high), Southern Cross, Pacific Jade, Vic Secret, Bravo, Polaris, Talus, El Dorado, Centennial

These survive boiling poorly → **whirlpool is the best route** to get them into the fermenter.

## Synergy — why combos matter

Janish (2021) emphasizes that perceived flavor isn't a sum of individual concentrations — compound classes **enhance each other's perception**:

- **4MMP enhances perception of monoterpene alcohols** (linalool, geraniol) without changing their concentrations.
- **High-geraniol hops** (Bravo) increase citrusy/flowery scores of low-geraniol hops (Simcoe).
- **3S4MP** can enhance perception of the 2MIB ester. Pairing Nelson Sauvin and Southern Cross can lift apricot character.
- **Hop-derived fatty acids** (2-methylbutyric acid, isovaleric acid) enhance "tropical" and "fruity" perception. Apollo and Bravo have the highest concentrations of these (Takoi 2019). Slightly aged hops can have more of these from oxidative degradation of bitter acids.

**Practical takeaway:** diversify across the four compound classes when designing a hop combo. A combo that's all monoterpene alcohols (Centennial-Cascade-Amarillo) won't have the same "loud" character as one that mixes thiol-rich (Citra, Galaxy) + ester-rich (Ekuanot, Idaho 7) + geraniol-rich (Sabro, Centennial) hops.

## The two-stage NEIPA dry hop

Modern NEIPA workflow uses two distinct dry hop additions:

### Stage 1: Active-fermentation dry hop (biotransformation)

Dropped when fermentation has reached **~50–70% attenuation** — typically 24–48 hours after pitch.

**What's happening:**

- Yeast is still very active and producing CO₂ (which scrubs O₂ — protective).
- **β-glucosidase** enzymes (yeast-derived) cleave hop **glycosides**, freeing bound aromatic compounds — especially **bound thiols** → tropical/passionfruit aromas that weren't there pre-fermentation.
- **Geraniol → β-citronellol** transformation by yeast reductases.
- **Linalool isomerization** can occur.

**What you get:** depth, juicy character, and the kind of complexity no amount of cold-side dry hopping can replicate.

**Risks:**

- **Yeast scrubbing.** Active yeast strips some volatile aromatics by binding them or carrying them out with CO₂. Some loss is inevitable.
- **Hop creep** (more on this below).
- **Hydrocarbon scrubbing as a feature.** Janish (2021) notes that mid-fermentation dry hopping can be a way to **reduce dominant hydrocarbon character** for varieties that lean very resinous/green — Sabro is the example given. CO₂ production scrubs the hydrocarbons while still letting the variety contribute its other compounds.

**How much:** typically 3–6 g/L for the active-ferm charge.

### Stage 2: Cold-side dry hop (aroma)

Dropped at terminal gravity, contact 1–3 days, then crashed.

**What's happening:**

- Yeast activity largely done. No biotransformation, minimal scrubbing.
- Pure extraction of volatile oils into finished beer.
- The aromatics you smell when you crack a fresh NEIPA come predominantly from this stage.

**Risks:**

- **Highest oxidation risk** — fermentation has stopped, no CO₂ to scrub introduced O₂. Closed transfers and CO₂ purging are essential.
- **Polyphenol astringency** — too-long or too-warm cold-side contact pulls excess polyphenols.
- **Hydrocarbon over-extraction** — myrcene specifically extracts much more at warm temps (more on this below).

**How much:** typically 3–6 g/L. Contact **1–3 days**.

## Janish's headline findings

### Extraction is *fast* — 1–3 days, not a week

Multiple studies cited in Janish (2021):

- A week-long static dry hop showed **day 7 concentrations of linalool and myrcene were not higher than day 1**. Most decreased by day 7.
- Another study found **myrcene and monoterpene alcohols fully extracted in 4 hours** with constant agitation.
- 4MMP thiol extraction was nearly complete in **2 days** of post-fermentation dry hopping in centrifuged beer (Reglitz et al. 2018).
- Polyphenol concentrations peak at day 3 and stay flat.

**Implication:** dry hop contact time of **1–3 days is sufficient**. Going longer adds polyphenols and grass without adding aroma. Janish recommends a **3-day max** at Sapwood, with spent hops removed before any additional dry hop charges.

### Cool dry hop temperatures (50–58 °F / 10–14 °C) are better

This is one of the most counterintuitive findings if you've absorbed older brewing wisdom. Janish (2021) recommends **cool dry hopping**, citing several converging benefits:

- **Linalool and other monoterpene alcohols extract well at all temperatures** — even at 39 °F (4 °C). Cold extraction was actually slightly *higher* than warm in one study (Hinz et al. 2016).
- **Hydrocarbons (myrcene, etc.) extract dramatically more at warmer temps.** At 68 °F (20 °C) myrcene extracted at much higher concentrations than at 34 or 39 °F (Haslbeck et al. 2018). For a NEIPA, **more myrcene is rarely a good thing** — green/resinous notes dominate fruity ones.
- **Polyphenols extract 2–2.5× more at 66 °F vs 39 °F** for low-alpha and high-alpha hops respectively. Less astringency at cool temps.
- **Foam retention is better** at cooler dry hop temps (57 °F vs 69 °F) — alpha acids stabilize foam more effectively when introduced cool.
- **Hop creep is reduced** at cooler temps and shorter durations (more below).

**Sapwood Cellars dry hops at 56 °F (13 °C) for 3 days.** This is a deliberate choice grounded in the data.

### Hop creep is real and measurable

Hop creep = unintended refermentation caused by hop-derived enzymes (amyloglucosidase, plus low levels of α- and β-amylase) hydrolyzing residual dextrins back into fermentable sugars. (Kirkpatrick & Shellhammer 2017.)

Consequences:

- Beer attenuates 5–10 points past your "FG"
- CO₂ regenerated → over-carbonation, possible bottle bombs
- Diacetyl can re-form from a stressed/unhealthy refermentation
- Body thins out

**Two schools of thought** for managing it (Janish 2021):

- **(A) Warm + extended.** Let the creep happen in the tank, hold until VDK (diacetyl) tests are clean. Used by Great Notion at 70 °F (21 °C).
- **(B) Cool + short.** Reduce enzymatic activity by dry hopping at 50–58 °F (10–14 °C) for 3 days max. Used by Sapwood. Sapwood reports no hop creep issues in cans using this approach.

For homebrew scale with a pressure-rated fermenter, **(B) cool + short is easier to execute and more forgiving.** You get hop quality benefits as a bonus.

### pH rises with heavy dry hopping

Dry hopping raises beer pH by **~0.036 units per 3 lb/bbl** of hops (Lafontaine & Shellhammer 2018). At very heavy NEIPA hopping rates, you can end up at **pH 4.7–5.0** which:

- Tastes *more bitter* than the same iso-alpha-acid content at lower pH (Meilgaard & Trolle 1957)
- Hurts foam retention
- Can hinder drinkability, especially in DIPAs

**The pH probably comes from the hop's leaf material**, not the lupulin. Lupulin powder products (Cryo Hops®, Lupomax®) likely cause less pH rise (Janish 2021).

**Sapwood's pH playbook:**

- Mash pH **5.2–5.3**
- Phosphoric acid in the kettle to hit **post-boil pH 4.8–4.9**
- Optional: post-fermentation acid additions to **4.2–4.4**

### Bitterness changes — sometimes more, sometimes less

Counterintuitive: dry hopping can either *increase* or *decrease* bitterness depending on starting IBU and dose (Maye et al. 2016):

- Hop vegetal material **adsorbs (strips) iso-alpha-acids** — at 2 lb/bbl dry hop, isomerized alpha-acids drop by **38%**.
- That bitterness loss is partially replaced by **humulinones** — water-soluble oxidized alpha-acids, **~66% as bitter** as iso-alpha-acids, with a smoother profile.
- **At low IBU (< 20)** with modest dry hop: net **more bitter** (humulinones add more than iso-alpha lose).
- **At high IBU (> 30)** with modest dry hop: net **less bitter**.
- **At very heavy dry hop loads:** humulinones + polyphenols stack into a vegetal/tea-like one-note bitterness without the supporting iso-alpha complexity (Janish 2021).

**Implication:** to compensate for iso-alpha adsorption, **push more bitter compounds into the whirlpool** (1.5–2.5 lb/bbl at 180 °F / 82 °C — Janish's "best practices" for matching heavy dry hop rates). The reduced whirlpool temp keeps IBU manageable while still adding hop flavor.

The **standard IBU test cannot distinguish iso-alpha from humulinones from polyphenols.** Calculated IBU is a recipe tool, not a reliable predictor of perceived bitterness in heavily dry-hopped beer.

### Foam retention takes a hit

Heavy dry hopping reduces foam stability for two reasons (Wilson et al. 2012):

- Higher pH from dry hopping → reduced foam
- Longer dry hop contact time → progressively worse foam (slight after 2 days, accelerating after day 3)

Cool + short dry hopping helps both. Cryo / lupulin powder helps too (less leaf material → less pH rise).

### Agitation matters — and method matters more

Static dry hopping (hops sit in the cone) can leave significant aroma compounds **in the hop material rather than the beer**, especially with high-alpha hops where oils stay locked in the lupulin's hydrophobic alpha-acid phase (Haslbeck et al. 2018).

Agitation options:

- **Pump recirculation** — extracts well (58% more linalool in 2h, Lagemann et al. 2017) but pulls more polyphenols.
- **CO₂ burping from the bottom of the cone** — Sapwood's preferred method. Less polyphenol extraction than pumping.
- **Manual rousing** (rocking, swirling) — works at homebrew scale.

Janish notes: **multiple agitations per day for high-alpha hops and low-ABV beers** — both situations where extraction is more limited.

## Janish's recommended best practices (paraphrased from the 2021 paper)

1. **Match heavy dry hopping with whirlpool hopping** at 1.5–2.5 lb/bbl (~6–10 g/L), at **180 °F (82 °C)** — better bittering balance, more hop-derived flavor complexity. Reduced whirlpool temp retains more oil and keeps IBUs down.
2. **Use survivable-compound hops in the whirlpool:** Idaho 7, Mosaic, Bravo, Citra, Millennium, Mount Hood, Ekuanot, Simcoe.
3. **Acidify the kettle** with phosphoric acid to hit **post-boil pH 4.8–4.9** for high-ABV / heavily-dry-hopped beers. Post-fermentation acid to **4.2–4.4** for drinkability.
4. **Dry hop max 3 days.** Remove spent hops before additional dry hop charges.
5. **Dry hop cool: 50–58 °F (10–14 °C).** Better foam, less hydrocarbon over-extraction, less polyphenol astringency, less hop creep.
6. **Minimize O₂ during dry hopping** — purge hops with CO₂ before adding; use a closed dry hop port or doser; never expose finished beer to air.
7. **Agitate at least once per day.** Multiple times for high-alpha hops or low-ABV beers.
8. **Consider mid-fermentation dry hopping** to soften strong hydrocarbon character from varieties like Sabro that can otherwise dominate the palate — CO₂ production scrubs hydrocarbons while preserving the variety's other contributions.

## Adapting to homebrew scale (FermZilla All Rounders)

The pro-scale procedures don't translate 1:1, but the principles do. For a 23–30 L FermZilla All Rounder pressure-fermenting under spunding:

### Pre-dry-hop

- Drop yeast from the bottom valve before dry hopping if you want a cleaner fermentation environment for the dry hop.
- Crash to **13 °C (~56 °F)** if you're adopting Sapwood's cool-and-short approach. (Or hold at 18–20 °C if you prefer the warm-and-extended Great Notion approach for biotransformation depth.)

### Adding hops with low DO

For closed, low-DO additions on the FermZilla:

- Use a **hop port adapter** (e.g., CMBecker, Keg Land) — purged with CO₂ before dropping hops.
- Or use a **purged collection container** (a small purged keg or bottle) to slot in via the dry hop port without breaking pressure.
- If you have to open the lid: at minimum, **flush the headspace with CO₂** before and after, and limit the time open to seconds.

### Agitation on FermZilla scale

- The pressure-rated FermZillas can spund. Use **brief CO₂ burps from the bottom valve** to rouse hops without pulling vacuum. Keep the spunding valve at typical serving pressure (10–15 PSI), open the bottom valve briefly to let hops circulate, close.
- Or just **swirl/rock the fermenter gently** once per day. Easier, almost as effective at homebrew scale.
- Sapwood's "30 PSI for ~1 minute" doesn't translate — at 30L scale the geometry is too different. **Once-daily gentle agitation is sufficient.**

### Removing spent hops

- Drop hops and yeast through the bottom collection container after 3 days.
- For multi-stage dry hops, drain spent first batch through the collection valve before adding the second.

## A practical NEIPA dry-hop schedule (revised)

For a 23 L batch, OG 1.065, total hopping rate 14 g/L (322 g total hops):

| When                          | Charge       | Hops                                     | Rate     | Temp        |
|-------------------------------|--------------|------------------------------------------|----------|-------------|
| Whirlpool (180 °F, 25 min)   | ~140 g       | Citra 50%, Mosaic 30%, Galaxy 20%        | ~6 g/L   | 82 °C       |
| Active-ferm (~36 hr post-pitch) | ~90 g     | Citra 50%, Galaxy 50%                    | ~4 g/L   | 18–20 °C    |
| Cold-side (at FG, 3 days)     | ~92 g        | Citra 40%, Mosaic 40%, Amarillo 20%      | ~4 g/L   | **13 °C**   |

Key changes from a more "traditional" homebrew NEIPA process:

- **Whirlpool at 180 °F (not 170 °F)** per Janish's recommendation — slightly more isomerization but the bittering balance benefit is real, and more compound extraction at the higher temp.
- **Cold-side dry hop at 13 °C, not at fermentation temperature.** Fewer polyphenols, less myrcene, better foam, less hop creep risk.
- **Total hopping 14 g/L** is in the higher-mainstream range. Push to 18 g/L for "haze bomb" intensity, or back off to 10 g/L for a more session-friendly NEIPA.
- **At very high hop loads (> 16 g/L), substitute Cryo / Spectrum** for some additions to control polyphenol load and pH rise.

## Hop loading rate guidance

| Style intensity              | Total hopping rate | Notes                                   |
|------------------------------|--------------------|-----------------------------------------|
| Soft / sessionable hazy      | 6–10 g/L           | Lighter, more food-friendly             |
| Standard NEIPA               | 10–14 g/L          | The mainstream sweet spot               |
| Aggressive NEIPA / DIPA      | 14–20 g/L          | Loud, polyphenol-heavy, faster-fading   |
| "Triple dry hop" novelty     | 20–28 g/L          | Astringency, pH issues, cost climb fast |

Above 20 g/L, switching some additions to **Cryo / Spectrum** is essential to keep polyphenols in check.

## What to *not* do

- **Don't dry hop in the boil kettle.** That's a late hop addition, not a dry hop.
- **Don't dry hop for more than 3 days.** No aroma gain. Polyphenols, grassiness, foam loss.
- **Don't dry hop, immediately keg, and serve.** Hop creep risk — let beer sit 2–3 days post dry hop with pressure relief, monitor gravity stability.
- **Don't open the fermenter for a "quick peek."** O₂ exposure is real, measurable damage.
- **Don't assume bigger is better.** 8 g/L of fresh, cool, well-handled hops will out-perform 16 g/L of mediocre or poorly-handled hops.
- **Don't dry hop with bittering hops.** CTZ, Magnum, Warrior — they'll add bitterness without aroma payoff.
- **Don't skimp on yeast health for the active-ferm dry hop.** Biotransformation needs vigorous yeast.
- **Don't assume "warmer is more extraction."** It's true for hydrocarbons (which you don't necessarily want more of) and minimally true for monoterpene alcohols. Cool dry hopping is a deliberate quality choice.

## Cross-references

- **[`../references.md`](../references.md)** — Janish blog, book, and the MBAA TQ paper this file draws from
- **[`varieties.md`](varieties.md)** — which hops are rich in which compounds
- **[`products.md`](products.md)** — T-90 vs Cryo® vs Spectrum® for managing polyphenol load
- **[`storage-oxidation.md`](storage-oxidation.md)** — keeping hops fresh until you use them
- **[`../process/whirlpool.md`](../process/whirlpool.md)** — the 180 °F window and survivable-compound hops
- **[`../process/fermentation.md`](../process/fermentation.md)** — biotransformation timing in the broader fermentation schedule
- **[`../process/packaging.md`](../process/packaging.md)** — closed transfers, FermZilla low-DO pipeline
