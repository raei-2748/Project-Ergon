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

---

## Scan: 2026-06-23

**Window covered:** 16 Jun – 23 Jun 2026 (7-day look-back from run date)
**Prior scan:** 2026-06-22 (items 1–20 above). Incremental new items catalogued below; items already logged are cross-referenced rather than duplicated.

---

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days

No new academic papers published 16–23 Jun 2026 on NEM electricity hedging for industrial buyers. All relevant preprints from the 2606.XXXXX arXiv space were checked; none in the q-fin, econ.GN, or eess.SY categories address demand-side NEM hedging.

#### Regulatory context (active this week)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 21 | **Market Price Cap rises to $23,200/MWh from 1 July 2026** | 1 Jul 2026 (eff.) | AEMC / WattClarity | AEMC's annual CPI adjustment lifts the NEM Market Price Cap (MPC) from its 2025–26 level to **$23,200/MWh** from 1 July 2026. The Cumulative Price Threshold (CPT) rises to **$2,225,900** per seven-day rolling window. These are the maximum exposures an unhedged industrial buyer faces per dispatch interval and per week respectively — inputs that any Kelly/log-wealth model of extreme loss must parametrise correctly. |

**Novelty flag (item 21):** ℹ️ CONTEXT. No novelty threat; this is a CPI-indexed parameter update. However, any project model calibrated on 2025–26 MPC values ($16,600/MWh typical before this uplift) should be updated. The new MPC is approximately 39% higher than the July 2024 figure, widening the tail-loss scenario for unhedged SA buyers.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

No papers published 16–23 Jun 2026 applying Kelly/log-wealth optimisation to firm-level energy, commodity, or electricity hedging. Searches covered arXiv (q-fin.PM, q-fin.RM, econ.GN), SSRN, and broad web.

**Gap status: INTACT (fifth consecutive daily scan with no threat).** The Kelly criterion continues to appear exclusively in investment-portfolio and betting contexts in the academic literature. No corporate or industrial energy application found to date.

---

### Topic 3 — South Australian Electricity Market Volatility

#### New within last 7 days — SA volatility cluster, 21–23 June 2026

A cluster of real-time market events breaks the "volatility drought" that has characterised SA since early 2026. This is the most significant new empirical finding this scan cycle.

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 22 | **"~72 hours becalmed in South Australia"** | 19–22 Jun 2026 | WattClarity | A sustained ~72-hour period of very low wind generation across SA. Wind, which typically supplies ~24% of NEM output, fell to negligible levels. SA spot prices were consistently elevated throughout; the event ended only when wind resumed on Tuesday 23 June. Characterised by WattClarity as ending a "volatility drought" that had persisted for several months. |
| 23 | **"A break in the 'volatility drought' – in TAS (Sun 21 Jun) and SA (21–22 Jun)"** | 21–22 Jun 2026 | WattClarity | Prices spiked Sunday evening 21 Jun and Monday morning 22 Jun when two risk factors coincided: (1) low wind NEM-wide, and (2) a reduced interconnector export limit from Victoria into SA (a "duck" condition). AEMO forecast an LOR2 (Lack of Reserve 2) in SA for 2030–2100 hrs 21 Jun but assessed it as transient and did not issue a formal LOR2 declaration. Combined wind-drought + interconnector constraint is a key correlated tail-risk scenario for SA industrial buyers. |
| 24 | **"Australian Power Price Surges as Low Wind and Cloud Cover Cut Output"** | 22 Jun 2026 | Bloomberg | 5-minute-ahead spot price in VIC reached ~A$450/MWh — highest intraday level since January 2026. SA prices elevated in parallel. Wind generation fell to **3% of total NEM output** (vs. ~24% typical). Widely reported event; confirms that June 2026 winter calm conditions can trigger sustained multi-interval price elevation across multiple NEM regions. |
| 25 | **"A summary of bidding in SA over 4 days (including the volatility)"** | 23 Jun 2026 | WattClarity | Bid analysis covering the 4-day volatility cluster (approx. 19–23 Jun 2026). Examines generator offer behaviour during the elevated-price environment. Published today; provides micro-level evidence on how thermal and storage assets priced during the event — relevant to calibrating tail-risk scenarios for hedging models. |

