# Beer

Brewers yeast and the rest of the chemistry that turns wort into beer. Same fundamentals as bread (see [`../theory/bread-vs-beer.md`](../theory/bread-vs-beer.md)) — different staging.

This section is **NEIPA-first** but expanded into the broader American IPA family, plus other styles (Saison, Pilsner, Stout, mixed-fermentation) for context. Depth over breadth, hop-head bias, low-DO pipeline assumed.

## Where to start

### Style files

- **[`styles/`](styles/)** — full style index. NEIPA, WCIPA, Cold IPA, Saison, Pilsner, Stout, mixed-fermentation, plus IPA-family comparison.

### Recipes

- **[`recipes/neipa-template.md`](recipes/neipa-template.md)** — NEIPA base recipe.
- **[`recipes/west-coast-ipa.md`](recipes/west-coast-ipa.md)** — WCIPA template.
- **[`recipes/west-coast-dipa.md`](recipes/west-coast-dipa.md)** — WCIPA DIPA at ~9%.
- **[`recipes/cold-ipa.md`](recipes/cold-ipa.md)** — Cold IPA template.
- **[`recipes/single-hop-experiments.md`](recipes/single-hop-experiments.md)** — framework for learning hop varieties.

### Yeast

- **[`yeast-strains.md`](yeast-strains.md)** — strain-by-strain character profiles for NEIPA.
- **[`yeast-products-neipa.md`](yeast-products-neipa.md)** — practical comparison of liquid vs dry yeast products. **Lallemand Verdant IPA recommendation for most brewers.**
- **[`yeast-starters.md`](yeast-starters.md)** — when starters matter (mostly liquid yeast), when to skip them (most dry yeast cases), and how to make one if you need to.

### Hops

- **[`hops/dry-hopping.md`](hops/dry-hopping.md)** — the headline content. Synthesizes Scott Janish's research (blog + *The New IPA* + MBAA TQ paper) on timing, biotransformation, hop creep, polyphenols, and DO control.
- **[`hops/varieties.md`](hops/varieties.md)** — ~30 hop-by-hop reference profiles.
- **[`hops/varieties/`](hops/varieties/)** — single-variety deep dives (Citra, Galaxy, Mosaic, Nelson Sauvin).
- **[`hops/sensory-analysis.md`](hops/sensory-analysis.md)** — sensory framework for evaluating hops.
- **[`hops/products.md`](hops/products.md)** — T-90 vs T-45 vs Cryo® vs Spectrum® product trade-offs.
- **[`hops/storage-oxidation.md`](hops/storage-oxidation.md)** — keeping hops fresh.

### Water

- **[`water.md`](water.md)** — NEIPA target water profile (chloride-forward); WCIPA inverts this.
- **[`water-tap-adjustments.md`](water-tap-adjustments.md)** — adjusting your specific tap water for brewing. Worked examples for soft, moderate, and hard water profiles.

### Process

- **[`process/mashing.md`](process/mashing.md)** — mash temp, step mashes, mash-out, lautering, stuck-mash recovery for high-adjunct grain bills.
- **[`process/whirlpool.md`](process/whirlpool.md)** — the 180 °F window per Janish, plus practical mechanics, multi-temp strategies, cold steep, acidification timing.
- **[`process/fermentation.md`](process/fermentation.md)** — ferm temps, biotransformation timing.
- **[`process/packaging.md`](process/packaging.md)** — closed transfers, FermZilla low-DO pipeline.
- **[`process/temperature-control.md`](process/temperature-control.md)** — KegLand fermentation chamber and temperature playbook.

### Workflow

- **[`brew-day-workflow.md`](brew-day-workflow.md)** — practical brew-day playbook: pre-brew checklist, hour-by-hour timeline, equipment-specific tips, troubleshooting.
- **[`house-recipes.md`](house-recipes.md)** — building a rotation of 3–5 house recipes you brew repeatedly and iterate on. The path from intermediate to truly skilled.

### References

- **[`references.md`](references.md)** — Janish (blog + book + MBAA TQ), YCH, foundational papers.

## Layout

```
beer/
├── styles/                       # 7 styles + comparison
├── hops/
│   ├── varieties.md              # quick-reference (~30 hops)
│   ├── varieties/                # deep dives (Citra, Galaxy, Mosaic, Nelson)
│   ├── dry-hopping.md            # Janish synthesis
│   ├── products.md               # T-90, T-45, Cryo, Spectrum
│   ├── storage-oxidation.md      # degradation and storage
│   └── sensory-analysis.md       # evaluation framework
├── water.md                      # NEIPA chloride-forward profile
├── water-tap-adjustments.md      # adjusting your tap water for brewing
├── yeast-strains.md              # London III, Conan, kveik, Chico (US-05)
├── yeast-products-neipa.md       # liquid vs dry comparison
├── yeast-starters.md             # when starters matter and when they don't
├── process/                      # mashing, whirlpool, fermentation, packaging, temp control
├── recipes/                      # NEIPA, WCIPA, DIPA, Cold IPA, single-hop
├── brew-day-workflow.md          # practical brew day playbook
├── house-recipes.md              # building a rotation
└── references.md                 # Janish, YCH, foundational papers
```

## Equipment assumed

- Boil kettle
- Immersion chiller
- FermZilla All Rounders (pressure-rated PET conical fermenters) — closed transfers, spunding, dry-hop additions under CO₂ all become possible
- KegLand fermentation chamber for temperature control
- Kegging system

If your kit differs (BIAB, no pressure fermenter, bottles), most of the recipes still apply — but the **packaging and dry-hop process notes assume pressure-capable fermentation** because that's where NEIPA quality lives or dies.

## Sources

The NEIPA content draws heavily on:

- **Scott Janish** — [scottjanish.com](https://scottjanish.com) and *The New IPA: Scientific Guide to Hop Aroma and Flavor*
- **Yakima Chief Hops** — Hop & Brew School podcast series and annual brewer-education event

See [`references.md`](references.md) for the full list.

## Cross-references

- **[`../theory/fermentation.md`](../theory/fermentation.md)** — the underlying glycolysis pathway, identical to bread
- **[`../theory/flavor-chemistry.md`](../theory/flavor-chemistry.md)** — esters, diacetyl, fusels in detail
- **[`../theory/bread-vs-beer.md`](../theory/bread-vs-beer.md)** — how brewing thinking maps to bread and back
- **[`../theory/yeast-strains.md`](../theory/yeast-strains.md)** — yeast across all crafts (the bigger picture)
- **[`../theory/fermentation-temperature.md`](../theory/fermentation-temperature.md)** — temperature playbook across all crafts
