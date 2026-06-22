# Literature Synthesis — Project Ergon

Daily scan cadence: 07:00 AEST. Covers four topic clusters:
1. NEM electricity hedging for industrial buyers
2. Log-wealth maximisation / Kelly criterion at firm level
3. South Australian electricity market volatility
4. Small manufacturer financial resilience and input costs

Novelty flags use: 🚨 HIGH THREAT · ⚠️ MODERATE THREAT · ℹ️ CONTEXT / BACKGROUND

---

## Scan: 2026-06-20

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 1 | **Forward Hedging Reshapes Incentive Provision** — René Aïd, Nizar Touzi, Stéphane Villeneuve | 15 Jun 2026 | arXiv:2606.16493 | Studies firm-level forward hedging within a continuous-time CARA principal-agent model. Considers a risk-averse producer facing demand and production risk who can either operate in-house or delegate to an agent under moral hazard while hedging in a competitive forward market. Key finding: delegation and external hedging are partial substitutes; access to forward hedging *reduces* the need to provide incentives through risk exposure. |

**Novelty flag:** 🚨 HIGH THREAT (Topic 1 + Topic 2 crossover). If the project frames NEM hedging as a firm-level decision under risk aversion, this paper directly addresses that structure. The CARA setup is a close cousin to log-wealth maximisation: both derive optimal hedge ratios from a utility-maximising firm. Differentiators to assert: (a) NEM-specific market mechanics (ASX 24 caps, spot volatility regime, no nodal LMP); (b) industrial *buyer* perspective vs. producer-side focus here; (c) Kelly/log framework vs. CARA.

#### Recent background (last 12 months, no last-7-days cut)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 2 | **Derivatives and Hedging Practices in the Australian NEM** | 2024 | *Energy Policy* (Griffith Univ.) [doi:10.1016/j.enpol.2024.001344] | Core baseline. Shows ASX-traded volumes tripled 2017–2021, peaked 2022, fell 15% in 2024. Derivative markets vital for generators, retailers, and *large industrial consumers*. PPAs dominant for new renewables. Covers load-serving instruments including caps and swaps. |
| 3 | **Hedging and Tail Risk in Electricity Markets** (OIES EL-53) | Apr 2024 | Oxford Institute for Energy Studies | Fat tails, tail dependence, implicit fuel volatility preventing long-term hedges in NEM. Framework for extreme risk in wholesale electricity. |
| 4 | **Risk Structure and Financial Hedging in Nodal Electricity Markets** (OIES EL-61) | Jan 2026 | Oxford Institute for Energy Studies | Identifies five evolving risk categories for market participants: (1) locational congestion, (2) temporal price, (3) volume variability, (4) demand/supply tail risks, (5) regulatory design risk. Driven by renewables, BESS, and large AI data-centre loads. Focused on nodal (US-style) markets, not NEM zonal; partial applicability only. |

**Novelty flag (EL-61):** ⚠️ MODERATE THREAT if the project claims novelty in a new taxonomy of electricity-market risks facing industrial buyers. EL-61 pre-empts a five-category framework, though it is US nodal in orientation and does not address NEM-specific contract structures (caps, swaps, ASX 24).

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

No papers found in the last 7 days that directly apply Kelly/log-wealth optimisation to firm-level energy or commodity hedging. The closest adjacent paper is arXiv:2606.16493 above (CARA utility, not log-wealth, but same utility-maximisation family).

#### Recent background

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 5 | **Infinite Horizon Optimal Consumption: Intertemporal Hedging under Epstein-Zin Preferences** | 5 Jun 2026 | arXiv:2606.02945 | Household/investor consumption-hedging under recursive utility. Conceptually adjacent (long-run growth maximisation) but individual investor, not firm. No energy application. |
| 6 | **Tackling Estimation Risk in Kelly Investing Using Options** | 2025 | arXiv:2508.18868 | Kelly betting with estimation error; portfolio finance context not firm-level energy. |
| 7 | **Application of the Kelly Criterion to Prediction Markets** | Dec 2024 | arXiv:2412.14144 | Kelly applied to prediction markets; no corporate or energy application. |

