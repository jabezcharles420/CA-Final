# AFM — CA Final Quick Reference

> Built from OCR'd concept notes (CA Ajay Agarwal, May/Nov 2025 syllabus) and web-verified against ICAI / SEBI / RBI sources. Any **⚠️ VERIFY** flag means double-check that formula against the original notes.

## Contents

1. [00. Basics of AFM](#00-basics-of-afm)
2. [01. Financial Policy & Corporate Strategy](#01-financial-policy-corporate-strategy)
3. [02. Risk Management](#02-risk-management)
4. [03. Advanced Capital Budgeting Decisions](#03-advanced-capital-budgeting-decisions)
5. [04. Security Analysis](#04-security-analysis)
6. [05. Security Valuation](#05-security-valuation)
7. [06. Portfolio Management](#06-portfolio-management)
8. [07. Securitization](#07-securitization)
9. [08. Mutual Funds](#08-mutual-funds)
10. [09. Derivatives Analysis & Valuation](#09-derivatives-analysis-valuation)
11. [10. Foreign Exchange Exposure & Risk Management](#10-foreign-exchange-exposure-risk-management)
12. [11. International Financial Management](#11-international-financial-management)
13. [12. Interest Rate Risk Management](#12-interest-rate-risk-management)
14. [13. Business Valuation](#13-business-valuation)
15. [14. Mergers, Acquisitions & Corporate Restructuring](#14-mergers-acquisitions-corporate-restructuring)
16. [15. Startup Finance](#15-startup-finance)

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

## 01. Financial Policy & Corporate Strategy

> **Where it fits:** The opening chapter of CA Final AFM — a largely *theory* chapter that frames how financial policy (financing, investment, dividend, risk decisions) is aligned to corporate strategy and long-term value creation. The source concept book explicitly notes: *"No practical concepts in this chapter; theory concepts are covered in Section B."* The only quantitative tool examinable here is the **Sustainable Growth Rate (SGR)**.

---

### Advanced Role of the CFO in Value Creation

- **Concept:** Traditionally the CFO's role was limited to **wealth maximisation for shareholders** — maintaining financial health and implementing adequate financial controls. In today's globalised, information-and-communication-technology-driven environment, the CFO's responsibilities have expanded to a **leadership role in value creation**.
- **Advanced areas of CFO responsibility:**
  1. Risk management
  2. Supply chain
  3. Mergers, acquisitions, and corporate restructuring
  4. Environmental, Social and Governance (ESG) financing
- **Exam tip:** A common short-note / distinguish question. Remember the shift is *"from a scorekeeper/controller to a strategic value-creating partner."*

---

### Strategic Financial Decision-Making Framework

- **Concept:** The three fundamentals of any business are **Strategy, Finance and Management.** Strategic financial management applies financial-management techniques to strategic decisions to maximise the organisation's market value, allocating scarce capital among competing opportunities and then implementing and monitoring the chosen strategy.
- **Key financial decisions** falling within the scope of financial strategy:

  | Decision | Core question it answers |
  |---|---|
  | Financing decisions | What mix of debt/equity to raise funds? |
  | Investment decisions | Which projects/assets to deploy capital in? |
  | Dividend decisions | How much profit to distribute vs. retain? |
  | Portfolio decisions | Which combination of businesses/assets to hold? |

- **Exam tip:** These four decisions are frequently asked as a list — link each back to "maximising market value."

---

### Strategy at Different Hierarchy Levels

- **Concept:** There are **three levels of strategy** in an organisation.

  | Level | Focus |
  |---|---|
  | **Corporate level strategy** | Selection of the businesses in which the company should compete. Must answer three tests: **Suitability, Feasibility, Acceptability.** |
  | **Business unit level strategy** | Practical coordination of operating units within a business. |
  | **Functional level strategy** | Functional business processes and the value chain; develops resources in operating departments so that business-unit strategies are executed efficiently and effectively. |

- **Pitfall:** Do not confuse the three **corporate-level tests** (Suitability / Feasibility / Acceptability) with the three **levels** of strategy — examiners test both separately.

---

### Interface of Financial Policy and Strategic Management

- **Concept:** Corporate strategy deals with **deployment** of resources; financial strategy is concerned with the **mobilisation and effective utilisation of money**. The two must be integrated — financial policy provides the framework within which strategic choices are financed.
- **Key interface dimensions (ICAI):**
  - Financing patterns and sources of long-term funds
  - Investment and fund-allocation decisions (policies regulating investment in fixed assets and restraining current assets)
  - Dividend and retention policy consistent with growth targets
- **Exam tip:** Frequently asked as *"Discuss the interface of financial policy and strategic financial management."* Anchor the answer on the deployment-vs-mobilisation distinction.

---

### Balancing Financial Goals vs. Sustainable Growth

This is the one **numerical/formula** area of the chapter.

- **Concept:** The **Sustainable Growth Rate (SGR)** is the *maximum rate at which sales/equity can grow without raising fresh external equity and without changing operating or financial policies* (i.e., funded only by retained earnings and proportional debt). A conflict arises if growth objectives are inconsistent with SGR — growing **too fast** strains funding, growing **too slow** wastes capacity; financial policy should keep actual growth close to the sustainable rate.

**Key formula(s):**

Simple (retention × profitability) form:

$$ \text{SGR} = b \times \text{ROE} = (1 - \text{Dividend Payout Ratio}) \times \text{ROE} $$

where the **retention ratio** is:

$$ b = 1 - \frac{\text{Dividends}}{\text{Net Income}} = \frac{\text{Retained Earnings}}{\text{Net Income}} $$

Higgins **PRAT** decomposition (ROE expanded via DuPont — profit margin × retention × asset turnover × leverage):

$$ \text{SGR} = \underbrace{\frac{\text{Net Profit}}{\text{Sales}}}_{P}\times\underbrace{b}_{R}\times\underbrace{\frac{\text{Sales}}{\text{Total Assets}}}_{A}\times\underbrace{\frac{\text{Total Assets}}{\text{Equity}}}_{T} $$

Underlying DuPont identity for ROE:

$$ \text{ROE} = \frac{\text{Net Profit}}{\text{Sales}}\times\frac{\text{Sales}}{\text{Total Assets}}\times\frac{\text{Total Assets}}{\text{Equity}} $$

- **Pitfalls / exam tips:**
  - Use **ROE on *beginning* equity** for the exact SGR $b\times ROE$; if ROE is computed on *ending* (average) equity, the textbook-exact form is $\text{SGR}=\dfrac{b\times ROE}{1-(b\times ROE)}$. State your assumption. ⚠️ VERIFY — ICAI problems almost always use the plain $b\times ROE$ (beginning-equity) version; adopt that unless the question specifies average equity.
  - "T" in PRAT is the **equity multiplier** (Total Assets ÷ Equity), *not* the tax rate — a classic slip.
  - SGR assumes **no new equity issue** and **constant** margins, asset turnover, leverage and payout. If any of these change, the actual affordable growth differs.
  - Retention ratio $b$ = 1 − payout; do not mix the two up.

**Definitions:**

| Term | Meaning |
|---|---|
| Sustainable Growth Rate (SGR) | Max growth financeable without new equity, holding policies constant |
| Retention ratio (b / plough-back) | Fraction of earnings retained = 1 − payout ratio |
| ROE | Return on Equity = Net Profit ÷ Shareholders' Equity |
| Equity multiplier (leverage, T) | Total Assets ÷ Equity — degree of financial leverage |
| PRAT model | Higgins' four-factor SGR = Profit margin × Retention × Asset turnover × leverage (T) |

---

### References

1. ICAI, *Final Course Study Material, Paper 2: Advanced Financial Management — Chapter 1: Financial Policy and Corporate Strategy* (Learning outcomes, CFO role, strategy levels, financial-policy interface, sustainable growth). https://resource.cdn.icai.org/74828bos60509-cp1.pdf and https://resource.cdn.icai.org/87842bos-aps2163-ch1.pdf
2. ICAI BoS Live, *Paper-2 Advanced Financial Management — Module 1* chapter listing (New Syllabus, 2025-26). https://boslive.icai.org/sm_chapter_details.php?p_id=35&m_id=73
3. R. C. Higgins, "How Much Growth Can a Firm Afford?", *Financial Management* (1977) — origin of the sustainable growth rate and the PRAT decomposition.
4. AnalystPrep / CFA Level II notes, *Financial Determinants of Growth Rates* — SGR = b × ROE and DuPont expansion. https://analystprep.com/study-notes/cfa-level-2/financial-determinants-of-growth-rates/
5. Wall Street Prep, *Sustainable Growth Rate (SGR): Formula + Calculator* — retention ratio and ROE cross-check. https://www.wallstreetprep.com/knowledge/sustainable-growth-rate/
6. Source concept book: *AFM Concept Book — CA Ajay Agarwal (AIR 1)*, Ch. "Financial Policy and Corporate Strategy" and Section B Theory Concepts (May 2026 edition OCR).

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

## 03. Advanced Capital Budgeting Decisions

> **Where it fits:** The toolkit for evaluating long-term investments/projects — the core discounting techniques (NPV, PI, IRR, MIRR, APV), how to handle inflation, how to build risk into the decision (RADR, certainty equivalent, sensitivity, statistical/decision-tree analysis), replacement & asset-selection decisions (EAC), and valuing managerial flexibility as Real Options.

---

### Cash Flow Building Blocks (for any NPV)

- **Concept:** Before any technique, lay out (i) Initial Investment at t=0, (ii) operating cash inflows each year, and (iii) terminal cash flows at end of life.

**Initial Investment (t = 0):**
$$\text{Initial Investment} = \text{Cost of Asset (Purchase} + \text{Installation)} + \text{Investment in Working Capital}$$

**Annual operating cash inflow:**
$$\text{CFAT} = \text{NOPAT} + \text{Depreciation} \pm \Delta \text{Working Capital}$$
where $\text{NOPAT} = \text{EBIT}(1-t)$ (profit after tax before interest).

**Terminal-year add-ons (last year only):**
$$\text{Terminal CF} = \text{Release of Working Capital} + \text{Salvage Value} \pm \text{Tax Effect on Sale of Asset}$$

$$\text{Tax Effect on Sale} = (\text{Salvage Value} - \text{Book Value}) \times \text{Tax Rate}$$

**Pitfalls / exam tips:**
- Allocated/apportioned fixed overheads and **sunk (historical) costs are NOT relevant** — exclude them from cash flows.
- Salvage > Book Value → tax on gain (outflow); Salvage < Book Value → tax **saving** on loss (inflow). Sign carefully.
- Include opportunity costs; use **incremental** cash flows only.

---

### Net Present Value (NPV)

**Key formula:**
$$\text{NPV} = \sum_{t=1}^{n} \frac{\text{CF}_t}{(1+r)^t} - \text{Initial Investment}$$

**Concept:** PV of inflows minus initial outlay. **Accept if NPV > 0**, reject if NPV < 0. Absolute rupee measure of value added.

**Pitfalls / exam tips:**
- Discount-rate priority: (1) rate given in question → (2) required rate of return → (3) cost of capital (WACC).

---

### Profitability Index (PI)

**Key formula:**
$$\text{PI} = \frac{\text{PV of Cash Inflows}}{\text{Initial Investment}}$$

**Concept:** Value per rupee invested. **Accept if PI ≥ 1**, reject if PI < 1. Best for ranking under capital rationing.

---

### Internal Rate of Return (IRR)

**Key formula (IRR = r that makes NPV = 0):**
$$\sum_{t=1}^{n} \frac{\text{CF}_t}{(1+\text{IRR})^t} = \text{Initial Investment}$$

Interpolation between rates $r_L$ (positive NPV) and $r_H$ (negative NPV):
$$\text{IRR} = r_L + \frac{\text{NPV}_{r_L}}{\text{NPV}_{r_L} - \text{NPV}_{r_H}} \times (r_H - r_L)$$

**Concept:** The rate at which PV of inflows equals the outlay. **Accept if IRR > required rate / cost of capital.**

**Pitfalls / exam tips:**
- Assumes reinvestment of inflows **at IRR** (often unrealistic) — this is why MIRR exists.
- Non-conventional cash flows (sign changes) can give multiple IRRs.

---

### Modified Internal Rate of Return (MIRR) — Terminal Value Method

**Key formula:**
$$\text{MIRR} = \left[\frac{\text{Terminal Value of Cash Inflows}}{\text{Initial Investment}}\right]^{\frac{1}{t}} - 1$$

where **Terminal Value** = each inflow compounded forward to end of project life at the discount/reinvestment rate, and $t$ = life of project.

**Concept:** IRR variant that assumes inflows are **reinvested at the discount rate** (not at IRR) and accumulated to the end of life. More realistic reinvestment assumption than plain IRR.

**Pitfalls / exam tips:**
- Compound inflows forward using the reinvestment (discount) rate before applying the root; do not present-value them.

---

### Adjusted Present Value (APV)

**Key formula:**
$$\text{APV} = \text{Base NPV} + \text{PV of Financing Side-effects}$$

$$\text{Base NPV} = \left(\text{Cash inflows discounted at Cost of Equity } K_e\right) - \text{Initial Investment}$$

$$\text{Effect of Debt} = \text{PV of Interest Tax Shield, discounted at pre-tax Cost of Debt}$$

where annual interest tax shield $= \text{Debt} \times \text{Interest Rate} \times \text{Tax Rate}$.

**Concept:** Value the project as if **all-equity financed** (base case), then add the PV of financing benefits (mainly the debt interest tax shield). Useful when the capital structure changes over the project life.

**Pitfalls / exam tips:**
- Base NPV uses **unlevered cost of equity ($K_e$)**, not WACC.
- Tax shield is discounted at the **pre-tax cost of debt** (per this book's approach).

---

### Impact of Inflation

**Key formulas:**

Convert real cash flow to nominal (same inflation each year):
$$\text{Nominal CF}_t = \text{Real CF}_t \times (1 + \text{Inflation Rate})^{t}$$

Different inflation each year:
$$\text{Nominal CF}_n = \text{Real CF}_n \times (1+IR_1)(1+IR_2)\cdots(1+IR_n)$$

Fisher relation — convert real discount rate to nominal:
$$1 + \text{Nominal Rate} = (1 + \text{Real Rate}) \times (1 + \text{Inflation Rate})$$
$$\Rightarrow \text{Nominal Rate} = (1+\text{Real})(1+\text{Inflation}) - 1$$

**Concept:** Be consistent — discount **nominal** cash flows at the **nominal** rate (or real at real). Never mix.

**Pitfalls / exam tips:**
- **Depreciation is based on historical cost** — it is NOT inflated (tax shield stays on original cost).
- The OCR example "$100 \times (1.10)^2 = 110$" for Year 1 is an OCR slip — Year 1 uses exponent 1: $100 \times (1.10)^1 = 110$.

---

### Risk Analysis — Conventional Techniques

#### (1) Risk-Adjusted Discount Rate (RADR)

**Key formulas:**
$$\text{RADR} = \text{Risk-free Rate} + \text{Risk Premium}$$
$$\text{Risk Premium} = (\text{Minimum Required Return of firm} - \text{Risk-free Rate}) \times \text{Risk Index}$$

**Concept:** Higher project risk → discount at a higher rate. Then compute NPV using RADR as the discount rate.

#### (2) Certainty Equivalent (CE) Approach

**Key formulas:**
$$\text{Certain CF}_t = \text{Expected CF}_t \times \text{Certainty Equivalent Coefficient}_t$$
$$\text{Discount Rate} = \text{Risk-free Rate}$$

**Concept:** Convert risky expected cash flows into risk-free equivalents (CE coefficient between 0 and 1), then discount at the risk-free rate — risk is handled in the **numerator**, not the denominator.

**Pitfalls / exam tips:**
- In RADR risk sits in the discount rate; in CE it sits in the cash flow. Do **not** double-count by using both.
- CE coefficient falls (closer to 0) as risk rises.

#### (3) Utility Approach

**Key formula:**
$$\text{Expected Utility} = \sum (\text{Utility Value}_i \times \text{Probability}_i)$$

**Concept:** Assign utility values (per the question's utility function) to outcomes; select the project with the **highest expected utility**.

| Method | Risk adjusted in | Discount rate |
|---|---|---|
| RADR | Discount rate | Risk-free + premium |
| CE | Cash flows | Risk-free rate |
| Utility | Utility of outcomes | (compare expected utility) |

---

### Sensitivity Analysis

**Concept:** Change **one variable at a time** (initial investment, sales volume, selling price, variable cost, fixed cost, discount rate, life) holding others constant, and see how NPV responds. The **most sensitive** factor is the one the decision is most vulnerable to.

**Method A — fixed % adverse change:**
$$\% \text{ Change in NPV} = \frac{\text{Existing NPV} - \text{Revised NPV}}{\text{Existing NPV}} \times 100$$
Most sensitive factor = **highest % change in NPV**.

**Method B — change that drives NPV to zero:**
$$\% \text{ Change in factor} = \frac{\text{Revised Value (NPV}=0) - \text{Existing Value}}{\text{Existing Value}} \times 100$$
Most sensitive factor = **lowest % change** needed to wipe out NPV.

**Pitfalls / exam tips:**
- Only one variable moves per run; keep all others at base value.
- Sensitivity analysis shows *which* variable matters but not the *probability* of the change.

---

### Statistical Techniques

**Concept:** Use probability distributions of cash flows to get Expected NPV, its risk (SD), and Coefficient of Variation.

**Expected NPV (when NPVs & probabilities given):**
$$\text{ENPV} = \sum P_i x_i \quad (x = \text{NPV})$$

**Risk of the project:**
$$\text{Variance } (\sigma^2) = \sum P_i (x_i - \text{ENPV})^2 \qquad \text{SD } (\sigma) = \sqrt{\sigma^2}$$

**Coefficient of Variation (risk per unit of return):**
$$\text{CV} = \frac{\text{Standard Deviation}}{\text{Expected NPV}}$$

#### Perfectly Independent cash flows across years

Expected net cash flow each year: $\text{ENCF}_t = \sum P x$. Then:
$$\text{ENPV} = \sum_{t=1}^{n} \frac{\text{ENCF}_t}{(1+r)^t} - \text{Initial Investment}$$
$$\sigma_p^2 = (\sigma_{cf_1} \times PVF_1)^2 + (\sigma_{cf_2} \times PVF_2)^2 + \cdots + (\sigma_{cf_n} \times PVF_n)^2$$
$$\sigma_p = \sqrt{\sigma_p^2}$$

#### Perfectly Dependent cash flows (Scenario Analysis)

Compute NPV under Worst / Most-Likely / Best case, then apply $\text{ENPV} = \sum Px$ and $\sigma = \sqrt{\sum P(x-\text{ENPV})^2}$ on the three scenario NPVs.

#### Moderately Dependent cash flows

Draw a decision tree of paths, get **joint probability** of each path, compute path NPVs, then $\text{ENPV}=\sum Px$ and SD on joint probabilities.

**Pitfalls / exam tips:**
- Unless the question hints otherwise, **treat cash flows as perfectly independent**.
- Selection rule: highest ENPV / lowest SD / **lowest CV** (CV is the best cross-project comparison when scales differ).
- For independent flows the yearly SDs are discounted and squared; for dependent flows you work on NPV outcomes directly — don't confuse the two.

---

### Decision Tree Analysis

**Concept:** For projects needing a **sequence of decisions** over time, where later investment depends on the outcome of earlier events. Roll back from right to left.

**Steps:**
1. Draw the tree (decision nodes □, chance nodes ○) with probabilities.
2. At each later decision point, compute NPV; **invest only if beneficial** (if benefit is negative, take it as zero — you would not invest).
3. Compute Expected Monetary Value at each chance node:
$$\text{EMV} = \sum (\text{Probability} \times \text{Benefit at that outcome})$$
4. At the first decision point, compare Investment amount vs EMV to decide.

**Pitfalls / exam tips:**
- A negative downstream branch is abandoned (value 0), not carried as a loss — that is the value of flexibility.

---

### Replacement Decision

**Concept:** Decide whether an existing asset should be replaced by a new one.

**(A) Replace now or not — Incremental NPV:**
$$\text{Incremental NPV} = \text{PV of Incremental Cash Inflows} - \text{Incremental Initial Investment}$$

Incremental initial investment:
$$= \text{Cost of New Asset} - \left[\text{Current Salvage of Old} \pm \text{Tax effect on sale of Old}\right]$$

Incremental annual inflow (either method):
$$= (\text{Increase in Sales} + \text{Savings in Operating Cost}) - \text{Extra Depreciation} \text{, then} \times(1-t) + \text{Extra Depreciation tax shield}$$
or simply: (Cash inflow if New) − (Cash inflow if Old continued).

**Decision:** Incremental NPV > 0 → **replace**.

**(B) When to replace — now or later (Total NPV approach):**
Compare Total NPV of replacing now vs after 1 year vs after 2 years …:
$$\text{Total NPV (Replace Now)} = \text{Current Salvage of Old} \pm \text{NPV of New Asset}$$
$$\text{Total NPV (Replace after 1 yr)} = [\text{CF from Old in Yr1} + \text{Salvage of Old at end Yr1} \pm \text{NPV of New}] \times PVF_1$$
(extend the same way for later years). **Choose the year with the highest Total NPV.**

**Pitfalls / exam tips:**
- Use **incremental** figures throughout; ignore the old asset's original cost (sunk).
- In the "when to replace" version, the NPV of the new asset is itself brought back with the appropriate PVF for the deferral year.

---

### Equivalent Annual Cost (EAC) & Asset Selection

**Key formula:**
$$\text{EAC} = \frac{\text{PV of Cash Outflows of Asset}}{\text{PVAF @ discount rate for life of asset}}$$

PV of cash outflows:
$$= \text{Initial Investment} + \text{PV of Annual Running Costs} - \text{PV of Salvage Value}$$

**Concept:** When choosing between assets/projects with **different useful lives**, convert each to an equal annual cost. **Select the asset with the lowest EAC.**

**Pitfalls / exam tips:**
- EAC works because it neutralises unequal lives — never compare raw NPVs/PVs of different-life assets directly.

---

### Optimum Replacement Cycle

**Concept:** When an asset is replaced continuously (project repeats indefinitely), find the cycle length that minimises cost — as an asset ages, running costs rise and salvage falls.

**Steps:** Compute EAC for a 1-year cycle, 2-year cycle, 3-year cycle, … The **optimum replacement cycle is the one with the lowest EAC**.

---

### Real Options

**Concept:** Applies option-pricing (from the Derivatives chapter) to capital budgeting — capturing the **value of managerial flexibility** that static NPV ignores.

| Type | Nature | Model | Value captured |
|---|---|---|---|
| Timing option | Call | Single-period Binomial | Value of waiting to invest |
| Abandonment option | Put | Single-period Binomial | Value of exiting/selling the project |
| Growth option | Call | Black–Scholes (dividend-adjusted) | Value of a follow-on / intangible (e.g. patent) |

#### Timing Option (Call)

**Concept:** Decide whether to invest **now or wait** for a future date. Treated as a call; apply single-period Binomial. Inputs:

| Binomial input | Real-option meaning |
|---|---|
| Current price of underlying (S) | PV of cash inflows from the project |
| Strike price (K) | Investment amount (cost of project) |
| Up price | PV of inflows on future date (higher) |
| Down price | PV of inflows on future date (lower) |
| T | Time till future investment date |

**Decision:** Compare NPV if accept now vs value of the timing option (NPV if wait); **choose the higher**.

#### Abandonment Option (Put)

**Concept:** Extra value from the right to **dispose of / abandon** the project at a future date. Treated as a **put**; single-period Binomial. Same inputs as above except **Strike price = Sale (abandonment) price of project**, and **T = time till disposal date**.

#### Growth Option (Call) — Black–Scholes (dividend-adjusted / Merton)

**Key formula:**
$$\text{Value of Growth Option} = \frac{S}{e^{D \cdot T}} \times N(d_1) - \frac{K}{e^{R \cdot T}} \times N(d_2)$$

$$d_1 = \frac{\ln\left(\dfrac{S}{K}\right) + \left(R - D + 0.5\,\sigma^2\right)T}{\sigma\sqrt{T}}$$

$$d_2 = d_1 - \sigma\sqrt{T}$$

| Symbol | Meaning |
|---|---|
| $S$ | Current price of underlying = PV of cash inflows from the project |
| $K$ | Strike price = investment amount (cost of development) |
| $R$ | Interest (risk-free) rate p.a. (continuous) |
| $T$ | Life of the intangible asset (years) |
| $D$ | Expected cost of delay $= \dfrac{1}{\text{Life of intangible asset in years}}$ (treated like a dividend yield) |
| $\sigma^2$ | Variance in PV of cash inflows from the project |
| $N(d)$ | Cumulative standard-normal probability |

**Concept:** Values intangibles (e.g. a patent) that may have insignificant standalone NPV but open future growth. The **cost of delay $D$ acts as a continuous dividend yield** (Merton adjustment) — income forgone by not exercising early.

**Pitfalls / exam tips:**
- $S$ and $K$ are both discounted with continuous factors ($e^{-DT}$ and $e^{-RT}$ respectively) — this is the **dividend-adjusted (Merton) Black–Scholes**, not the plain version.
- $D$ enters the $d_1$ drift term as $(R - D)$; a larger cost of delay lowers the option value.
- $\sigma$ is the volatility (SD) of the underlying's PV; the variance $\sigma^2$ is what's usually supplied.

---

### References

1. ICAI, *Advanced Financial Management (Paper 2, Final)* — Study Material, Module on Advanced Capital Budgeting Decisions (2025–26 syllabus, applicable May/Nov 2025).
2. CA Ajay Agarwal (AIR 1), *AFM Concept Book* (May 2026 edition) — chapter "Advanced Capital Budgeting Decisions" (primary source, OCR).
3. ACCA Global, *P4/AFM Technical Article: Modified Internal Rate of Return* — MIRR terminal-value formula. https://www.accaglobal.com/us/en/student/exam-support-resources/professional-exams-study-resources/p4/technical-articles/Modified-internal-rate-return.html
4. Wall Street Prep / Wikipedia, *Adjusted Present Value (APV)* — base NPV + PV of financing side-effects; interest tax shield = tax rate × debt × interest rate. https://en.wikipedia.org/wiki/Adjusted_present_value
5. A. Damodaran (NYU Stern), *Real Option Valuation* (Ch. 5) — dividend-adjusted Black–Scholes for growth/patent options; cost of delay as dividend yield. https://pages.stern.nyu.edu/~adamodar/pdfiles/DSV2/Ch5.pdf
6. Real Option Valuation Methods – Black–Scholes Models (Merton dividend adjustment; cost of delay interpretation). https://ideas.repec.org/a/wut/journl/v1y2005p85-95.html
7. Standard finance references on Certainty Equivalent vs Risk-Adjusted Discount Rate methods in capital budgeting. https://theintactone.com/2023/05/08/certainty-equivalent-approach-and-risk-adjusted-discount-rate-method/

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

## 05. Security Valuation

> **Where it fits:** Fundamental (financial-data-based) valuation of individual securities — equity shares, rights, bonds/fixed-income, convertibles and money-market instruments — so an investor can decide to buy, hold or sell by comparing **intrinsic value** with **current market price (CMP)**.

---

### Required Rate of Return (CAPM)

**Key formula:**

$$R_s = R_f + \beta_s\,(R_m - R_f)$$

**Concept:** The return an investor requires (a.k.a. expected return) to hold a security, given its systematic risk. It is the discount rate used in every valuation model below.

**Definitions:**

| Term | Meaning |
|------|---------|
| $R_s$ | Required / expected rate of return on the security |
| $R_f$ | Risk-free rate (T-Bills, G-Secs, Treasury bonds) |
| $R_m$ | Market rate of return (Sensex / Nifty index) |
| $\beta_s$ | Beta = systematic risk of the security |
| $R_m - R_f$ | Market risk premium |
| $\beta_s(R_m - R_f)$ | Security risk premium |

*Verified against ICAI CA Final AFM (Security Analysis & Valuation) and standard CAPM.*

---

### Equity — Dividend Discount Models (DDM)

**Key formulas:**

Constant-growth (Gordon Growth Model), perpetual dividend:

$$V_0 = \frac{D_1}{K_e - g}\qquad D_1 = D_0(1+g),\quad g = b \times ROE$$

Variable / multi-stage growth (n-stage DDM):

$$V_0 = \sum_{t=1}^{n}\frac{D_t}{(1+K_e)^t} \;+\; \frac{TV_n}{(1+K_e)^n},\qquad TV_n=\frac{D_{n+1}}{K_e-g}$$

Two-stage (finite holding period), share sold at end of year $n$:

$$V_0 = \sum_{t=1}^{n}\frac{D_t}{(1+K_e)^t} \;+\; \frac{P_n}{(1+K_e)^n}$$

Solving for $K_e$ (constant-growth case):

$$K_e = \frac{D_1}{P_0}\times 100 + g \qquad (P_0 = \text{current MPS})$$

**Concept:** Intrinsic value = PV of all future dividends (plus terminal value / sale price). Use constant-growth when $g$ is stable and $K_e > g$; use multi-stage when growth changes over an initial horizon.

**Pitfalls / exam tips:**
- If the question says "dividend **paid**/**pays**" or gives dividend in the income statement, treat the figure as $D_0$ and grow it; otherwise treat it as $D_1$.
- Gordon formula is valid **only** when $K_e > g$.
- For $K_e$ in any non-constant-growth case, solve by **trial & error + interpolation**: $LR + \dfrac{\text{Value at }LR - \text{Required Value}}{\text{Value at }LR - \text{Value at }HR}\times(HR-LR)$.

**Decision rule:**

| Condition | Verdict | Action |
|-----------|---------|--------|
| Intrinsic Value > CMP | Underpriced | Buy |
| Intrinsic Value < CMP | Overpriced | Sell |
| Intrinsic Value = CMP | Fairly priced | Buy / hold |

*Verified against ICAI CA Final AFM and standard Gordon/DDM references.*

---

### Equity — Earnings-Based Models

**Key formulas:**

Earnings growth model:

$$V_0 = \frac{EPS\,(1+g)}{ROE - g}$$

P/E multiple approach:

$$MPS = \text{P/E Ratio} \times EPS$$

Gordon's model (earnings form):

$$V_0 = \frac{EPS\,(1-b)}{K_e - br}\;\equiv\;\frac{D_1}{K_e - g}\qquad (b=\text{retention ratio},\; r=ROE,\; g=br)$$

Walter's model:

$$V_0 = \frac{D + (E-D)\dfrac{r}{K_e}}{K_e}$$

Yield-on-share (accounting) approach:

$$V_0 = \frac{\text{Actual Yield on Equity (\%)}}{\text{Expected Yield on Equity (\%)}}\times \text{Paid-up Value per Share}$$

**Definitions:**

| Term | Meaning |
|------|---------|
| $D$ | Dividend per share (DPS) |
| $E$ | Earnings per share (EPS) |
| $r$ | Return on investment / ROE |
| $b$ | Retention ratio; $(1-b)$ = payout ratio |
| $K_e$ | Cost of equity / required return |

**Concept:** Walter's model captures the interplay of $r$ vs $K_e$ (growth firm $r>K_e$ ⇒ retain; declining firm $r<K_e$ ⇒ distribute). Actual yield = Yield on equity ÷ Equity share capital × 100; Expected yield = normal return of comparable firms ± risk premium of our company.

*Verified against ICAI CA Final AFM, Walter's model references, and Gordon earnings model.*

---

### Valuation of Rights

**Key formulas:**

Theoretical ex-rights price (TERP / post-rights price):

$$P_{xr} = \frac{(N_o \times \text{Existing MPS}) + (N_r \times \text{Rights Issue Price})}{N_o + N_r}$$

Theoretical value of a right (per new share):

$$\text{Value of a Right} = P_{xr} - \text{Rights Issue Price}$$

Value of right per original share (fall in MPS after issue):

$$= \frac{\text{Value of a Right}}{\text{No. of original shares needed to buy 1 right share}}\;=\;\text{Existing MPS} - P_{xr}$$

**Definitions:** $N_o$ = existing (original) shares; $N_r$ = right shares issued.

**Concept:** A rights issue offers new shares to existing shareholders, usually below market price; the share price re-bases to TERP after issue.

**Pitfalls / exam tips — effect on shareholder wealth:**
- **Exercises** the right → no change in wealth (loss on old shares offset by gain on cheap new shares).
- **Sells** the right → no change in wealth (loss offset by sale proceeds of the right).
- **Ignores** (lapses) the right → **wealth declines** by the value of the rights foregone.

*Verified against ICAI CA Final AFM and TERP references (Wikipedia / accounting-simplified).*

---

### Bond Pricing (Intrinsic Value)

**Key formulas:**

Redeemable bond:

$$V_0 = \sum_{t=1}^{n}\frac{I_t}{(1+K_d)^t} + \frac{RV_n}{(1+K_d)^n}$$

Irredeemable (perpetual) bond:

$$V_0 = \frac{I}{K_d}$$

Zero-coupon bond (ZCB):

$$V_0 = \frac{FV}{(1+K_d)^n}$$

Non-flat term structure (spot rate $R_t$ for each year):

$$V_0 = \frac{I_1}{(1+R_1)^1} + \frac{I_2}{(1+R_2)^2} + \dots + \frac{I_n + RV_n}{(1+R_n)^n}$$

Semi-annual coupons: halve the coupon and discount rate, double the number of periods.

**Definitions:** $I$ = coupon (always on **face value**); $K_d$ = required return / yield on similar bond; $RV$ = redemption value; $n$ = years to maturity.

**Concept:** Intrinsic value = PV of all future cash flows discounted at the required return on a comparable bond.

**Pitfalls / exam tips:**
- If face value not given, assume **₹100**; if redemption terms silent, assume redeemable **at par**.
- Expected market price = Intrinsic value $V_0 \times$ Beta of bond (when a bond beta is given).
- Yield curve: **normal** = long-term yield > short-term (normal market); **inverted** = short-term yield > long-term (recession signal).

*Verified against ICAI CA Final AFM bond valuation.*

---

### Bond Yield (Current Yield, YTM, Realised Yield)

**Key formulas:**

Current yield (redeemable / irredeemable):

$$\text{Current Yield} = \frac{\text{Annual Interest}}{\text{CMP of Bond}}\times 100$$

YTM (redeemable) — rate that equates PV of all future cash flows to CMP; solve by trial & error + interpolation. For an irredeemable bond, Current Yield = YTM.

YTM of a ZCB:

$$YTM = \left(\frac{FV}{\text{CMP}}\right)^{\frac{1}{n}} - 1$$

Realised yield (all coupons + redemption assumed received together at maturity):

$$\text{Realised Yield} = \left(\frac{\text{Total payments received at maturity}}{\text{CMP of Bond}}\right)^{\frac{1}{n}} - 1$$

**Concept:** Current yield ignores redemption gain/loss; YTM is the true internal rate of return over the bond's life.

**Pitfalls / exam tips:**
- "Prevailing interest / yield on a similar bond" ⇒ compute **YTM**.
- Yield spread = YTM of our bond − yield of similar bond.
- ZCB example check: $(1000/900)^{1/3}-1 = 0.0357 = 3.57\%$ (the "0.6357" in the source scan is an OCR slip).

*Verified against ICAI CA Final AFM and CFA money-market/YTM references.*

---

### Bond Forward Rates (Term Structure Theory)

**Key formula:**

$$V_0 = \frac{CF_1}{(1+R_1)} + \frac{CF_2}{(1+R_1)(1+R_2)} + \frac{CF_3}{(1+R_1)(1+R_2)(1+R_3)} + \dots$$

**Concept:** Under an expectations/term-structure view, one-year rates roll over each year ($R_1$ then $R_2$ then $R_3$ …). Each year's cash flow is discounted by the **product** of the successive one-year forward rates. ($CF$ = coupon, plus redemption in the final year.)

**Pitfalls / exam tips:** The primary OCR's denominators were garbled — the correct pattern compounds each successive year's rate; note $R_2$ etc. here are the one-year rates applicable to that year, not spot rates.

*Verified against ICAI CA Final AFM term-structure treatment.*

---

### Bond Duration & Volatility

**Key formulas:**

Macaulay's duration:

$$D = \sum_{t=1}^{n} t \times w_t,\qquad w_t = \frac{PV\ of\ CF_t}{\sum PV\ of\ CF}\;=\;\frac{CF_t/(1+YTM)^t}{V_0}$$

Modified duration (volatility):

$$MD = \frac{D}{1 + YTM}\qquad (YTM \text{ in decimals})$$

Approximate price change from duration:

$$\%\Delta P = -\,MD \times \Delta YTM\ (\%);\qquad \Delta P\,(\text{₹}) = \text{CMP} \times \%\Delta P$$

**Concept:** Duration = weighted-average time (in years) to recover the investment; modified duration = % change in price per 1% change in yield. Lower duration ⇒ less interest-rate sensitivity (generally preferable).

**Pitfalls / exam tips:**
- Discount at **YTM** (not coupon rate) when computing PV weights; the sum of PVs equals the bond's market price.
- Price and yield move **inversely**: YTM ↑ ⇒ price ↓, and vice-versa.

*Verified against ICAI CA Final AFM and standard duration references.*

---

### Bond Convexity

**Key formulas:**

$$C = \frac{V_+ + V_- - 2V_0}{2 \times V_0 \times (\Delta y)^2}$$

$$\text{Convexity adjustment (\%)} = C \times (\Delta y)^2 \times 100$$

Total estimated price change:

$$\%\Delta P = \underbrace{(-MD \times \Delta y)}_{\text{duration effect}} \;+\; \underbrace{C\,(\Delta y)^2 \times 100}_{\text{convexity adj. (always +)}}$$

**Definitions:**

| Term | Meaning |
|------|---------|
| $V_0$ | Current price at initial YTM |
| $V_+$ | Price if YTM **rises** by $\Delta y$ |
| $V_-$ | Price if YTM **falls** by $\Delta y$ |
| $\Delta y$ | Change in YTM (decimals) |

**Concept:** Duration alone under-estimates true price change because the price-yield curve is convex. The convexity adjustment corrects it and is **always added** — whether yield rises (offsets part of the duration-implied fall) or falls (adds to the rise).

**Pitfalls / exam tips:** If YTM **decreases** → % change = volatility effect **+** convexity; if YTM **increases** → % change = (−) volatility effect **+** convexity. The convexity term itself is never subtracted.

*Verified against ICAI CA Final AFM and CFA (AnalystPrep / CFI) convexity references.*

---

### Bond Immunization

**Key relationship:**

$$\text{Duration of Bond Portfolio} = \text{Duration of Liability}$$

$$D_A w_A + D_B w_B + \dots = D_{\text{Liability}},\qquad \sum w_i = 1$$

Amount to invest in each bond:

$$= \big(\text{PV of liability discounted at bond's YTM}\big)\times w_i$$

**Concept:** To fund a future liability, invest in ≥ 2 bonds so the portfolio's weighted duration equals the liability's duration — this offsets **price risk** against **reinvestment risk**, locking in the target amount.

**Pitfalls / exam tips:** Durations drift with time and yield changes, so the portfolio must be periodically **re-weighted (churned)**.

*Verified against ICAI CA Final AFM bond immunization.*

---

### Bond Refunding

**Key formula:**

$$\text{Call Premium} = (\text{Call Price} - FV)\times \text{No. of old bonds}\;=\;FV_{\text{old}}\times \text{Call Premium \%}$$

**Concept:** When market rates fall, a company may issue new low-coupon bonds and call (refund) existing high-coupon bonds before maturity. Evaluate by **NPV**.

**Method (NPV of refunding):**
1. **Initial outflow:** Call premium (net of tax saving) + flotation cost of new bonds − tax saving on unamortised discount & flotation cost of old bonds + overlapping interest on old bond (net of tax).
2. **Annual cost of old bond:** After-tax interest − tax saving on old-bond discount & flotation amortisation.
3. **Annual cost of new bond:** After-tax interest − tax saving on new-bond discount & flotation amortisation.
4. **Annual saving** = (2) − (3); take PV over the new bond's life at the **after-tax cost of debt** (or after-tax new-bond rate if not given).
5. **NPV** = PV of annual savings − initial outflow.

**Decision:** NPV positive ⇒ refunding beneficial; negative ⇒ not beneficial.

*Verified against ICAI CA Final AFM bond refunding.*

---

### Convertible Bonds

**Key formulas:**

$$\text{Conversion Value} = \text{Conversion Ratio} \times \text{MPS}$$

$$\text{Conversion Premium (\%)} = \frac{\text{MP of Bond} - \text{Conversion Value}}{\text{Conversion Value}}\times 100$$

$$\text{Conversion Premium per Share} = \frac{\text{MP of Bond} - \text{Conversion Value}}{\text{Conversion Ratio}}$$

$$\text{Market Conversion Price} = \frac{\text{MP of Bond}}{\text{Conversion Ratio}} = \text{CMP of Share} + \text{Conversion Premium per Share}$$

$$\text{Favourable Income Differential per Share} = \frac{\text{Coupon Interest} - (\text{Conversion Ratio}\times DPS)}{\text{Conversion Ratio}}$$

$$\text{Premium Payback Period} = \frac{\text{Conversion Premium per Share}}{\text{Favourable Income Differential per Share}}$$

$$\%\ \text{Downside Risk} = \frac{\text{MP of Bond} - \text{Straight Value}}{\text{MP of Bond}}\times 100$$

$$\text{Premium over Straight Value} = \frac{\text{MP of Bond} - \text{Straight Value}}{\text{Straight Value}}\times 100$$

**Definitions:** Conversion ratio = shares received per bond on conversion; Straight value = PV of the bond's cash flows discounted at the yield on a comparable **non-convertible** bond.

**Concept:** A convertible bond gives the holder the option to convert into a fixed number of shares. Total conversion premium = MP of bond − conversion value.

**Pitfalls / exam tips:** Bondholders convert only when **conversion value > straight value**. Straight value acts as the price floor; downside risk measures how far the market price can fall to that floor.

*Verified against ICAI CA Final AFM convertible-bond analysis.*

---

### Money Market Instruments

**Key formulas** (use **360 or 365** days for $n$ in days, or 12 for months, as the question specifies):

Nominal interest / Bond-equivalent yield:

$$y = \frac{F - P}{P} \times \frac{12\ \text{or}\ 365}{n} \times 100$$

Price / investment amount from a given yield:

$$P = \frac{F}{1 + y \times \dfrac{n}{12\ \text{or}\ 365}}\qquad (y \text{ in decimals})$$

Discount yield:

$$\text{Discount Yield} = \frac{F - P}{F} \times \frac{12\ \text{or}\ 365}{n} \times 100$$

Effective annual return / interest:

$$EAR = \left(1 + y \times \frac{n}{12\ \text{or}\ 365}\right)^{\frac{12\ \text{or}\ 365}{n}} - 1$$

Cost of funds (commercial paper only):

$$\text{Cost of Funds} = \frac{(\text{Interest Expense} + \text{Issue Expense})}{(1 - T)} \times \frac{12\ \text{or}\ 365}{n} \times 100$$

**Definitions:** $F$ = face value; $P$ = issue price / investment amount / current price; $F-P$ = interest (income to investor, expense to issuer); $n$ = tenor (days or months); $T$ = tax rate. Examples: Commercial Paper (CP), Certificate of Deposit (CD), Treasury Bills.

**Concept:** Short-term (≤ 1 year) instruments issued at a discount, redeemed at face value. Bond-equivalent yield uses **price** as base; discount yield uses **face value** as base (so BEY > discount yield).

**Pitfalls / exam tips:**
- ⚠️ VERIFY — the day-count basis (**360 vs 365**) and the **cost-of-funds** placement of $(1-T)$ depend on the specific question's convention; the source book divides by $(1-T)$ to gross up the after-tax cost. Read the question's day-count instruction carefully.
- Net amount received by company (CP) = Issue price − issue expense − minimum bank balance to be maintained.

*Verified against ICAI CA Final AFM and CFA money-market yield references (AnalystPrep / analystnotes).*

---

### Repo (Repurchase Agreement)

**Key relationships:**

Start proceeds (first leg):

$$= (\text{No. of GOI bonds} \times \text{Dirty Price}) - \text{Initial Margin}$$

$$\text{Dirty Price} = \text{Clean Price} + \text{Accrued Interest}$$

$$\text{Accrued Interest} = FV_{\text{single bond}} \times \text{Coupon Rate} \times \frac{\text{Accrued days}}{360\ \text{or}\ 365}$$

Repayment at maturity (second leg):

$$= \text{Start Proceeds} + \Big(\text{Start Proceeds}\times \text{Repo Rate}\times \tfrac{\text{Repo days}}{360\ \text{or}\ 365}\Big)$$

**Concept:** A bank raises short-term funds by selling GOI bonds with an agreement to repurchase them later at a price that includes interest at the **repo rate**. Initial margin (haircut) protects the lender.

**Definitions:** No. of GOI bonds = Total face value ÷ face value of single bond (assume ₹100 if not given). Clean price = price when last coupon was paid.

*Verified against ICAI CA Final AFM / RBI repo mechanics.*

---

### Miscellaneous Applications

**Key relationships:**

External Fund Requirement (EFR):

$$EFR = \big[\text{(Total Assets} - \text{Payables \& Provisions)}\times \text{Sales Growth \%}\big] - \text{Retained Earnings (next year)}$$

Amount from each source = New target amount (per given ratio) − existing amount in balance sheet.

Effect of a new project / expansion on share price:

$$\text{Expected MPS} = \frac{\text{MV of existing shares} \pm NPV_{\text{project}} + \text{Equity raised} - \text{Flotation cost} + \text{Other benefits}}{\text{No. of existing} + \text{new shares}}$$

**Concept:**
- **Fund-raising decision:** choose debt vs equity so that MPS under the P/E multiple approach is **highest**.
- **EFR:** external funds needed when sales grow, after absorbing spontaneous financing and retained earnings.
- **Project effect:** re-price the share by adding project NPV and net equity inflow to existing market value, then divide by post-issue share count. "Other benefit" includes gains on early bond redemption (intrinsic value of bonds today − amount paid on early redemption incl. penalty).

*Verified against ICAI CA Final AFM.*

---

### References

1. ICAI CA Final AFM Study Material — Security Analysis & Valuation module (2025-26 syllabus).
2. AnalystPrep (CFA Level I, Fixed Income) — bond convexity, percentage price change using duration & convexity; money-market yields. https://analystprep.com
3. Corporate Finance Institute — Fixed Income Interest Rate Risk (convexity). https://corporatefinanceinstitute.com
4. Wikipedia / Accounting-Simplified / Finance Strategists — Theoretical Ex-Rights Price (TERP) and value of a right.
5. eFinanceManagement / Finance Strategists — Walter's model of share valuation.
6. analystnotes / Nasdaq — money-market yield measures (bank discount yield, bond-equivalent yield, effective annual yield).
7. Standard finance references — CAPM, Gordon Growth / Dividend Discount Models, Macaulay & modified duration, bond immunization.

## 06. Portfolio Management

> **Where it fits:** The core equity-portfolio chapter of AFM — how to measure a security's return & risk, combine securities into a portfolio (Markowitz), price risk (CAPM/Sharpe), split risk into systematic vs unsystematic, build optimum portfolios, evaluate performance, and rebalance. Foundation for Security Analysis, Mutual Funds and Derivatives.

---

### 1. Return & Risk of a Single Security

**Key formula(s):**

*Ex-post (past data):*
$$\text{Annual Return }(x)=\frac{D+P_1-P_0}{P_0}\times100$$
$$\bar{x}=\frac{\sum x}{N}\qquad \sigma^2=\frac{\sum(x-\bar{x})^2}{N}\qquad \sigma=\sqrt{\sigma^2}$$

*Ex-ante (future data with probability):*
$$\bar{x}=\sum Px\qquad \sigma^2=\sum P(x-\bar{x})^2\qquad \sigma=\sqrt{\sum P(x-\bar{x})^2}$$

**Concept:** $D$ = dividend/interest for the year, $P_1$ = closing price, $P_0$ = opening price/cost. $\sigma$ (standard deviation) here is the **total risk** of the security.

**Pitfalls / exam tips:**
- Use all data in **%** inside the formulas (return, variance, SD).
- Ex-post divides by $N$ (population form used by ICAI), **not** $N-1$.
- Variance & SD of a **risk-free security are always zero**.
- If annual returns (%) are given directly, skip Step 1.

---

### 2. Expected Return & Risk of a Portfolio

**Key formula(s):**

*Portfolio return (weighted average):*
$$ER_P=ER_A\,W_A+ER_B\,W_B+\dots+ER_n\,W_n$$

*Correlation & covariance:*
$$r_{AB}=\frac{Cov_{AB}}{\sigma_A\,\sigma_B}\qquad\Rightarrow\qquad Cov_{AB}=\sigma_A\,\sigma_B\,r_{AB}$$
$$Cov_{AB}=\frac{\sum(x-\bar{x})(y-\bar{y})}{N}\quad\text{(past)}\qquad Cov_{AB}=\sum P(x-\bar{x})(y-\bar{y})\quad\text{(future)}$$

*Correlation between two securities via market (if only security–market correlations given):*
$$r_{AB}=r_{AM}\times r_{BM}$$

*Portfolio variance — 2 securities:*
$$\sigma_P^2=W_A^2\sigma_A^2+W_B^2\sigma_B^2+2\,W_A W_B\,\sigma_A\sigma_B\,r_{AB}$$

*Portfolio variance — 3 securities:*
$$\sigma_P^2=W_A^2\sigma_A^2+W_B^2\sigma_B^2+W_C^2\sigma_C^2+2W_AW_B Cov_{AB}+2W_BW_C Cov_{BC}+2W_AW_C Cov_{AC}$$
$$\sigma_P=\sqrt{\sigma_P^2}$$

**Concept:** Portfolio risk is **not** the weighted average of security risks — diversification benefit depends on correlation. Lower/negative $r_{AB}$ ⇒ greater risk reduction.

**Pitfalls / exam tips:**
- Weights default to opening market value (No. of shares × opening price) unless given.
- The last term uses **either** $2W_AW_B\sigma_A\sigma_B r_{AB}$ **or** $2W_AW_B Cov_{AB}$ — never mix (they are the same thing since $Cov=\sigma_A\sigma_B r$).
- $Cov_{AA}$ (covariance of a security with itself) = **variance of that security**.
- $r$ ranges $-1$ to $+1$: $+1$ perfect positive, $-1$ perfect negative, $0$ independent.

**Definitions:**

| Term | Meaning |
|---|---|
| Covariance | Joint deviation of two securities' returns from their means |
| Correlation ($r$) | Standardised covariance; strength/direction of the relationship |

---

### 3. Minimum Variance (Minimum Risk) Portfolio

**Key formula(s):**

*2 securities — weight giving lowest portfolio risk:*
$$W_A=\frac{\sigma_B^2-Cov_{AB}}{\sigma_A^2+\sigma_B^2-2\,Cov_{AB}}\qquad W_B=1-W_A$$

*3 securities — Critical Line Equation:*
$$W_B=a+b\,W_A\qquad W_C=1-W_A-W_B$$

**Concept:** The weight combination that minimises $\sigma_P^2$. For 3 securities, form two critical-line equations from the investor's existing minimum-variance portfolios, solve for $a$ and $b$, then plug in the new $W_A$.

**Pitfalls / exam tips:**
- Denominator is variance sum **minus 2×covariance** — a very common sign slip.
- Take weights to **4 decimals**.

---

### 4. Markowitz Efficient Portfolio

**Key formula(s):**
$$CV=\frac{\sigma\ (\text{SD of security})}{ER\ (\text{Expected return})}\times100$$

**Concept:** An efficient portfolio gives the **highest return for a given risk** (or lowest risk for a given return). Two selection tools:
- **Efficient frontier method:** among same-return securities pick the lowest risk; among same-risk securities pick the highest return.
- **Coefficient of Variation (CV):** risk per unit of return — **select the security with the lower CV**.

**Pitfalls / exam tips:**
- CV compares risk–return trade-off across securities with **different** risk and return; efficient-frontier comparison only works when either risk or return matches.

---

### 5. Capital Asset Pricing Model (CAPM)

**Key formula(s):**

*Required return on a security:*
$$R_s=R_f+\beta_s\,(R_m-R_f)$$

*Required return on a portfolio:*
$$R_P=R_f+\beta_P\,(R_m-R_f)$$

*Beta of portfolio (weighted average):*
$$\beta_P=\beta_A W_A+\beta_B W_B+\dots+\beta_n W_n$$

*Risk-free rate from a T-bill (if not given):*
$$R_f=\frac{\text{Coupon on T-bill}}{\text{Market price of T-bill}}\times100$$

*Actual/realised portfolio return (balancing figure):*
$$R_P=\frac{\text{Closing MV}+\text{Dividend/Interest}-\text{Opening Cost}}{\text{Opening Cost}}\times100$$

**Concept:** Required return = risk-free rate + $\beta\times$ market risk premium. $(R_m-R_f)$ = market risk premium; $\beta(R_m-R_f)$ = security risk premium.

**Pitfalls / exam tips:**
- If two $R_f$ figures are given, use the **moderate approach** — average them.
- If $R_m$ & $R_f$ are unknown but two securities' required returns and betas are given, form **two CAPM equations and solve simultaneously**.
- If inflation premium is specified, add it into the CAPM result.
- **Valuation decision (CAPM vs MPT):**

| Comparison | Verdict | Action |
|---|---|---|
| Required (CAPM) > Expected (MPT) | Over-valued | Sell |
| Required (CAPM) < Expected (MPT) | Under-valued | Buy |
| Required (CAPM) = Expected (MPT) | Correctly valued | Hold/indifferent |

---

### 6. Beta

**Key formula(s):**

*Two-period data:*
$$\beta=\frac{\text{Change in security return}}{\text{Change in market return}}=\frac{R_{s1}-R_{s2}}{R_{m1}-R_{m2}}$$

*Multi-period data:*
$$\beta=\frac{Cov_{SM}}{\sigma_M^2}=r_{SM}\times\frac{\sigma_S}{\sigma_M}$$

*Asset (unlevered) vs Equity (levered) beta:*
$$\beta_A=\beta_E\cdot\frac{E}{E+D(1-T)}+\beta_D\cdot\frac{D(1-T)}{E+D(1-T)}$$

*Multi-business firm — asset beta:*
$$\beta_A=\beta_{A,\text{Business 1}}\times W_1+\beta_{A,\text{Business 2}}\times W_2+\dots$$

**Concept:** Beta = sensitivity of a security's return to market return (systematic risk relative to the market).

**Pitfalls / exam tips:**
- $\beta_{\text{market}}=1$; $\beta_{\text{risk-free}}=0$.
- $\beta>1$ more volatile than market; $\beta<1$ less; negative $\beta$ moves opposite to market.
- $\beta_E\ge\beta_A$ (equity holders bear business **and** financial risk); in a silent case assume $\beta_D=0$.
- **Unlisted-company beta:** take a listed proxy → find its equity beta → un-lever to asset beta using proxy's D/E → re-lever to the unlisted firm's equity beta using its own D/E (assuming same asset beta).
- Report beta to **3 decimals** unless told otherwise.

---

### 7. Portfolio Beta Management

**Key formula(s):**
$$W_R\ (\text{weight of risky position})=\frac{\text{Required }\beta_P}{\text{Existing }\beta_P}\times100\qquad W_{RF}=100\%-W_R$$
$$\text{Amount in/(borrowed from) risk-free}=\text{Existing MV of portfolio}\times W_{RF}$$

**Concept:** Adjust portfolio beta to market view — **reduce** beta if market expected to fall, **increase** if expected to rise.

**Pitfalls / exam tips:**
- **Method 1 (risk-free security):** invest in risk-free to *reduce* beta; *borrow* at risk-free (negative weight) to *increase* beta.
- **Method 2 (sell risky, buy risk-free):** reduces beta only; amount to sell of each company = (portfolio MV × $W_{RF}$) × weight of that security.
- **Method 3:** index/stock futures — covered in the Derivatives chapter.

---

### 8. Sharpe (Single) Index Model — Systematic & Unsystematic Risk

**Key formula(s):**

*Per security:*
$$\text{Systematic Risk}=\beta_s^2\times\sigma_M^2$$
$$\text{Total Risk (variance)}=\text{Systematic}+\text{Unsystematic}\ (\sigma_e^2)$$
$$\text{Unsystematic Risk}=\text{Variance (MPT)}-\text{Systematic Risk}$$

*Portfolio:*
$$\text{Systematic Risk}=\beta_P^2\times\sigma_M^2$$
$$\text{Unsystematic Risk}=W_A^2\,USR_A+W_B^2\,USR_B+\dots+W_n^2\,USR_n$$
$$\text{Total Portfolio Risk}=\beta_P^2\sigma_M^2+\sum W_i^2\,USR_i$$

*Coefficient of Determination:*
$$r_{SM}^2=(\text{correlation security–market})^2=\frac{\text{Systematic Risk}}{\text{Total Risk}}$$

**Concept:** Splits total risk into **systematic** (market-wide, measured by beta, cannot be diversified away) and **unsystematic** (firm-specific, diversifiable, a.k.a. residual/random error).

**Pitfalls / exam tips:**
- Systematic risk uses $\beta^2$ and $\sigma_M^2$ (variances) — square the beta.
- To bifurcate portfolio risk: Systematic $=\beta_P^2\sigma_M^2$; Unsystematic = (Portfolio variance per MPT) − Systematic.
- $r_{SM}^2$ = proportion of total risk that is systematic.

---

### 9. Market Lines

**Key formula(s):**

*Security Market Line (SML) = CAPM plotted against beta:*
$$R_s=R_f+\beta\,(R_m-R_f)$$

*Characteristic Line (security return vs market return):*
$$\bar{R_s}=\alpha+\beta R_m\qquad\Rightarrow\qquad \alpha=\bar{R_s}-\beta R_m$$

*Capital Market Line (CML) — efficient portfolios only:*
$$R_P=R_f+\frac{R_m-R_f}{\sigma_M}\times\sigma_P$$

**Concept:** SML relates required return to **systematic risk (beta)** for any security. Characteristic line regresses a security's return on the market's return — $\alpha$ is the market-independent portion of return. CML relates return to **total risk (SD)** for efficient portfolios only.

**Pitfalls / exam tips:**
- SML x-axis = $\beta$; CML x-axis = $\sigma$ (total risk). Do not confuse them.
- Positive $\alpha$ ⇒ security outperformed what the market alone explains.

---

### 10. Sharpe Optimum Portfolio (Cut-off Model)

**Key formula(s):**

*Step 1 — rank by excess-return-to-beta (Treynor ratio):*
$$\text{Treynor Ratio}=\frac{ER-R_f}{\beta}$$

*Cut-off value $C_i$ (cumulative from the top-ranked security down):*
$$C_i=\frac{\sigma_M^2\displaystyle\sum_{j=1}^{i}\frac{(R_j-R_f)\,\beta_j}{\sigma_{ej}^2}}{1+\sigma_M^2\displaystyle\sum_{j=1}^{i}\frac{\beta_j^2}{\sigma_{ej}^2}}$$

*$Z$ value and weights of selected securities:*
$$Z_i=\frac{\beta_i}{\sigma_{ei}^2}\left(\frac{ER_i-R_f}{\beta_i}-C^{*}\right)\qquad W_i=\frac{Z_i}{\sum Z}\times100$$

**Concept:** Builds the optimum portfolio. Rank securities by Treynor ratio (high→low), compute cumulative $C_i$; the **highest $C_i$ is the cut-off $C^{*}$**. Select every security whose Treynor ratio $\ge C^{*}$, then weight by $Z$.

**Pitfalls / exam tips:**
- $\sigma_{ei}^2$ = unsystematic risk (residual variance) of security $i$; $\sigma_M^2$ = market variance.
- The book's ranked table columns correspond to: $\dfrac{(ER-R_f)\beta}{\sigma_e^2}$, its cumulative, $\dfrac{\beta^2}{\sigma_e^2}$, its cumulative, then $C_i$.
- Select securities **above** the cut-off only; a security with Treynor ratio below $C^{*}$ is dropped even if its $C_i$ was computed.

---

### 11. Arbitrage Pricing Theory (APT)

**Key formula(s):**

*Security:*
$$ER=R_f+\beta_1 FRP_1+\beta_2 FRP_2+\dots+\beta_n FRP_n$$

*Portfolio:*
$$ER=R_f+\beta_{P1}FRP_1+\beta_{P2}FRP_2+\dots+\beta_{Pn}FRP_n$$

*Factor Risk Premium (surprise element):*
$$FRP=\text{Actual value (\%)}-\text{Expected value (\%)}$$

**Concept:** Multi-factor extension of CAPM — return driven by several systematic factors (market, inflation, GDP, interest rate, etc.), each with its own beta and risk premium. $\beta_{Pk}$ = weighted average of factor-$k$ betas across the portfolio.

**Pitfalls / exam tips:**
- FRP is the **surprise** (actual − expected), so it can be negative.
- Unlike CAPM, APT does not require a single market portfolio.

---

### 12. Portfolio Evaluation

**Key formula(s):**
$$\text{Sharpe Ratio}=\frac{ER-R_f}{\sigma}\qquad\text{(reward to variability)}$$
$$\text{Treynor Ratio}=\frac{ER-R_f}{\beta}\qquad\text{(reward to volatility)}$$
$$\text{Jensen's Alpha}=\underbrace{ER\ (\text{MPT})}_{\text{actual/expected}}-\underbrace{[R_f+\beta(R_m-R_f)]}_{\text{required, CAPM}}$$

**Concept:** Three risk-adjusted performance measures. **Highest ratio = Rank 1.**

**Pitfalls / exam tips:**
- Sharpe uses **total risk ($\sigma$)**; Treynor uses **systematic risk ($\beta$)**.
- Use Sharpe for a whole (undiversified) portfolio, Treynor when only market risk matters.
- Positive Jensen's alpha ⇒ outperformance vs CAPM.
- To benchmark against the market, compute Sharpe/Treynor with $R_m,\sigma_M,\beta_M(=1)$.

---

### 13. Portfolio Rebalancing

**Key formula(s):**

*Value of portfolio (Buy & Hold):*
$$V=\text{No. of shares/units initially bought}\times\text{Current price/NAV}$$

*CPPI:*
$$\text{Max Decline\%}=\frac{\text{Present Index}-\text{Expected Min Index}}{\text{Present Index}}\times100$$
$$\text{Floor Value}=\text{Total Investment}\times(1-\text{Max Decline\%})$$
$$\text{Investment in Equity}=(\text{Portfolio Value}-\text{Floor Value})\times\text{Multiplier};\quad\text{Bonds}=\text{balancing figure}$$

**Concept:** Split funds between equity (aggressive) and bonds (conservative) and rebalance as equity prices move.

**Definitions:**

| Policy | Rule |
|---|---|
| Buy & Hold (do nothing) | All in equity; no rebalancing |
| Constant Ratio Plan | Keep equity:bond at a fixed ratio; buy/sell equity to restore ratio after each price move |
| CPPI | Equity = Multiplier × (Portfolio Value − Floor); rest in bonds |

**Pitfalls / exam tips:**
- ⚠️ VERIFY — Floor Value: the OCR states "Total Investment − Expected Maximum Decline %." The correct computation is **Total Investment × (1 − Max Decline%)** (equivalently Total Investment − Total Investment×Decline%); use the multiplicative form.
- Constant Ratio: when equity price **rises**, sell equity; when it **falls**, buy equity (to restore the target ratio).
- CPPI: rising market ⇒ buy more equity (momentum); falling market ⇒ sell equity to protect the floor. Higher multiplier = more aggressive.

---

### 14. Stock Lending Scheme (SLS)

**Key formula(s):**

*Lender's total earnings:*
$$\text{(Lending fee per share}+\text{Dividend per share)}\times\text{No. of shares}$$

*Borrower's (short-seller's) profit/(loss) per share:*
$$\underbrace{(P_0-P_1)}_{\text{gain/(loss) on short}}-\text{Lending fee}-\underbrace{\left(\text{Share price}_{0}\times\text{BG cost\%}\times\frac{\text{months}}{12}\right)}_{\text{bank guarantee charge}}$$

**Concept:** A long-term investor (lender) lends shares; a short-seller (borrower) sells them now and buys back later to return them. Lender earns a fee plus dividends; borrower profits if the price falls.

**Definitions:**

| Term | Meaning |
|---|---|
| Long position | Buy first, sell later (bullish) |
| Short position | Sell first, buy later (bearish) |
| Bank guarantee cost | Borrower's charge for the guarantee given to the lender, pro-rated for the borrowing months |

---

### Points to Remember

- Use all data in **%** in the formulas.
- Weights to **4 decimals**; beta to **3 decimals** (unless stated).
- NIFTY = top 50 NSE companies; SENSEX = top 30 BSE companies.
- When own funds are combined with short-selling and risk-free borrowing, weights are computed on **own funds**: invested security weight = +Amount/Own funds; short-sold and borrowed positions carry **negative** weights.

---

### References

1. ICAI — CA Final *Advanced Financial Management* Study Material (2025–26), Chapter on Portfolio Management / Security Analysis. https://www.icai.org
2. Elton, Gruber, Brown & Goetzmann, *Modern Portfolio Theory and Investment Analysis* — Sharpe single-index cut-off ($C_i$), Treynor ratio, optimal portfolio construction.
3. Markowitz, H. (1952), *Portfolio Selection*, Journal of Finance — mean-variance framework, minimum-variance portfolio.
4. Sharpe, W. F. (1964), CAPM / single-index model; Treynor & Jensen performance measures.
5. Ross, S. (1976), *Arbitrage Pricing Theory* — multi-factor return model.
6. WallStreetPrep / Financial Edge — Security Market Line vs Capital Market Line (systematic vs total risk). https://www.wallstreetprep.com/knowledge/security-market-line-sml/
7. WallStreetMojo — two-asset minimum-variance portfolio weight formula. https://www.wallstreetmojo.com/minimum-variance-portfolio/
8. EconomicsDiscussion / theintactone — Sharpe's optimal portfolio cut-off rate ($C^{*}$) and excess-return-to-beta ranking. https://www.economicsdiscussion.net/portfolio-management/theories-portfolio-management/sharpe-theory-of-portfolio-management-financial-economics/29763

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

## 09. Derivatives Analysis & Valuation

> **Where it fits:** A derivative is a contract between two parties that derives its value from an underlying asset (equity/share/index, commodity, currency, interest rate, etc.). This chapter covers the valuation and hedging toolkit for equity forwards/futures, options (Binomial + Black-Scholes), equity swaps and commodity futures — the numerical core of the AFM derivatives paper.

---

### Participants & Classification (Concept)

| Participant | Existing exposure? | Objective |
|---|---|---|
| **Hedger** | Yes | Kill an existing risk by taking an offsetting position |
| **Speculator** | No | Earn profit by betting on price direction |
| **Arbitrageur** | No | Earn (near) risk-free profit from mispricing |

- **Classification by underlying:** Equity, Interest-Rate (IRRM), Currency (FOREX), Commodity, Other (credit, weather, electricity).
- **Contract types:** Forwards, Futures, Options, Swaps.
- **Forward vs Future:** economically identical *except* a forward is Over-The-Counter (OTC) while a future trades on a stock exchange (standardised, margined, daily settled). Both create an **obligation on both parties**.

---

### Pricing of Forwards & Futures — Cost of Carry Model

- **Key formula(s):** fair (theoretical) futures price under the three compounding conventions:

$$F = S \times (1 + R \cdot T) \qquad \text{(Simple interest)}$$

$$F = S \times e^{R T} \qquad \text{(Continuous compounding)}$$

$$F = S \times (1 + R)^{T} \qquad \text{(Discrete / periodic compounding)}$$

where $F$ = fair futures price, $S$ = current spot price/value of the underlying share or index, $R$ = interest rate p.a., $T$ = time in years (months/12 or days/365). For monthly compounding, $R$ = rate p.m. = (rate p.a. ÷ 12) and $T$ = number of months.

- **Dividend adjustments:**
  - **Fixed dividend amount** (dividend rate on face value): deduct the *present value* of the dividend from $S$ before applying the formula: $F = (S - PV_{\text{div}}) \times e^{RT}$.
  - **Dividend yield** $y$ (% p.a.): net it against the interest rate: $F = S \times e^{(R - y)T}$.

- **Concept:** The fair future price is today's spot "carried forward" by the net cost of holding the asset (financing cost minus any income earned). It is the no-arbitrage price.

- **Pitfalls / exam tips:**
  - Choose the compounding convention from the question wording: "compounded continuously" → $e^{RT}$; "interest p.m. / monthly rest" → monthly compounding; **otherwise default to simple interest**.
  - Deduct PV of *fixed* dividends from $S$; deduct dividend *yield* from $R$ — do not mix the two treatments.
  - The computed figure is only the *theoretical* price; the actual quoted (traded) price can differ (that gap drives arbitrage).

- **Definitions:**

| Term | Meaning |
|---|---|
| Basis | $\text{Basis} = S - F$ (spot minus future) |
| Backwardation | Basis positive ($S > F$); futures trade below spot |
| Contango | Basis negative ($S < F$); futures trade above spot |
| Convergence | Basis narrows to zero as maturity approaches |
| Lot / Contract size | No. of shares/units in one contract (contract multiplier) |
| Contract value | Price of 1 futures contract × No. of contracts |

---

### Pay-off (Gain / Loss) on Futures Contracts

- **Key formula(s):**

$$\text{Gain/Loss} = \text{No. of contracts} \times \text{Lot size} \times (\,F_{\text{settlement}} - F_{\text{contracted}}\,)$$

$$\text{Gain/Loss} = \text{Contract value} \times \%\ \text{rise/fall in futures price}$$

- **Concept:** Squaring off on maturity (cash settlement).
  - **Long position (buy):** gain if price rises, loss if it falls.
  - **Short position (sell):** gain if price falls, loss if it rises.

- **Pitfalls / exam tips:** For a short position, reverse the sign of the difference — a settlement price *below* the contracted price is a gain.

---

### Margins in Futures Contracts

- **Key formula(s):**

$$\text{Initial Margin} = \text{Contract value} \times \text{Initial-margin \%} \quad\text{OR}\quad \mu + 3\sigma$$

$$\text{Maintenance Margin} = \text{Initial Margin} \times \text{Maintenance \%} \;\;(\text{or Contract value} \times \text{Maint. \%})$$

$$\text{Mark-to-Market (daily)} = \text{No. of contracts} \times \text{Lot size} \times (F_{\text{today}} - F_{\text{previous day}})$$

where in the SD-based initial margin, $\mu$ = average daily absolute change in contract value and $\sigma$ = standard deviation of that daily change.

- **Concept:** *Initial margin* is deposited to open a position; *MTM margin* credits/debits daily gains and losses to the margin account; when the balance falls below the *maintenance margin*, a **margin call** tops it back up to the initial-margin level.

- **Pitfalls / exam tips:**
  - Margin-account statement columns: Opening balance → ± MTM → balance → + call money (only when balance < maintenance) → closing balance.
  - Call money restores the account to the **initial margin**, not merely to the maintenance level.
  - Total of the MTM column over the period = overall gain/loss (a useful cross-check).

---

### Hedging Using Futures

- **Key formula(s):** number of index-futures contracts to adjust portfolio beta:

$$N = \frac{V_P \times (\beta_{\text{existing}} - \beta_{\text{required}})}{\text{Price of 1 futures contract}}$$

Rise/fall % in the market (index) when only the portfolio move is given:

$$\%\ \Delta\text{Index} = \frac{\%\ \Delta\text{Portfolio}}{\beta_{\text{existing}}}$$

Portfolio beta on maturity after hedging:

$$\beta_{\text{total portfolio}} = \frac{\%\ \Delta\text{Total portfolio}}{\%\ \Delta\text{Index}}, \qquad \%\ \Delta\text{Total portfolio} = \frac{\text{Overall Gain/(Loss)}}{\text{Value of total portfolio at beginning}} \times 100$$

- **Concept:**
  - *Respective share futures:* long shares → sell (short) that share's futures; short shares → buy futures.
  - *Index futures:* used to hedge a portfolio (or a stock with no single-stock future). Long portfolio → short index futures; short portfolio → long index futures.
  - To **reduce** beta, sell futures; to **increase** beta, buy futures. Full hedge means $\beta_{\text{required}} = 0$.

- **Pitfalls / exam tips:**
  - If required beta is not given, assume **zero** (complete hedge).
  - **Round the number of contracts UP** to the next whole number (e.g. 2.47 → 3).
  - Cash & bank balance is risk-free ($\beta = 0$): exclude it from the *hedging* value (Steps 1–3) but include it in *total portfolio value* when computing the final portfolio beta.
  - This assumes the index future's own beta ≈ 1.

---

### Arbitrage Using Futures

- **Key formula(s):**

$$\text{Gain}_{\text{Cash \& Carry}} = F_{\text{actual quoted}} - F_{\text{theoretical (fair)}} \quad (\text{future overvalued})$$

$$\text{Gain}_{\text{Reverse Cash \& Carry}} = F_{\text{theoretical (fair)}} - F_{\text{actual quoted}} \quad (\text{future undervalued})$$

- **Concept:**
  - **Future overvalued** (actual > fair): do **Cash & Carry** — borrow, buy the spot asset, **short** the future.
  - **Future undervalued** (actual < fair): do **Reverse Cash & Carry** — short the spot asset, invest proceeds, **buy** the future.

- **Pitfalls / exam tips:** The arbitrage gain per unit is simply the absolute mispricing; direction of the future position is always the *opposite* of the over/under-valuation.

---

### Options — Meaning & Pay-off

- **Key formula(s):** net pay-off to the **holder**:

$$\text{Call pay-off} = \max(S_T - X,\ 0); \qquad \text{Net gain} = \max(S_T - X,\ 0) - \text{Premium}$$

$$\text{Put pay-off} = \max(X - S_T,\ 0); \qquad \text{Net gain} = \max(X - S_T,\ 0) - \text{Premium}$$

Break-even prices:

$$\text{Call BEP} = X + \text{Premium}; \qquad \text{Put BEP} = X - \text{Premium}$$

where $S_T$ = spot at maturity, $X$ = strike/exercise price.

- **Concept:** An option gives the **buyer a right (choice)** and imposes an **obligation on the seller (writer)**, in exchange for the premium.

| | Call option | Put option |
|---|---|---|
| Buyer/holder | Right to **buy** at strike | Right to **sell** at strike |
| Seller/writer | Obligation to **sell** at strike | Obligation to **buy** at strike |
| Exercised when | $S_T > X$ | $S_T < X$ |

- **Pitfalls / exam tips:**
  - Pay-off (before premium) is *never negative* — floor it at zero. Only the *net* pay-off (after premium) can be negative.
  - **Holder:** loss limited to premium, gain (call) unlimited. **Writer:** gain limited to premium, loss potentially unlimited.
  - The seller's gain/loss is the exact mirror of the holder's.

- **Definitions (Moneyness):**

| Moneyness | On exercise |
|---|---|
| In-the-Money (ITM) | Profit |
| At-the-Money (ATM) | Neither profit nor loss |
| Out-of-the-Money (OTM) | Loss |

---

### Expected Value of Option at Maturity

- **Key formula:**

$$\text{Expected value at maturity} = \sum_{i=1}^{n} \text{Pay-off}_i \times P_i$$

- **Concept:** When the question gives several possible maturity prices with probabilities, weight each pay-off by its probability. Used when actual (not risk-neutral) probabilities are supplied.

---

### Value of Option at Beginning — Binomial Model

- **Key formula(s):** risk-neutral probability of an up-move:

$$p = \frac{e^{RT} - d}{u - d} \quad (\text{continuous}) \qquad\text{OR}\qquad p = \frac{(1 + R \cdot T) - d}{u - d} \quad (\text{simple}); \qquad (1-p) = \text{down prob.}$$

$$u = \frac{S_{\text{up}}}{S_0}, \qquad d = \frac{S_{\text{down}}}{S_0}, \qquad T = \frac{\text{months to (first) period end}}{12}$$

**Single-period** value of option today:

$$V_0 = \frac{\text{Pay-off}_{\text{up}} \times p + \text{Pay-off}_{\text{down}} \times (1-p)}{e^{RT}\ \text{OR}\ (1 + R \cdot T)}$$

**Two-period:** value each node of period 1 by discounting its two period-2 pay-offs, then discount the two period-1 node values back one more period:

$$V_0 = \frac{V_B \times p + V_C \times (1-p)}{e^{RT}\ \text{OR}\ (1 + R \cdot T)}$$

**Delta (riskless hedge / replicating portfolio):**

$$\Delta = \frac{\text{Pay-off}_{\text{up}} - \text{Pay-off}_{\text{down}}}{S_{\text{up}} - S_{\text{down}}}$$

**Expected rate of return on option** (using the *given* probabilities):

$$\text{Expected return} = \frac{\text{Expected value at maturity} - \text{Premium}}{\text{Premium (value at beginning)}}$$

- **Concept:** Two equivalent routes give the same premium — the **Risk-Neutral approach** (discount probability-weighted pay-offs, holder's view) and the **Delta-Hedging / Replicating-Portfolio approach** (seller's view). $\Delta$ = number of shares to buy per call written for a perfect hedge.

- **Pitfalls / exam tips:**
  - If the question gives *actual* up/down probabilities, **ignore them** and use risk-neutral $p$ for valuation (the given probabilities are only for the "expected return" workings).
  - Discount each period by its own length; in a two-period model, discount **twice**.
  - Assumption: return on the option equals the risk-free return; price moves either up or down (only two states per step).

---

### Value of Option at Beginning — Black-Scholes Model (BSM)

- **Key formula(s):**

$$C = S \cdot N(d_1) - \frac{X}{e^{RT}} \cdot N(d_2)$$

$$d_1 = \frac{\ln\!\left(\dfrac{S}{X}\right) + \left(R + \tfrac{1}{2}\sigma^2\right) T}{\sigma \sqrt{T}}, \qquad d_2 = d_1 - \sigma\sqrt{T}$$

Put value via **put-call parity**:

$$P = \frac{X}{e^{RT}} - S + C$$

where $S$ = current share price, $X$ = strike, $R$ = risk-free rate p.a. (decimal), $\sigma$ = SD of returns (decimal), $T$ = years to maturity. $N(d_1)$ = call delta (probability of price increase); $N(d_2)$ = risk-neutral probability the option is exercised.

- **Concept:** Used when the *volatility (SD/variance)* is given rather than discrete up/down prices. Prices European options in continuous time.

- **Pitfalls / exam tips:**
  - $N(d_1), N(d_2)$ read from the standard normal (cumulative) table; for a negative $d$, use $N(-d) = 1 - N(d)$.
  - Fixed dividend → deduct its PV from $S$; dividend yield $y$ → replace $R$ with $(R - y)$.
  - Use $R$ and $\sigma$ as decimals, and $\ln$ (natural log).
  - **Assumptions:** European options; no transaction costs; constant short-term interest rate; constant variance of return.

- **Definitions (Option Greeks):**

| Greek | Sensitivity of option value to… |
|---|---|
| Delta (Δ) | ₹1 change in price of underlying |
| Gamma (Γ) | ₹1 change in price of underlying → change in **Delta** |
| Theta (Θ) | 1-day change in time to expiry |
| Rho (ρ) | 1% change in risk-free interest rate |
| Vega | 1% change in volatility |

---

### Exotic Options (Theory)

| Type | Feature |
|---|---|
| Chooser | Decide later whether it is a call or a put |
| Compound / Split-fee | Option on an option (right to buy another option) |
| Barrier | Activates only if underlying hits a set level |
| Binary / Digital | Fixed pay-off if a specified event occurs, else nil |
| Asian | Pay-off based on *average* price over its life |
| Bermuda | Exercisable on certain dates before/at expiry |
| Basket | Value depends on a portfolio, not one underlying |
| Spread | Pay-off from the difference between two underlyings |
| Look-back | Strike chosen on the best min/max price over its life |

*Exotics are hybrids of American & European options, traded OTC.*

---

### Equity Swap

- **Key formula:** net payment for the fixed-rate receiver on a settlement date:

$$\text{Net received/(paid)} = \big(\text{Notional} \times \text{Fixed \%}\big) - \big(\text{Notional} \times \text{Equity return \%}\big)$$

- **Concept:** Two parties exchange, on a notional principal, the return on an equity (share portfolio) against a fixed rate. One leg pays equity return, the other pays fixed.

---

### Commodity Derivatives — Hedging with Commodity Futures

- **Key formula(s):** number of commodity-futures contracts:

$$N = \frac{\text{Total quantity of commodity} \times \text{Hedge ratio}}{\text{Futures contract size}}$$

Minimum-variance **hedge ratio**:

$$h = \rho_{sf} \times \frac{\sigma_s}{\sigma_f}$$

Net cash and effective price on maturity:

$$\text{Net cash} = (\text{Qty} \times \text{Actual spot}) \pm \text{Gain/(Loss) on futures}$$

$$\text{Effective price} = \frac{\text{Net cash received on maturity after hedging}}{\text{Total quantity of commodity}}$$

where $\rho_{sf}$ = correlation between changes in spot and futures prices, $\sigma_s$ / $\sigma_f$ = SD of change in spot / futures price.

- **Concept:** Long the physical commodity → **sell** commodity futures; short the commodity → **buy** futures. The effective price locks in the realised sale price regardless of the maturity spot.

- **Pitfalls / exam tips:**
  - If the hedge ratio is not given, assume **1**.
  - **Stock index futures vs single-stock futures** (advantages): more flexible, cost-efficient hedging, harder to manipulate, cash-settled, less regulatory complexity, and hedges a whole portfolio.
  - A commodity qualifies for derivatives trading only if it is durable, storable, of standard/gradable quality, freely traded, with volatile prices and sufficient supply-demand depth.

---

### References

1. ICAI CA Final — *Advanced Financial Management* Study Material (2025–26 syllabus), Chapter "Derivatives Analysis and Valuation" (forwards/futures pricing, options, Binomial & Black-Scholes valuation, commodity hedging).
2. CA Ajay Agarwal (AIR 1), *AFM Concept Book* (May 2026 edition), Derivatives Analysis and Valuation — primary source (concept + theory sections).
3. Cost-of-carry futures pricing with continuous compounding and dividend yield $F = S\,e^{(R-y)T}$ — Risk Hub / ThisMatter futures-pricing references (verified against ICAI treatment).
4. Black-Scholes-Merton formula ($d_1$, $d_2$, $N(d_1)$, $N(d_2)$) and put-call parity $C + Xe^{-RT} = P + S$ — Macroption; Columbia FoundationsFE (M. Haugh), *The Black-Scholes Model*.
5. One-period Binomial model risk-neutral probability $p = (e^{RT}-d)/(u-d)$ and delta/replicating-portfolio equivalence — CFA Institute refresher reading; QuantStart risk-neutral binomial pricing.
6. Minimum-variance hedge ratio $h = \rho\,\sigma_s/\sigma_f$ and index-futures beta-hedging $N = (\beta_T - \beta_P)\,V_P/V_F$ — Wolfram Formula Repository; AnalystPrep FRM "Hedging Strategies Using Futures".
7. SEBI (Stock Exchanges and Clearing Corporations) framework on futures margining (initial / mark-to-market / maintenance margin) — general regulatory reference for margin mechanics.

## 10. Foreign Exchange Exposure & Risk Management

> **Where it fits:** The forex chapter of CA Final AFM — how exchange rates are quoted, how forward/expected rates are derived from parity theories, and how importers/exporters/treasuries hedge currency risk (forward, money-market, futures, options), arbitrage, and manage bank positions.

---

### Exchange Rate Quotation — Base vs Price Currency

**Concept:** An exchange rate is the price of one currency in another. In `1 $ = ₹80`, the **base currency** ($) is the item being priced (always the *first*, quantity fixed at 1); the **price/quote currency** (₹) states its value.

- **Direct quote:** units of *home* currency per **1 unit of foreign** currency (e.g. India: `1 $ = ₹80`).
- **Indirect quote:** units of *foreign* currency per **1 unit of home** currency (e.g. India: `1 ₹ = 0.0125 $`).
- Direct quote is the **reciprocal** of the indirect quote and vice-versa.

$$\text{Direct Quote} = \frac{1}{\text{Indirect Quote}}$$

**Conversion rule:**

$$\text{If currency of amount} = \text{base currency of rate:}\quad \text{Home Amount} = \text{Amount} \times \text{Rate}$$
$$\text{If currency of amount} \ne \text{base currency of rate:}\quad \text{Amount} = \frac{\text{Amount}}{\text{Rate}}$$

**Pitfalls / exam tips:**
- If a quote is written oddly (e.g. `USD/₹ = 80`), read it by **value hierarchy** — GBP > USD > INR etc. — so it means `1 $ = ₹80` regardless of presentation.
- When only the last decimal digits differ in bid/ask (e.g. `80.3011 / 25`), the "25" repeats the leading digits → `80.3011 / 80.3025`.

---

### Bid Rate, Ask (Offer) Rate & Spread

**Concept:** Rates are quoted from the **dealer's** perspective on the **base currency**.

| Term | Meaning |
|---|---|
| **Bid rate** | Rate at which dealer **buys** base currency (lower rate) |
| **Offer/Ask rate** | Rate at which dealer **sells** base currency (higher rate) |
| **Spread** | Offer − Bid |

$$\text{Spread} = \text{Offer Rate} - \text{Bid Rate}$$

**Pitfalls / exam tips:**
- **Always solve from the customer's viewpoint** (except forward-contract execution/cancellation questions, solved from dealer's view).
- Customer **buying** base currency → **higher (adverse) rate**; customer **selling** base currency → **lower (adverse) rate**. The dealer always keeps the favourable side.
- When one dealer approaches another in the inter-bank market, the first dealer is treated as the *customer*.

---

### Spot vs Forward Rate — Premium / Discount

**Concept:** Spot rate = delivery today; forward rate = delivery on a future date. The gap is **premium** (base currency dearer forward) or **discount** (cheaper forward).

$$\text{Forward Rate} = \text{Spot Rate} + \text{Premium} \quad\text{OR}\quad \text{Spot Rate} - \text{Discount}$$

**Pitfalls / exam tips:**
- **Premium** is quoted low→high (`3 / 3.50`); **Discount** is quoted high→low (`1 / 0.50`). Match them column-wise to bid/offer.
- If one currency is at a premium, the counter-currency is necessarily at a **discount**.
- **Swap points** are added to / subtracted from the **last decimal digits** of the spot rate.

---

### Merchant Rate (Inter-Bank Rate ± Exchange Margin)

**Concept:** The rate a dealer gives a customer = inter-bank rate adjusted for the dealer's exchange margin.

$$\text{Merchant Rate} = \text{Inter-Bank Rate} \pm \text{Exchange Margin}$$

- Dealer **buys** foreign ccy from customer (customer sells) → start from **low/bid** side, **deduct** margin.
- Dealer **sells** foreign ccy to customer (customer buys) → start from **high/offer** side, **add** margin.

**Broken-period forward (interpolation)** — when the exact tenor's premium isn't given:

$$\text{Premium for broken period} = \text{Prem}_{\text{lower}} + \frac{\text{Prem}_{\text{upper}} - \text{Prem}_{\text{lower}}}{\text{days in interval}} \times \text{extra days}$$

**Pitfalls / exam tips:**
- A **"contracted rate"** / "rate booked with customer" is the **final** rate — no further margin adjustment.
- With a **transit period**, take the premium/discount of the **lower or upper month whichever is beneficial to the dealer**.

---

### Annual Premium / Discount (%)

**Method I — Exchange-rate differential** (gives prem./disc. of the **base** currency):

$$\text{Annual Prem./Disc.}\ (\%) = \frac{\text{Forward Rate} - \text{Spot Rate}}{\text{Spot Rate}} \times 100 \times \frac{12}{n_{\text{months}}}$$

$$\left(\text{if } n \text{ in days: } \times \frac{365}{n_{\text{days}}}\right)$$

Positive → premium on base currency; negative → discount.

**Method II — Interest-rate (or inflation-rate) differential:**

$$\text{Annual Prem./Disc. (Base Ccy)} = \frac{R_O - R_B}{1 + R_B}$$

where $R_O$ = interest/inflation rate of **other (price)** currency, $R_B$ = that of the **base** currency (treat as base the currency whose prem./disc. you want).

**To get the forward rate from an annual %:**
$$\text{Prem./Disc. for period} = \frac{\text{Annual }\%}{365/12}\times n \;=\; \text{Annual }\%\times\frac{n_{\text{months}}}{12}$$

**Pitfalls / exam tips:**
- **Lower** interest/inflation currency is always at a **premium**; **higher** at a **discount**.
- To find prem./disc. of the *price* currency, first flip the quote to make it the base.
- Interest rates in problems are **annual** unless stated "p.m." — "6-month borrowing @ 10%" still means 10% **p.a.**
- If both bid and offer are given, compute prem./disc. **separately** for each.

---

### Interest Rate Parity (IRP) — Expected Spot / Forward Rate

**Concept:** Forward (or expected spot) rate is driven by the interest-rate differential; removes covered arbitrage.

$$\frac{f_t}{S} = \frac{1 + R_O \cdot t}{1 + R_B \cdot t}\quad(\text{tenor} < 1\text{ year})$$

$$\frac{f_t}{S} = \frac{(1 + R_O)^{t}}{(1 + R_B)^{t}}\quad(\text{tenor} > 1\text{ year})$$

| Symbol | Meaning |
|---|---|
| $f_t$ | Expected forward / spot rate |
| $S$ | Today's spot rate |
| $R_O$ | Interest rate of **other (price)** currency |
| $R_B$ | Interest rate of **base** currency |
| $t$ | Time = (days or months) ÷ (365 or 12) |

**Pitfalls / exam tips:** Keep the interest rate of the *price/quote* currency in the numerator so the ratio moves the rate in the right direction (higher-interest currency depreciates forward).

---

### Purchasing Power Parity (PPP)

**Concept:** Exchange rate adjusts to offset inflation differentials between the two countries.

$$\frac{f_t}{S} = \frac{1 + \text{Inf}_O}{1 + \text{Inf}_B}$$

($\text{Inf}_O$ = inflation of other/price currency; $\text{Inf}_B$ = inflation of base currency.)

---

### International Fisher Effect (IFE)

**Concept:** Combines IRP and PPP — the change in the exchange rate equals both the interest-rate differential and the inflation-rate differential.

$$\frac{f - S}{S} = \frac{R_O - R_B}{1 + R_B} = \frac{\text{Inf}_O - \text{Inf}_B}{1 + \text{Inf}_B}$$

$$\underbrace{\frac{f-S}{S}}_{\text{Exchange-rate diff.}} = \underbrace{\frac{R_O - R_B}{1+R_B}}_{\text{Interest-rate diff.}} = \underbrace{\frac{\text{Inf}_O-\text{Inf}_B}{1+\text{Inf}_B}}_{\text{Inflation-rate diff.}}$$

---

### Forward Contract Settlement (FEDAI: Execution, Cancellation, Extension)

**Concept:** A booked forward is honoured on the due date (exact execution) or defaulted (early / late / automatic). On default, the customer bears any loss and receives any gain — **except automatic cancellation, where loss is charged but gain is NOT passed on** to the customer.

**Components of profit/loss on default:**

| Component | Meaning |
|---|---|
| **Swap gain/loss** | Difference between two same-day, opposite-direction, different-tenor inter-bank deals by the dealer |
| **Exchange difference** (cancellation gain/loss) | Difference between the original customer deal and the reversing inter-bank deal; **exchange margin is loaded on the inter-bank reversing leg** (FEDAI rule) |
| **Interest** | Charged only on **early** delivery (early→due date) and **late** settlement (due→late date), on the net cash flow |
| **Flat charge** | Fixed fee, considered only if given |

**Automatic cancellation:** on the 3rd working day after maturity if the customer doesn't appear.

---

### Hedging Technique 1 — Forward Cover

**Concept:** Lock the settlement rate today via a forward contract.

- **Should we hedge?** Compare payment/receipt at **forward rate** vs at **expected spot rate** of settlement date.
- **Profit/Loss of hedging** = difference between amount at forward rate and amount at expected/actual spot rate on settlement.

---

### Hedging Technique 2 — Leading / Lagging

**Concept:** Advance (lead) or defer (lag) a foreign-currency payment to benefit from expected rate moves.

- **Leading (early pay):** Invoice − supplier's early-payment discount, converted at the **leading-date** rate; charge interest (opportunity cost of borrowing) from lead date to original due date.
- **Lagging (late pay):** Invoice + supplier's interest, converted at the **lagging-date** rate.

---

### Hedging Technique 3 — Money Market Cover

**Concept:** Offset a foreign-currency asset/liability by creating the opposite money-market position now.

**Foreign-currency liability (importer to pay):**
1. Deposit today in foreign currency the present value of the liability:
$$P = \frac{\text{FC Liability}}{1 + R_{fc}\cdot t}$$
2. Buy that FC at spot → home-currency amount borrowed = $P \times \text{Spot}$.
3. **Actual outflow** = home-currency borrowing repaid with interest at maturity.

**Foreign-currency asset (exporter to receive):**
1. Borrow today in foreign currency the PV of the receivable: $P = \dfrac{\text{FC Asset}}{1 + R_{fc}\cdot t}$.
2. Convert $P$ to home currency at spot and invest domestically.
3. **Actual inflow** = home-currency investment plus interest at maturity.

**Pitfalls / exam tips:** When two rates per country are given, the **lower rate = deposit/investment**, the **higher rate = borrowing/loan**.

---

### Hedging Technique 4 — Currency Futures

**Concept:** Exchange-traded standardized contracts. Importer (pay foreign ccy) → **buy** the foreign-ccy future; exporter → **sell**.

$$\text{No. of contracts} = \frac{\text{Total Exposure Amount}}{\text{Lot (Contract) Size}}$$

If exposure currency ≠ lot-size currency, convert the exposure using the selected **futures rate** first. Fractional contracts are **ignored** (residual left uncovered / forward-covered).

**Final amount = three effects:**
1. Actual buy/sell of exposure at **actual spot** on maturity.
2. **Interest cost on initial margin** = Margin × borrowing rate × period.
3. **Profit/loss on futures** = No. of lots × contract size × (sell rate − buy rate of future); convert to home ccy at maturity spot if lot is in home ccy.

$$\text{Initial Margin} = \text{Margin per contract} \times \text{No. of contracts (refunded at maturity)}$$

---

### Hedging Technique 5 — Currency Options

**Concept:** Right (not obligation) to transact at the strike. Importer paying foreign ccy → **buy Call** on foreign ccy; exporter → **buy Put**.

| | Call option | Put option |
|---|---|---|
| Buyer's right | Buy currency at strike | Sell currency at strike |
| Exercise when | Spot at maturity **>** strike | Spot at maturity **<** strike |

$$\text{No. of contracts} = \frac{\text{Total Exposure Amount}}{\text{Lot Size}}\quad(\text{fraction ignored} \to \text{forward-cover it})$$

**Final payment = four effects:**
1. **Premium** = No. of lots × lot size × premium (convert to home ccy at beginning spot if lot in home ccy).
2. **Interest on premium** = Premium × borrowing rate × option period.
3. **Covered amount** — if exercised, at **strike**; if not exercised, at **maturity spot**.
4. **Uncovered amount** — at forward rate.

**Pitfalls / exam tips:**
- If maturity spot is not given, **assume the option is exercised**.
- With a probability range of maturity prices, decide exercise/lapse **for each price** and take the expected payment.

---

### Arbitrage in Forex

**Concept:** Riskless profit from rate mismatches.

**(a) Geographical arbitrage:**
- *Two-point:* buy in the low-rate market, sell in the high-rate market.
- *Three-point (triangular):* cycle through 3 currencies/markets; if one direction gives a loss, the reverse direction gives the profit.

**(b) Covered interest arbitrage** — borrow in one currency, invest in another, cover with a forward:

$$\text{Interest Rate Differential} = R_A - R_B$$
$$\text{Exchange Rate Differential} = \frac{F - S}{S}\times 100 \times \frac{12}{n_{\text{months}}}$$

**Decision:** compare the two differentials.
- If **interest-rate** differential is higher → **borrow in the lower-interest** currency.
- If **exchange-rate** differential is higher → **borrow in the higher-interest** currency.

Then: convert at spot → deposit abroad → lock forward → at maturity withdraw + convert forward → repay borrowing. **Gain = inflow (forward-converted deposit) − outflow (borrowing repaid).**

---

### Cross Rates

**Concept:** Derive a rate between two currencies with no direct quote, by chain-linking through a common currency.

$$\frac{X}{Z} = \frac{X}{Y}\times\frac{Y}{Z}$$

**Steps:** (1) fix the base currency for which a quote is needed; (2) with two-way quotes, pick the applicable side by linking currencies (start from the one being sold); (3) form and solve the equation; (4) load exchange margin on the **final** cross rate.

---

### International Cash Management (Cash Pooling)

**Concept:** A multinational with surplus-cash subsidiaries decides between **acting independently** (each invests locally, convert at maturity forward rate) and **immediate cash pooling** (repatriate all to home currency now at spot, invest centrally). Compare maturity value in home currency and pick the higher.

---

### Where to Borrow / Where to Invest

**Borrow (rates + exchange rates given):** compare **maturity outflow in home currency** under home-ccy loan vs foreign-ccy loan.

**Borrow (only interest rates given):** compare **net cost %:**

$$\text{Net cost of FC loan}\ (\%) = \underbrace{\frac{\text{Interest rate required by foreign bank}}{1 - \text{Withholding Tax Rate}}}_{\text{grossed-up effective rate}} \;\pm\; \text{Prem./Disc. on foreign ccy}$$

(add premium / subtract discount on the foreign currency, from the interest-rate differential). Add any other charges (e.g. LC).

**Invest:** compare **maturity receipt in home currency** under home-ccy vs foreign-ccy investment.

---

### Exchange Position & Cash Position (Nostro / Vostro / Loro)

**Exchange position:** a statement of **all spot + forward** foreign-ccy purchases (inflows) and sales (outflows) for a period.

**Cash position (Nostro A/c):** the passbook of the bank's FC account held abroad — **credited** on spot **purchase** (inflow), **debited** on spot **sale** (outflow). Only **spot** entries appear (no forwards).

| Account | Meaning |
|---|---|
| **Nostro** | "Our account with you" — our FC account with a foreign bank |
| **Vostro** | "Your account with us" — a foreign bank's local-ccy account with us |
| **Loro** | "Their account with them" — a third bank's account referred to by another |

---

### Foreign Exchange Exposure — Types

| Exposure | Meaning |
|---|---|
| **Translation (Accounting)** | Gain/loss on translating foreign-ccy assets/liabilities in the financial statements |
| **Transaction** | Gain/loss on a foreign-ccy transaction entered today but settled later |
| **Operating / Economic** | Gain/loss from changed product demand caused by exchange-rate movements |

$$\text{Transaction Exposure P/L} = (\text{Net flow} \times \text{Spot-date rate}) - (\text{Net flow} \times \text{Settlement-date rate})$$

**Pitfalls / exam tips:** "Transaction **and** operating exposure" asks for the **combined** profit/loss = transaction P/L ± operating P/L (operating = P/L on the increased/decreased units at settlement-date rate).

---

### Currency Swap

**Concept:** Two parties exchange principal + interest in one currency for principal + interest in another, lowering each other's borrowing cost when each has a comparative advantage in a different currency.

**Steps:**
1. **Amount received at start** = Principal borrowed from lender − principal transferred to counterparty + principal received from counterparty.
2. **Interest cost** = interest received from counterparty − interest paid to own lender (= gain/loss, converted to the party's required currency) + interest paid to counterparty.
$$\text{Interest Cost}\ (\%) = \frac{\text{Interest Cost (amount)}}{\text{Amount received at beginning}} \times 100$$
3. **Opportunity gain (saving)** = interest cost % if the required loan were taken **directly** − interest cost % **with** the swap.

---

### References

1. ICAI CA Final AFM Study Material (2025–26 syllabus) — Module on *Foreign Exchange Exposure and Risk Management* (quotation, forward rates, hedging techniques, parity conditions).
2. FEDAI (Foreign Exchange Dealers' Association of India) rules — forward contract execution, cancellation (incl. automatic on 3rd day) and extension; exchange-margin treatment. fedai.org.in.
3. RBI — regulatory framework for authorised dealers and foreign-exchange transactions (FEMA).
4. CFA Institute / AnalystPrep — Covered Interest Rate Parity: $(1+i_D)/(1+i_F) = F/S$; forward premium/discount and interest differentials.
5. AnalystPrep / CFA Level II *International Parity Conditions* — Relative PPP and International Fisher Effect (nominal interest differential = expected inflation differential).
6. Taxmann, *Theories of Foreign Exchange Rate Movement and International Parity Conditions* — PPP, IRP and IFE linkage.

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

## 12. Interest Rate Risk Management

> **Where it fits:** Interest Rate Derivatives (FRA, futures, options, swaps) used to hedge the risk that a change in market interest rates hurts a borrower or lender. The underlying asset in every instrument here is an **interest rate**.

### Types of Interest Rate & Interest Rate Risk

**Concept:** A loan carries either a **fixed rate** (same for the whole life, e.g. 8%/10%) or a **floating rate** that resets to a benchmark (MIBOR, LIBOR, BPLR) on each **Reset Date**. Floating is often quoted as `Benchmark + spread` (e.g. LIBOR + 3% ⇒ if LIBOR = 10%, rate = 13%). The spread is the fixed interest component.

**Definitions — Types of Interest Rate Risk (ICAI):**

| Type | Meaning |
|---|---|
| Net Interest Position Risk | Bank with more earning assets than paying liabilities sees Net Interest Income (NII) fall when market rates decline. |
| Price Risk | Assets sold before maturity realise a loss because bond prices and yields move inversely. |
| Reinvestment Risk | Uncertainty over the rate at which future cash flows can be reinvested. |
| Basis Risk | Rates on different assets/liabilities change by different magnitudes. |
| Yield Curve Risk | Movements/shifts in the yield curve across business cycles. |
| Embedded Option Risk | Rate changes trigger prepayment of loans or exercise of embedded options. |
| Gap / Mismatch Risk | Assets and liabilities of different amounts or maturities create exposure to rate changes. |

**Methods of hedging:** *Traditional* — Asset & Liability Management (ALM), Forward Rate Agreement (FRA). *Modern* — Interest Rate Futures (IRF), Interest Rate Options (IRO) / Interest Rate Guarantee (IRG), Interest Rate Swaps (IRS).

---

### Forward Rate Agreement (FRA)

**Concept:** A cash-settled contract with a bank that fixes the interest rate on a loan of a certain maturity starting after a specified period. A borrower fearing a **rise** in rates **buys** the FRA (upside bet); one expecting a **fall** **sells** the FRA (downside bet).

**Key formula — Final Settlement Amount:**

$$\text{Settlement Amount} = \frac{N \times (RR - FR) \times t}{1 + (RR \times t)}$$

where $N$ = notional principal, $RR$ = reference (actual) rate at settlement, $FR$ = contracted FRA rate, and $t = \dfrac{\text{No. of days (or months) of the FRA loan}}{365 \ (\text{or } 12)}$.

**Key formula — Theoretical (fair) FRA Rate** (rate that makes two short borrowings indifferent to one long borrowing — no-arbitrage forward rate):

$$\text{FRA Rate (for the 2nd period)} = \frac{1 + r_L \times \frac{T_L}{12}}{1 + r_S \times \frac{T_S}{12}} - 1 \quad \text{(simple-interest / months)}$$

$$\text{FRA Rate} = \frac{(1 + r_L)^{n_L}}{(1 + r_S)^{n_S}} - 1 \quad \text{(compounded / annual periods)}$$

where $r_L$ = rate for the full long period ($T_L$ / $n_L$) and $r_S$ = rate for the first short period ($T_S$ / $n_S$). Multiply the decimal result by 100 for %; annualise a part-period rate by $\times \frac{12}{\text{months}}$.

**Quotation:** "$a \times b$ FRA" = a loan starting after $a$ months, running to month $b$ (loan length = $b - a$). E.g. **6×9** = 3-month loan starting in 6 months; **3×9** = 6-month loan starting in 3 months. When two rates are quoted (e.g. 9%–10%), the **low** rate is the sell/downside side and the **high** rate is the buy/upside side.

**Settlement direction:**

| | Bought FRA (upside) | Sold FRA (downside) |
|---|---|---|
| RR > FR | Profit | Loss |
| RR < FR | Loss | Profit |

**Pitfalls / exam tips:**
- Do **not** forget the discount denominator $(1 + RR \times t)$ — settlement happens at the **start** of the loan period, so the interest differential is present-valued at the reference rate. Omitting it overstates the payoff.
- Use 12 for months / 365 for days consistently in both $t$ and the discount factor.

---

### Interest Rate Futures (IRF) — Zero-Coupon Bond underlying

**Concept:** Exchange-traded, cash-settled contract betting on the price of a zero-coupon bond on a future date.

**Key formula — Price of IRF:**

$$\text{IRF Price} = 100 - \text{Interest Rate on that date}$$

**Key formula — Number of contracts:**

$$\text{No. of Contracts} = \frac{\text{Loan Amount}}{\text{Futures Contract Size}} \times \frac{\text{Loan Duration (months)}}{\text{Futures Contract Period (months)}}$$

**Hedge direction:** A **borrower** fears rising rates (falling IRF price) ⇒ **sell** IRF. A **lender** fears falling rates (rising IRF price) ⇒ **buy** IRF.

**Net interest & locked rate:**

$$\text{Net Interest (Paid/Received)} = \text{Actual Interest on Loan} \pm \text{Gain/(Loss) on IRF Contracts}$$

$$\text{Net Interest Rate Locked} = \frac{\text{Net Interest Amount (Step 3)}}{\text{Loan Amount}} \times \frac{12}{\text{Loan Duration (months)}} \times 100$$

**Pitfall:** Gain/(Loss) on IRF = (change in IRF price) × contract size × no. of contracts, netted against actual loan interest — a proper hedge should leave the net rate close to the futures-implied rate.

---

### Interest Rate Futures (IRF) — Coupon-Bearing Bond underlying

**Concept:** Exchange-traded contract to buy/sell a **notional** coupon bond, settled by **physical delivery**. The short may deliver any bond from the exchange's deliverable basket, so he picks the **Cheapest-to-Deliver (CTD)** bond.

**Key formula — Profit on delivering each bond:**

$$\text{Profit/(Loss)} = \big(\text{Futures Settlement Price} \times \text{Conversion Factor}\big) - \text{Quoted (Purchase) Price of Bond on Maturity}$$

**Concept — CTD:** The first term is the **invoice price received** by the short; deduct the market price of buying that bond. Choose the bond giving **maximum profit** (i.e. cheapest to deliver). Conversion factors are set by the exchange and given in the question.

---

### Interest Rate Options (IRO)

**Interest Rate Guarantee (IRG):** A contract giving the **right** to take a loan at a **strike rate** after a specified period, for an upfront premium. Exercise if actual rate > strike (borrow at strike); else let it lapse and borrow at the lower actual rate.

$$\text{Total Interest Payable} = \text{Interest at the selected rate} + \text{IRG Premium}$$

**Cap Option (a Call on interest rates):** On each reset date, if the benchmark **exceeds** the strike, the buyer receives, on the next payment date:

$$\text{Cap Payoff} = \text{Loan} \times \max\!\big(\text{Benchmark Rate} - \text{Strike Rate},\ 0\big) \times \frac{\text{Days/Months from reset to payment}}{365 \ (\text{or } 12)}$$

**Floor Option (a Put on interest rates):** On each reset date, if the benchmark falls **below** the strike, the buyer receives:

$$\text{Floor Payoff} = \text{Loan} \times \max\!\big(\text{Strike Rate} - \text{Benchmark Rate},\ 0\big) \times \frac{\text{Days/Months from reset to payment}}{365 \ (\text{or } 12)}$$

**Premium & allocation:**

$$\text{Option Premium} = \text{Loan Amount} \times \text{Premium \%}$$

$$\text{Premium allocated per payment date} = \frac{\text{Premium paid at beginning}}{\text{PVAF @ fixed rate for all payment dates}}$$

**Definitions:**

| Term | Meaning |
|---|---|
| Cap | Buy protection against **rising** rates; payoff never negative (max with 0). |
| Floor | Buy protection against **falling** rates; payoff never negative. |
| Interest Rate Collar | **Buy a Cap + Sell a Floor** on a loan — receive Cap payoffs, pay Floor payoffs, lowering net premium. |
| Net hedged payoff | Payoff from option on a date **−** premium allocated to that date. |

**Pitfalls / exam tips:**
- A payoff can never be negative — a lapsed cap/floor pays **0**, not a loss.
- *Example:* ₹1 Cr loan at 6-month LIBOR for 2 yrs, Cap strike 8%, premium 1%, fixed rate 7% p.a. Premium = 1 Cr × 1% = **₹1,00,000**. There are 4 half-yearly dates; PVAF(3.5%, 4) = 3.673. Premium per date = 1,00,000 ÷ 3.673 ≈ **₹27,226**. *(Primary OCR shows "₹2.726" and "1/10" — both garbled; the correct figures are 1% premium and ≈₹27,226.)*

---

### Interest Rate Swaps (IRS)

**Concept:** Exchange of interest payments between two parties on a **notional** principal — one pays a fixed rate (fixed-rate payer), the other pays a floating rate (floating-rate payer). Principal is never exchanged.

**Plain Vanilla Swap (Generic / Coupon Swap)** — interest computed on a **360-day** basis:

$$\text{Fixed leg} = N \times AIC \times \frac{\text{No. of days till settlement}}{360} \quad (\text{30 days/month assumed})$$

$$\text{Floating leg} = N \times \text{Floating Rate} \times \frac{\text{Actual no. of days till settlement}}{360}$$

$$\text{Net Settlement} = \text{Fixed leg} - \text{Floating leg}$$

where $N$ = notional principal and $AIC$ = All-In-Cost (the fixed rate).

**Overnight Index Swap (OIS):** Same as plain vanilla, except the floating leg is **compounded daily**. (If the question says assume 365 days, use 365.)

**Swap to reduce cost of borrowing:**

$$\text{Net Gain} = \Big[\text{Sum of both parties' direct rates} - \text{Sum of both parties' swapped rates}\Big] - \text{Swap Commission}$$

If Net Gain > 0 a beneficial swap exists; the gain is shared between the parties as agreed. Each party's effective cost = its own required-loan rate **−** its share of the net gain.

**Definitions:**

| Term | Meaning |
|---|---|
| Notional Principal | Reference amount for computing interest; not exchanged. |
| AIC (All-In-Cost) | The fixed interest rate leg of the swap. |
| Comparative advantage | The rate differential across parties that makes the swap gain possible (exploited via the swap). |

**Pitfalls / exam tips:**
- Fixed leg uses **assumed 30 days/month (360)**; floating leg uses **actual days/360** — do not mix them up.
- A swap is only worthwhile if the **combined** interest bill falls after netting the bank's commission; the net gain (not the gross) is what the parties share.

---

### References

1. ICAI CA Final AFM Study Material (2025–26 syllabus) — *Interest Rate Risk Management* module (types of IRR, hedging methods FRA/IRF/IRO/IRS).
2. IOTA Finance — *Formula: Settlement amount for a Forward Rate Agreement (FRA)* (settlement = interest differential ÷ [1 + settlement rate × days/360]).
3. AnalystPrep (CFA) — *Interest Rate Forward Contracts* and *Pricing and Valuation of Forward Commitments* (no-arbitrage forward/FRA rate).
4. CME Group — *Calculating U.S. Treasury Futures Conversion Factors* and thismatter.com — *Interest Rate Futures* (price = 100 − rate; invoice price = futures price × conversion factor; cheapest-to-deliver).
5. NYU Stern (Prof. Carpenter) — *Caps, Floors, and Collars* and financetrain.com — *How Interest Rate Caps Work* (caplet/floorlet payoff = N × τ × max(R−K, 0) / max(K−R, 0)).
6. Wikipedia / RBI–FIMMDA market conventions — *Forward Rate Agreement* and OIS / plain-vanilla swap day-count (360-day, daily-compounded floating) conventions.

## 13. Business Valuation

> **Where it fits:** Determining the value of a business or its equity for M&A, sale of business, fund-raising and strategic decisions — using asset, income, cash-flow and relative (multiple) approaches, plus value-based metrics (EVA/MVA) and special cases (digital platforms, distressed firms, start-ups).

---

### Basics — Enterprise Value, Equity Value & bridge

- **Key formula(s):**

$$\text{Value of Firm (Enterprise Value)} = \text{Value of Equity} + \text{Value of Debt} - \text{Surplus funds (Cash \& Cash Equivalents)}$$

$$\text{Value of Equity} = \text{Value of Firm} - \text{Value of Debt} + \text{Surplus funds (Cash \& Cash Equivalents)}$$

$$\text{Value per Equity Share} = \frac{\text{Value of Equity}}{\text{No. of Equity Shares}}$$

- **Concept:** The firm/equity bridge lets you move between an enterprise-level number (FCFF, EBITDA multiple) and an equity-level number (FCFE, P/E). Surplus cash is non-operating, so it is stripped out of EV and added back to reach equity.
- **Pitfalls / exam tips:**
  - If there is **no debt and no surplus funds**, then Value of Firm = Value of Equity.
  - "Value of Debt" here means long-term/interest-bearing debt; keep surplus-cash treatment consistent with the method used.

---

### Cost of Capital (WACC)

- **Key formula(s):**

$$\text{WACC } (K_o) = K_e \times W_e + K_d \times W_d$$

$$K_e = R_f + \beta_e (R_m - R_f) \quad\text{(CAPM)}$$

$$K_d = \text{Interest rate on debt} \times (1 - t) \quad\text{(post-tax cost of debt)}$$

$$W_e = \frac{E}{E + D}, \qquad W_d = \frac{D}{E + D}$$

If long-term debt exists but $K_d$ is not given, WACC may be approximated using the **asset beta**:

$$\text{WACC } (K_o) = R_f + \beta_A (R_m - R_f)$$

- **Concept:** $K_o$ discounts firm-level cash flows (FCFF); $K_e$ discounts equity-level cash flows (FCFE, dividends). $E$ = equity share capital + reserves & surplus + intangibles not in books; $D$ = long-term debt (debentures, long-term loans/borrowings).
- **Pitfalls / exam tips:**
  - The asset-beta route and the $K_e W_e + K_d W_d$ route generally give **different** WACC values — do not treat them as interchangeable. Use the asset-beta form only when $K_d$ is genuinely unavailable.
  - Use **market weights** for $W_e, W_d$ when market values are supplied; book weights only if that is all the question gives.

---

### Market-Based Models

- **Key formula(s):**

$$\text{Value of Equity} = \text{MPS} \times \text{No. of Equity Shares} \quad\text{(Market Price Method)}$$

$$\text{Value of Equity (per share)} = \text{P/E Ratio} \times \text{EPS}$$

$$\text{Value of Equity (total)} = \text{P/E Ratio} \times \text{Earnings Available to Equity Shareholders (EAT for ESH)}$$

- **Concept:** Market Price Method uses the quoted price (only for listed firms). P/E Method capitalises earnings at a comparable/industry P/E multiple.
- **Pitfalls / exam tips:** Use a **normalised/sustainable** EPS and an appropriate comparable P/E; MPS-based value can be distorted by thin trading or market sentiment.

---

### Asset-Based Models

- **Key formula(s):**

$$\text{Net Asset Value (Book Value Method)} = \text{Equity Share Capital} + \text{Reserves \& Surplus} - \text{Contingent / Fictitious Assets \& liabilities (if any)}$$

$$\text{Net Realizable Value (Liquidation Method)} = \text{Net Assets at Book Value} + \text{Surplus on realisation} - \text{Shortfall on realisation}$$

- **Concept:** Book Value Method values equity at net assets per the balance sheet (adjusted for contingent liabilities and fictitious assets). Liquidation/Net Realizable Value restates assets at what they would actually fetch on sale — the **floor** value of a business.
- **Pitfalls / exam tips:**
  - Deduct preference capital and external liabilities to isolate equity holders' claim.
  - Liquidation value ignores going-concern/goodwill value, so it usually understates a healthy firm.

| Term | Meaning |
|---|---|
| Net Asset Value | Equity's book claim on net assets after adjustments |
| Liquidation Value | Realisable value of net assets on a forced/orderly sale |

---

### Income (Earning) Based Models

**(a) Dividend Growth (Gordon) Model**

- **Key formula(s):**

$$\text{Value of Equity} = \frac{D_1}{K_e - g}, \qquad D_1 = D_0(1 + g)$$

$$K_e = \frac{D_1}{\text{Current Market Price}} + g \quad\text{(implied cost of equity)}$$

- **Concept:** Values equity as the present value of a perpetually growing dividend stream. $g$ = expected growth (often post-merger growth); $K_e$ from CAPM (first priority) or the implied-yield formula (second priority).
- **Pitfalls / exam tips:**
  - Use **per-share** dividend → value per share; use **total** dividend → total equity value.
  - Requires $K_e > g$; not valid for high-growth start-ups where $g \ge K_e$.

**(b) Earnings Capitalisation Method**

- **Key formula(s):**

$$\text{Value of Business} = \frac{\text{Future Maintainable Profit (FMP)}}{\text{Capitalization Rate}}$$

$$\text{Per share} = \frac{\text{Value of Business}}{\text{No. of Equity Shares}}$$

- **Concept:** Capitalises a **sustainable** (future maintainable) profit at an appropriate rate. Capitalisation rate = specific rate given in question (1st priority) else WACC (2nd priority).
- **Definitions — Future Maintainable Profit build-up:**

| Particulars | Effect |
|---|---|
| Profit Before Tax (recent year) | xx |
| (−) Extraordinary income in above profit | (xx) |
| (+) Extraordinary loss in above profit | xx |
| (+) Profit from launch of new products | xx |
| (−) Taxes | (xx) |
| = Future Maintainable Profit | xx |

- **Pitfalls / exam tips:** Strip out one-off/extraordinary items so the capitalised profit is genuinely recurring.

---

### Cash-Flow Based Models

**(a) Free Cash Flow to Firm (FCFF)**

- **Key formula(s):**

$$\text{FCFF} = \text{EBIT}(1 - t) - \text{Net Capex} \pm \Delta \text{Working Capital}$$

where $\text{Net Capex} = \text{Capital Expenditure} - \text{Depreciation}$, and a **decrease** in WC is added, an **increase** is subtracted.

Discount by WACC ($K_o$):

$$\text{Value of Firm} = \frac{\text{FCFF}_1}{K_o - g} = \frac{\text{FCFF}_0(1 + g)}{K_o - g} \quad\text{(perpetual, constant growth)}$$

For variable growth: Value of Firm = PV of explicit-period FCFF discounted at $K_o$ **+** PV of terminal value.

- **Concept:** FCFF is cash available to **all** capital providers (debt + equity); discounting at WACC gives enterprise value. NOPAT = EBIT(1−t).

**(b) Free Cash Flow to Equity (FCFE)**

- **Key formula(s):**

$$\text{FCFE} = \text{PAT} - \text{Net Capex} \times (1 - \text{Debt Ratio}) \pm \Delta \text{Working Capital} \times (1 - \text{Debt Ratio})$$

Discount by cost of equity ($K_e$):

$$\text{Value of Equity} = \frac{\text{FCFE}_1}{K_e - g}, \qquad \text{FCFE}_1 = \text{FCFE}_0 (1 + g)$$

For variable growth: Value of Equity = PV of explicit-period FCFE at $K_e$ **+** PV of terminal value.

- **Concept:** FCFE is cash available to **equity** holders after debt servicing. The $(1 - \text{Debt Ratio})$ factor is the ICAI shortcut for the portion of capex / WC financed by equity (debt finances the rest), replacing an explicit net-borrowing figure.
- **Pitfalls / exam tips:**
  - Match the discount rate to the cash flow: **FCFF ↔ WACC**, **FCFE ↔ $K_e$**. Mismatching is the classic error.
  - If there is **no debt**: PAT = NOPAT and **FCFE = FCFF**.
  - **Incremental value of a new strategy** = Value of firm (FCFF, post-strategy) − Existing value of firm ($\dfrac{\text{Existing NOPAT}}{K_o}$).
  - Growth model needs $K_o > g$ (FCFF) / $K_e > g$ (FCFE).

---

### Relative Valuation Models

**(a) Sales (Revenue) Multiple**

$$\text{Sales Multiple} = \frac{\text{Enterprise Value}}{\text{Sales}} \;\Rightarrow\; \text{EV (ours)} = \text{Sales Multiple (comparable)} \times \text{Sales (ours)}$$

**(b) EBITDA Multiple**

$$\text{EBITDA Multiple} = \frac{\text{Enterprise Value}}{\text{EBITDA}} \;\Rightarrow\; \text{EV (ours)} = \text{EBITDA Multiple (comparable)} \times \text{Adjusted EBITDA (ours)}$$

Adjusted EBITDA = EBITDA (given) − extraordinary gains + extraordinary losses − expenses pending write-off + income pending recognition.

**(c) Comparable Companies Multiple (CCM)** — average of four value estimates:

$$\text{MV} = \frac{\text{MV}}{\text{BV}} \times \text{BV}; \quad \frac{\text{MV}}{\text{Replacement Cost}} \times \text{RC}; \quad \frac{\text{MV}}{\text{Sales}} \times \text{Sales}; \quad \frac{\text{MV}}{\text{Net Income}} \times \text{Net Income}$$

Value of Equity = average of the four Market Values (each ratio taken from the comparable, each base taken from our company). If ratios are given for two comparables, average each ratio across the two first.

**(d) Chop Shop / Break-up Value Approach** — for multi-segment firms:

$$\text{Capitalization to Sales} = \frac{\text{Capitalization}}{\text{Sales}}; \quad \frac{\text{Capitalization}}{\text{Assets}}; \quad \frac{\text{Capitalization}}{\text{Operating Income}}$$

For each segment: Capitalization (ours) = ratio (comparable) × base (ours) — computed on Sales, Assets and Operating Income. Value of firm = **average of the three** capitalisation figures (summed across segments).

- **Concept:** Relative valuation prices a business off observable multiples of comparable listed companies; Chop Shop sums the standalone value of each business segment.
- **Pitfalls / exam tips:** Always apply the **comparable's** multiple to **your** company's base; normalise EBITDA for one-off items before applying the multiple.

---

### Economic Value Added (EVA)

- **Key formula(s):**

$$\text{EVA} = \text{NOPAT} - (\text{Invested Capital} \times \text{WACC})$$

Equivalently, $\text{EVA} = (\text{ROIC} - \text{WACC}) \times \text{Invested Capital}$.

$$\text{EVA Dividend} = \frac{\text{EVA}}{\text{No. of Equity Shares}}$$

- **Concept:** EVA measures the surplus return earned **over** the minimum required return on capital (the capital charge). Positive EVA = value created. Concept was developed and trademarked by Stern Stewart & Co.
- **Definitions — Adjusted NOPAT & Invested Capital:**

| NOPAT build-up | Effect |
|---|---|
| EBIT | xx |
| (−) Tax on EBIT | (xx) |
| = NOPAT | xx |
| (+) Non-cash expenses (e.g. provision for bad debts) | xx |
| = Adjusted NOPAT | xx |

| Invested Capital — Liability approach | Invested Capital — Asset approach |
|---|---|
| Equity share capital + Reserves & Surplus + Long-term debt + Intangibles not in books + Non-cash adjustment done in NOPAT | Total Assets − Current Liabilities + Intangibles not in books + Non-cash adjustment done in NOPAT |

- **Pitfalls / exam tips:**
  - If EBIT is not given but PAT and financial leverage are: $\text{EBIT} = \dfrac{\text{Financial Leverage} \times \text{Interest Expense}}{\text{Financial Leverage} - 1}$, since $\text{FL} = \dfrac{\text{EBIT}}{\text{EBIT} - \text{Interest}}$. (Or: EBIT = PBT + Interest, where PBT = PAT ÷ (1 − t).)
  - Company with **higher EVA** is preferred for investment.
  - Keep NOPAT non-cash adjustments **consistent** on both sides (added to NOPAT and to Invested Capital).

---

### Market Value Added (MVA)

- **Key formula(s):**

$$\text{MVA} = \text{Market Value of Firm} - \text{Invested Capital}$$

$$\text{MVA} = \text{Market Value of Equity (MPS} \times \text{No. of shares)} - \text{Shareholders' Funds (Equity Capital + Reserves \& Surplus)}$$

$$\text{Value of Firm} = \text{MVA} + \text{Invested Capital}, \qquad \text{MVA} = \text{PV of all future EVA discounted at WACC}$$

- **Concept:** MVA is the cumulative wealth created for stakeholders since inception — the excess of market value over the capital invested. Theoretically, MVA = present value of all future EVAs.
- **Pitfalls / exam tips:** Match the base — if market value of the **firm** is given, subtract **invested capital**; if market value of **equity** is given, subtract **shareholders' funds**.

---

### Valuation of Digital Platforms

- **Concept:** A digital platform is software-based online infrastructure enabling interaction/transaction between users (e.g. Amazon, Uber, YouTube, Netflix, LinkedIn). Traditional earnings/asset methods fit poorly because value is driven by users, network effects and future scalability rather than current profits or tangible assets — so user-based and forward-looking cash-flow methods are used.
- **Pitfalls / exam tips:** Watch for negative current earnings; value often rests on network effects and user monetisation, not book assets.

---

### Valuation of Distressed Companies

- **Concept:** A distressed company cannot meet its financial obligations (debt service + operating expenses) and may head toward bankruptcy — but it is not necessarily worthless.
- **Key formula(s) / methods:**

**Modified DCF** — probability-weight the survival scenario:

$$\text{Expected Future Cash Flow} = \text{Cash Flow} \times (1 - \text{Probability of Distress})$$

**Cash-flow value + Distress-sale value:**

$$\text{Value} = \big[\text{Value per Cash-Flow Model}\big] \times (1 - \text{Prob. of Distress}) + \text{Distress Sale Value} \times \text{Prob. of Distress}$$

**Adjusted Present Value (APV):**

$$\text{APV} = \text{Value of firm without debt} \pm \text{Effect of Debt}$$
$$\text{Effect of Debt} = \text{PV of Tax Shield on Interest} - \text{Expected Bankruptcy Cost}$$
$$\text{Expected Bankruptcy Cost} = \big(\text{Value of firm without debt} - \text{Distress Sale Value}\big) \times \text{Probability of Distress}$$

- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — the OCR states the unlevered firm value is found by "discounting FCFF by $K_e$". In standard APV this discount rate is the **unlevered cost of equity** ($K_{eu}$, i.e. cost of equity of an all-equity/no-debt firm — often via asset beta), **not** the levered $K_e$. Use the unlevered cost of equity unless the question explicitly directs otherwise.
  - Relative valuation for distressed firms is applied the same way as for other companies.

---

### Valuation of Start-ups

- **Concept:** A start-up is an early-stage company created to deliver a unique product/service; little history and negative/volatile cash flows make conventional methods unreliable, so specialised methods are used.

| Method | Basis of value |
|---|---|
| **Cost to Duplicate** | Total costs/expenses of building the start-up and its product, incl. purchase of physical assets |
| **Berkus Approach** | Sum of estimated value of ~5 key success factors: basic (sound idea) value, technology/prototype, quality of execution/management, strategic relationships, and production & sales |
| **Comparable Transactions** | Value from a similar start-up (e.g. value per user × our users) |
| **Scorecard Valuation** | Value = valuation of similar start-up × Scorecard Multiplier % |
| **First Chicago** | DCF using probability-weighted (worst/normal/best scenario) expected cash flows |
| **Venture Capital** | PV of estimated exit value at investor's required rate of return |

- **Key formula(s):**

Comparable Transactions (per-unit) example:
$$\text{Value per user} = \frac{\text{Value of comparable}}{\text{Users of comparable}}; \quad \text{Value of target} = \text{Users of target} \times \text{Value per user}$$

Scorecard Multiplier = Σ (assigned quality % for comparison × weight of each quality). Typical weights: Strength of Team 0.30, Size of Opportunity 0.25, Product/Service 0.15, Competitive Environment 0.10, Marketing/Sales 0.10, Need for Additional Investment 0.05, Others 0.05.

First Chicago expected cash flow (per period):
$$\text{Expected CF}_t = \sum (\text{Scenario CF}_t \times \text{Probability of that scenario})_{\text{worst, normal, best}}$$

Venture Capital Method:
$$\text{Value today} = \frac{\text{Estimated exit value}}{(1 + \text{Investor's required return})^{n}}$$

- **Pitfalls / exam tips:**
  - The handwritten book labels the factor method the "Berkshire Approach"; the standard/textbook name is the **Berkus Approach** (Dave Berkus). Note it if the exam uses either wording.
  - Scorecard weights sum to 1.00 — verify before computing the multiplier.

---

### References

1. ICAI CA Final — *Advanced Financial Management (AFM)* Study Material, Chapter on Business Valuation (2025-26 syllabus, applicable May/Nov 2025).
2. CA Ajay Agarwal (AIR 1), *AFM Concept Book* (May 2026 edition) — source concept notes for this chapter.
3. Wall Street Prep — *Free Cash Flow to Firm (FCFF)* and *Free Cash Flow to Equity (FCFE)* — Formula + Calculator. https://www.wallstreetprep.com/knowledge/free-cash-flow-to-firm-fcff/ ; https://www.wallstreetprep.com/knowledge/free-cash-flow-to-equity-fcfe/
4. Corporate Finance Institute — *EVA – Economic Value Added* and *How to Calculate FCFE from Net Income*. https://corporatefinanceinstitute.com/learn/resources/valuation/eva-economic-value-added
5. Aswath Damodaran (NYU Stern) — *The Adjusted Present Value Approach* and *Distress in Discounted Cash Flow Valuation*. https://pages.stern.nyu.edu/~adamodar/New_Home_Page/valquestions/apv.htm ; https://pages.stern.nyu.edu/~adamodar/New_Home_Page/valquestions/distresspaper.htm
6. Standard CAPM / Gordon dividend-growth references for cost of equity and equity valuation (ICAI AFM & standard corporate finance texts).

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

## 15. Startup Finance

> **Where it fits:** A theory-only chapter of ICAI CA Final AFM. It covers what qualifies as a startup, how early-stage ventures raise money (bootstrapping → angels → venture capital), how they pitch investors, milestone jargon (Unicorn/Decacorn), and succession planning. **There are no computational formulas in this chapter** — marks come entirely from definitions, criteria and structured lists, so precision of wording matters more than any calculation.

---

### Startup India Initiative — Eligibility Criteria

**Concept:** DPIIT (Department for Promotion of Industry and Internal Trade) recognition lets an entity avail Startup India benefits (tax holiday u/s 80-IAC, self-certification, faster IP processing, etc.). An entity qualifies as a "startup" only if **all** conditions are met.

**Definitions / Criteria:**

| Condition | Requirement |
|---|---|
| Age of entity | Up to **10 years** from date of incorporation/registration |
| Legal form | **Private Limited Company** *or* **Registered Partnership Firm** *or* **Limited Liability Partnership (LLP)** |
| Turnover | Annual turnover has **not exceeded ₹100 crore** in any financial year since incorporation |
| Nature of work | Working towards **innovation, development or improvement** of products/services/processes, *or* a **scalable business model** with high potential for employment generation or wealth creation |
| Disqualifier | An entity formed by **splitting up or reconstruction** of an existing business is **NOT** a startup |

**Pitfalls / exam tips:**
- Write the ICAI figures: **10 years** and **₹100 crore**. (Some 2025-26 commercial/DPIIT notes quote ₹200 crore turnover and a 20-year/₹300-crore Deep-Tech carve-out — do **not** use these in an AFM answer; stick to the ICAI study-material numbers unless the question states otherwise.)
- The three eligible forms are only Pvt Ltd / Partnership / LLP — **sole proprietorship, HUF, trust and public limited companies do NOT qualify.**
- "Innovation OR scalable model" is an **either/or** — mention both limbs.

---

### Innovative Ways to Finance a Startup

**Concept:** Non-bank sources used because early ventures lack collateral/track record for conventional bank loans.

**Definitions:**

| Source | Meaning / Example |
|---|---|
| Personal financing | Founder's own savings |
| Personal credit lines | Credit cards, personal overdraft |
| Family and friends | Informal loans from close circle |
| Peer-to-peer (P2P) lending | A group of people lend to each other (via P2P platforms) |
| Crowdfunding | Small amounts from a **large number of individuals**, raised through social media / crowdfunding websites |
| Microloans | Small loans at lower interest to new ventures |
| Vendor financing | Manufacturers/distributors **defer payment terms** to the startup |
| Purchase-order (PO) financing | Financer advances funds to the **supplier** to complete a large new order |
| Factoring of receivables | Seller who sold on credit funds his **receivables** by selling them |

**Exam tip:** Distinguish P2P lending (many-to-many lending) from crowdfunding (many-to-one funding of one initiative) — examiners test the confusion.

---

### Pitch Presentation

**Concept:** A short, brief presentation (**not more than ~20 minutes**) to investors giving a quick overview of the business plan, to convince them to invest. Can be face-to-face or online.

**Definitions — elements to cover ("methods for approaching a pitch"):**

| Element | What to communicate |
|---|---|
| Introduction | Introduce the startup |
| Team | The people behind the scenes |
| Problem | The problem the promoter is solving |
| Solution | How the company plans to solve it |
| Marketing / Sales | Market size + growth and future-revenue forecast |
| Projections / Milestones | Projected income statement, cash-flow statement, balance sheet |
| Competition | How products/services differ from competitors |
| Business model | Purpose, process, target customers, infrastructure, sourcing, operations, policies |
| Financing | Money raised so far, who invested, and use of funds |

---

### Concept of Unicorn / Decacorn

**Concept:** Valuation-milestone jargon for privately held startups.

**Definitions:**

| Term | Meaning |
|---|---|
| **Unicorn** | A **privately held** startup whose valuation reaches **US$ 1 billion**; emphasises the rarity of such success. Common features: new ideas, innovation, consumer focus, high on technology |
| **Decacorn** | A company that has attained a valuation of **more than US$ 10 billion** |

**Exam tips / facts:**
- If a startup's valuation **slips below US$ 1 billion, it can LOSE** its unicorn status.
- **InMobi** (an ad-tech startup) was **India's first Unicorn**, after **SoftBank invested US$ 200 million** in it.

---

### Modes of Financing for Startups

Ordered roughly by stage: **Bootstrapping → Angel Investors → Venture Capital.**

#### (1) Bootstrapping

**Concept:** Founding and building a company from **personal finances** or from the **operating revenues** of the new company — no external capital.

**Definitions — methods of bootstrapping:**

| Method | How it conserves cash |
|---|---|
| Trade credit | Convince reluctant suppliers with a well-crafted financial plan to extend credit |
| Factoring | Sell accounts receivable to a commercial finance company to raise capital |
| Leasing | Take equipment on **lease** rather than buying, to reduce upfront cash outflow |

#### (2) Angel Investors

**Concept:** Wealthy individuals (often the entrepreneur's family/friends) who invest their **own money** in small startups — typically a **one-time** investment to propel the business through difficult early stages.

**Exam tips:**
- Angel investors bet on the **entrepreneur**, not primarily the viability of the business → they offer **more favourable terms** than other lenders.
- They are the **opposite of venture capitalists**: angels use **their own** money; VCs manage **pooled** money from many investors.
- Also called: informal investors, angel funders, private investors, seed investors, business angels.
- Though they *are* individuals, the funding entity may itself be a company, business, trust or investment fund.

#### (3) Venture Capital (VC) Fund

**Concept:** An investment vehicle that manages investors' funds to invest in startups with **exceptional growth potential**. VCs finance new/rapidly-growing firms, purchase **equity securities**, help develop products/services, and add value through **active participation**.

**Characteristics:**

| Characteristic | Detail |
|---|---|
| Long time horizon | Minimum ~**3 years**, maximum ~**10 years** |
| Lack of liquidity | Equity held by VC is illiquid |
| High risk | Principle of **high risk, high return** |
| Equity participation | VC invests in the form of **equity** |

**Advantages:** injects long-term equity finance; VC is a business partner sharing risk & reward; provides practical advice/assistance and a network of contacts; can provide additional rounds of funding; experienced in preparing the company for IPO; can facilitate a trade sale.

---

### Stages of Venture Capital Funding (Risk Matrix)

**Concept:** Risk and activity differ by stage; earlier stages = higher risk and longer fund lock-in.

| Stage | Funds locked (yrs) | Risk perception | Activity financed |
|---|---|---|---|
| Seed Money | 7–10 | Extreme | Supporting an idea; low level of financing |
| Start Up | 5–9 | Very high | Prototype operations / developing product & its marketing |
| First Round | 3–7 | High | Starting commercial production and marketing |
| Second Round | 3–5 | Sufficiently high | Working-capital growth (company not yet profitable) |
| Third Round | 1–3 | Medium | Market expansion & product development for a profit-making company — **Mezzanine financing** |
| Fourth Round | 1–3 | Low | Facilitating the public issue — **Bridge financing** |

**Exam tips:** Remember the two named rounds — **Third = Mezzanine**, **Fourth = Bridge**. Risk **falls** and lock-in **shortens** as you move down the table.

---

### Venture Capital Investment Process

**Definitions — the steps:**

| Step | What happens |
|---|---|
| Deal Origination | VC operates directly or via intermediaries (e.g., CAs); company submits a detailed business/financial/exit plan in an **Investment Memorandum (IM)** |
| Screening | Deal sent to senior-level people; shortlisted for further processing |
| Due Diligence | VC verifies veracity of documents, often using external bodies/consultants |
| Deal Structuring | Structured as a win-win; often a **convertible** structure so the promoter retains buy-back right. A **tag-along clause** forces the promoter to sell part of his stake alongside the VC to facilitate exit |
| Post-Investment Activity | VC nominates its **nominee to the Board** |
| Exit Plan | Spelt out at investment time. Two routes: **(i)** sell to third party (IPO / private placement to another VC); **(ii)** promoter gives a **buy-back commitment** at a pre-agreed rate (generally **IRR of 18%–25%**) |

**Exam tips:** Learn **two jargon terms**: **tag-along clause** (promoter must sell alongside VC) and **Investment Memorandum**. The buy-back IRR band is **18%–25%**.

---

### Structure of a Venture Capital Fund in India

**Concept:** Three fund structures exist — **one** for domestic funds and **two** for offshore funds.

| Structure | Meaning |
|---|---|
| **Domestic Funds** | (i) A domestic vehicle for pooling investor funds, and (ii) a separate investment adviser acting as asset manager. Pooling vehicle is typically a **trust** or a **company** |
| **Offshore — (i) Offshore structure** | Investment vehicle (LLC/LP organised **outside India**) invests directly into Indian companies; assets managed by an offshore manager |
| **Offshore — (ii) Unified structure** | Used when domestic investors also participate: overseas investors pool assets in an offshore vehicle that invests in a locally-managed **trust**, while domestic investors contribute directly to that trust |

---

### Why India is a Sustainable Environment for Startups

Quick list (theory 4–5 marker): **(i)** pool of talent, **(ii)** cost-effective workforce, **(iii)** increasing use of the internet, **(iv)** technology, **(v)** variety of funding options available.

---

### Succession Planning in Business

**Concept:** The process of identifying **critical positions** within an organisation and developing action plans for individuals to assume those positions — ensuring the right people are ready for the right jobs today and in future (not just at management/executive levels).

**Definitions:**

| Head | Points |
|---|---|
| **Need for succession planning** | Risk mitigation; cause removal; talent pipeline; conflict-resolution mechanism; aligning |
| **Business succession strategy (steps)** | 1. Evaluate key leadership positions → 2. Map competencies required → 3. Identify competencies of current workforce → 4. Bridge the leadership gap |
| **Challenges (esp. for startups)** | Founder mindset differs from corporate mindset; may be premature for a startup to implement; founder is the face of the startup, so succession is hard in his absence |

---

### References

1. ICAI, CA Final — *Advanced Financial Management (AFM)* Study Material, Chapter on **Startup Finance** (2025–26 / New Scheme syllabus). *Primary authority for all criteria, stages and definitions above.*
2. **Startup India** portal, Government of India — Startup Scheme & DPIIT recognition eligibility (10-year / ₹100-crore criteria): https://www.startupindia.gov.in/content/sih/en/startup-scheme.html
3. DPIIT Notification **G.S.R. 127(E)** (as amended) — definition of "startup", turnover and reconstruction conditions.
4. CA Ajay Agarwal (AIR 1), *AFM Concept Book* (May 2026 edition) — Startup Finance theory pages (source OCR).
5. Public reporting on **InMobi** as India's first unicorn and SoftBank's US$200 million investment (fact check): https://www.rkdewan.com/blogs/inmobi-indias-first-start-up-unicorn/

## ⚠️ Formulas to double-check


**01. Financial Policy & Corporate Strategy**
- Use **ROE on *beginning* equity** for the exact SGR $b\times ROE$; if ROE is computed on *ending* (average) equity, the textbook-exact form is $\text{SGR}=\dfrac{b\times ROE}{1-(b\times ROE)}$. State your assumption. ⚠️ VERIFY — ICAI problems almost always use the plain $b\times ROE$ (beginning-equity) version; adopt that unless the question specifies average equity.

**05. Security Valuation**
- ⚠️ VERIFY — the day-count basis (**360 vs 365**) and the **cost-of-funds** placement of $(1-T)$ depend on the specific question's convention; the source book divides by $(1-T)$ to gross up the after-tax cost. Read the question's day-count instruction carefully.

**06. Portfolio Management**
- ⚠️ VERIFY — Floor Value: the OCR states "Total Investment − Expected Maximum Decline %." The correct computation is **Total Investment × (1 − Max Decline%)** (equivalently Total Investment − Total Investment×Decline%); use the multiplicative form.

**08. Mutual Funds**
- ⚠️ VERIFY — **AMC minimum net worth:** the concept book states **₹100 crore**, but the operative SEBI figure under Reg. 21 is **₹50 crore** (raised from ₹10 cr in 2014, unchanged as of the 2025-26 syllabus). Write ₹50 crore unless the question quotes otherwise; flag the discrepancy if the book value is expected.

**11. International Financial Management**
- ⚠️ VERIFY — When instead the % change is quoted in terms of the **investor's home currency** (i.e. how the home currency moves against the security's currency), the OCR is garbled; the economically correct form is the reciprocal:

**13. Business Valuation**
- ⚠️ VERIFY — the OCR states the unlevered firm value is found by "discounting FCFF by $K_e$". In standard APV this discount rate is the **unlevered cost of equity** ($K_{eu}$, i.e. cost of equity of an all-equity/no-debt firm — often via asset beta), **not** the levered $K_e$. Use the unlevered cost of equity unless the question explicitly directs otherwise.
