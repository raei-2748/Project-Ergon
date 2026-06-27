# Literature Synthesis — Project Ergon

Automated daily scan. Papers published within the prior 7 days are flagged **[NEW]**.
Potential threats to novelty claims are flagged **[NOVELTY RISK]**.

---

## Scan: 2026-06-27

### Topic 1 — NEM Electricity Hedging for Industrial Buyers

**Flottmann J., Wild P. & Todorova N. (2024)**
"Derivatives and hedging practices in the Australian National Electricity Market"
*Energy Policy* vol. 189, art. 114114.
<https://www.sciencedirect.com/science/article/pii/S0301421524001344>
*Key findings:* Survey of NEM participants shows PPA use rising while traditional ASX swap/cap liquidity declines (ASX-traded volumes fell 15% in 2024). Aside from a small number of sophisticated industrial customers, most end-use consumers are either unaware of the 5-minute clearing process or unable to respond to NEM spot prices. Rising contract premiums pass through to retail bills; consumers most exposed to liquidity deterioration.

**Flottmann J., Simshauser P., Wild P. & Todorova N. (2025)**
"The forward market dilemma in energy-only electricity markets"
Cambridge EPRG Working Paper 2502; also published *Energy Economics*.
<https://www.jbs.cam.ac.uk/wp-content/uploads/2025/02/eprg-wp2502.pdf> | SSRN 5127374
*Key findings:* Government-initiated CfDs for renewable entry crowd out on-market hedge capacity, creating structural primary-issuance shortages. Model results for the NEM show shortages materialise when off-market fixed-price CfDs dominate. Industrial buyers face reduced access to standard swaps/caps.
**[NOVELTY RISK — MODERATE]** The most comprehensive recent treatment of NEM hedge availability for all buyer classes. If the thesis argues industrial buyers face a structural hedging gap in the NEM, this paper pre-establishes that claim. Distinguish by: (a) decision-theoretic framing from the *buyer's* perspective (vs. market-design framing here), or (b) firm-level optimisation methodology.

**Yang D. (2026, January)**
"Risk Structure and Financial Hedging in Nodal Electricity Markets" — OIES EL-61.
<https://www.oxfordenergy.org/wpcms/wp-content/uploads/2026/01/EL-61-Risk-Structure-and-Financial-Hedging.pdf>
*Key findings:* Categorises five grid-risk types (locational congestion, temporal price, volume variability, demand/supply tail risks, regulatory design). Proposes Multi-Period Volume-Adjustable (MPVA) Financial Transmission Rights. Focus is on nodal markets (primarily US context); FTRs not applicable to the Australian NEM's zonal structure.
*Novelty status:* Not directly competing; different market architecture and no industrial-buyer decision framing.

**Anon. (2025, December) — ArXiv 2512.17508**
"Most certainly certain? The Impact of Contract for Difference Design on Renewables' Strike Prices and Electricity Market Risks"
<https://arxiv.org/abs/2512.17508>
*Key findings:* Empirical and modelling study on CfD strike-price design and its downstream effect on market risk premiums; NEM referenced as comparator for correlation between long-term hedge availability and lower LCOEs.
*Novelty status:* Generator/policy focus, not buyer-side decision-making.

**Anon. (2025, March) — ArXiv 2503.13056**
"Deep Hedging of Green PPAs in Electricity Markets"
<https://arxiv.org/abs/2503.13056>
*Key findings:* ML-based dynamic hedging strategies for Green PPA holders; outperforms static benchmarks. Retailer/generator counterparty orientation.
*Novelty status:* Method (deep RL hedging) differs from analytical/Kelly approach; no industrial buyer or NEM-SA focus.

**MDPI *Energies* (2026, January)**
"Research on Energy Futures Hedging Strategies for Electricity Retailers' Risk Based on Monthly Electricity Price Forecasting"
<https://www.mdpi.com/1996-1073/19/2/552>
*Key findings:* Monte Carlo + t-GARCH model for CVaR minimisation; optimal futures portfolio weights for electricity *retailers*.
*Novelty status:* Retailer, not industrial buyer; no NEM-specific or Kelly connection.

**2025 NEM Review (Final Report) — Expert Panel**
Recommends: Market Making Obligation (MMO) for liquidity; standardised exchange-tradeable contracts in parcels of ~100 kW; ESEM pilot late 2026, formal commencement early 2027.
<https://shellenergy.com.au/energy-insights/understanding-the-2025-national-electricity-market-nem-review/>
*Relevance:* Policy context only; confirms the gap in standardised products accessible to smaller industrial buyers.

---

### Topic 2 — Log-Wealth Maximisation / Kelly Criterion at Firm Level

