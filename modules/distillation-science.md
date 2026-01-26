# Distillation Science Module

**Sources**:
- *Craft Gin Making* by Rachel Hicks and Andrew Parsons (Crowood Press, 2021)
- *The Art of Distilling Whiskey and Other Spirits* by Bill Owens and Alan Dikty (Quarry Books, 2009)
- Distillers Wiki / homedistiller.org (Beginner's Guide, Safety, Cuts and Fractions, Spirit Style Guide)
- American Home Distillers Association, PhilBilly Moonshine, Clawhammer Supply calculators
- DIY Distilling, Difford's Guide, Wikipedia (Genever production)

---

## Legal Disclaimer

**IMPORTANT**: Distillation of alcohol is heavily regulated in most jurisdictions. In the United States, it is illegal to distill alcohol at home without a federal Distilled Spirits Permit, regardless of whether the product is for personal use. This module is for **educational purposes only**. Always check and comply with your local, state/provincial, and federal laws before attempting any distillation. Penalties for illegal distillation can include significant fines and imprisonment.

---

## 1. Fundamentals of Distillation

### How Distillation Works

Distillation separates alcohol from water based on their different boiling points:
- **Ethanol boils at**: 78.3°C (173°F) at sea level
- **Water boils at**: 100°C (212°F) at sea level

By heating a fermented liquid (the "wash") to 80-85°C, alcohol vaporizes while most water remains liquid. The alcohol vapor is then cooled and condensed back into liquid form—now at a much higher concentration.

### Key Terminology

| Term | Definition |
|------|------------|
| **Wash/Mash** | The fermented liquid to be distilled |
| **Distillate** | The liquid collected after condensation |
| **ABV** | Alcohol by volume (percentage) |
| **Proof** | ABV × 2 (US system); 100 proof = 50% ABV |
| **Heads** | First portion of distillate; contains methanol and harsh volatiles |
| **Hearts** | Middle portion; the desirable spirit |
| **Tails** | Final portion; contains heavier oils and off-flavors |
| **Cuts** | The decision points between heads/hearts and hearts/tails |
| **Rectification** | Re-distilling an already distilled spirit |
| **Neutral spirit** | Highly purified ethanol (96% ABV), nearly flavorless |

---

## 2. Still Design and Components

### Basic Pot Still Components

```
┌─────────────────────────────────────────────────┐
│                                                 │
│   ┌─────┐                                       │
│   │     │ ← Column/Swan Neck                    │
│   │     │                                       │
│   │     └────────────┐                          │
│   │                  │ ← Lyne Arm               │
│   │                  │                          │
│  ┌┴┐                 ▼                          │
│  │ │              ┌─────┐                       │
│  │ │              │     │ ← Condenser           │
│  │ │              │ ≋≋≋ │   (cold water         │
│  │ │              │ ≋≋≋ │    jacket)            │
│  │ │              │     │                       │
│  └─┘              └──┬──┘                       │
│   ▲                  │                          │
│   │                  ▼                          │
│ Kettle           Distillate                     │
│ (with wash)      Collection                     │
│                                                 │
└─────────────────────────────────────────────────┘
```

### Component Functions

| Component | Function |
|-----------|----------|
| **Kettle (Pot)** | Holds the wash; heated to vaporize alcohol |
| **Column** | Allows reflux (repeated vaporization/condensation) for purity |
| **Plates** | Increase surface area for more reflux; more plates = purer spirit |
| **Dephlegmator** | Additional reflux section, sometimes water-cooled |
| **Lyne Arm** | Connects column to condenser |
| **Condenser** | Cools vapor back to liquid (tube-in-tube design) |
| **Parrot** | Allows continuous ABV monitoring with floating alcoholmeter |
| **Thumper** | Optional: adds extra distillation stage; can increase purity or strength |
| **Gin Basket** | Holds botanicals above the wash for vapor infusion |

### Thumper (Doubler) Design

A thumper is a secondary vessel placed between the pot still and condenser. Hot vapor from the pot enters the thumper below the liquid surface, effectively distilling through the liquid and adding an extra distillation stage.

- **Size**: 1/3 to 2× the volume of ethanol in the wash. For a 5-gallon wash at 10% ABV (0.5 gal ethanol), the thumper should hold 0.17–1.0 gallons.
- **Fill level**: Approximately half full with liquid
- **Best fill liquid** (in order of preference): Tails from a previous run → wash being distilled → water (last resort)
- **Design**: Taller, more slender thumpers are preferred for better vapor contact time
- **Traditional use**: American moonshiners sometimes linked up to 6 thumpers in series for progressive purification
- **Two thumpers** in series produce notably clean bourbon character
- **Limitation**: Temperature-based cuts are unreliable with thumpers — rely on nose, taste, and alcoholmeter readings

### Pot Still Characteristics

A pot still performs a **single distillation** per run. The distillate retains significant flavor from the wash, making pot stills ideal for whiskey, brandy, rum, and any spirit where character from the base material is desired.

- **Output**: Typically 55–70% ABV (110–140 proof) from a single pass
- **Double distillation**: Common for Scotch single malt — first pass produces "low wines" (~25% ABV), second pass produces spirit (~70% ABV)
- **Triple distillation**: Traditional for Irish whiskey — produces a lighter, smoother spirit
- **Cannot produce neutral spirit**: Multiple pot still runs plateau around 80% ABV due to the ethanol-water azeotrope approaching equilibrium inefficiently

### Reflux Still Types

Reflux stills perform multiple condensation/re-vaporization cycles in a single run. The column contains either **packing** or **plates** to create reflux surfaces.

**Packed columns**: Filled with copper mesh, stainless steel scrubbers, Raschig rings, glass marbles, or ceramic saddles. The packing creates surface area for vapor to condense and re-vaporize.

**Plated columns**: Use bubble cap, sieve, or perforated plates. Each plate acts as a discrete distillation stage. Fewer than 6–8 plates still produce flavorful spirits; more plates approach neutral.

#### Reflux Management Methods

| Type | Mechanism | Best For |
| --- | --- | --- |
| **Liquid Management (LM)** | Controls the ratio of liquid reflux returned vs. distillate collected | Precise control; versatile |
| **Vapor Management (VM)** | Diverts a portion of vapor to a separate condenser | Good for higher throughput |
| **Cooling Management (CM)** | Adjusts condenser cooling to regulate reflux amount | Simpler to build; less precise |

### Reflux and Purity

The more times alcohol is vaporized and recondensed before collection, the purer the spirit:
- More reflux = purer, more neutral spirit
- Less reflux = more flavor retained from the wash
- **Trade-off**: High purity strips flavor; low purity retains character

**Column plates**: Each plate adds another stage of reflux
- 4-6 plates: Typical for gin (retains botanical character)
- 20+ plates: Required for neutral spirit production (96% ABV)

**Column choking**: If column packing is too tightly packed or the column diameter is too small for the heat input, rising vapor and falling liquid compete for the same space. A liquid "wall" forms in the column — distillation ceases, temperature drops, pressure builds below the wall, then suddenly bursts through as a surge of liquid from the condenser and a temperature spike. Fix by reducing heat input. When packing a column with copper mesh, the roll should grip the column walls by friction but not be compressed so tightly that it restricts airflow.

### Choosing a Still Type

| Goal | Still Type | Reason |
| --- | --- | --- |
| Whiskey, brandy, rum | Pot still | Retains wash character |
| Flavored spirits with some purity | Plated reflux (<8 plates) | Balance of flavor and clarity |
| Vodka, neutral spirit, gin base | Packed or plated reflux (15+ plates) | High purity (90–96% ABV) |
| Versatile (all spirits) | Reflux still with removable packing | Runs as pot still (empty column) or reflux (packed) |

---

## 3. Wash Types and Preparation

### Sugar Washes

Sugar washes use refined sugar as the primary fermentable. They produce a **neutral spirit** with little base-material character — ideal for vodka, gin bases, liqueurs, and flavored spirits.

**Why start here**: Sugar washes are inexpensive, easy to prepare, and ferment quickly. Experienced distillers recommend 3–6 practice runs on sugar wash before attempting expensive grain or fruit spirits.

**Basic sugar wash**: For a 5-gallon (19L) batch at ~10% ABV:
- 7 lbs (3.2 kg) white table sugar
- Water to 5 gallons total
- Yeast nutrient (DAP or commercial blend — sugar has zero nutrients)
- Distiller's yeast, turbo yeast, or wine yeast

**Procedure**:
1. Dissolve sugar in warm water (~40°C / 104°F)
2. Top up to target volume with cool water
3. Confirm OG with hydrometer (~1.065–1.080 depending on target ABV)
4. Cool to yeast pitching temperature (25–30°C / 77–86°F)
5. Pitch yeast and nutrient
6. Ferment at 20–25°C (68–77°F) until FG reaches ~1.000 (7–14 days)
7. Let settle 2–3 days before distilling

**Key points**:
- Sugar has no nutrients — yeast nutrient is essential or fermentation will stall and produce off-flavors
- Target 7–10% ABV for clean fermentation. Higher ABV washes (14–20%) ferment slower and produce more congeners
- Turbo yeast can reach 18–20% ABV but often produces harsh character

### Sugarhead Washes

A sugarhead uses sugar as the primary fermentable but adds a flavoring ingredient during fermentation — grain, fruit, molasses, etc. This produces a spirit with flavor character at lower cost than an all-grain or all-fruit wash.

### Grain Washes (All-Grain Mash)

Grain washes produce whiskey, bourbon, and other grain spirits. Requires mashing to convert starch to sugar.

#### Cooked Mash Method (Traditional)

1. **Mill grain** to a fine grist between normal brewing grist and flour. Grocery-store cornmeal/polenta works for bourbon (check: 100% corn, no preservatives or lye treatment).
2. **Gelatinize starch**: Heat grain in water to gelatinization temperature (varies by grain — see grain profiles below)
3. **Saccharification**: Cool to ~63–67°C (145–153°F), add malted barley (10–20% of grist) or commercial enzymes, hold 60–90 min. Target: 66°C (150–155°F) is ideal. Mash is done when it tastes like sweet tea.
4. **Iodine test**: Confirm complete conversion — a drop of iodine on a cooled sample should stay amber (no blue-black starch reaction)
5. **Cool to pitching temp**: 25–33°C (77–92°F)
6. **Ferment**: 2–7 days to completion (~8–10% ABV typical for grain wash)
7. **Enzyme insurance**: Adding ½ tsp powdered amylase per gallon increases yield 10–20% even when recipe doesn't call for it

#### No-Cook Mash Method

An alternative that uses flaked or pre-gelatinized grains with gluco-amylase enzyme added at fermentation temperature. Starch conversion and fermentation happen simultaneously (saccharification + fermentation in parallel).

1. Heat water to 32°C (90°F) — fermentation temperature, not mash temperature
2. Add flaked maize, flaked barley, or other pre-gelatinized grains
3. Add gluco-amylase enzyme and yeast together
4. Ferment normally — enzyme converts starch to sugar as yeast consumes it

**Character difference**: No-cook mashes produce different flavor profiles than cooked mashes. More commonly used in sour mash recipes.

#### Sour Mash Process

Most commercial bourbon and many whiskeys use sour mashing for consistency and flavor:

- **Backset**: Reserve liquid from the boiler after distillation (the spent wash). Use a **minimum 25% backset** in the next batch.
- The acidic, mineral-rich backset lowers starting pH, inhibits spoilage bacteria, and adds distinctive flavor character.
- **Alternative (pre-souring)**: Pitch Lactobacillus bacteria first, wait several hours to a full day before adding yeast. Bacteria lower pH quickly, producing different acid profiles than yeast alone. Longer pre-souring produces more dramatic acid/ester effects, but beyond one day can produce unpleasant salty/fermented-noodle notes.
- **Bacterial culture sources**: Yogurt, cheese-making cultures, probiotic tablets, homebrew shop cultures

### Fruit Washes (Brandy/Eau de Vie)

Fruit washes for brandy use juice or whole crushed fruit. See `modules/wine-science.md` and `modules/country-wine.md` for fermentation details.

### Grain Flavor Profiles for Distilling

| Grain | Flavor Contribution | Starch Content | Diastatic Power | Gelatinization Temp | Notes |
| --- | --- | --- | --- | --- | --- |
| **Barley (malted)** | Malty, biscuity | 58–63% | 100–160°L | 60–65°C (140–149°F) | Self-converting; provides enzymes for other grains |
| **Barley (2-row)** | Clean malt base | 58–63% | ~140°L | 60–65°C (140–149°F) | Standard base malt; high extract |
| **Barley (6-row)** | Grainy, slightly huskier | 55–60% | ~160°L | 60–65°C (140–149°F) | Higher enzyme content; converts adjuncts |
| **Corn/Maize** | Sweetness, body, smoothness | 70–75% | 0 (unmalted) | 65–75°C (150–167°F) | Requires cooking or exogenous enzymes |
| **Rye** | Spicy, peppery, grassy | 55–65% | Varies | 60–70°C (140–158°F) | Very sticky when mashed; use rice hulls |
| **Wheat** | Smooth, gentle, bready | 65–70% | ~80°L (malted) | 58–64°C (136–147°F) | Supporting grain; softens spirit character |
| **Oats** | Smooth, silky, round | 55–60% | Low | 53–60°C (127–140°F) | Counteracts hard water effects |
| **Rice** | Light, clean, neutral | 75–80% | 0 (unmalted) | 70–80°C (158–176°F) | Requires cereal mash; very high starch |

### Fermentation for Distillers

Distilling fermentation differs from brewing in several key ways.

#### Yeast Selection

- **Ale yeasts** (Saccharomyces cerevisiae, top-fermenting) are preferred for most whiskeys — they produce a wider range of volatile acids and esters that survive distillation and contribute complexity.
- **Lager yeasts** produce fewer esters, resulting in simpler whiskey character.
- **Turbo yeast** and **champagne yeast** produce higher ABV but at the expense of flavor — suitable for fuel or sugar-wash neutral spirits, not for whiskey.
- **Specific strain**: Lalvin ICV-D21 produces high levels of ethyl heptanoate (cherry note) — the dominant ester in commercial bourbon.
- **Belgian ale yeast** is a good starting point for single malt whiskey — high ester production.
- **Baker's yeast** works adequately (even Laphroaig uses baker's yeast).

