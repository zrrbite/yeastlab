# Beer

Brewers yeast and the rest of the chemistry that turns wort into beer. Same fundamentals as bread (see [`../theory/bread-vs-beer.md`](../theory/bread-vs-beer.md)) — different staging.

This section is **NEIPA-first by intent**: depth over breadth, hop-head bias, low-DO pipeline assumed. Other styles can come later. The structure is general enough to absorb them.

## Where to start

- **[`styles/neipa.md`](styles/neipa.md)** — the style itself: history, defining traits, what "good" tastes and looks like, the haze stability problem, the freshness clock.
- **[`hops/dry-hopping.md`](hops/dry-hopping.md)** — the headline content. Synthesizes Scott Janish's research (blog + *The New IPA*) on timing, biotransformation, hop creep, polyphenols, and dissolved-oxygen control.
- **[`hops/varieties.md`](hops/varieties.md)** — hop-by-hop reference profiles: oils, descriptors, what they pair with, NEIPA fit.
- **[`recipes/neipa-template.md`](recipes/neipa-template.md)** — parameterized base recipe. Plug in your hop choices.

## Layout

```
beer/
├── styles/                    # style definitions (NEIPA only for now)
├── hops/
│   ├── varieties.md           # hop-by-hop profiles
│   ├── dry-hopping.md         # Janish synthesis
│   ├── products.md            # T-90, T-45, Cryo, Spectrum — when to use what
│   └── storage-oxidation.md   # how hops degrade and how to fight it
├── water.md                   # NEIPA chloride/sulfate, mash pH
├── yeast-strains.md           # London III, Conan, kveik, English ale strains
├── process/
│   ├── whirlpool.md           # the 170°F window, oil retention vs bitterness
│   ├── fermentation.md        # ferm temps, biotransformation timing, free-rise
│   └── packaging.md           # closed transfers, spunding, FermZilla notes, the freshness clock
├── recipes/
│   ├── neipa-template.md      # base recipe to swap hops into
│   └── single-hop-experiments.md   # framework for learning hop varieties
└── references.md              # Janish, Yakima Chief, others
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
- **Yakima Chief Hops** — [Hop & Brew School](https://www.yakimachief.com/blog/hop-and-brew-school) educational series

See [`references.md`](references.md) for the full list.

## Cross-references

- **[`../theory/fermentation.md`](../theory/fermentation.md)** — the underlying glycolysis pathway, identical to bread
- **[`../theory/flavor-chemistry.md`](../theory/flavor-chemistry.md)** — esters, diacetyl, fusels in detail
- **[`../theory/bread-vs-beer.md`](../theory/bread-vs-beer.md)** — how brewing thinking maps to bread and back