**Atlas Peak Research (2026, April)**
"The Kelly Criterion in Financial Markets: Optimal Position Sizing, Portfolio Construction, and Risk Management"
<https://www.atlaspeakresearch.com/report/07bf72>
*Key findings:* Practitioner synthesis; positions full Kelly as theoretical ceiling and fractional Kelly as operating heuristic. Addressed to financial market participants, not non-financial firms.
*Novelty status:* No firm-level operational hedging angle; investment-portfolio framing.

**ArXiv 2508.18868 (2025, November revision)**
"Tackling estimation risk in Kelly investing using options"
<https://arxiv.org/abs/2508.18868>
*Key findings:* Options used to build Kelly-optimal portfolios robust to parameter misspecification. Financial-market context.
*Novelty status:* No connection to energy procurement or real-asset firm operations.

**ArXiv 2508.16598 (2025, August)**
"Sizing the Risk: Kelly, VIX, and Hybrid Approaches in Put-Writing on Index Options"
<https://arxiv.org/abs/2508.16598>
*Key findings:* Kelly + VIX-weighted position sizing for equity options. Financial-market context only.

**ArXiv 2502.16859 (2025, February)**
"The Kelly Criterion And Utility Function Optimisation For Stochastic Binary Games: Submartingale And Supermartingale Regimes"
<https://arxiv.org/abs/2502.16859>
*Key findings:* Theoretical analysis of Kelly under different stochastic game regimes. No applied energy context.

**Medium / informal (2025, March)**
"Risk Management Using Kelly Criterion" (tmapendembe)
<https://medium.com/@tmapendembe_28659/risk-management-using-kelly-criterion-2eddcf52f50b>
*Key findings:* Informal worked example applying asymmetric Kelly to electricity price hedging — with 60% probability of price falls (5% gain) vs. 40% probability of rally (7% loss), optimal hedge fraction ≈ 57% of monthly production.
**[NOVELTY RISK — LOW]** This is a non-peer-reviewed blog post, not academic work. Nevertheless, it demonstrates the conceptual link between Kelly and electricity hedging is circulating in practitioner discourse. If the thesis introduces Kelly to electricity procurement as a *novel academic* contribution, this must be noted (though it does not constitute prior academic art).

*Summary gap:* No academic paper found applying log-wealth maximisation or Kelly criterion to **firm-level operational hedging of energy input costs** in a manufacturing or industrial context. This gap appears to be intact as at 2026-06-27.

---

### Topic 3 — South Australian Electricity Market Volatility

**WattClarity (2026, January 27)**
"After Adelaide's Hottest Night on Record, SA Sees Flashes of Further Price Volatility"
<https://wattclarity.com.au/articles/2026/01/after-adelaides-hottest-night-on-record-sa-sees-flashes-of-further-price-volatility-on-tuesday-morning-27th-january-2026/>
*Key findings:* Prices hit $19,000/MWh across 28 dispatch intervals on 27 Jan 2026 during Adelaide heatwave (>43°C) when interconnectors were constrained and cooling demand surged. Third-highest average daily spot price outcome in SA NEM history.

**Energy-Storage.News (2026, January)**
"South Australia battery storage captures 4-hour AU$1,000/MWh price event as heatwave drives revenue uplift"
<https://www.energy-storage.news/south-australia-battery-storage-captures-4-hour-au1000-mwh-price-event-as-heatwave-drives-revenue-uplift/>
*Key findings:* BESS operators captured sustained $1,000/MWh price window during SA heatwave; highest battery revenue week of 2026. Demonstrates that BESS is increasing as a price-setting participant during spikes, altering traditional volatility dynamics.

**Leading Edge Energy / Utilizer (2026, Q1 Market Reviews)**
<https://leadingedgeenergy.com.au/blog/electricity-market-review-latest/>
<https://utilizer.com.au/energy-insights/energy-market-update-australia-q1-2026/>
*Key findings:* SA Q1 2026 average wholesale price $88/MWh — up 33% year-on-year; only NEM region to record a YoY increase. SA simultaneously described as "most stable" NEM region in benign periods (high renewable penetration + strong interconnection) but most exposed in constraint events.

**ArXiv 2311.07289 — Manner, Roberts et al. (2023, published)**
"A probabilistic forecast methodology for volatile electricity prices in the Australian National Electricity Market"
<https://arxiv.org/abs/2311.07289>
*Key findings:* SA identified as exhibiting the highest price volatility levels of any modern electricity market; quantile regression ensemble for probabilistic forecasting outperforms constituent models. Confirms SA structural volatility characteristics used in this project's motivation.