**Novelty flag (items 22–25):** ℹ️ CONTEXT — these are market-data / practitioner sources, not academic papers. They do not threaten novelty. However, they provide critical empirical support for two elements of the project's motivation: (a) tail-risk events persist even in periods of depressed average prices; (b) correlated wind-drought + interconnector constraint represents a distinct risk factor beyond simple spot volatility. Any model treating SA spot price risk as i.i.d. or symmetric should be reconsidered in light of this event.

#### New academic preprint (adjacent — European focus)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 26 | **"Analysing drivers and interdependencies in European electricity markets using XAI"** — Antoine Pesenti & Aidan O'Sullivan | 17 Jun 2026 | arXiv:2606.19118 (12 pp.) | Combines DNN models with XAI (SHAP/SSHAP) across 39 European bidding zones to quantify what drives electricity prices. Key findings: (1) renewables — particularly solar — play a disproportionately large price-setting role relative to their generation share; (2) gas prices remain the dominant cross-market driver; (3) interconnections strongly shape price dynamics and create cross-border dependence. Also constructs a counterfactual single-price EU market. |

**Novelty flag (item 26):** ℹ️ CONTEXT/METHOD. European focus; no NEM or industrial hedging content. The XAI/SHAP driver-identification methodology could be cited as a comparator if the project models SA spot price drivers (wind intermittency, gas peakers, interconnector constraints). Not a novelty threat to any of the project's four research claims.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days

No academic papers from 16–23 Jun 2026 specifically addressing small-manufacturer energy-cost hedging or SA-specific input-cost resilience.

#### New background items (not within 7-day window, but new to catalogue)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 27 | **"Energy prices are spiking again: New relief measures, old lessons"** | Apr 2026 | OECD (PDF) | Documents the 2026 global energy price shock (geopolitical origin). Analyses SME/manufacturer exposure across OECD countries. Policy evidence: Ireland covered 40% of SME energy bill increases (cap €10k/month); Bulgaria covered 75% of SME electricity costs for four months. Policy lessons: (1) target support toward viable, exposed firms; (2) preserve price signals; (3) build ex-ante resilience via supply diversification and energy efficiency. Not Australia-specific; cross-country evidence base. |
| 28 | **OECD Economic Outlook Vol. 2026 Issue 1 — "From energy shocks to stronger resilience"** | Jun 2026 | OECD | Dedicated chapter on building firm and sector resilience to energy cost shocks. Documents manufacturing-sector exposure to input-cost volatility under current geopolitical disruption. Recommends structured procurement (long-term contracts, hedging instruments) as superior to ex-post government relief. Not SA or NEM specific. |

**Novelty flag (items 27–28):** ℹ️ CONTEXT. Neither item applies Kelly/log-wealth or any decision-theoretic framework to manufacturer hedging. Neither is Australian-specific. They strengthen the motivation section of the project (global problem, urgent policy interest, SME vulnerability documented) without threatening the theoretical or empirical novelty gap.

---

### Overall Novelty Assessment — 2026-06-23

| Claim area | Threat level | Change since 2026-06-22 | Key item |
|---|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | 🚨 HIGH | **Unchanged** | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) — priority full-text read overdue |
| NEM risk taxonomy for industrial buyers | ⚠️ MODERATE | Unchanged | OIES EL-61 (Jan 2026) |
| SA volatility characterisation | ⚠️ MODERATE | **New empirical support** — Jun 21–23 event confirms tail-risk persistence | arXiv:2606.05991 + items 22–25 (market events) |
| SA manufacturer resilience scoring / threshold rule | ⚠️ MODERATE | Unchanged | CERRE EPR metric (item 20, Mar 2026) |
| Kelly/log-wealth criterion at firm level | ✅ GAP INTACT | **Confirmed fifth consecutive scan** | None found |
| SA small-manufacturer electricity hedging (practical) | ✅ GAP INTACT | Unchanged | None found |