**Gap confirmed:** No paper found applying Kelly/log-wealth growth criterion to *firm-level* commodity or electricity hedging decisions. The literature applies Kelly exclusively to investment portfolios and betting. This remains a plausible novelty gap.

---

### Topic 3 — South Australian Electricity Market Volatility

#### New within last 7 days

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 8 | **Forecasting of Volatility and Risk Premia in Electricity Markets** — Thomas K. Kloster, Fred Espen Benth | 4 Jun 2026 | arXiv:2606.05991 | Matrix-valued representation of covariance operator; parsimonious matrix-HAR model. One-week-ahead forecasts of realized covariance. Variance forecasts substantially improve spread risk premia predictions vs. standard methods. Market focus appears to be European/Nordic; Australian NEM coverage unclear from abstract. |

**Novelty flag (2606.05991):** ⚠️ MODERATE THREAT if project uses variance forecasting or risk premia modelling as inputs to hedging decisions. Methodology is sophisticated and may be cited as prior art for any volatility-modelling component.

#### Recent background and market data

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 9 | **ML and DL Models for Short-Term Electricity Price Forecasting in Australian NEM** | Apr 2026 | arXiv:2604.23908 | Benchmarks ML/DL forecasters in NEM. Finds SA's high renewable share and battery penetration drive structural breaks in price series; five-minute settlement adds complexity. |
| 10 | **Hybrid KAN-XGBoost Week-Ahead NEM Forecasting** | May 2026 | arXiv:2605.22387 | Kolmogorov-Arnold Network + XGBoost for weekly NEM price forecasts. SA included as most volatile region. |
| 11 | **SA market structural data (Q4 2025 / Q1 2026)** | Various 2026 | AEMO / Modo Energy / RenewEconomy | SA negative price intervals: **48.4% of all dispatch intervals in Q4 2025** (highest in NEM). Q1 2026 average price: ~$40–57/MWh (well below historical norms). BESS set marginal price in 32% of NEM trading intervals in Q1 2026. |
| 12 | **SA Price Event, 6 Jan 2026** | 6 Jan 2026 | WattClarity | Spot prices cleared above $1,000/MWh in SA (and Vic, Tas) on evening of 6 January; driven by renewable shortfall + thermal backup constraints. |

**Novelty flag:** ℹ️ CONTEXT. The arXiv papers 2604.23908 and 2605.22387 pre-empt any ML forecasting novelty claim but are not threats to hedging-framework or decision-rule contributions. The structural-data items confirm SA remains the highest-volatility NEM region and that the hedging problem is urgent and real.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days

No papers from the last 7 days found that specifically address *small manufacturer* energy-cost hedging or electricity-specific input-cost resilience.

#### Recent background

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 13 | **Organization Capital and Firm Resilience to Cash Flow Shocks** — Huang (2026) | 2026 | *Financial Review* (Wiley) doi:10.1111/fire.70024 | Organizational capital (tacit skills, processes) significantly mitigates adverse cash flow shocks. Post-COVID evidence: firms with higher org capital used trade credit, cost-cutting, and operational efficiency more effectively. Not energy-specific; general SME resilience. |
| 14 | **Energy Uncertainty and Firm Performance: Does ESG Matter?** | 2026 | *ScienceDirect* | Energy price uncertainty reduces manufacturing firm performance; ESG practices provide partial buffer. Larger firms with hedging access outperform smaller unhedged peers. |
| 15 | **Industrial Development in Africa: Role of Energy Price Volatility** | 2025 | *Energy Sources, Part B* (Taylor & Francis) | Energy price volatility significantly reduces manufacturing growth; smaller, less diversified firms most vulnerable. Cross-country evidence, not Australia-specific. |
| 16 | **Manufacturing: How to Control Energy Costs to Manage Volatility** | Apr 2026 | ICAEW (practitioner) | Lists fixed contracts, PPAs, on-site generation, demand flexibility as key tools for manufacturers. Notes that most SMEs are price-takers with little hedging access. |
| 17 | **Gas Supply Shocks, Uncertainty and Price Setting: Evidence from Italian Firms** | Oct 2025 | arXiv:2510.03792 | Manufacturing firms adjust input prices sharply in response to gas supply shocks; smaller firms lag larger ones. Relevant analogy for SA industrial buyers facing electricity cost shocks. |

