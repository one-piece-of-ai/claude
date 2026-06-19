# Semiconductor Cycle Report — 2026-06-19

**Report date:** 2026-06-19 (established from system clock; all staleness checks relative to this date)
**Run type:** **BASELINE** — `./reports/` was empty; no prior `semi-cycle-report-*.md` exists to compare against. Future runs should diff against this file.

---

## 1. EXECUTIVE SUMMARY

We are in a **mid-to-late upcycle**, and the two engines of the cycle have de-synced. The **capex/AI-demand engine looks mid-cycle and durable** — ASML raised its 2026 outlook with "very strong" order intake, TSMC revenue is +30% YoY, NVIDIA data-center +92% YoY, and hyperscaler capex is tracking ~+40% to >$600B. But the **memory-pricing engine is in its late, parabolic phase**: WSTS sales +93.9% YoY is almost entirely price-led (DRAM contract ~+90–95% QoQ in Q1, guided +58–63% in Q2), and the first crack — spot prices softening slightly at high levels — has appeared. Sentiment is extended (SOX +139.6% over the trailing 12 months, leading the S&P 500 by a wide margin). Net read: **demand is real, but memory pricing momentum is closer to a peak than a trough.** This is a baseline, so there is no prior reading to compare; the next report should watch for the spot→contract rollover.

---

## 2. CYCLE DASHBOARD TABLE

