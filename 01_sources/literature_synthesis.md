# Literature Synthesis — Project Ergon

Automated daily scan. Each entry covers the **7-day window ending on the scan date**.  
Search covers arXiv, SSRN, ScienceDirect, OIES, Wiley, and open-web academic sources.

---

## Scan: 2026-06-28

### 1. NEM Electricity Hedging for Industrial Buyers

#### Papers surfaced (last 7 days)

No new preprints with arXiv prefix `2606` were identified in this specific window targeting NEM hedging for industrial/commercial buyers.

#### Recent prior work still relevant

| Source | Title / Reference | Date | Relevance |
|--------|------------------|------|-----------|
| OIES EL-61 | *Risk Structure and Financial Hedging in Nodal Electricity Markets*, Daniel Yang | Jan 2026 | Comprehensive treatment of risk categories (congestion, temporal, volume, tail, regulatory) and FTR effectiveness; focuses on nodal design, not the NEM's zonal/regional structure |
| arXiv 2604.23908 | *Machine Learning and Deep Learning Models for Short Term Electricity Price Forecasting in Australia's NEM* — Wei Lu et al. | Apr 26 2026 | Explicitly models SA price volatility and negative-price intervals driven by high renewable penetration; addresses five-minute settlement complexity |
| ScienceDirect / Griffith WP 2023-07 | *Derivatives and Hedging Practices in the Australian National Electricity Market* | 2024 | Most direct match: caps, swaps, PPAs, and vertical integration as hedging tools; covers large industrial customer access |
| OIES EL-53 | *Hedging and Tail Risk in Electricity Markets* | Apr 2024 | Tail-risk measurement and hedging instruments in liberalised electricity markets |
| arXiv 2605.22387 | *Hybrid KAN-XGBoost for Week-Ahead Price Forecasting in the NEM* | May 2025 | Week-ahead forecasting supporting scheduling and hedging decisions; SA included |
| arXiv 2506.03808 | *Market Power Abuse in Wholesale Electricity Markets* | Jun 2025 | Hedging–market-power interaction dynamics; framework for identifying abuse |

#### Novelty threat assessment
- **LOW–MODERATE.** The OIES EL-61 paper is the closest conceptual neighbour but addresses a nodal market architecture (not the NEM). The Griffith 2024 paper covers NEM derivatives comprehensively but does not apply a capital-growth / log-wealth objective to the buyer's decision problem. No 2606-prefix paper found that attacks the industrial buyer hedging problem from the financial-economics angle.

---

### 2. Log-Wealth Maximisation / Kelly Criterion at Firm Level

#### Papers surfaced (last 7 days)

No new arXiv `2606` preprints directly applying the Kelly criterion or log-wealth objective at the **firm** or **corporate operations** level were identified.

#### Recent prior work still relevant

| Source | Title / Reference | Date | Relevance |
|--------|------------------|------|-----------|
| arXiv 2507.05994 | *Beating the Best Constant Rebalancing Portfolio: A Generalisation of the Kelly Criterion and Universal Learning Algorithm for Markets with Serial Dependence* — Duy Khanh Lam | Jul 2025 | Extends classical Kelly to serially dependent market environments; proves asymptotic optimality of proposed learning strategy. Covers portfolio management, not operational hedging |
| arXiv 2412.14144 | *Application of the Kelly Criterion to Prediction Markets* | Dec 2024 | Applies Kelly to prediction market betting; narrow scope |
| arXiv 2502.16859 | *The Kelly Criterion and Utility Function Optimisation for Stochastic Binary Games* | Feb 2025 | Submartingale/supermartingale regime analysis; theoretical |
| arXiv 2503.07498 | *Optimal Diversification and Leverage in a Utility-Based Portfolio Allocation Approach* | Mar 2025 | Utility-based allocation incorporating leverage; investment focus |

#### ⚠️ NOVELTY FLAG — MODERATE THREAT
**arXiv 2507.05994** (Jul 2025) is the most threatening: it generalises the Kelly criterion to serially dependent markets (electricity prices are notoriously autocorrelated and regime-switching) and provides a universal learning algorithm. **If the project's contribution is an extension of Kelly to correlated or regime-switching electricity price processes, this paper significantly narrows the gap.** Action: verify whether Lam (2025) is cited and whether the project's application to a physical commodity buyer (rather than a financial portfolio) is sufficiently distinct.

---

### 3. South Australian Electricity Market Volatility

#### Papers surfaced (last 7 days)

| Source | Title / Reference | Date | Notes |
|--------|------------------|------|-------|
| WattClarity / market data | Prices above $500/MWh re-emerged in SA on 24 Jun 2026 | Jun 24 2026 | Live market event; documents ongoing volatility regime consistent with project motivation |

#### Recent prior work still relevant

