# Semiconductor Cycle Report — 2026-10-03

**Report date:** 2026-10-03 (Saturday). Last completed trading day: **Friday 2026-10-02**. Staleness checks are relative to 2026-10-03.
**Run type:** **COMPARISON** against `semi-cycle-report-2026-09-26.md` (call then: **LATE upcycle, turn thesis rejected, confidence MEDIUM-HIGH**). That report named the 9/30 double-header (Aug PCE + Micron FQ4) as the next hard tells and a hot PCE pushing the 30Y decisively >5.5% with a SOX/SPX break as the invalidation trigger.

Repo: https://github.com/one-piece-of-ai/claude
This run's report: https://github.com/one-piece-of-ai/claude/blob/claude/main/reports/semi-cycle-report-2026-10-03.md

---

## 1. EXECUTIVE SUMMARY

**Both 9/30 tells landed bullish for the cycle and the SOX/SPX ratio rose a 5th straight week. LATE upcycle, turn thesis stays rejected; confidence MEDIUM-HIGH, edging toward HIGH on the demand side.** What changed vs. 9/26:
- **Micron FQ4 (9/30):** revenue **$54.23B** vs. ~$50.5–51.1B consensus, adj. EPS **$33.42** vs. ~$31.2, GM **87%**, FQ1 guide **~$61.5B / EPS $38.15**. The stock was flat to lower after hours because FY27 capex is heading past **$50B (~2x FY26)**. That capex ramp is the new watch item for the memory cycle.
- **Rates:** Aug core PCE was cooler than feared (**3.0% YoY, +0.2% MoM**), but the 30Y still hit **~5.63% (highest since 2002)** on 9/30. A weak Sep payrolls print on 10/2 (**+29K** vs. +84K forecast, unemployment 4.2%) pulled yields back (10Y ~5.18%) and cut Fed-hike odds.
- **SOX 13,136.7 (10/2), +2.4% on the day.** NVDA hit its first record since May.
- **Still pending:** SIA Aug sales, TSMC Sep revenue (~10/10), ASML Q3 (~mid-Oct).
- **New this run:** the agentic-AI → CPU thesis now has hard datapoints (AMD, Intel). See §3.

---

## 2. CYCLE DASHBOARD TABLE

| Indicator | Latest value (as-of date) | Direction | Cycle implication |
|---|---|---|---|
| Book-to-bill / equipment demand | NA book-to-bill discontinued (2022). Proxy: **SEMI Q2 2026 global equipment billings $40.53B, +23% YoY, +11% QoQ** (SEMI, 9/3). No new print; Q3 due ~early Dec. | Up (record; no new data) | Fabs are still committing capex ahead of demand. Micron's FY27 capex guide (>$50B, ~2x) corroborates the equipment pipeline |
| Semiconductor sales (WSTS/SIA) | **July $146.8B, +135.1% YoY, +6.4% MoM** (SIA, released early Sep). **August not yet found as released** (expected ~early Oct). | Flat (no new data) | Last read still accelerating. Not stale (<6 weeks), but the August print is due now. YoY is inflated by a low base and memory pricing; MoM is the cleaner read |
| SOX/SPX relative strength (high-freq) | **SOX 13,136.7 / SPX ~7,666 ≈ 1.71 (10/2)** vs. ~1.636 (9/25). SOX ~+3.7% on the week; SPX ~-1.0% (7,743.41 → ~7,666). SOX ~-10% off its 6/22 record (14,655). | **UP (5th straight week)** | The leading indicator keeps outperforming through a 2002-high yield backdrop. Caveat: one source cites a different SPX close (+0.7% day), so ratio and SPX weekly move are approximate |
| Memory pricing signal (DRAM/NAND) | TrendForce: **4Q26 conventional DRAM contract +10–15% QoQ**, AI-server-led. Micron FQ4 DRAM prices **up high-teens % QoQ** on mid-single-digit bit growth. Spot (10/2) mixed, wide DDR4/DDR5 ranges. Contract table last updated **2H Aug**. | Up (contract, decelerating rate) / spot mixed | Shortage intact. Pricing gains are moderating off a high base. HBM FY27 supply largely contracted at significantly higher prices |
| Foundry demand (TSMC revenue) | **August NT$514.8B (~US$16.35B), +53.3% YoY, +10.1% MoM** (TSMC, 9/10). Not stale. **Sep revenue due ~10/10.** | Up (no new data) | Record, 4th straight up-month. Next print ~10/10 |
| Capex outlook (ASML / bookings) | ASML **Q2 €9.3B, FY26 €43–45B** (7/15). Q3 + order intake **~mid-Oct** (not yet released). | Up / pending | Pipeline intact. Q3 order intake is the next 12–36-month forward read |

