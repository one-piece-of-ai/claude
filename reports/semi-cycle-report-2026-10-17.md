# Semiconductor Cycle Report — 2026-10-17

**Report date:** 2026-10-17 (Saturday). Last completed trading day: **Friday 2026-10-16**. Staleness checks are relative to 2026-10-17.
**Run type:** **COMPARISON** against `semi-cycle-report-2026-10-10.md` (call then: **LATE upcycle, turn thesis rejected, confidence MEDIUM-HIGH on fundamentals, MEDIUM on the weekly price signal**; pending: TSMC Q3, ASML Q3, SOX/SPX verification, SEMI Sep billings).

Repo: https://github.com/one-piece-of-ai/claude
This run's report: https://github.com/one-piece-of-ai/claude/blob/claude/main/reports/semi-cycle-report-2026-10-17.md

---

## 1. EXECUTIVE SUMMARY

**Fundamentals strengthened again (TSMC and ASML both guided sharply higher); the equity signal weakened. LATE upcycle, turn thesis still rejected; confidence MEDIUM-HIGH on fundamentals, but the SOX/SPX divergence is now a real warning.** What changed vs. 10/10:
- **TSMC Q3 (10/15): revenue US$46.72B (+41.2% YoY, +16.2% QoQ), GM 66.4%. Q4 guide US$52.3–54.3B (~+14% QoQ, ~+58% YoY at midpoint), GM 65–67%.** 2026 capex held at $60–64B. A sequential acceleration in the guide.
- **ASML Q3 (10/14): sales €11.7B, GM 57.5%; Q4 guide €14.2–15.2B (+~25% QoQ); FY26 narrowed to €44–45B.** Management says planned 2027–28 supply "will not fully meet" customer demand, and some customers are asking about 2029–30 orders. Order intake is not disclosed, so this is the strongest 12–36 month capex read available.
- **Chips sold off hard this week:** the SOX fell 1.5% on 10/13, its 5th straight daily loss and a one-month low, on China CXMT memory-competition worries and a Broadcom CEO "casino gambling" comment about AI spending (secondary reporting, not verified at source). NVDA fell 3.2% on 10/14. This is a second consecutive week of chips lagging, so the SOX/SPX lead-lag signal has probably turned negative.
- **Still pending:** SEMI Sep billings (~10/21), Intel (10/29), Samsung full Q3 (10/29), SK Hynix, AMD (date unconfirmed), hyperscaler capex.

---

## 2. CYCLE DASHBOARD TABLE

