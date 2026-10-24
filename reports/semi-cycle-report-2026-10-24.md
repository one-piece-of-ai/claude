# Semiconductor Cycle Report — 2026-10-24

**Report date:** 2026-10-24 (Saturday). Last completed trading day: Friday 2026-10-23. Staleness checks are relative to 2026-10-24.
**Run type:** COMPARISON against `semi-cycle-report-2026-10-17.md` (call then: LATE upcycle, turn thesis rejected, confidence MEDIUM-HIGH on fundamentals, MEDIUM on near-term direction; SOX/SPX divergence flagged).

Repo: https://github.com/one-piece-of-ai/claude
This run's report: https://github.com/one-piece-of-ai/claude/blob/claude/main/reports/semi-cycle-report-2026-10-24.md

---

## 1. EXECUTIVE SUMMARY

**The equity warning is now confirmed with verified data; hard fundamentals have not rolled over. LATE upcycle, still not a turn; confidence MEDIUM-HIGH on fundamentals, MEDIUM on near-term direction.** What changed vs. 10/17:
- **SOX verified: 8 straight down sessions, 10/7–10/16, about -16%, the longest losing streak since 2008** (247wallst/Motley Fool/Mitrade, 10/17–10/20). Last week's report only had secondary hints. Triggers cited: AI-ROI doubts, credit stress (CoreWeave -12%, bonds near distress levels) and hot inflation/PPI prints. Stocks rebounded 10/19. I could not verify closes for 10/20–10/23, so the current ratio is unknown.
- **Lam Research (10/21), single source:** revenue $8.22B vs $8.13B expected, systems $5.73B, China $2.88B, Dec-quarter guide ~$8.6B. Shares sold off despite the beat. Equipment demand is still rising (see the caveat in the flags).
- **Memory: TrendForce 10/21 bulletin says DDR5 is hard to source, suppliers are reluctant to sell, and vendors are pushing for bigger Q4 contract hikes.** This eases last week's "spot softening" worry. DDR4 spot +0.84% WoW to $46.357 (10/20). NAND wafer spot -1.28% WoW.
- **Not out yet:** SEMI Sep billings (not found), Intel/Samsung (10/29), SK Hynix Q3, hyperscaler Q3 capex, AMD, SIA Sep sales.

---

## 2. CYCLE DASHBOARD TABLE

| Indicator | Latest value (as-of date) | Direction | Cycle implication |
|---|---|---|---|
| Book-to-bill / equipment demand | NA book-to-bill discontinued (Feb 2022). Proxy: **SEMI Q2 2026 global billings $40.53B, +23% YoY, +11% QoQ** (SEMI, 9/3). No Sep monthly figure found (searched 10/24). Lam FQ1 (10/21, one source): revenue $8.22B, Dec guide ~$8.6B. | Up (record; proxy unchanged) | Capex still expanding. The SEMI figure is under 8 weeks old but quarterly, so it is not stale |
| Semiconductor sales (WSTS/SIA) | **Aug $159.7B, +8.0% MoM, +144.3% YoY** (SIA, 10/5, 3-mo avg). No newer release; Sep due ~early Nov. | Up | Strongest fundamental read. YoY is inflated by memory prices and a low base, so weight MoM |
| SOX/SPX relative strength | **SOX -16% over 8 sessions 10/7–10/16**, longest losing streak since 2008. NVDA $239.24 (10/6 record close) to $214.13 (10/16), about -10%. MU -5.6% and AMD -5.9% on 10/16. Broad market rebounded 10/19. **No verified SOX/SPX closes after 10/16.** | **Down (verified through 10/16)** | The leading indicator is firmly negative. Historically equities discount a peak 2–3 quarters early. This is the cycle's main warning |
| Memory pricing signal | TrendForce 10/21: DDR5 spot tight, suppliers reluctant to sell. DDR4 1Gx8 3200 avg $46.357 (+0.84% WoW, 10/20). NAND 512Gb TLC wafer $18.592 (-1.28% WoW). Q4 DRAM contract: conflicting, +10–15% (TrendForce 9/30 via NextMSC) vs ~+20% (secondary summary of TrendForce 10/20). | Up (DRAM) / slightly down (NAND spot) | Still tight, but the rate of rise is decelerating (Q2 ~+80%, Q3 ~+40%, Q4 +10–20%). Late-cycle shape: price still rising, second derivative negative |
| Foundry demand (TSMC) | **Q3 $46.72B, +41.2% YoY; Q4 guide $52.3–54.3B** (TSMC, 10/15). Carried from 10/17. | Up | Full utilization, 66.4% GM. No new TSMC data this week |
| Capex outlook (ASML / equipment) | **ASML Q4 guide €14.2–15.2B; FY26 €44–45B**; 2027–28 supply "will not fully meet" demand (ASML, 10/14). Lam as above. | Up | Confirms the cycle's duration into 2028+. Equipment is a lagging beneficiary, so it does not call the peak |