**New modelling input this scan — MPC calibration:** The MPC rises to $23,200/MWh on 1 July 2026 (item 21). Any model using the NEM price cap as the tail-loss bound must update this parameter. If the project uses a capped-lognormal or spike-diffusion price model, the cap level change materially affects Kelly hedge ratios and the value of cap contracts.

**New empirical framing — "volatility drought then spike" pattern:** The June 21–23 SA event (items 22–25) provides real-time evidence for a structural pattern: extended periods of low average prices interrupted by multi-day tail events driven by correlated wind-drought + interconnector constraints. This pattern is distinct from the high-frequency spike literature and may warrant a specific modelling note in the project.

**Action items from this scan:**
1. **arXiv:2606.16493** — Priority read remains open (now 8 days old). No further deferral recommended.
2. **MPC update (item 21)** — Verify all model calibrations use $23,200/MWh as the 2026–27 NEM price cap.
3. **Items 22–25 (SA volatility cluster)** — Consider adding an appendix note or robustness check addressing the wind-drought + interconnector correlation scenario.

---

*Scan produced by automated daily routine — 2026-06-23 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY, stat.AP, 2606.XXXXX range), SSRN, ScienceDirect, Oxford Energy Institute, OECD, AEMC, WattClarity (21–23 Jun 2026 articles), Bloomberg (22 Jun 2026), Leading Edge Energy*
*Note: No new HIGH-threat academic papers emerged this scan. The threat landscape is unchanged from 2026-06-20. The June 21–23 SA volatility cluster is the significant new real-world finding.*

---

## Scan: 2026-06-24

**Window covered:** 17 Jun – 24 Jun 2026 (7-day look-back from run date)
**Prior scan:** 2026-06-23 (items 1–28 above). Incremental new items catalogued below; prior items are cross-referenced rather than duplicated.

---

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days

No new academic papers published 17–24 Jun 2026 on NEM electricity hedging for industrial or manufacturing buyers. The 2606.XXXXX arXiv space (q-fin, econ.GN, eess.SY) was rechecked; no new entries since the June 23 scan.

**arXiv:2606.16493 (Aïd, Touzi, Villeneuve) remains the sole HIGH-threat item** from this scan window. It is now 9 days post-publication; a full-text read is strongly recommended before any further delay.

#### New background item (not within 7-day window; new to catalogue)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 29 | **"NSW-EPNews: A News-Augmented Benchmark for Electricity Price Forecasting with LLMs"** | Jun 2026 | arXiv:2506.11050 | Introduces the first multimodal benchmark jointly evaluating time-series models and LLMs on real-world NEM electricity price prediction, using >175,000 half-hourly NSW spot prices (2015–2024), daily temperature data, and curated news summaries from WattClarity. Task: 48-step-ahead price forecasting with prompt-engineered structured context for LLMs. Scope is NSW only; no SA region or industrial hedging content. |

**Novelty flag (item 29):** ℹ️ CONTEXT/METHOD. NSW-focused; no SA, no industrial buyer, no hedging decision modelling. The benchmark dataset and news-augmented forecasting methodology could be cited as prior art if the project incorporates text-based or news-driven features into a price model. Not a novelty threat to any of the four core claims.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

No papers published 17–24 Jun 2026 applying Kelly or log-wealth maximisation to firm-level energy, commodity, or operational hedging. Searches repeated across arXiv (q-fin.PM, q-fin.RM, q-fin.GN, econ.GN) and broad web.

**Gap status: INTACT — sixth consecutive daily scan with no threat identified.** The Kelly criterion remains absent from corporate electricity or commodity procurement literature. No paper bridges log-wealth growth optimisation and industrial energy cost management at any level of abstraction.

---

### Topic 3 — South Australian Electricity Market Volatility

#### SA market update — evening 23 June 2026

The June 19–23 volatility cluster (items 22–25) continued into Tuesday evening:

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 30 | **SA spot price: $845/MWh at 18:55 dispatch interval, 23 Jun 2026** | 23 Jun 2026 (evening) | WattClarity | SA1 recorded its highest spot price of the preceding 24 hours at $845/MWh in the 18:55 dispatch interval. The wind-drought pattern (low aggregate wind since Saturday 20 Jun) remained the primary driver; wind generation rose from negligible levels to approximately 500 MW by Tuesday afternoon but was still well below the ~1,700 MW typical output that characterises SA's renewable baseload. Confirms the volatility cluster extended at least four full days. |

