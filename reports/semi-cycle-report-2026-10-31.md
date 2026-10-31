# Semiconductor Cycle Report — 2026-10-31

**Report date:** 2026-10-31 (Saturday). Last completed trading day: Friday 2026-10-30. Staleness checks are relative to 2026-10-31.
**Run type:** COMPARISON against `semi-cycle-report-2026-10-24.md` (call then: LATE upcycle with a market-led warning, not a turn; confidence MEDIUM-HIGH on fundamentals, MEDIUM on timing).

Repo: https://github.com/one-piece-of-ai/claude
This run's report: https://github.com/one-piece-of-ai/claude/blob/claude/main/reports/semi-cycle-report-2026-10-31.md

---

## 1. EXECUTIVE SUMMARY

**LATE upcycle, still not a turn. Supplier earnings were huge this week, but the hyperscaler capex signal turned mixed. Confidence MEDIUM-HIGH on fundamentals, MEDIUM on timing.** What changed vs. 10/24:
- **Memory suppliers confirmed peak-level earnings.** SK Hynix Q3 (10/28, preliminary): revenue KRW 104.6T, operating profit KRW 83.33T (80% margin), +37.6% QoQ. Samsung's 10/8 preannouncement: operating profit KRW 107.4T (+783% YoY). I could not find Samsung's full 10/29 release.
- **The CPU thesis got its first hard datapoint.** Intel Q3 (10/29, SEC 8-K): DCAI revenue $7.3B, +78% YoY (Q2: $6.3B). CEO: "extraordinary demand for our Xeon family", with supply the constraint. No agentic-specific quote in the release.
- **Hyperscaler capex turned mixed, which is the new caution.** Microsoft cut its current-year capex to $170B from $175B, citing third-party GPU delays and shifting some capacity into 1H27. Alphabet held $195–205B and said 2027 capex will "significantly" rise, but fell ~10–13% on a miss and negative free cash flow. Meta (10/22) fell ~3–7% on higher spending. Amazon's 10/29 print was not found.
- **Still unverified:** SOX/SPX after 10/16, SEMI Sep billings, and SIA Sep sales (due early Nov).

---

## 2. CYCLE DASHBOARD TABLE

| Indicator | Latest value (as-of date) | Direction | Cycle implication |
|---|---|---|---|
| Book-to-bill / equipment demand | NA book-to-bill discontinued (Feb 2022). Proxy: **SEMI Q2 2026 global billings $40.53B, +23% YoY, +11% QoQ** (SEMI, 9/3). Q3 data is expected early Dec. No Sep monthly figure found (searched 10/31). | Up (record; unchanged) | Capex still expanding. The figure is under 8 weeks old but quarterly, so it is not stale |
| Semiconductor sales (WSTS/SIA) | **Aug $159.7B, +8.0% MoM, +144.3% YoY** (SIA, 10/5, 3-mo avg), carried. Sep due ~early Nov. | Up | Strongest fundamental read. The YoY figure is inflated by memory prices and a low base, so weight MoM. About 4 weeks old, not stale |
| SOX/SPX relative strength | **No verified SOX or SPX closes after 10/16 (SOXX $493.39 on 10/16, -4.1% that day).** SOX fell ~16% over 8 sessions 10/7–10/16 (carried, secondary). NVDA closed $217.09 on 10/19. The ratio cannot be computed. | **Down through 10/16; unknown since** | Still the cycle's main warning. Single-name hyperscaler and neocloud selloffs 10/22–10/29 (Alphabet, Meta, CoreWeave, Nebius, Oracle) point to continued financing and ROI stress |
| Memory pricing signal | Carried from 10/24 (TrendForce 10/20–21): DDR5 spot tight, DDR4 $46.357 (+0.84% WoW), NAND wafer -1.28% WoW. **New: SK Hynix Q3 DRAM ASP ~+22%, NAND ~+15% QoQ (Meritz estimate, secondary).** No fresh TrendForce Nov contract data found. | Up (DRAM) / flat-down (NAND spot) | Q3 realized prices strong, rate of rise decelerating (Q2 ~+80%, Q3 ~+40% contract). Late-cycle shape: price up, second derivative negative |
| Foundry demand (TSMC) | **Q3 $46.72B, +41.2% YoY; Q4 guide $52.3–54.3B** (TSMC, 10/15), carried. Oct monthly revenue due ~11/10. | Up | Full leading-edge utilization. Not stale (under 3 weeks) |
| Capex outlook (ASML / equipment / hyperscalers) | **ASML Q4 guide €14.2–15.2B; FY26 €44–45B** (10/14), carried. **Hyperscalers: MSFT 2026 capex $170B (from $175B); GOOGL $195–205B, 2027 "significantly" higher; META $135–145B** (CNBC 10/29, 24/7 Wall St 10/22). | Up (equipment) / mixed (hyperscaler) | Upstream pipeline is intact into 2028. Microsoft's trim is a delivery-timing issue, not demand loss, but it is the first hyperscaler downward revision |