**Springer Nature (2025, April)**
"Intertwined renewable and digital transitions: a study on South Australia's hybridized electricity system"
*Sustainability Science*. <https://link.springer.com/article/10.1007/s11625-025-01647-1>
*Key findings:* SA advancing toward 100% renewable electricity by 2030; hybridised system (high-VRE + storage + interconnection + demand response) as a global transition case study. Discusses price volatility as a systemic feature, not a bug.

**SAPC / University of Western Australia (commissioned research)**
"Analysis of historical wholesale electricity spot price volatility in South Australia"
<https://www.sapc.sa.gov.au/inquiries/inquiries/south-australias-renewable-energy-competitiveness/commissioned-research-to-support-the-inquiry/Question-C-Projections-of-spot-price-volatility-UoW.pdf>
*Key findings:* Quantitative projections of SA spot-price volatility for the SA Productivity Commission inquiry. Provides baseline volatility statistics directly applicable to hedging modelling.

**NextG Power (2026)**
"Australia BESS Market 2026-27: Mastering NEM Volatility & FCAS Revenue Stacking"
<https://nextgpower.com/australia-bess-market-2026-27-mastering-nem-volatility-fcas-revenue-stacking/>
*Relevance:* Industry outlook confirming BESS participation is reshaping SA volatility and dispatch dynamics — relevant to any hedging model that uses historical SA spot price distributions.

---

### Topic 4 — Small Manufacturer Financial Resilience and Input Costs

**Springer — Review of Managerial Science (2025)**
"Resilience of small and medium-sized enterprises in times of crisis: an umbrella review"
<https://link.springer.com/article/10.1007/s11846-025-00883-0>
*Key findings:* Meta-synthesis of SME resilience literature; identifies financial reserves, relational capital, and operational flexibility as key resilience dimensions. Energy cost shock not treated as a distinct driver.

**ICAEW (2026, April)**
"Manufacturing: how to control energy costs to manage volatility"
<https://www.icaew.com/insights/viewpoints-on-the-news/2026/apr-2026/manufacturing-how-to-control-energy-costs-to-manage-volatility>
*Key findings:* Strategic energy procurement with a 2–3 year forward horizon identified as essential for manufacturing competitiveness. Energy has shifted from a routine procurement exercise to a financial, operational, and infrastructure issue. Targeted at UK manufacturers but principles apply to Australian context.

**IEA (2023)**
"Coping with the Crisis: Increasing Resilience in Small Businesses in Europe through Energy Efficiency"
<https://www.iea.org/reports/coping-with-the-crisis-increasing-resilience-in-small-businesses-in-europe-through-energy-efficiency>
*Key findings:* Cost-effective energy efficiency measures could reduce SME energy demand by 30%; enhanced efficiency frees capital for productive reinvestment, strengthening competitiveness and resilience. European context; no hedging or financial derivatives angle.

**OECD (2026)**
"Scaling Up Public Financial and Non-Financial Support for SME Sustainability"
<https://www.oecd.org/en/publications/scaling-up-public-financial-and-non-financial-support-for-sme-sustainability_bf835159-en.html>
*Key findings:* SMEs face disproportionate barriers in accessing financing for energy transition investments. Highlights capital constraints as the binding constraint on energy resilience for small firms.

**Pew Charitable Trusts (2026, April)**
"Distributed Energy Can Unleash the Resilient, Affordable Grid of the Future"
<https://www.pew.org/en/research-and-analysis/reports/2026/04/distributed-energy-can-unleash-the-resilient-affordable-grid-of-the-future>
*Relevance:* Distributed generation framed as a resilience tool for commercial and industrial energy buyers facing volatile grid prices.

*Summary gap:* No academic paper found specifically combining: (a) small/mid-size manufacturers + (b) financial hedging of energy input costs + (c) Australian NEM context + (d) financial resilience framing. This intersection remains an open research gap as at 2026-06-27.

---

## Novelty Threat Summary — 2026-06-27

| Threat | Paper | Severity | Mitigation |
|--------|-------|----------|------------|
| NEM industrial hedging gap already documented | Flottmann et al. (2025), *Forward Market Dilemma* | Moderate | Distinguish by buyer-side decision theory / firm-level optimisation vs. market-design focus |
| Kelly applied to electricity hedging informally | Medium blog post, Mar 2025 | Low | Not academic; no NEM or firm-level treatment; cite and distinguish |
| CfD design / NEM risk covered | ArXiv 2512.17508 (Dec 2025) | Low | Generator/policy framing, not buyer optimisation |
| SA volatility well-characterised | ArXiv 2311.07289; SAPC/UoW | Background | These support rather than threaten novelty — use as inputs |
| Kelly at firm level in energy context | **None found** | **None** | Gap intact; key novelty claim holds |
| Small-manufacturer NEM hedging | **None found** | **None** | Gap intact |

---

*Next scan due: 2026-07-04*
