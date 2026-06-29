# Literature Synthesis — Project Ergon

Automated daily scan · K-Dense scientific search
Coverage window: last 7 days prior to scan date
Novelty claim under watch: Applying log-wealth maximisation (Kelly criterion) to NEM electricity hedging for small industrial buyers, with focus on South Australian market volatility.

---

## Scan: 2026-06-29

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

| Paper / Source | Date | Venue | Relevance |
|---|---|---|---|
| *Risk Structure and Financial Hedging* (OIES EL-61) | Jan 2026 | Oxford Inst. Energy Studies | Taxonomises five grid-risk categories (locational congestion, temporal price, volume variability, demand/supply tail, regulatory design). Does **not** use log-wealth or Kelly framework. Buyer-side focus is at retailer level, not direct industrial load. |
| *Derivatives and hedging practices in the Australian National Electricity Market* | Apr 2024 | *Energy Policy* (ScienceDirect) | Describes standard NEM swap/cap contracts, PPAs transferring price and volume risk to industrial buyers. Key reference for contract-type taxonomy. Pre-dates 2026 window but flagged as foundational. |
| *Hedging and Tail Risk in Electricity Markets* (OIES EL-53) | Apr 2024 | Oxford Inst. Energy Studies | Statistical properties of NEM prices; extreme-price tail behaviour. No Kelly/log-utility content. |
| *The Forward Market Dilemma in Energy-Only Electricity Markets* | 2025 | *Energy Economics* (ScienceDirect) | "Unholy trinity" argument explaining why long-term risk markets are thin in energy-only designs. Relevant to liquidity constraint faced by small buyers. No Kelly. |
| *Deep Hedging of Green PPAs in Electricity Markets* (arXiv 2503.13056) | Mar 2025 | arXiv preprint | ML-based PPA hedging; quantity + price risk factors. Buyer perspective but no log-wealth objective. |
| *Research on Energy Futures Hedging Strategies for Electricity Retailers* | Jan 2026 | *Energies* (MDPI) | Futures-based hedging via SHAP + Monte Carlo t-GARCH / CVaR. Retailer-side. No industrial SME context; no Kelly. |
| CBA Newsroom: *Electricity hedging — the risk management tool Australia can't afford to ignore* | Nov 2025 | CommBank (industry) | Notes A$18–20/GJ as industrial exit threshold; recommends dynamic hedging for large energy users. Non-academic; confirms practitioner relevance of topic. |

**Verdict (Topic 1, week of 22–29 Jun 2026):** No new peer-reviewed or preprint paper found within the 7-day window. The closest recent work is OIES EL-61 (Jan 2026); it does not use log-wealth or Kelly, leaving the methodological niche open.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

| Paper / Source | Date | Venue | Relevance |
|---|---|---|---|
| *Tackling Estimation Risk in Kelly Investing Using Options* (arXiv 2508.18868) | Nov 2025 | arXiv | Kelly framework with options overlay to handle parameter uncertainty. Investment portfolio focus; no corporate operations or commodity procurement angle. |
| *Optimal Betting: Beyond the Long-Term Growth* (arXiv 2503.17927) | Mar 2025 | arXiv | Extension of Kelly to cases where growth-rate maximisation is suboptimal. Theoretical; finance portfolio context. |
| *Beating the Best Constant Rebalancing Portfolio* (arXiv 2507.05994) | Jul 2025 | arXiv | Log-optimal portfolio under serial dependence. Finance portfolio; no firm operations angle. |
| *A Utility Based Approach to Energy Hedging* (arXiv 1103.5973) | 2011 | arXiv | **Closest existing overlap** — applies utility (including log) functions to energy hedging. Pre-dates by 15 years; does not address NEM, SA, or SME context. Worth citing as prior art. |
| Atlas Peak Research: *Kelly Criterion in Financial Markets* | Apr 2026 | Industry report | Practitioner overview of Kelly for position sizing. No firm-level operations or energy procurement content. |

**Verdict (Topic 2, week of 22–29 Jun 2026):** No paper found in the 7-day window combining Kelly/log-wealth with firm-level energy procurement or input-cost management. The 2011 arXiv utility-hedging paper (1103.5973) is the most direct prior-art risk — it should be explicitly addressed in the literature review to establish novelty by context (NEM, South Australia, SME scale, post-renewable-transition market structure).

**Novelty flag — MEDIUM:** arXiv 1103.5973 (*A Utility Based Approach to Energy Hedging*) applies log utility to energy hedging. While dated, if the novelty claim rests solely on "log utility + electricity hedging," this paper weakens it. The claim should be sharpened to the combination of (a) Kelly/log-wealth, (b) NEM industrial buyer, (c) South Australian volatility regime, and (d) small-manufacturer balance-sheet framing.