| Indicator | Latest value (as-of date) | Direction | Cycle implication |
|---|---|---|---|
| Book-to-bill / equipment demand | NA book-to-bill discontinued (SEMI NA release stopped Feb 2022). Proxy: **SEMI Q2 2026 global billings $40.53B, +23% YoY, +11% QoQ** (SEMI, 9/3), second straight record. No newer SEMI figure found; next monthly update ~10/21. ASML's Q4 guide (+~25% QoQ) implies equipment demand is still rising. | Up (record; no new SEMI data) | Capex still expanding ahead of demand. Quarterly proxy is <6 weeks old, so not stale |
| Semiconductor sales (WSTS/SIA) | **Aug $159.7B, +8.0% MoM, +144.3% YoY** (SIA, 10/5; 3-mo moving average). Jul revised to $147.9B. No newer release (Sep due ~early Nov). Carried from the 10/10 report. | Up (accelerating) | Strongest fundamental read in the series. YoY is inflated by memory pricing and a low base, so weight MoM |
| SOX/SPX relative strength (high-freq) | **Weaker.** SOX fell 1.5% on 10/13, 5th straight daily loss, one-month low (secondary report, 10/13); Nasdaq Comp -1.88% and NVDA -3.2% to $221.30 on 10/14 (heygotrade, one source, article's date is inconsistent). **No verified SOX or SPX closes for 10/9–10/16 were found, so the ratio cannot be computed.** | **Down (directional, unverified)** | Second week of chip underperformance and a lower low. Leading indicator now flashing caution while fundamentals accelerate: classic late-cycle divergence |
| Memory pricing signal (DRAM/NAND) | Latest TrendForce spot read: **9/16** (DDR4 1Gx8 3200 avg $45.54, +0.47% WoW; "DDR5 inquiries slowed, some prices softening"). **>4 weeks old; treat as dated.** 4Q26 contract guide (TrendForce, 9/30, via third-party tracker NextMSC 10/9): **DRAM +10–15% QoQ, NAND +15–20%** (unverified at source). | Up (contract) / spot cooling | Contract still rising but spot softening is the first sign of an inflection; consistent with a deceleration phase. Chip-sector worry about CXMT supply is the new bear angle |
| Foundry demand (TSMC revenue) | **Q3 US$46.72B, +41.2% YoY; Q4 guide US$52.3–54.3B** (TSMC, 10/15). Sep monthly NT$511.9B, +54.6% YoY, -0.6% MoM (10/8). Advanced nodes (7nm and below) 79% of wafer revenue; 3nm 33%, 2nm 8%. | Up | Demand strong and re-accelerating into Q4. GM 66.4% shows pricing power and utilization |
| Capex outlook (ASML / equipment) | **ASML Q3 sales €11.7B, GM 57.5%; Q4 guide €14.2–15.2B; FY26 €44–45B** (ASML, 10/14). "Order book momentum continues to increase quarter on quarter." No bookings figure disclosed. TSMC 2026 capex $60–64B unchanged (Q3 capex $13.8B). | Up | 12–36 month pipeline intact and extended: supply for 2027–28 "will not fully meet" demand. Equipment is a lagging beneficiary of AI capex, so this confirms the cycle's duration, not its peak |

---

## 3. KEY SIGNALS INTERPRETATION

- **Demand momentum: accelerating (fundamentals).** TSMC guides Q4 +14% QoQ after Q3 +16%; ASML guides Q4 +~25% QoQ; SIA MoM rose to +8.0% (Aug).
- **Supply tightness vs. oversupply: tight.** ASML says its supply plan falls short of customer demand through 2028. TSMC's gross margin is 66%+. No oversupply signal in hard data. Watch China (CXMT) memory capacity as the potential supply-side crack: **market reaction is documented, the actual capacity or price evidence is not, and I did not verify the story at source.**
- **Memory cycle direction: strong, late-stage, spot softening.** Contract guide Q4 is +10–15% DRAM (decelerating from Q3's +13–18%); spot cooled in mid-Sept; memory equities sold off this week. Industry capex (Micron FY27 >$50B, Samsung's record profit) is ramping, which is how shortages eventually end, with a 12–24 month lag. *Agentic link (memory intensity):* long-context, high-concurrency agent loops with large KV-caches add DRAM/HBM demand per unit of compute; I found no new quantified datapoint this period, so this stays a structural argument, not a measurement.
- **AI-driven demand vs. cyclical weakness:** AI dominates. The risk is not current demand but **durability of AI financing** (last week's OpenAI revenue scare, this week's "casino gambling" remark and CXMT). Hard data (TSMC, ASML) shows no weakening.
- **Agentic AI → CPU reliance (standing thesis): supported but no fresh earnings datapoint this period.**
  - Intel Q3 is **10/29** (company-confirmed); AMD Q3 date not confirmed (third-party estimate 11/3). No CPU-side company reported this week.
  - *Carried hard data (Q2):* AMD data center $6.7B (+107% YoY); Intel DCAI $6.3B (+59% YoY); Intel CFO said (Q1 call) the CPU:GPU deployment ratio moved from 1:8 to ~1:4. AMD says it doubled its server-CPU TAM forecast to $120B on agentic demand; EPYC 9006 "Venice" (Zen 6, TSMC 2nm) launched 7/23.
  - *Projections (not measurements):* TrendForce CPU:GPU toward 1:1–1:2; Citi agentic-CPU market $59.4B by 2030; Cornell research cited at ~44% of agentic-workflow compute on CPUs.
  - *Share data (secondary):* Intel's x86 server revenue share 54.9% vs AMD 46.2% (Q1 2026 per a secondary summary; the figures sum above 100%, so basis differs; treat as indicative only). Arm-based custom silicon (Graviton, Cobalt, Axion, Vera) reportedly ~37% of the market (single analysis, unverified).
  - Supply claims (EPYC sold out, Intel lead times 8–22 weeks, +10% list prices) come from one distributor's marketing blog: unverified.
  - *TSMC read-through:* 2nm at 8% of wafer revenue in its first quarters, with Venice and other 2nm CPUs part of the ramp, is consistent with, but does not prove, CPU demand.
  - *Verdict:* plausible and supported by vendor revenue, but not yet confirmed as agentic-specific. The test is Intel on 10/29 and AMD in early Nov: server-CPU unit/ASP re-acceleration and explicit agentic call-outs.

---

## 4. COMPANY READOUTS

- **Micron:** no new earnings since FQ4 (9/30): revenue $54.23B, GM 87%, FQ1 guide ~$61.5B, DIO 129 days, FY27 capex >$50B (carried from prior reports). Shares fell sharply 10/13 on CXMT competition worries (sentiment, not fundamentals). Next: FQ1 in Dec.
- **TSMC (10/15):** Q3 NT$1,494.24B (US$46.72B), net income NT$763.06B, EPS NT$29.43, GM 66.4%, operating margin 58.7%. Q4 guide US$52.3–54.3B, GM 65–67%, op margin 56.5–58.5%. 2026 capex $60–64B (unchanged after the July raise from $52–56B). A secondary summary says shares fell ~1.7% on margin dilution from capacity spending (not verified against the transcript). Utilization effectively full at the leading edge. 2027 capex not guided; analyst estimates (~$75–80B, Morgan Stanley pre-earnings) are forecasts only.
- **ASML (10/14):** Q3 sales €11.7B, GM 57.5%, net income €5.0B. Q4 guide €14.2–15.2B, GM ~57%; FY26 €44–45B (raised floor). No bookings disclosed; CEO: order book momentum increasing quarter on quarter; customers raising short and medium-term demand forecasts, some discussing 2029–30 orders; 2027–28 supply will not fully meet demand. Capacity +30% in 2027, studying another +30% in 2028. **Capex-pipeline signal: positive, extends cycle duration into 2028+.**
- **Samsung:** prelim Q3 operating profit ~KRW 107.4T (10/8); full results 10/29. SK Hynix Q3 not yet reported (late Oct).
- **CPU-side names (Intel, AMD, Arm, NVIDIA Vera/Grace, Graviton/Axion/Cobalt):** no new reports this period; see Section 3. Inference-vs-training mix: no fresh datapoint.

---

## 5. CYCLE POSITIONING CALL

- **Where we are: LATE upcycle, breadth widening (GPU + HBM/DRAM + equipment + server CPU), with an equity-market divergence.** Agentic CPU demand remains a *positive breadth indicator* that is revenue-supported (AMD/Intel Q2) but awaiting Q3 confirmation.
- **Confidence: MEDIUM-HIGH** on the late-upcycle label (fundamentals unambiguous), **MEDIUM** on near-term direction because the leading price indicator is deteriorating. Not yet a turn: no hard data (billings, sales, TSMC guide, ASML guide) has rolled over.
- **Key risk that invalidates this view:** (1) AI-financing shock leading to hyperscaler capex cuts, seen first in late-Oct hyperscaler capex guides or TSMC's next guide; (2) the SOX/SPX divergence persisting through earnings while fundamentals still print strong (equities discount a peak 2–3 quarters early); (3) memory spot and contract prices rolling over while CXMT and Big-3 capacity ramps; (4) rate/oil shock (30Y yields and oil were elevated in the last report; not refreshed).

---

## 6. WHAT TO WATCH NEXT (4–8 weeks)

- **SOX/SPX weekly:** a verified ratio series; does it stabilize after the one-month low?
- **SEMI Sep billings (~10/21)** and SEMI Q3 global billings (~early Dec).
- **Hyperscaler Q3 earnings (MSFT/GOOGL/AMZN/META, late Oct; dates not confirmed this run):** capex guides, mix toward general-purpose compute, agentic call-outs.
- **Intel Q3 (10/29, confirmed):** DCAI revenue/ASP, Xeon supply, agentic commentary. **AMD Q3 (~11/3, unconfirmed):** EPYC vs Instinct.
- **Samsung full Q3 (10/29); SK Hynix Q3 (late Oct):** HBM/DRAM mix, capex, CXMT commentary.
- **TrendForce Oct/Nov DRAM and NAND contract and spot updates:** does spot keep softening?
- **SIA Sep sales (~early Nov); NVIDIA FQ3 (~late Nov); Micron FQ1 (Dec).**
- **Macro:** Fed/CPI, 30Y yield, oil.

---

## 7. PORTFOLIO IMPLICATION

*(Separate from the objective analysis.)* Stay the course on the core sleeve (SMH/SOXX/NVDA), but keep the mildly defensive call-book tilt (strikes closer to the money on NVDA/SOXX) and do not add SOXL while the SOX/SPX signal is negative; fundamentals do not justify raising cash yet. Consider trimming leverage if the ratio makes another lower low before the late-Oct earnings.

---

### Sources

- TSMC Q3 2026 results (10/15): [TSMC press release](https://pr.tsmc.com/english/news/3346), [SEC 6-K](https://www.sec.gov/Archives/edgar/data/0001046179/000104617926000726/a3q26e_withguidancexfinal.htm), [FourWeekMBA](https://fourweekmba.com/ai-tsmc-q3-revenue-rises-to-46-7b-with-a-66-4-gross-margin/), [CryptoBriefing](https://cryptobriefing.com/tsmc-q4-revenue-forecast-record-q3-profit/)
- ASML Q3 2026 (10/14): [SEC 6-K press release](https://www.sec.gov/Archives/edgar/data/0000937966/000162828026065813/pressreleasefinancialresul.htm), [Capital.com](https://capital.com/en-au/news/asml-reports-11-7-billion-total-net-sales-and-5-0-billion), [Vested Finance](https://vestedfinance.com/blog/us-stocks/asml-q3-earnings-2026/)
- Market moves: [NVDA 10/15 note](https://www.heygotrade.com/en/news/nvidia-nvda-stock-news-october-15-2026/), [NVDA 10/14 note](https://www.heygotrade.com/en/news/nvidia-nvda-stock-news-october-14-2026/), [NewsBytes: chip stocks one-month low](https://www.newsbytesapp.com/news/business/us-chip-stocks-hit-month-low-after-cxmt-memory-advances/tldr)
- SEMI Q2 billings (9/3): [SEMI](https://www.semi.org/en/semi-press-release/global-semiconductor-equipment-billings-increased-23-percent-year-over-year-in-q2-2026-semi-reports)
- Memory pricing: [DRAMeXchange/TrendForce weekly](https://www.dramexchange.com/WeeklyResearch/Post/2/12476.html), [NextMSC tracker (10/9)](https://www.nextmsc.com/industry-deep-dive/dram-nand-price-tracker-quarterly)
- Intel Q3 date: [Intel IR](https://www.intc.com/news-events/press-releases/detail/1782/intel-to-report-third-quarter-2026-financial-results); AMD date estimate: [days.to](https://days.to/amd-earnings)
- Agentic CPU: [SoftwareSeni](https://www.softwareseni.com/how-ai-agents-are-reshaping-server-cpu-demand-and-data-centre-architecture), [AMD blog](https://amd.com/en/blogs/2026/agentic-ai-amd-epyc-9005-cpus-wins-today-epyc-9006.html), [Fusion Worldwide](https://info.fusionww.com/blog/server-cpu-shortage-2026), [TrendForce insight](https://insights.trendforce.com/p/agentic-ai-cpu-gpu)
- Carried from 10/10 report: SIA Aug sales ([SIA](https://www.semiconductors.org/policies/tax/market-data/)), TSMC Sep revenue ([TSMC](https://pr.tsmc.com/english/news/3343)), Samsung prelim, Micron FQ4, Intel/AMD Q2.

*Data flags:*
1. *Book-to-bill is discontinued; SEMI Q2 billings (9/3) is the latest proxy. Monthly SEMI update ~10/21 not yet out.*
2. *SOX/SPX: no verified SOX or SPX closes for 10/9–10/16 were found (undated SOX snapshots of ~11,819 and ~7,833 conflict and were not used). The "down" call rests on secondary reports of a 5-day SOX losing streak ending 10/13 and a 10/14 NVDA/Nasdaq drop; the NVDA article's dating is inconsistent. Treat as directional only.*
3. *The cause of the 10/13 selloff (CXMT memory advances, Broadcom CEO comment) is from an aggregator summary I could not open (403); not verified at source.*
4. *DRAM/NAND spot: latest found is 9/16 (>4 weeks); no October spot figure found. 4Q26 contract guide is from a third-party tracker citing TrendForce 9/30; not verified at source.*
5. *ASML does not disclose order intake (since Q1 2026); "record bookings" headlines from some outlets are not supported by the company release. Do not rely on them.*
6. *TSMC capex-dilution and share-reaction details are from a single secondary summary; 2027 capex figures are analyst forecasts.*
7. *Server-CPU supply/price/share claims are from vendor, distributor and secondary sources; Intel/AMD figures carried from Q2. Hyperscaler Q3 dates and AMD Q3 date not confirmed.*
8. *SIA Aug sales (10/5) is the latest monthly release (<6 weeks); carried from the 10/10 report.*