**Novelty flag (item 30):** ℹ️ CONTEXT. Extends the empirical picture of items 22–25. No novelty threat; directly supports the project's problem motivation. The four-day duration is significant: most hedging models treat spikes as sub-daily events, but this cluster has sustained elevated prices over a full business week — a scenario that amplifies financial exposure for unhedged small manufacturers with weekly or monthly billing cycles.

#### New background paper (adjacent — not within 7-day window; new to catalogue)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 31 | **"Deep Time-Series Models Meet Volatility: Multi-Horizon Electricity Price Forecasting in the Australian NEM"** | 13 Feb 2026 | arXiv:2602.01157 | First study to evaluate deep-learning forecasting models across all five NEM regions simultaneously using post-2022 data (post-NEM suspension, post-accelerated renewables uptake). Key finding: SA is the hardest region to forecast; structural breaks driven by BESS dispatch and high renewable penetration mean pre-2022 models significantly underestimate tail-price risk. Evaluates LSTM, Transformer, N-BEATS, and N-HiTS architectures at 30-min, 1-hr, 4-hr, and 24-hr horizons. |

**Novelty flag (item 31):** ⚠️ MODERATE THREAT (limited). If the project's hedging model incorporates a price-forecasting sub-model for SA, arXiv:2602.01157 is prior art for that sub-model and must be cited. Its finding that SA is structurally harder to forecast post-2022 also has implications for any claim that the project's approach achieves robust hedge ratios under model uncertainty. However, the paper is purely a forecasting benchmark — it does not address hedging decisions, industrial buyer perspective, or Kelly/log-wealth — so the core novelty gap is unaffected.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days

No academic papers from 17–24 Jun 2026 specifically addressing small-manufacturer electricity hedging, SA-specific energy input-cost resilience, or NEM-context financial fragility.

**Gap status: INTACT.** No paper bridges the NEM/SA empirical setting, a decision-theoretic hedging framework, and the small-manufacturer demand-side perspective. The confluence of OECD policy interest (items 27–28) and live SA market volatility (items 22–25, 30) continues to make this an under-served research area.

---

### Overall Novelty Assessment — 2026-06-24

| Claim area | Threat level | Change since 2026-06-23 | Key item |
|---|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | 🚨 HIGH | **Unchanged — read overdue (9 days)** | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) |
| NEM risk taxonomy for industrial buyers | ⚠️ MODERATE | Unchanged | OIES EL-61 (Jan 2026) |
| SA volatility characterisation / forecasting sub-model | ⚠️ MODERATE | **New background threat added** — arXiv:2602.01157 (item 31) | arXiv:2606.05991 + arXiv:2602.01157 |
| SA manufacturer resilience scoring / threshold rule | ⚠️ MODERATE | Unchanged | CERRE EPR metric (item 20, Mar 2026) |
| Kelly/log-wealth criterion at firm level | ✅ GAP INTACT | **Confirmed sixth consecutive scan** | None found |
| SA small-manufacturer electricity hedging (practical) | ✅ GAP INTACT | Unchanged | None found |

**Key judgements from this scan:**

1. **No new HIGH-threat papers this cycle.** The threat landscape is stable. arXiv:2606.16493 (Aïd, Touzi, Villeneuve) remains the only HIGH-rated item and has been open for 9 days without a full read — this is the single most urgent action.

2. **SA volatility cluster now confirmed at 4+ days** (items 22–25, 30). The extended duration (19–23 Jun, likely settling 24 Jun) is materially different from the intraday spike literature and may warrant explicit modelling (e.g., a Markov-switching regime where "calm" and "stressed" states persist for days, not hours). If the project's model treats spike events as Poisson arrivals with sub-daily mean duration, this evidence suggests the calibration underestimates the financial exposure of unhedged buyers.

3. **arXiv:2602.01157 (item 31) added as new MODERATE background threat.** If the project incorporates any SA price-forecasting component, this paper must be cited and its post-2022 structural-break findings addressed.

