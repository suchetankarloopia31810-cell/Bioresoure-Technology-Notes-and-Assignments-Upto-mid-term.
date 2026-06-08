# Bioresource Technology — Last-Minute Revision Cheat Sheet
*(One-page recap of the key facts, numbers, equations & diagrams)*

---

## 1. CORE DEFINITIONS
- **Bioresources:** non-fossil, biogenic resources for food / products / energy. Natural (plants, animals, microbes) vs Anthropogenic (rice husk, bagasse, straw).
- **Classification:** Primary (grain, fish) → Secondary (molasses, bagasse, by-products) → Tertiary (residues) → Quaternary (post-use: faeces→short, packaging→mid, furniture→long).
- **Bioresource Technology:** interdisciplinary = engineering + biology, applied to non-fossil biogenic resources; broader than biotechnology.
- **Biomass:** organic matter from photosynthesis = cellulose + hemicellulose + lignin + extractives; "stored solar energy," carbon-neutral, low ash/N/S.

## 2. COURSE OUTCOMES
CO1 fundamentals/applications · CO2 properties + conversion tech · CO3 systems · CO4 data analysis + design.

## 3. BIOMASS PROPERTIES (for conversion)
Moisture · Fixed Carbon & Volatile Matter (proximate) · Heating value (HHV/LHV) · Ash (slagging) · C,H,O,N,S (ultimate) · Alkali metals · **Cellulose/Lignin ratio**.
- **HHV** = gross (incl. water latent heat); **LHV** = net (usable).
- **Van Krevelen:** higher O/C & H/C → **lower** energy (C–C bonds hold most energy).
- **HHV ↑ with lignin ↑.**

## 4. CONVERSION ROUTES
- **Thermo-chemical:** combustion, gasification, pyrolysis, liquefaction.
- **Bio-chemical:** anaerobic digestion (biogas), fermentation (ethanol), aerobic digestion.
- **Mechanical:** extraction (oilseeds → biodiesel via esterification).

---

## 5. KEY NUMBERS (memorise!)
| Process | Temperature / value |
|---|---|
| Combustion | 800–1000 °C; moisture <50 %; efficiency 20–40 % |
| Gasification | 800–900 °C; CV 4–6 MJ/Nm³ (1000–1200 kcal/m³); **ER 0.2–0.4** |
| Pyrolysis | ~500 °C; flash → bio-oil up to 80 % |
| Anaerobic digestion | 8–55 °C, **optimum 35 °C**; pH 6.8–7.8 (not >8.5); **C:N 30:1** |
| Biogas | CH₄ 50–70 %, CO₂ 30–40 % |
| AD solids | works at 8–9 % solids → dilute gobar 1:1 with water |
| Air O₂ content | 23.3 % by mass; N₂ 76.7 % |

## 6. KEY EQUATIONS
- **Min air** = (2.667 C + 8 H + S − O)/0.233  kg/kg fuel
- **Actual air** = (1 + excess) × min air
- **HHV** = 0.35C + 1.18H + 0.1S − 0.02N − 0.01O − 0.02A (MJ/kg)
- **HHV vs lignin:** HHV = 0.0979·L + 16.29 (R²≈0.93, RMSE≈0.38)
- **RMSE** = √[(1/n)Σ(obs − pred)²]
- **Equivalence ratio Φ** = actual air / stoichiometric air
- **Gasifier efficiency η** = chemical energy in dry producer gas (15 °C) / energy in biomass

## 7. GASIFICATION REACTIONS
| | Reaction | ΔH |
|---|---|---|
| Partial oxid. | C + ½O₂ → CO | −268 |
| Complete oxid. | C + O₂ → CO₂ | −406 |
| Water-gas | C + H₂O → CO + H₂ | +118 |
| Boudouard | C + CO₂ → 2CO | +170.7 |
| Water-gas shift | CO + H₂O → CO₂ + H₂ | −42 |
| Methanation | CO + 3H₂ → CH₄ + H₂O | −88 |
**4 stages:** Drying → Pyrolysis → Oxidation → Reduction.

## 8. GASIFIERS
- **Downdraft (co-current):** gas+ash exit bottom; tar cracked → **low-tar clean gas** (engines); 1000–1200 °C; moisture max 40 %.
- **Updraft (counter-current):** gas exits top at 130–150 °C → **high efficiency but tar-rich**; tolerates higher moisture.
- **Fluidized-bed:** sand, 800–900 °C, near-isothermal, fuel-flexible, more tar/oil.
- **Entrained-flow:** >1000 °C, cracks tar, needs pulverised fuel.

## 9. PYROLYSIS PRODUCTS
- **Bio-oil** (liquid): engines/turbines/refinery — but corrosive, low HV, needs upgrading.
- **Biochar** (solid): soil amendment, activated carbon, fuel.
- **Syngas** (H₂ + CO + CH₄...): fuel + chemical feedstock (methanol, H₂).
Reactors: fixed-bed (char/slow), **fluidized-bed (bio-oil/fast)**, ablative, vacuum, rotating-cone, auger.

## 10. ANAEROBIC DIGESTION — 4 STAGES
**Hydrolysis** (polymers→monomers, enzymes, rate-limiting) → **Acidogenesis** (→VFAs, H₂, CO₂) → **Acetogenesis** (→acetate + H₂ + CO₂) → **Methanogenesis** (→CH₄ + CO₂).
- Aceticlastic: CH₃COOH → CH₄ + CO₂ (≈70 %)
- Hydrogenotrophic: CO₂ + 4H₂ → CH₄ + 2H₂O (≈30 %)
- Trace metals: **Ni, Co, Mo, Fe** (Ni unique to methanogens).

## 11. BIOGASIFICATION / COW DUNG (India)
Faeces:urine 3:1 · 69.9 % rural · cow gives 9–15 kg dung/day · first plant patented 1946.
**KVIC floating-dome plant:** underground brick digester, centre wall to half-height, floating G.I. gas holder, oil/water seal, inlet & outlet pits; gas after 15–20 days.

## 12. GOBAR PLANT DESIGN STEPS
1. Daily gobar = Σ(animals × kg/animal)
2. Biogas = gobar × biogas-yield
3. Gobar volume = mass / bulk density
4. Slurry/day = gobar vol × 2 (1:1 water)
5. Digester V = RT (≈30 d) × slurry/day
6. V = (π/4)D²h → solve D, add 0.5 m freeboard for H
7. Gas holder ≈ 50 % daily gas; D_G = D − 2×clearance
8. Mixing tank vol = daily slurry vol

## 13. COMBUSTION ESSENTIALS
- Equations: C+O₂→CO₂; H₂+½O₂→H₂O; S+O₂→SO₂.
- **Two-stage:** primary air (sub-stoich, devolatilise) → secondary air (complete burnout) → low emissions.
- **Fuel-N → NOₓ:** N released as NH₃/HCN; oxidising→NO, reducing/staged→N₂ (so air-staging cuts NOₓ).
- Pollutants: CO, hydrocarbons, soot, NOₓ, SOₓ, particulates.
- Particulate control: cyclone, ESP, bag filter, scrubber.
- Flue gas: CO₂=3.667C, H₂O=9H, SO₂=2S, N₂=0.767×air, O₂=0.233×excess air.

---
**Quick numeric recall:** Miscanthus HHV wet 20.86 / dry 22.80 MJ/kg · Rice husk: air 5.98 kg/kg, flue gas 6.80 kg/kg (25 % excess) · Dairy farm gobar plant: 1100 kg/day, 38.5 m³ biogas, digester ≈55 m³.

**Good luck! 🎓**