**Novelty flag:** ℹ️ CONTEXT. No single paper bridges (a) NEM/SA context + (b) Kelly/log-wealth framework + (c) small manufacturer demand-side perspective. The literature on SME energy resilience is empirical and policy-focused rather than decision-theoretic. This cross-topic gap appears intact.

---

### Overall Novelty Assessment — 2026-06-20

| Claim area | Threat level | Key paper to watch |
|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | 🚨 HIGH | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) |
| NEM risk taxonomy for industrial buyers | ⚠️ MODERATE | OIES EL-61 (Jan 2026) |
| SA volatility characterisation | ⚠️ MODERATE | arXiv:2606.05991 (Kloster & Benth) |
| Kelly/log-wealth criterion at firm level | ✅ GAP INTACT | None found |
| SA small-manufacturer electricity hedging (practical) | ✅ GAP INTACT | None found |

**Recommended action:** Read the full text of arXiv:2606.16493 to assess overlap with the project's utility-maximising hedge-ratio model. If the project uses log-wealth rather than CARA, the difference is defensible but should be explicitly argued. OIES EL-61 should be cited in the literature review as complementary (different market design) rather than competing.

---

*Scan produced by automated daily routine — 2026-06-20 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY), SSRN, ScienceDirect, Oxford Energy Institute, WattClarity, Modo Energy, ICAEW*

---

## Scan: 2026-06-22

**Window covered:** 15 Jun – 22 Jun 2026 (7-day look-back from run date)
**Prior scan:** 2026-06-20 (items 1–17 above). Incremental new items catalogued below; items already logged on 2026-06-20 are cross-referenced rather than duplicated.

---

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days (not yet catalogued)

No papers found from 20–22 Jun 2026 that are new to the catalogue. arXiv:2606.16493 (Aïd, Touzi, Villeneuve — HIGH THREAT, logged 2026-06-20) remains the active watch item from this window.

One new background reference surfaced during today's search sweep:

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 18 | **Energy Futures Hedging Strategies for Electricity Retailers Based on Monthly Price Forecasting** | Jan 2026 | *Energies* (MDPI) doi:10.3390/en19020552 | Proposes a futures-based hedging model for electricity *retailers* using Monte Carlo + t-GARCH to simulate price paths and CVaR optimisation to set portfolio weights across ASX-style futures contracts. No industrial buyer perspective; focuses on retailer revenue hedging, not load-side procurement cost. |

**Novelty flag (item 18):** ℹ️ CONTEXT. Methodology (CVaR + futures portfolio) is related but the agent is a retailer, not an industrial buyer. If the project targets the demand side, this is background rather than a competitor. The CVaR optimisation framework may warrant a direct comparison to a Kelly/log-wealth approach.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

No new papers found from 15–22 Jun 2026 applying Kelly or log-wealth maximisation to firm-level energy, commodity, or operational risk. Broader search across q-fin.PM, q-fin.RM, econ.GN also returned no new entries in this window.

**Gap status: INTACT.** No literature found bridging log-wealth/Kelly to corporate electricity hedging at either the theoretical or empirical level.

---

### Topic 3 — South Australian Electricity Market Volatility

#### New within last 7 days (not yet catalogued)

No papers from 20–22 Jun 2026 surfaced beyond what was logged on 2026-06-20.

