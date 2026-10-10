# Semiconductor Cycle Report — 2026-10-10

**Report date:** 2026-10-10 (Saturday). Last completed trading day: **Friday 2026-10-09**. Staleness checks are relative to 2026-10-10.
**Run type:** **COMPARISON** against `semi-cycle-report-2026-10-03.md` (call then: **LATE upcycle, turn thesis rejected, confidence MEDIUM-HIGH**; named SIA Aug sales, TSMC Sep revenue and ASML Q3 as pending, and a SOX/SPX break or memory-pricing rollover as invalidation).

Repo: https://github.com/one-piece-of-ai/claude
This run's report: https://github.com/one-piece-of-ai/claude/blob/claude/main/reports/semi-cycle-report-2026-10-10.md

---

## 1. EXECUTIVE SUMMARY

**Fundamentals confirmed again; the high-frequency read turned shaky. LATE upcycle, turn thesis still rejected; confidence MEDIUM-HIGH on fundamentals, MEDIUM on the weekly price signal.** What changed vs. 10/3:
- **SIA Aug sales (10/5): $159.7B, +8.0% MoM, +144.3% YoY**, 18th straight month of growth; YTD sales passed **$1T**. July was revised up to $147.9B.
- **TSMC Sep revenue (10/8): NT$511.9B (~US$16.07B), +54.6% YoY, -0.6% MoM.** Q3 revenue was a record NT$1.494T (+17.6% QoQ), above the top of guidance. The first MoM dip in five months is a flat, not a rollover.
- **Samsung Q3 prelim (10/8): operating profit ~KRW 107.4T**, the first quarter above KRW 100T, slightly above consensus. Memory shortage intact.
- **Warning:** on 10/8 chips led a selloff (a Bloomberg chip gauge **-3.4%**) after an FT report that OpenAI's annualized revenue is ~$20B below prior estimates, with oil >$104. This is an AI-financing/demand-durability scare, not a cycle datapoint, but it is the first real stress test of the leading indicator. SPX recovered +0.6% on 10/9, so the SOX/SPX streak (5 weeks as of 10/3) is probably broken. See flags.
- **Still pending:** ASML Q3 (date not confirmed; order intake no longer reported), SEMI Sep billings (~10/21).

---

## 2. CYCLE DASHBOARD TABLE

| Indicator | Latest value (as-of date) | Direction | Cycle implication |
|---|---|---|---|
| Book-to-bill / equipment demand | NA book-to-bill discontinued; SEMI NA billings press release stopped Feb 2022. Proxy: **SEMI Q2 2026 global billings $40.53B, +23% YoY, +11% QoQ** (SEMI, 9/3). SEMI monthly billings page schedule lists **~10/21** for next release. | Up (record; no new data) | Fabs still committing capex ahead of demand. Micron's FY27 capex >$50B and Samsung's profit surge reinforce it |
| Semiconductor sales (WSTS/SIA) | **Aug $159.7B, +8.0% MoM, +144.3% YoY** (SIA, 10/5; 3-month moving avg). Jul revised to $147.9B (from $146.8B); Jun $137.9B. 3-mo trend: +6.4% then +8.0% MoM, accelerating. | **Up (accelerating)** | Strongest fundamental read in the series. YoY is inflated by memory pricing and a low base, so use MoM |
| SOX/SPX relative strength (high-freq) | SPX **7,765.36 (10/8)**, ~7,811.5 (10/9, +0.59%) vs ~7,666 (10/2): **~+1.9% on the week**. SOX level for 10/9 **not verified**; chip gauge -3.4% on 10/8. 10/2 ratio was ~1.71. | **Likely down this week (unconfirmed)** | First crack in the leading indicator since the 5-week run. SPX up while chips lagged = ratio fell. Needs a verified SOX close to size it |
| Memory pricing signal (DRAM/NAND) | TrendForce: Q3 conventional DRAM contract **+13–18% QoQ**, NAND **+10–15%**; 4Q26 DRAM contract guided **+10–15%** (per 10/3 report). Latest TrendForce bulletin found is **Aug 2026** (>6 weeks: **STALE** for spot). Aug 12 bulletin: contract momentum slowing, future capacity expected to pressure prices. Samsung record profit (10/8) confirms pricing power in Q3. | Up (contract, decelerating rate) / spot unverified | Shortage intact; rate of change fading off a very high base, as expected late-cycle |
| Foundry demand (TSMC revenue) | **Sep NT$511.86B (~US$16.07B), +54.6% YoY, -0.6% MoM** (TSMC, 10/8). Q3 NT$1.494T, +17.6% QoQ, +50.9% YoY, above guidance (US$44.6–45.8B). YTD +41.1%. | Up YoY / flat MoM | Still very strong; MoM pause after Aug record is normal quarter-end lumpiness. Q3 earnings (~mid-Oct) give Q4 guide and capex |
| Capex outlook (ASML / bookings) | ASML Q2 (7/15): sales €9.3B, FY26 €43–45B, **Q3 guide €11.0–12.0B, GM 55–57%**. ASML **stopped reporting quarterly order intake from Q1 2026**; last figure Q4 2025 (€13.2B). Q3 date not confirmed. | Up / pending | Pipeline intact. The forward read now comes from guidance/backlog commentary, not bookings, so weaker visibility than before |