---

## 3. KEY SIGNALS INTERPRETATION

- **Demand momentum: accelerating.** Micron's revenue was $54.23B vs. $41.46B the prior quarter (+31% QoQ) and $11.32B a year ago. Guidance steps to ~$61.5B. TSMC and SIA were last read up. The leading indicator rose a 5th week.
- **Supply tightness vs. oversupply: tight.** Micron's DRAM revenue was a record $39.8B (+343% YoY, 73% of revenue). HBM FY27 bit supply is mostly contracted. No oversupply signal.
- **Memory cycle direction: strong / late-stage-intensifying, not peaking.**
  - *Internal tells to track:* Micron **DIO rose to 129 days (+9 days QoQ)**, which management attributes to node end-of-life build-ahead and incentive compensation, and expects to decline. The share-price reaction to the **>$50B FY27 capex** also matters, because capex ramps are historically how shortages end (12–24 months out).
  - *Agentic link (memory intensity):* agentic inference carries large KV-caches, long context and high concurrency. This is a structural support for DRAM/HBM demand. I found no Micron-specific agentic quantification in this run's sources, so this is inference, not a datapoint.
- **AI-driven demand vs. cyclical weakness:** AI demand dominates. The macro softening (payrolls +29K, UMich 4-month low last week) is a demand-side watch item outside semis, but it helped by lowering rate-hike odds.
- **Agentic AI → CPU reliance (standing thesis): supported by this period's data.**
  - *AMD (Q2, reported ~Aug):* data center revenue **$6.7B, +107% YoY**. Server CPU growth guided **>80% YoY**. AMD cites agentic AI as expanding CPU TAM (reported as $60B → $120B). Microsoft expanded 6th-gen EPYC deployments on Azure.
  - *Intel (Q2):* Data Center & AI **$6.3B, +59% YoY**.
  - *Supply:* secondary sources (not primary) report EPYC lead times ~30+ weeks, Intel Xeon under-shipping demand, and server CPU prices up ~20%+. Treat these as unverified.
  - *Architecture:* NVIDIA Vera (88-core Arm) is shipping, positioned for agentic orchestration. Arm's own AGI CPU (Neoverse V3, 136 cores) was announced 3/24. BofA reportedly forecasts the data center CPU market doubling to ~$60B by 2030.
  - *Verdict:* **materializing, not just narrative**. Server-CPU revenue growth has re-accelerated sharply (AMD, Intel), but part of that is cyclical refresh and pricing, so agentic attribution is partly management framing. No fresh Q3 CPU datapoints this week (AMD/Intel Q3 reports are late Oct). Hyperscaler custom-CPU (Graviton/Axion/Cobalt) unit data is not disclosed.

---

## 4. COMPANY READOUTS

- **Micron (FQ4, Sep 30): beat and raise, with capex the one flag.** Revenue $54.23B, adj. EPS $33.42, GM 87% (+210bp QoQ), guide ~$61.5B / $38.15. HBM revenue grew faster than company revenue, with most of CY27 HBM bit supply under agreement at significantly higher prices, narrowing the HBM–DRAM margin gap. DIO 129 days (+9, management expects it to fall). FY27 capex >$50B, with construction capex growing faster than equipment capex. Shares slipped after hours on the spend.
- **TSMC:** unchanged since 9/10. August NT$514.8B, +53.3% YoY; FY26 capex $60–64B; leading-edge utilization implicitly full. September revenue ~10/10.
- **ASML:** unchanged. Q2 €9.3B, FY26 €43–45B. Q3 order intake ~mid-Oct is the key forward read. Micron's >$50B FY27 capex and SEMI's record billings are supportive read-throughs.
- **CPU-side names (new section per standing thesis):**
  - *Intel:* DCAI $6.3B (+59% YoY, Q2).
  - *AMD:* data center $6.7B (+107% YoY); EPYC + Instinct; Anthropic up-to-2GW MI450 agreement and Microsoft EPYC/Helios expansion.
  - *Arm:* AGI CPU (3/24), royalty exposure through Vera/Graviton/Axion/Cobalt.
  - *NVIDIA:* Vera shipping; stock at a record 10/2 after a $150B buyback authorization.
  - *Cloud custom silicon:* no fresh data.
  - *Mix:* inference-vs-training mix datapoints not found this period.