---

## 3. KEY SIGNALS INTERPRETATION

- **Demand momentum: accelerating in hard data (TSMC, ASML, Lam, SIA), but the equity market is pricing a peak or financing risk.** The gap between the two is the story of this phase.
- **Supply tightness vs. oversupply: tight.** DDR5 allocation-constrained, ASML supply short through 2028. China CXMT is the supply-side bear angle; the market reaction is documented, capacity and price evidence is not.
- **Memory cycle direction: strong but decelerating (late stage).** Contract still rising, but each quarter's increase is smaller. Higher component prices are already feeding into customer capex (Q1 hyperscaler commentary: Microsoft ~$25B of 2026 capex from component pricing, Meta raising capex on component prices). That is a classic late-cycle feedback loop: price inflation raises buyers' costs and eventually curbs unit demand. *Agentic link:* long-context, high-concurrency agent loops with large KV-caches raise DRAM/HBM per unit of compute. No new quantified datapoint this period, so it remains a structural argument.
- **AI-driven demand vs. cyclical weakness:** AI dominates. The risk is AI financing and ROI (CoreWeave credit stress, inflation/rates), not current order flow.
- **Agentic AI → CPU reliance (standing thesis): no fresh CPU datapoint this period.**
  - No Intel, AMD, Arm, NVIDIA or cloud-silicon earnings landed this week. Intel Q3 is 10/29 (company-confirmed); AMD ~11/3 (unconfirmed estimate).
  - Carried (Q2): AMD data center $6.7B (+107% YoY); Intel DCAI $6.3B (+59%); Intel CFO said the CPU:GPU ratio moved from 1:8 to ~1:4 (Q1 call). AMD doubled its server-CPU TAM forecast to $120B citing agentic demand. Projections (TrendForce, Citi) are not measurements.
  - Amazon said in April its in-house chip business topped a $20B revenue run rate (Q1 hyperscaler coverage); no Q3 update yet.
  - Verdict: plausible and revenue-supported but not confirmed as agentic-specific. The test is Intel 10/29, hyperscaler Q3 calls, and AMD in early Nov (server CPU units/ASPs and explicit agentic call-outs). Treat it as a positive breadth indicator only once it appears in the numbers.

---

## 4. COMPANY READOUTS

- **Micron:** no new earnings since FQ4 (9/30): revenue $54.23B, GM 87%, FQ1 guide ~$61.5B, DIO 129 days, FY27 capex >$50B (carried). Stock -5.6% on 10/16 in the chip selloff. Next: FQ1 in December.
- **TSMC:** no new data since 10/15 (Q3 $46.72B, GM 66.4%, Q4 guide $52.3–54.3B, 2026 capex $60–64B). Utilization effectively full at the leading edge. Next: Oct monthly revenue ~11/10.
- **ASML:** no new data since 10/14 (Q4 guide €14.2–15.2B; order intake no longer disclosed). Capex-pipeline signal: positive, extends the cycle into 2028+.
- **Lam Research (10/21, single secondary source, unverified at the primary):** beat; shares fell on the print, which is the same pattern as TSMC (good print, muted stock reaction), a late-cycle sign.
- **SK Hynix:** Q3 not yet reported (latest actual: Q2 revenue ~KRW 79.3T). Previews put Q3 revenue at KRW 89.5–99.2T and operating profit at KRW 70–78T (analyst estimates only). Samsung full Q3: 10/29.
- **CPU-side names:** see Section 3; nothing new this period.

---

## 5. CYCLE POSITIONING CALL

- **Where we are: LATE upcycle, with a market-led warning.** Breadth is wide (GPU, HBM/DRAM, equipment, server CPU), but price momentum has cracked while the rate of change in memory prices decelerates.
- **Confidence: MEDIUM-HIGH** on the late-upcycle label; **MEDIUM** on timing. No hard series has rolled over (SIA, TSMC and ASML guides, billings), so this is not yet a turn, but the verified 8-session, -16% SOX drawdown moves the probability of a turn within 2–3 quarters up from last week's view.
- **Key risk that invalidates this view:** (1) hyperscaler capex cuts or a financing event (CoreWeave credit) seen in the late-Oct capex guides; (2) memory contract prices flatten or fall while CXMT and Big-3 capacity ramp; (3) a rates/inflation shock (hot CPI/PPI this month). The opposite risk: if the 10/19 rebound extends and hyperscalers raise capex, the drawdown was a positioning flush rather than a peak.

---

## 6. WHAT TO WATCH NEXT (4–8 weeks)