---

## 3. KEY SIGNALS INTERPRETATION

- **Demand momentum: accelerating (fundamentals).** SIA MoM rose from +6.4% to +8.0%; TSMC Q3 beat its guide; Samsung posted a record quarter.
- **Supply tightness vs. oversupply: tight.** Samsung's chip unit earned roughly KRW 110T (analyst estimate; no official segment split until 10/29) while its mobile unit reportedly faces a loss from memory costs, which shows who pays for the shortage. No oversupply signal.
- **Memory cycle direction: strong, late-stage; not peaking.** Contract-price growth is decelerating (Q3 +13–18% to Q4 +10–15%) while the industry's capex ramps (Micron >$50B FY27). Capex is how shortages end, but with a 12–24-month lag. *Agentic link (memory intensity):* agents carry large KV-caches, long contexts and high concurrency, which supports DRAM/HBM demand. This remains inference; I found no new quantified memory-per-agent datapoint this run.
- **AI-driven demand vs. cyclical weakness:** AI dominates. The new risk is *financing durability*: the FT report on OpenAI revenue (via Yahoo/Bloomberg market wraps; I did not read the FT piece) hit Nvidia, Micron and Intel on 10/8. If AI-lab revenue disappoints, hyperscaler capex is the transmission channel; none of this week's hard data shows that yet.
- **Agentic AI → CPU reliance (standing thesis): supported, with no new earnings datapoints this week.**
  - *Fresh (analyst/secondary):* Futurum (10/1) argues most agent-loop steps (tool calls, code execution, API requests) run on CPUs and sizes the CPU opportunity at $246B. TrendForce projects CPU:GPU ratios moving from ~1:4–1:8 toward ~1:1–1:2. Bank of America reportedly raised its 2030 server-CPU forecast to >$170B. These are projections, not measured outcomes.
  - *Hard data (carried from Q2 earnings):* AMD data center $6.7B (+107% YoY); Intel DCAI $6.3B (+59% YoY). Intel's CFO said on the Q1 call that deployment ratios had moved from 1:8 to 1:4.
  - *Supply/price claims* (Intel/AMD price hikes, EPYC sold out, long Xeon lead times) come from distributor/vendor blogs and are unverified.
  - *Verdict:* materializing in vendor revenue, but attribution to agentic AI vs. refresh and pricing is partly management framing. The test is Intel/AMD Q3 (late Oct): unit/ASP re-acceleration and explicit agentic call-outs. Hyperscaler custom CPUs (Graviton/Axion/Cobalt) disclose no units; no fresh data.

---

## 4. COMPANY READOUTS