---

### Topic 3 — South Australian Electricity Market Volatility

| Paper / Source | Date | Venue | Relevance |
|---|---|---|---|
| *A Probabilistic Forecast Methodology for Volatile Electricity Prices in the Australian NEM* (arXiv 2311.07289) | Nov 2023 | arXiv | SA identified as highest-volatility NEM region; spike modelling methodology. Foundational reference. |
| *NSW-EPNews: A News-Augmented Benchmark for Electricity Price Forecasting with LLMs* (arXiv 2506.11050) | Jun 2026 | arXiv | LLM-augmented price forecasting benchmark for NEM; NSW-focused but methodology transfers to SA. Published within the scan window — **no direct SA volatility content**; no hedging angle. |
| WattClarity analysis: SA price event 21–22 Jun 2026 | 22 Jun 2026 | WattClarity (industry blog) | Detailed post-mortem of SA price spike on the night of 21–22 Jun 2026. Direct evidence of ongoing extreme volatility in the current period. Confirms empirical backdrop for research context. (Site returned 403 on automated fetch; access via browser recommended.) |
| Leading Edge Energy: *Electricity Market Review — May 2026* | May 2026 | Industry | SA futures edged down 1% in May; prices range A$83.70–88.63/MWh. Stability in futures but spot remains volatile. |
| Modo Energy: *NEM Battery Revenues — January 2026* | Jan 2026 | Industry research | SA batteries earned A$356k/MW/year in Jan 2026 — 3–6× other states — directly attributable to SA spot volatility and renewable intermittency. |
| University of Wollongong / SAPC: *Projections of Spot Price Volatility* | n.d. (commissioned) | SA Productivity Commission | Historical and projected SA spot volatility; 68% renewable share driving A$110–180/MWh swings; negative pricing 18–22% of operational hours. |

**Verdict (Topic 3, week of 22–29 Jun 2026):** One arXiv paper published in the scan window (2506.11050) touches NEM price forecasting but is NSW-focused and LLM-benchmarking in nature — no threat to novelty. The SA volatility event of 21–22 Jun 2026 is empirical news, not a competing research paper. The volatility backdrop for the research remains well-documented and uncontested.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

| Paper / Source | Date | Venue | Relevance |
|---|---|---|---|
| OneDigital: *Small Business Financial Resilience in 2026* | 2026 | Industry | Framework: cost control + strategic outsourcing as resilience pillars. No energy-specific hedging content; practitioner level. |
| Citrin Cooperman: *Financial Risk Management in Manufacturing and Distribution* | 2026 | Industry advisory | Supply-chain unpredictability + commodity price risk for manufacturers; recommends BI and cyber insurance. No electricity-specific hedging; no Kelly/log-wealth. |
| FM Insurance: *Resilience Is Essential — New Policy for Manufacturers* | May 2026 | Press release | Insurance-based resilience product launch. Not research; signals market demand for manufacturer resilience tools. |
| Nationwide/Agency Forward: *Manufacturing in 2026: Signs of Renewal amid Ongoing Complexity* | 2026 | Industry | Broad manufacturing risk landscape; no energy hedging detail. |

**Verdict (Topic 4, week of 22–29 Jun 2026):** No peer-reviewed or preprint academic paper found in the 7-day window on SME/manufacturer financial resilience and input-cost risk management. All results are industry/practitioner publications. The academic gap is clear; no novelty threat.

---

## Consolidated Novelty Assessment — 2026-06-29

| Risk level | Item |
|---|---|
| **MEDIUM** | arXiv 1103.5973 — *A Utility Based Approach to Energy Hedging* (2011). Applies log utility to energy hedging. Predates the NEM post-renewables era but must be explicitly distinguished in the literature review. |
| **LOW** | OIES EL-61 (Jan 2026) — Comprehensive NEM risk taxonomy from buyer perspective; no Kelly/log-wealth content. |
| **LOW** | arXiv 2503.13056 — Deep Hedging of Green PPAs (Mar 2025). ML hedging for PPAs; no log-wealth objective; no SME context. |
| **NONE detected** | No paper from 22–29 Jun 2026 directly combines Kelly criterion / log-wealth maximisation with NEM industrial buyer hedging or South Australian manufacturer risk management. |

**Recommended action:** Strengthen novelty framing by explicitly citing arXiv 1103.5973 and articulating the four-way novelty intersection: (1) log-wealth/Kelly objective function, (2) NEM contract structure (swaps + caps + PPAs), (3) South Australian post-renewable-transition price regime, (4) small-manufacturer balance-sheet constraints. No new competitor paper was published in the scan window.

---

*Next scan scheduled: 2026-06-30 · Sources: arXiv, SSRN, ScienceDirect, MDPI, OIES, WattClarity, AER, industry reports*