---

## 3. KEY SIGNALS INTERPRETATION

- **Demand momentum: accelerating in supplier results, with equities and hyperscaler spending signaling digestion risk.** Memory and CPU suppliers posted records. Buyers are being punished for spending (Alphabet, Meta), and Microsoft cited deliveries, not demand, for trimming capex.
- **Supply tightness vs. oversupply: tight.** Intel says Xeon supply is the constraint. Microsoft says GPU deliveries are delayed. ASML supply is short through 2028. DDR5 is allocation-constrained.
- **Memory cycle direction: peak-level profits, decelerating price growth (late stage).** SK Hynix's 80% operating margin is the kind of figure that historically marks a cycle's high-profit phase, not its start. Microsoft expects capex to accelerate in 1H27 "because of higher component costs", which is the late-cycle feedback loop I flagged last week: component inflation raises buyers' costs. *Agentic link:* long-context, high-concurrency agent loops with large KV-caches raise DRAM/HBM per unit of compute. There is no new quantified datapoint, so it remains a structural argument.
- **AI-driven demand vs. cyclical weakness:** AI still dominates. The risk is financing and free cash flow (Alphabet FCF negative, more than $9B outflow; Meta negative FCF; neocloud stress), not current orders.
- **Agentic AI → CPU reliance (standing thesis): first measurable support this period.**
  - **Intel Q3 (SEC 8-K, 10/29):** DCAI revenue $7.3B, +78% YoY (from $4.1B), segment operating income $3.0B. Implied +16% QoQ against Q2's $6.3B (my arithmetic from the prior report). Intel's CEO said CPU demand "remains robust" and the priority is unlocking Xeon supply. Intel is supply-constrained while the PC business is weak, so the strength is in the data center. A secondary source (MarketBeat) gave a conflicting DCAI figure of $4.1B, which appears to be the year-ago base. The primary 8-K takes precedence.
  - **Not confirmed:** the release has no agentic quote and no CPU:GPU ratio update (Q1 call: 1:8 to ~1:4, carried). The surge is consistent with the thesis but not proven to be agentic-driven; enterprise refresh and server share also contribute.
  - **Still pending:** AMD Q3 on 11/3 after the close (confirmed, AMD IR), Amazon Graviton/Trainium (Amazon's 10/29 results not found; April coverage cited a >$20B run rate, with conflicting sources), Arm, and Microsoft Cobalt / Google Axion (no datapoint found).
  - **Breadth read:** positive. Server CPU demand is accelerating alongside GPUs and memory, which broadens the cycle beyond the GPU-only story. Treat it as confirmed only after AMD EPYC and cloud-silicon numbers show units and ASPs re-accelerating.

---

## 4. COMPANY READOUTS

- **Micron:** no new earnings since FQ4 (9/30): revenue $54.23B, GM 87%, FQ1 guide ~$61.5B, DIO 129 days (carried). SK Hynix and Samsung results are strong read-throughs for FQ1 (December).
- **SK Hynix (10/28, preliminary, review not complete):** revenue KRW 104.6T (+31.9% QoQ) vs consensus ~98.3T; operating profit KRW 83.33T vs ~77T expected; margin 80%; net profit ~KRW 39.8T, a miss. About KRW 100T of 2026 shareholder returns, including a KRW 20T buyback. Returning cash instead of raising capex is a mild late-cycle discipline signal.
- **Samsung:** only the 10/8 preannouncement was found (operating profit KRW 107.4T, revenue ~KRW 195T; HBM4 and price gains cited). Memory-segment profit of ~KRW 110T is an analyst estimate. Full 10/29 detail unverified.
- **TSMC:** no new data since 10/15 (Q3 $46.72B, GM 66.4%, Q4 guide $52.3–54.3B, 2026 capex $60–64B). Next: Oct revenue ~11/10.
- **ASML:** no new data since 10/14. Capex-pipeline signal: positive into 2028+. The hyperscaler 2027 capex guides (Alphabet "significantly" higher; estimates above $1T industry-wide, per CNBC) support that, but Microsoft's trim shows delivery bottlenecks.
- **Intel:** see Section 3. Foundry revenue $6.7B (+58% YoY), operating loss narrowed to $1.9B. Q4 guide $15.0–16.0B, below Q3's $16.5B. PC slowdown expected through at least 1H27 (CFO).
- **CPU-side names:** AMD 11/3. Arm, NVIDIA Grace and cloud custom CPUs: no fresh datapoint.

---

## 5. CYCLE POSITIONING CALL

- **Where we are: LATE upcycle.** Fundamentals are at records (SK Hynix, Samsung, TSMC, Intel DCAI) and breadth is wide (GPU, memory, equipment, server CPU). Leading indicators are lagging: equities cracked, memory price growth is decelerating, and hyperscalers are now being punished for capex.
- **Confidence: MEDIUM-HIGH** on the late-upcycle label, **MEDIUM** on timing. No hard series has rolled over, but the first hyperscaler capex trim, even if delivery-related, is a new yellow flag.
- **Key risk that invalidates this view:** (1) a hyperscaler or neocloud financing event leading to broader capex cuts into 2027 (Alphabet and Meta negative FCF, CoreWeave credit); (2) memory contract prices flattening while CXMT and the Big-3 add capacity; (3) a rates or inflation shock. The opposite risk: Alphabet's "significant" 2027 rise and rising component costs mean spending, and thus supplier revenue, could keep climbing through 2027, extending the cycle.

---

## 6. WHAT TO WATCH NEXT (4–8 weeks)

- **AMD Q3, 11/3 after the close (confirmed):** EPYC and Instinct split, any agentic call-out, and server-CPU TAM commentary. Guide was ~$13B ±$0.3B.
- **SIA Sep sales (~early Nov, date unconfirmed); TSMC Oct revenue (~11/10); SEMI Sep billings (monthly, date unconfirmed) and Q3 billings (~early Dec).**
- **Amazon Q3 (reported 10/29, results not found):** capex versus the ~$220B plan, Graviton/Trainium run rate. Verify first.
- **Samsung full Q3 detail (10/29); TrendForce Nov contract prices:** is the DRAM rate of increase still positive?
- **SOX/SPX weekly:** need a verified series; does the 10/16 low hold?
- **NVIDIA FQ3 (~late Nov); Micron FQ1 (Dec); Fed/CPI.**

---

## 7. PORTFOLIO IMPLICATION

*(Separate from the objective analysis.)* Stay invested in the core sleeve (SMH/SOXX/NVDA), since supplier fundamentals are at records, but keep covered calls closer to the money on NVDA/SOXX, do not add SOXL, and consider trimming SOXL into strength. The first hyperscaler capex trim and negative-FCF reactions raise the bar for getting more bullish. Raise cash only if 2027 capex guides or memory contract momentum disappoint.

---

### Sources

- Intel Q3 2026 results: [Intel 8-K exhibit (SEC, 10/29)](https://www.sec.gov/Archives/edgar/data/0000050863/000005086326000188/q326earningsrelease.htm); conflicting secondary DCAI figure: [MarketBeat](https://www.marketbeat.com/originals/intels-breakout-quarter-more-than-a-beat-its-a-declaration/)
- SK Hynix Q3: [Korea Times (10/28)](https://www.koreatimes.co.kr/business/companies/20261028/sk-hynix-logs-record-q3-operating-profit-of-628-bil), [investingLive](https://investinglive.com/stocks/sk-hynix-q3-operating-profit-beats-at-83tn-won-unveils-100tn-won-shareholder-payout-plan/), [Cloudspress](https://www.cloudspress.com/sk-hynix-q3-2026-revenue-hits-104-6t-won-as-operating-profit-jumps-632/)
- Samsung preannouncement: [TrendForce (10/8)](https://trendforce.com/news/2026/10/08/news-samsung-sees-3q26-operating-profit-soaring-783-to-record-krw-107-4-trillion-on-hbm4-memory-price-gains)
- Hyperscaler capex: [CNBC (10/29)](https://www.cnbc.com/2026/10/29/microsoft-google-ai-capex-estimates.html), [24/7 Wall St (10/22)](https://247wallst.com/investing/2026/10/22/meta-falls-3-as-higher-ai-spending-outlook-overshadows-earnings-beat-alphabet-dips-microsoft-holds-steady/), [Advisor Perspectives (10/28)](https://www.advisorperspectives.com/articles/2026/10/28/microsoft-alphabet-earnings-focus-ai-cash-flow-drain)
- AMD date: [AMD IR](https://ir.amd.com/news-events/press-releases/detail/1300/amd-to-report-fiscal-third-quarter-2026-financial-results)
- Amazon preview and Q2 baseline: [Pepperstone](https://pepperstone.com/en/insights/market-analysis/equities/amazon-q3-2026-earnings-preview)
- SEMI Q2 billings: [SEMI (9/3)](https://www.semi.org/en/semi-press-release/global-semiconductor-equipment-billings-increased-23-percent-year-over-year-in-q2-2026-semi-reports)
- Carried from 10/24 report: SIA Aug sales ([SIA](https://www.semiconductors.org/policies/tax/market-data/)), TSMC Q3 ([TSMC](https://pr.tsmc.com/english/news/3346)), ASML Q3 ([SEC 6-K](https://www.sec.gov/Archives/edgar/data/0000937966/000162828026065813/pressreleasefinancialresul.htm)), chip selloff ([247wallst](https://247wallst.com/investing/2026/10/17/chip-stocks-just-fell-8-days-in-a-row-their-longest-losing-streak-since-2008/)), TrendForce DRAM bulletin ([10/21](https://www.trendforce.com/research/download/RP261021BP)).

*Data flags:*
1. *Book-to-bill is discontinued; SEMI Q2 billings (9/3) is the latest proxy. No Sep monthly figure found.*
2. *SOX/SPX: no verified closes after 10/16 and no computed ratio. The -16% / 8-session figure is from secondary reports (carried).*
3. *SK Hynix figures are preliminary (review not complete); the DRAM/NAND ASP changes are a Meritz estimate relayed by a secondary source.*
4. *Samsung: only the 10/8 preannouncement was found; the 10/29 full results and the memory/HBM split are unverified; the segment profit is an analyst estimate.*
5. *Amazon's 10/29 Q3 results were not found; Graviton/Trainium run-rate figures conflict across sources ($20B vs $25B each).*
6. *Alphabet/Microsoft/Meta stock moves come from a few secondary reports and conflict in places (Microsoft: up vs flat; Meta: -3% vs -7%). Capex figures are from CNBC; one preview listed Microsoft at $220B, which conflicts and was not used.*
7. *No fresh TrendForce Nov DRAM contract figures found; memory price rows are carried from 10/24.*
8. *TSMC, ASML, SIA, Micron and AMD Q2 figures are carried and within one quarter / ~6 weeks (SIA Aug 10/5, not stale).*
9. *Intel's DCAI "+16% QoQ" is derived from the prior report's Q2 figure ($6.3B), not stated in the release.*