- **Micron:** no new earnings since FQ4 (9/30): revenue $54.23B, GM 87%, FQ1 guide ~$61.5B, DIO 129 days, FY27 capex >$50B. Memory-cycle read-through: Samsung's record Q3 (10/8) corroborates it; Micron fell with chips on 10/8 (a sentiment move, not a fundamental one). Next: FQ1 in Dec.
- **TSMC:** Sep revenue NT$511.9B (-0.6% MoM, +54.6% YoY); Q3 record NT$1.494T, above guidance. Full-year capex guide from last report: $60–64B (not refreshed this run). Utilization implicitly full at leading edge. Q3 earnings call ~mid-Oct for Q4 guide, 2nm ramp and capex.
- **ASML:** Q3 guide €11–12B sales (7/15). Order intake no longer disclosed, so SEMI billings and customer capex (Micron, TSMC) are better 12–36-month proxies. Q3 date unconfirmed (typically mid-Oct).
- **Samsung:** prelim Q3 operating profit ~KRW 107.4T on ~KRW 195T revenue (10/8); revenue 2.8% below consensus, profit 0.7% above; full results 10/29. SK Hynix Q3 not yet reported.
- **CPU-side names:** Intel (DCAI $6.3B, +59%, Q2), AMD (data center $6.7B, +107%, Q2; EPYC + Instinct), Arm (AGI CPU launched 3/24; royalties via Vera/Graviton/Axion/Cobalt), NVIDIA Vera (shipping, standalone CPU sales since March). No new reports this week. Inference-vs-training mix: no fresh datapoint.

---

## 5. CYCLE POSITIONING CALL

- **Where we are: LATE upcycle, breadth widening** (GPU + HBM/DRAM + server CPU). Agentic CPU demand remains a *positive breadth indicator*, now supported by revenue (AMD/Intel) but awaiting Q3 confirmation.
- **Confidence: MEDIUM-HIGH** (unchanged). Up: SIA acceleration, TSMC beat, Samsung record. Down: the 10/8 chip selloff and probable SOX/SPX break, TSMC's flat MoM, decelerating memory contract gains, ASML's reduced disclosure, 30Y yields near 2002 highs, oil >$104.
- **Key risk that invalidates this view:** (1) AI-demand financing shock (OpenAI-type revenue misses) leading to hyperscaler capex cuts, visible first in TSMC's Q4 guide and Q3 capex commentary; (2) SOX/SPX failing to recover while SPX holds, i.e. a sustained lead-lag reversal; (3) memory contract prices rolling over while industry capex accelerates; (4) a rate/oil shock.

---

## 6. WHAT TO WATCH NEXT (4–8 weeks)

- **SOX/SPX weekly:** does the ratio reclaim ~1.7 by 10/16, or does the 10/8 drop extend? (Needs verified SOX closes.)
- **TSMC Q3 earnings (~mid-Oct):** Q4 guide, capex, AI revenue mix.
- **ASML Q3 (date unconfirmed, ~mid-Oct):** sales vs €11–12B guide, 2027 commentary, backlog.
- **SEMI Sep billings (~10/21)** and SEMI Q3 global billings (~early Dec).
- **Samsung full Q3 (10/29); SK Hynix Q3 (late Oct):** HBM/DRAM mix and capex.
- **Intel, AMD, Arm Q3 (late Oct) and hyperscaler capex (MSFT/GOOGL/AMZN/META, late Oct):** server-CPU units/ASPs, "agentic workload" call-outs, capex mix toward general-purpose compute. Also AI-lab financing headlines.
- **SIA Sep sales (~early Nov); NVIDIA FQ3 (~late Nov).**
- **Macro:** Fed meeting/CPI, 30Y vs ~5.5–5.6%, oil.

---

## 7. PORTFOLIO IMPLICATION

*(Separate from the objective analysis.)* Stay the course on the core sleeve (SMH/SOXX/NVDA) but tilt the call book mildly more defensive for now: move some NVDA/SOXX strikes closer to the money and hold off adding SOXL until the SOX/SPX ratio is verified back up and TSMC/hyperscaler prints confirm capex. No raise-cash move is warranted on fundamentals, which are still accelerating.

---

### Sources

