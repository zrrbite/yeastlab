# Beer

Brewers yeast and the rest of the chemistry that turns wort into beer. Same fundamentals as bread (see [`../theory/bread-vs-beer.md`](../theory/bread-vs-beer.md)) — different staging.

This section is **NEIPA-first** but expanding into the broader American IPA family. Depth over breadth, hop-head bias, low-DO pipeline assumed. The structure is general enough to absorb other styles.

## Where to start

- **[`styles/`](styles/)** — style index. NEIPA, West Coast IPA, and a comparison file.
- **[`styles/neipa.md`](styles/neipa.md)** — the original headline style: hazy, juicy, soft.
- **[`styles/west-coast-ipa.md`](styles/west-coast-ipa.md)** — clear, dry, piney — the inverted twin of NEIPA.
- **[`styles/comparison.md`](styles/comparison.md)** — NEIPA / Modern WCIPA / Classic WCIPA / Cold IPA at a glance.
- **[`hops/dry-hopping.md`](hops/dry-hopping.md)** — the headline content. Synthesizes Scott Janish's research (blog + *The New IPA* + MBAA TQ paper) on timing, biotransformation, hop creep, polyphenols, and dissolved-oxygen control.
- **[`hops/varieties.md`](hops/varieties.md)** — hop-by-hop reference profiles: oils, descriptors, what they pair with.
- **[`hops/sensory-analysis.md`](hops/sensory-analysis.md)** — sensory framework for evaluating hops: dry rub, cold tea, hot tea, in beer.
- **[`recipes/neipa-template.md`](recipes/neipa-template.md)** — NEIPA base recipe.
- **[`recipes/west-coast-ipa.md`](recipes/west-coast-ipa.md)** — WCIPA template.
- **[`recipes/west-coast-dipa.md`](recipes/west-coast-dipa.md)** — WCIPA DIPA at ~9%.
- **[`yeast-strains.md`](yeast-strains.md)** — strain-by-strain character profiles for NEIPA.
- **[`yeast-products-neipa.md`](yeast-products-neipa.md)** — practical comparison of liquid vs dry yeast products. **Lallemand Verdant IPA recommendation for most brewers.**
- **[`yeast-starters.md`](yeast-starters.md)** — when starters matter (mostly liquid yeast), when to skip them (most dry yeast cases), and how to make one if you need to.

## Layout

```
beer/
├── styles/                       # style definitions
│   ├── neipa.md                  # New England IPA
│   ├── west-coast-ipa.md         # West Coast IPA (modern + classic)
│   └── comparison.md             # IPA family side-by-side
├── hops/
│   ├── varieties.md              # ~30 hop-by-hop profiles
│   ├── dry-hopping.md            # Janish synthesis
│   ├── products.md               # T-90, T-45, Cryo, Spectrum
│   ├── storage-oxidation.md      # degradation and storage
│   └── sensory-analysis.md       # evaluation framework
├── water.md                      # NEIPA chloride-forward profile (WCIPA inverts this)
├── yeast-strains.md              # London III, Conan, kveik, Chico (US-05)
├── process/
│   ├── whirlpool.md              # the 180 °F window per Janish
│   ├── fermentation.md           # ferm temps, biotransformation timing
│   └── packaging.md              # closed transfers, FermZilla low-DO pipeline
├── recipes/
│   ├── neipa-template.md         # NEIPA base
│   ├── west-coast-ipa.md         # Modern WCIPA
│   ├── west-coast-dipa.md        # WCIPA DIPA
│   └── single-hop-experiments.md # framework for learning hop varieties
└── references.md                 # Janish (blog + book + MBAA TQ), YCH, foundational papers
```

## Equipment assumed

- Boil kettle
- Immersion chiller
- FermZilla All Rounders (pressure-rated PET conical fermenters) — closed transfers, spunding, dry-hop additions under CO₂ all become possible
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