#### Temperature and Duration

Unlike brewing, **hot fermentation is often desirable** for whiskey — higher temperatures produce more esters:

| Spirit | Fermentation Temp | Duration | Notes |
| --- | --- | --- | --- |
| Bourbon | 29–32°C (85–90°F) | 2–4 days | Ferment hot for maximum ester production |
| Rye | Room temp | 2–3 days | Distill as soon as yeast weakens; spoilage risk after day 3 |
| Irish whiskey | Room temp | 2–3 days | — |
| Single malt | Room temp | 2–6 days | Longer fermentation for complexity |
| Sugar wash | 20–25°C (68–77°F) | 7–14 days | Lower temp for cleaner fermentation |

- **Maximum safe temp**: Below 35°C (95°F) — above this, yeast risk dying.
- **Starting sugar**: Target 6–10% potential alcohol. Over 10% can quickly kill yeast. Under 6% indicates a problem.
- **Completion signs**: Cap sinks back into mash, bubbling slows dramatically, potential alcohol reads below 2%.

#### Bacterial Cultures for Flavor

Some whiskey recipes deliberately include **Lactobacillus** bacteria to produce acids that later esterify into fruity/floral flavors during aging:

- **Dosing**: 1–2 tsp yogurt or cheese-making culture per gallon
- **Effect**: Bacteria produce lactic acid and other organic acids; during barrel aging, these acids combine with alcohols to form fruity esters
- **Pre-souring**: Pitching bacteria hours before yeast creates more dramatic acid profiles
- **Caution**: If bacteria dominate for more than 1 day before yeast, unpleasant salty/fermented-noodle flavors may develop

---

## 4. The Spirit Run

### Planning Your First Run

**Mental preparation**: A distillation run requires 2–5 hours of constant attention. Never leave a running still unattended. Plan to distill when alert and undistracted. If you ever need to step away — turn it off.

**Pre-run checklist**:

1. **Location**: Well-ventilated area. Gas heat requires open doors/windows and a CO detector. Electric heat requires GFCI-protected circuits rated for the load.
2. **Water supply**: Non-potable water is fine for cooling. Run a hose from tap to condenser.
3. **Hot water disposal**: Condenser output reaches 70–82°C (160–180°F). Collect in metal containers. Do not pour on plants or into plastic drains.
4. **Stillage disposal**: Post-run liquid is hot and acidic. Allow to cool. Do not leave in copper vessels.
5. **Collection containers**: Prepare 20–30% of your wash volume in collection capacity. Use glass or stainless jars.
6. **Fire safety**: Extinguisher within reach. No smoking. No open flames.
7. **Flour seal**: Mix flour and water 3:1 (bread dough consistency), roll into 1.3 cm (½") logs. Apply to joints when still reaches near-untouchable temperature.
8. **Dry run**: Practice the physical setup — assembly, hose routing, jar placement, jar-swapping choreography — before heating anything.

### Cleaning and Seasoning a New Still

Before distilling spirits through a new still:

1. **Vinegar run**: Charge with 50/50 vinegar and water. This tests for leaks without involving alcohol. Run 20–30 minutes after output starts. Apply flour seals; verify zero leakage. Monitor condenser: cool at bottom, warm-to-hot at top = correct balance.
2. **Sacrificial run**: Use an inexpensive sugar wash. Run a full distillation to purge residual manufacturing oils, flux residue, and vinegar. Discard the output — it is not for consumption.
3. After the sacrificial run, the still is ready for quality production.

### Stripping Run

A stripping run is a fast, rough first distillation done **without making cuts**. Its purpose is to separate alcohol from the bulk wash before a more careful spirit run.

- Run at high heat for maximum throughput
- Collect everything in a single container
- Stop when output drops below ~10–20% ABV
- The result is called **low wines** (typically 25–35% ABV)
- Multiple stripping runs can be combined into a single charge for the spirit run

### Spirit Run (Second Distillation)

The spirit run is done slowly and carefully, with cuts separating the distillate into fractions.

**Process**:
1. Charge the still with low wines (dilute to ~40% ABV if higher)
2. Add boiling chips to promote smooth boiling
3. Heat slowly — bring to near boiling (78–100°C depending on charge strength)
4. Start condenser cooling when temperature approaches boiling
5. When distillate begins dripping, **reduce heat** to a steady, moderate flow
6. Collect in numbered small jars (see jar technique below)
7. Make cuts based on sensory evaluation

**Timeline** (approximate for 25L still):

| Stage | Vapor Temp | Output ABV | Duration | Action |
| --- | --- | --- | --- | --- |
| Heating | Ambient → 78°C | — | 30–60 min | Start condenser when temp rises |
| Foreshots | ~78°C | ~82%+ | First 150 mL | **Discard always** |
| Heads | 78–80°C | 80–82% | Varies | Collect separately; save as feints |
| Hearts | 80–86°C | 80% → 60% | 60–120 min | Primary product |
| Tails | 86–96°C | 60% → 10% | 30–60 min | Collect separately; save for re-distillation |
| End | >96°C | <10% | — | Stop collection; turn off heat |

### Making the Cuts

**The most critical skill in distillation.** Cuts improve dramatically with practice. Temperature provides a guide but **sensory evaluation always takes priority** — every still, charge, and recipe behaves differently.

#### Foreshots
- **Volume**: ~30 mL per gallon of wash (minimum 125 mL per 19L/5-gal wash)
- **Pot still**: Collect and discard at least 125 mL (4 oz) per 5-gallon wash
- **Reflux still**: Discard first 30–90 mL (1–3 oz) — the column concentrates volatiles into a smaller foreshots fraction
- **Contains**: Acetone, methanol, ethyl acetate, and other low-boiling-point compounds
- **Character**: The very first drops may smell deceptively sweet and rich — but these are the most dangerous compounds
- **Action**: **ALWAYS DISCARD** — never re-distill, never consume, never blend back
- **Use**: Solvent or cleaning agent only

#### Heads
- **ABV range**: ~82–80% (from a 40% low wines charge)
- **Expected volume**: 2–3 liters from three stripped 25L sugar washes
- **Contains**: Methanol, acetone, ethyl acetate mixed with ethanol
- **Character**: Sharp, biting taste with potential sweet and buttery notes but a solvent-like sting. Blamed for harsh hangovers.
- **Action**: Collect separately. Save in a "feints" container for reprocessing in a future all-feints run. Do not discard — significant alcohol remains.

#### Hearts
- **ABV range**: ~80% dropping to 60–50% (varies by spirit type)
- **Character**: Very clean tasting and smelling, without the chemical bite of heads, with good flavor character
- **Cut widths by spirit style**:
  - **Vodka / neutral**: Strict, narrow cut (~80–70% ABV) — purity over flavor
  - **American whiskey**: Medium cut
  - **Bourbon / rye**: Medium to wide
  - **Highland / Islay Scotch**: Wide cuts — include some heads/tails character
  - **Jamaican rum**: Wide cuts biased toward tails (funky ester character)
  - **Brandy / fruit spirits**: Medium cut to preserve fruit character
- **Action**: This is your product. The foundation for blending and finishing.

#### Tails
- **ABV range**: Below ~60% (or 50% for wider cuts), down to 10–20%
- **Character**: Wet dog, wet cardboard, damp socks. Increasingly bitter with late notes of dirty water. May show oily film on surface or crystalline formations after sitting.
- **Contains**: Fusel oils (amyl alcohol, butanol), furfural, heavier esters
- **Hidden value**: Contains deeply flavorful compounds. Small amounts blended back into hearts can add complexity — especially for whiskey and rum.
- **Action**: Save with heads in feints container for re-distillation. Stop collecting when output tastes like dirty water (~10–20% ABV).

### The Jar Technique (Beginner's Method)

Collecting into many small numbered jars makes cut decisions easier and reversible.

1. Prepare 10–20 jars of 250–500 mL each (mason jars work well)
2. Number them sequentially
3. Collect the entire run, switching to the next jar at regular intervals (every 50–250 mL depending on still size)
4. After the run, cover each jar with a coffee filter (not a lid) and let rest 1–2 days — volatile undesirable compounds will partially evaporate
5. **Evaluate each jar** using the tasting protocol below
6. Decide which jars are hearts, which are heads/tails
7. Blend selected jars together

This approach separates the distillation from the cutting decision, reducing pressure during the run.

### Tasting Protocol for Cuts

1. Dilute each sample to 35–40% ABV with clean water
2. Swirl gently 2–3 times
3. **Nose first**: Harsh solvents = heads territory. Wet cardboard = tails territory. Clean and sweet = hearts.
4. **Taste**: Sip a small amount. **Spit, do not swallow.** Rinse mouth between samples.
5. Never make cut decisions while intoxicated
6. Work from the center outward — identify the cleanest hearts jars first, then decide how many adjacent jars to include

### Blending Strategy

After identifying your hearts, you can add complexity by incrementally blending in small amounts of heads or tails:

1. Start with your cleanest hearts as the base
2. Trial-blend in a small glass before committing to the batch
3. Add heads or tails one teaspoon at a time
4. Heads additions add: fruity, floral, or estery notes (but also solvent character if overdone)
5. Tails additions add: body, depth, grain character (but also oily/bitter notes if overdone)
6. For whiskey and rum, wider hearts cuts (including more tails) are traditional

**Recovery**: If you make a mistake in blending, you can re-distill the entire batch (minus foreshots). Add water to dilute to ~40% ABV and run it again. This is one of distilling's great advantages over brewing.

### Feints Management

"Feints" are the combined heads and tails collected across multiple runs. Over time, you accumulate a feints container.

- Run an **all-feints distillation** periodically to recover alcohol
- Feints runs produce surprisingly good hearts if done slowly with careful cuts
- Always discard foreshots from feints runs
- Some distillers add feints to the next stripping run instead of running separately

### Developing a Flavor Profile

Flavor in spirits comes from multiple stages:

| Stage | Flavor Influence |
| --- | --- |
| **Raw materials** | Grain type, fruit variety, sugar source |
| **Fermentation** | Yeast selection, temperature, esters, pH, open vs. closed fermentation |
| **Still type** | Pot still retains wash character; reflux strips toward neutral |
| **Distillation ABV** | Higher collection ABV = less flavor; lower = more character |
| **Cut width** | Wider cuts = more complexity (and more risk of off-flavors) |
| **Aging** | Wood type, char level, time, temperature variation |

**Spirit character by still type and distillation count**:
- Pot still, single distillation: Heavy, full-bodied (e.g., Jamaican rum)
- Pot still, double distillation: Medium body (e.g., Scotch single malt)
- Pot still, triple distillation: Light, smooth (e.g., Irish whiskey)
- Reflux, <8 plates: Light to medium flavor (versatile for flavored spirits)
- Reflux, packed column to 90%+: Very light, approaching neutral (vodka base)

**Beginner's path**: Start with sugar wash runs to learn your still's behavior. After 3–6 runs, move to a simple grain wash or molasses rum. Develop your palate by tasting each fraction carefully. Keep detailed notes.

---

## 5. Gin Production

### Legal Definition (EU/UK)

**London Dry Gin** must:
- Be made from alcohol of agricultural origin
- Have all flavoring from re-distillation with natural plant materials
- Distillate must be at least 70% ABV
- No added sweetening (>0.1 g/L sugar)
- No colorants or additives (except water)
- Minimum 37.5% ABV final strength

### Production Methods

#### 1. One-Shot Method (London Dry)
The gold standard—what goes into the still is what comes out.

**Process**:
1. Add neutral spirit + water (40-60% ABV) to kettle
2. Add all botanicals to wash or gin basket
3. Optional: Macerate for 2-24 hours
4. Distill, collecting hearts only
5. Dilute to bottling strength (typically 40-47% ABV)

**Advantages**: Purest expression of botanicals
**Challenge**: Recipe must be perfect—no post-distillation adjustments

#### 2. Concentrate Method
Create a highly concentrated botanical distillate, then dilute with neutral spirit.

**Process**:
1. Distill with heavy botanical load
2. Collect concentrated distillate
3. Blend with additional neutral spirit
4. Dilute to bottling strength

**Advantages**: More economical; consistent batches
**Note**: Still qualifies as London Dry if no other additions

#### 3. Compound/Macerated Gin
Botanicals steeped in spirit without redistillation.

**Process**:
1. Steep botanicals in neutral spirit (37.5-60% ABV)
2. Macerate for hours to weeks
3. Filter and bottle

**Characteristics**:
- Oilier mouthfeel
- Different flavor profile than distilled
- Cannot be labeled "Distilled Gin" or "London Dry"

#### 4. Vapor Infusion
Botanicals held above the wash; vapors pass through them.

**Process**:
1. Place botanicals in gin basket in column
2. Alcohol vapors pass through, extracting oils
3. Collect distillate

**Characteristics**:
- Cleaner, subtler flavors
- Lighter botanical character
- Easier still cleaning

### Gin Botanicals

**Required**: Juniper must be predominant (recommend ≥50% by weight)

| Botanical | Flavor Contribution | Typical Amount (2L wash) |
|-----------|---------------------|--------------------------|
| **Juniper berries** | Pine, resinous, gin character | 30g |
| **Coriander seed** | Citrus-spice, earthy depth | 2g |
| **Angelica root** | Earthy, binding agent | 1 tsp powder |
| **Citrus peel** | Bright, fresh citrus | 1×1cm piece |
| **Orris root** | Floral, fixative | 0.5 tsp |
| **Cardamom** | Warm, aromatic spice | 2-3 pods |
| **Cassia/Cinnamon** | Warm, sweet spice | Small piece |
| **Liquorice root** | Sweet, round mouthfeel | 0.5 tsp |

**Botanicals release different flavors than expected when distilled**—always test individually before combining.

### Designing Your Gin

**Recommended approach**:
1. **Design flavor profile first** (not botanical list)
   - Example: "Juniper-forward with floral depth and citrus brightness"
2. **Select botanicals to achieve profile**
3. **Start with 3-5 botanicals**—add complexity gradually
4. **Test single botanicals** to understand their distilled character
5. **Record everything**—exact weights, times, temperatures

### Gin Styles

| Style | Character | Botanical Approach |
|-------|-----------|-------------------|
| **London Dry** | Juniper-forward, dry, classic | Traditional; juniper dominant |
| **Plymouth** | Slightly sweeter, earthy | More root botanicals |
| **Old Tom** | Sweeter, botanically intense | Sugar added; historical style |
| **Contemporary** | Complex, other flavors prominent | Many botanicals; creative profiles |
| **Navy Strength** | 57%+ ABV; intense | Same botanicals, higher proof |
| **Western Dry** | Less juniper-forward; other botanicals prominent | Creative, modern profiles |
| **Sloe Gin** | Sweet, fruity (15–40% ABV) | Sloe berries macerated post-distillation; technically a liqueur |

---

## 6. Genever (Jenever)

Genever is the original juniper spirit — the ancestor of modern gin. While gin evolved toward neutral-spirit-plus-botanicals, genever retains its **malt wine** base, giving it a richness and grain character that bridges the worlds of gin and whiskey.

### History

The first written genever recipe dates to 1522 (Phillipus Hermanni, Antwerp). Originally, genever was simply malt wine — a pot-distilled grain spirit. Juniper and other botanicals were added to mask the rough character of early distillation. After the invention of the continuous still in the 1830s, clean neutral spirit became available, and genever evolved into a blend of malt wine and botanical-infused neutral spirit.

### Production: Three Components

Genever is made by blending three separately produced components:

#### 1. Moutwijn (Malt Wine)

The heart of genever. A grain mash of **rye, corn, and malted barley** (sometimes wheat) is fermented and then distilled **three or four times** in pot stills:

| Distillation | Name | Result |
| --- | --- | --- |
| First | Ruwnat | Rough distillate from stripping column |
| Second | Enkelnat | Pot still redistillation |
| Third | Bestnat / Moutwijn | Final malt wine, 46–48% ABV |
| Fourth (optional) | Korenwijn | Luxury malt wine for premium genever |

The relatively low distillation strength (46–48% ABV) retains malty, grainy flavors from the base ingredients — this is what distinguishes genever from gin.

**Typical moutwijn grain bill**: Roughly equal parts rye, corn, and malted barley. Some producers add wheat.

#### 2. Botanical Distillate

Neutral grain spirit (often wheat-based or sugar beet-based) is redistilled with botanicals, similar to London Dry gin production.

**Key botanicals**:
- **Juniper berries** — required and defining (quantities vary widely between producers)
- Coriander, angelica root, caraway, orris root, licorice
- Dutch producers tend to use more botanicals than Belgian
- **Notable absence**: Citrus peel is rarely used in traditional genever (unlike gin)

Some producers make multiple botanical distillates — one with juniper only, another with the remaining botanicals — for more precise blending control.

#### 3. Blending

The moutwijn, botanical distillate(s), and additional neutral spirit are blended according to the distiller's recipe. The blend rests for a few days to marry, is proofed down, and then bottled or transferred to barrels for aging.

### Styles

| Style | Min. Moutwijn | Min. ABV | Max Sugar | Character |
| --- | --- | --- | --- | --- |
| **Jonge (Young)** | ≤15% | 35% | 10 g/L | Lighter, gin-like, bright. Developed 1950s in response to vodka's rise. |
| **Oude (Old)** | ≥15% (typically ~17%) | 35% | 20 g/L | Fuller, malty, grain-forward. Sometimes barrel-aged. Resembles whisky. |
| **Korenwijn (Grain Wine)** | ≥51% (typically ~53%) | 38% | 20 g/L | Richest, most whiskey-like. Netherlands only. Luxury style. |

**Important**: "Oude" and "Jonge" refer to recipe style, **not** age. An "oude" genever may or may not be aged.

### Aging

No genever style requires aging. If aging is mentioned on the label, it must be a minimum of **1 year** in barrels no larger than 700 liters. Aged genever develops woody, smoky notes that overlap significantly with whiskey character.

Common barrel types: Used bourbon barrels, French oak, new oak.

### Home Production Method

1. **Make moutwijn**: Mash a grain bill (~33% each rye, corn, malted barley). Ferment to ~8% ABV. Strip run, then spirit run in pot still to ~47% ABV. Wide cuts to retain grain character.
2. **Make botanical distillate**: Take neutral spirit (or a clean hearts cut from a reflux still) at ~60% ABV. Macerate juniper, coriander, angelica, and other botanicals for 24+ hours. Redistill on a pot still.
3. **Blend**: Combine moutwijn and botanical distillate. For oude style, use at least 15% moutwijn. Dilute to 35–42% ABV.
4. **Rest**: Bottle and allow to marry for 48 hours to one week minimum before drinking.
5. **(Optional) Age**: Transfer to small oak barrel or add oak spirals for 1–12 months.

### Genever vs. Gin

| Aspect | Genever | Gin |
| --- | --- | --- |
| Base spirit | Malt wine (pot-distilled grain) | Neutral spirit |
| Grain character | Central to flavor | Absent |
| Juniper role | Present but not always dominant | Dominant (especially London Dry) |
| Body | Rich, full, malty | Light, clean |
| Citrus | Rarely used | Common |
| Aging | Sometimes (1+ year) | Rarely |
| Origin | Netherlands / Belgium | England (evolved from genever) |
| Cocktail use | Original spirit in many classic cocktails (Martinez, early Martini) | Modern cocktail standard |

---

## 7. Whiskey Production

### Whiskey vs. Gin: Key Differences

| Aspect | Gin | Whiskey |
|--------|-----|---------|
| Base | Neutral spirit (bought or made) | Fermented grain mash (made) |
| Flavor source | Botanical distillation | Grain, fermentation, aging |
| Aging | None required | Required (usually oak barrels) |
| Distillation | Single rectification | Often double or triple |
| Process | Relatively quick | Months to years |

### Basic Whiskey Process

1. **Mashing**: Convert grain starches to fermentable sugars
2. **Fermentation**: Yeast converts sugars to alcohol (~8-10% ABV wash)
3. **Distillation**: Concentrate alcohol, develop flavor
4. **Aging**: Mature in wooden barrels (legal requirement for most whiskeys)

### US Government Whiskey Requirements

All US whiskies must:
- Be distilled at ≤90% ABV (180° proof)
- Be reduced to ≤62.5% ABV (125° proof) before barrel aging
- Have the aroma, taste, and characteristics generally attributed to whiskey
- Be bottled at ≥40% ABV (80° proof)

---

## 8. American Whiskey Categories

### Bourbon Whiskey

**Legal requirements**:
- Mash bill: ≥51% corn
- Distilled at ≤80% ABV (160° proof)
- Aged in **new charred oak barrels**
- Entered into barrel at ≤62.5% ABV (125° proof)
- Made in the United States (not exclusively Kentucky)
- No minimum aging (though 2 years required for "Straight" designation)
- No added coloring, flavoring, or blending spirits

**History**: Developed by Scotch-Irish immigrants in the late 18th century who adapted their distilling techniques to abundant American corn. The charred barrel requirement emerged organically—legend credits Elijah Craig with accidentally discovering charred barrel aging after a barn fire.

**Sour mash**: Most bourbon uses the "sour mash" process, where a portion of the previous fermentation (stillage/backset) is added to the new mash as a starter, maintaining consistency batch-to-batch and providing optimal pH for fermentation. A "sweet mash" uses only fresh yeast.

**Flavor profile**: Sweet corn notes, caramel and vanilla from charred oak, varying degrees of spice depending on rye content.

### Tennessee Whiskey

**What makes it different**: Lincoln County Process—filtering through thick beds of sugar-maple charcoal before aging. This removes some congeners and creates a distinctively smooth, mellow palate.

**Legal requirements**: Same as bourbon, plus the charcoal filtration step. Must be made in Tennessee.

**Character**: "Same church, different pew" compared to bourbon—similar but noticeably mellower.

### Rye Whiskey

**Legal requirements**:
- Mash bill: ≥51% rye
- Same aging and proof requirements as bourbon

**History**: The first truly American whiskey style. German immigrants brought their rye distilling traditions, particularly in Pennsylvania and Maryland. Rye was the dominant American whiskey style until Prohibition decimated the industry.

**Flavor profile**: Hard-edged, grainy, spicy, drier than bourbon. The pungent character led to its decline during Prohibition when drinkers shifted to lighter spirits.

**Current status**: Revival among craft distillers and cocktail enthusiasts who value its backbone in mixed drinks like the Manhattan and Sazerac.

### Corn Whiskey

**Legal requirements**:
- Mash bill: ≥80% corn
- **No aging required** (or aged in uncharred or used barrels)
- If aged, must be in uncharred oak or used barrels

**History**: The precursor to bourbon—what Scotch-Irish farmers produced for family consumption or barter. When excise taxes arrived during the Civil War, much production went underground as moonshine.

**Character**: Clear, unaged spirit with corn sweetness. Now marketed as an alternative to vodka with more flavor character.

### Wheat Whiskey

**Legal requirements**:
- Mash bill: ≥51% wheat
- Same aging requirements as bourbon

**Character**: Softer, rounder, breadier than rye. Wheat's softening influence is also used in "wheated bourbons" where wheat replaces rye as the secondary grain.

### Blended American Whiskey

**What it is**: One or more straight whiskeys blended with neutral grain spirits. The taste and quality varies by the ratio of straight whiskey to neutral spirit.

**History**: Became popular after WWII when distillers used blending to stretch limited straight whiskey supplies. Declined as consumers seeking lighter spirits migrated to vodka.

### Mash Bill Science

**Grain contributions to whiskey flavor**:

| Grain | Flavor Contribution | Role in Mash |
|-------|---------------------|--------------|
| **Corn** | Sweetness, body, smooth texture | Base grain in bourbon (≥51%) |
| **Rye** | Spice, dryness, peppery bite | Adds complexity; dominant in rye whiskey |
| **Wheat** | Softness, breadiness, gentle sweetness | Softens; used in "wheated" bourbons |
| **Malted barley** | Maltiness, enzymatic conversion | Provides enzymes; always included (5-15%) |

**High-rye bourbon** (15-35% rye): More spice, bite, complexity
**Wheated bourbon** (wheat replaces rye): Softer, sweeter, rounder

**Example mash bills**:
- Classic bourbon: 70% corn, 15% rye, 15% malted barley
- Wheated bourbon: 70% corn, 16% wheat, 14% malted barley
- High-rye bourbon: 60% corn, 35% rye, 5% malted barley
- Rye whiskey: 95% rye, 5% malted barley
- Monongahela rye: 80%+ rye, remainder malted barley
- Maryland rye: 51–65% rye, corn or wheat tempering grain, malted barley

### Regional Rye Styles

**Monongahela (Pennsylvania) Rye**: The original American rye style, named after the Monongahela River valley. Uses **80%+ rye** with wide cuts that include significant heads and tails character. The result is bold, aggressive, intensely spicy — "a punch in the face" as home distillers describe it. This style is experiencing a craft revival.

**Maryland Rye**: A gentler rye tradition. Uses the legal minimum 51% rye tempered with corn or wheat, producing a spirit that is spicy but more approachable. Historically, the distinction was: Pennsylvania rye knocked you down; Maryland rye shook your hand firmly.

### Moonshine and Unaged Spirits

"Moonshine" has no TTB legal definition. It historically refers to any illegally produced spirit, but is now used commercially as a marketing term for unaged spirits.

| Style | Base | Character |
| --- | --- | --- |
| **Corn moonshine** | 80–100% corn, 5–20% malted barley for enzymes | Sweet, smooth, corn-forward. Popular base for flavored products. |
| **Sugarshine** | 100% refined white sugar | Sweet with minimal other flavor. Essentially unaged vodka. |
| **Sugarhead** | Sugar + flavoring agent added during fermentation | Flavoring can be fruit, grain, spices, etc. The "Uncle Jesse" method (UJSSM) is a well-known sour mash sugarhead technique. |

**UJSSM (Uncle Jesse's Simple Sour Mash)**: A popular home distiller recipe that creates a corn-flavored spirit from sugar using a sour mash technique — backset from the previous fermentation is added to the new wash along with sugar and cornmeal. This produces a spirit with corn character at a fraction of the grain cost.

### Home-Scale Whiskey Recipes

The following recipes are scaled for small (1-gallon) batches on a pot still. All recipes use the cooked mash method unless noted otherwise: heat water to 160°F, stir in grains, hold at 152–155°F for 1–2 hours, cool to 92°F, pitch yeast. Distill with grain-in (including lees from fermentation bucket) for maximum flavor.

#### Bourbon (1 Gallon)

| Ingredient | Amount |
| --- | --- |
| Water | 1 gallon |
| Ground cornmeal/polenta (untreated, 100% corn) | 2 lbs |
| Cracked malted barley | ½ lb |
| Cracked rye berries | ¼ lb |
| Wheat flakes | ¼ lb |
| Yeast: Lalvin ICV-D21 (for cherry/ethyl heptanoate ester production) | 1 packet |

- Ferment **hot** (85–90°F) for 2–4 days
- Strip run to ~30% ABV low wines
- Spirit run: discard 1 Tbsp heads per gallon of mash, collect hearts to 68–75% ABV
- Age in heavily charred new American oak (~20 seconds yellow flame)
- **Variations**: Increase rye at expense of wheat for high-rye bourbon; replace rye with wheat for wheated bourbon
- **Entry proof**: Dilute to 55% ABV before barreling

#### American Rye (1 Gallon)

| Ingredient | Amount |
| --- | --- |
| Water | 1 gallon |
| Cracked rye berries | 2 lbs |
| Cracked malted barley | ½ lb |
| Cracked malted rye | ½ lb |
| Powdered amylase enzyme | ½ tsp |
| Ale yeast | 1 packet |
| Yogurt or cheese-making culture | 2 tsp |

- Add Lactobacillus culture with yeast — protects against rye's spoilage bacteria that emerge around day 3
- Ferment at **room temperature** for 2–3 days. Distill as soon as yeast activity weakens.
- Spirit run: collect hearts at 60–72% ABV (by taste)
- Age in heavily charred new American oak
- **100% rye malt variant**: Replace all grains with cracked rye malt. Extremely spicy, virtually extinct commercially. Add amylase and Lactobacillus.
- **Lactic acid tip**: Heavy Lactobacillus dosing produces ethyl lactate (dairy cream flavor) during aging

#### Irish Pure Pot Still (1 Gallon)

| Ingredient | Amount |
| --- | --- |
| Water | 1 gallon |
| Cracked barley (unmalted) | 1½ lbs |
| Cracked malted barley | 1½ lbs |
| Ale or lager yeast | 1 packet |
| Yogurt or cheese-making culture | 1 tsp |

- **Distill as wort, not mash**: After mashing, strain grain from liquid (lautering). Wash grain bed twice (first at 165°F, second at 180°F). Combine washings with initial wort.
- Ferment at room temperature for 2–3 days
- **Triple distillation**: Strip run → spirit run (collect at 55–70% ABV) → third run (collect at 80–90% ABV)
- Age in lightly toasted ex-bourbon or ex-white wine casks
- **Entry proof**: Dilute to 62.5% ABV before barreling

#### Single Malt — Unpeated (1 Gallon)

| Ingredient | Amount |
| --- | --- |
| Water | 1 gallon |
| Cracked malted barley | 3 lbs |
| Cracked peated malted barley (40 ppm) | 1/10 lb (~45 g) |
| Ale yeast (try Belgian ale yeast for high ester production) | 1 packet |
| Yogurt or cheese-making culture | 1 tsp |

- **Distill as wort** (strain and lauter as for Irish whiskey)
- The small amount of peat triggers a chemical reaction that produces characteristic honey notes
- Ferment at room temperature for 2–6 days (longer = more complexity from bacterial fermentation)
- Spirit run: collect hearts at 55–72% ABV
- Age in ex-bourbon, ex-sherry, or ex-wine casks
- **Peated variant**: Replace all barley with 20–40 ppm peated malted barley

### Oak Species for Whiskey Aging

Different oak sub-species contribute distinct flavor profiles. How the oak is toasted or charred has as much impact as the species itself.

| Oak Species | Flavor Character |
| --- | --- |
| **American (Q. alba)** | Strong vanilla, woody resin, light brown spice, tannic |
| **French (Q. robur/petraea)** | Strong cinnamon, lots of brown spice, light vanilla, moderate tannin |
| **Limousin** | Very strong vanilla, some brown spice |
| **Hungarian** | Vanilla and earthy chocolate notes, peppery |
| **Mongolian (Q. mongolica / Mizunara)** | Caramel vanilla, floral, aromatic (also: sandalwood, incense, coconut) |

#### Toasting and Charring Levels

Measured by seconds of yellow flame from a propane torch after the wood ignites:

| Level | Yellow Flame | Character |
| --- | --- | --- |
| **Light toast** | Flash only (extinguish immediately) | Strong caramel, praline, cashews |
| **Medium toast** | 5 seconds | Praline, light almonds, sweet |
| **Heavy toast** | 10 seconds | Rubbery, slightly bitter |
| **Light char** | ~15 seconds (wood partially blackened) | Sweet, almonds, desserts, slightly smoky |
| **Heavy char** | ~25 seconds (wood blackened and splitting) | Dark barrel-char, almonds, desserts, smoke, dark caramel |
| **Over-charred** | 30+ seconds | Rancid butter — **ruined** |

- **Bourbon pairing**: French oak + high-rye bourbon adds cinnamon character. Used red wine casks + wheated bourbon adds red fruit.
- **Malt pairing**: Test with 5–10 drops of the previous cask contents in a dram of your whiskey before committing a full batch.

#### Barreling Proof

| Spirit | Entry Proof |
| --- | --- |
| American whiskey (bourbon, rye) | 55% ABV (110 proof) |
| Malt whiskey, Irish whiskey | 62.5% ABV (125 proof) |
| General optimal (Morris) | 60–62% ABV (120–124 proof) |

Above 62% ABV, harsh tannin extraction increases. The US legal maximum for barrel entry is 62.5% ABV (125 proof).

#### Aging in Glass (Small-Scale Alternative)

When barrel aging is impractical, age in glass bottles with oak cubes:

- Add **3 oak cubes (~1 cm each)** per 750 mL bottle
- Leave headspace in the bottle for air
- Periodically open the bottle to introduce fresh oxygen, then shake to aerate
- Optionally pre-soak oak cubes in sherry, wine, or other spirits to simulate used-cask aging
- This method provides extraction and (with periodic aeration) some ester formation, but lacks the continuous micro-oxygenation of a barrel

#### Rapid Aging (Freeze-Thaw Cycling)

Barrel aging is driven partly by temperature-induced movement of spirit in and out of wood pores. This can be accelerated on a small scale:

1. Place spirit (in barrel or with oak alternatives) in a **freezer** for ~2 weeks (simulates winter — wood pores close, push spirit out)
2. Move to a warm room or closet (simulates summer — wood pores open, absorb spirit)
3. Repeat several cycles

This does not fully replicate years of warehouse aging but produces a meaningful effect, especially on small barrels or oak alternatives.

---

## 9. Scotch Whisky

### Categories

**Single Malt Scotch**: 100% malted barley, from a single distillery, pot still distilled, aged minimum 3 years in Scotland.

**Single Grain Scotch**: Mostly unmalted wheat or corn, column still, single distillery.

**Blended Malt**: Multiple single malts blended together (no grain whisky).

**Blended Scotch**: Single malts blended with grain whiskies. Accounts for ~90% of Scotch sales. The malt whiskies provide character while grain whisky provides smoothness.

### Production Specifics

**Malting**: Barley is steeped, germinated, and kiln-dried. In traditional regions like Islay, peat fires provide the heat, infusing the malt with characteristic smoky phenolic compounds measured in **PPM (parts per million)**.
- Unpeated: 0-5 PPM
- Lightly peated: 5-15 PPM
- Heavily peated: 30-50+ PPM (Islay style)

**Distillation**: All Scotch malt whisky is **double distilled** in pot stills (some Lowland distilleries triple distill).

**Cask types**:
- **Ex-bourbon**: Most common; adds vanilla, coconut, caramel
- **Ex-sherry**: Oloroso (rich, dried fruit), PX (very sweet, raisiny), Fino (lighter, nutty)
- **Refill casks**: Less wood influence, allows spirit character to shine
- **Virgin oak**: Rarely used; more aggressive extraction

**Still shape matters**: Tall stills with upward-angled lyne arms produce lighter, more delicate spirits (more reflux). Squat stills with downward arms produce heavier, oilier spirits (less reflux).

### Regional Styles

| Region | Character | Notable Distilleries |
|--------|-----------|---------------------|
| **Speyside** | Elegant, fruity, floral, often sherried | Glenfiddich, Macallan, Glenlivet |
| **Islay** | Intensely peated, maritime, medicinal, iodine | Ardbeg, Laphroaig, Lagavulin |
| **Highland** | Diverse; heathery, robust | Dalmore, Glenmorangie, Oban |
| **Lowland** | Light, grassy, delicate | Auchentoshan, Glenkinchie |
| **Campbeltown** | Briny, oily, complex | Springbank, Glen Scotia |
| **Islands** | Maritime, varied peat | Talisker (Skye), Highland Park (Orkney) |

The distinctive **iodine/medicinal** character of Islay whiskies comes from sea salt permeating the local peat that's used to dry the barley malt.

---

## 10. Irish Whiskey

### Distinguishing Features

**Triple distillation**: Most Irish whiskey is **triple distilled** (vs. double for Scotch), producing a lighter, smoother spirit. Exceptions exist.

**No peat**: Traditional Irish whiskey uses kiln-dried (not peat-smoked) malt, resulting in a cleaner, less smoky profile than Scotch.

**Single Pot Still**: A uniquely Irish style using a mash of **malted barley + unmalted barley**, producing a distinctively creamy, spicy character. This style developed historically to avoid British taxes on malted barley.

### History

Irish monks likely brought distillation to Scotland. By the late 19th century, over 400 brands of Irish whiskey were exported to the US. The industry collapsed due to:
- Slow response to blended Scotch's rise
- American Prohibition closing the export market
- Trade embargoes after Irish independence
- World War II disruptions

By 1966, only three distillers remained, merging into Irish Distillers Company. The modern revival began in 1989 with Cooley Distillery.

### Major Categories

| Type | Production | Character |
|------|------------|-----------|
| **Single Pot Still** | Mixed malted/unmalted barley, pot still | Creamy, oily, spicy |
| **Single Malt** | 100% malted barley, pot still | Clean, fruity |
| **Grain Irish** | Column still | Light, smooth |
| **Blended Irish** | Combination of above | Approachable, mixable |

### Poitín (Irish Moonshine)

Ireland's oldest spirit, predating whiskey. Poitín (poh-CHEEN) was traditionally made in small pot stills from barley, potatoes, or whey, and consumed unaged. Legalized in 1997.

- **Wash**: Mixture of grains (often including unmalted barley), potatoes, or sugar
- **Distillation**: Pot still, typically double-distilled
- **ABV**: 40–90% (traditionally high-proof)
- **Aging**: Usually unaged; some modern producers use oak briefly
- **Character**: Raw, grainy, fiery. Modern craft versions can be surprisingly smooth.

---

## 11. Japanese Whisky

### Origins

Modern Japanese whisky traces to **Masataka Taketsura**, son of a sake brewer, who studied chemistry at Glasgow University and worked at a Speyside distillery (1918-1920). He returned to Japan with a Scottish wife and determination to create world-class whisky.

Taketsura convinced Suntory to begin production based on the Scottish model. He later founded **Nikka Whisky** in 1934.

### Characteristics

- **Scottish model**: Pot still malt whisky and column still grain whisky
- **Subtle peat**: Peat-smoke character is generally more delicate than Scotch
- **Mizunara oak**: Japanese oak (Quercus mongolica) adds distinctive sandalwood, incense, and coconut notes. Difficult to work with (porous, prone to leaking).
- **Blending philosophy**: Emphasis on harmony and balance

### Major Producers

- **Suntory**: Yamazaki (Japan's first malt distillery), Hakushu
- **Nikka**: Yoichi (Hokkaido, peatier), Miyagikyo (Honshu, elegant)

---

## 12. Canadian Whisky

### Production Method

Unique **base + flavoring whisky** approach:
1. **Base whisky**: High-corn column-distilled spirit, aged in used barrels
2. **Flavoring whisky**: Rye-heavy pot still spirit with more character
3. **Blending**: Master blender combines these elements

**Note**: Canadians call their whisky "rye" even though modern mash bills are predominantly corn, wheat, and barley—a holdover from earlier rye-dominant production.

### Legal Requirements

- Aged minimum 3 years in Canada
- May contain up to 9.09% "non-Canadian" spirits (often sherry or bourbon)

---

## 13. World Whiskeys

### Australian Whisky

Scottish, Irish, and American traditions cheerfully mixed. Tasmanian distilleries (Sullivan's Cove, Lark) have won international acclaim. Often aged in ex-wine casks from local vineyards.

### Indian Whisky

**Amrut** and **Paul John** produce well-regarded single malts. Tropical climate accelerates aging dramatically—3-year Indian whisky can taste like 10-year Scotch.

### Taiwanese Whisky

**Kavalan** (founded 2005) produces award-winning single malts. Subtropical climate creates rapid maturation with intense wood extraction.

---

## 14. Vodka

### Definition and Production

**US legal definition**: "Neutral spirits, so distilled, or so treated after distillation with charcoal or other materials, as to be without distinctive character, aroma, taste or color."

**Traditional base materials**:
- **Rye**: Classic Russian and Polish base; considered highest quality
- **Wheat**: Swedish and Baltic preference; clean, slightly sweet
- **Potato**: Creamy, full-bodied; traditional Polish specialty
- **Molasses**: Inexpensive mass-market production

### History

The word "vodka" comes from Russian *voda* (water). Eastern European peoples discovered they could create stable alcoholic beverages by distilling mead, beer, or "freeze-concentrated" wines (where frozen water is removed from fermented beverages).

- **1540**: Czar Ivan the Terrible established first government vodka monopoly
- **1780**: Charcoal filtration invented at a Russian czar's distillery
- **1830s**: Sweden had 175,000+ registered stills for 3 million people

**In America**: Vodka was introduced by Eastern European immigrants but remained niche until Heublein marketed Smirnoff as "White Whisky—No taste. No smell." The Moscow Mule cocktail (vodka + ginger beer) launched its popularity.

### Production Methods

**Pot still vodka**: Retains subtle aromatics and flavor elements from the base ingredient. Must be redistilled (rectified) multiple times to increase proof.

**Column still vodka**: More efficient, produces high-proof neutral spirit in single passes. Standard for commercial production.

**Filtration**: Charcoal filtration removes remaining congeners. Some producers filter through other materials (lava rock, diamond dust) for marketing differentiation.

### Regional Classifications

**Poland**: Graded by purity—*zwykly* (standard), *wyborowy* (premium), *luksusowy* (deluxe)
**Russia**: *Osobaya* (special, exportable quality), *Krepkaya* (strong, 56%+ ABV)

### Carbon Filtration for Neutral Spirits

Carbon filtration ("polishing") removes residual congeners that survive even careful distillation. It is used primarily for vodka and other neutral spirits — **never** filter flavored spirits (whiskey, rum, brandy), as it strips desirable flavor compounds.

**Activated carbon vs. charcoal**: They are different products. Charcoal (as used in the Lincoln County Process for Tennessee whiskey) is burned wood — it removes some harsh congeners but leaves flavor intact. Activated carbon has been processed to create extensive internal pore structures that trap molecules by adsorption. Using charcoal when you need activated carbon (or vice versa) will give wrong results.

#### Carbon Selection

| Parameter | Recommendation |
| --- | --- |
| **Format** | Granular only — not powdered (clogs) or pelletized (poor contact) |
| **Mesh size** | 20×40 (0.4–0.85 mm) is the best balance of flow and effectiveness |
| **Pore type needed** | Meso pores (1–25 nm) — these trap the 2–10 nm congener molecules |
| **Base material** | Coconut shell (mostly micro pores, but effective with slow flow), stone coal (good meso + micro pore mix), or peat (ideal but hard to source and regenerate) |
| **Grade** | Food-grade only — non-food-grade carbon can leach contaminants |

#### Filter Setup

- **Shape**: Round tube, minimum 1.5" (40 mm) inside diameter. Square shapes create void spaces where spirit bypasses the carbon.
- **Volume**: ~100–110 in³ (1.6–1.8 L) of carbon for 2–3 gallons of spirit at 50% ABV
- **Dimensions**: A 1.5" ID tube × 60" long ≈ 106 in³
- **Flow rate**: 1 quart/hour (ideal) to 2 quarts/hour (acceptable). Slower = more effective.
- **Construction**: Food-grade PVC or ABS tube (ABS preferred for ethanol tolerance), large funnel as reservoir, filter paper(s) secured at bottom with stainless hose clamp

#### Filtration Process

1. **Pre-rinse carbon**: Soak in simmering water, stir, pour off — repeat 4–5 times. This removes manufacturing residues and saturates the carbon.
2. **Load tube**: Spoon wet carbon into filter tube, tap sides to settle evenly
3. **Secondary rinse**: Run ~1 gallon of hot water through the loaded filter
4. **Dilute spirit**: Reduce to **no more than 55% ABV** before filtering. Undiluted high-proof spirit is too thin (low density) and channels around the carbon.
5. **Start filtering**: Add spirit to reservoir before water fully drains — never let the liquid level drop below the top of the carbon bed (air gaps destroy filtration efficiency)
6. **Chase with hot water**: When last spirit enters reservoir, follow with hot water to push remaining spirit through. Feel the tube — you can detect the warm water/cool spirit boundary as it moves down.
7. **Capacity**: Expect 2–4 gallons of 50% ABV spirit per 100 in³ of carbon before exhaustion

**Do not** simply add carbon to a jar of spirit and shake — this forces spirit *around* the granules, not *through* the pores.

---

## 15. Brandy

### Types of Brandy

| Type | Base | Character |
|------|------|-----------|
| **Grape brandy** | Fermented grape juice | Aged in oak; amber color |
| **Pomace brandy** | Pressed grape skins/stems | Raw, fruity (grappa, marc) |
| **Fruit brandy** | Fermented fruit other than grapes | Varies by fruit |
| **Eau de vie** | Fruit (unaged) | Clear, intense fruit character |

### Cognac

The benchmark for grape brandy, produced in the Cognac region of France.

**Grape varieties**: Ugni Blanc (primary), Folle Blanche, Colombard—thin, tart, low-alcohol wines perfect for distillation.

**Distillation**: Double distilled in **Charentais alembic** pot stills. The wine is distilled twice; the "heart" of the second distillation becomes cognac.

**Cask aging**: Limousin or Tronçais oak. New oak first (for color and initial mellowing), then transferred to seasoned casks for extended aging.

**Growing regions** (crus):
1. Grande Champagne (highest quality)
2. Petite Champagne
3. Borderies
4. Fins Bois
5. Bons Bois
6. Bois Ordinaires

**Age classifications**:
| Designation | Minimum Age | Typical Age |
|-------------|-------------|-------------|
| VS (Very Superior) | 2 years | 4-5 years |
| VSOP (Very Superior Old Pale) | 4 years | 10-15 years |
| XO (Extra Old) | 10 years | 20+ years |
| XXO | 14 years | 25+ years |

### Armagnac

Older than Cognac, from Gascony in southwest France.

**Key differences from Cognac**:
- **Single continuous distillation** in the unique *alambic armagnacais* (vs. double distillation for Cognac)
- More rustic, assertive character
- Vintage-dated bottlings are common
- Aged in local Monlezun oak (increasingly Limousin as Monlezun becomes scarce)

### Calvados

Apple brandy from Normandy, France.

**Production**: Cider apples (small, tart) fermented to hard cider, then distilled. Best examples from **Pays d'Auge** appellation use pot stills and double distillation.

**Aging**: Oak casks minimum 2 years. Uses cognac-style designations (VS, VSOP, XO, Hors d'Age) though they have no legal standing.

### Other Notable Brandies

**Pisco**: Clear Peruvian/Chilean brandy from Muscat grapes. Double pot-distilled, **not aged**. Base for Pisco Punch and Pisco Sour.

**Grappa** (Italy): Pomace brandy from pressed grape skins. Can be raw firewater or elegant single-varietal artisan spirits. Usually unaged or minimally aged.

**Marc** (France): French pomace brandy, similar to grappa. Marc de Gewürztraminer from Alsace retains the grape's distinctive perfume.

**Brandy de Jerez** (Spain): Aged in solera system using ex-sherry casks, creating rich, slightly sweet brandy. Classifications: Solera (6 months), Reserva (1 year), Gran Reserva (3+ years).

**American brandy**: California produces both commercial (light, mixable) and craft (Cognac-style) brandies. Craft producers like Germain-Robin use traditional Cognac grapes and pot stills.

---

## 16. Rum

### Production Fundamentals

**Base material options**:
- **Molasses**: Byproduct of sugar refining; 50%+ sugar with minerals and trace elements. Used for most rum worldwide.
- **Fresh cane juice** (*rhum agricole*): Pressed sugarcane juice. Produces naturally smoother rum with grassy, vegetal notes.

**Fermentation**: Wild yeasts (traditional) or cultured yeasts. Fermentation length affects flavor—24 hours for light rums, several weeks for heavy rums.

### Production Styles

**Light rum** (Puerto Rican style):
- Column still distillation
- Charcoal filtered
- Aged minimally in used oak
- Clean, vodka-like, mixable

**Heavy rum** (Jamaican style):
- Pot still distillation
- Dunder (dead wash from previous distillation) added for funk
- Extended fermentation for ester development
- Rich, aromatic, assertive

**Rhum agricole** (French Caribbean):
- Fresh sugarcane juice (not molasses)
- Pot or column still
- Terroir-driven like wine
- Grassy, floral, herbal

### Regional Styles

| Region | Character | Notable Producers |
|--------|-----------|-------------------|
| **Jamaica** | Funky, high-ester, aromatic | Hampden, Worthy Park, Appleton |
| **Barbados** | Balanced, refined, approachable | Mount Gay, Foursquare |
| **Martinique** | Agricole, grassy, terroir-driven | Clément, Rhum JM, Neisson |
| **Cuba** | Light, dry, crisp | Havana Club |
| **Puerto Rico** | Light, column-distilled | Bacardí, Don Q |
| **Guyana** | Rich, heavy Demerara style | El Dorado |
| **Haiti** | Pot-distilled, full-flavored, agricole | Barbancourt |
| **Trinidad** | Aromatic, refined | Angostura |

### Rum Classifications

- **Blanco/White/Silver**: Unaged or briefly aged then filtered
- **Gold/Oro**: Lightly aged; color may be from caramel
- **Añejo**: Aged minimum 1 year
- **Dark/Black**: Heavily aged or colored with molasses/caramel
- **Navy rum**: Traditionally high-proof blend; Royal Navy ration was 160° proof diluted with water to make "grog"

**Note**: Unlike Scotch, rum has few regulated age statements. Some producers add sugar post-distillation. Look for "no sugar added" or check independent analyses.

### Cachaça

Brazilian sugarcane spirit, **not technically rum** by Brazilian law.

**Production**: Fresh sugarcane juice fermented and distilled (like agricole). Often aged in native Brazilian woods (amburana, balsam, jequitibá) which impart unique flavors.

**Character**: Grassy, vegetal, distinctive. Base for the Caipirinha cocktail.

---

## 17. Tequila and Mezcal

### Tequila

**Legal requirements**:
- Made from **Blue Weber agave** (*Agave tequilana Weber*)
- Produced in designated regions (primarily Jalisco)
- **100% agave** or **mixto** (minimum 51% agave, remainder cane sugar)

**Production process**:
1. **Harvest**: Jimador cuts the piña (pineapple-shaped agave heart, 25-100 lbs) after 8-10 years of growth
2. **Cooking**: Steam ovens or autoclaves convert starch to sugar
3. **Extraction**: Piñas crushed (traditionally by stone tahona wheel)
4. **Fermentation**: Aguamiel (honey water) fermented with yeasts
5. **Distillation**: Usually double distilled in pot stills
6. **Aging**: Categorized by aging period

**Tequila classifications**:
| Category | Aging | Character |
|----------|-------|-----------|
| **Blanco/Silver** | Unaged or <2 months | Pure agave expression |
| **Reposado** | 2-12 months | Light oak influence |
| **Añejo** | 1-3 years | Significant oak, smoother |
| **Extra Añejo** | 3+ years | Deep oak, cognac-like |

**100% agave vs. mixto**: If bottle doesn't state "100% de agave," it's mixto. All 100% agave tequila must be bottled in Mexico.

### Mezcal

The broader category of Mexican agave spirits (tequila is technically a type of mezcal).

**Key differences from tequila**:
- **Many agave varieties**: Espadín (most common), tobalá, tepeztate, madrecuixe, etc.—each with distinct flavor
- **Traditional pit-roasting**: Piñas cooked in underground earth ovens over wood charcoal, creating the distinctive smoky character
- **Artisanal production**: Often small-batch, traditional methods

**The worm** (*gusano*): Larva of an agave moth, found in some mezcals. Originally a proof-of-potency marker (high alcohol preserves the worm). Top-quality mezcals don't include a worm.

**Primary region**: Oaxaca (though produced throughout Mexico).

### Other Agave Spirits

- **Raicilla**: From Jalisco highlands; different agave varieties, often sweeter
- **Bacanora**: From Sonora; made from wild Pacifica agave
- **Sotol**: Technically not agave—made from Dasylirion (desert spoon); similar production

---

## 18. Liqueurs and Other Spirits

### Liqueurs

**Definition**: Sweetened, flavored spirits. "Liqueur" from Latin *liquifacere* (to dissolve)—referring to dissolving flavorings in spirits.

**Production methods**:
- **Distillation**: Botanicals distilled with spirit (highest quality)
- **Maceration**: Botanicals soaked in spirit, then filtered
- **Infusion**: Similar to maceration; often with heating
- **Percolation**: Spirit repeatedly passed over botanicals

**Categories**:
- **Crèmes**: Single dominant flavor (crème de menthe, crème de cacao)
- **Cream liqueurs**: Dairy cream emulsified with spirit (shelf-stable)
- **Fruit liqueurs**: Fruit-based (Chambord, Cointreau)
- **Herbal liqueurs**: Botanical blends (Chartreuse, Bénédictine)

### Schnapps

Northern European clear or flavored spirits (German *Schnaps*, "gulp"). Made from grain, potatoes, or molasses with virtually any flavoring.

### Anise-Flavored Spirits

| Spirit | Origin | Character |
|--------|--------|-----------|
| **Pastis** | France | Macerated; licorice-forward |
| **Absinthe** | France/Switzerland | Distilled; wormwood, anise, fennel |
| **Ouzo** | Greece | Distilled; drier than pastis |
| **Sambuca** | Italy | Distilled then sweetened |
| **Arak** | Middle East | Distilled from grapes with anise |

**Absinthe** (40–74% ABV): The "Green Fairy." Required botanicals: **grand wormwood** (*Artemisia absinthium*, source of thujone), **anise**, and **fennel**, plus typically hyssop, melissa, and other herbs. Historically banned in the early 20th century due to alleged psychoactive effects (now shown to be greatly exaggerated by temperance advocates). Legal again in most countries.
- **Production**: Macerate botanicals in neutral spirit, then redistill. The distillate is clear ("blanche"). For green absinthe ("verte"), a second maceration with coloring herbs (petite wormwood, hyssop, melissa) produces the characteristic green color.
- **Must louche**: When mixed with water, the essential oils precipitate out of solution, creating a characteristic milky-opalescent appearance. If your absinthe doesn't louche, the botanical extraction was insufficient.
- **Service**: Traditionally diluted 3:1 to 5:1 with cold water, dripped slowly over a sugar cube.

### Amaro

Italian bitter herbal liqueur (25–50% ABV). Made by **tincturing** botanicals in spirit (not redistilling). The base can be NGS, brandy, rum, or blends.

- **Character**: Should be predominantly bitter, not sweet (despite sugar often being added for balance)
- **Ingredients**: Gentian root, wormwood, cinchona bark, artichoke, citrus peel, and dozens of other botanicals
- **Styles**: Range from light and citrusy (Aperol) to intensely bitter and herbal (Fernet-Branca)
- **Service**: Typically served as a digestif, neat or on ice

**Three essential ingredient categories**:
1. **Bittering agents** (at least one required): Gentian root, cinchona bark, wormwood, artichoke leaf, quassia bark, dandelion root
2. **Flavoring botanicals**: Herbs (sage, mint, rosemary, thyme), spices (anise, clove, allspice, cinnamon, star anise), citrus peel, dried fruit, vanilla, cocoa nibs
3. **Base spirit**: High-proof neutral grain spirit (75% ABV / 151-proof ideal); vodka (40% ABV) works but extracts less efficiently

**Production method**:
1. **Grind** botanicals coarsely with mortar and pestle or food processor — rough-crush, not powder
2. **Macerate** ground botanicals in high-proof spirit in a sealed glass jar at room temperature for 3–5 weeks, shaking frequently
3. **Sweeten**: Make simple syrup (equal parts sugar and water by volume, heated until dissolved, cooled). Add to macerated spirit. Rest 2 more weeks, stirring frequently
4. **Filter**: Strain through cheesecloth to remove solids, then fine-filter through coffee filter or fresh cheesecloth
5. **Rest and adjust**: Taste; adjust bitterness (more tincture) or sweetness (more syrup). Final ABV typically 25–35%

**Starter recipe** (Averna-style, ~4½ cups yield):
- 1 tsp anise seeds, 6 sage leaves, 6 mint leaves, 1 tsp fresh rosemary, 1 allspice berry, ½ tsp whole cloves, ½ tsp gentian root (cut, not powdered)
- 3 cups 151-proof NGS (or highest-proof vodka available)
- 1¼ cups sugar + 1¼ cups water (simple syrup)
- Steep botanicals in spirit 3 weeks → add cooled syrup → rest 2 more weeks → filter
- Substitute cinchona bark for gentian if unavailable

**Customization guidance**:
- **More bitter**: Increase gentian/cinchona, add wormwood or quassia
- **More citrusy**: Add dried orange/lemon peel, grapefruit zest
- **More herbal**: Increase sage, add thyme, oregano, bay leaf
- **Darker/richer**: Add cocoa nibs, coffee beans, dried fig, molasses syrup instead of simple syrup
- **Higher complexity**: Use multiple bittering agents; layer flavors by adding delicate botanicals (flowers, fresh herbs) in the final week only

**Shelf life**: 6 months at room temperature. Higher ABV versions last longer.

### Bitters

Descendants of medieval medicinal potions. High-proof spirits infused with roots, herbs, and botanicals. Used as digestifs or cocktail ingredients.

**Types**:
- **Potable bitters / Amari**: Meant for drinking (Campari, Fernet-Branca, Montenegro)
- **Cocktail bitters**: Concentrated flavoring agents dashed into drinks (Angostura, Peychaud's, orange bitters)

### Vermouth

Aromatized, fortified wine (16–22% ABV). Not a spirit per se, but production relies on spirit-based tinctures and fortification — the same techniques as liqueur making.

**Styles**:

| Style | Character | ABV | Typical base |
|-------|-----------|-----|-------------|
| **Dry (French)** | Pale, herbal, crisp | 16–18% | Dry white wine |
| **Sweet/Rosso (Italian)** | Dark, rich, bittersweet | 16–18% | White wine + caramel color |
| **Blanc/Bianco** | Pale, floral, moderately sweet | 16–18% | White wine |
| **Amber/Rosé** | Copper-hued, balanced | 16–18% | Rosé or blended |

**Base wine**: Neutral, not too flavorful — an inexpensive dry white works well (10–14% ABV). Country wines (birch sap, gooseberry, apple) also work as unconventional bases.

**Botanical categories**:
- **Bitter aromatics** (essential — defines vermouth): Wormwood (*Artemisia absinthium* or *A. pontica*), mugwort (*A. vulgaris*), yarrow, tansy, bog myrtle
- **Spicy/aromatic**: Angelica root, coriander, cardamom, conifer needles (fir, spruce, larch), juniper
- **Floral/sweet**: Elderflower, meadowsweet, chamomile, sweet cicely, rose petals
- **Citrus**: Orange peel (dried), lemon zest, grapefruit peel
- **Savory/umami** (optional, unconventional): Dried mushrooms (ceps, chanterelles), seaweed, smoked ingredients

**Wormwood note**: A little goes a very long way. Start with 1–2 g per 750 mL and increase cautiously. Over-extraction produces harsh, undrinkable bitterness.

**Production method**:

1. **Prepare tinctures**: Steep individual botanicals in 40%+ ABV spirit (vodka or NGS) — delicate botanicals (flowers, shoots) for hours to days; robust botanicals (roots, bark, seeds) for days to weeks. Prepare several separate tinctures for blending control
2. **Infuse base wine** (optional): Heat wine to 60–70°C for 15–30 minutes with selected fresh botanicals (lid on to prevent alcohol loss). Do not exceed 78°C. Alternatively, use sous vide at ~70°C for 45–60 minutes
3. **Fortify**: Add tinctures incrementally to the base wine, tasting between additions. Target 16–20% ABV final
4. **Sweeten**: Add simple syrup, honey, caramel syrup, or flavored syrups (elderflower, burdock, angelica) to balance. Dry vermouth needs less; sweet vermouth needs generous sweetening
5. **Clarify**: Strain through muslin or coffee filter. Optional: freeze at −8°C for several days, then rack off clear liquid for complete clarity
6. **Bottle and store**: Refrigerate. Use a vacuum cork to slow oxidation. Best consumed within 2–3 months of opening

**Tips**:
- Build iteratively: prepare a base batch, then split into portions and experiment with different tincture and syrup additions
- Taste frequently during assembly — vermouth is blended to taste, not to formula
- Sweetening level dramatically affects perception of bitterness — add sweetener in small increments

### Aquavit / Akvavit

Scandinavian spirit (40–50% ABV) flavored with **caraway and/or dill** as the defining botanicals, plus fennel, anise, citrus, or cumin. Base is neutral grain spirit or neutral potato spirit.

- **Norwegian style**: Often aged. **Linje aquavit** is aged while crossing the equator by ship — the motion and temperature variation in the hold creates distinctive character.
- **Swedish/Danish style**: Often unaged, lighter, dill-forward.
- **Home production**: Redistill neutral spirit with caraway, dill, and supporting botanicals. Or macerate botanicals in neutral spirit for 1–2 weeks and filter.

### Slivovitz

Central/Eastern European plum brandy (25–70% ABV), particularly associated with Serbia, Croatia, Bosnia, Czech Republic, and surrounding regions. Made from Damson plums or other plum varieties.

- **Production**: Whole plums (including stones) are crushed and fermented, then double-distilled in pot stills
- **Character**: Dry to slightly sweet, strong plum aroma, often fiery
- **Aging**: Not required. Some versions aged in mulberry or oak barrels
- **Note**: The stones (containing traces of amygdalin) are traditionally included during fermentation, contributing a subtle almond note

---

## 19. Safety Considerations

**Never leave a running still unattended.** Constantly monitor cooling water flow, leaks, collection, and temperatures. Work in well-ventilated spaces. Operate sober.

### Methanol Hazards

**Methanol is produced during fermentation** of pectin-rich materials (fruits, especially). Distillation concentrates methanol per liter of distillate, but the total amount of methanol in your distillate equals what was in the wash — distillation does not create new methanol.

**Perspective**: A 90 kg person would need approximately 1,400–4,000 liters of 50% spirit to reach methanol's LD50 — ethanol toxicity is a far greater immediate risk. Proper technique makes methanol poisoning from home-distilled spirits virtually impossible.

**Dangers** (acute methanol poisoning from contaminated sources):
- Severe headache, dizziness, nausea (2–6 hours post-ingestion)
- Temporary or permanent vision loss (2–6 days post-exposure)
- Organ damage, death

**Prevention**:
- **Always discard foreshots**: 50 mL per 20L wash (reflux still) or 100–200 mL (pot still)
- Use properly fermented wash from non-toxic ingredients
- Fruit washes (high pectin) produce more methanol than grain or sugar washes
- On reflux stills, slow collection (~1 drop/second initially) concentrates volatiles in foreshots for cleaner removal
- Never consume the heads fraction

**Real-world methanol poisoning** comes from criminal adulteration (adding industrial methanol to stretch product) or redistilling denatured alcohol — not from careful home distillation.

### Fire and Explosion Risks

**Ethanol burns with a nearly invisible pale blue flame**, making fires extremely difficult to detect.

- Room-temperature spirits ignite at ~50% ABV with an ignition source
- Hot alcohol vapor ignites readily from any spark or flame
- **No smoking** anywhere near the still
- **No open flames** (gas stove pilot lights count)
- Keep a fire extinguisher within arm's reach
- Use **water** to fight alcohol fires (it cools and dilutes the ethanol)
- If vapor is escaping from the condenser: **shut down immediately** — insufficient cooling means flammable vapor is venting into the room

**Pressure hazards**:
- Well-designed stills should not generate significant internal pressure
- **Never seal a still completely** — the system must always vent to atmosphere
- Check outlet tubes and connections for blockages before every run
- Crimped or clogged tubing can cause dangerous pressure buildup and explosions
- Cheap pressure cooker stills with small outlets are particularly prone to clogging
- Consider adding a pressure relief valve to any still that lacks one
- **Post-shutdown vacuum risk**: After turning off heat, the liquid in the kettle remains above ethanol's boiling point and continues producing vapor. Keep cooling water running until the head temperature drops well below 173°F (78°C). Then **open the still** (remove thermometer, loosen still head) to allow airflow — if the system cools while sealed, the condensing vapor creates a vacuum that can **implode** the kettle or column. Always vent before walking away from a cooling still.

### Material Compatibility

Ethanol is a powerful solvent. Using incorrect materials causes dangerous leaching of toxins into the distillate.

**Vapor path** (hot ethanol vapor contact):
- **Use only**: Copper, stainless steel (304 or 316)
- **Never use**: Aluminum (reacts with ethanol), PVC, rubber, silicone (except rated food-grade high-temp silicone), galvanized metal (zinc leaches)
- **Sealing**: PTFE tape or flour paste only. No synthetic gaskets or putty.

**Cold-side storage** (below 15% ABV):
- Acceptable: PET, polyethylene, stainless steel, glass

**Cold-side storage** (above 15% ABV):
- **Glass or stainless steel only**
- Ethanol will leach compounds from most plastics at higher concentrations

**Flour seals**: Mix flour and water 3:1, roll into logs, apply to still joints when hot. Safe, effective, traditional. Do not use silicone sealant or plumber's putty.

### Lead Poisoning

**Never use lead-soldered equipment.** This is the single most dangerous equipment mistake in distilling.

- Automobile radiators are the primary hazard — historical moonshine stills made from car radiators caused documented cases of severe lead poisoning (blood levels 50×–100× normal)
- Lead solder dissolves readily in hot ethanol vapor
- Confiscated radiator stills have tested at 7,400–9,700 µg/L lead (safe limit: <15 µg/L in water)
- **Safe construction**: Use welding, brazing, or silver-bearing solder only (not lead-tin solder)

### Denatured Alcohol Warning

**Never attempt to re-distill denatured alcohol (methylated spirits).** Denaturing agents (pyridine, methyl ethyl ketone, methanol) are selected specifically because their vaporization properties are nearly identical to ethanol. Standard distillation cannot separate them. Consuming re-distilled denatured alcohol causes serious illness or death.

### Ethyl Carbamate (Urethane) Warning

**Avoid urea-containing turbo yeasts.** Ethyl carbamate is a believed carcinogen that forms when urea reacts with ethanol during fermentation and distillation. Some turbo yeasts contain urea as a nitrogen source — these can produce elevated ethyl carbamate levels. If using turbo yeast, check the ingredients for urea or urea-based nitrogen supplements. Non-urea nutrient sources (DAP, organic nitrogen blends) are safer alternatives.

### Ethanol Toxicity

Ethanol itself is toxic in acute quantities:
- **Fatal dose**: 300–400 mL pure ethanol (600–800 mL of 50% spirit) consumed within one hour
- Always sip and spit during tasting for cuts — never swallow more than traces

| BAC Level | Effects |
| --- | --- |
| 0.05–0.15% | Reduced inhibition, slight impairment |
| 0.15–0.30% | Sensory loss, slurred speech |
| 0.30–0.50% | Severe uncoordination, stupor |
| >0.50% | Coma, respiratory depression, death |

### Heating Source Safety

**Electric**: Install GFCI/RCD circuit breakers. Keep electrical connections away from water and spirits. Know where the power switch is for emergency shutdown.

**Gas**: Use a carbon monoxide detector. Maintain excellent ventilation (open garage door or work outdoors). Never position the collection vessel near the burner flame.

### Equipment Safety Summary

- Use food-grade materials only (copper, stainless steel, borosilicate glass)
- No lead solder or fittings — ever
- Check all connections and hoses before heating
- Pressure-test with water before every alcohol run
- Replace worn or degraded hoses and seals regularly
- Keep a logbook of equipment maintenance

---

## 20. Calculations and Measurements

### ABV Measurement

**Alcoholmeter** (specialized hydrometer):
- Calibrated for ethanol, not water
- Usually calibrated to 20°C (68°F)
- Temperature correction required if sample is warmer/cooler

**Temperature correction**: Use distiller's calculator or correction tables

### Dilution Calculations

**To dilute spirit to target ABV**:

```
Final Volume = (Current Volume × Current ABV) ÷ Target ABV
Water to Add = Final Volume - Current Volume
```

**Example**: Dilute 500mL of 75% ABV to 40% ABV
```
Final Volume = (500 × 0.75) ÷ 0.40 = 937.5mL
Water to Add = 937.5 - 500 = 437.5mL
```

### Yield Expectations

| Still Type | Typical Yield (hearts) |
|------------|------------------------|
| 2L development | 600-800mL at 70-80% ABV |
| 25L pot still | 3-5L at 65-75% ABV |
| Commercial | Varies widely |

---

## 21. Record Keeping

**Essential records for every run**:

1. **Wash composition**
   - Spirit type and ABV
   - Water volume added
   - Final wash ABV and volume

2. **Botanicals** (for gin)
   - Exact weights of each
   - Source/supplier
   - Maceration time

3. **Process times**
   - Heat on
   - First distillate
   - Heads cut
   - Tails cut
   - Heat off

4. **Output**
   - Volume of hearts collected
   - ABV of hearts
   - Volume and ABV of tails
   - Tasting notes

---

## 22. Troubleshooting

### Distillation Problems

| Problem | Likely Cause | Solution |
|---------|--------------|----------|
| Cloudy distillate | Temperature too high; water coming over | Reduce heat; improve condenser cooling |
| Low yield | Incomplete distillation; early tails cut | Run longer; taste more frequently for cuts |
| Harsh spirit | Heads in hearts; cut too late | Cut to hearts earlier; discard more heads |
| Oily/bitter | Tails in hearts | Cut to tails earlier |
| Weak botanical flavor | Insufficient botanicals; too much reflux | Increase botanicals; reduce column plates |
| Overpowering single flavor | Botanical imbalance | Reduce dominant botanical; rebalance recipe |
| Burnt taste / smoke from condenser | Wash scorched on bottom of still | Discard and start over. Use lower heat; stir wash; add extra water for fluidity; use steam jacket |
| Blue or green distillate | Copper deposits in condenser | Clean all copper equipment thoroughly and redistill the affected spirit. Not acutely toxic but heavy metals accumulate — do not drink blue/green spirit |
| Paint thinner taste (ethyl acetate) | Excess ethyl acetate production | Age on heavily charred oak — ethyl acetate bonds with phenolic acids from char to form new esters (honey character). Adding a small amount of smoked barley to the mash bill provides additional phenolic acids to accelerate this conversion |
| Pounding hangover | Methanol in heads not fully removed | Increase heads cut (from 1 to 2 tablespoons per gallon of mash). Also try distilling more slowly during the early phase of the spirit run to better separate methanol |
| Column surging/flooding | Column choking — packing too tight or heat too high | Reduce heat input. Repack column with looser packing. See choking note under Still Design. |

### Fermentation Problems

| Problem | Likely Cause | Solution |
|---------|--------------|----------|
| Fermentation never started | Dead yeast (heat-damaged packet) or preservatives on grain | Re-pitch fresh yeast. Verify grain is untreated. |
| Stuck fermentation (stopped above 2% potential alcohol) | Lack of oxygen; starting gravity too high; yeast stress signals | Splash mash between buckets to oxygenate, re-pitch fresh yeast. If sugar was too high, dilute with warm water. If yeast death signals are present, remove mash from lees and re-pitch in a clean vessel (last resort). |
| Vomit smell | Spoilage bacteria (often anaerobic) | If caught early: splash between buckets to introduce O₂ (many spoilage bacteria are strict anaerobes). If strong: discard. Prevent: sanitize everything, pitch 2–3× yeast with friendly Lactobacillus. Note: butyric acid (vomit smell) can form strawberry esters during barrel aging if present in trace amounts. |
| Rancid cheese smell | *Brettanomyces* contamination | Start over. Prevent: pitch 3× yeast immediately at 92°F; speed up wort cooling to minimize Brett's window. |
| Buckwheat soup taste in distillate | Bacterial fermentation went too long | Distill sooner — limit total fermentation to 2–4 days for whiskey. |
| Alcohol burn, too hot | High acid : ester ratio | Will improve with aging. Next batch: use a yeast strain that produces more esters; ensure 4–5% amino acid content in mash (add amino supplements or ferment with grain in). |
| Gray/black mold on fermentation cap | Mold growth on exposed grain cap | If caught early: punch cap back into mash to kill mold. If extensive: discard (causes swampy taste). Prevent: punch cap down 2× daily. |

---

## References

- Hicks, Rachel and Andrew Parsons. *Craft Gin Making*. Crowood Press, 2021.
- Owens, Bill and Alan Dikty. *The Art of Distilling Whiskey and Other Spirits*. Quarry Books, 2009.
- Davis, Bryan Alexander. *How To Make Whiskey: A Step-by-Step Guide to Making Whiskey*. CreateSpace, 2012.
- Morris, Rick. *The Joy of Home Distilling: The Ultimate Guide to Making Your Own Vodka, Whiskey, Rum, Brandy, Moonshine, and More*. Skyhorse Publishing, 2014.
- [Distillers Wiki — Beginner's Guide](https://homedistiller.org/wiki/index.php/Beginner%27s_Guide) (homedistiller.org)
- [Distillers Wiki — Cuts and Fractions](https://homedistiller.org/wiki/index.php/Cuts_and_fractions) (homedistiller.org)
- [Distillers Wiki — Safety](https://homedistiller.org/wiki/index.php/Safety) (homedistiller.org)
- [Distillers Wiki — Spirit Style Guide](https://homedistiller.org/wiki/index.php/Spirit_Style_Guide) (homedistiller.org)
- [American Home Distillers — Distilling Calculator](https://americanhomedistillers.com/distilling-calculator/)
- [PhilBilly Moonshine — Alcohol Calculators](https://philbillymoonshine.com/alcoholcalculators/)
- [Clawhammer Supply — Potential Alcohol Table](https://www.clawhammersupply.com/blogs/moonshine-still-blog/14514521-distilling-potential-alcohol-table)
- [DIY Distilling — How to Make Genever](https://diydistilling.com/how-to-make-genever/)
- [Difford's Guide — Moutwijn Genevers](https://www.diffordsguide.com/beer-wine-spirits/category/1136/moutwijn-maltwine-genevers)
- [Wikipedia — Jenever](https://en.wikipedia.org/wiki/Jenever)
- [Distillique Calculator Tools](https://distillique.co.za/distilling-calculators)
- TTB (Alcohol and Tobacco Tax and Trade Bureau) regulations and Gauging Manual