- SIA Aug 2026 sales (10/5): [AnySilicon](https://anysilicon.com/news/year-to-date-global-semiconductor-sales-top-1-trillion-through-august/), [Evertiq](https://evertiq.com/design/2026-10-07-global-chip-sales-top-1-trillion-in-first-eight-months-of-2026), [SIA market data](https://www.semiconductors.org/policies/tax/market-data/)
- TSMC Sep revenue (10/8): [TSMC press release](https://pr.tsmc.com/english/news/3343), [SEC 6-K](https://www.sec.gov/Archives/edgar/data/0001046179/000104617926000680/tsm-revenue20261008.htm), [Devdiscourse](https://www.devdiscourse.com/article/business/3988867-tsmc-september-revenue-surges-546-yoy-to-usd-1607-billion-slips-marginally-month-on-month)
- Samsung Q3 prelim (10/8): [StockHub](https://stockhub.kr/en/insights/view_1791420339349_rirmz2bfh-samsung-electronics-005930-cy26-q3-preliminary-earnings-20261008), [SamMobile](https://www.sammobile.com/?p=16681640)
- Markets 10/8–10/9: [Yahoo Finance 10/8](https://finance.yahoo.com/markets/live/stock-market-today-thursday-october-8-dow-sp-500-nasdaq-080537884.html), [Yahoo Finance chip selloff](https://finance.yahoo.com/markets/live/stock-market-today-sp-500-nasdaq-futures-slip-after-samsung-results-spark-chip-sell-off-223015294.html), [YourNews](https://yournews.com/2026/10/08/7220319/wall-street-retreats-from-record-highs-as-tech-stocks-slide/), [Trading Economics SPX](https://tradingeconomics.com/united-states/stock-market)
- SEMI billings schedule: [SEMI billings report](https://semi.org/en/products-services/market-data/equipment/billings-report); SEMI Q2 billings (9/3): [SEMI](https://www.semi.org/en/semi-press-release/global-semiconductor-equipment-billings-increased-23-percent-year-over-year-in-q2-2026-semi-reports)
- ASML: [Q2 2026 results](https://www.asml.com/news/press-releases/2026/q2-2026-financial-results)
- Memory pricing: [TrendForce Aug contract report](https://www.trendforce.com/research/download/RP260831UX), [TrendForce Aug 12 bulletin](https://www.trendforce.com/research/download/RP260812LF), [IgorsLab on Q3](https://www.igorslab.de/en/dram-and-nand-remain-more-expensive-trendforce-sees-slowing-but-still-rising-memory-prices-q3-2026/)
- Agentic CPU: [TrendForce insight](https://insights.trendforce.com/p/agentic-ai-cpu-gpu), [TrendForce report](https://www.trendforce.com/research/download/RP260408AD), [Futurum (10/2026)](https://futurumgroup.com/wp-content/uploads/2026/10/The-246-Billion-CPU-Opportunitys-Winning-Chip-Has-Not-Been-Designed-Yet_AIOBB202609.docx.pdf), [Fusion Worldwide](https://info.fusionww.com/blog/server-cpu-shortage-2026), [AMD Q2](https://newsroom.amd.com/news/amd-2q-2026-earnings/)
- Carried from 10/3 report: Micron FQ4 (9/30), Intel/AMD Q2.

*Data flags:*
1. *Book-to-bill is discontinued; the SEMI quarterly billings proxy (9/3) is current. Next SEMI monthly update ~10/21.*
2. *SOX/SPX: no verified SOX close for 10/8–10/9 was found. An undated Investing.com snapshot (~11,819, -4.25%) could not be dated and is not used. The "likely down" call rests on the -3.4% chip gauge move (10/8) against SPX +1.9% on the week. Treat as unconfirmed.*
3. *SPX 7,765.36 (10/8) and ~7,811.5 (10/9) come from market-wrap summaries; 10/2 base (~7,666) is from the 10/3 report.*
4. *TrendForce spot/contract pages: nothing newer than Aug 2026 was found, so spot-price direction is STALE/unverified. Q4 contract guide is carried from the 10/3 report.*
5. *Whether TSMC's September was a "record" differs by outlet; the company table shows Aug (NT$514.8B) as the monthly high.*
6. *OpenAI/FT revenue claim is as relayed by market wraps; not verified at the source.*
7. *Samsung figures are preliminary; segment split unavailable until 10/29.*
8. *ASML no longer reports order intake (from Q1 2026) and the Q3 date was not confirmed.*
9. *CPU supply/price/lead-time claims and market-size forecasts are analyst/vendor sources, unverified; AMD/Intel Q2 figures carried from the prior report.*