---

## 5. CYCLE POSITIONING CALL

- **Where we are: LATE upcycle, with breadth widening** (GPU + HBM/DRAM + now server CPU). The SOX is ~-10% off its June record, so this is a recovery rather than a breakout.
- **Confidence: MEDIUM-HIGH.** Raised by Micron's beat/raise, the 5th rising SOX/SPX week and the rate relief from payrolls. Held back by: 30Y at ~2002-high yields; weak labor data that could become a demand problem; the DIO uptick; and a memory-industry capex ramp (Micron >$50B) that plants the seeds of an eventual supply response.
- **Key risk that invalidates this view:** (1) a rate shock that breaks the SOX/SPX ratio, now less likely with hike odds fading, but the 30Y trades near 5.6%; (2) evidence of memory pricing rolling over (contract gains decelerating faster, DIO rising again) combined with industry capex acceleration; (3) a hyperscaler capex pause, visible first in ASML bookings or TSMC.

---

## 6. WHAT TO WATCH NEXT (4–8 weeks)

- **SIA/WSTS August sales** (~early/mid Oct): is MoM growth still positive off $146.8B?
- **TSMC September revenue (~Oct 10) and Q3 earnings (~mid-Oct):** capex and utilization commentary.
- **ASML Q3 (~mid-Oct):** order intake, the 12–36-month capex read.
- **Q3 earnings, late Oct:** Intel, AMD, Arm and hyperscaler capex mix. This is the test of **server-CPU unit/ASP re-acceleration and "agentic workload" call-outs**, and whether CPU strength is broad or narrative.
- **NVIDIA FQ3 (~late Nov), Samsung/SK Hynix Q3:** HBM/DRAM pricing and capacity plans.
- **Macro:** the Fed's October meeting (hike odds faded), CPI, and the 30Y vs. ~5.5–5.6%.
- **SOX/SPX ratio weekly:** does it hold above ~1.6?
- **TrendForce:** 4Q26 contract updates (DRAM/NAND) and any 2027 capacity-addition commentary.

---

## 7. PORTFOLIO IMPLICATION

*(Separate from the objective analysis.)* Stay the course: keep the core semi sleeve (SMH/SOXX/NVDA) intact and keep writing covered calls, with strikes further OTM while the leading indicator is running. NVDA at a record argues against capping upside. Hold off on adding SOXL leverage until the TSMC/ASML prints (10/10 to mid-Oct) and the late-Oct CPU/hyperscaler earnings confirm breadth. No move toward defensive is warranted unless the SOX/SPX ratio breaks or memory pricing rolls over.

---

### Sources