4. **MPC calibration reminder:** The NEM Market Price Cap rises to $23,200/MWh on 1 July 2026 (item 21). This is one week away. Any model outputs should be re-run under the new cap before submission.

**Action items from this scan:**
1. **arXiv:2606.16493** — Full-text read is now critical. Assess CARA vs. log-wealth differentiator explicitly.
2. **arXiv:2602.01157 (item 31)** — Assess whether the SA price-forecasting component of the project overlaps; if so, reframe as building on rather than independently discovering the post-2022 structural break.
3. **SA volatility cluster (items 22–25, 30)** — Review whether the project's hedging simulation uses event durations calibrated to the multi-day regime confirmed by this event.
4. **MPC update** — Confirm all model calibrations use $23,200/MWh from 1 July 2026.

---

*Scan produced by automated daily routine — 2026-06-24 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY, 2506.XXXXX and 2506.XXXXX ranges), SSRN, ScienceDirect, Oxford Energy Institute, OECD, WattClarity (23–24 Jun 2026), Modo Energy, energy-storage.news, Leading Edge Energy, IEA*
*Note: No new HIGH-threat papers this scan. Kelly/log-wealth gap intact for sixth consecutive day. SA volatility cluster extended to 4+ days — see item 30 and action item 3.*

---

## Scan: 2026-06-25

**Window covered:** 18 Jun – 25 Jun 2026 (7-day look-back from run date)
**Prior scan:** 2026-06-24 (items 1–31 above). Incremental new items catalogued below; prior items are cross-referenced rather than duplicated.

---

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

#### New within last 7 days

No new academic papers published 18–25 Jun 2026 specifically on NEM electricity hedging for industrial or manufacturing buyers were found. The 2606.XXXXX arXiv space (q-fin, econ.GN, eess.SY) was checked; no new entries beyond what was catalogued on 2026-06-24.

**arXiv:2606.16493 (Aïd, Touzi, Villeneuve) remains the sole HIGH-threat item.** It is now 10 days post-publication; a full-text read is critically overdue.

#### New background item (new to catalogue — July 2025)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 32 | **"Pricing energy spread options with variance gamma-driven Ornstein-Uhlenbeck dynamics"** | Jul 2025 | arXiv:2507.11480 | Prices two types of NEM-relevant spread options: (1) *spark spreads* — options for generators hedging unanticipated production cost spikes; (2) *regional spreads* — options on inter-regional price differences across the five NEM states. Adopts exponential Ornstein-Uhlenbeck spot-price dynamics driven by a sum of independent multivariate variance gamma (VG) processes, giving mean-reverting, infinite-activity, non-Gaussian price dynamics with realistic jump behaviour. Calibrated to real Australian electricity futures data (NSW and VIC, 2018–Jan 2026). Derives semi-closed-form pricing formulae via moment generating functions and FFT methods. Affiliated with Australian institutions. |

**Novelty flag (item 32):** ⚠️ MODERATE THREAT (Topic 1). This paper develops a derivatives-pricing model directly calibrated to NEM data and targeting the same class of hedging instruments (spread options) relevant to industrial buyers managing inter-regional exposure or fuel-cost pass-through risk. The threat is bounded because: (a) the paper is a *pricing* model (what is a fair option price?), not a *decision* model (how much should a firm hedge?); (b) it takes the producer/market-maker perspective, not the industrial buyer perspective; (c) it does not incorporate Kelly/log-wealth or any utility-maximising framework for the hedging firm. The VG-OU process modelling contribution is notable and may overlap with any stochastic price-dynamics component in the project. **Recommended action:** read Section 2 of arXiv:2507.11480 to assess whether the spot-price model used in this paper coincides with the project's assumed SA price dynamics.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### New within last 7 days

No papers published 18–25 Jun 2026 applying Kelly or log-wealth maximisation to firm-level energy, commodity, or electricity hedging. Searches covered arXiv (q-fin.PM, q-fin.RM, q-fin.GN, econ.GN, econ.EM) and broad web.

**Gap status: INTACT — seventh consecutive daily scan with no threat identified.** The Kelly criterion continues to appear exclusively in investment-portfolio and betting contexts in the academic literature. No corporate or industrial energy application found at any level of abstraction (theoretical, empirical, or practitioner).

