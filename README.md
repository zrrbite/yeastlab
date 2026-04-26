# yeastlab

A working notebook for fermentation crafts that share more than they look like — sourdough, baker's yeast bread, beer, and coffee. Built around the idea that **fermentation is one craft with many costumes**: the same enzymes (amylase, protease), the same microbes (yeast, lactic acid bacteria), the same Maillard chemistry on the back end. Understand it once, then stage time, temperature, and water for whatever you're making.

The repo is named "yeastlab" because the work started with yeast — but **coffee was actually the first lens** through which water chemistry got serious here, and water turns out to be the hidden third leg of the stool that ties everything together.

## What is fermentation

> Fermentation is the **anaerobic metabolism of sugar into simpler compounds — alcohols, acids, CO₂** — releasing small amounts of energy.

Every craft in this repo is a different costume on the same biology. Before getting into specifics, here's the chemistry that ties bread, beer, and coffee together.

### Anaerobic respiration — the core idea

Cells need energy. They get it by **breaking down sugar** and capturing the released energy as ATP (adenosine triphosphate, the cellular "energy currency").

There are three ways to do this:

- **Aerobic respiration** — uses oxygen. Sugar is **completely oxidized** to CO₂ + H₂O. Yields ~36 ATP per glucose. This is what your muscles do when they have enough oxygen.
- **Anaerobic respiration** — uses an alternative electron acceptor (nitrate, sulfate). Some bacteria do this. Yields ~2–30 ATP per glucose.
- **Fermentation** — uses **no external electron acceptor at all**. The cell oxidizes part of the sugar molecule and reduces another part of *the same molecule* — internal redox. Yields **only 2 ATP per glucose** (~5% of aerobic respiration's energy).

The other 95% of the energy stays locked up in the byproducts: **ethanol, lactic acid, acetic acid, CO₂, and a hundred aromatic compounds**. That low energy yield is exactly why fermentation is so useful for food and drink: the yeast doesn't extract all the energy, leaving most of it (in the form of alcohol and flavor compounds) for us.

### The two main fermentations in this repo

| Type                       | Microbe                          | Inputs                       | Products                                          | Where it shows up                       |
|----------------------------|----------------------------------|------------------------------|---------------------------------------------------|------------------------------------------|
| **Alcoholic fermentation** | *Saccharomyces cerevisiae* (yeast) | Glucose                    | Ethanol + CO₂ + esters/aldehydes                  | Bread (CO₂ for rise), beer, wine, kombucha |
| **Lactic fermentation**    | *Lactobacillus*, *Pediococcus* (LAB) | Glucose, maltose          | Lactic acid (sometimes acetic acid + ethanol)     | Sourdough, sour beer, yogurt, kimchi, coffee processing |

Both happen at once in **sourdough** (mixed yeast + LAB), and in **coffee processing** (the same microbes living on the cherry during washed / honey / natural / anaerobic processing). Beer is mostly alcoholic except for sour styles.

### Inside the yeast cell — alcoholic fermentation

Glycolysis (the Embden–Meyerhof–Parnas pathway):

```
Glucose ──(10 enzyme steps)──> 2 Pyruvate + 2 ATP + 2 NADH
```

Then under anaerobic conditions, two more steps:

```
2 Pyruvate ──(decarboxylase)──> 2 Acetaldehyde + 2 CO₂
2 Acetaldehyde + 2 NADH ──(alcohol dehydrogenase)──> 2 Ethanol + 2 NAD⁺
```

The last step is the actual "fermentation" part — yeast regenerates NAD⁺ so glycolysis can keep running. Net per glucose: **2 ethanol + 2 CO₂ + 2 ATP**.

That CO₂ is what lifts your bread and carbonates your beer. The ethanol is what evaporates from a baking loaf or stays in finished beer. The trace esters and aldehydes from this pathway are what give each yeast its character.

### Inside the LAB cell — lactic fermentation

Two flavors:

**Homofermentative** (most *Lactobacillus*):

```
Glucose → 2 Lactic acid + 2 ATP
```

→ Clean, yogurt-like acidity. No gas. The "smooth tang" of mild sourdough.

**Heterofermentative** (*Leuconostoc*, *Weissella*, some *Lactobacillus*):

```
Glucose → Lactic acid + (Acetic acid OR Ethanol) + CO₂ + 1 ATP
```

→ Tangy, aromatic, complex sourness. The "vinegar edge" of long-fermented sourdough or sour beer.

### The combined sourdough equation

Both yeast and LAB working in parallel:

```
Glucose → (Ethanol + CO₂)_yeast + (Lactic + Acetic acid)_LAB
```

That's the chemical fingerprint of sourdough — **and of natural-process coffee**, and of saison-style beer. The same fermentation in different containers.

### Why this matters across crafts

The fact that **the same chemistry runs in four different crafts** is the throughline of this repo. Once you understand what fermentation actually *is*:

- **Bread:** you understand why warm dough rises faster (yeast metabolism), why slow-fermented bread is more sour (LAB has time to acidify), why crust browns (residual sugars hit Maillard at oven temps).
- **Beer:** you understand why ales (warm, fast) taste different from lagers (cold, slow), why a NEIPA wants biotransformation timing, why dry-hop creep is a thing (hop enzymes restart fermentation).
- **Coffee:** you understand why a natural-process coffee tastes funky (long fermentation in the fruit), why a washed coffee tastes clean (short controlled fermentation), why anaerobic coffees are more aromatic (sealed-vessel fermentation favors specific microbes).
- **Across all three:** you understand that **temperature, time, and oxygen** are the three knobs that change everything.

Read more in **[`theory/fermentation.md`](theory/fermentation.md)** for the full chemistry and pathway diagrams. The other theory files build on this foundation:

- **[`theory/enzymes.md`](theory/enzymes.md)** — amylase, protease, the autolytic process
- **[`theory/flavor-chemistry.md`](theory/flavor-chemistry.md)** — esters, diacetyl, Maillard, where flavor actually comes from
- **[`theory/yeast-strains.md`](theory/yeast-strains.md)** — every yeast (and LAB) used across crafts
- **[`theory/fermentation-temperature.md`](theory/fermentation-temperature.md)** — temperature playbook spanning all crafts
- **[`theory/water-minerals.md`](theory/water-minerals.md)** — water chemistry, applies everywhere
- **[`theory/bread-vs-beer.md`](theory/bread-vs-beer.md)** — same enzymes, same tricks, side-by-side

## Where to start

Pick the craft you're here for:

- **[`sourdough/course/`](sourdough/course/)** — **brand new to sourdough?** Start with the 4-week beginner course. From scratch starter to weekly DEAM rhythm.
- **[`sourdough/methods/double-enzymatic-activation.md`](sourdough/methods/double-enzymatic-activation.md)** — the headline sourdough method (full reference). A low-maintenance cold-fed-levain workflow built around enzyme timing rather than recipe slavishness.
- **[`beer/styles/neipa.md`](beer/styles/neipa.md)** + **[`beer/hops/dry-hopping.md`](beer/hops/dry-hopping.md)** — NEIPA-first beer section, with Scott Janish's dry-hopping research as the spine.
- **[`coffee/water/recipes.md`](coffee/water/recipes.md)** — the fastest path to better coffee is better water. Start here.
- **[`coffee/processing/`](coffee/processing/)** — how the bean got the way it is, fermentation-wise.
- **[`theory/`](theory/)** — the cross-cutting science. Fermentation pathways, enzyme behavior, flavor chemistry, water minerals, and how brewing and baking borrow from each other.

## Layout

```
yeastlab/
├── theory/          # cross-cutting science (applies to all crafts)
├── sourdough/       # wild yeast + LAB
│   ├── course/      # 4-week beginner course
│   ├── methods/     # the DEAM method lives here
│   └── recipes/
├── bakers-yeast/    # commercial yeast bread
├── beer/            # brewers yeast — NEIPA-first
│   ├── styles/      # style definitions
│   ├── hops/        # variety reference, dry hopping (Janish synthesis)
│   ├── process/     # mashing, whirlpool, fermentation, packaging, temp control
│   └── recipes/
├── coffee/          # the fermented bean and the water that brews it
│   ├── water/       # mineral recipes (TWW, Lotus, Hendon, DIY)
│   ├── processing/  # washed, natural, honey, anaerobic, experimental
│   ├── brewing/     # V60, AeroPress, espresso
│   └── roasting.md  # Aillio Bullet R2 roasting guide
└── doc/             # original source PDFs (DEAM, Janish MBAA TQ)
```

## The throughline

Why one repo for sourdough, NEIPA, and coffee? Because the chemistry is shared:

| Concept                | Sourdough                          | Beer (NEIPA)                          | Coffee                                  |
|------------------------|------------------------------------|---------------------------------------|------------------------------------------|
| **Microbial culture**  | Wild yeast + LAB in starter        | Cultured yeast (+ sometimes LAB)      | Wild yeast + LAB on coffee cherry        |
| **Substrate**          | Flour starches → maltose           | Malted grain sugars                   | Coffee cherry sugars + mucilage          |
| **Fermentation phase** | Bulk + proof                       | Primary + dry hop window              | Cherry processing (washed/natural/honey) |
| **Flavor chemistry**   | LAB acids + yeast esters → Maillard| LAB acids + yeast esters + hop oils + Maillard | LAB acids + yeast esters + Maillard in roast |
| **Water role**         | Hydration, mash chemistry          | Whole beer, hop chemistry             | Extraction medium, the cup itself        |
| **Locking it in**      | Bake                               | Boil → ferment → package              | Drying → roasting                        |

Once you understand one of these crafts deeply, you're 70% of the way to understanding the others. The remaining 30% is what each craft does *with* the same chemistry, in a different physical setup.

## Philosophy

> Think like a builder, not a follower. Your formula is a starting ratio, not a rulebook.

These docs explain *why* a step works, not just *what* to do. Once you know how the enzymes and microbes behave, the recipes write themselves and the schedule bends to your life instead of the other way around.

## License

MIT — see [`LICENSE`](LICENSE). Use, adapt, share.