- Micron FQ4 2026 results (9/30): [GlobeNewswire press release](https://www.globenewswire.com/news-release/2026/09/30/3372366/14450/en/micron-technology-inc-reports-record-fiscal-fourth-quarter-and-full-year-2026-results.html), [CNBC](https://www.cnbc.com/2026/09/30/micron-mu-q4-earnings-report-2026.html), [Investing.com call transcript](https://www.investing.com/news/transcripts/earnings-call-transcript-micron-tops-q4-2026-estimates-as-demand-stays-hot-93CH-4925992), [StockAnalysis transcript](https://stockanalysis.com/stocks/mu/transcripts/699706-q4-2026/), [IndMoney analysis](https://www.indmoney.com/blog/us-stocks/micron-stock-q4-earnings-analysis-mu)
- Aug PCE and yields (9/30): [CNBC: core PCE 3.0%](https://www.cnbc.com/2026/09/30/feds-preferred-gauge-showed-core-inflation-at-3point0percent-in-august-much-lighter-than-expected.html), [CNBC: Treasury yields](https://www.cnbc.com/2026/09/30/treasury-yields-bonds-selloff.html), [Yahoo Finance: September losses](https://finance.yahoo.com/markets/live/stock-market-today-wednesday-september-30-dow-sp-500-nasdaq-080339262.html)
- Sep jobs report and yields (10/2): [CNBC jobs report](https://www.cnbc.com/2026/10/02/jobs-report-september-2026.html), [CNBC Treasury yields](https://www.cnbc.com/amp/2026/10/02/treasury-yields-bonds-nonfarm-payrolls.html), [BLS Employment Situation](https://www.bls.gov/news.release/empsit.nr0.htm)
- Markets 10/2 (SOX 13,136.7, SPX ~7,666.45, Nasdaq): [TheStreet](https://www.thestreet.com/stock-market-today/stock-market-today-dow-jones-sp-500-nasdaq-updates-oct-02-2026), [Yahoo Finance](https://finance.yahoo.com/markets/live/stock-market-today-friday-october-2-dow-sp-500-nasdaq-september-jobs-report-080623878.html), [Investing.com SOX](https://www.investing.com/indices/phlx-semiconductor). NVDA record and $150B buyback: [Bloomberg](https://www.bloomberg.com/news/articles/2026-10-02/nvidia-hits-first-record-since-may-as-value-nears-6-trillion), [ROIC.ai](https://www.roic.ai/news/nvidia-shares-hit-first-record-high-since-may-on-150-billion-buyback-ai-demand-10-02-2026)
- Memory pricing: [TrendForce DRAM spot](https://www.trendforce.com/price/dram/dram_spot), [TrendForce press center](https://www.trendforce.com/presscenter)
- SIA July sales: [SIA market data](https://www.semiconductors.org/policies/tax/market-data/)
- AMD Q2 2026 / Intel Q2 2026: [AMD Newsroom](https://newsroom.amd.com/news/amd-2q-2026-earnings/), [Investing.com AMD slides](https://www.investing.com/news/company-news/amd-q2-2026-slides-data-center-revenue-doubles-ai-partnerships-expand-93CH-4836256), [Yahoo Finance AMD Q2](https://finance.yahoo.com/markets/stocks/articles/amd-q2-2026-earnings-record-202927876.html)
- Agentic CPU context (secondary, unverified supply claims): [Fusion Worldwide server CPU supply](https://www.fusionww.com/insights/server-cpu-shortage-2026), [Futurum on Arm](https://futurumgroup.com/insights/arms-15-billion-cpu-opportunity-hinges-on-agentic-data-center-design/), [Arm Newsroom](https://newsroom.arm.com/blog/arm-rubin-converged-ai-datacenter), [Forbes on NVIDIA Vera](https://www.forbes.com/sites/marcochiappetta/2026/07/21/nvidia-vera-redefines-server-cpu-performance-for-the-agentic-ai-era/)
- Carried from prior report (unchanged): SEMI Q2 billings (9/3), TSMC Aug revenue (9/10), ASML Q2 (7/15): [SEMI](https://www.semi.org/en/semi-press-release/global-semiconductor-equipment-billings-increased-23-percent-year-over-year-in-q2-2026-semi-reports), [TSMC IR](https://investor.tsmc.com/english/monthly-revenue/2026), [ASML](https://www.asml.com/en/news/press-releases/2026/q2-2026-financial-results)

*Data flags:*
1. *Book-to-bill is discontinued; the quarterly SEMI billings proxy is current (not stale).*
2. *SIA August not found as released; July is the latest confirmed print (<6 weeks old).*
3. *SOX 13,136.7 (10/2) is from search snippets. SPX close varies by source (~7,666.45 used), so the ratio (~1.71) and weekly percentages are approximate.*
4. *AMD/Intel Q2 figures are from search results and company sources; AMD's exact reporting date was not confirmed here (~early Aug assumed). Intel and AMD Q3 prints are late Oct.*
5. *CPU supply/lead-time/price claims come from secondary sources and are unverified.*
6. *No Micron-specific agentic commentary was verified; the memory-intensity link is inference.*
7. *TrendForce contract tables were last updated 2H Aug; exact levels are paywalled.*
8. *Micron consensus varied by source (~$50.5–51.1B revenue; ~$31.2–31.6 EPS).*
9. *Several primary pages (CNBC, TheStreet) returned 403 on fetch, so figures come from search summaries.*
