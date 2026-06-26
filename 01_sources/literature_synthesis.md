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
| 1 | **Forward Hedging Reshapes Incentive Provision** — René Aïd, Nizar Touzi, Stéphane Villeneuve | 15 Jun 2026 | arXiv:2606.16493 | Studies firm-level forward hedging within a continuous-time CARA principal-agent model. Considers a risk-averse producer facing demand and production risk who can either operate in-house or delegate to an agent under moral hazard while hedging in a competitive forward market with a rational market maker. Key finding: delegation and external hedging are partial substitutes; access to forward hedging *reduces* the need to provide incentives through risk exposure. |

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

## Scan: 2026-06-26

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days (2026-06-19 to 2026-06-26)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 18 | **Robust Hedging Valuation Adjustment under Liquidity-Demand Stress** | 25 Jun 2026 | arXiv:2606.26731 | Develops a robust hedging valuation adjustment (HVA) measure for dynamic hedging under simultaneous liquidity and demand stress. Simulates rebalancing and maturity-unwind trades to generate a loss distribution per no-trade-band rule; robust HVA defined as worst-case expected loss over a relative-entropy neighbourhood of that distribution. Focus is generic financial derivatives, not energy-specific. |

**Novelty flag (2606.26731):** ℹ️ CONTEXT. Methodology for quantifying hedging cost under stress is relevant background if the project models transaction costs or liquidity constraints on NEM derivative positions, but does not directly address electricity or industrial buyers.

#### Previously uncatalogued background (found this scan — not new, but not in Jun-20 synthesis)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 19 | **The Forward Market Dilemma in Energy-Only Electricity Markets** — Flottmann, Simshauser, Wild, Todorova | 2025 | *Energy Economics* (ScienceDirect) doi:10.1016/j.eneco.2025.005031; also EPRG Working Paper 2502, Cambridge Judge Business School | Analyses how growing VRE penetration (modelled at 60% market share) creates a structural shortfall in forward contract supply in energy-only gross-pool markets, using Australia's NEM as the primary case study. SA is explicitly cited as the most affected region: with only a few physically-backed generators remaining able to sell forward contracts, and at significant premiums. Key finding: speculative forward-market participants exit as VRE scales and scarcity pricing becomes infrequent; residual industrial buyer exposure grows. Policy conclusions include capacity market supplements and two-way CfDs. |

**Novelty flag (Flottmann et al. 2025):** ⚠️ MODERATE–HIGH THREAT. This paper directly addresses the hedging access problem for industrial buyers in the NEM, with SA as the canonical case. It pre-empts any novelty claim about *identifying* or *characterising* the hedging shortfall problem. Differentiators to assert: (a) the project's contribution is a *decision framework* for the buyer facing the shortfall (log-wealth hedge ratio), not a structural analysis of why the shortfall exists; (b) Flottmann et al. are supply-side / market-design focused, not demand-side decision-theoretic; (c) the project's framework is applicable regardless of the cause of the shortfall. This paper should be prominently cited as motivating context.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 20 | **Reinforcement Learning for Risk-Sensitive Investment Management: a Free Energy–Entropy Duality Approach** — Sebastien Lleo, Wolfgang Runggaldier | ~20 Jun 2026 | arXiv:2606.20903 | Develops a continuous-time RL approach to risk-sensitive benchmarked asset allocation using free energy–entropy duality to reformulate a non-standard stochastic control problem as a linear-quadratic-Gaussian saddle-point game. Yields explicit finite- and infinite-horizon solutions; an ergodic counterpart connects to the Kelly growth-optimal policy as the risk-neutral limit. Key phrase: "the learned allocation admits an economic interpretation through fractional Kelly decompositions." No energy or commodity application; purely portfolio/investment context. Companion to the same authors' earlier arXiv:2604.15463 (Apr 2026). |

**Novelty flag (2606.20903):** ⚠️ MODERATE THREAT (Topic 2). The paper advances the theoretical toolkit for Kelly-adjacent allocation in continuous time, and the "fractional Kelly decompositions" framing is directly analogous to the partial-hedge structure a log-wealth-maximising firm would adopt. However, the application domain is portfolio management, not corporate commodity/electricity hedging. Differentiators: (a) the project applies log-wealth optimisation to a *production cost* decision (hedge ratio on electricity input), not a financial portfolio; (b) no RL or learning component required for the project's closed-form framework; (c) the ergodic/growth-rate connection is methodologically adjacent but not an overlap in application. Monitor for any follow-on paper by Lleo & Runggaldier applying this to commodity markets.

---

### Topic 3 — South Australian Electricity Market Volatility

