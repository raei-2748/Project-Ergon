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

## Scan: 2026-06-21

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days

No new academic papers identified in the 24 hours since the June 20 scan. The principal threat from last cycle — arXiv:2606.16493 (Aïd, Touzi, Villeneuve, "Forward Hedging Reshapes Incentive Provision", 15 Jun 2026) — remains the most recent and most significant risk item for this topic.

Additional background item surfaced this cycle:

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 18 | **Developing Derivative-Based Hedging Strategies to Manage Volatility in Energy Market Prices** | 2026 | *International Journal of Research and Innovation in Social Science* (IJRISS) | Proposes derivative-based hedging frameworks for industrial energy buyers. Content details limited from abstract; not NEM-specific. Does not engage with log-wealth or Kelly objective functions. |

**Novelty flag (IJRISS item):** ℹ️ CONTEXT. Generic hedging-strategy paper; no NEM or Australian focus; no decision-theoretic novelty. Treat as practitioner-literature background.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

No papers published in the last 7 days applying Kelly/log-wealth optimisation to firm-level energy, commodity, or electricity hedging. Searched arXiv (q-fin.PM, q-fin.RM, econ.GN), SSRN, and broader web.

**Gap status: INTACT.** The Kelly criterion continues to appear exclusively in investment-portfolio and betting contexts in the academic literature. No corporate or industrial application found.

---

### Topic 3 — South Australian Electricity Market Volatility

#### New within last 7 days

No new academic preprints or journal papers on SA electricity market volatility identified this cycle.

#### New market data (week of 14–21 Jun 2026)

| # | Item | Date | Source | Key data |
|---|------|------|---------|---------|
| 19 | **SA average peak spot price, June 2026** | Jun 2026 | CEIC / AEMO | Average peak price: **$18.55/MWh** — a sharp decline from **$86.57/MWh in May 2026**. Lowest of any NEM region in June. Driven by high renewable output and mild demand. |
| 20 | **SA forward curve, May 2026 update** | May 2026 | Leading Edge Energy / market data | SA forward contracts trading at **$83–89/MWh** for CY27–CY29. Implies a large spot-forward spread (~$65–70/MWh vs. current spot) — a significant hedging incentive for risk-averse buyers. |
| 21 | **SA heatwave spike event** | Jun 2026 | Energy-Storage.News | SA battery storage captured a 4-hour sustained AU$1,000/MWh price event during a heatwave period. Confirms continued tail-risk exposure even as average prices fall. |
| 22 | **SA retail tariff adjustment, 1 Jul 2026** | Jul 2026 (announced Jun) | EnergyPlans.com.au | SA retail flat-rate tariffs rising **+1.4%** from 1 July — the only NEM state with a retail price increase. Signals that network/retailer cost pass-through diverges from low spot conditions. Industrial buyers on market tariffs exposed differently from mass-market customers. |

**Novelty flag:** ℹ️ CONTEXT. The June 2026 market data reinforces two key aspects of the research problem: (a) extreme spot-forward spread creates strong incentive to hedge, and (b) tail-risk events persist despite low average prices — consistent with a bimodal or spike-heavy price distribution. Neither the low-spot conditions nor the forward premium threaten novelty; they strengthen the real-world motivation.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days

No new academic papers in the last 7 days directly addressing small-manufacturer energy-cost hedging or input-cost resilience in an Australian context.

#### Practitioner evidence (new this cycle)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 23 | **"Energy Volatility Is Reshaping How SMEs Think About Resilience"** | 2026 | We Mean Business Coalition | Documents a shift: hedging is transitioning from an "optional" tool to an "essential" business practice for SMEs under sustained energy-cost volatility. Previously a corporate-only instrument; smaller firms increasingly seeking fixed-rate or structured contracts. |
| 24 | **"Iran War Forces Small Dairies to Hedge Like Multinationals"** | Apr 2026 | FoodNavigator-USA | Illustrative case: fuel-price shocks driven by geopolitical events forcing food-manufacturing SMEs to adopt derivative hedging previously confined to large corporates. Direct analogy to SA industrial buyers facing electricity cost spikes. |

**Novelty flag:** ℹ️ CONTEXT. Practitioner evidence confirms the problem is live and commercially relevant. Neither item is an academic paper; neither threatens the theoretical novelty gap. They can be cited in the introduction to establish real-world motivation.

---

### Overall Novelty Assessment — 2026-06-21

| Claim area | Threat level | Change from prior scan | Key item |
|---|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | 🚨 HIGH | **No change** | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) — still primary threat |
| NEM risk taxonomy for industrial buyers | ⚠️ MODERATE | No change | OIES EL-61 (Jan 2026) |
| SA volatility characterisation | ⚠️ MODERATE | No change | arXiv:2606.05991 (Kloster & Benth, 4 Jun) |
| Kelly/log-wealth criterion at firm level | ✅ GAP INTACT | **Confirmed again** | No papers found (7-day window and broader search) |
| SA small-manufacturer electricity hedging | ✅ GAP INTACT | **Confirmed again** | No academic papers found; practitioner evidence only |

**New data point of note:** The SA spot-forward spread (spot ~$18/MWh vs. forward CY27 ~$83–89/MWh) is historically unusual. If the project models hedging value using a spread-based approach, this spread magnitude may need to be documented as an empirical input — and any model calibrated on it should note the structural low-price period in June 2026 as potentially transitory.

**No action required on novelty positioning.** The arXiv:2606.16493 threat identified on June 20 remains the only HIGH-level item. Full-text review of that paper (recommended in the June 20 scan) should be completed before submission.

---

*Scan produced by automated daily routine — 2026-06-21 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY), SSRN, ScienceDirect, Oxford Energy Institute, WattClarity, Leading Edge Energy, CEIC, EnergyPlans.com.au, We Mean Business Coalition, FoodNavigator-USA*