| Source | Title / Reference | Date | Relevance |
|--------|------------------|------|-----------|
| arXiv 2604.23908 | *ML and DL for Short Term EPF in the NEM* — Wei Lu et al. | Apr 26 2026 | SA-specific; quantifies volatility and negative-price frequency under 5-min settlement |
| arXiv 2602.01157 | *Deep Time-Series Models Meet Volatility: Multi-Horizon Electricity Price Forecasting in the NEM* | Feb 2026 | All five NEM regions; explicitly addresses post-renewable-transition volatility |
| arXiv 2311.07289 | *Probabilistic Forecast Methodology for Volatile Electricity Prices in the NEM* | 2023 (v2 updated) | Quantile regression for extreme price events; SA benchmark |
| SAPC / UoW | *Projections of Spot Price Volatility in SA* (commissioned research) | — | Historical and projected spot price volatility analysis for SA; regulatory context |
| Modo Energy | SA battery revenues $356k/MW/yr in Jan 2026 heatwave | Feb 2026 | Quantifies volatility magnitude; supports market motivation section |

#### Novelty threat assessment
- **LOW.** All SA volatility papers focus on **forecasting**; none apply financial hedging instruments from the industrial buyer's perspective. The 2026 market data (prices >$500/MWh on 24 Jun) actually **strengthens** project motivation.

---

### 4. Small Manufacturer Financial Resilience and Input Costs

#### Papers surfaced (last 7 days)

No arXiv `2606` papers targeting small/SME manufacturer financial resilience with an energy-cost focus were found in this window.

#### Recent prior work still relevant

| Source | Title / Reference | Date | Relevance |
|--------|------------------|------|-----------|
| *Financial Review* (Wiley) | *Organisation Capital and Firm Resilience to Cash Flow Shocks* — Kouretas, Nguyen, Zhang | 2026 | Published 2026; studies firm resilience mechanisms (trade credit, cost reduction, operational efficiency) against cash flow shocks; COVID-19 window (2017–22). Relevant to resilience framing but does not address energy input costs |
| *Nature H&SS Communications* | *Resilient Futures: Intellectual and Thematic Pathways in Financial Resilience Research* | 2026 | Bibliometric review of 527 publications to Nov 2025; identifies liquidity, innovation, governance as corporate resilience themes |
| arXiv 2506.08638 | *Industrial Flexibility Investment Under Uncertainty: A Multi-Stage Stochastic Framework* | Jun 2025 | Multi-stage stochastic model for industrial firms investing in flexibility under energy and reserve market uncertainty; closest to industrial energy-cost risk management |
| ScienceDirect | *Prediction of Energy Consumption for Manufacturing SMEs* | 2024 | Energy consumption prediction for manufacturing SMEs; efficiency focus |

#### ⚠️ NOVELTY FLAG — LOW–MODERATE THREAT
**arXiv 2506.08638** (Jun 2025) addresses industrial flexibility investment under energy market uncertainty using a multi-stage stochastic framework. **If the project models industrial buyer decision-making under SA electricity price uncertainty using a stochastic optimisation approach, this paper's framework overlaps.** Key differentiator: 2506.08638 focuses on investment in physical flexibility (demand response, storage) rather than financial hedging instruments. Verify this distinction is clear in the project's framing.

---

### Cross-cutting Novelty Summary

| Risk level | Paper | Specific threat |
|-----------|-------|----------------|
| 🔴 Moderate | arXiv 2507.05994 (Lam, Jul 2025) | Kelly generalisation to serial dependence — may pre-empt contribution if project extends Kelly to autocorrelated electricity prices |
| 🟡 Low–moderate | arXiv 2506.08638 (Jun 2025) | Industrial flexibility investment under energy market uncertainty — overlaps with buyer decision model if stochastic optimisation is the method |
| 🟡 Low–moderate | OIES EL-61 (Yang, Jan 2026) | Risk typology and hedging instrument analysis — broad conceptual overlap, mitigated by nodal vs. zonal market difference |
| 🟢 Low | Griffith WP / ScienceDirect 2024 | Comprehensive NEM derivatives survey — does not apply log-wealth objective |
| 🟢 Low | arXiv 2604.23908 (Apr 2026) | NEM/SA ML forecasting — different method and objective (forecasting, not hedging optimisation) |
| 🟢 Low | Financial Review 2026 (Kouretas et al.) | Firm resilience to cash flow shocks — general mechanism, not energy-specific |

**No paper found in the June 21–28 2026 window that directly combines** (a) NEM/SA electricity hedging, (b) the Kelly/log-wealth objective, and (c) the small industrial buyer context. Novelty appears intact as of this scan date.

---

*Next scan due: 2026-07-05. Flag any papers combining topics (a)+(b) or (a)+(c) as high priority.*