#### New within last 7 days — market events

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 21 | **~72-hour wind lull and SA price spike event** | 21–24 Jun 2026 | WattClarity (multiple articles) | The worst consecutive low-wind episode in SA in 2026, lasting from Sunday 21 June through Wednesday 24 June. SA spot prices hit the **AU$20,300/MWh market price cap twice on the evening of 21 June** (event began 19:35 AEST, lasted ~2 h 35 min; average across event ~AU$3,900/MWh). Prices remained elevated (>AU$500/MWh) on Wednesday morning 24 June and again in the afternoon. Root causes: (1) near-zero wind output across SA for ~72 hours; (2) Tailem Bend–Tungkillo 275kV line outage, reducing import capacity from Victoria. BESS fleet captured ~AU$324,000 during the June 21 event; WattClarity published a multi-article retrospective on BESS operations and SA bidding over the four-day window. WattClarity analysis also notes this wind lull was the worst consecutive-low-wind run in SA in 2026. |
| 22 | **Market Price Cap to rise to AU$23,200/MWh from 1 July 2026** | (announced Feb 2026; effective 1 Jul 2026) | AEMC / WattClarity | The NEM market price cap (MPC) steps up 14.3% from AU$20,300 to AU$23,200/MWh on 1 July 2026, continuing the multi-year step-up pathway set under the AEMC's 2023 rule change. The cumulative price threshold (CPT) rises proportionally. For unhedged industrial buyers, the worst-case single-interval exposure increases accordingly. The MPC pathway continues toward a higher base rate through to 2028. |

**Novelty flag:** ℹ️ CONTEXT / CONFIRMS RESEARCH URGENCY. The June 21–24 event is the most acute SA price episode since the January 2026 heatwave event (item 12), and provides fresh empirical evidence that the research problem is live and urgent. The cap increase to AU$23,200 from July 1 raises the maximum unhedged exposure for industrial buyers and strengthens the motivation for a systematic hedging framework. No academic paper on these events yet; news/analysis cycle only. These items do not threaten novelty but should be incorporated into the empirical motivation section.

#### New within last 7 days — academic

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 23 | **Analysing Drivers and Interdependencies in European Electricity Markets using XAI** — Pesenti, O'Sullivan | 17 Jun 2026 | arXiv:2606.19118 (UCL Energy Institute) | Uses SHAP-based explainability (extended SSHAP aggregation) with DNN models to quantify feature contributions to electricity prices across 39 European bidding zones. Key drivers identified: solar generation (disproportionate impact), gas prices, cross-border interconnections. Constructs a counterfactual single EU-price scenario. European market only; no NEM/SA application. |

**Novelty flag (2606.19118):** ℹ️ CONTEXT. Methodology (XAI price-driver decomposition) is potentially applicable to SA price formation analysis but paper is European-only. Not a threat; possible future citation for methodology if the project analyses drivers of SA price spikes.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days

No papers found in the last 7 days that address small manufacturer energy-cost hedging, electricity-specific input-cost resilience, or SME financial resilience in an energy price volatility context.

**Gap confirmed:** The cross-topic gap — combining (a) NEM/SA context, (b) Kelly/log-wealth decision framework, and (c) small manufacturer demand-side perspective — remains intact as of 2026-06-26.

---

### Overall Novelty Assessment — 2026-06-26

| Claim area | Change since 2026-06-20 | Threat level | Key item |
|---|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | No change | 🚨 HIGH | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) — prior scan |
| NEM forward-market access for industrial buyers | **UPGRADED** ⬆️ | ⚠️ MODERATE–HIGH | Flottmann et al. (2025, *Energy Economics*) — newly catalogued |
| Kelly/log-wealth criterion at firm level | New adjacent paper | ⚠️ MODERATE | arXiv:2606.20903 (Lleo & Runggaldier) — fractional Kelly in RL portfolio context |
| SA volatility characterisation | **STRENGTHENED EMPIRICALLY** | ℹ️ CONTEXT | Jun 21–24 price events; MPC rising to $23,200 from 1 Jul 2026 |
| SA small-manufacturer electricity hedging (decision-theoretic) | No change | ✅ GAP INTACT | None found |

**Recommended actions:**
1. Add Flottmann et al. (2025, *Energy Economics*) as a prominent citation in the literature review. Frame as: "This paper establishes *why* the hedging problem exists for SA industrial buyers at a market-design level; the present project addresses *how* buyers should respond at the firm level."
2. Read arXiv:2606.20903 (Lleo & Runggaldier) in full to assess whether the fractional Kelly framing overlaps with the project's hedge-ratio derivation. The ergodic/growth-rate connection is the closest theoretical parallel found to date.
3. Update empirical motivation section with the June 21–24 price event and the July 1, 2026 MPC increase to AU$23,200/MWh.
4. Continue monitoring for any Lleo & Runggaldier follow-on applying fractional Kelly to commodity or energy markets.

---

*Scan produced by automated daily routine — 2026-06-26 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY), SSRN, ScienceDirect, WattClarity, Energy-Storage.News, AEMC, RenewEconomy, Modo Energy*