One adjacent paper noted for completeness:

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 19 | **An Integrated Techno-Economic Framework for Optimal Microgrid Design: An Australian Case Study** | 2 Jun 2026 | arXiv:2606.03783 | Optimal sizing of PV + wind + battery + diesel + grid-exchange hybrid microgrid for a 1,000-household community in Rockhampton, QLD. Evaluates NPC, COE, renewable penetration, and emissions under sensitivity analysis (discount rate, fuel price, capital cost, carbon price, grid outage). No SA-specific focus; no wholesale spot market or hedging content. |

**Novelty flag (item 19):** ℹ️ CONTEXT only. Techno-economic microgrid design is a separate literature stream from wholesale market hedging. Not a novelty threat; citable as complementary on-site generation as an alternative to market hedging.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days (not yet catalogued)

No academic papers from 15–22 Jun 2026 specifically addressing small-manufacturer electricity hedging or SA-specific energy input-cost management.

One new European policy paper is noted:

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 20 | **Resilience to Price Shocks in Coupled Gas-Electricity Markets** (CERRE Issue Paper) | Mar 2026 | Centre on Regulation in Europe (CERRE) | Proposes an Energy Price Resilience (EPR) metric to measure ex-ante exposure to wholesale gas-electricity price shocks. Argues that high-impact, low-probability compound supply events (LNG stress + gas-power coupling) drive acute wholesale price spikes. Policy conclusion: ex-ante demand-side flexibility, procurement contracts, and storage governance outperform ex-post crisis coping. European context; NEM coupling dynamics differ but analogy is strong for SA's gas-peaker / renewable intermittency interaction. |

**Novelty flag (item 20):** ⚠️ MODERATE. The EPR metric concept pre-empts any similar resilience-scoring proposal for Australian industrial buyers. The European framing limits direct competition, but if the project proposes a new "electricity cost risk score" or threshold rule for SA manufacturers, cite CERRE EPR to situate and differentiate.

---

### Overall Novelty Assessment — 2026-06-22

| Claim area | Threat level | Change since 2026-06-20 | Key paper |
|---|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | 🚨 HIGH | Unchanged | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) |
| NEM risk taxonomy for industrial buyers | ⚠️ MODERATE | Unchanged | OIES EL-61 (Jan 2026) |
| SA volatility characterisation | ⚠️ MODERATE | Unchanged | arXiv:2606.05991 (Kloster & Benth) |
| SA manufacturer resilience scoring / threshold rule | ⚠️ MODERATE | **NEW** — added this scan | CERRE EPR metric (Mar 2026) — item 20 |
| Kelly/log-wealth criterion at firm level | ✅ GAP INTACT | Unchanged | None found |
| SA small-manufacturer electricity hedging (practical) | ✅ GAP INTACT | Unchanged | None found |

**Action items from this scan:**

1. **arXiv:2606.16493** (Aïd, Touzi, Villeneuve) — Priority read still open from 2026-06-20 scan. No further delay: the paper is 7 days old and directly overlaps with any utility-maximising hedge-ratio model in the project.
2. **CERRE EPR metric (item 20)** — If the project proposes any form of electricity-cost resilience score or trigger threshold for small manufacturers, read the CERRE paper and explicitly differentiate on: (a) NEM vs. EU market design, (b) demand-side industrial buyer framing vs. system-level policy metric, (c) Kelly/log-wealth grounding vs. EPR's regulatory-design framing.
3. **Item 18 (retailer CVaR hedging)** — Low priority; background only unless the project directly compares CVaR and Kelly criteria.

---

*Scan produced by automated daily routine — 2026-06-22 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY, econ.EM), SSRN, ScienceDirect, Oxford Energy Institute, CERRE, MDPI Energies, WattClarity*
*Note: No new HIGH-threat papers emerged in the 20–22 Jun window. The threat landscape is unchanged from the 2026-06-20 scan.*