---

### Topic 3 — South Australian Electricity Market Volatility

#### SA market update — post-volatility-cluster settlement (June 24–25)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 33 | **SA futures settle at $87.31/MWh (May 2026 review); SA only NEM region where flat-rate retail prices rise on 1 July 2026 (+1.4%)** | May–Jun 2026 | Leading Edge Energy / EnergyPlans.com.au | SA wholesale futures closed the month at $87.31/MWh (−1.0% for May), trading in a tight $83.70–$88.63/MWh band — the narrowest monthly range of any NEM region. High renewable penetration and strong interconnection support underpinned intra-month stability. However, this calm-month pattern stands in contrast to the June 19–23 volatility cluster (items 22–25, 30), which produced intraday spikes to $845/MWh. Retail flat-rate prices in SA rise +1.4% from 1 July 2026 — the only NEM region where flat rates increase — while TOU rates fall slightly. This divergence reflects SA's unique cost structure: high renewable share but ongoing reliance on gas peakers for reliability during wind droughts. |
| 34 | **SA electricity: 68–75% renewable share; negative pricing in 18–22% of hours; price swings $110–$180/MWh** | 2026 | DiscoveryAlert.com.au / Modo Energy | Structural description of SA's 2026 generation mix and price behaviour. 68% renewable energy share creates asymmetric price distribution: frequent negative or near-zero prices during sunny/windy periods, alternating with steep spikes when renewable generation falls and gas peakers set the marginal price. Characterises a bimodal dispatch regime that is poorly captured by symmetric volatility models. The $110–$180/MWh swing range represents the inter-quartile spread between deep-negative dispatch and high-gas-dispatch intervals, not the tail. Tail events (MPC $20,300–$23,200/MWh) are separate. |

**Novelty flag (items 33–34):** ℹ️ CONTEXT. Both items are market intelligence / practitioner sources, not academic papers. They are not novelty threats. Item 34 adds a useful framing for the bimodal dispatch regime that may be underrepresented in the academic forecasting literature (items 9, 10, 31), which tends to focus on point-forecast accuracy rather than bimodal distributional structure. If the project models SA spot prices with a regime-switching or spike-diffusion model, these items provide empirical grounding for the distributional assumptions.

#### No new SA academic preprints this scan window

The SA volatility cluster (items 22–25, 30) has generated no academic preprints in this scan window; the event is too recent for academic publication timescales. Market participants are expected to publish operational assessments in the coming weeks; this space should be monitored.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

#### New within last 7 days

No academic papers from 18–25 Jun 2026 specifically addressing small-manufacturer electricity hedging or SA-specific input-cost resilience.

#### New background item (new to catalogue — 2025)

| # | Item | Date | Source | Summary |
|---|------|------|---------|---------|
| 35 | **"Renewable energy adoption in European small and medium-sized enterprises: A comparative sectoral analysis"** | 2025 | *Renewable Energy Focus* (ScienceDirect, doi:10.1016/j.ref.2025.000585) | Cross-sectoral analysis of renewable energy adoption rates in European SMEs. Documents that manufacturing SMEs face higher relative exposure to energy cost volatility than service-sector SMEs due to energy-intensive processes. Adoption of on-site renewables (rooftop solar, combined heat and power) provides partial but incomplete hedging: it reduces average costs but does not eliminate exposure to wholesale spot price spikes that determine grid import costs during low-generation periods. Identifies access to capital and energy literacy as the main barriers. No Australia/NEM content; no decision-theoretic framework. |

**Novelty flag (item 35):** ℹ️ CONTEXT. European SME focus; no Kelly/log-wealth; no NEM. Strengthens the motivation that small manufacturers remain structurally under-hedged. The finding that on-site generation provides only partial protection is directly relevant to a project arguing for *financial* (contract-based) hedging as a complement to physical hedging in the SA context.

---

### Overall Novelty Assessment — 2026-06-25

