# AFM — CA Final Quick Reference (Sample — 7 of 16 chapters)

Built from OCR'd concept notes (CA Ajay Agarwal, May/Nov 2025 syllabus) and web-verified against ICAI/SEBI/RBI sources. Any line marked "⚠️ VERIFY" means double-check it against the original notes before relying on it. The remaining 9 chapters are pending and will be added in a later build.

## Contents

1. [Basics of AFM](#00-basics-of-afm)
2. [Risk Management](#02-risk-management)
3. [Security Analysis](#04-security-analysis)
4. [Securitization](#07-securitization)
5. [Mutual Funds](#08-mutual-funds)
6. [International Financial Management](#11-international-financial-management)
7. [Mergers, Acquisitions & Corporate Restructuring](#14-mergers-acquisitions--corporate-restructuring)

*Coming soon:* 01 Financial Policy & Corporate Strategy, 03 Advanced Capital Budgeting, 05 Security Valuation, 06 Portfolio Management, 09 Derivatives, 10 Foreign Exchange & Risk Mgmt, 12 Interest Rate Risk, 13 Business Valuation, 15 Startup Finance.

---

## 00. Basics of AFM

> **Where it fits:** the toolkit chapter — the financial-statement structure, ratios, interest-rate conventions, calculator technique and time-value-of-money mechanics that every later AFM topic (capital budgeting, valuation, portfolio, derivatives, forex) silently assumes.

### Financial Statements for AFM

**Income-statement ladder (AFM convention):**

$$\text{Sales} - \text{COGS} = \text{Gross Profit}$$
$$\text{Gross Profit} - \text{Operating Expenses} = \text{EBIT (PBIT / Operating Profit)}$$
$$\text{EBIT} - \text{Interest} = \text{EBT (PBT)}\;;\quad \text{EBT} - \text{Tax} = \text{EAT (PAT)}$$
$$\text{EAT} - \text{Preference Dividend} = \text{EATESH}$$
$$\text{EATESH} - \text{Equity Dividend} = \text{Retained Earnings}$$
$$\text{NOPAT} = \text{EBIT}\,(1-t)$$

**Balance-sheet identities:**

$$\text{Total Assets} = \text{Fixed Assets} + \text{Current Assets}$$
$$\text{Total Liabilities} = \text{Debt} + \text{Current Liabilities}$$
$$\text{Working Capital} = \text{Current Assets} - \text{Current Liabilities}$$
$$\text{Net Worth} = \text{Share Capital} + \text{Reserves \& Surplus} - \text{Preliminary Exp.} = \text{Total Assets} - \text{Total Liabilities}$$
$$\text{Capital Employed} = \text{Equity} + \text{Debt} = \text{Total Assets} - \text{Current Liabilities}$$

**Concept:** A slimmed statement used only to trace where each ratio's numerator/denominator sits. NOPAT = the after-tax operating profit available to *all* capital providers (debt + equity), so interest is **not** deducted — it is the base cash flow for DCF/EVA.

**Pitfalls / exam tips:**
- Unless told otherwise, treat all "Share Capital" as **equity**; add preference separately only when the question gives it.
- Preliminary expenses are a fictitious asset — always **subtract** them from Net Worth and Capital Employed.
- NOPAT ≠ PAT: PAT is *after* interest, NOPAT is *before* interest.

| Term | Meaning |
|---|---|
| EBIT | Earnings Before Interest & Tax = Operating Profit |
| EAT / PAT | Earnings/Profit After Tax (after interest & tax) |
| EATESH | Earnings Available To Equity Shareholders = PAT − Preference Dividend |
| Net Worth | Equity funds = Book Value = Shareholders' funds |
| Capital Employed | Long-term funds = Equity + Debt |

### Profitability & Margin Ratios

$$\text{GP Ratio}=\frac{\text{Gross Profit}}{\text{Sales}}\times100 \qquad \text{COGS Ratio}=\frac{\text{COGS}}{\text{Sales}}\times100 = 100\% - \text{GP Ratio}$$
$$\text{Operating Profit (Margin) Ratio}=\frac{\text{EBIT}}{\text{Sales}}\times100$$
$$\text{Operating Ratio}=\frac{\text{COGS}+\text{Operating Expenses}}{\text{Sales}}\times100 = 100\% - \text{Operating Profit Ratio}$$
$$\text{Net Profit Ratio}=\frac{\text{Net Profit (PAT)}}{\text{Sales}}\times100$$

**Concept:** Each margin expresses a profit line as a % of sales; higher is better.

**Pitfalls:** Operating Ratio and Operating Profit Ratio are complements (sum to 100%) — don't confuse the two.

### Capital-Structure / Leverage Ratios

$$\text{Debt Ratio}=\frac{\text{Debt}}{\text{Equity}+\text{Debt}} \qquad \text{Equity Ratio}=\frac{\text{Equity}}{\text{Equity}+\text{Debt}}$$
$$\text{Debt-Equity Ratio}=\frac{\text{Debt}}{\text{Equity}}$$
$$\text{Capital Gearing Ratio}=\frac{\text{Debt}+\text{Preference Share Capital}}{\text{Equity Share Capital}+\text{Reserves \& Surplus}}$$

**Concept:** Measure reliance on fixed-cost capital. Capital gearing groups *all* fixed-return capital (debt **and** preference) against equity — lower is safer.

**Pitfalls:**
- Debt Ratio + Equity Ratio = 1 (both use Capital Employed as denominator); Debt-Equity uses only equity below the line.
- Capital gearing puts **preference capital in the numerator** (it carries a fixed dividend) — a classic slip is to leave it in equity.

### Activity (Turnover) Ratios

$$\text{Assets TO}=\frac{\text{Sales}}{\text{Assets}} \quad \text{Fixed Assets TO}=\frac{\text{Sales}}{\text{Fixed Assets}} \quad \text{Current Assets TO}=\frac{\text{Sales}}{\text{Current Assets}}$$
$$\text{Inventory TO}=\frac{\text{COGS}}{\text{Stock}} \qquad \text{Debtors TO}=\frac{\text{Credit Sales}}{\text{Debtors}} \qquad \text{Assets-to-Sales}=\frac{\text{Assets}}{\text{Sales}}$$

**Concept:** How many rupees of sales each rupee of asset generates (expressed as "times", or ×100 for %). Higher = more efficient asset use.

**Pitfalls:**
- Inventory turnover uses **COGS**, not Sales (matches inventory's cost basis).
- Assets-to-Sales is simply the reciprocal of Assets Turnover.

### Coverage Ratios

$$\text{Interest Coverage Ratio}=\frac{\text{EBIT}}{\text{Interest}}\quad[\text{higher} = \text{safer}]$$
$$\text{Interest \& Fixed-Dividend Coverage}=\frac{\text{PAT}+\text{Interest}}{\text{Interest}+\text{Preference Dividend}}\quad[\text{higher} = \text{safer}]$$

**Concept:** Ability of earnings to service fixed financing charges.

**Pitfalls:** Interest Coverage takes **EBIT** (pre-interest, pre-tax). The combined coverage above is the book's simplified form (PAT add-back); if a question specifies a strict pre-tax basis, gross-up preference dividend by ÷(1−t) — read the requirement.

### Per-Share & Market-Value Ratios

$$\text{EPS}=\frac{\text{EATESH}}{\text{No. of Equity Shares}} \qquad \text{DPS}=\frac{\text{Equity Dividend}}{\text{No. of Equity Shares}}$$
$$\text{BVPS}=\frac{\text{Book Value (Net Worth)}}{\text{No. of Equity Shares}} \qquad \text{MPS}=\text{Market Price per Equity Share}$$
$$\text{Dividend Payout}=\frac{\text{Equity Dividend}}{\text{EATESH}}\times100=\frac{\text{DPS}}{\text{EPS}}\times100=100\%-\text{Retention Ratio}$$
$$\text{Retention Ratio}=\frac{\text{Retained Earnings}}{\text{EATESH}}\times100=100\%-\text{Payout}$$
$$\text{Dividend Yield}=\frac{\text{DPS}}{\text{MPS}}\times100 \qquad \text{P/E Ratio}=\frac{\text{MPS}}{\text{EPS}}$$
$$\text{Market Capitalisation}=\text{MPS}\times\text{No. of Equity Shares}=\text{P/E}\times\text{EATESH}$$

**Concept:** Bridge accounting output (EPS, BVPS) to market value (MPS, P/E, market cap).

**Pitfalls:** Payout Ratio + Retention Ratio = 100% — a fast cross-check. Dividend Yield is on **market price**; dividend rate (%) declared is on **face value** — never interchange.

### Return Ratios

$$\text{ROCE}=\frac{\text{EBIT}}{\text{Capital Employed}}\times100$$
$$\text{ROE}=\frac{\text{EATESH}}{\text{Net Worth}}\times100=\frac{\text{EPS}}{\text{BVPS}}\times100$$

**Concept:** ROCE = return to all capital providers (uses EBIT); ROE = return to equity only (uses EATESH).

**Pitfalls:** ROCE takes EBIT over Capital Employed; ROE takes EATESH over Net Worth — matching numerator to the capital base is where marks are lost.

| Note | Relation |
|---|---|
| ROE on market price | $\text{ROE}=\dfrac{\text{EPS}}{\text{MPS}}$ = earnings yield $=\dfrac{1}{\text{P/E}}$ |

### Interpretation of Dividend

| Basis | Metric |
|---|---|
| On **Face Value** | Dividend rate declared (%) |
| On **Market Price** | Dividend Yield |
| On **Earnings** | Dividend Payout |

**Exam tip:** "20% dividend" means 20% of *face value*, not of market price or EPS.

### Interpretation of Interest Rate

- **100 basis points (bps) = 1%** (so 1 bp = 0.01%).
- Every rate is **per annum (p.a.)** unless the question explicitly says otherwise — even "6-month LIBOR is 10%" or "interest for 6-month borrowing is 10%" means 10% **p.a.** Only "1% per month" is p.m.

**Pitfall:** For a 6-month period at a 10% p.a. rate, apply 5% for the period — don't apply the full 10%.

### Basic Mathematics (Powers & Calculator Technique)

$$a^{-n}=\frac{1}{a^{n}} \qquad \sqrt{a}=a^{1/2}$$

**Non-scientific calculator technique (exam hall):**
- **Whole power** $a^{n}$: type base → press ×, then press **= (n−1) times**. (e.g. $6^4$: 6 × = = = → 1296.)
- **"Dirty"/fractional power** $a^{p}$ (e.g. $6^{0.30}$): type base → press **√ 12 times** → **−1** → **× power** → **+1** → press **× = 12 times**.

**Concept:** ICAI allows only a basic calculator; the √-12-times routine approximates fractional exponents (used everywhere in TVM, IRR interpolation, volatility).

**Pitfalls:** BODMAS order — **B**racket, **O**rders (powers/roots), **D**ivide, **M**ultiply, **A**dd, **S**ubtract. Sign rules: $(-)\times(-)=(+)$; $5+(-3)=2$.

### Time Value of Money

$$\text{FV}=\text{PV}\,(1+R)^{t}\;;\qquad \text{FVF}_t=(1+R)^{t}$$
$$\text{PV}=\frac{\text{FV}}{(1+R)^{t}}=\text{Cash flow}_t\times\text{PVF}_t\;;\qquad \text{PVF}_t=\frac{1}{(1+R)^{t}}$$

**Uneven cash flows (limited period):**
$$\text{PV}=\sum_{t=1}^{n}\text{CF}_t\times\text{PVF}_t \quad(\text{use a Year / CF / PVF / PV table})$$

**Even cash flows (annuity):**
$$\text{PV}=\text{Annuity}\times\text{PVAF}_{n,r}$$

**Perpetuity (level, forever):**
$$\text{PV}=\frac{\text{Perpetual Cash Flow}}{R}$$

**Growing perpetuity (Gordon):**
$$\text{PV}=\frac{\text{First Perpetual Cash Flow}}{R-g}$$

**Mixed: uneven CF for a limited period, then perpetuity from year (t) onward:**
$$\text{PV}=\underbrace{\sum \text{CF}\times\text{PVF}}_{\text{explicit years}}+\text{TV}_{(t-1)}\times\text{PVF}_{(t-1)}$$
$$\text{TV}_{(t-1)}=\frac{\text{CF}_t}{R}\quad\text{(level)}\qquad \text{TV}_{(t-1)}=\frac{\text{CF}_{(t-1)}(1+g)}{R-g}\quad\text{(growing)}$$

**Concept:** Terminal value sits **one year before the first perpetual cash flow** (i.e. at t−1), so it must still be discounted back by $\text{PVF}_{(t-1)}$. For the growing case the first perpetual cash flow $=\text{CF}_{(t-1)}\times(1+g)$.

**Worked check (level TV):** CF₁₋₃ = 1,000 / 2,000 / 5,000 then 7,000 forever from yr 4, R = 10%. Explicit PV = 6,316; $\text{TV}_3 = 7{,}000/0.10 = 70{,}000$; discount ×0.751 = 52,570; **Total PV ≈ 58,886**.

**Worked check (growing TV):** same CF₁₋₃, then grows 2% from yr 4, R = 10%. $\text{TV}_3 = 5{,}000(1.02)/(0.10-0.02) = 63{,}750$; ×0.751 = 47,876; **Total PV ≈ 54,192**. Simple growing-perpetuity example: $1{,}000/(0.10-0.02)=12{,}500$.

**Pitfalls / exam tips:**
- Carry **PVF to 3 decimals** unless the question says otherwise; 3-year PVF @10% = **0.751** (the book's table once printed 0.757 — use 0.751).
- The single most common error: forgetting that the perpetuity/Gordon formula gives value at **t−1**, then failing to discount that TV to today.
- Growing perpetuity is valid only when $R>g$; if $g\ge R$ the formula breaks down.
- Match the discount period to the compounding frequency (semi-annual data → half-year rate, double the periods).

### References
1. **ICAI CA Final – Advanced Financial Management (Paper 2) Study Material, May 2025 onwards** — the exam authority; base for statement structure, ratios and TVM treatment.
2. **ICAI BOS Ratio Analysis (standard format) PDF, live.icai.org** — backs the ratio set incl. Capital Gearing = (Debt + Preference)/Equity.
3. **Wall Street Prep / Investopedia — NOPAT & Growing Perpetuity** — backs NOPAT = EBIT(1−t) and PV = CF₁/(R−g).
4. **LibreTexts Finance / Wall Street Oasis — Terminal Value timing** — confirms a perpetuity is valued one period before its first cash flow and must be discounted back.
5. **Standard corporate-finance references (Gordon growth model, annuity/PVAF, PVF tables)** — TVM discounting mechanics.

---

## 02. Risk Management

> **Where it fits:** Risk Management is the AFM foundation topic that classifies the risks a firm faces and quantifies market/loss risk — chiefly via the standard-normal Z-score and Value at Risk (VaR) — before the hedging chapters (derivatives, forex, interest-rate) apply mitigation tools.

### Types of Risk Faced by an Organization

**Concept:** Broad taxonomy examiners expect you to name and one-line define.

| Term | Meaning |
|---|---|
| Strategic Risk | Firm's strategy becomes less effective; it struggles to reach its goals. |
| Compliance Risk | Failure to comply with rules/regulations, leading to penalties. |
| Operational Risk | Internal risk — failure to handle day-to-day operations; relates to 'people' and 'process'. |
| Financial Risk | Unexpected changes in financial conditions — prices, exchange rate, credit rating, interest rate. |

**Evaluation of financial risk (perspectives):**
- **Stakeholder:** views financial gearing (ratio of debt in capital structure) as risk.
- **Company:** excessive borrowing can force it into liquidation.
- **Government:** viewed as failure of any bank.

### Classification of Financial Risk

**Concept:** ICAI splits financial risk into counter-party, political/country, and interest-rate risk — present each as Meaning / Assessment / Mitigation.

| Type | Meaning | Key mitigation |
|---|---|---|
| Counter-party risk | Non-honouring of obligations by counter party (also covers credit risk). | Due diligence, know/review exposure & credit limits, don't over-commit, performance guarantees, rapid action on default. |
| Political (Country) risk | Adverse host-government action against an overseas investor — confiscation, rationing of remittance, currency-conversion/borrowing restrictions, price control. | Local sourcing of materials & labour, joint ventures, local financing, prior negotiations. |
| Interest-rate risk | Change in interest rates altering the value of assets & liabilities. | Assessed via monetary policy, government action (e.g. demonetisation), economic growth; hedged in later chapters (FRA, swaps, futures). |

**Exam tip:** Mark schemes reward the Meaning / Assessment / Mitigation structure — write all three heads even under time pressure.

### Standard Normal Distribution & Z-Score

**Key formula:**

$$ Z = \frac{x - \mu}{\sigma} $$

**Concept:** Converts a required value into standard-deviation units; the probability is then read off the standard-normal table. Used inside VaR and in probability-of-loss questions.

**Worked logic (book example):** Mean wealth ₹5 lakh, σ = ₹1.5 lakh. For P(wealth < ₹2 lakh): Z = (2 − 5)/1.5 = −2.
- If *area from mean to Z* = 0.4772 → P(< 2L) = 0.50 − 0.4772 = **0.0228 (2.28%)**; P(> 2L) = 0.50 + 0.4772 = **0.9772 (97.72%)**.
- If *cumulative area up to Z=2* = 0.9772 → P(< 2L) = 1 − 0.9772 = 0.0228; P(> 2L) = 0.9772.
- If *one-tail area* = 0.0228 → P(< 2L) = 0.0228; P(> 2L) = 1 − 0.0228 = 0.9772.

**Pitfalls / exam tips:**
- Identify which table is given: *area-from-mean* (0.4772), *cumulative* (0.9772), or *one-tail* (0.0228) — each combines differently.
- Negative Z lies left of the mean; by symmetry left-tail(−2) = right-tail(+2).

### Value at Risk (VaR)

**Key formula(s):**

$$ \text{VaR}_{\text{security}} = \text{Investment}_{s} \times \sigma_{s} \times \sqrt{t} \times Z $$

$$ \text{VaR}_{\text{portfolio}} = \text{Investment}_{p} \times \sigma_{p} \times \sqrt{t} \times Z $$

$$ \sigma_{p} = \sqrt{w_A^{2}\sigma_A^{2} + w_B^{2}\sigma_B^{2} + 2\,w_A w_B\,\rho_{AB}\,\sigma_A \sigma_B} $$

**Concept:** VaR is the expected maximum loss on a share / portfolio over a given horizon at a chosen confidence level (parametric / variance-covariance method).

| Term | Meaning |
|---|---|
| σ_s / σ_p | Daily standard deviation of the security / portfolio |
| t | Number of days over which the loss is measured (√t scaling) |
| Z | Z-score for the chosen confidence, one-tailed (95% → 1.645, 99% → 2.326) |
| ρ_AB | Correlation coefficient between assets A and B |

**Pitfalls / exam tips:**
- σ must be *daily* to pair with √t in days; if σ is annual, keep t in years — stay consistent.
- Use the **one-tailed** Z for VaR (loss side only), not the two-tailed value.
- Portfolio σ_p is **not** the weighted average of the individual σ's — use the MPT formula; correlation below 1 reduces it.

### References

1. **ICAI CA Final AFM Study Material — Risk Management** (Paper 2: Advanced Financial Management, applicable May 2024 onward / 2025-26 syllabus): backs the risk taxonomy, financial-risk classification, and the Z-score / VaR treatment.
2. **Parametric (variance-covariance) VaR & square-root-of-time rule** — standard finance / CFA curriculum: VaR = Value × Z × σ × √t; one-tailed z of 1.645 (95%) and 2.326 (99%).
3. **Markowitz Modern Portfolio Theory** — two-asset portfolio standard deviation including the correlation term.
4. **Standard normal distribution table** — Z = (x − μ)/σ and area / cumulative / one-tail probability readings.

---

## 04. Security Analysis

> **Where it fits:** Security Analysis is the toolkit an investor uses to decide *buy / sell / hold* on a single security. In AFM it bridges into Portfolio Management and Security Valuation — fundamental analysis (intrinsic value) is covered under Security Valuation, while this chapter concentrates on **technical analysis**, **moving-average trading rules**, and **tests of the Efficient Market Hypothesis** (run test, autocorrelation).

---

### Meaning & Approaches of Security Analysis

**Concept:** Systematic analysis of security prices so an investor can take a purchase/sale decision. Two broad approaches:

| Approach | Basis | Where studied |
|---|---|---|
| **Fundamental Analysis** | Intrinsic worth from economy → industry → company; assumes price depends on future dividends/earnings | Security Valuation chapter (touched below) |
| **Technical Analysis** | Study of past price & volume charts to predict future price movement | This chapter |

**Exam tip:** Fundamental analysts ask *"what is it worth?"*; technical analysts ask *"where is the price heading?"*. The two are complementary, not mutually exclusive.

---

### Fundamental Analysis (EIC framework)

**Concept:** A top-down "E-I-C" drill — **E**conomy, then **I**ndustry, then **C**ompany — to arrive at intrinsic value. Assumes share price ultimately reflects the present value of future dividends/earnings.

| Level | Factors considered | Techniques |
|---|---|---|
| **Economic analysis** | National income growth, industrial-sector growth, inflation, monsoon | Anticipatory surveys; Barometer/Indicator approach (leading, roughly-coincidental, lagging indicators); Economic model-building |
| **Industry analysis** | Product life-cycle, demand-supply gap, barriers to entry, Govt. attitude | Regression analysis; Input-Output analysis |
| **Company analysis** | Net worth & book value, sources/uses of funds, growth record, financial analysis | Decision-tree analysis; Trend analysis; Correlation & regression |

**Exam tip:** Descriptive/theory marks — memorise the three-level table and the indicator sub-classification (leading / coincidental / lagging).

---

### Technical Analysis — Principles & Theories

**Concept:** A method of predicting share-price movement from the study of price graphs/charts, on the belief that history repeats and prices move in trends.

**Three underlying principles:**
1. Market discounts everything (all information is already in the price).
2. Price moves in trends.
3. History tends to repeat itself.

**Theories:**

| Theory | Originator | Core idea |
|---|---|---|
| **Dow (Dow Jones) Theory** | Charles Dow | Gauges relative strength of the market / acts as a business barometer, built on two indices (DJIA & DJTA). Market moves in **3 classifications**: *primary movement* (long-term tide), *secondary movement* (intermediate reaction), *daily fluctuations* (ripples). |
| **Elliott Wave Theory** | Ralph Elliott | Prices unfold in repeating waves: **impulsive/basic waves** (in trend direction) and **corrective/reaction waves** (against it) — classically a 5-wave advance + 3-wave correction. |
| **Random Walk Theory** | — | Stock-price behaviour is **unpredictable**; past price trends do not reliably predict future moves. Directly contradicts technical analysis and underpins the Efficient Market Hypothesis. |

**Pitfall:** Random Walk and Dow/Elliott are opposing philosophies — do not blend them in an answer. Random Walk says charts are useless; Dow/Elliott say charts reveal exploitable patterns.

---

### Moving Averages — Trading Decisions

Two moving averages are used to smooth out day-to-day noise and reveal the trend.

**1. Arithmetic / Simple Moving Average (AMA / SMA)** — simple average of the last *n* days' prices (equal weight to each day):

$$\text{SMA} = \frac{\sum \text{Share Prices of last } n \text{ days}}{n}$$

**2. Exponential Moving Average (EMA)** — exponentially weighted, giving more weight to recent prices; more responsive than SMA:

$$\text{EMA}_{\text{today}} = \text{EMA}_{\text{prev day}} + \Big[\big(\text{Closing Price}_{\text{today}} - \text{EMA}_{\text{prev day}}\big)\times K\Big]$$

where the smoothing constant (exponent) is:

$$K = \frac{2}{n+1}$$

**Concept:** *K* is the weight given to the change of the latest price from the previous EMA. *n* = number of days in the average. If a value of *K* (the exponent/multiplier) is supplied in the question, use it directly instead of `2/(n+1)`.

**Decision rule:**

| Moving-average trend | Market signal | Action |
|---|---|---|
| Rising day by day (up-trend) | Bullish | Take **long** position (buy) |
| Falling day by day (down-trend) | Bearish | Take **short** position (sell) |

A common variant: when the **price (or short-term MA) crosses above the longer MA → buy**; crosses below → sell.

**Pitfalls / exam tips:**
- AMA and EMA **cannot be computed for non-trading days** — skip holidays, don't carry the price forward.
- SMA gives equal weight to all *n* days; EMA front-loads recent data — state this if asked to compare.
- For the very first EMA in a series, the SMA (or the given seed) is used as the "previous day EMA".

---

### Efficient Market Theory / Hypothesis (EMH)

**Concept:** In an efficient market an investor *cannot* forecast prices from available information to earn abnormal profits — prices already reflect that information. Three levels:

| Form | Price reflects… | Implication |
|---|---|---|
| **Weak** | All past price information | **Technical analysis** cannot earn abnormal profit |
| **Semi-strong** | Past prices + all publicly available information | Neither technical **nor** fundamental analysis helps; only **private/insider** info could |
| **Strong** | Past prices + public + **private** information | **No one** (not even insiders) can earn abnormal profit |

**Pitfall:** Efficiency is *cumulative* — semi-strong includes weak, strong includes semi-strong. If strong form holds, all three hold.

---

### Test of Weak Form — Run Test

**Concept:** A non-parametric test of randomness. A **run** is an unbroken sequence of price moves in the *same* direction; a new run starts each time the direction reverses (a "+" spell followed by a "−" spell, etc.). If actual runs fall inside the expected band, price changes are random → weak-form efficient.

**Step 1 — Observed number of runs (r):** count the number of direction-change sequences in the price data.

**Step 2 / 3 — Count signs:** $n_1$ = number of "+" (up) movements, $n_2$ = number of "−" (down) movements.

**Step 4 — Expected (mean) number of runs:**

$$\mu_r = \frac{2\,n_1 n_2}{n_1 + n_2} + 1$$

**Step 5 — Standard deviation of runs (ICAI / CA-exam convention):**

$$\sigma_r = \sqrt{\frac{(\mu_r - 1)\,(\mu_r - 2)}{\,n_1 + n_2 - 1\,}}$$

**Step 6 — Confidence band:**

$$\text{Upper limit} = \mu_r + (\sigma_r \times t), \qquad \text{Lower limit} = \mu_r - (\sigma_r \times t)$$

**Conclusion:** If observed **r** lies **between** the lower and upper limits, the series is random → the market is in **weak form** of efficiency. *r* should be neither too low nor too high.

**Pitfalls / exam tips:**
- **Two SD formulas exist.** The ICAI/CA-exam form above uses $\mu_r$. The general-statistics form is $\sigma_r=\sqrt{\dfrac{2n_1 n_2\,(2n_1 n_2 - n_1 - n_2)}{(n_1+n_2)^2\,(n_1+n_2-1)}}$. **Use the ICAI form in the CA Final exam** (it is what the study material / examiner expects) unless the question specifies otherwise.
- ***t*** is the value from the standard normal / t-table at the given **significance level**; it is almost always **given in the question**. Degrees of freedom = $n_1 + n_2 - 1$.
- Count the *first* price only as a reference (no sign); signs are assigned to each *change*.

---

### Test of Weak Form — Autocorrelation / Serial Correlation Test

**Concept:** Tests whether today's price is correlated with a lagged (earlier) price. Split the price series into two equal periods and treat them as two "shares."

**Step 1 — Split & correlate:** e.g. for 20 days, Period 1 = days 1-10, Period 2 = days 11-20; compute the correlation coefficient between the two periods' prices:

$$\rho = \frac{\text{Cov}(P_1, P_2)}{\sigma_{P_1}\,\sigma_{P_2}}$$

**Step 2 — Interpret:** If $\rho \approx 0$, successive prices are **independent** → the market is **weak-form efficient**. A significant non-zero $\rho$ means prices are predictable from the past (weak form violated).

**Pitfall:** "Near zero" is the efficiency signal — a *high* correlation is evidence *against* weak-form efficiency (the opposite of a beginner's intuition that "high correlation = good/efficient").

---

### References

1. **ICAI, CA Final Study Material, Paper 2 — Advanced Financial Management, Chapter "Security Analysis"** (Final New Scheme, applicable May/Nov 2025) — the exam authority for the EIC framework, technical-analysis theories (Dow/Elliott/Random Walk), EMH forms, and the run-test/autocorrelation procedures & the $\mu_r$ / $\sigma_r$ conventions used above.
2. **Corporate Finance Institute — "Efficient Markets Hypothesis"** — backs the definitions of weak, semi-strong and strong forms of market efficiency (as of 2025).
3. **FxExplained / Statology / CapMint — "Exponential Moving Average"** — confirm the EMA recursive formula and the smoothing multiplier $K = 2/(n+1)$ (as of 2025).
4. **Standard non-parametric statistics references (runs test)** — confirm $\mu_r = \tfrac{2n_1 n_2}{n_1+n_2}+1$ and document the general-statistics variance $\tfrac{2n_1 n_2(2n_1 n_2 - n_1 - n_2)}{(n_1+n_2)^2(n_1+n_2-1)}$, noted as the alternative to the ICAI exam form.
5. **Charles Dow / Ralph Elliott — original technical-analysis theory** (Dow Theory 3 movements; Elliott 5-impulse + 3-corrective wave structure) — standard finance/technical-analysis literature.

*Source: OCR of CA Ajay Agarwal AFM Concept Book (May 2025 sitting), cross-checked against a second scan and the authorities above. Page boilerplate and dead diagram links removed.*

---

## 07. Securitization

> **Where it fits:** A theory-only chapter in AFM (ICAI treats it under "Securitization"). No numerical problems are set on it except conceptual pricing of the paper — examinable almost entirely as short/long theory notes. Know the parties, the mechanism, the instruments, and the risks cold.

### Meaning & Features
**Concept:** Securitization is the process of repackaging illiquid, income-generating assets (loans, mortgages, receivables) into marketable, tradable securities backed by the cash flows of those assets.

- **Features:** creation of financial instruments; bundling & unbundling; tool of risk management (default risk shifted to investors); structured finance (tailored to investor risk-return); **tranching** (pool split into slices of differing risk/return); homogeneity of issued securities.

| Term | Meaning |
|---|---|
| Bundling | Combining many assets into one pool |
| Unbundling | Splitting the pool into fixed-denomination instruments |
| Tranche | A slice of the pool carrying a distinct risk/return/priority of payment |

**Exam tip:** "Repackaging of illiquid assets into marketable securities" is the one-line definition graders look for.

### Benefits of Securitization
**Concept:** Benefits differ by the party viewing them.

- **Originator:** off-balance-sheet financing; greater focus/specialisation in core business; improved financial ratios; reduced borrowing cost.
- **Investor:** diversification of risk; helps meet regulatory requirements; protection against default (via credit enhancement/tranching).

### Participants
| Category | Participant | Role |
|---|---|---|
| Primary | Originator | Initiator/"securitizer"; sells assets off its books and receives funds |
| Primary | Special Purpose Vehicle (SPV) | Entity created solely for the deal; buys and holds the asset pool, issues the paper |
| Primary | Investors | Buyers of the securitized paper (retail/institutional) |
| Secondary | Obligors | Original borrowers who owe money (the underlying asset) |
| Secondary | Rating Agency | Assesses credit quality of the securitized paper |
| Secondary | Receiving & Paying Agent (RPA) / Servicer | Collects from obligors, passes cash to SPV |
| Secondary | Trustee | Safeguards investors' interest |
| Secondary | Credit Enhancer | Originator or third party (bank) giving added comfort via collateral / L-C / surety bonds |
| Secondary | Structurer / Arranger | Investment banker who brings all parties together |

**Exam tip:** SPV is central — it achieves the "true sale" and bankruptcy-remoteness that keeps the assets off the originator's books.

### Mechanism of Securitization
**Concept:** Sequential steps:
1. Creation of pool of assets (segregate similar mortgages/receivables).
2. Transfer to SPV.
3. Sale of securitized papers (SPV designs instruments, e.g. PTC & PTS).
4. Administration of assets (collect principal + interest).
5. Recourse to originator (on default, paper performance depends on underlying; may revert to originator).
6. Repayment of funds to investors from pooled cash flows.
7. Credit rating of instruments (before sale, to signal risk).

### Securitization Instruments
**Concept:** Classified by maturity/cash-flow structure.

| Instrument | Cash-flow character |
|---|---|
| Pass Through Certificate (PTC) | Direct ownership claim; all interest & principal collected are **passed straight through** to investors as received (pro-rata) |
| Pay Through Security (PTS) | SPV **debt** backed by the assets; SPV can restructure multiple tranches of differing maturities and reinvest surplus short-term |
| Stripped Securities | Pool cash flows split into two: **Interest-Only (IO)** and **Principal-Only (PO)** |

- **IO holder** receives only interest; **PO holder** receives only principal.
- **Rate sensitivity (examinable):** When market YTM **rises**, prepayments slow → **PO price falls**, and prolonged interest cash flows make **IO value rise**. When rates fall, prepayments speed up → PO gains, IO loses.

**Pitfall:** Do not equate PTS with PTC. PTC passes cash immediately (pass-through); PTS is a bond of the SPV that can be re-tranched and lets the SPV reinvest surplus (pay-through). IO/PO react to interest rates in **opposite** directions — the IO/PO direction is the single most tested trap.

### Pricing of Securitization Instruments
**Concept:** Price must be acceptable to both originator (an outflow/cost of funds) and investor (a required return).
- **Originator's angle:** priced at the rate at which the originator is willing to incur outflow (its effective cost of funds).
- **Investor's angle:** present value of the best estimate of expected future cash flows, discounted at the required yield to maturity (YTM).

**Key formula (investor's angle):**

$$P_0 = \sum_{t=1}^{n} \frac{E(CF_t)}{(1 + y)^{t}}$$

where $P_0$ = price of the securitized instrument, $E(CF_t)$ = expected cash flow (interest + principal, net of servicing) in period $t$, $y$ = required yield to maturity, $n$ = number of periods.

**Exam tip:** This is ordinary DCF/bond valuation applied to **expected** (not contractual) pool cash flows — expectations must reflect prepayment and default estimates.

### Risks in Securitization
| Risk | Nature |
|---|---|
| Credit / Counterparty risk | Bankruptcy or non-performance of the servicer/obligors |
| Legal risk | Weak statutory framework in India; disputes over legal ownership can delay investor payouts |
| Market risk — Macroeconomic | Underlying loan performance depends on industry/economy downturns |
| Market risk — Prepayment | Falling rates trigger prepayment → reinvestment risk at lower yields |
| Market risk — Interest-rate mismatch | Floating-rate pool vs fixed-rate payouts (or vice-versa) can leave inflows short of payouts |

### Problems in Securitization (Indian context)
**Concept:** Reasons for the dismal growth of securitization in India:
- **Stamp duty** on mortgage-debt transfer (can be very high, historically up to ~12% in some states).
- **Taxation** — SPV/trustee taxed in a representative capacity; investors taxed on their share of income.
- **Accounting** difficulties when assets are transferred without recourse.
- **Lack of standardization** — each originator uses its own documentation format.
- **Inadequate debt market** — no well-developed secondary debt market.
- **Ineffective foreclosure laws** — not supportive of lending institutions.

### Tokenization & Blockchain / DLT
| Term | Meaning |
|---|---|
| Tokenization | Converting tangible & intangible assets into blockchain tokens; like securitization it turns illiquid assets liquid |
| Similarities with securitization | Liquidity, diversification, tradability, new investment opportunities |
| Blockchain / Distributed Ledger Technology (DLT) | Shared, peer-to-peer, decentralised, immutable ledger with no trusted intermediary |

- **DLT applications:** financial services, healthcare, government, travel, economic forecasting.
- **DLT risks:** unclear risk-ownership/accountability; tampered technology corrupts stored data; no central authority weakens process controls; information overload from huge data volumes.

### Regulatory reference (India)
- Governed by the **RBI (Securitisation of Standard Assets) Directions, 2021** (issued 24 Sep 2021, as updated).
- **Minimum Retention Requirement (MRR):** originator must retain **5%** of book value for loans of original maturity ≤ 24 months, **10%** for > 24 months, and **5%** for residential-mortgage-backed securities (RMBS). MRR is held by the originating lender itself.
- **Minimum Holding Period (MHP):** the originator must hold a loan for a minimum period (now linked to loan tenor, not repayment frequency) before it is eligible for securitization — ensures seasoning and skin-in-the-game.

**Exam tip:** MRR + MHP together ensure the originator keeps "skin in the game," aligning it with investors (a post-2008-crisis reform).

### References
1. **RBI (Securitisation of Standard Assets) Directions, 2021** (RBI Master Direction, 24 Sep 2021, as updated) — MRR (5%/10%/5% RMBS), MHP, true-sale conditions; current for the 2025-26 syllabus.
2. **ICAI CA Final AFM Study Material — "Securitization" chapter** — features, participants, mechanism, instruments (PTC/PTS/stripped), pricing, risks, problems in India, tokenization/DLT (exam authority).
3. **Standard fixed-income valuation (bond DCF / YTM discounting)** — investor-angle pricing formula $P_0=\sum E(CF_t)/(1+y)^t$.
4. **Stripped MBS references (IO/PO strips)** — confirmation that a rise in interest rates lowers PO value and raises IO value (opposite prepayment sensitivities).

---

## 08. Mutual Funds

> **Where it fits:** In AFM, Mutual Funds is a high-scoring, calculation-light chapter on collective investment vehicles — computing NAV, pricing units (issue/repurchase with loads and dividend equalisation), measuring investor returns (HPR, annualised yield), and evaluating fund performance (expense ratio, tracking error). It also carries small theory-driven topics (SEBI structure, hedge-fund fees, indifference return).

---

### 1. Introduction & Types of Mutual Funds

**Concept:** A mutual fund is a **trust** that pools money from many investors by issuing **units**, and invests the pool in securities (shares, debentures, bonds, money-market instruments). It suits investors who lack time or expertise and want diversification with small outlays. Returns and risks are passed through to unitholders in proportion to units held.

**Definitions:**

| Term | Meaning |
|---|---|
| Open-ended scheme | No fixed maturity; units bought/sold continuously at NAV-based prices directly from the fund. |
| Close-ended scheme | Fixed corpus and maturity; units issued once, then traded on the exchange. |
| Interval scheme | Hybrid — open for purchase/redemption only during specified intervals. |
| Growth plan | Income reinvested; investor gains only through NAV appreciation (no payout). |
| Dividend / Income-payout plan | Fund distributes income periodically; NAV falls by the amount distributed. |
| Dividend reinvestment plan | Distributions used to allot additional units instead of cash. |
| Load | Charge added to (entry) or deducted from (exit) NAV on transacting in units. |

**Pitfalls / exam tips:**
- A mutual fund is a *trust*, not a company — the AMC merely manages it.
- SEBI has **abolished entry load** on Indian mutual-fund schemes (since Aug 2009); questions may still specify a load for computation, so use whatever the problem gives.

---

### 2. Establishment & SEBI Regulation of Mutual Funds

**Concept:** A mutual fund is registered with SEBI and set up under a **four-tier structure**: Sponsor → Trust/Trustees → AMC → Custodian.

**Definitions:**

| Party | Role / Norm (per SEBI (Mutual Funds) Regulations, 1996) |
|---|---|
| Sponsor | Like a promoter; provides seed capital and appoints trustees. Must be in financial-services business for **≥ 5 years** and contribute **≥ 40%** of the AMC's net worth. |
| Trust / Trustees | Fund is set up as a trust; **≥ 2/3 of trustees (trustee-company directors) must be independent.** Trustees hold property for unitholders' benefit. |
| AMC (Asset Management Company) | Manages the fund's investments; **≥ 50% of AMC directors must be independent.** May charge management & advisory fees. |
| Custodian | Holds custody of the fund's securities; registered with SEBI. |

**Pitfalls / exam tips:**
- ⚠️ VERIFY — **AMC minimum net worth:** the concept book states **₹100 crore**, but the operative SEBI figure under Reg. 21 is **₹50 crore** (raised from ₹10 cr in 2014, unchanged as of the 2025-26 syllabus). Write ₹50 crore unless the question quotes otherwise; flag the discrepancy if the book value is expected.
- "Sponsor ≥ 40% of AMC net worth" is a favourite one-liner; note that holding ≥ 40% of an AMC's net worth *deems* a person a sponsor.

---

### 3. Net Asset Value (NAV)

**Concept:** NAV is the per-unit value of the fund's net assets, computed (usually daily, at market value) as net assets divided by units outstanding. It drives issue and repurchase pricing.

**Key formulas:**

$$\text{NAV per unit} = \frac{\text{Net Assets of the Mutual Fund}}{\text{No. of Units Outstanding}}$$

**Net Assets buildup (at market value):**

| Particulars | Amount |
|---|---|
| Market value of investments (shares, debentures, bonds) | xx |
| (+) Accrued income (e.g. dividend/interest accrued) | xx |
| (+) Closing cash balance | xx |
| (−) Accrued expenses / expenses payable | (xx) |
| (−) Other liabilities (e.g. amount payable on securities) | (xx) |
| **Net Assets of the Fund** | **xx** |

**Closing cash balance** (when not given):

| Particulars | Amount |
|---|---|
| Amount received on issue of units | xx |
| (−) Initial expenses | (xx) |
| (−) Initial investment in securities | (xx) |
| (+) Sale proceeds of securities | xx |
| (−) Purchase cost of securities | (xx) |
| (+) Income received on investments (dividend/interest) | xx |
| (−) Realised earnings distributed to unitholders | (xx) |
| (−) Operating expenses paid | (xx) |
| (+) Amount received on issue of new units | xx |
| (−) Amount paid on repurchase of units | (xx) |
| **Closing cash balance** | **xx** |

**Roll-forward closing NAV** (when only opening NAV is available):

| Particulars | Amount |
|---|---|
| Opening net assets (opening units × opening NAV) | xx |
| (±) Portfolio appreciation / (depreciation) | xx/(xx) |
| (+) Issue of new units (units × issue price) | xx |
| (−) Repurchase of units (units × repurchase price) | (xx) |
| (+) Income earned during the period | xx |
| (−) Income distributed to unitholders | (xx) |
| (+) Sale proceeds of securities | xx |
| (−) Purchase cost of securities | (xx) |
| **Closing net assets** | **xx** |

$$\text{Closing NAV} = \frac{\text{Closing Net Assets}}{\text{Closing No. of Units Outstanding}}$$

**Pitfalls / exam tips:**
- Value investments at **market price**, not cost.
- Round NAV and number of units to **2 decimals** unless the question states otherwise.
- Don't double count: if income is *distributed*, it leaves cash *and* is not in net assets; if *retained*, it stays in cash/accrued income.

---

### 4. Issue Price & Repurchase Price

**Concept:** For open-ended funds, units are transacted at NAV adjusted for loads and dividend equalisation. Entry (front-end) load raises the buying price; exit (back-end) load lowers the selling price.

**Key formulas:**

$$\text{Issue (Public Offer) Price} = \text{NAV} + \big(\text{Entry Load\%} \times \text{NAV}\big) + \text{Dividend Equalisation p.u.}$$

$$\text{Repurchase (Redemption) Price} = \text{NAV} - \big(\text{Exit Load\%} \times \text{NAV}\big) + \text{Dividend Equalisation p.u.}$$

Equivalently, with load stated as a fraction of NAV:

$$\text{Issue Price} = \text{NAV}\,(1 + \text{Entry Load\%}) \qquad \text{Repurchase Price} = \text{NAV}\,(1 - \text{Exit Load\%})$$

**Definitions:**

| Term | Meaning |
|---|---|
| Entry / front-end load | Add-on to NAV paid by an incoming investor. |
| Exit / back-end load | Deduction from NAV borne by an outgoing investor. |
| Dividend equalisation | Per-unit accrued (undistributed) income; **collected** from new investors on issue and **paid** to exiting investors on repurchase, so distributable income per unit stays fair across cohorts. |

**Dividend equalisation p.u.** is derived from a "Statement of Income Available for Distribution": accumulate income earned each sub-period across the units then outstanding, add equalisation collected on fresh issues, deduct amounts attributable to repurchased units, giving per-unit income at each event date.

**Pitfalls / exam tips:**
- Both loads are usually a **% of NAV**, not of the issue/repurchase price — read carefully.
- Dividend equalisation is **added on both sides** (issue and repurchase): the incoming investor pays for income already accrued; the exiting investor is paid their share of accrued-but-undistributed income.

---

### 5. Returns — Holding Period Return & Annual Return

**Concept:** HPR is the total percentage return a unitholder earns over the holding period; annualising makes different holding periods comparable.

**Key formulas:**

Dividend-payout (regular income) plan:

$$\text{HPR (\%)} = \frac{\big(\text{End Value} - \text{Begin Value}\big) + \text{Income received}}{\text{Begin Value}} \times 100$$

where End Value = units × NAV(end), Begin Value = units × NAV(begin), Income received = units × income p.u.

Growth / dividend-reinvestment / bonus plan (income reflected in extra units, not cash):

$$\text{HPR (\%)} = \frac{\text{End Value} - \text{Begin Value}}{\text{Begin Value}} \times 100$$

where End Value = **(initial + reinvested/bonus units)** × NAV(end); Begin Value = initial units × NAV(begin).

Annualised return:

$$\text{Annual Return (\%)} = \text{HPR} \times \frac{365}{\text{No. of days held}} \quad\text{or}\quad \text{HPR} \times \frac{12}{\text{No. of months held}}$$

**Pitfalls / exam tips:**
- In the **payout** plan, distributed income is a separate cash inflow (numerator) — units stay constant. In the **reinvestment/bonus/growth** plan, income shows up as *more units*, so never add cash income again (double counting).
- If issue price / repurchase price are given, use them in place of NAV for begin/end values.
- Count **both** start and end dates when computing days held.

---

### 6. Evaluation — Expense Ratio & Tracking Error

**Concept:** Expense ratio shows the drag of operating costs on the fund; tracking error measures how tightly a fund follows its benchmark (key for index funds).

**Key formulas:**

$$\text{Expense Ratio (\%)} = \frac{\text{Total Operating Expenses during the period}}{\text{Average Net Assets}} \times 100, \qquad \text{Average Net Assets} = \frac{\text{Opening} + \text{Closing Net Assets}}{2}$$

$$\text{Tracking Error} = \sqrt{\frac{\sum (d - \bar{d})^2}{n - 1}}$$

where \(d\) = differential return = (Return on fund − Return on benchmark), \(\bar{d}\) = mean differential return, \(n\) = number of observations.

**Definitions:**

| Term | Meaning |
|---|---|
| Expense ratio | Operating costs (management/advisory fee, admin, marketing) as a % of average net assets. |
| Tracking error | Standard deviation of the fund-minus-benchmark return series; lower = closer tracking. |

**Pitfalls / exam tips:**
- Tracking error uses the **sample** standard deviation — divide by **(n − 1)**, not n.
- Work returns in **% units** consistently; a tracking error of "1.507%" means SD of the differential-return series.
- A high expense ratio erodes net investor return even when gross performance is strong.

---

### 7. Indifference Return (Direct vs Mutual-Fund Investment)

**Concept:** The gross return a mutual fund must earn so an investor is *indifferent* between investing directly in the market and going through the fund, after allowing for the fund's initial (one-time) and annual recurring expenses.

**Key formula:**

$$\text{Required MF Return (\%)} = \frac{\text{Return on direct investment (\%)}}{1 - \text{Initial Expenses (\%)}} + \text{Annual Recurring Expenses (\%)}$$

**Pitfalls / exam tips:**
- Initial expense is a **divisor** (grossing up the invested base that shrank at entry); recurring expense is simply **added** on top.
- Express all three inputs in % of the amount invested.

---

### 8. Hedge Fund Manager Fees

**Concept:** A hedge fund is a lightly-regulated, private pooled vehicle for select clients seeking high returns. The manager charges a fixed fee plus a performance-linked fee.

**Key formulas:**

$$\text{Base (fixed) Fee} = \text{Fixed \%} \times \text{Assets under Management}$$

$$\text{Incentive (performance) Fee} = \text{Incentive \%} \times \big(\text{Portfolio Value} - \text{Threshold}\big)$$

where the **threshold** is the contractually agreed level — typically the **high-water mark** (highest prior portfolio value) and/or a **hurdle rate**; the incentive fee applies only to value **above** it.

**Definitions:**

| Term | Meaning |
|---|---|
| Base fee | Charged on AUM regardless of performance (positive or negative return). |
| Incentive fee | Charged only on the excess of portfolio value over the agreed threshold. |
| High-water mark | Highest NAV/value previously reached; no incentive fee until it is exceeded, preventing double-charging for recovering past losses. |
| Hurdle rate | Minimum return that must be beaten before an incentive fee accrues. |

**Pitfalls / exam tips:**
- The classic structure is **"2 and 20"** (2% base, 20% incentive), but always use the % given.
- With a high-water mark, if the current value is **below** the mark, incentive fee = **0** (base fee still applies).
- Apply the hurdle before the high-water mark only if the contract specifies both; read the terms carefully.

---

### 9. Special Funds

**Concept:** Objective-specific schemes tested mostly as theory.

| Fund | Meaning |
|---|---|
| Index fund | Invests in the same stocks in the same weights as a chosen index (passive). |
| International fund | Raises money in India but invests globally. |
| Offshore fund | Located outside India; raises money globally to invest in India. |
| Sector fund | Invests the entire corpus in one sector (e.g. infrastructure, technology). |
| Money-market fund | Invests in short-term debt (commercial paper, T-bills, CDs). |

**Advantages:** professional management, diversification, convenient administration, potentially higher returns, tight regulation.
**Drawbacks:** no guaranteed return, over-diversification can dilute gains, difficulty selecting the right fund, cost (loads + expense ratio).

---

### References

1. **ICAI CA Final AFM Study Material (Paper 2, 2025-26 syllabus), Chapter "Mutual Funds"** — NAV computation, net-assets/closing-cash tables, issue & repurchase pricing, dividend equalisation, HPR (payout vs growth/reinvestment), annualised yield, expense ratio and tracking-error definitions.
2. **SEBI (Mutual Funds) Regulations, 1996 (as amended; current as of the 2025-26 syllabus), Reg. 7, 18, 21** — fund registration and four-tier structure; sponsor 5-year track record and ≥40% AMC net-worth contribution; ≥2/3 independent trustees; ≥50% independent AMC directors; **AMC minimum net worth ₹50 crore** (raised from ₹10 cr in 2014) — note the concept book's ₹100 cr figure is not the operative SEBI number.
3. **SEBI investor-education material / notification on abolition of entry load (effective 1 Aug 2009)** — treatment of loads in issue pricing.
4. **CA Final SFM/AFM revision references (e.g. ICAI-aligned faculty notes)** — indifference-return formula: MF return = Direct return ÷ (1 − initial expense%) + recurring expense%.
5. **CFA Program / standard alternative-investments references (hedge-fund fee structures)** — base ("management") fee on AUM, incentive fee on gains above a high-water mark / hurdle rate ("2 and 20").

---

## 11. International Financial Management

> **Where it fits:** The AFM cross-border chapter — how a firm raises money abroad (GDR/ADR/FCCB), appraises a project in a foreign currency (international capital budgeting), and measures the return a foreign investor earns on a security once currency movement is layered on. It leans on the Forex Exposure chapter for exchange-rate estimation (IRP/PPP) and on the Cost of Capital / Capital Budgeting chapters for the mechanics.

---

### International Sources of Finance

**Concept:** Instruments an Indian company uses to raise capital in foreign currency. A **Depository Receipt** is a negotiable certificate, denominated in a currency not native to the issuer, representing the company's underlying equity shares held by a custodian.

**Definitions**

| Term | Meaning |
|---|---|
| GDR | Global Depository Receipt — DR issued/traded **outside** the issuer's home country (and outside USA); represents underlying shares; raises foreign currency. |
| ADR | American Depository Receipt — a DR issued in the **USA**, denominated in USD. |
| IDR | Indian Depository Receipt — a DR issued **in India** by a foreign company. |
| FCCB | Foreign Currency Convertible Bond — a convertible bond issued in a currency other than the issuer's domestic currency; holder can convert into equity. |
| ECB (Euro Convertible Bond) | Debt instrument giving the holder an option to convert the bond into equity shares. |

**Pitfalls / exam tips**
- "GDR issued in the US = ADR; DR issued in India by a foreign issuer = IDR" — a favourite one-liner.
- **FCCB advantages:** flexibility to convert to equity, *delayed* dilution of equity, easily marketable. **Disadvantages:** higher exchange risk, creates more debt with interest outgo in foreign currency.
- GDRs usually carry **no voting rights** for the DR holder until conversion (shares are held by the custodian).

---

### Cost of GDR (Kₑ) and Number of GDRs to be issued

**Key formulas**

$$K_e = \left(\frac{D_1}{P_0}\right)\times 100 + g$$

where $g$ = growth rate of dividend, $P_0$ = **net proceeds per GDR**, and

$$D_1 = \left(\text{No. of shares underlying per GDR}\right)\times\left(\text{Expected dividend per underlying share at end of Year 1}\right)$$

$$\text{Issue Price per GDR} = \left(\text{No. of shares per GDR}\right)\times\left(\text{Market Price per underlying share}\right)\times\left(1 - \text{Discount on issue \%}\right)$$

$$P_0 = \text{Net Proceeds per GDR} = \text{Issue Price per GDR}\times\left(1 - \text{Flotation Cost \%}\right)$$

$$\text{No. of GDRs to be issued} = \frac{\text{Amount required for investment in the project}}{\text{Net Proceeds per GDR}}$$

**Concept:** A Gordon (constant-growth) cost-of-equity applied to a fresh issue: the price in the denominator is the **net proceeds** (after discount on issue *and* flotation cost), which raises Kₑ relative to using market price.

**Pitfalls / exam tips**
- GDRs are typically issued at a **discount to the current market price** — apply `(1 − discount%)` to the market price to get the issue price. Do not confuse the discount with flotation cost; both reduce proceeds and are applied sequentially.
- $D_1$ is the dividend **per GDR**, so multiply the per-share dividend by the number of shares bundled into one GDR.
- If the question gives $D_0$ and $g$, then $D_1 = D_0(1+g)$.

---

### International Capital Budgeting

**Concept:** Evaluating/selecting long-term projects in a foreign country. Techniques are identical to domestic capital budgeting (NPV, MIRR, etc.). The single rule: **cash flows and the discount rate must be in the same currency.** Two approaches:

**(i) Foreign Currency Approach** — estimate cash flows in foreign currency, discount at a foreign-currency discount rate, then convert the resulting NPV to home currency at the **spot rate at the beginning**.

$$r_{foreign} = \left[\frac{(1 + \text{Required Return in Home Currency})}{(1 + \text{Risk-Free Rate in Home Currency})}\times\left(1 + \text{Risk-Free Rate in Foreign Currency}\right)\right] - 1$$

**(ii) Home Currency Approach** — convert each year's foreign-currency cash flows to home currency using **estimated future exchange rates** (from IRP or PPP), then discount at the home-currency discount rate; NPV is already in home currency.

**Definitions**

| Term | Meaning |
|---|---|
| IRP (Interest Rate Parity) | Forward/estimated rate driven by the interest-rate differential between two currencies. |
| PPP (Purchasing Power Parity) | Estimated rate driven by the inflation-rate differential between two currencies. |

**Pitfalls / exam tips**
- The foreign-currency discount rate above strips the home real return and re-inflates it with the foreign nominal rate — it is the Fisher/IRP-consistent conversion of the home required return into a foreign-currency rate. Both approaches give the **same NPV** in a common currency if assumptions are consistent.
- **Silent case:** if the question gives one discount rate without saying which currency, assume it is the company's **home-currency** rate (use the Home Currency Approach).
- Convert the *final NPV* (not intermediate flows) at the spot rate under the Foreign Currency Approach.

---

### Foreign Company Developing a Product (Software) in India — Repatriation & Viability

**Concept:** An MNC gets software built by its Indian arm at a **transfer price**, then repatriates the after-tax profit home. Used to find the minimum price to charge the end customer and whether the project is viable.

**Repatriation amount (in ₹, then converted)**

| Particulars | Amount (₹) |
|---|---|
| Transfer Price | xxx |
| (−) Costs (rent, manpower, administration, etc.) | (xxx) |
| **EBT** | xxx |
| (−) Corporate Tax | (xxx) |
| **EAT** | xxx |
| (−) Withholding Tax *(only if NOT eligible for tax credit)* | (xxx) |
| **Repatriation Amount (₹)** | xxx |
| **Repatriation Amount (in foreign company's currency)** | xxx |

**Total cost incurred on product development** (in foreign currency) = Transfer Price − Repatriation Amount.

**Viability advice** = Selling price to customers − Total cost incurred on development = Profit / (Loss).

**Pitfalls / exam tips**
- Deduct **withholding tax only when it is not creditable** against home-country tax (double-tax-avoidance) — otherwise ignore it, as the parent recovers it.
- Keep the currency label on every line; convert to the parent's currency **only at the repatriation line** unless told otherwise.

---

### Return on Investment in International Securities Market

**Concept:** A foreign investor's total return = the security's return in its local currency, geared up or down by the currency movement on conversion back home.

**Method A — appreciation/depreciation % given**

Step 1 — domestic (local-currency) return:

$$R_{domestic} = \frac{D + P_1 - P_0}{P_0}\times 100$$

where $D$ = dividend/interest for the year, $P_1$ / $P_0$ = market price at end / beginning.

Step 2 — foreign investor's return (when the % change of the **security's currency** vs the investor's home currency is given):

$$R_{foreign} = \left(1 + R_{domestic}\right)\times\left(1 \pm \text{Appreciation/(Depreciation)}\right) - 1$$

(use **+** for appreciation of the security's currency, **−** for depreciation.)

⚠️ VERIFY — When instead the % change is quoted in terms of the **investor's home currency** (i.e. how the home currency moves against the security's currency), the OCR is garbled; the economically correct form is the reciprocal:
$$R_{foreign} = \frac{\left(1 + R_{domestic}\right)}{\left(1 \pm \text{Appreciation/(Depreciation) of home currency}\right)} - 1$$
(home-currency **appreciation ⇒ divide by (1 + %)**, i.e. the foreign investor's return falls). Confirm the exact denominator against the specific ICAI question wording.

**Method B — exchange rates given (step method)**
1. Convert the home-currency investment into foreign currency at the beginning spot rate.
2. Units bought = Investment in foreign ccy ÷ market price per unit at beginning.
3. Value at year-end (foreign ccy) = Units × market price per unit at year-end.
4. Convert step-3 value to home currency at the year-end exchange rate.
5. Return = (Home-ccy value at end − Home-ccy investment at beginning) ÷ Home-ccy investment at beginning.

**Pitfalls / exam tips**
- Never add the security return and the currency return arithmetically — **compound** them: `(1+r)(1±e) − 1`.
- Watch the direction convention: gains to the foreign investor come from the *security's currency appreciating* (equivalently, the home currency depreciating).

---

### Foreign Exchange Exposure — Essentials

**Concept:** Operating across currencies exposes a firm to three exposures; banks route interbank funds through three account types; and four broad strategies manage exposure.

**Definitions — types of exposure**

| Type | Meaning |
|---|---|
| Transaction Exposure | Effect of an exchange-rate change on **outstanding obligations** that are settled after the rate changes. |
| Translation / Accounting Exposure | Gains/losses from translating foreign-currency assets & liabilities into the **parent's currency for consolidation**. |
| Economic Exposure | Extent to which the firm's **economic value** can decline due to rate changes altering input costs and output prices. |

**Definitions — interbank accounts**

| Account | Meaning ("our / your / their") |
|---|---|
| Nostro | "Our account with you" — a bank's foreign-currency account held **in a foreign country**. |
| Vostro | "Your account with us" — a local-currency account maintained by a **foreign bank** with the domestic bank. |
| Loro | "Their account" — a third bank's account referenced when one bank remits foreign currency for credit to another bank. |

**Exposure-management strategies (risk : reward)**

| Strategy | Description |
|---|---|
| Low Risk : Low Reward | Automatic hedging of every exposure in the forward market as it arises; never leave a position open. |
| Low Risk : Reasonable Reward | Selective hedging — cover when forward rates are attractive, stay open when they are not. |
| High Risk : Low Reward | Worst strategy — leave all exposures unhedged; no effort. |
| High Risk : High Reward | Active trading via continuous cancellation/extension of forwards; treasury becomes a profit centre. |

**Pitfalls / exam tips**
- Translation exposure is a **book/consolidation** effect; economic exposure is a **cash-flow/value** effect over the long run — do not conflate them.
- **Money-market hedge** fixes the future rate (eliminates downside) but forgoes favourable movements and is more complex to arrange — a common advantage/disadvantage list.

---

### References

1. **ICAI CA Final AFM Study Material / Module — International Financial Management & Cost of Capital** (exam authority; 2025-26 syllabus): backs Cost of GDR = (D₁/P₀)+g using **net proceeds**, number of GDRs, repatriation/viability format, and the two capital-budgeting approaches.
2. **ICAI BOS — Cost of Capital chapter** (live.icai.org): backs the fresh-issue rule that net proceeds `(P − F)` replace market price in Kₑ.
3. **International Fisher Effect / Interest Rate Parity** (Fisher hypothesis; standard IFM references): backs the foreign-currency discount-rate conversion `[(1+home req.)/(1+home Rf)]×(1+foreign Rf) − 1` and IRP/PPP-based estimated exchange rates.
4. **International capital budgeting — foreign-currency vs home-currency (own-currency discounting) approach** (Cambridge *International Financial Management*; xplaind): backs the "same-currency for cash flows and discount rate" rule and NPV conversion at spot.
5. **Foreign-currency rate of return / uncovered return** (Saylor/Lardbucket *International Economics: Theory and Policy*, Ch. on FX markets and rates of return): backs the currency-adjusted foreign-investor return `(1+r_local)(1±Δe) − 1`.
6. **FEDAI / RBI interbank practice** (standard): backs the Nostro/Vostro/Loro account definitions and money-market/forward hedging notes.

---

## 14. Mergers, Acquisitions & Corporate Restructuring

> **Where it fits:** The applied "deal-math" chapter of AFM. Given two companies, you fix the consideration (a share **swap ratio** or **cash**), rebuild the merged entity's book value, earnings, market value and shareholding, decide who gains or loses, find the acceptable-ratio limits for each side, test deal feasibility by NPV, and handle the other restructuring tools (demerger, capital reduction, stock split, bonus, buyback).

**Notation used throughout:** subscript `A` = Acquirer, `T` = Target, `AT` = merged entity. `N` = no. of equity shares, `E` = earnings available to equity shareholders (PAT − preference dividend), `V` = market capitalisation, `ER` = exchange (swap) ratio, `t` = tax rate.

---

### Introduction & Market Capitalisation

**Concept:** Corporate restructuring reorganises operations to improve efficiency. Types: **M&A**, **Demerger**, **Reconstruction** (financial restructuring), **Stock split**, **Bonus issue**, **Equity buyback** (ownership restructuring). In an M&A the **Acquirer** buys the **Target**; the Target ceases to exist and its shareholders are paid in **shares** of the acquirer or in **cash**.

**Key formula(s):**

$$\text{Promoters' Holding \%} = \frac{\text{Shares held by Promoters}}{\text{Total Shares Outstanding}}\times 100$$

$$\text{Market Capitalisation} = \text{MPS}\times N = \text{EPS}\times \text{P/E} \times N$$

$$\text{Free-float Market Cap} = \text{MPS}\times(\text{Shares held by Non-Promoters})$$

**Definitions:**

| Term | Meaning |
|---|---|
| Market capitalisation | Market value of **all** equity (promoters + non-promoters) |
| Free-float market cap | Market value of **non-promoter** (public) shares only |

---

### Exchange (Swap) Ratio and Shares Issued — Share Offer

**Key formula(s):**

$$ER = \frac{\text{Parameter of Target}}{\text{Parameter of Acquirer}}\quad\text{(positive parameter: EPS, MPS, BVPS)}$$

$$ER = \frac{\text{Parameter of Acquirer}}{\text{Parameter of Target}}\quad\text{(negative parameter, e.g. NPA)}$$

$$\text{Weighted } ER = ER_1 W_1 + ER_2 W_2 + \dots + ER_n W_n$$

$$\text{Shares issued to Target} = N_T \times ER \qquad N_{AT} = N_A + (N_T \times ER)$$

$$\text{If consideration is given: Shares issued} = \frac{\text{Consideration}}{\text{MPS}_A}\;;\quad ER = \frac{\text{Shares issued to Target}}{N_T}$$

$$\text{Promoters' Holding \% in Merged Entity} = \frac{\text{Promoter shares in }A + \text{shares issued to Target's promoters}}{N_{AT}}\times 100$$

**Concept:** `ER` = number of acquirer shares given per 1 target share. Where several bases are used (e.g. BVPS 25% / EPS 50% / MPS 25%), take the weighted average.

**Pitfalls / exam tips:**
- A "positive" parameter (higher = better) puts **Target over Acquirer**; a negative parameter (lower = better, e.g. NPA) inverts it.
- `MPS_A` used to convert a cash-value consideration into shares is the **pre-merger** acquirer price.
- Watch rounding of `N_T × ER` — do not round to whole shares unless the question says so.

---

### Post-Merger Book Value — Share Offer

**Key formula(s):**

$$\text{Post-Merger Book Value} = \underbrace{N_{AT}\times \text{FV}_A}_{\text{Share Capital}} + \underbrace{(\text{Reserves}_A + \text{Capital Reserve on acquisition})}_{\text{Reserves}}$$

$$\text{Capital Reserve on acquisition} = \text{BV of Target} - (N_T\times ER)\times \text{FV}_A$$

$$BVPS_{AT} = \frac{\text{Post-Merger Book Value}}{N_{AT}}$$

**Concept:** The excess of the Target's book value over the par value of shares issued to it becomes capital reserve (a bargain / negative-goodwill style adjustment in this simplified model). `FV` = face (par) value per acquirer share.

---

### Post-Merger Earnings — Share Offer

**Key formula(s):**

$$E_{AT} = E_A + E_T + \text{Synergy in Earnings (if any)}$$

$$EPS_{AT} = \frac{E_{AT}}{N_{AT}}$$

**Concept:** Simply pool the two firms' earnings (add cost/revenue synergies), then divide by the enlarged share count. Because no debt is raised, there is **no interest drag** in a pure share offer.

---

### Post-Merger Market Value — Share Offer

**Key formula(s):**

$$MPS_{AT} = EPS_{AT}\times \text{P/E of Merged Entity}\quad\text{(if P/E given)}$$

$$MPS_{AT} = \frac{V_A + V_T + \text{Synergy in Market Value (if any)}}{N_{AT}}\quad\text{(if P/E not given)}$$

$$V_{AT} = MPS_{AT}\times N_{AT}$$

**Concept:** Synergy in market value = PV of future gains/savings. `V_A`, `V_T` may be pre-merger market caps or values derived from a valuation approach.

**Pitfalls / exam tips:**
- If a merged-entity P/E is given, use the P/E route (it captures re-rating); otherwise use the pooled-value route.

---

### Impact of Merger (Gain / Loss to Shareholders) — Share Offer

**Concept:** Also phrased "accretion/dilution", "benefit to shareholders", "better/worse off". Compare each group's post-merger position against its pre-merger position.

**Key formula(s):**

*On EPS basis:*

$$\text{Acquirer gain/share} = EPS_{AT} - EPS_A \qquad \text{Target gain/share} = (EPS_{AT}\times ER) - EPS_T$$

*On MPS basis:*

$$\text{Acquirer gain/share} = MPS_{AT} - MPS_A \qquad \text{Target gain/share} = (MPS_{AT}\times ER) - MPS_T$$

$$\text{Total gain to a group} = \text{gain/share}\times \text{(its pre-merger shares)}$$

$$\text{Total Gains from Merger} = \text{Total gain to Acquirer's SH} + \text{Total gain to Target's SH (on MPS)}$$

$$\text{True Cost of Merger (Net Cost / Cost of Takeover)} = \text{Total gain to Target's shareholders (on MPS)}$$

**Pitfalls / exam tips:**
- "Equivalent EPS/MPS" for the Target = post-merger figure **× ER** (because 1 old target share now equals `ER` merged shares).
- **If the question is silent, work on the MPS basis.**
- True cost of merger to the acquirer = the value handed to (gained by) the Target's shareholders — consistent with the standard "cost = value given − value of target received".

---

### Value of Original Shareholders

**Concept:** Splits the no-synergy merged value between the two original shareholder groups.

**Key formula(s):**

$$\text{Value per share} = \frac{V_A + V_T}{N_{AT}}$$

$$\text{Acquirer's SH} = \text{Value per share}\times N_A \qquad \text{Target's SH} = \text{Value per share}\times (N_T\times ER)$$

---

### Maximum Exchange Ratio (Acceptable to Acquirer)

**Concept:** The highest `ER` the acquirer can offer without diluting its own EPS/MPS. `ER` is solved as the balancing figure by setting the post-merger figure equal to the acquirer's pre-merger figure.

**Key formula(s):**

*No EPS dilution:*

$$\frac{E_{AT}}{N_A + (N_T\times ER)} = EPS_A$$

*No MPS dilution (P/E given):*

$$\frac{E_{AT}\times \text{P/E}_{AT}}{N_A + (N_T\times ER)} = MPS_A$$

*No MPS dilution (P/E not given):*

$$\frac{V_A + V_T + \text{Synergy (if any)}}{N_A + (N_T\times ER)} = MPS_A$$

**Pitfalls / exam tips:** If silent, use the **MPS (no-dilution) basis**. The acquirer wants a *low* ER; this gives its ceiling.

---

### Minimum Exchange Ratio (Acceptable to Target)

**Concept:** The lowest `ER` at which the Target's shareholders are no worse off (their equivalent EPS/MPS at least equals their pre-merger figure). `ER` is the balancing figure.

**Key formula(s):**

*No EPS dilution:*

$$\frac{E_{AT}}{N_A + (N_T\times ER)}\times ER = EPS_T$$

*No MPS dilution (P/E given):*

$$\frac{E_{AT}\times \text{P/E}_{AT}}{N_A + (N_T\times ER)}\times ER = MPS_T$$

*No MPS dilution (P/E not given):*

$$\frac{V_A + V_T + \text{Synergy (if any)}}{N_A + (N_T\times ER)}\times ER = MPS_T$$

**Pitfalls / exam tips:** If silent, use the MPS basis. The bargaining zone is **Min ER (Target) ≤ ER ≤ Max ER (Acquirer)**.

---

### M&A through Cash Offer

**Concept:** The Target's shareholders are paid cash, so **no shares are issued** ⇒ `N_AT = N_A`. Cash is usually borrowed, so post-merger earnings bear an **after-tax interest cost**.

**Key formula(s):**

$$\text{Cash paid} = \text{Cash per share}\times N_T$$

$$\text{Capital Reserve on acquisition} = \text{BV of Target} - (\text{Cash per share}\times N_T)$$

$$E_{AT} = E_A + E_T + \text{Synergy} - \big[\text{Cash/share}\times N_T\times \text{Interest Rate}\times (1-t)\big]$$

$$EPS_{AT} = \frac{E_{AT}}{N_A}\qquad BVPS_{AT} = \frac{\text{Post-Merger Book Value}}{N_A}$$

$$MPS_{AT} = EPS_{AT}\times \text{P/E}_{AT}\quad\text{OR}\quad \frac{V_A + V_T + \text{Synergy} - (\text{Cash/share}\times N_T)}{N_A}$$

$$V_{AT} = MPS_{AT}\times N_A$$

**Pitfalls / exam tips:**
- Divide by `N_A` (not `N_AT`) in every cash-offer per-share formula.
- The interest drag is **after tax**: `Interest × (1 − t)`. Omit it only if the question says the purchase is funded from own cash/reserves.

---

### Impact & Max/Min Cash — Cash Offer

**Key formula(s):**

$$\text{Acquirer gain/share} = MPS_{AT} - MPS_A \qquad \text{Target gain/share} = \text{Cash per share} - MPS_T$$

$$\text{True Cost of Merger} = \text{Total gain to Target's shareholders}$$

*Maximum cash per share (Acquirer, no dilution) — cash/share is the balancing figure:*

$$\frac{E_A + E_T + \text{Synergy} - [\text{Cash/share}\times N_T\times \text{Int.}\times(1-t)]}{N_A} = EPS_A$$

$$\frac{\{E_A + E_T + \text{Synergy} - [\text{Cash/share}\times N_T\times \text{Int.}\times(1-t)]\}\times \text{P/E}_{AT}}{N_A} = MPS_A$$

$$\frac{V_A + V_T + \text{Synergy} - (\text{Cash/share}\times N_T)}{N_A} = MPS_A\quad\text{(P/E not given)}$$

*Minimum cash per share (Target):*

$$\text{Min Cash/share} = MPS_T + \text{Loss of remuneration per share to Target's SH (if any)}$$

**Pitfalls / exam tips:** If silent, compute the maximum cash per share on the **MPS (no-dilution)** basis.

---

### Value of Acquisition & Financial Feasibility (NPV)

**Key formula(s):**

$$\text{Value of Acquisition} = V_{AT} - V_A$$

$$\text{NPV} = \text{PV of cash inflows from Target after acquisition} - \text{Net outflow to acquire Target}$$

$$\begin{aligned}\text{Net outflow} =\ &\text{Value of shares issued }(N_{issued}\times MPS_A) + \text{Debentures issued}\\ &+ \text{External-liability settlement} - \text{Amount realised from Target's assets (debtors, inventory, cash)}\end{aligned}$$

**Concept:** Value of acquisition = the gain in the acquirer's own value. Feasibility is judged on NPV.

**Pitfalls / exam tips:**
- **NPV > 0 ⇒ acquisition advantageous; NPV < 0 ⇒ not advantageous.**
- Net-outflow build-up nets off cash quickly realisable from the Target's own assets.
- (Value lens: a deal creates value only if post-deal **EVA = NOPAT − Invested Capital × WACC** improves; see Business Valuation chapter.)

---

### Demerger

**Concept:** A division of the **Demerged Company** is transferred to a **Resulting Company**. Assets and liabilities of the sold division move out; only the retained division's assets/liabilities stay. Usually the resulting company issues its shares to the demerged company's existing shareholders — a **spin-off**.

**Pitfalls / exam tips:** The **number of shares of the Demerged Company does not change** after a demerger.

---

### Reconstruction (Financial Restructuring)

**Concept:** Internal capital reduction/reorganisation. Compute the pool of "benefits", apply it to write off losses/assets, and the surplus is capital reserve.

**Key formula(s):**

$$\text{Step 1 — Benefits} = \begin{array}{l}\text{Reduction in Equity Capital} + \text{Reduction in Pref. Capital}\\ + \text{Waiver of debt claims (debentures, interest, creditors)} + \text{Upward revaluation of assets}\end{array}$$

$$\text{Step 2 — Utilised} = \begin{array}{l}\text{Write-off fictitious assets (prelim. exp., issue costs)} + \text{Write-off Dr. balance of P\&L}\\ + \text{Provisions created (e.g. bad debts)} + \text{Downward revaluation of assets}\end{array}$$

$$\text{Step 3 — Capital Reserve} = \text{Step 1} - \text{Step 2}$$

---

### Stock Split, Bonus Issue & Equity Buyback

**Concept:** Stock split raises share count by cutting face value (total capital unchanged). Bonus issue capitalises reserves into free shares (no cash in). Buyback purchases own shares (usually above market) to cut the share count.

**Key formula(s):**

*Stock split:*
$$N_{\text{after}} = \frac{\text{Existing Share Capital}}{\text{New Face Value per share}}$$

*Bonus issue (ratio a : b = a bonus per b held):*
$$N_{\text{after}} = N_{\text{before}} + \text{Bonus shares}\qquad \text{Reserves}_{\text{after}} = \text{Reserves}_{\text{before}} - (\text{Bonus shares}\times \text{FV})$$
$$EPS_{\text{after}} = \frac{E}{N_{\text{after}}}\qquad MPS_{\text{after}} = EPS_{\text{after}}\times \text{P/E}$$

*Equity buyback:*
$$\text{Buyback Price/share} = \text{Current MPS} + \text{Buyback Premium/share}$$
$$\text{Total buyback outlay} = \text{Shares bought back}\times \text{Buyback Price/share}$$
$$N_{\text{after}} = N_{\text{before}} - \text{Shares bought back}$$
$$EPS_{\text{after}} = \frac{E_{\text{before}} - \text{Interest on buyback loan}\times(1-t)}{N_{\text{after}}}\;;\quad \text{Interest} = \text{Total outlay}\times \text{Loan rate \%}$$
$$MPS_{\text{after}} = EPS_{\text{after}}\times \text{P/E}\qquad \text{Market Cap} = MPS_{\text{after}}\times N_{\text{after}}$$

**Pitfalls / exam tips:**
- Bonus/split leave **total earnings and total market cap unchanged** — only per-share figures fall proportionately (subject to any re-rating).
- Buyback EPS rises only if the after-tax cost of the buyback loan is **below** the firm's pre-buyback earnings yield; drop the interest term if the buyback is funded from own reserves.
- Buybacks in India are governed by **SEBI (Buy-Back of Securities) Regulations, 2018** (limits, debt-equity cap, procedure) read with s.68 Companies Act, 2013.

---

### References

1. **ICAI CA Final AFM Study Material — Ch. Mergers, Acquisitions & Corporate Restructuring** (2025-26 syllabus, exam authority) — swap/weighted ratio, post-merger EPS/MPS/BV, gain-loss and max/min ratio framework, NPV feasibility. Cross-checked against CA Ajay Agarwal concept book (source OCR).
2. **Ross, Westerfield, Jaffe & Jordan — Corporate Finance, Ch. 29 "Mergers and Acquisitions"** — cost of merger = value given − value of target received; NPV of merger = (V_B + synergy) − cost; synergy definition. (Standard reference, as-of 9th–13th eds.)
3. **CA Final AFM formula/revision compilations (Rohit Chipper; Zeroinfy exam-oriented theory)** — corroboration of ICAI swap-ratio weights (BV 25% / EPS 50% / MPS 25%) and true-cost-of-merger treatment.
4. **SEBI (Buy-Back of Securities) Regulations, 2018 — last amended 28 Nov 2024** (sebi.gov.in), with s.68 Companies Act, 2013 — legal basis and limits for equity buyback.
5. **Corporate Finance Institute / Wall Street Prep — Economic Value Added (EVA)** — EVA = NOPAT − (Invested Capital × WACC) = NOPAT − Capital Charge; value-creation lens for judging an acquisition. (As-of 2025.)
6. **CFA Program / AnalystPrep & Vernimmen — Effects of share repurchases on EPS** — buyback accretive only when after-tax cost of debt < pre-buyback earnings yield; after-tax interest = rate × (1 − t).

---

## ⚠️ Formulas to double-check

Every line still flagged `⚠️ VERIFY` across the 7 chapters, grouped by chapter. Confirm each against the original CA Ajay Agarwal notes / the cited authority before relying on it in the exam.

### 08. Mutual Funds
- **AMC minimum net worth:** the concept book states **₹100 crore**, but the operative SEBI figure under Reg. 21 is **₹50 crore** (raised from ₹10 cr in 2014, unchanged as of the 2025-26 syllabus). Write ₹50 crore unless the question quotes otherwise; flag the discrepancy if the book value is expected.

### 11. International Financial Management
- **Return on foreign security when the % change is quoted in the investor's home currency:** the OCR is garbled; the economically correct form is the reciprocal $R_{foreign} = \dfrac{1 + R_{domestic}}{1 \pm \text{Appreciation/(Depreciation) of home currency}} - 1$ (home-currency appreciation ⇒ divide by (1 + %), so the foreign investor's return falls). Confirm the exact denominator against the specific ICAI question wording.