| Indicator | Latest value (as-of date) | Direction | Cycle implication |
|---|---|---|---|
| Book-to-bill / equipment demand | Monthly NA book-to-bill **discontinued by SEMI (Feb 2022)** — proxy: global equipment **billings +14% YoY, Q1 2026** | Up (decelerating vs. +24% Q2'25) | Expansion intact, but growth rate cooling — mid-cycle |
| Semiconductor sales (WSTS/SIA) | **$110.5B, +93.9% YoY, April 2026** (3-mo avg); +11% MoM | Up sharply | Price-led, not unit-led → late memory-pricing surge |
| SOX/SPX relative strength (high-freq) | **SOX 13,477, +139.6% TTM** (as-of 2026-06-19), vastly outpacing S&P 500 | Up (leading), off intraday high | Semis leading hard — bullish but extended/euphoric |
| Memory pricing (DRAM/NAND) | DRAM contract **+58–63% QoQ guided Q2'26**, NAND **+70–75% QoQ**; **spot softening slightly mid-April** | Up (contract), flattening (spot) | Peak-momentum memory upcycle; first caution flag |
| Foundry demand (TSMC revenue) | **NT$416.98B / $13.25B, +30.1% YoY, May 2026**; +1.5% MoM; YTD +30% | Up | Healthy mid-upcycle AI/HPC pull |
| Capex outlook (ASML / bookings) | 2026 guide **raised to €36–40B**; Q1 sales €8.8B (+~13% YoY); order intake "very strong" | Up | Forward capex pipeline expanding — bullish 12–36mo |

---

## 3. KEY SIGNALS INTERPRETATION

- **Demand momentum: peaking-but-not-rolling.** Logic/foundry/AI demand (TSMC +30%, NVDA DC +92%, ASML guide raise) is still accelerating on a 12–36mo forward basis. Equipment billings growth is decelerating (+24% → +11% → +14% over recent quarters), which says the *rate* of expansion has plateaued even as the *level* stays high. Classic mid-to-late.
- **Supply tightness vs. oversupply: acute tightness.** Memory is the binding constraint. Micron is "sold out of HBM for the next several quarters," and the 3:1 HBM-to-DDR5 wafer conversion is structurally draining general-purpose DRAM supply. No oversupply signal anywhere — the opposite.
- **Memory cycle direction: late upcycle / peak-pricing.** Contract prices are still ripping (Q2 DRAM +58–63%, NAND +70–75%), but the leading tell — **spot prices — softened slightly in mid-April** as buyers balked at higher levels. In memory cycles, spot leads contract. This is the single most important thing to watch; it is the first plausible early-warning of a pricing peak, though one soft print is not a trend.
- **AI-driven demand vs. cyclical weakness: genuinely AI-driven.** This is not a broad inventory-restock illusion. The pull is concentrated in AI infrastructure (HBM, CoWoS, leading-edge logic, hyperscaler capex +40%). The risk is therefore not "no demand" but "demand digestion / capex air-pocket" if hyperscalers pause.

---

## 4. COMPANY READOUTS

- **Micron (MU) — memory-cycle read: peak-strength, watch the rollover.** Most recent reported quarter is **FQ2 2026** (DRAM $18.8B, +207% YoY; NAND $5.0B, +169% YoY; record GM 74.9%, up from 56% sequentially). FQ3 guidance is extraordinary: **~$33.5B revenue, ~81% gross margin, ~$19.15 EPS**, driven by HBM mix, higher price and lower cost. CapEx >$25B FY26 with a step-up in FY27. **Read-through:** memory is at the most profitable point of the cycle. That is bullish *now* but is also exactly what late-cycle peaks look like. **MU reports FQ3 on June 24** — the key event of the next two weeks; watch days-of-inventory (DSI), HBM sold-out commentary, and any spot-pricing caution.
- **TSMC — AI/HPC + utilization: strong, mid-cycle.** May revenue +30.1% YoY, +1.5% MoM, YTD +30%, on tight leading-edge capacity and AI/HPC orders. No utilization stress; demand-led, not price-led. Confirms the *logic* side of the cycle is healthy and not yet frothy the way memory is.
- **ASML — capex pipeline (12–36mo forward): expanding.** Q1 2026 sales €8.8B, net income €2.8B, GM 53% (high end). **2026 guide raised to €36–40B** (from €34–39B) on AI-driven demand. ASML did not disclose a Q1 net-bookings figure in the release (qualitative "very strong" only — **flagged: exact order-intake number unavailable**). As the longest-lead indicator, a guide-raise plus strong commentary says the capex cycle still has 12–36 months of runway — the most reassuring datapoint for "this is mid-cycle, not the end."

---

## 5. CYCLE POSITIONING CALL

- **Where we are: MID-to-LATE upcycle.** Forward/capex indicators (ASML guide-raise, TSMC, hyperscaler capex) read mid-cycle and durable; the memory-pricing sub-cycle reads late (parabolic YoY, record margins, first spot softening).
- **Confidence: MEDIUM.** The bull case (AI capex, ASML bookings, HBM sold out) and the caution case (extended SOX, price-led sales, spot softening) are both well-supported; they point to "late-ish but not yet turning."
- **Key risk that could invalidate this view:** a **memory-price rollover** — if spot weakness bleeds into contract guidance (watch MU on June 24 and Q3 TrendForce contract data), the late-cycle call flips toward "turning." The mirror-image upside risk: a hyperscaler capex *acceleration* would push this back to a cleaner mid-cycle read. Secondary risks: export-control shifts (ASML/NVDA flagged China exclusions) and AI-capex digestion.

---

## 6. WHAT TO WATCH NEXT (4–8 weeks)

- **Micron FQ3 2026 earnings — June 24, 2026** *(highest priority)*: DSI, HBM order book, spot-vs-contract commentary, FQ4 guide. This tests whether the HBM/memory super-cycle is still cresting or peaking.
- **TSMC June + Q2 revenue — ~July 10, 2026** (monthly); **TSMC Q2 2026 earnings ~mid-July**: utilization, capex, AI/HPC commentary.
- **ASML Q2 2026 earnings — ~July 16, 2026**: the actual bookings number (missing this period) and whether the €36–40B guide holds — the cleanest forward-cycle read.
- **WSTS/SIA May 2026 sales — early July**: confirm whether the +94% YoY is still price-driven and whether MoM momentum holds.
- **DRAM/NAND spot prices — weekly**: the highest-frequency early-warning. A continued spot softening is the first domino of a pricing peak.
- **Hyperscaler Q2 capex updates (late July/Aug)**: any cut to the ~$600B/+40% trajectory would hit the demand thesis directly.

---

## 7. PORTFOLIO IMPLICATION

*(Kept separate from the objective analysis above.)* For a tech-heavy book with ~20% semi exposure (SMH/SOXX/NVDA direct + QQQM/VGT look-through) running covered calls: lean **modestly more defensive into strength** — with SOX +140% TTM and memory pricing parabolic, write **closer-to-the-money calls** to harvest elevated premium and accept assignment that raises cash, and **trim leveraged exposure (e.g. SOXL)**. Don't de-risk wholesale: ASML/TSMC forward indicators are still expansionary, so this is a tactical trim on a strong structural backdrop, not an exit — keep MU/June-24 and the spot-price trend as your triggers to get more defensive.

---

### Sources
- SEMI — equipment billings (Q1 2026 +14% YoY; monthly book-to-bill discontinued 2022): [semi.org press release](https://www.semi.org/en/semi-press-release/semi-reports-global-semiconductor-equipment-billings-increased-14-percent-year-over-year-in-q1-2026), [SEMI billings report](https://www.semi.org/en/products-services/market-data/equipment/billings-report)
- WSTS/SIA — April 2026 sales +93.9% YoY: [SIA](https://www.semiconductors.org/global-semiconductor-sales-increase-11-month-to-month-in-april/), [Electronics Weekly](https://www.electronicsweekly.com/news/business/q1-semiconductor-sales-2026-06/), [WSTS](https://www.wsts.org/76/Recent-News-Release)
- SOX index level / TTM performance (2026-06-19): [Investing.com](https://www.investing.com/indices/phlx-semiconductor), [Nasdaq SOX](https://indexes.nasdaqomx.com/Index/Overview/SOX)
- DRAM/NAND/HBM pricing (Q1–Q2 2026 contract, mid-April spot): [TrendForce 2Q26](https://www.trendforce.com/presscenter/news/20260331-12995.html), [TrendForce 1Q26](https://www.trendforce.com/presscenter/news/20260105-12860.html), [Tom's Hardware](https://www.tomshardware.com/pc-components/dram/dram-and-nand-contract-prices-to-climb-again-in-q2)
- TSMC May 2026 revenue +30.1% YoY: [Digitimes](https://www.digitimes.com/news/a20260610VL218/2026-capacity-demand-revenue-taiwan-monthly-tracker-tsmc.html), [TSMC IR monthly revenue](https://investor.tsmc.com/english/monthly-revenue/2026)
- Micron FQ2 2026 results + FQ3 guide (reports FQ3 June 24): [Micron IR prepared remarks](https://investors.micron.com/static-files/e089f8c0-065d-47b8-9d02-bfa863cdb357), [earnings preview](https://www.techtimes.com/articles/318228/20260611/micron-earnings-preview-june-24-tests-whether-hbm-supercycle-real-cresting.htm)
- ASML Q1 2026 results + raised 2026 guide: [ASML press release](https://www.asml.com/en/news/press-releases/2026/q1-2026-financial-results)
- NVIDIA Q1 FY27 (May 20, 2026), DC +92% YoY: [NVIDIA 8-K](https://www.sec.gov/Archives/edgar/data/0001045810/000104581026000051/q1fy27pr.htm), [CNBC](https://www.cnbc.com/2026/05/20/nvidia-nvda-earnings-report-q1-2027.html)

*Data flags: (1) SEMI monthly NA book-to-bill discontinued since Feb 2022 — quarterly billings used as proxy. (2) ASML Q1 2026 exact net-bookings figure not disclosed in the release — qualitative only. (3) DRAM/NAND spot data is ~mid-April 2026 (latest cited public read) — slightly aged for a "high-frequency" signal; verify weekly. All other series are current as of 2026-06-19.*