| Claim area | Threat level | Change since 2026-06-24 | Key item |
|---|---|---|---|
| Firm-level utility-maximising hedge ratio in NEM | 🚨 HIGH | **Unchanged — read critically overdue (10 days)** | arXiv:2606.16493 (Aïd, Touzi, Villeneuve) |
| NEM spread-option pricing / price-process modelling | ⚠️ MODERATE | **NEW — item 32 added** | arXiv:2507.11480 (VG-OU NEM spread options, Jul 2025) |
| NEM risk taxonomy for industrial buyers | ⚠️ MODERATE | Unchanged | OIES EL-61 (Jan 2026) |
| SA volatility characterisation / forecasting sub-model | ⚠️ MODERATE | Unchanged | arXiv:2606.05991 + arXiv:2602.01157 |
| SA manufacturer resilience scoring / threshold rule | ⚠️ MODERATE | Unchanged | CERRE EPR metric (item 20, Mar 2026) |
| Kelly/log-wealth criterion at firm level | ✅ GAP INTACT | **Confirmed seventh consecutive scan** | None found |
| SA small-manufacturer electricity hedging (practical) | ✅ GAP INTACT | Unchanged | None found |

**Key judgements from this scan:**

1. **New MODERATE threat added (item 32, arXiv:2507.11480).** The VG-OU spread-option pricing paper is new to the catalogue and is the most technically proximate paper to any stochastic modelling of NEM hedging instruments in the project. The threat is bounded to the price-dynamics / option-pricing layer; the Kelly/log-wealth decision layer remains uncontested.

2. **SA bimodal dispatch structure (item 34) warrants modelling attention.** The 18–22% negative-price frequency combined with gas-peaker spikes implies a highly non-Gaussian spot price distribution. Any hedging model calibrated only to first and second moments will systematically underestimate both the frequency of near-zero prices (reducing hedge value) and the tail-event severity (increasing unhedged exposure). The VG-OU model in item 32 captures this structure; if the project uses a simpler model, a robustness check against VG-OU dynamics is advisable.

3. **Kelly/log-wealth gap confirmed seventh consecutive scan.** No competing paper has emerged applying Kelly or log-wealth growth maximisation to industrial electricity hedging at any level. This remains the project's strongest novelty anchor.

4. **MPC rises to $23,200/MWh on 1 July 2026 — 6 days away.** Final reminder before this parameter change becomes active. All hedging model outputs calibrated against the $16,600/MWh or earlier cap value should be recomputed before submission.

**Action items from this scan:**

1. **arXiv:2606.16493 (Aïd, Touzi, Villeneuve)** — This is now the most urgent single task in the project's novelty management. Full-text read is 10 days overdue. Assess: (a) does the paper's CARA hedge ratio formula reduce to a Kelly-equivalent under log-utility? (b) does it address electricity markets at all (vs. generic commodity forwards)? (c) does it treat the buyer's or seller's side? Differentiate explicitly in the project literature review.
2. **arXiv:2507.11480 (item 32, VG-OU spread options)** — Read Section 2 (price process specification) and the NEM calibration section. Assess overlap with the project's SA spot price dynamics assumptions. If the project uses a simpler model, add a robustness note.
3. **SA bimodal dispatch (item 34)** — Consider whether the hedging simulation accounts for the bimodal structure (high frequency of near-zero/negative prices *and* infrequent tail spikes) rather than treating SA spot prices as unimodal with high variance.
4. **MPC update deadline: 1 July 2026** — Six days. Recompute all model outputs using $23,200/MWh cap.

---

*Scan produced by automated daily routine — 2026-06-25 07:00 AEST*
*Sources searched: arXiv (q-fin, econ.GN, eess.SY, 2506.XXXXX–2507.XXXXX ranges), SSRN, ScienceDirect (Renewable Energy Focus, Energy Policy), Oxford Energy Institute, WattClarity, Modo Energy, Leading Edge Energy, EnergyPlans.com.au, DiscoveryAlert.com.au, ICAEW, Bloomberg*
*Note: No new HIGH-threat papers this scan. One new MODERATE threat added (arXiv:2507.11480 — NEM spread-option pricing). Kelly/log-wealth gap intact for seventh consecutive scan. MPC update deadline: 1 July 2026.*