- **Hyperscaler Q3 earnings (MSFT/GOOGL/AMZN/META, late Oct; dates not confirmed):** 2027 capex guides, general-purpose vs. accelerator mix, agentic call-outs.
- **Intel Q3 (10/29, confirmed), Samsung full Q3 (10/29), SK Hynix Q3 (late Oct), AMD Q3 (~11/3, unconfirmed).**
- **SEMI Sep billings (monthly, date unconfirmed) and SEMI Q3 global billings (~early Dec); SIA Sep sales (~early Nov); TSMC Oct revenue (~11/10).**
- **SOX/SPX weekly:** need a verified series; does the ratio hold the 10/16 low?
- **TrendForce Nov contract prices:** the rate of increase in DRAM; any DDR5 spot rollover.
- **NVIDIA FQ3 (~late Nov); Micron FQ1 (Dec); Fed/CPI.**

---

## 7. PORTFOLIO IMPLICATION

*(Separate from the objective analysis.)* Stay invested in the core sleeve (SMH/SOXX/NVDA) because fundamentals have not rolled over, but keep covered calls closer to the money on NVDA/SOXX and do not add SOXL; consider trimming SOXL into any rebound, since realized volatility is at crisis-era levels. Raise cash only if hyperscaler capex guides disappoint or memory contract momentum stalls.

---

### Sources

- Chip selloff: [247wallst, 8 days in a row (10/17)](https://247wallst.com/investing/2026/10/17/chip-stocks-just-fell-8-days-in-a-row-their-longest-losing-streak-since-2008/), [Mitrade/Motley Fool (10/20)](https://www.mitrade.com/insights/news/live-news/article-8-2175265-20261020), [CryptoBriefing](https://cryptobriefing.com/us-chip-stocks-longest-losing-streak-2008/), [Stocktwits](https://stocktwits.com/news-articles/Markets/Equity/semiconductor-stocks-sox-losing-streak-2-trillion-ai-selloff/cZxKaOoRBsy)
- Memory: [TrendForce DRAM Market Bulletin 10/21](https://www.trendforce.com/research/download/RP261021BP), [StockHub (10/20)](https://www.stockhub.kr/en/news/news_b7244c205001), [NextMSC tracker](https://www.nextmsc.com/industry-deep-dive/dram-nand-price-tracker-quarterly)
- Lam Research: [24/7 Wall St (10/21)](https://247wallst.com/cards/lam-research-q1-2027-earnings-lrcx-01m5g284sg6y780zdr123b3q83), [preview](https://247wallst.com/investing/2026/10/20/texas-instruments-and-lam-research-report-earnings-ai-equipment-boom-meets-analog-rebound/)
- SK Hynix previews and Q2: [S&P Global (8/5)](https://www.spglobal.com/market-intelligence/en/news-insights/research/2026/08/sk-hynix-postq-profit-beat-offsets-revenue-miss)
- SEMI Q2 billings: [SEMI (9/3)](https://www.semi.org/en/semi-press-release/global-semiconductor-equipment-billings-increased-23-percent-year-over-year-in-q2-2026-semi-reports)
- Hyperscaler Q1 capex context (April): [Yahoo Finance](https://finance.yahoo.com/markets/article/magnificent-7-earnings-rush-reveals-ai-spending-surge-with-hyperscaler-capex-set-to-reach-725-billion-in-2026-224901707.html)
- Carried from 10/17 report: TSMC Q3 ([TSMC](https://pr.tsmc.com/english/news/3346)), ASML Q3 ([SEC 6-K](https://www.sec.gov/Archives/edgar/data/0000937966/000162828026065813/pressreleasefinancialresul.htm)), SIA Aug sales ([SIA](https://www.semiconductors.org/policies/tax/market-data/)), Micron FQ4, Intel/AMD Q2, Intel Q3 date ([Intel IR](https://www.intc.com/news-events/press-releases/detail/1782/intel-to-report-third-quarter-2026-financial-results)).

*Data flags:*
1. *Book-to-bill is discontinued; SEMI Q2 billings (9/3) is the latest proxy. No Sep monthly figure found.*
2. *SOX/SPX: the losing streak and -16% are from secondary reports (247wallst, Mitrade/Motley Fool, CryptoBriefing); no verified SOX or SPX closes after 10/16 and no computed ratio. Undated index snapshots found online conflict and were not used.*
3. *Lam results come from one secondary source (247wallst); the Dec-quarter guide of ~$8.6B is unverified against Lam's release.*
4. *DRAM Q4 contract guidance conflicts (+10–15% vs ~+20%); neither verified at TrendForce's primary report (paywalled). The TrendForce spot headlines are from the public bulletin highlights; the 10/21 spot price table is paywalled.*
5. *SK Hynix Q3 estimates are analyst previews, not results.*
6. *Hyperscaler capex numbers are from Q1 (April) coverage; no Q3 figures yet. Hyperscaler, AMD and SEMI release dates are unconfirmed.*
7. *TSMC, ASML, SIA, Micron and Intel/AMD figures are carried from the 10/17 report; all are within one quarter / ~6 weeks (SIA Aug 10/5, not stale).*
8. *No fresh CPU/agentic datapoint this period; Intel/AMD figures are carried from Q2.*
