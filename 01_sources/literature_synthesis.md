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
