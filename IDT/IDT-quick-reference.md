# IDT — CA Final Quick Reference

> Built from OCR'd concept notes (CA Surendra Mittal) and web-verified against CGST/IGST/Customs Act sources. Any ⚠️ VERIFY flag means double-check that item against the original notes.

## Contents

1. [00. Basics of GST (Constitutional Background & Introduction)](#00-basics-of-gst-constitutional-background-introduction)
2. [01. Supply under GST, Charge/Levy, Composition Levy, Reverse Charge & Exemptions](#01-supply-under-gst-chargelevy-composition-levy-reverse-charge-exemptions)
3. [02. Time of Supply](#02-time-of-supply)
4. [03. Value of Supply](#03-value-of-supply)
5. [04. Place of Supply](#04-place-of-supply)
6. [05. Import and Export under GST](#05-import-and-export-under-gst)
7. [06. Electronic Commerce Transactions and TCS](#06-electronic-commerce-transactions-and-tcs)
8. [07. Registration](#07-registration)
9. [08. Tax Invoice, Credit/Debit Notes, Accounts & Records and E-Way Bill](#08-tax-invoice-creditdebit-notes-accounts-records-and-e-way-bill)
10. [09. Payment of Tax, TDS/TCS, Returns & Refunds under GST](#09-payment-of-tax-tdstcs-returns-refunds-under-gst)
11. [10. Assessment, Audit, Inspection/Search/Seizure/Arrest, Demand & Recovery](#10-assessment-audit-inspectionsearchseizurearrest-demand-recovery)
12. [11. Appeals and Revision](#11-appeals-and-revision)
13. [12. Liability to Pay in Certain Cases, Advance Ruling & Miscellaneous Provisions](#12-liability-to-pay-in-certain-cases-advance-ruling-miscellaneous-provisions)
14. [13. Customs - Basics, Levy, Types of Duty & Exemptions (incl. Baggage & Stores)](#13-customs---basics-levy-types-of-duty-exemptions-incl-baggage-stores)
15. [14. Customs - Valuation, Importation & Exportation Procedures](#14-customs---valuation-importation-exportation-procedures)
16. [15. Customs - Warehousing, Classification of Goods & Refund](#15-customs---warehousing-classification-of-goods-refund)
17. [16. Foreign Trade Policy & Duty Drawback](#16-foreign-trade-policy-duty-drawback)

## 00. Basics of GST (Constitutional Background & Introduction)

> **Where it fits:** This chapter is largely outside the exam syllabus itself, but it lays the constitutional and conceptual foundation (why GST exists, which Articles empower it, how the GST Council works) that every later CGST/IGST chapter builds on.

### Direct vs Indirect Tax — the core distinction

- **Concept:** A **direct tax** is levied on and paid by the same person out of their own pocket (burden cannot be shifted) — e.g., Income Tax. An **indirect tax** is levied on supply of goods/services; the supplier collects it from the buyer and deposits it with the government, so the **incidence (burden) is shifted** to the ultimate consumer while the **liability to pay** remains on the supplier.
- **Illustration (as in the source book):** Mr. Ram buys a laptop priced ₹1,00,000. Supplier charges GST @18% = ₹18,000, so Mr. Ram pays ₹1,18,000. The supplier deposits the ₹18,000 GST to the Government — Mr. Ram bears the tax, but the supplier is legally liable to pay it over.
- **Pitfalls / exam tips:**
  - Do not confuse "person liable to pay" (supplier) with "person who bears the burden" (consumer) — this distinction is the classic MCQ trap.
  - GST is a **destination-based consumption tax** — revenue accrues to the State where goods/services are *consumed*, not where they are produced.

| Term | Meaning |
|---|---|
| Direct Tax | Levied on income/wealth of a person; burden cannot be shifted (e.g., Income-tax) |
| Indirect Tax | Levied on supply of goods/services; burden shifted to the consumer (e.g., GST, Customs Duty) |

### Need for GST / Cascading Effect

- **Concept:** In the pre-GST regime, goods suffered **Excise Duty** (at manufacture, Central) + **VAT/CST** (at sale, State), with no cross-credit between the two levies. Tax paid on tax (i.e., VAT charged on a value that already includes Excise Duty) caused a **cascading effect ("tax on tax")**, inflating the final price to the consumer.
- GST was introduced to:
  - Remove the cascading effect by allowing seamless **Input Tax Credit (ITC)** across the supply chain.
  - Subsume multiple indirect taxes into a single levy — "One Nation, One Tax."
  - Widen the tax base and reduce compliance burden from multiple registrations/returns under different laws.
- **Pitfalls / exam tips:** Remember the phrase "tax cascading" = tax levied on a value that itself includes an earlier tax component, because credit of the earlier tax was not allowed against the later tax.

### Constitutional Framework Enabling GST

- **Key rules:**
  - **Article 265:** No tax shall be levied or collected except by authority of law.
  - **Article 245:** Parliament may make laws for the whole/part of India; State Legislatures for the whole/part of the State — subject to the Constitution.
  - **Article 246 read with the Seventh Schedule:** Distributes law-making power via three lists — **Union List** (List I — e.g., Customs Duty), **State List** (List II — e.g., pre-GST State Excise on liquor, Stamp Duty), and **Concurrent List** (List III).
  - **Article 246A** *(inserted by the Constitution (101st Amendment) Act, 2016)*: Gives Parliament and every State Legislature **concurrent/simultaneous power** to make laws with respect to GST on intra-State supplies. Parliament alone has **exclusive power** to legislate on GST for **inter-State** supplies of goods and/or services.
  - **Article 269A:** IGST on inter-State supply (including imports) is **levied and collected by the Government of India** and apportioned between the Union and the States in the manner provided by Parliament by law, on GST Council's recommendation.
- **Concept:** The 101st Constitutional Amendment Act, 2016 carved out GST as a special concurrent field of taxation (via Art. 246A), overriding the earlier rigid Union List/State List split for the specific case of GST.
- **Pitfalls / exam tips:**
  - Do not mix up Article 245 (extent of laws) with Article 246 (subject-matter distribution) — both are quoted, and the OCR/source book conflates them; keep them distinct.
  - Article 246A is the *charging power* Article for CGST/SGST; Article 269A is specifically for IGST apportionment — a favourite one-line MCQ distinction.

| Article | Deals with |
|---|---|
| 265 | No tax without authority of law |
| 245 | Extent of laws made by Parliament/State Legislature |
| 246 / Seventh Schedule | Subject-matter distribution of legislative power (Union/State/Concurrent Lists) |
| 246A | Concurrent power of Centre & States to levy GST (inserted by 101st Amendment) |
| 269A | Levy & collection of IGST on inter-State supply; apportionment between Centre & States |
| 279A | Constitution of the GST Council |

### GST Council (Article 279A)

- **Concept:** To avoid disputes between the Centre and States on GST matters (rates, exemptions, thresholds, laws), the President is empowered by **Article 279A** to constitute the **GST Council** — a joint constitutional forum recommending GST policy to the Union and States.
- **Composition:**
  - **Chairperson:** Union Finance Minister.
  - **Member:** Union Minister of State in charge of Revenue/Finance.
  - **Members:** Minister in charge of Finance/Taxation (or any other Minister nominated by each State Government).
  - States collectively elect a **Vice-Chairperson** from among themselves.
- **Voting rule (Article 279A(9)):**
  - Quorum for a meeting: **one-half of the total number of members**.
  - Every decision is taken by a majority of **not less than three-fourths of the weighted votes** of members present and voting, where:
    $$\text{Weightage of Centre's vote} = \frac{1}{3} \text{ of total votes cast}$$
    $$\text{Weightage of all States' votes together} = \frac{2}{3} \text{ of total votes cast}$$
- **Functions:** Recommends the rates of GST, goods/services to be exempted, threshold limits, model GST laws, taxes/cesses to be subsumed, special provisions for special-category States, etc.
- **Pitfalls / exam tips:**
  - The 3/4 weighted majority with a 1/3 (Centre) : 2/3 (all States) split is the single most-tested numeric fact from this topic — memorize it precisely; do not swap the fractions.
  - GST Council recommendations are **not binding** in the sense of an ordinary statute — per Supreme Court (*Union of India v. Mohit Minerals*, 2022), they have persuasive value; Parliament/State Legislatures retain simultaneous legislative power under Art. 246A. ⚠️ VERIFY — this case-law point is well-established doctrine but was not present in the OCR source; include as a well-known SC ruling, cross-check against your update material if a newer ruling has refined it further for the 2026 attempt.

### Taxes Subsumed in GST / Structure of GST (CGST, SGST/UTGST, IGST, Compensation Cess)

- **Key rule — taxes subsumed:** GST subsumed **17 different Central and State taxes and 13 cesses** levied earlier on the supply of goods and services (Ministry of Finance / PIB, "One Nation, One Tax").
  - **Central taxes subsumed:** Central Excise Duty, Additional Excise Duties, Service Tax, Countervailing Duty (CVD) & Special CVD (on imports), Central Sales Tax (CST — collected by States but levied by Centre), central surcharges/cesses relating to supply of goods/services.
  - **State taxes subsumed:** State VAT/Sales Tax, Entry Tax/Octroi, Luxury Tax, Entertainment Tax (except that levied by local bodies), Taxes on lottery/betting/gambling, State surcharges/cesses relating to supply of goods/services.
- **Not subsumed / kept outside GST:**
  - Basic Customs Duty (levied under the Customs Act/Customs Tariff Act, continues separately).
  - Alcoholic liquor for human consumption — constitutionally outside GST altogether.
  - Five specified petroleum products — Petroleum Crude, High Speed Diesel, Motor Spirit (Petrol), Natural Gas, Aviation Turbine Fuel — kept out of GST for now (to be brought in from a date to be notified on GST Council's recommendation); currently continue to suffer central excise + State VAT.
- **Structure — dual GST model:**
  - **Intra-State supply:** **CGST** (Central GST, under CGST Act, 2017) + **SGST/UTGST** (State/Union Territory GST) levied concurrently on the same value.
  - **Inter-State supply (incl. imports):** **IGST** (Integrated GST, under IGST Act, 2017) levied by the Centre, later apportioned between Centre and the destination State (Art. 269A).
  - **GST Compensation Cess:** levied under the **GST (Compensation to States) Act, 2017** to compensate States for revenue loss for a transition period; charged over and above GST on notified luxury/sin goods (e.g., pan masala, tobacco, aerated drinks, motor vehicles, coal).
- **Concept:** GST is a value-added, destination-based, dual tax — one tax event but two/three components (CGST+SGST, or IGST) depending on whether supply is intra-State or inter-State.
- **Pitfalls / exam tips:**
  - "17 taxes + 13 cesses" is the number quoted by the Government — use it if asked for a count of taxes subsumed, but do not try to enumerate exactly 17 by rote; know the categories (Central vs State) instead.
  - CST is a **Central** levy (though collected/retained by the origin State) — students often wrongly classify it as a State tax.
  - Petroleum products and alcohol are commonly tested "exceptions" — remember: alcohol is permanently out; the 5 petroleum products are temporarily out (a mechanism exists to bring them in later).

| Levy | Governing Act | Levied by | On |
|---|---|---|---|
| CGST | CGST Act, 2017 | Centre | Intra-State supply |
| SGST/UTGST | Respective SGST Acts / UTGST Act, 2017 | State/UT | Intra-State supply |
| IGST | IGST Act, 2017 | Centre | Inter-State supply & imports |
| GST Compensation Cess | GST (Compensation to States) Act, 2017 | Centre | Notified luxury/sin goods, over & above GST |

### Framework / Sources of GST Law

- **Concept:** GST law in India is not a single Act — it is a body of statutes, delegated legislation, and interpretive material, applied in the following order of authority:
  1. **The GST Acts** — CGST Act, 2017; respective SGST Acts, 2017; UTGST Act, 2017; IGST Act, 2017; GST (Compensation to States) Act, 2017.
  2. **Rules** made under these Acts (CGST Rules, IGST Rules, etc.).
  3. **Notifications** issued by the Central/State Government (e.g., notifying rates, exemptions, effective dates).
  4. **Circulars and Orders** issued by the **Central Board of Indirect Taxes and Customs (CBIC)** — clarificatory, binding on the department, not on courts/assessees.
  5. **Judicial decisions/precedents** of the Supreme Court, High Courts, and Appellate Tribunals interpreting the above.
- **Pitfalls / exam tips:** CBIC (Central Board of Indirect Taxes and Customs) was renamed from **CBEC (Central Board of Excise & Customs)** in the run-up to GST's rollout — a favourite one-mark factual question.

| Term | Meaning |
|---|---|
| CGST Act, 2017 | Governs levy & collection of Central GST on intra-State supply |
| SGST Act, 2017 | Governs levy & collection of State GST (State-specific enactment) |
| UTGST Act, 2017 | Governs levy in Union Territories without a legislature |
| IGST Act, 2017 | Governs levy on inter-State supply and imports |
| GST (Compensation to States) Act, 2017 | Governs GST Compensation Cess on notified goods |
| CBIC | Apex body administering indirect taxes (successor to CBEC) |

### References

1. Constitution (One Hundred and First Amendment) Act, 2016 — insertion of Articles 246A, 269A, 279A (CBIC Taxinformation portal, taxinformation.cbic.gov.in).
2. Article 279A of the Constitution — GST Council composition, quorum, and weighted-voting rule (Drishti Judiciary / GST Council official site, gstcouncil.gov.in).
3. Ministry of Finance / Press Information Bureau — "GST subsumed over 17 taxes and 13 cesses of Central and States" (PIB/Ministry of Finance press communication).
4. CBIC — "About GST" overview of taxes subsumed and taxes kept outside GST (cbic-gst.gov.in).

## 01. Supply under GST, Charge/Levy, Composition Levy, Reverse Charge & Exemptions

> **Where it fits:** This is the foundation chapter of GST — before valuing, timing, or claiming credit on any transaction, you must first establish (a) that it is a "supply" under Section 7, (b) who is liable to pay tax on it (forward charge vs. reverse charge), (c) whether the supplier can instead pay a flat composition rate, and (d) whether the supply is exempt altogether. Every later IDT chapter (Value of Supply, Time of Supply, ITC, Registration, Returns) assumes this chapter's classification is already settled.

### Meaning & Scope of Supply — Section 7

- **Key formula(s)/rule(s):**
  - Section 7(1)(a): Supply **includes** all forms of supply of goods/services such as sale, transfer, barter, exchange, licence, rental, lease or disposal, made **or agreed to be made for a consideration** by a person **in the course or furtherance of business**.
  - Section 7(1)(aa) *(inserted retrospectively w.e.f. 1-7-2017 by Finance Act 2021)*: the activities of a club/association/society and its members are supply of goods/services to each other, notwithstanding mutuality of interest — this overturned the "principle of mutuality" argument used to escape GST.
  - Section 7(1)(b): Import of services for a consideration, whether or not in the course or furtherance of business, **is** a supply (this is the one exception to the "business test").
  - Section 7(1)(c): Activities specified in **Schedule I**, made or agreed to be made **without consideration**, are still treated as supply.
  - Section 7(1A) read with **Schedule II**: where an activity/transaction falls within the meaning of supply under 7(1), Schedule II merely classifies it as a supply of goods or a supply of services (it does not by itself create a supply).
  - Section 7(2) read with **Schedule III**: activities/transactions listed in Schedule III (and those notified by Government on recommendation of Council) are treated as **neither a supply of goods nor a supply of services** — i.e., outside GST altogether.

- **Concept:** "Supply" is the taxable event under GST. The four tests to apply, in order, are: (i) is it in Schedule III (then no GST, stop); (ii) is there consideration and a business nexus (or is it an import of service, or is it in Schedule I) — if none of these, no supply; (iii) use Schedule II only to label an already-existing supply as goods or services.

- **Pitfalls / exam tips:**
  - A transaction can be a "supply" even with **zero monetary consideration** only if it falls in Schedule I — do not assume "no money changed hands = no GST."
  - Donation/gift to a charitable body is **not** consideration only if (a) it is a gift/donation in the ordinary sense and (b) it has **no reciprocal identifiable service** attached to it (e.g., naming a hall after the donor with no advertisement obligation is fine; a donor plaque amounting to advertisement service can turn it into a taxable supply).
  - Schedule I applies **even without consideration** to: (1) permanent transfer/disposal of business assets on which ITC was availed; (2) supply between related persons/distinct persons in the course/furtherance of business (gifts by employer to employee up to ₹50,000 in a financial year are excluded); (3) supply of goods (only goods, not services) between principal and agent where the agent supplies/receives goods on behalf of the principal in his own name; (4) import of services by a taxable person from a related person or from any establishment outside India, in the course/furtherance of business.
  - Schedule III items commonly tested: services by employee to employer in the course of employment; services by court/tribunal; functions of MPs/MLAs; funeral/burial services; sale of land and sale of building (post-completion certificate); actionable claims other than lottery, betting and gambling; high-seas sale and sale of warehoused goods before clearance for home consumption (both notified as neither goods nor services w.e.f. 1-2-2019).

- **Definitions:**

| Term | Meaning |
|---|---|
| Consideration [Sec. 2(31)] | Payment made or the monetary value of any act/forbearance in respect of/in response to/for the inducement of a supply, whether by recipient or any other person, but **excludes** any subsidy given by CG/SG |
| Business [Sec. 2(17)] | Includes trade, commerce, manufacture, profession, vocation, adventure, wager, and any incidental/ancillary activity; also covers activities of clubs/associations to members and any activity by Government/local authority as a public authority |
| Related persons [Sec. 15 Expl.] | Officers/directors of one another's business; legally recognised partners; employer-employee; a person directly/indirectly owning 25%+ of shares/capital of both; one directly/indirectly controls the other; both directly/indirectly controlled by a third person; together they control a third person; members of the same family |
| Distinct persons [Sec. 25(4)/(5)] | Establishments of the same PAN person registered in different States/UTs, or same State but different registrations for business verticals — treated as separate/distinct persons for GST |

### Composite Supply and Mixed Supply — Section 8

- **Key formula(s)/rule(s):**
$$
\text{Composite Supply: rate of tax} = \text{rate of tax of the } \textbf{Principal Supply}
$$
$$
\text{Mixed Supply: rate of tax} = \text{highest rate of tax applicable to any item forming part of the mixed supply}
$$

- **Concept:** A **composite supply** [Sec. 2(30)] is two or more naturally bundled taxable supplies made in conjunction with each other in the ordinary course of business, one of which is a **principal supply** [Sec. 2(90)] (e.g., goods packed and transported with insurance). A **mixed supply** [Sec. 2(74)] is two or more individual supplies made together for a single price, where they are **not naturally bundled** and could be supplied separately (e.g., a gift hamper of chocolates, aerated drinks, and dry fruits).

- **Pitfalls / exam tips:**
  - Test for composite supply = "naturally bundled" + "supplied in conjunction in the ordinary course of business" — both conditions must be satisfied.
  - If any single test fails (goods can easily be sold separately without loss of business logic), classify as mixed supply and pick the **highest** rate among all items, not the principal item's rate.
  - Works contract [Sec. 2(119)] and supply of food/drink for consideration (restaurant, catering) are **deemed composite supplies of service** by a legal fiction under Schedule II, overriding the general composite-supply test.

### Charge / Levy of GST — Section 9 (CGST) & Section 5 (IGST)

- **Key formula(s)/rule(s):**
$$
\text{Intra-State Supply Tax} = \text{CGST (Sec. 9, CGST Act)} + \text{SGST/UTGST (State/UT GST Act)}
$$
$$
\text{Inter-State Supply Tax} = \text{IGST (Sec. 5, IGST Act)} \approx \text{CGST rate} + \text{SGST rate}
$$
$$
\text{Tax Payable} = \text{Applicable Rate (as per Sec. 9/5)} \times \text{Value of Supply (as per Section 15)}
$$
  - Levy under Section 9(1)/Section 5(1) is on **all intra-State/inter-State supplies of goods and/or services** except supply of alcoholic liquor for human consumption (permanently outside GST) and, currently, five petroleum products — petroleum crude, high-speed diesel, motor spirit (petrol), natural gas and aviation turbine fuel (outside GST until a date notified by the Council).
  - Rates are notified on the recommendation of the GST Council and cannot exceed the caps prescribed in the Acts (20% CGST/20% SGST i.e. effectively 40% combined cap; 40% IGST cap for inter-State/import — these are ceiling rates, not actual applied rates).

- **Concept:** Section 9/Section 5 are the actual **charging sections** — the legal trigger for tax liability. Supply (Sec. 7) tells you *whether* a transaction is taxable; Section 9/5 tells you *who* levies it and *at what point* liability attaches.

- **Pitfalls / exam tips:**
  - Do not confuse "supply" (Section 7 — the taxable event) with "levy" (Section 9/5 — the charge). A transaction can be a supply under Section 7 yet still be non-taxable/exempt if notified so under Section 11, or kept outside the levy (alcohol, specified petroleum products).
  - GST is a **destination-based** consumption tax — the place of supply (not the place of the supplier) generally decides which State gets SGST.

### Composition Levy — Section 10

- **Key formula(s)/rule(s):**

| Category of registered person | Combined rate (CGST + SGST/UTGST) | Levied on |
|---|---|---|
| Manufacturer (other than notified goods) — Sec. 10(1) | 1% (0.5% + 0.5%) | Turnover in State/UT |
| Trader/other supplier — Sec. 10(1) | 1% (0.5% + 0.5%) | **Taxable** turnover in State/UT |
| Restaurant/food-and-drink service (not serving alcohol) — Sec. 10(1) | 5% (2.5% + 2.5%) | Turnover in State/UT |
| Service providers/mixed suppliers not eligible under 10(1)/10(2) — Sec. 10(2A) | 6% (3% + 3%) | Turnover in State/UT |

$$
\text{Eligibility (Sec. 10(1)): Aggregate Turnover in preceding FY} \le \begin{cases}\text{₹1.5 crore (normal States)}\\ \text{₹75 lakh (8 Special Category States)}\end{cases}
$$
$$
\text{Eligibility (Sec. 10(2A)): Aggregate Turnover in preceding FY} \le \text{₹50 lakh}
$$

- **Concept:** Composition levy lets a small taxpayer pay tax at a flat, low percentage of turnover **instead of** the regular rate on each supply — in exchange, he **cannot collect tax from customers, cannot issue a tax invoice (only a "Bill of Supply"), and cannot claim input tax credit**.

- **Pitfalls / exam tips:**
  - "Turnover in State/UT" for the composition rate base **includes exempt supplies** and interest/discount on loans/deposits/advances — except for a trader, where the base is restricted to **taxable supplies of goods**. ⚠️ VERIFY — the OCR's phrasing on the trader carve-out was garbled; the settled position (Sec. 10(1) proviso, as clarified by CBIC) is that a trader pays 1% only on the value of **taxable supplies of goods**, while manufacturers/restaurant suppliers pay on total turnover in State including exempt supplies.
  - Persons **not eligible** to opt for composition (Sec. 10(2)): makes any inter-State outward supply; is a casual taxable person or non-resident taxable person; supplies goods/services through an e-commerce operator required to collect TCS u/s 52 (except selling goods, subject to the ECO not allowing inter-State supply and complying with TCS/return conditions); is a manufacturer of notified goods (ice cream and other edible ice, pan masala, tobacco/manufactured tobacco substitutes, and certain bricks — fly-ash bricks, building bricks, earthen/roofing tiles); supplies non-taxable goods.
  - Export and inter-State outward supplies (though barred) are still added to "aggregate turnover" **only** when checking the ₹1.5 crore/₹75 lakh eligibility limit for a **future** year, since the person could not have made such supplies while already under composition in the current year.
  - All registrations under the **same PAN** must opt in/out of composition together — you cannot run one GSTIN on composition and another on regular scheme for the same PAN.
  - A person can supply services (of any value) **incidental/ancillary** to his principal supply of goods up to the higher of ₹5 lakh or 10% of turnover in the preceding FY in the State/UT, without losing eligibility under Sec. 10(1) — this is the key relaxation that lets a composition trader also render minor services.

- **Definitions:**

| Term | Meaning |
|---|---|
| Aggregate Turnover [Sec. 2(6)] | All taxable supplies (excluding inward supplies on which RCM is paid) + exempt supplies + exports + inter-State supplies of a person having the same PAN, computed on **all-India** basis, excluding CGST/SGST/IGST/cess |
| Bill of Supply | Document a composition taxpayer issues instead of a tax invoice, since tax cannot be shown separately or collected from the recipient |

### Reverse Charge Mechanism (RCM) — Section 9(3), 9(4) & 9(5)

- **Key formula(s)/rule(s):**
$$
\text{Sec. 9(3)/5(3): Liability to pay GST shifts from Supplier} \to \text{Recipient, for specified goods/services notified by Government}
$$
$$
\text{Sec. 9(4): RCM applies where a \textbf{registered person} receives specified supplies from an \textbf{unregistered} supplier (currently restricted to notified promoters/real-estate context)}
$$
$$
\text{Sec. 9(5): E-Commerce Operator is deemed the supplier and pays tax, for notified services supplied through it}
$$
$$
\text{Promoter RCM trigger (Notification 07/2019-CT(Rate)): } \frac{\text{Value of inputs \& input services purchased from registered persons}}{\text{Total value of inputs \& input services}} < 80\% \Rightarrow \text{RCM on the shortfall}
$$

- **Concept:** Ordinarily the supplier pays GST (forward charge). Under RCM, the **recipient** is made statutorily liable — used where the supplier base is unorganised/hard to track (e.g., GTA, agriculturists) or to plug specific revenue leakage (import of services, e-commerce gig/platform services).

- **Pitfalls / exam tips:**
  - Notified goods under RCM [Sec. 9(3)] include: cashew nuts (not shelled/peeled), bidi wrapper leaves (tendu), tobacco leaves, raw cotton, silk yarn, supply of lottery, used vehicles/seized & confiscated goods/old & used goods/waste & scrap (by Government to any registered person), Priority Sector Lending Certificates (PSLC), and metal scrap (by an unregistered person to a registered person, effective 2024).
  - Notified services under RCM [Sec. 9(3)] commonly tested: Goods Transport Agency (GTA) services (to specified categories of recipients — factory, society, registered dealer, body corporate, partnership firm, casual taxable person, etc. — **unless** the GTA itself opts to pay under forward charge at 5% (no ITC) or 12% (with ITC)); legal services by an advocate/firm of advocates/arbitral tribunal to a business entity; services by an insurance agent to an insurance company; services by a recovery agent to a banking company/NBFC/financial institution; sponsorship services to a body corporate/partnership firm; services supplied by CG/SG/UT/local authority to a business entity (excluding renting of immovable property, and certain specified excluded services); services of a director to the company; transfer of development rights (TDR)/Floor Space Index (FSI) for construction; long-term lease of land by any person to a promoter; security services (supply of security personnel) by any person other than a body corporate, to a registered person (with specified exceptions).
  - **Legal services exemption threshold:** legal services by an individual advocate/senior advocate/firm of advocates are **exempt** (not taxable at all, so RCM never arises) when supplied to (a) another advocate/firm of advocates, (b) any person other than a business entity, or (c) a business entity with aggregate turnover up to the registration threshold (₹20 lakh, or ₹10 lakh in special category states) in the preceding FY.
  - **Section 9(4)** currently applies narrowly: a **promoter** receiving cement from an unregistered supplier must pay RCM on cement **regardless** of the 80% test; for all other inputs/input services, RCM applies only on the shortfall if registered-supplier procurement falls below 80% of total value of inputs and input services used in the project.
  - **Section 9(5)** ECO-pays-as-supplier categories: passenger transport by radio-taxi, motorcab, maxicab and motor-cycle; housekeeping services (plumbing, carpentry) supplied by unregistered persons; restaurant services supplied through the ECO (other than services supplied at "specified premises," i.e., hotels charging above the declared-tariff threshold, which remain under forward charge); accommodation services supplied through the ECO by unregistered suppliers (other than specified premises), added w.e.f. 1-10-2023. The actual supplier retains threshold exemption from registration even though the ECO discharges the tax.
  - Under RCM, the recipient must **self-invoice** and pay tax in cash (RCM liability cannot be discharged by utilising ITC), though the tax so paid is available as ITC to the recipient (subject to the usual eligibility conditions) in the same/later period.

- **Definitions:**

| Term | Meaning |
|---|---|
| Reverse Charge [Sec. 2(98)] | Liability to pay tax by the recipient of supply instead of the supplier |
| Goods Transport Agency (GTA) | Any person who provides service of transport of goods by road and issues a consignment note, by whatever name called |
| Electronic Commerce Operator (ECO) [Sec. 2(45)] | Any person who owns/operates/manages a digital or electronic facility/platform for electronic commerce |

### Exemptions from GST — Section 11

- **Key formula(s)/rule(s):**
$$
\text{Exempt Supply [Sec. 2(47)]} = \text{Nil-rated} + \text{Wholly exempt u/s 11 (or Sec. 6, IGST Act)} + \text{Non-taxable supply}
$$
  - Section 11(1)/Section 6(1) IGST empower the Government, on Council's recommendation, to exempt goods/services generally (by notification) or specifically (by special order), where it is **necessary in the public interest**.

- **Concept:** Exemption is granted **after** a supply is already found taxable under Sections 7 & 9 — it is a policy relief, distinct from Schedule III items (which are outside "supply" itself) and distinct from non-taxable supplies (alcohol, specified petroleum, which are outside the levy).

- **Pitfalls / exam tips — key exemption categories frequently tested:**
  - **Healthcare services** by a clinical establishment, an authorised medical practitioner, or para-medics are exempt; but cosmetic/plastic surgery (except to restore anatomy/function lost due to congenital defect, injury, or trauma) is **taxable**.
  - **Educational services** by an "educational institution" (up to higher secondary, or approved vocational courses) are exempt for the core educational service and transportation/catering/security provided **to its own students, faculty & staff**; coaching/private tuition centres and services **to** an educational institution by outsiders beyond the specified list are taxable.
  - **Services by charitable entities** registered under Section 12AA/12AB of the Income-tax Act, by way of charitable activities (relief of the poor, medical relief, advancement of religion/spirituality, etc.), are exempt — but any activity in the nature of business (e.g., renting a marriage hall, running a paid gym) is taxable even if run by a charitable trust.
  - **GTA transport of goods** is exempt where the gross transportation charge for a single consignee's consignment does not exceed ₹1,500 (or ₹750 per consignment where multiple consignees are carried in one carriage), and transport of specified exempt goods (agricultural produce, milk, salt, relief materials, defence/military equipment, newspapers/magazines, organic manure, etc.) is exempt regardless of value.
  - **Transport of passengers** by non-AC contract carriage/stage carriage (other than for tourism), metro, monorail, inland waterways, and public transport in a vessel between places in India, is exempt.
  - **Services by RBI, Government/local authority**, and specified services to/by CG/SG/UT/local authority are exempt, subject to detailed carve-outs (e.g., renting of immovable property to a non-Government entity is taxable, speed-post/express-parcel/courier and services in relation to an aircraft/vessel are taxable).
  - Renting of **residential dwelling** for use as residence is exempt (renting for commercial use, or to a registered person under specified reverse-charge notified categories, is taxable).
  - Note the terminology distinction tested repeatedly: "exempt supply" (fully outside tax by notification u/s 11) vs. "zero-rated supply" (exports/SEZ supplies — taxable in law but effectively tax-free with ITC refund, dealt with in the IGST Act, not Section 11).

- **Definitions:**

| Term | Meaning |
|---|---|
| Non-taxable supply [Sec. 2(78)] | A supply of goods or services which is not leviable to tax under the CGST/IGST Act (e.g., alcoholic liquor for human consumption, specified petroleum products) |
| Exempt supply [Sec. 2(47)] | Supply attracting nil rate of tax, or wholly exempt u/s 11/Sec. 6 IGST Act, or a non-taxable supply |
| Zero-rated supply [Sec. 16, IGST Act] | Export of goods/services, or supply to a SEZ developer/unit — taxable in principle, but no tax borne on the supply itself, with full ITC/refund eligibility |

### References

1. CGST Act, 2017 — Sections 2 (definitions), 7 & Schedules I–III, 8, 9, 10, 11.
2. IGST Act, 2017 — Sections 5, 6, 16.
3. Notification No. 14/2019-Central Tax dated 07-03-2019 — enhanced composition threshold to ₹1.5 crore (₹75 lakh for 8 special category States).
4. Notification No. 3/2019-Central Tax (Rate) and Notification No. 2/2019-Central Tax (Rate) — composition rates for manufacturers/traders (1%), restaurants (5%), and Section 10(2A) service-composition scheme (6%, turnover up to ₹50 lakh).
5. Notification No. 13/2017-Central Tax (Rate) dated 28-06-2017 (as amended) — list of services under reverse charge u/s 9(3), including GTA, legal services, sponsorship, director's services, TDR/FSI, security services.
6. Notification No. 4/2017-Central Tax (Rate) — list of goods under reverse charge u/s 9(3).
7. Notification No. 07/2019-Central Tax (Rate) dated 29-03-2019 — Section 9(4) RCM for promoters (cement, and 80% procurement-from-registered-persons rule).
8. Notification No. 17/2017-Central Tax (Rate) (as amended, including Notification No. 09/2023-Central Tax (Rate)) — Section 9(5) e-commerce operator notified services (radio-taxi/motorcab transport, housekeeping, restaurant services, accommodation services).
9. Notification No. 12/2017-Central Tax (Rate) dated 28-06-2017 (as amended) — exemption notification for services (healthcare, education, GTA, charitable activities, GoI/local authority services, etc.), issued under Section 11.
10. CGST/IGST amendments per Finance Act 2021 (Section 7(1)(aa) — club/association mutuality) and Finance Act 2023/2024 updates as applicable for the 2026 CA Final syllabus.

## 02. Time of Supply

> **Where it fits:** Time of Supply (ToS) fixes the *point in time* at which the liability to pay GST arises — it tells you *when*, not *how much* (Value of Supply) or *whether* (Levy/Scope of Supply) tax is payable. It also fixes the applicable rate of tax when the rate changes mid-transaction.

### Time of Supply for Goods — Forward Charge [Section 12(2)]

- **Key formula(s)/rule(s):**

$$
\text{ToS (Goods, FCM)} = \min\big(\text{Date of issue of invoice (or last date by which invoice ought to have been issued u/s 31(1))},\ \ \text{Date of receipt of payment}\big)
$$

- Section 31(1): invoice for goods must be issued **on or before removal**, where supply involves movement of goods; or **on or before delivery/making available**, in any other case.
- **Practical override:** Notification No. 66/2017-CT dated 15.11.2017 exempts *all registered persons other than composition taxpayers* from paying tax on **advances received for future supply of goods**. Net effect for regular taxpayers: ToS for goods (FCM) collapses to the **invoice date / last date for issuing invoice**; the "payment date" limb is effectively relevant only to composition suppliers of goods.
- **Second proviso (excess payment up to ₹1,000):** where the supplier receives an amount **in excess of the invoice value, up to ₹1,000**, the ToS for that excess amount, at the supplier's option, is the **date of issue of the invoice** relating to such excess.

- **Concept:** Governs when tax must be paid on outward supplies of goods made under forward charge by a regular (non-composition) taxpayer.

- **Pitfalls / exam tips:**
  - Do not forget Notification 66/2017-CT in numerical problems — advances on goods (non-composition dealer) are **not** an independent trigger for ToS.
  - The ₹1,000 excess-receipt proviso is a favourite 2-mark twist — it applies to **both goods and services** symmetrically.
  - "Continuous supply of goods" (e.g., through a wire/pipeline, successive statements of accounts) — invoice must be issued on/before each statement/payment date; that date becomes the ToS trigger.

### Time of Supply for Goods — Reverse Charge (RCM) [Section 12(3)]

- **Key formula(s)/rule(s):**

$$
\text{ToS (Goods, RCM)} = \min\Big(\text{Date of receipt of goods},\ \ \min(\text{date entered in recipient's books},\ \text{date debited in bank a/c}),\ \ \text{31st day from supplier's invoice date}\Big)
$$

- If none of the above can be determined, ToS = **date of entry in the books of account of the recipient**.

- **Concept:** For goods notified under RCM, the *recipient* self-assesses and pays tax; the earliest of receipt, payment, or a 30-day-from-invoice backstop fixes the point.

- **Pitfalls / exam tips:**
  - The backstop is the **31st day** from invoice date (i.e., 30 days have elapsed) — commonly misquoted as "30 days."
  - Distinguish this backstop from the RCM-services backstop (61st day), a classic mix-up in exams.

### Time of Supply for Vouchers [Section 12(4)] & Residual Case [Section 12(5)]

- **Key formula(s)/rule(s):**
  - Where supply is identifiable at the point the voucher is issued: ToS = **date of issue of voucher**.
  - In any other case: ToS = **date of redemption of voucher**.
  - **Residual case** (where ToS cannot be determined under (2)/(3)/(4)):
    - If a periodical return has to be filed → ToS = **due date of filing that return**.
    - In any other case → ToS = **date on which tax is actually paid**.

- **Concept:** Catch-all provisions to ensure every supply has a determinable point of taxation.

- **Pitfalls / exam tips:** Interest/late fee/penalty for delayed payment — ToS for such addition to value is the **date on which the supplier receives such addition in value** (a distinct, later ToS from the principal supply).

### Time of Supply for Services — Forward Charge [Section 13(2)]

- **Key formula(s)/rule(s):**

$$
\text{If invoice issued within time limit u/s 31(2):}\quad \text{ToS} = \min(\text{Date of issue of invoice},\ \text{Date of receipt of payment})
$$

$$
\text{If invoice NOT issued within time limit:}\quad \text{ToS} = \min(\text{Date of provision of service},\ \text{Date of receipt of payment})
$$

$$
\text{If neither of the above can be determined:}\quad \text{ToS} = \text{Date on which recipient shows receipt of service in his books of account}
$$

- Section 31(2)/31A time limit to issue invoice for services:
  - **Ordinary supplier:** within **30 days** from the date of supply of service.
  - **Banking company / financial institution / NBFC:** within **45 days** from the date of supply of service.
- **Second proviso (excess payment up to ₹1,000):** same as goods — ToS for excess receipt up to **₹1,000** over invoice value is, at supplier's option, the **date of invoice**.

- **Concept:** Timely invoicing (within 30/45 days) is rewarded with the invoice-or-payment (whichever earlier) rule; late invoicing shifts the trigger to actual provision of service.

- **Pitfalls / exam tips:**
  - "Date of receipt of payment" = earlier of date entered in supplier's books **or** date credited to bank account.
  - Continuous supply of services with a due date fixed under contract: the **due date of payment as per contract** is deemed the "date of provision of service," whether or not invoice/payment actually happens on that date — a frequently tested nuance (e.g., NHAI/instalment-based government contracts, spectrum/licence-fee arrangements under RCM).

### Time of Supply for Services — Reverse Charge (RCM) [Section 13(3)]

- **Key formula(s)/rule(s):**

$$
\text{ToS (Services, RCM)} = \min\Big(\min(\text{date entered in recipient's books},\ \text{date debited in bank a/c}),\ \ \text{61st day from supplier's invoice date}\Big)
$$

- If it cannot be determined, ToS = **date of entry in the books of account of the recipient**.
- **Associated enterprises, supplier located outside India:** ToS = **earlier of** (a) date of entry in the books of account of the recipient, or (b) date of payment.

- **Concept:** Mirrors the goods-RCM structure but with a 60-day (i.e., 61st-day) backstop instead of 30 days, reflecting the longer invoicing window for services.

- **Pitfalls / exam tips:**
  - Backstop = **61st day** from invoice date (30 days for goods vs. 60 days for services — do not swap).
  - The special associated-enterprise rule (import of service from a related/associated foreign entity) drops the invoice-backstop limb entirely — only books-entry vs. payment date matters.

### Vouchers & Residual Case for Services [Section 13(4)/(5)]

- **Key formula(s)/rule(s):** Identical structure to goods — voucher: date of issue (if supply identifiable) or date of redemption; residual: due date of return, else date tax is actually paid.
- **Concept:** Same catch-all logic as Section 12(4)/(5), applied to services.

### Time of Supply on Change in Rate of Tax [Section 14]

- **Key formula(s)/rule(s):** Three reference points — **date of actual supply**, **date of invoice**, **date of payment**. "Date of receipt of payment" = earlier of date credited in bank account or date entered in books of account; **but** if the bank credit happens **after 4 working days** from the date of change in rate of tax, the date of credit in the bank account is deemed the date of receipt of payment (safeguard against manipulation).

**(A) Goods/services supplied BEFORE the change in rate of tax:**

$$
\begin{cases}
\text{Invoice \& payment both after change} & \Rightarrow\ \text{ToS} = \min(\text{Date of invoice},\ \text{Date of payment}) \\
\text{Invoice before change, payment after change} & \Rightarrow\ \text{ToS} = \text{Date of invoice} \\
\text{Payment before change, invoice after change} & \Rightarrow\ \text{ToS} = \text{Date of payment}
\end{cases}
$$

**(B) Goods/services supplied AFTER the change in rate of tax:**

$$
\begin{cases}
\text{Payment after change, invoice before change} & \Rightarrow\ \text{ToS} = \text{Date of payment} \\
\text{Invoice \& payment both before change} & \Rightarrow\ \text{ToS} = \min(\text{Date of invoice},\ \text{Date of payment}) \\
\text{Invoice after change, payment before change} & \Rightarrow\ \text{ToS} = \text{Date of invoice}
\end{cases}
$$

- **Concept:** Whenever two of the three events (supply, invoice, payment) straddle the date of rate change, the ToS — and hence the applicable rate — is fixed by whichever of invoice/payment is **earlier** if both fall on the *same side* of the change (post- or pre-), or by the single event that falls on the *opposite side* of the actual-supply date if the other two are split.
- **Mnemonic:** if invoice and payment are on the **same side** of the rate-change date → take the **earlier** of the two; if they are on **different sides** → the ToS is whichever one occurs **after the date of actual supply's own side is broken**, i.e., simply the one event (invoice or payment) that is *out of sync* with the supply timing decides it alone.

- **Pitfalls / exam tips:**
  - This is a high-weightage numerical topic — always draw a 3-point timeline (supply / invoice / payment) before applying the rule.
  - The 4-working-day safeguard on bank credit is a common trap in "manipulated payment date" fact patterns.
  - Section 14 overrides Sections 12/13 whenever a rate change is involved — apply Section 14 first in mixed problems.

### Definitions

| Term | Meaning |
|---|---|
| Date of receipt of payment | Earlier of: date entered in supplier's books of account, or date payment is credited to supplier's bank account |
| Continuous supply of goods | Supply provided/agreed to be provided continuously/on recurrent basis, under a contract, with periodic invoicing/payment (e.g., through pipeline/wire) |
| Continuous supply of services | Supply provided/agreed to be provided continuously/on recurrent basis for a period exceeding 3 months with periodic payment obligation, or as notified by Government |
| Associated enterprises | Enterprises related as per Section 92A of the Income-tax Act, 1961 (common control/ownership tests) |
| Voucher | An instrument accepted as consideration (whole/part) for a supply, where the supply/identity of possible suppliers is indicated on the instrument or related documentation |

### References
1. Section 12, CGST Act, 2017 — Time of supply of goods (forward charge, RCM, vouchers, residual, ₹1,000 proviso) — cross-verified via Masters India, TaxGuru, and AUBSP commentaries.
2. Section 13, CGST Act, 2017 — Time of supply of services (forward charge, RCM 61st-day backstop, associated enterprises) — cross-verified via AUBSP and ConsultEase commentaries.
3. Section 14, CGST Act, 2017 — Time of supply in case of change in rate of tax — cross-verified via TaxGuru and CA Club India analyses.
4. Section 31, CGST Act, 2017 — Tax invoice: time limits for issue (removal/delivery for goods; 30 days / 45 days for services).
5. Notification No. 66/2017-Central Tax, dated 15.11.2017 — Exemption from payment of tax on advances received for supply of goods (non-composition suppliers) — verified via GST Council / GSTZen records.

## 03. Value of Supply

> **Where it fits:** GST is charged ad valorem — as a % of the "value of supply." Section 15 of the CGST Act lays down the transaction-value principle, and Chapter IV (Rules 27–35) of the CGST Rules provides special valuation methods for cases where transaction value cannot be applied directly (related-party supplies, barter, agent transactions, lottery/gaming, air travel agents, insurance, second-hand goods, pure agent, forex, etc.).

### Transaction Value — Section 15(1)

- **Key formula(s)/rule(s):**
  - Value of supply = transaction value, i.e., the price actually paid or payable for the supply, **provided both conditions below are satisfied**:
    - Supplier and recipient are **not related persons**; and
    - **Price is the sole consideration** for the supply (i.e., entire consideration is in money, no non-monetary component).
  - If either condition fails, transaction value under Section 15(1) cannot be adopted — value must instead be determined under Rule 27 (non-monetary consideration) or Rule 28 (related-party/distinct-person transactions).
- **Concept:** Section 15(1) is the default/general rule — used in the vast majority of ordinary arm's-length sales. It is the starting point before checking any inclusions/exclusions or the special valuation rules.
- **Pitfalls / exam tips:**
  - "Related person" is defined in Explanation to Section 15 (read with Schedule I concept of "distinct persons" for same-PAN branches across states) — a recurring cross-reference from the Supply chapter.
  - MRP is irrelevant for GST valuation unless it happens to equal the actual transaction price; GST is charged on transaction value, not MRP.
- **Definitions:**

| Term | Meaning |
|---|---|
| Transaction value | Price actually paid or payable for the supply when supplier & recipient are unrelated and price is the sole consideration |
| Related person | As defined in Explanation to Section 15 (officers/directors of one another's business, legally recognised partners, employer-employee, common third-person control, one directly/indirectly controls the other, together they control a third person, members of the same family, sole agent/sole distributor/sole concessionaire of each other) |

### Inclusions in Value of Supply — Section 15(2)

- **Key formula(s)/rule(s):** The following are **added** to the transaction value if not already included in the price:
  1. Any taxes, duties, cesses, fees and charges levied under any law **other than GST laws** (e.g., municipal tax, entertainment tax not subsumed), if charged separately by the supplier.
  2. Any amount that the supplier is liable to pay in relation to the supply but which has been incurred by the **recipient** and is not included in the price (e.g., recipient pays a third party directly on supplier's behalf).
  3. Incidental expenses charged by the supplier to the recipient, including commission and packing, and any amount charged for anything done by the supplier at the time of, or before, delivery (e.g., weighment, installation, testing/inspection charges).
  4. Interest, late fee, or penalty for **delayed payment** of consideration for any supply.
  5. Subsidies **directly linked to the price**, excluding subsidies given by the Central Government or a State Government — such non-government subsidies are added back to value of supply (grossed up as recipient of subsidy generally is the supplier).
- **Concept:** These are amounts that, though sometimes billed separately or received from a third party, are economically part of what the supplier is realising for the supply and so must be added back to arrive at the true taxable value.
- **Pitfalls / exam tips:**
  - Subsidy given by Central/State Government is **never** added to value of supply, regardless of who it is linked to — a favourite trick in MCQs/case studies.
  - Interest/late fee/penalty for delayed payment is generally treated as **cum-tax (inclusive of GST)** unless the question states otherwise, and its time of supply is the date such amount is actually received (relevant cross-reference to Time of Supply chapter) — rate of tax applicable is the rate applicable on the principal supply.
  - Amount paid by recipient to a third party is added **only if the supplier was liable to make that payment** — if the recipient was independently liable (not on supplier's behalf), it is not added.
- **Definitions:**

| Term | Meaning |
|---|---|
| Incidental expenses | Costs like packing, commission, weighment/loading, installation and testing charges billed alongside the principal supply |
| Cum-tax value | Value treated as inclusive of GST, requiring back-calculation to arrive at the taxable value |

### Exclusions — Discounts [Section 15(3)]

- **Key formula(s)/rule(s):** Value of supply **excludes** discount if:
  - **Pre-supply discount** (recorded in the invoice itself) — always excluded, no condition attached.
  - **Post-supply discount** — excluded only if **both** conditions are met:
    - Discount is established in terms of an agreement entered into **at or before the time of supply**, and is specifically linked to relevant invoices; **and**
    - Input tax credit attributable to the discount has been **reversed by the recipient** of the supply.
- **Concept:** A discount reduces value of supply (and hence GST liability) only when it is transparent, pre-agreed, and does not leave the recipient over-claiming ITC on the discounted portion.
- **Pitfalls / exam tips:**
  - **Secondary/post-sale discounts given through a financial/commercial credit note** (not a GST tax credit note) that do NOT satisfy the Section 15(3)(b) conditions — neither reduces the supplier's tax liability, **nor** does the recipient need to reverse any ITC (per CBIC Circular No. 92/11/2019-GST and Circular No. 105/24/2019-GST, as clarified/partly withdrawn by Circular No. 112/31/2019-GST).
  - If the post-sale discount is in the nature of consideration for a **separate service** (e.g., dealer undertakes additional promotional/marketing activity for the manufacturer under a specific agreement, for a specific consideration), that amount is taxable as a separate supply of service by the dealer — it is not merely a "discount."
  - ⚠️ VERIFY — the OCR table on secondary discounts was heavily garbled; the summary above reflects the settled CBIC circular position but the specific illustration in the source could not be reliably reconstructed.

### Value of Supply — Rule 27 (Consideration not wholly in money)

- **Key formula(s)/rule(s):** Where consideration is not wholly in money, value of supply is determined by applying the following, in sequence:
  1. Open market value (OMV) of such supply.
  2. If OMV not available: total money consideration + monetary equivalent of the non-monetary consideration (if such amount is known at the time of supply).
  3. If value not determinable under (1)/(2): value of supply of like kind and quality.
  4. If not determinable under (1)/(2)/(3): value using Rule 30 (cost basis) or Rule 31 (residual method), in that order.
- **Concept:** Applies typically to barter/exchange transactions (e.g., part-payment in goods, exchange offers).
- **Pitfalls / exam tips:** Always check for OMV first; students often jump straight to cost-plus-10% without checking the earlier steps.

### Value of Supply — Rule 28 (Related persons / distinct persons)

- **Key formula(s)/rule(s):** Value of supply between related persons (other than through an agent) or between distinct persons (Schedule I, e.g., branches with separate GST registrations under one PAN), where price is not the sole consideration or parties are related:
  - Value = Open Market Value of such supply; or
  - If OMV not available, value of supply of goods/services of like kind and quality; or
  - If not determinable under either, value as per Rule 30 (cost method) or Rule 31 (residual method), in that order.
  - **Proviso:** Where the recipient is eligible for **full input tax credit**, the value declared in the invoice is deemed to be the open market value (i.e., no further valuation exercise needed) — this covers most inter-branch/distinct-person stock transfers.
- **Concept:** Prevents undervaluation between related/group entities where price alone cannot be trusted as arm's length.
- **Pitfalls / exam tips:**
  - The full-ITC proviso is the most commonly tested point — if recipient can avail full ITC, invoice value is accepted at face value regardless of OMV.
  - Applies to transactions **not** made through an agent — agent transactions fall under Rule 29.
- **Definitions:**

| Term | Meaning |
|---|---|
| Open Market Value (OMV) | Full value in money, excluding GST/compensation cess, payable for a supply to an unrelated person in the ordinary course of trade where price is the sole consideration |
| Distinct persons | Establishments of a person with separate GST registrations (e.g., in different states, or multiple registrations in the same state), treated as separate persons for GST |

### Value of Supply in case of Corporate Guarantee [Rule 28(2)]

- **Key formula(s)/rule(s):**
$$
\text{Value of Supply} = \max\Big(1\% \text{ of the amount of guarantee offered} \times \text{No. of years the guarantee is in force,}\ \ \text{Actual consideration}\Big)
$$
  - Applies where a supplier provides corporate guarantee to a banking company/financial institution **on behalf of a related recipient located in India**, to secure credit facilities for the recipient.
  - **Proviso:** Where the recipient is eligible for full ITC, the value declared in the invoice is deemed to be the value of the supply (similar override as in Rule 28 generally).
- **Concept:** A specific valuation rule inserted to tax related-party corporate guarantees (common in group companies guaranteeing loans for subsidiaries), since no explicit "price" is typically charged for such guarantees.
- **Pitfalls / exam tips:**
  - Effective for corporate guarantees issued or renewed **on or after 26.10.2023** [Notification No. 52/2023-CT], with the valuation mechanics further amended vide Notification No. 12/2024-CT dated 10.07.2024 (clarifying per-annum computation for guarantees given for a specified/part period, and the full-ITC override).
  - Rule does **not** apply to personal guarantees given by directors/promoters (individuals) — only to corporate guarantees by one related company for another.
- **Definitions:**

| Term | Meaning |
|---|---|
| Corporate guarantee | A guarantee given by one company on behalf of a related company to a bank/financial institution to secure a loan/credit facility for the latter |

### Value of Supply — Rule 29 (Principal–Agent transactions)

- **Key formula(s)/rule(s):** Value of supply of goods between principal and agent (a Schedule I "deemed supply" even without consideration) shall be:
  - Open Market Value of goods; **or**, at the supplier's option,
  - **90% of the price charged by the agent to his unrelated customer**, for goods of like kind and quality; **or**
  - If value not determinable under the above, Rule 30 (cost method) / Rule 31 (residual method), in that order.
- **Concept:** Applies to del-credere agent and similar principal–agent goods transactions, giving suppliers the option of a simple 90%-of-onward-sale-price benchmark instead of computing true OMV.
- **Pitfalls / exam tips:**
  - The 90% option is available **only** where the agent further supplies such goods to unrelated buyers — the choice between OMV and the 90% rule lies with the supplier.
  - A **State marketing federation/corporation acting as the sole selling agent** on behalf of a principal is also treated as falling within the ambit of this rule.
  - In a Del Credere Agent (DCA) fact pattern, the DCA's supply of goods to the buyer and the DCA's agency/credit-facilitation service to the principal are separate supplies; interest recovered by the DCA from the buyer for delayed payment (where DCA settles with the principal on time and later collects with interest from the buyer) is treated as part of the value of the DCA's own supply of credit/agency service, taxable accordingly — this is a nuanced, frequently examined illustration.
  - ⚠️ VERIFY — the OCR's Del Credere Agent flowchart (numbered points (i)–(vi)) was almost entirely garbled; the summary above reflects the generally accepted treatment but the source's exact enumeration of "independent vs. composite" supplies could not be reliably reconstructed from this OCR pass.

### Value of Supply — Rule 30 (Cost basis)

- **Key formula(s)/rule(s):**
$$
\text{Value of Supply} = 110\% \times \big(\text{Cost of production/manufacture, or cost of acquisition of goods, or cost of provision of services}\big)
$$
- **Concept:** A fallback/residual-before-residual method used only when value cannot be determined under Rules 27–29.
- **Pitfalls / exam tips:** Under Rules 27, 28 and 29, the taxpayer may choose to apply Rule 30 **before** Rule 31 (residual method) — i.e., cost method is optional but, if opted, must be applied ahead of the fully residual Rule 31.

### Value of Supply — Rule 31 (Residual method)

- **Key formula(s)/rule(s):** Where value cannot be determined under Rules 27–30, it shall be determined using **reasonable means consistent with the principles and general provisions of Section 15 and Chapter IV of the CGST Rules**.
  - For supply of services, the supplier may, at his option, choose to determine value directly under Rule 31 even by-passing Rule 30 (i.e., Rule 30 and Rule 31 may be applied in either order for services, but for goods Rule 30 must be attempted before Rule 31).
- **Concept:** The ultimate catch-all valuation method — a facts-and-circumstances-based approach.
- **Pitfalls / exam tips:** Frequently tested only as a concept (rare to require numeric computation), since it has no fixed formula by design.

### Value of Supply — Rule 31A (Lottery, Betting, Gambling, Horse Racing)

- **Key formula(s)/rule(s):**
$$
\text{Lottery run by State Government: VOS} = \max\left(\frac{100}{112}\times \text{Face value of ticket},\ \ \frac{100}{112}\times \text{Price notified in Official Gazette}\right)
$$
$$
\text{Lottery authorised by State Government: VOS} = \max\left(\frac{100}{128}\times \text{Face value of ticket},\ \ \frac{100}{128}\times \text{Price notified in Official Gazette}\right)
$$
$$
\text{Betting/Gambling/Horse Racing (totalisator/book-maker's licence): VOS} = 100\% \text{ of the face value of the bet or the amount paid/payable to the totalisator/book-maker}
$$
- **Concept:** "Run by" State Government = State itself is the lottery organiser (sold within that State) and attracts a lower GST rate/28% with abatement factor 100/112; "authorised by" State Government = privately distributed/marketed lottery across States, taxed with abatement factor 100/128.
- **Pitfalls / exam tips:** Always take the **higher** of face value or notified price as the base before applying the fraction; students often forget the "whichever is higher" condition.

### Value of Supply — Rule 31B & 31C (Online Gaming and Casino)

- **Key formula(s)/rule(s):**
  - Rule 31B (Online gaming, including online money gaming): Value of supply = **total amount paid or payable to, or deposited with, the supplier** by way of money or money's worth, including virtual digital assets, by or on behalf of the player for participation in such online gaming.
  - Rule 31C (Casino): Value of supply = **total amount paid or payable** by/on behalf of a player for (a) purchase of tokens, chips, coins or tickets for use in the casino, and/or (b) participating in any event, including game, scheme, competition or any other activity, the outcome of which determines the distribution of prizes.
- **Concept:** Both rules ensure GST is levied on the entry amount/deposit itself (not merely the "platform fee" or "rake"), reflecting the amendments effective 1 October 2023 taxing online money gaming, casinos, and horse racing at 28% on full face value.
- **Pitfalls / exam tips:**
  - Any amount **returned/refunded** to the player is **not** deductible from value of supply already computed on the deposit.
  - Winnings from one game re-deposited/used to play a further game are **not again added** to value of supply (to avoid double taxation of the same money re-circulated within the platform).

### Value of Supply — Rule 32 (Specific businesses)

- **Key formula(s)/rule(s):**
  - **Air travel agent — booking of air tickets [Rule 32(3)]:**
$$
\text{VOS (Domestic booking)} = 5\% \times \text{Basic Fare} \qquad
\text{VOS (International booking)} = 10\% \times \text{Basic Fare}
$$
    — "Basic fare" = that part of the air fare on which commission is normally paid by the airline to the agent (excludes taxes/other levies).
  - **Life insurance business [Rule 32(4)]:**
    - Value = gross premium charged **less** the amount allocated for investment/savings on behalf of the policyholder, if intimated to the policyholder at the time of supply; **or**, if not so intimated —
      - Single premium annuity policies: **10% of the single premium** charged; and
      - All other cases: **25% of the premium in the first year**, and **12.5% of the premium in subsequent years**.
    - Where the entire premium is towards risk cover only (pure term policy), the entire premium is taxable (rule does not reduce value).
  - **Second-hand goods — dealer margin scheme [Rule 32(5)]:**
$$
\text{Value of Supply} = \text{Selling Price} - \text{Purchase Price}
$$
    — applicable to a person dealing in buying and selling of second-hand goods, taxed only on the margin; if the margin is negative, it is **ignored** (no GST, no negative value carried forward). Benefit of this rule (motor vehicles) has been extended to **all persons** dealing in used motor vehicles, not just dealers of second-hand goods; where depreciation has been claimed under Section 32 of the Income-tax Act, the **depreciated (written-down) value** is treated as the purchase price for margin computation.
  - **Redeemable vouchers/tokens/coupons/stamps [Rule 32(6)]:** Value of supply = **money value of the goods or services** for which the voucher/token/coupon/stamp is redeemable.
  - **Purchase/sale of foreign currency, including money changing [Rule 32(2)]:**
    - Where one of the currencies exchanged is INR: value = (Buying/Selling rate − RBI reference rate for that currency) × Total units of currency; **or**, at the supplier's option, a slab-based deemed-value method (fixed % of gross amount of INR, subject to minimum/maximum) may be adopted for the entire financial year.
    - Where neither currency exchanged is INR: value = 1% of the lesser of the two amounts, each converted into INR at the RBI reference rate.
- **Concept:** Rule 32 provides simplified, sector-specific presumptive valuation methods for businesses (travel agents, insurers, forex dealers, second-hand goods dealers, voucher issuers) where computing exact transaction value is impractical.
- **Pitfalls / exam tips:**
  - Rule 32 methods are **optional** for the supplier (not mandatory) in the currency-exchange slab method and, per CBIC guidance, the option once exercised for a financial year cannot be withdrawn mid-year.
  - For air travel agents, GST @ 18% applies on the 5%/10% deemed commission value, not on the full ticket price.
  - ⚠️ VERIFY — the OCR's worked forex example ("ABC Ltd sold 2,000 USD/EUR at 86, RBI reference rate 84 → VOS = (86−84) × 2,000 = 4,000") appears numerically consistent with Method-1 of Rule 32(2)(a) but the source's exact currency labels were garbled; treat the mechanics (not the specific currency names) as reliable.

### Value of Supply — Rule 33 (Pure Agent)

- **Key formula(s)/rule(s):** Expenditure or costs incurred by a supplier as a **pure agent** of the recipient are **excluded** from the value of supply, provided **all** of the following conditions are satisfied:
  - Supplier acts as a pure agent when making payment to the third party on authorisation by the recipient;
  - The payment made by the pure agent is separately indicated in the invoice issued to the recipient;
  - Supplies procured by the pure agent from the third party, as pure agent, are **in addition to** the services the supplier provides on his own account.
- **Concept:** A pure agent merely facilitates payment on behalf of the recipient (e.g., a CA firm paying statutory/government fees like MCA filing fees on the client's behalf and getting reimbursed at actuals) — such reimbursement is not part of the CA firm's own taxable value.
- **Pitfalls / exam tips:**
  - Only the **exact reimbursed amount** paid to the third party is excluded; the supplier's own fee/professional charges remain fully taxable.
  - Classic exam illustration: A CA firm charges ₹50,000 as professional fee plus reimbursement of ₹5,000 (MCA government fee paid on client's behalf as pure agent) — value of supply of the CA's own service = ₹50,000 only; the ₹5,000 pure-agent reimbursement is excluded from value.

### Rate of Exchange for Valuation [Rule 34]

- **Key formula(s)/rule(s):**
  - **Goods:** Rate of exchange = rate notified by CBIC (Board) under Section 14 of the Customs Act, 1962, for the date of time of supply.
  - **Services:** Rate of exchange = rate as per generally accepted accounting principles (GAAP), for the date of time of supply.
- **Concept:** Determines the INR value of a supply where consideration is in foreign currency, aligning goods valuation with the customs-notified rate and services valuation with accounting-standard rates.
- **Pitfalls / exam tips:** A commonly tested distinction — goods use the CBIC/customs-notified rate, services use GAAP/accounting rate — do not mix the two up.
- **Definitions:**

| Term | Meaning |
|---|---|
| Rate of exchange | Reference rate used to convert foreign-currency consideration into INR for GST valuation purposes |

### References

1. CGST Act, 2017 — Section 15 (Value of Taxable Supply): https://taxinformation.cbic.gov.in/ (CBIC Tax Information Portal, CGST Act repository).
2. CGST Rules, 2017 — Chapter IV, Rules 27 to 34 (Determination of Value of Supply): https://taxinformation.cbic.gov.in/content/html/tax_repository/gst/rules/cgst_rules/active/chapter4/
3. Notification No. 52/2023-Central Tax dated 26.10.2023 and Notification No. 12/2024-Central Tax dated 10.07.2024 — insertion/amendment of Rule 28(2) (corporate guarantee valuation).
4. CBIC Circular No. 92/11/2019-GST, Circular No. 105/24/2019-GST (partly withdrawn), and Circular No. 112/31/2019-GST — clarification on treatment of secondary/post-sale discounts.
5. Rule 32(3) (air travel agent), Rule 32(4) (life insurance), Rule 32(5) (second-hand goods) — CGST Rules, 2017, as summarised across CBIC-aligned professional commentary (GSTZen, TaxTMI reproduction of rule text) cross-checked against the bare Rule text.

## 04. Place of Supply

> **Where it fits:** Place of Supply (PoS) fixes the *location* to which a supply is attributed. Combined with the location of the supplier, it determines whether a supply is **intra-State** (CGST + SGST/UTGST) or **inter-State/import/export** (IGST) — it answers *where*, not *when* (Time of Supply) or *how much* (Value of Supply). Governed by Chapter V (Sections 10–13) of the IGST Act, 2017.

### Place of Supply of Goods — Domestic Supply, Movement Involved [Section 10(1)(a) & (c), IGST Act]

- **Key formula(s)/rule(s):**

$$
\text{PoS (movement involved)} = \text{Location of goods at the time at which movement of goods terminates for delivery to the recipient}
$$

$$
\text{PoS (no movement, e.g. sale of machinery installed at site)} = \text{Location of goods at the time of delivery to the recipient} \quad [\text{Sec. }10(1)(c)]
$$

- Section 10(1)(d): where goods are **assembled or installed at site**, PoS = **place of such installation or assembly**.
- Section 10(1)(e): where goods are supplied **on board a conveyance** (vessel, aircraft, train, motor vehicle), PoS = **location at which such goods are taken on board**.

- **Concept:** The default rule for domestic B2B/B2C goods supplies — PoS follows the goods to their delivery destination, not the supplier's location.

- **Pitfalls / exam tips:**
  - "Termination of movement for delivery to recipient" ≠ where the transporter physically stops en route; it is the final delivery point.
  - Do not confuse Sec. 10 (domestic goods) with Sec. 11 (import/export of goods) — different section, different rule.

### Place of Supply of Goods — Bill-to-Ship-to / Three-Party Transaction [Section 10(1)(b)]

- **Key formula(s)/rule(s):**

$$
\text{PoS (Supply-1: Supplier} \to \text{Third Person)} = \text{Principal place of business of the third person (who gave the direction)}
$$

$$
\text{PoS (Supply-2: Third Person} \to \text{Actual Recipient)} = \text{Location where movement of goods terminates (i.e., recipient's location)}
$$

- Applies where goods are delivered by the supplier to a recipient (or any other person) **on the direction of a third person**, whether acting as an agent or otherwise, before or during movement of goods — by transfer of documents of title or otherwise. The third person is **deemed to have received the goods**.

- **Concept:** Splits one physical movement into two legal supplies for PoS purposes — e.g., A (Rajasthan) is instructed by B (Gujarat) to ship goods directly to C (Maharashtra); Supply-1 (A→B) has PoS = Gujarat (B's principal place of business); Supply-2 (B→C) has PoS = Maharashtra (where movement ends).

- **Pitfalls / exam tips:**
  - The commonly tested trick: PoS for Supply-1 is the third person's location, **not** the location where goods are physically shipped.
  - Two separate invoices, two separate PoS determinations — do not collapse into one.

### Place of Supply of Goods — No Movement / Over-the-Counter Sale [Section 10(1)(c)]

- **Key formula(s)/rule(s):** PoS = **location of goods at the time of delivery to the recipient**.
- **Concept:** Applies where there is no movement of goods, e.g., an over-the-counter retail sale, or sale of goods forming part of immovable property/fixture at the point of sale.
- **Pitfalls / exam tips:** Frequently tested with showroom/counter-sale fact patterns — PoS = the shop location itself, regardless of buyer's billing address.

### Place of Supply of Goods — Import into / Export from India [Section 11, IGST Act]

- **Key formula(s)/rule(s):**

$$
\text{PoS (Import of goods into India)} = \text{Location of the importer}
$$

$$
\text{PoS (Export of goods from India)} = \text{Location outside India}
$$

- **Concept:** Import of goods is treated as an **inter-State supply** liable to IGST (levied under the Customs Tariff Act along with basic customs duty — Sec. 5(1) proviso, IGST Act); export of goods is a **zero-rated supply** under Section 16, IGST Act.

- **Pitfalls / exam tips:**
  - Import of goods PoS/IGST is charged and collected under the Customs Act mechanism, not a GST return — do not confuse the levy point with the return-filing PoS rule for domestic goods.
  - Export always keeps PoS outside India, supporting the zero-rating claim (LUT/bond or IGST-refund route).

---

### Place of Supply of Services — General/Default Rule (Domestic) [Section 12(1) & 12(2), IGST Act]

- **Key formula(s)/rule(s):**

$$
\text{PoS (B2B, general rule)} = \text{Location of the recipient of service (registered person)}
$$

$$
\text{PoS (B2C, general rule)} = \begin{cases}\text{Address on record of recipient,} & \text{if available} \\ \text{Location of the supplier,} & \text{otherwise}\end{cases}
$$

- Applies **only** where the transaction does not fall under the specific cases of Section 12(3) to 12(14).
- Section 12 applies where **location of supplier and location of recipient are both in India**.

- **Concept:** The residual/default rule for domestic services; PoS generally follows the recipient for B2B, and the recipient's known address (else supplier's location) for B2C.

- **Pitfalls / exam tips:** Always check the specific-case list (immovable property, restaurant/catering, training, event admission, transportation, banking/intermediary, insurance, advertisement to Government, etc.) **before** falling back to the general rule.

### Place of Supply — Services related to Immovable Property [Section 12(3)]

- **Key formula(s)/rule(s):**

$$
\text{PoS} = \text{Location at which the immovable property (or boat/vessel) is located or intended to be located}
$$

- If located **outside India**, PoS = **location of the recipient**.
- Covers: architects, interior decorators, surveyors, engineers, other experts/estate agents; grant of rights to use immovable property; carrying out construction; lodging/accommodation by a hotel, inn, guest house, homestay, club, campsite, houseboat or vessel; accommodation for marriage/functions; and ancillary services to the above.

- **Concept:** Location-of-property rule — the tax follows the immovable asset, mirroring the "destination" logic used in international VAT/GST for real estate.

- **Pitfalls / exam tips:** A common exam twist: property located outside India flips PoS to the **recipient's location** (not supplier's) — do not default this to the general rule's supplier fallback.

### Place of Supply — Restaurant, Catering, Personal Grooming, Fitness, Beauty Treatment, Health Services [Section 12(4)]

- **Key formula(s)/rule(s):** PoS = **location where the services are actually performed**.
- **Concept:** A "performance-based" rule — since these are place-specific personal services, PoS = the physical location of performance, irrespective of recipient's registration status.

### Place of Supply — Training and Performance Appraisal [Section 12(5)]

- **Key formula(s)/rule(s):**

$$
\text{PoS} = \begin{cases}\text{Location of recipient,} & \text{if registered} \\ \text{Location where services are actually performed,} & \text{if unregistered}\end{cases}
$$

- **Concept:** Distinguishes B2B (recipient-based) from B2C (performance-based) treatment for training/appraisal services.

### Place of Supply — Admission to an Event or Amusement Park [Section 12(6)]

- **Key formula(s)/rule(s):** PoS = **place where the event is actually held** or where the park/other place is located.
- **Concept:** Covers cultural, artistic, sporting, scientific, educational, entertainment events, conferences, exhibitions and amusement parks.

### Place of Supply — Organization of an Event [Section 12(7)]

- **Key formula(s)/rule(s):**

$$
\text{PoS} = \begin{cases}\text{Location of recipient,} & \text{if registered}\\ \text{Place where the event is actually held,} & \text{if unregistered}\end{cases}
$$

- If the event is held **outside India**, PoS = **location of the recipient**.
- Covers organizing conferences, fairs, exhibitions, celebrations and ancillary services, and assigning sponsorship to such events.

- **Pitfalls / exam tips:** Do not confuse "admission to" (Sec. 12(6), always performance-location based) with "organization of" (Sec. 12(7), recipient-based if registered).

### Place of Supply — Transportation of Goods, including by Mail or Courier [Section 12(8)]

- **Key formula(s)/rule(s):**

$$
\text{PoS} = \begin{cases}\text{Location of the registered recipient} \\ \text{Location at which the goods are handed over for transportation, if recipient is unregistered}\end{cases}
$$

- ⚠️ VERIFY (amendment awareness) — the earlier **proviso** to Section 12(8), which fixed PoS at the **destination of goods** when the destination was **outside India**, has been **omitted w.e.f. 1 October 2023** (Finance Act, 2023). Post-amendment, PoS for transportation of goods follows only the two limbs above (recipient's location if registered; place where goods are handed over for transportation, otherwise) — destination is no longer relevant even for exports.

- **Concept:** A recipient-centric rule for goods transportation (GTA, courier, mail) — contrast with passenger transportation (Sec. 12(9), embarkation-based).

- **Pitfalls / exam tips:** This is a live, exam-relevant amendment for the current syllabus — many older notes/solved papers still show the "destination if outside India" proviso; that proviso **no longer exists**.

### Place of Supply — Passenger Transportation [Section 12(9)]

- **Key formula(s)/rule(s):**

$$
\text{PoS} = \begin{cases}\text{Location of the registered recipient}\\ \text{Place where the passenger embarks on the conveyance for a continuous journey, if unregistered}\end{cases}
$$

- Return journey is treated as a **separate journey**, even if the right to passage for onward and return journey is issued at the same time.

- **Concept:** For unregistered/B2C passengers, PoS is anchored to the **point of embarkation**, not the ticket-issue location or destination.

### Place of Supply — Services on Board a Conveyance [Section 12(10)]

- **Key formula(s)/rule(s):** PoS = **first scheduled point of departure of that conveyance for the journey**.
- **Concept:** Applies to services (e.g., food, entertainment) supplied on board a vessel, aircraft, train or motor vehicle during a journey.

### Place of Supply — Telecommunication Services [Section 12(11)]

- **Key formula(s)/rule(s):**
  - Fixed telecommunication line, circuit, dish/antenna installed: PoS = **location where the line/circuit/dish is installed**.
  - Post-paid mobile/internet connection: PoS = **billing address of the recipient on record of the supplier**.
  - Pre-paid (through voucher/otherwise) sold through a selling agent/re-seller/distributor: PoS = **address of the selling agent/re-seller as per supplier's records at the time of supply**.
  - Pre-paid sold over the counter/electronic mode of payment: PoS = **location where such pre-payment is received or vouchers are sold**.
  - In other cases, PoS = **address of recipient on record**; if not available, **location of supplier**.

- **Concept:** A layered rule distinguishing fixed-line, post-paid, pre-paid-through-agent, and pre-paid-direct scenarios for telecom services.

### Place of Supply — Banking/Financial/NBFC Services to Account Holders, Intermediary Services, Hiring of Means of Transport [Section 12(12), (13) & (14)... rearranged]

- **Key formula(s)/rule(s):**
  - Banking and other financial services (including stockbroking) supplied to account holders: PoS = **location of the recipient of services on record of the supplier**; if not on record, **location of the supplier**.
  - Intermediary services: PoS = **location of the supplier of services**.
  - Hiring of means of transport (including yacht, but **excluding aircraft and vessels**), up to a period of **one month**: PoS = **location of the supplier of services**.

- **Definitions:**

| Term | Meaning |
|---|---|
| Intermediary | A broker, agent or any other person who arranges/facilitates the supply of goods/services/securities between two or more persons, but does not include a person who supplies such goods/services/securities **on his own account**. Minimum 3 parties, 2 distinct supplies (main + ancillary/facilitation). |

- **Pitfalls / exam tips:**
  - Intermediary PoS = **supplier's** location — the opposite of the general B2B default (which is recipient-based); a classic exam flip.
  - "Hiring of aircraft/vessel" is specifically **excluded** from the supplier-location rule (falls back to the general rule instead), regardless of period.

### Place of Supply — Insurance Services [Section 12(13)]

- **Key formula(s)/rule(s):**

$$
\text{PoS} = \begin{cases}\text{Location of recipient, per supplier's records,} & \text{if registered}\\ \text{Location of recipient at the time of entering into contract,} & \text{if unregistered}\end{cases}
$$

### Place of Supply — Advertisement Services to the Central/State Government [Section 12(14)]

- **Key formula(s)/rule(s):** Where advertisement services are supplied to the Central Government, a State Government, a statutory body, or a local authority meant for identifiable States, PoS = **each such State**, and the value of such supply is deemed to be in the same proportion as the amount attributable to the dissemination in each State (e.g., pro-rated by circulation figures for print, or as per contract terms).
- **Concept:** Necessary because a single advertisement contract for Government clients often spans multiple States; the value (and hence tax) must be apportioned across those States.

---

### Place of Supply of Services — Where Supplier or Recipient is Located Outside India [Section 13, IGST Act]

- **Key formula(s)/rule(s):**

$$
\text{PoS (General rule, Section 13(2))} = \begin{cases}\text{Location of the recipient of services} \\ \text{Location of the supplier of services, if recipient's location is not available in the ordinary course of business}\end{cases}
$$

- Section 13 applies **only** where the **location of the supplier of services OR the location of the recipient of services is outside India** (i.e., at least one leg is outside India — import or export of service scenarios).

- **Concept:** Mirrors Section 12's structure but is the operative section whenever cross-border services are involved; used to test whether a service is an "export of services" (PoS outside India + other Sec. 2(6) IGST conditions) or "import of services."

- **Pitfalls / exam tips:** Students often apply Section 12 to cross-border facts by mistake — the trigger for Section 13 is location of *either party* outside India, not registration status.

### Place of Supply — Performance-Based Services (Cross-Border) [Section 13(3)]

- **Key formula(s)/rule(s):**
  - Services supplied **in respect of goods** that are required to be made physically available by the recipient to the supplier (or a person acting on the supplier's behalf) to provide the service: PoS = **location where the services are actually performed**.
    - Exception: where such services are provided from a remote location by way of electronic means (e.g., remote repair/diagnostics), PoS = **location where goods are situated at the time of supply**.
  - Services requiring the **physical presence of the recipient** (or a person acting on the recipient's behalf) with the supplier to provide the service: PoS = **location where the services are actually performed**.

- **Concept:** A "performance-location" rule for cross-border repair/testing/certification of goods, and personal services requiring physical co-presence.

### Place of Supply — Immovable Property, Event-Based (Cross-Border) [Section 13(4) & 13(5)]

- **Key formula(s)/rule(s):**
  - Services **directly related to immovable property**: PoS = **location where the immovable property is located or intended to be located**.
  - Services relating to **admission to, or organization of, an event** (cultural, artistic, sporting, scientific, educational, entertainment event; celebration; conference; fair; exhibition): PoS = **place where the event is actually held**.

- **Concept:** Same underlying logic as Sections 12(3)/12(6)/12(7), transposed to cross-border facts.

### Place of Supply — Services Supplied at More than One Location [Section 13(6) & 13(7)]

- **Key formula(s)/rule(s):**
  - Where a service under Section 13(3)/(4)/(5) is supplied at more than one location, **including a location in the taxable territory**: PoS = **the location in the taxable territory** (Sec. 13(6)).
  - Where such services are supplied in **more than one State/UT**: PoS = each such State/UT, value apportioned in **proportion to the value of services so provided in each such State/UT** (Sec. 13(7), similar to the apportionment logic in Section 12(14)).

### Place of Supply — Banking/Intermediary/Hiring of Transport (Cross-Border) [Section 13(8)]

- **Key formula(s)/rule(s):** PoS = **location of the supplier of services**, for:
  - Services supplied by a **banking company, financial institution, or NBFC** to account holders.
  - **Intermediary services.**
  - Services of **hiring of means of transport (other than aircraft and vessels)**, up to a period of **one month**.

- **Concept:** Cross-border mirror of Section 12(12)/12(14) rules — same supplier-location anchor.

- **Pitfalls / exam tips:** This supplier-location rule is the single biggest reason **intermediary services and BFSI-to-account-holder services rendered from India for a foreign client typically do NOT qualify as "export of services"** — PoS stays in India, so one of the export conditions (PoS outside India) fails.

### Place of Supply — Transportation of Goods (Cross-Border) [Section 13(9) — Omitted]

- ⚠️ VERIFY (structural change) — Section 13(9), which earlier fixed PoS for goods-transportation services (other than by mail/courier) at the **destination of the goods**, has been **omitted w.e.f. 1 October 2023** (Finance Act, 2023, Sec. 162). Transportation of goods (import/export leg) is therefore **no longer a "specific case"** and now falls back to the **general rule of Section 13(2)** — PoS = location of the recipient; if not available, location of the supplier.
- **Concept:** A structural simplification — pre-Oct-2023 solved illustrations showing "PoS = destination of goods" under Section 13(9) are now superseded.
- **Pitfalls / exam tips:** For current-syllabus attempts, do not cite Section 13(9) as an operative specific-case provision — cite the general rule instead.

### Place of Supply — Passenger Transportation (Cross-Border) [Section 13(10)]

- **Key formula(s)/rule(s):** PoS = **place where the passenger embarks on the conveyance for a continuous journey**.

### Place of Supply — Services on Board a Conveyance (Cross-Border) [Section 13(11)]

- **Key formula(s)/rule(s):** PoS = **first scheduled point of departure of that conveyance for the journey**.

### Place of Supply — Online Information and Database Access or Retrieval (OIDAR) Services [Section 13(12)]

- **Key formula(s)/rule(s):**

$$
\text{PoS (OIDAR)} = \text{Location of the recipient of services}
$$

- The recipient is **deemed to be located in the taxable territory** if **any two of the following seven non-contradictory conditions** are satisfied:

| # | Condition |
|---|---|
| 1 | Address (through internet) presented by the recipient is in taxable territory |
| 2 | Credit/debit/store-value/charge/smart card used for payment is issued in taxable territory |
| 3 | Billing address of the recipient is in taxable territory |
| 4 | IP address of the device used by the recipient is in taxable territory |
| 5 | Bank in which the recipient's account used for payment is maintained is in taxable territory |
| 6 | Country code of the SIM card used by the recipient is of taxable territory |
| 7 | Location of the recipient's fixed land line through which the service is received is in taxable territory |

- **Concept:** OIDAR (e-books, cloud services, online gaming, streaming, online advertising, database access, etc.) has no natural "place of performance," so PoS is proxied via at least two independent, non-contradictory digital footprint indicators pointing to India.

- **Pitfalls / exam tips:** "Any **two**" is the operative number (not "any one" and not "all") — a frequently tested numeric detail.

### References

1. IGST Act, 2017 — Section 10 (Place of supply of goods — other than import/export), CBIC Tax Information Portal, taxinformation.cbic.gov.in.
2. IGST Act, 2017 — Section 12 (Place of supply of services — where location of supplier and recipient is in India), CBIC Tax Information Portal.
3. IGST Act, 2017 — Section 13 (Place of supply of services — where location of supplier or recipient is outside India), CBIC Tax Information Portal.
4. Finance Act, 2023, Section 162 — omission of proviso to Section 12(8) and of Section 13(9) of the IGST Act, effective 01.10.2023 (Notification No. 28/2023-Central Tax dated 31.07.2023 appointing the date); as summarized by Bizsolindia/Lakshmikumaran & Sridharan/TaxGuru commentaries on the amendment.
5. Section 13(12), IGST Act, 2017 and related OIDAR guidance (CBIC/GST Gyaan/InfiniteOnTax commentary) for the "any two of seven conditions" taxable-territory test.

## 05. Import and Export under GST

> **Where it fits:** Cross-border transactions sit outside the normal CGST+SGST/IGST supply rules — imports are taxed as a deemed inter-State supply (Customs duty + IGST at the border), while exports are "zero-rated" (no output tax, but full ITC/refund) to keep Indian goods/services competitive abroad. This chapter builds on Place of Supply and feeds directly into the Refunds chapter.

### Import of Goods

- **Key formula(s)/rule(s):**
  - Import of goods = bringing goods into India from a place outside India — treated as an **inter-State supply** [Section 7(2), IGST Act] and liable to IGST under the **Customs Tariff Act, 1975** (collected as "levy" along with Basic Customs Duty at the point of import), *not* under Section 9 of CGST Act.
  - Levy point: IGST on imported goods is charged and collected under **Section 3(7) of the Customs Tariff Act, 1975**, in addition to Basic Customs Duty (BCD), on the value determined under the Customs Act.
  - ITC of IGST paid on import of goods is available on the basis of the **Bill of Entry (BOE)**, provided the importer's GSTIN is quoted on it.
- **Concept:** Import of goods never passes through the GST return chain as an "outward supply" of the foreign seller — it is picked up entirely at Customs; the importer self-assesses and pays IGST + BCD to Customs, then avails ITC through the BOE reflected in GSTR-2B/ICEGATE-GSTN link.
- **Pitfalls / exam tips:**
  - Do not confuse this with RCM under Section 5(3) IGST Act — import of goods is *not* an RCM supply, it is a Customs-frontier levy.
  - Actionable claims are excluded from the scope of "goods" for this purpose (per Schedule III), so import of actionable claims (other than lottery/betting/gambling) is outside GST.
- **Definitions:**

| Term | Meaning |
|---|---|
| Import of goods [Sec 2(10), IGST Act] | Bringing goods into India from a place outside India |
| Bill of Entry (BOE) | Customs document filed by importer; basis for claiming ITC of IGST paid on import |

### Import of Services

- **Key formula(s)/rule(s):**
  - Import of services = supply where (a) supplier is located outside India, (b) recipient is located in India, and (c) place of supply is in India [Section 2(11), IGST Act].
  - **Taxability trigger:** first test whether the transaction is a "supply" (including the "even without consideration" exception under Schedule I for import of services from a related person/distinct establishment in the course/furtherance of business), then check for exemption.
  - Import of service **by a registered business recipient** → taxable under **Reverse Charge Mechanism (RCM)** [Section 5(3), IGST Act read with Notification 10/2017-IT(Rate)] — recipient pays IGST and can claim ITC.
  - Import of service **by a non-taxable online recipient (unregistered individual, for OIDAR services)** → taxable under **Forward Charge (FCM)**, with the foreign OIDAR supplier (or its intermediary/representative in India) liable to register and pay IGST.
- **Concept:** Services don't cross a physical Customs frontier, so GST law itself deems the import and shifts the compliance burden to whichever side is easier to enforce against — the Indian recipient (RCM) for B2B, or the foreign supplier (FCM) for B2C-OIDAR.
- **Pitfalls / exam tips:**
  - Import of services **without consideration** is taxable only between related persons / distinct persons (e.g., Indian branch and its foreign HO) in the course or furtherance of business — a personal, non-business import without consideration stays outside GST.
  - Always run the sequence: Is it a supply? → Is it exempt? → Who pays (RCM/FCM)?
- **Definitions:**

| Term | Meaning |
|---|---|
| Import of services [Sec 2(11), IGST Act] | Supplier outside India + recipient in India + POS in India |
| OIDAR | Online Information and Database Access or Retrieval services |
| Non-taxable online recipient | Unregistered person in India receiving OIDAR services for non-business purposes |

### Export of Goods and Export of Services — Definitions

- **Key formula(s)/rule(s):**
  - **Export of goods** [Section 2(5), IGST Act]: taking goods out of India to a place outside India.
  - **Export of services** [Section 2(6), IGST Act] — ALL FIVE conditions must be cumulatively satisfied:
    1. Supplier is located in India;
    2. Recipient is located outside India;
    3. Place of supply of the service is outside India;
    4. Payment for the service has been received by the supplier in convertible foreign exchange (or in Indian Rupees, wherever permitted by the RBI);
    5. Supplier and recipient are not merely "establishments of a distinct person" [per Explanation 1 to Section 8, IGST Act].
- **Concept:** Export of goods needs only physical movement out of India; export of services is a stricter, five-condition test — miss even one condition and the transaction is reclassified as a normal (taxable) supply, losing zero-rated status.
- **Pitfalls / exam tips:**
  - A classic exam trap: an Indian company and its foreign subsidiary/branch/holding company are still **separate legal persons** unless one is merely an "establishment" of the other (e.g., HO-branch of the *same* legal entity) — in that latter case, condition 5 fails and the supply is *not* export (it's a supply between distinct persons of the same legal entity, taxable/Schedule I situation).
  - Payment condition: receipt must be in convertible foreign exchange/INR as permitted by RBI — payment in any other currency does not qualify.
- **Definitions:**

| Term | Meaning |
|---|---|
| Convertible foreign exchange | Foreign currency freely convertible per FEMA/RBI regulations |
| Establishment of a distinct person | Same legal entity's establishments in India and outside India (Explanation 1, Sec 8 IGST Act) — supply between them is intra-entity, not export |

### Zero-Rated Supply vs Exempt Supply

- **Key formula(s)/rule(s):**
  - **Zero-rated supply** [Section 16, IGST Act] means: (a) export of goods or services or both, or (b) supply of goods or services or both to a **SEZ developer or SEZ unit for authorised operations**.
  - ⚠️ VERIFY (amendment nuance, know for MCQs) — w.e.f. **1 October 2023** (Finance Act 2021 provision operationalised via Notification 27/2023-CT), supplies to a SEZ unit/developer are zero-rated **only if made for "authorised operations"** — the supply must be endorsed as such by the Specified Officer of the SEZ; supplies to SEZ not for authorised operations are NOT zero-rated.
  - No IGST/CGST+SGST is charged on the outward zero-rated supply, but the supplier is entitled to **full ITC** of tax paid on inputs/input services used for such supply (unlike an ordinary exempt supply).
- **Concept:** "Zero-rated" ≠ "exempt". Zero-rating removes tax at *both* ends of the chain (output tax is nil AND input tax is fully creditable/refundable); exemption only removes output tax while blocking/reversing input credit.
- **Pitfalls / exam tips:** Students frequently answer "zero-rated = exempt" — this is wrong and a guaranteed mark-loser; always state the ITC-availability distinction explicitly.
- **Definitions:**

| Aspect | Exempt Supply | Zero-Rated Supply |
|---|---|---|
| Output tax | Nil | Nil |
| ITC on inputs used | Not available; must be reversed (Rule 42/43) | Fully available |
| Registration | Not compulsory solely due to exempt supply | Compulsory (as it's a taxable supply at nil effective rate) |
| Refund of accumulated ITC | Not allowed | Allowed |
| Includes | Exempt/nil-rated/non-GST goods & services | Export + supply to SEZ unit/developer (authorised operations) |

### Options for Zero-Rated Supply — Payment Route Choice

- **Key formula(s)/rule(s): Exporter/SEZ-supplier has TWO options** [Section 16(3), IGST Act]:
  1. **Export/supply without payment of IGST**, under a **Bond or Letter of Undertaking (LUT)** — and claim **refund of unutilised ITC**; OR
  2. **Export/supply on payment of IGST** — and claim **refund of the IGST so paid**.
- **Concept:** Both routes achieve zero-rating; Option 1 avoids a cash outflow but needs a Bond/LUT upfront, Option 2 is operationally simpler (shipping bill itself is the refund application) but blocks working capital until refund is processed.
- **Pitfalls / exam tips:** A supply of exempted goods/services when exported, or when supplied to an SEZ unit/developer, is ALSO treated as zero-rated (i.e., the normal exemption is overridden for export/SEZ purposes).

### Letter of Undertaking (LUT) / Bond

- **Key formula(s)/rule(s):**
  - LUT/Bond is furnished in **Form GST RFD-11** [Rule 96A, CGST Rules] before undertaking export without payment of tax, binding the exporter to pay tax + interest if conditions are breached.
  - **LUT is available to ALL registered persons**, EXCEPT those who have been **prosecuted for any offence under the CGST Act/IGST Act/an existing law where the amount of tax evaded exceeds ₹250 lakh** — such persons must furnish a **Bond** instead.
  - A **Bond** must be backed by a **bank guarantee**, which should normally **not exceed 15% of the bond amount** (jurisdictional Commissioner may waive/reduce based on track record) — [Circular No. 8/8/2017-GST].
  - LUT is valid for the **whole financial year** in which it is furnished.
- **Concept:** LUT is the default, low-friction route for genuine exporters; the Bond + bank guarantee route is a safeguard reserved for high-risk/previously-defaulting taxpayers.
- **Pitfalls / exam tips:** Remember the ₹250 lakh figure is about **tax evaded** in a **prosecution**, not merely turnover — a common confusion point in MCQs.
- **Definitions:**

| Term | Meaning |
|---|---|
| LUT | Self-declaration (Form GST RFD-11) allowing export/SEZ supply without upfront IGST payment |
| Bond | Formal undertaking with bank guarantee, required where LUT is not available |

### Time Limit for Export / Consequence of Non-Compliance (Rule 96A)

- **Key formula(s)/rule(s):**
  - **Goods:** must actually be exported within **3 months from the date of issue of the export invoice** (or such further period as the Commissioner allows).
  - **Services:** payment must be received in convertible foreign exchange (or INR where RBI permits) within **1 year from the date of issue of the invoice** for such services (or such further period as the Commissioner allows).
  - If these limits are not met, the exporter must **pay IGST + interest under Section 50(1)** within **15 days** after expiry of the above period; the LUT/Bond-without-payment facility is treated as withdrawn until the amount is paid, and is restored on payment.
- **Concept:** Rule 96A is the enforcement mechanism behind the "export without payment of IGST" option — it converts the zero-rated supply back into a taxable one if the export/realisation does not actually materialise in time.
- **Pitfalls / exam tips:** The 3-month clock (goods) runs from **invoice date**, not shipping bill date or date of LUT — a frequent numerical-question trap.

### Refund of IGST Paid on Export of Goods (Rule 96)

- **Key formula(s)/rule(s):**
  - Where goods are exported **on payment of IGST**, the **shipping bill filed by the exporter is itself deemed to be an application for refund of IGST** [Rule 96, CGST Rules] — no separate RFD-01 application needed for this route.
  - Refund is processed automatically once: (a) the person in charge of the conveyance files an **Export General Manifest (EGM)/export report**, and (b) the exporter has filed a valid **GSTR-3B/GSTR-1** for the relevant period showing the export details/IGST paid matches.
- **Concept:** This is the "automatic refund route" — designed to be faster than the standard RFD-01 refund-application process used for the LUT/unutilised-ITC route.
- **Pitfalls / exam tips:** Refund is withheld/not processed if the exporter has defaulted in furnishing returns, or is under a risk-flag by Customs, or is covered by specific restriction notifications for the relevant period.

### Refund of Unutilised ITC on Zero-Rated Supply (Rule 89(4))

- **Key formula(s)/rule(s):**
$$
\text{Refund Amount} = \frac{\text{Turnover of zero-rated supply of goods and services}}{\text{Adjusted Total Turnover}} \times \text{Net ITC}
$$
  - **Net ITC** = ITC availed on inputs and input services during the relevant period (as per the statutory definition under Rule 89(4)).
  - **Turnover of zero-rated supply of goods** is capped at **1.5 times the value of like goods domestically supplied** by the same or similarly-placed supplier, where applicable, to curb over-invoicing of exports.
  - **Adjusted Total Turnover** = turnover in the State/UT (per Section 2(112), CGST Act), excluding value of exempt supplies other than zero-rated supplies, during the relevant period.
- **Concept:** This is the refund formula used ONLY for the "export/supply without payment of IGST" route (LUT/Bond) — it proportionately releases the ITC that has accumulated because no output tax was charged.
- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — Rule 89(4A) (deemed export supplies received) and Rule 89(4B) (supplies received at concessional/notified rate, e.g. merchant-exporter inward supply) along with **Rule 96(10)** (restriction on IGST-refund route for those availing specified duty-exemption/concessional benefits on inputs) were **omitted w.e.f. 8 October 2024** by **Notification No. 20/2024-Central Tax** — students preparing for 2026 attempts should treat these restrictions as removed (this is a high-yield recent amendment).
  - Do not confuse Rule 89(4) (zero-rated supply, general) with Rule 89(4B) pre-omission (special formula that used to apply where inputs were procured at concessional/nil rate, e.g., merchant exports) — the latter no longer applies post 8-10-2024.

### Deemed Exports

- **Key formula(s)/rule(s):**
  - **Section 147, CGST Act** empowers the Government to notify certain supplies of goods (made within India, not physically leaving India) as **"deemed exports"**, where consideration is received in INR or convertible foreign exchange.
  - Notified deemed export categories (Notification No. 48/2017-CT) include: supply of goods against **Advance Authorisation**, supply of capital goods against **EPCG Authorisation**, and supply of goods to an **Export Oriented Unit (EOU)**.
  - Refund of tax paid on deemed export supplies may be claimed by **either the supplier or the recipient** (only one of them, as per prescribed conditions and declaration).
- **Concept:** Deemed exports remain taxable (unlike true zero-rated exports) but are refund-eligible to preserve the export-promotion/duty-free-input-sourcing benefit for schemes like Advance Authorisation/EPCG/EOU.
- **Pitfalls / exam tips:** Deemed exports are **not** zero-rated supplies — GST is charged normally at the time of supply; only the *refund* mechanism is special. Don't classify them under Section 16 IGST Act.
- **Definitions:**

| Term | Meaning |
|---|---|
| Deemed Export [Sec 147, CGST Act] | Notified domestic supply of goods (goods do not leave India) treated as export only for refund purposes |
| EOU | Export Oriented Unit — approved unit obligated to export a specified portion of production |

### Merchant Exporter — Concessional Rate Scheme

- **Key formula(s)/rule(s):**
  - Registered supplier may supply goods to a registered **merchant exporter** at a **concessional GST rate of 0.1%** (0.05% CGST + 0.05% SGST/UTGST for intra-State, or 0.1% IGST for inter-State) [Notification No. 40/2017-CT(Rate) & 41/2017-IT(Rate) dated 23.10.2017].
  - **Key conditions:** goods must be exported **within 90 days from the date of issue of the tax invoice** by the registered supplier; the merchant exporter must be registered with an Export Promotion Council/Commodity Board; goods must move directly from the supplier's place of business to the port/ICD/airport/land customs station (or via a registered warehouse) for export; the supplier's GSTIN and tax invoice number must be indicated on the shipping bill/bill of export.
  - If goods are **not exported within 90 days**, the concessional rate benefit is denied and the registered supplier becomes liable to pay the **normal/differential GST** (the merchant exporter is expected to intimate the jurisdictional officer if timelines slip).
- **Concept:** The scheme reduces cash-flow blockage for merchant exporters (who buy only to export, without adding value) by letting them procure at a nominal 0.1% GST instead of full-rate GST followed by a refund claim.
- **Pitfalls / exam tips:** The 90-day clock again runs from the **supplier's tax invoice date**, mirroring the Rule 96A logic — examiners like to test both together in the same numerical problem.

### Supplies to SEZ Unit / Developer

- **Key formula(s)/rule(s):**
  - Supply of goods or services to a SEZ unit or SEZ developer, **for authorised operations**, is a zero-rated supply [Section 16, IGST Act as amended, effective 1-10-2023 per Notification 27/2023-CT] — eligible for the same two options (LUT/refund of ITC, or pay IGST/claim refund) as regular exports.
  - Supply **by** an SEZ unit/developer to a Domestic Tariff Area (DTA) unit is treated as an **import** by the DTA recipient (liable to IGST + applicable Customs duties on clearance, per SEZ Act read with Customs Act).
- **Concept:** SEZs are treated as if they are outside the customs territory of India ("deemed foreign territory") for GST purposes — hence supplies into an SEZ (for authorised ops) are zero-rated exports, and supplies out of an SEZ into India proper are imports.
- **Pitfalls / exam tips:** Since the 2023 amendment, don't automatically zero-rate every SEZ supply — check that it is for "authorised operations" and duly endorsed; supplies to SEZ for non-authorised purposes are taxed normally.

### References
1. Section 2(5), 2(6), 2(10), 2(11), 2(112), 16 — Integrated Goods and Services Tax Act, 2017.
2. Rule 89(4), Rule 96, Rule 96A — Central Goods and Services Tax Rules, 2017 (as amended); Section 147 — CGST Act, 2017.
3. Notification No. 20/2024-Central Tax, dated 08.10.2024 (omission of Rules 89(4A), 89(4B) & 96(10)) — CBIC; Notification No. 27/2023-Central Tax (SEZ "authorised operations" condition, Finance Act 2021 amendment to Sec. 16 IGST Act, effective 01.10.2023).
4. Notification No. 40/2017-Central Tax (Rate) & 41/2017-Integrated Tax (Rate), dated 23.10.2017 — concessional 0.1% GST rate for merchant exporters; Notification No. 48/2017-Central Tax — deemed export categories.
5. Circular No. 8/8/2017-GST, dated 04.10.2017 — LUT/Bond procedure, bank guarantee (15% of bond amount) — CBIC.

## 06. Electronic Commerce Transactions and TCS

> **Where it fits:** GST treats sales/services routed through an e-commerce platform differently from a normal B2C sale — either the platform (ECO) itself becomes the deemed supplier for certain notified services [Section 9(5)/5(5)], or the platform must collect tax at source (TCS) on behalf of the actual suppliers selling through it [Section 52]. This chapter also covers the registration and penalty consequences that flow from these two mechanisms.

### Electronic Commerce Operator (ECO) — Basic Definitions

| Term | Meaning |
|---|---|
| Electronic Commerce | Supply of goods or services, including digital products, over a digital or electronic network [Section 2(44), CGST Act] |
| Electronic Commerce Operator (ECO) | Any person who owns, operates, or manages a digital or electronic facility/platform for electronic commerce [Section 2(45), CGST Act] |
| Net value of taxable supplies | Aggregate value of taxable supplies of goods/services (other than services notified u/s 9(5)) made by registered suppliers through the ECO during a month, **less** the aggregate value of taxable supplies returned to suppliers during that month |

**Concept:** An ECO can play two very different roles under GST — (a) a mere aggregator/marketplace collecting TCS on supplies made by *other* registered suppliers through it (Section 52), or (b) the **deemed supplier itself**, made fully liable to pay GST on specified notified services (Section 9(5) CGST / 5(5) IGST). A student must first classify the transaction correctly before applying either mechanism — they are mutually exclusive for the same supply.

**Pitfalls / exam tips:**
- Do not apply TCS (Section 52) and Section 9(5) deemed-supplier liability to the *same* supply — Section 9(5) supplies are specifically excluded while computing "net value of taxable supplies" for TCS.
- ECO does not need to be based in India to be covered — if it does not have a physical presence in the taxable territory, its agent/representative in India is liable in its place (or it must appoint one).

---

### Section 9(5) CGST Act / 5(5) IGST Act — ECO as Deemed Supplier (Notified Services)

- **Key rule:** For services notified under Section 9(5), the ECO is treated **as if it is the supplier** liable to pay tax, in place of the actual (unregistered) service provider — all provisions of the Act apply to the ECO as though it were the supplier.
- **Notified services** (as notified by Government on Council's recommendation):
  1. Passenger transportation services by radio-taxi, motor cab, maxi-cab, motorcycle, or any other motor vehicle (e.g., Ola, Uber, Rapido)
  2. Accommodation services in hotels, inns, guest houses, clubs, campsites, etc. for residential/lodging purposes — where the person supplying such service through the ECO is not liable for registration under Section 22(1) (e.g., OYO, Airbnb-hosted unregistered hosts)
  3. Housekeeping services, e.g., plumbing, carpentering — where the person supplying such service through the ECO is not liable for registration (e.g., Urban Company)
  4. Restaurant services — **except** restaurant services supplied from a "specified premises" (see below)

**Concept:** These are the classic "gig/aggregator" services where the actual provider is typically small/unregistered — GST law shifts full tax liability onto the platform to ease collection and prevent revenue leakage.

**Pitfalls / exam tips:**
- ITC is **not available** to the underlying service provider on these Section 9(5) supplies (the ECO discharges tax as if it were the supplier and takes credit in its own hands).
- The actual service provider still enjoys threshold-exemption from registration on this specific supply (registration of the *provider* is not triggered merely because the supply is routed through ECO under 9(5)) — but the ECO itself must compulsorily register (no threshold) to discharge this liability.
- ⚠️ VERIFY — item (2)/(3) in the OCR ("housekeeping services i.e. plumbing… local delivery services") suggested a possible 5th/6th notified category (e.g., "local delivery services"); confirm against the current consolidated notification (as amended) for the applicable assessment year before quoting it as a notified category in the exam.

---

### Restaurant Services & "Specified Premises" Exception

- **Rule:** Where restaurant services are supplied through an ECO **from a specified premises**, the liability to pay GST remains with the restaurant/supplier itself (normal forward charge) — Section 9(5) does **not** apply, and the ECO merely collects TCS under Section 52 instead.
- **Specified premises** = premises from which the supplier has provided "hotel accommodation" service having a value of supply of any unit of accommodation **above ₹7,500 per unit per day** (or equivalent) at any time during the preceding financial year, **or** premises for which the supplier has filed a declaration opting to be a "specified premises" for the current financial year.

**Concept:** This carve-out keeps GST liability with well-established/registered hotel-restaurants (who can validly opt in/out) while routing smaller/standalone restaurant aggregator sales through the ECO's Section 9(5) liability.

**Pitfalls / exam tips:**
- The earlier "declared tariff" concept has been replaced by actual value of supply/opt-in declaration — do not use the old "declared tariff" terminology in current-syllabus answers.
- Remember the ₹7,500 threshold is **per unit of accommodation per day**, not an aggregate turnover limit.

---

### Tax Collection at Source (TCS) under Section 52

**Key formula:**

$$
\text{TCS Collectible} = \text{Net Value of Taxable Supplies} \times \text{Rate}
$$

$$
\text{Net Value of Taxable Supplies} = \left(\begin{array}{l}\text{Aggregate value of taxable supplies of goods/services} \\ \text{(other than services notified u/s 9(5)) made through the} \\ \text{ECO by all registered suppliers during the month}\end{array}\right) - \left(\begin{array}{l}\text{Aggregate value of taxable supplies} \\ \text{returned to the suppliers during} \\ \text{that month}\end{array}\right)
$$

- **Rate of TCS (w.e.f. 10-07-2024, Notification No. 15/2024-Central Tax):** 0.5% overall — 0.25% CGST + 0.25% SGST/UTGST for intra-State supplies, or 0.5% IGST for inter-State supplies. (Rate was 1% — 0.5%+0.5%, or 1% IGST — for periods before 10-07-2024; use the rate applicable to the period in the question.)
- Maximum rate permitted by the statute itself is 1% (Section 52(1)) — the notified rate can be anywhere up to this ceiling.
- **When TCS applies:** Only where the ECO collects the consideration on behalf of the supplier (i.e., "operator" model, not a pure "agent" who buys/sells on its own account — an agent selling on its own account is a normal taxable supplier, not subject to TCS on itself).
- **Timing:** TCS is collected with reference to the *month in which the supply is made* through the ECO, **irrespective of the month in which payment/consideration is actually collected** by the ECO (e.g., supply made in May, consideration collected in July → TCS relates to May).
- **Payment to Government:** Amount collected as TCS must be paid to the Government **within 10 days after the end of the month** in which the collection was made (Section 52(3)) — must be paid in cash (electronic cash ledger), not through ITC.
- **TCS not required to be collected on:**
  - Supplies of services notified under Section 9(5) (ECO already discharges full tax as deemed supplier).
  - Supplies made through the ECO by an **unregistered person** exempted from registration for intra-State supply of goods per Notification No. 34/2023-CT (turnover below threshold, single State, no inter-State supply, valid PAN + enrolment number) — effective 01-10-2023.
  - Supplies of goods made through the ECO by a **composition taxpayer** for intra-State supply per Notification No. 37/2023-CT — effective 01-10-2023 (ECO must still report these supplies in GSTR-8, just without collecting TCS).

**Concept:** Section 52 makes the ECO a tax-collection intermediary (similar to TCS/TDS under Income-tax) — it collects a small % of the sale value upfront from suppliers and deposits it with Government; the supplier later claims credit of this TCS in its electronic cash ledger while discharging its own output tax liability.

**Pitfalls / exam tips:**
- TCS is deposited/credited to the **supplier's electronic cash ledger** (not credit ledger) — the supplier uses it like an advance tax payment, matched against the statement (GSTR-8) filed by the ECO.
- Net value excludes the value of supplies *returned*, not merely cancelled orders before dispatch — read the numbers carefully in problems.
- ⚠️ VERIFY — the OCR referenced a "matching mechanism" between ECO's GSTR-8 and supplier's GSTR-1/GSTR-3B with discrepancies added back to the supplier's output liability if unrectified; the underlying statutory matching provisions (old Section 52(9)/(10)/(11)) have largely been omitted from the Act — confirm current-syllabus status before relying on "matching/discrepancy" mechanics in an answer.

---

### Registration Requirements

- **Every ECO required to collect TCS under Section 52** must obtain **compulsory registration** — **no threshold exemption** applies [Section 24(x)], regardless of its own turnover.
- **Every person (other than one supplying only Section-9(5)-notified services) who supplies goods or services through an ECO that is required to collect TCS** must also obtain **compulsory registration** [Section 24(ix)] — **except**:
  - A supplier of **services** (not goods) through an ECO is entitled to the normal threshold exemption (₹20 lakh / ₹10 lakh special category) if not making inter-State supply — per Notification No. 65/2017-CT.
  - An **unregistered person** and a **composition taxpayer** supplying **goods** (not services) intra-State only through an ECO are exempted from compulsory registration for this purpose, subject to the conditions of Notification Nos. 34/2023-CT and 37/2023-CT respectively (see above).
- ECO must **not allow any inter-State supply of goods** by an unregistered person or a composition taxpayer through its platform — such supplies must remain intra-State only.
- A supplier of the notified Section 9(5) services *through* an ECO is **not** required to register merely because of that supply (the ECO bears the tax liability instead) — ordinary threshold-based registration rules (Section 22/23) apply to any of the supplier's other independent supplies.

**Concept:** The law distinguishes "goods" from "services" and "registered/composition" from "wholly unregistered" suppliers when deciding whether routing a sale through an ECO forces compulsory registration — always check what is being supplied (goods vs. services) and whether the 2023 relaxation notifications apply before concluding registration is mandatory.

**Pitfalls / exam tips:**
- A very common trap: "Composition dealer wants to sell online" — under current law this is now **permitted for goods, intra-State only**, via Notification 37/2023-CT; it is **not** an absolute bar anymore (pre-2023 position was an absolute bar — do not apply the old rule to current-syllabus questions).
- Composition suppliers remain barred from making inter-State supplies in general (Section 10) — this restriction continues even when selling through an ECO.

---

### Returns, Payment & Statutory Compliance for ECO

- **Statement of outward supplies:** Every ECO required to collect TCS must furnish a monthly statement, electronically, in **FORM GSTR-8**, containing details of outward supplies of goods/services (including supplies returned) made through it and the amount of TCS collected.
- **Due date for GSTR-8:** On or before the **10th day of the month succeeding** the month in which the collection was made [Section 52(4)].
- **Payment of TCS:** Within **10 days** after the end of the month of collection, deposited in cash (electronic cash ledger) — Section 52(3).
- **Annual statement:** ECOs are also required to furnish an annual statement (FORM GSTR-9B) for the financial year by the prescribed due date [Section 52(5)] — ⚠️ VERIFY — confirm from the latest CBIC notifications/press releases whether filing of GSTR-9B has been kept optional/deferred for the year(s) tested in the current exam attempt.
- **Rectification:** If the ECO discovers any error/omission in a statement already furnished (other than as a result of scrutiny/audit), it may rectify it in the statement for the month in which the error is noticed, but **not later than 30th November following the end of the relevant financial year**, or the actual date of furnishing the relevant annual statement, whichever is earlier.

**Concept:** GSTR-8 is the ECO's return which feeds each registered supplier's electronic cash ledger; suppliers can claim credit of TCS reflected there while discharging their own output tax through their monthly return.

**Pitfalls / exam tips:**
- Note the parallel with the supplier's own return timelines — TCS credited to cash ledger is available to the supplier only after the ECO has correctly furnished its GSTR-8.
- The rectification deadline (30th November of the following FY) mirrors the general amendment-window logic used elsewhere in GST law (e.g., credit notes, ITC amendment) — a useful memory anchor.

---

### Penalty Provisions — Section 122(1B)

**Key rule (penalty formula):**

$$
\text{Penalty} = \max\big(\, \text{₹}10{,}000,\ \ \text{Amount of tax involved (as regular/non-composition rate)} \,\big)
$$

- Applies specifically to an **ECO who is required to collect TCS under Section 52**, where the ECO:
  1. Allows a supply of goods or services through it by a person who is **not registered**, other than a person exempted from registration by notification;
  2. Allows an **inter-State supply** of goods or services through it by a person who is **not eligible** to make such inter-State supply (e.g., a composition taxpayer); or
  3. Fails to furnish **correct and complete details** in the statement (FORM GSTR-8) of an outward supply made through it by a person exempted from obtaining registration.
- The "amount of tax involved" is computed as if the supply were made by a person paying tax at the regular (non-composition) rate.

**Concept:** This penalty makes the ECO an active gatekeeper — it is directly penalised for facilitating non-compliant (unregistered/ineligible inter-State) sales through its own platform, not just for its own TCS defaults.

**Pitfalls / exam tips:**
- The penalty is the **higher of** ₹10,000 or the tax amount — students frequently just write "₹10,000" and miss the "or tax involved, whichever is higher" alternative.
- Finance (No. 2) Act, 2024 clarified/restricted Section 122(1B) to apply only to ECOs who are required to collect TCS u/s 52 — do not extend this penalty to every ECO indiscriminately.

---

### References
1. Section 52, CGST Act, 2017 (TCS by e-commerce operator) — CBIC Tax Information Repository, https://taxinformation.cbic.gov.in
2. CBIC Notification No. 15/2024-Central Tax (TCS rate reduced to 0.5% w.e.f. 10-07-2024)
3. Section 9(5), CGST Act, 2017 and Notification No. 17/2021-CT(Rate) (restaurant services/specified premises; notified services list)
4. CBIC Notification Nos. 34/2023-CT and 37/2023-CT (special procedure/exemption for unregistered persons and composition taxpayers supplying goods intra-State through ECO, effective 01-10-2023)
5. Section 24(ix)/(x), CGST Act, 2017 (compulsory registration for ECO and suppliers through ECO) and Notification No. 65/2017-CT (threshold exemption for service suppliers through ECO)
6. Section 122(1B), CGST Act, 2017 (penalty for ECO), as amended by Finance (No. 2) Act, 2024

## 07. Registration

> **Where it fits:** Once a person crosses the threshold (or falls under a compulsory-registration category under Sections 22-24), Sections 25-30 of the CGST Act govern *how* registration is obtained, amended, suspended, cancelled and revoked — this chapter is entirely procedural/timeline-driven, which makes it high-yield for MCQs and short-answer questions on "within how many days."

### Procedure for Registration — Section 25 r/w Rules 8-10

- **Key formula(s)/rule(s):**

$$
\text{Application} \to \text{Part-A (PAN + mobile/e-mail OTP)} \to \text{TRN generated} \to \text{Part-B (documents + Aadhaar authentication)} \to \text{ARN generated}
$$

- Application is made electronically in **FORM GST REG-01** on the common portal.
- A **Temporary Reference Number (TRN)** is generated after Part-A verification; Part-B (with supporting documents) must be filled using the TRN.
- Where the applicant opts for **Aadhaar authentication**, it must be completed for the Primary Authorised Signatory and at least one Partner/Karta/Managing Director/whole-time Director/Member of Managing Committee (as applicable).
- **Effective date of registration (Rule 10):** date of grant, if application is submitted within **30 days** from the date on which the person becomes liable to register; otherwise the effective date is the **date of grant of registration**.
- **Concept:** This is the digital, faceless onboarding process — TRN and ARN are the two tracking numbers a student must not confuse (TRN = before submission, ARN = after submission/acknowledgment).
- **Pitfalls / exam tips:**
  - TRN is valid only for completing Part-B; it is not proof of registration.
  - "Within 30 days of becoming liable" is the key line tested for effective date of registration — miss it and registration is effective only from grant date (no retrospective benefit, and tax is payable as an unregistered person for the gap period).

| Term | Meaning |
|---|---|
| TRN | Temporary Reference Number — issued after Part-A |
| ARN | Application Reference Number — issued after full application submission |

---

### Verification and Time Limit for Grant of Registration — Rule 9

- **Key formula(s)/rule(s):**

$$
\text{Registration granted within } 7 \text{ working days from date of submission} \iff \text{Aadhaar authentication successful AND no risk flag on data-analysis}
$$

$$
\text{Registration granted within } 30 \text{ days from date of submission} \iff \text{Aadhaar authentication not opted/failed, OR applicant flagged on risk parameters (physical verification of place of business required)}
$$

$$
\text{No action by proper officer within the applicable period} \Rightarrow \text{Registration deemed approved}
$$

- If the proper officer requires clarification, a notice is issued in **FORM GST REG-03**; the applicant must reply in **FORM GST REG-04** within **7 working days**; the officer must then act within a further **7 working days** of receiving the reply (else deemed approved).
- Where physical verification is required, the verification report must be uploaded in **FORM GST REG-30** at least **5 working days** before expiry of the 30-day period.
- **Concept:** Rule 9 links the *speed* of registration to Aadhaar authentication + a risk-based (data-analytics) filter — a deliberate anti-fake-invoicing safeguard introduced after large-scale ITC-fraud detections.
- **Pitfalls / exam tips:**
  - Do not default to "3 working days" — that older timeline was replaced; current timelines are 7 working days (Aadhaar-authenticated, no risk) and 30 days (not authenticated / risk-flagged, needs physical verification).
  - Deemed registration is a favourite MCQ trap: officer's silence within the prescribed window = deemed grant, not deemed rejection.

---

### Bank Account Details — Rule 10A

- **Key formula(s)/rule(s):**

$$
\text{Deadline to furnish bank account details} = \min\big(30 \text{ days from grant of registration},\ \text{date of furnishing GSTR-1/IFF, whichever is earlier}\big)
$$

- **Concept:** Registration can be granted without bank details, but the registered person must submit valid bank account details (in their own name, with PAN linked, and Aadhaar/e-KYC verified) within the above window — failure risks suspension/cancellation under Rule 21.
- **Pitfalls / exam tips:** The "whichever is earlier" clause matters — a person who files GSTR-1 on day 10 must give bank details by day 10, not day 30.

---

### Deemed Registration — Section 26

- **Key formula(s)/rule(s):**

$$
\text{Grant/rejection of registration/UIN under CGST Act} \equiv \text{Grant/rejection under SGST/UTGST Act}
$$

- **Concept:** A single registration process serves both CGST and SGST/UTGST authorities — if approved (or deemed approved) under one Act, it is deemed approved under the other, avoiding duplicate scrutiny.
- **Pitfalls / exam tips:** This "deeming fiction" is why a single GSTIN suffices for both Central and State tax administrations at a given place of business.

---

### Casual Taxable Person (CTP) & Non-Resident Taxable Person (NRTP) — Section 27

- **Key formula(s)/rule(s):**

$$
\text{Validity of registration} = \min\big(\text{period applied for},\ 90 \text{ days from effective date of registration}\big)
$$

$$
\text{Extension} \le \text{further } 90 \text{ days (on sufficient cause shown, before expiry of original validity)}
$$

$$
\text{Advance tax deposit} = \text{estimated tax liability for the registration period}\ (+\ \text{additional estimated liability if extension is sought})
$$

- Application for registration must be submitted **at least 5 days prior** to commencement of business.
- The advance tax deposited is credited to the **Electronic Cash Ledger** and used to discharge liability per normal utilisation rules (Section 49).
- **Concept:** CTP = a taxable person who occasionally undertakes transactions in a State/UT where they have no fixed place of business (e.g., an exhibition stall); NRTP = a non-resident who occasionally undertakes transactions but has no fixed place of business or residence in India.
- **Pitfalls / exam tips:**
  - Unlike regular registrants, CTP/NRTP must pay tax **in advance**, before even obtaining the registration certificate — this is the single most-tested distinguishing feature.
  - The extension cap is 90 days *additional* (i.e., maximum total validity = 90 + 90 = 180 days), not a flat "180 days" from the outset.

| Term | Meaning |
|---|---|
| CTP | Person supplying in a State/UT where he has no fixed place of business, occasionally |
| NRTP | Person supplying occasionally, having no fixed place of business or residence in India |

---

### TDS Deductor / TCS Collector Registration — Section 24 r/w Rule 12

- **Key formula(s)/rule(s):**
- Persons liable to deduct tax at source (Section 51) or collect tax at source (Section 52, e-commerce operators) require **compulsory registration** irrespective of turnover.
- Registration is granted (or the department may grant it *suo motu*/"department-driven") based on the **TAN** or PAN, without going through the standard Rule 9 clarification workflow — a distinct application/grant track from regular taxpayers.
- **Concept:** These registrations exist purely to enable TDS/TCS compliance (filing GSTR-7/GSTR-8) and are not linked to a turnover threshold.
- **Pitfalls / exam tips:** A TDS deductor/TCS collector GSTIN does not by itself make the holder liable to pay output tax on its own supplies — that liability (if any) requires a separate normal registration.

---

### Simplified / Fast-Track Registration Scheme — Rule 14A ⚠️ VERIFY — recently inserted provision, cross-check the exact monetary figure and effective date against the CGST Rules in force for your attempt

- **Key formula(s)/rule(s):**

$$
\text{Eligible if } \text{estimated monthly output tax liability on B2B supplies} \le ₹2,50,000
$$

$$
\text{Registration granted within } 3 \text{ working days of successful Aadhaar authentication}
$$

- Only **one registration per State/UT under a given PAN** is permitted under this scheme (no multiple GSTINs within the same State).
- Withdrawal from the scheme (e.g., on breach of the ₹2.5 lakh/month cap) is made in **FORM GST REG-32**, and the officer converts it to a normal registration via **FORM GST REG-33** on the *same* GSTIN.
- **Concept:** This is an *optional*, low-risk, technology-driven fast-track route (inserted via the CGST (Fourth Amendment) Rules, 2025) targeted at small, low-value B2B suppliers, trading off simplicity for a single-registration-per-State restriction.
- **Pitfalls / exam tips:** The ₹2.5 lakh figure is a **tax-liability** ceiling (aggregate of CGST+SGST/UTGST+IGST+cess), not a turnover ceiling — do not confuse it with the Section 22 turnover thresholds.

---

### Amendment of Registration — Section 28 r/w Rule 19

- **Key formula(s)/rule(s):**

$$
\text{Application for amendment within } 15 \text{ days of the event necessitating change}
$$

$$
\text{Proper officer to approve/reject within } 15 \text{ working days of application} \Rightarrow \text{else amendment deemed approved}
$$

- **Non-core fields** (e.g., e-mail ID, mobile number, and other day-to-day/administrative details) can be self-updated by the registered person on the common portal — no departmental approval needed.
- **Core fields** (e.g., legal name of business, address of principal/additional place of business not involving a change of State, addition/deletion of partners/directors/promoters) require submission of **FORM GST REG-14** and approval by the proper officer via **FORM GST REG-15**.
- A change of **PAN** or a change of **State** cannot be carried out as an amendment — the existing registration must be **cancelled** and a **fresh registration** obtained.
- **Concept:** The core/non-core split exists purely to reduce departmental workload — only changes with revenue/jurisdiction significance are routed through officer approval.
- **Pitfalls / exam tips:** "Change in constitution of business resulting in change of PAN" is a classic trick statement — students often try to "amend" it; the correct answer is always cancel + fresh registration.

---

### Cancellation of Registration — Section 29 r/w Rule 21 & 22

- **Key formula(s)/rule(s):**
- **Voluntary cancellation:** by the registered person himself (e.g., business discontinued/transferred, change in constitution, no longer liable to register under Section 22/24).
- **Cancellation by proper officer** (Section 29(2)) — may be from any date, including a **retrospective date**, in these circumstances:
  - Registered person contravenes specified provisions of the Act/Rules (Rule 21), including: not conducting business from the declared place of business; issuing invoices/bills without actual supply of goods or services (bogus invoicing); violating the anti-profiteering provisions of Section 171; not furnishing bank account details within the time prescribed under Rule 10A; availing input tax credit in violation of Section 16 or the rules; furnishing outward-supply details in GSTR-1 in excess of GSTR-3B for the corresponding period(s); violating restrictions on utilisation of ITC in the electronic credit ledger under Rule 86B.
  - **Composition taxpayer** has not furnished the return for a financial year beyond **3 months** from its due date.
  - **Regular taxpayer** has not furnished returns for a continuous period as prescribed under Rule 21 — **6 months** for monthly return filers, **2 tax periods** (quarters) for QRMP/quarterly filers.
  - Voluntarily-registered person has not commenced business within **6 months** from the date of registration.
  - Registration was obtained by fraud, wilful misstatement, or suppression of facts.
- **Concept:** Cancellation ends the GSTIN's operative status going forward (or retrospectively); it does not extinguish liabilities/proceedings that arose while registered (Section 29(3)).
- **Pitfalls / exam tips:**
  - "3 consecutive tax periods" for composition dealers was replaced (Finance Act 2022, effective 1.10.2022) by "return for a FY beyond 3 months from due date" — an old-syllabus figure students often still quote incorrectly.
  - Continuous non-filing threshold differs by filing frequency: 6 months (monthly) vs 2 tax periods (quarterly) — a frequently tested distinction.

---

### Suspension of Registration — Rule 21A

- **Key formula(s)/rule(s):**

$$
\text{Suspension effective date} = \max\big(\text{date of application for cancellation},\ \text{date from which cancellation is sought}\big)
$$

(where suspension arises on the registered person's own application for cancellation); alternatively, suspension takes effect from the date of issue of the show-cause notice (**FORM GST REG-17**) where initiated suo motu by the proper officer.

- **Concept:** Suspension is an *interim freeze* pending the outcome of cancellation proceedings — a suspended person cannot make any taxable supply (cannot issue a tax invoice) and need not file returns for the suspension period, but existing liabilities remain payable.
- **Pitfalls / exam tips:** Suspension ≠ cancellation — GSTIN continues to exist and can be revived if the officer decides not to cancel (order revoking suspension issued in **FORM GST REG-20**).

---

### Revocation of Cancellation — Section 30 r/w Rule 23

- **Key formula(s)/rule(s):**

$$
\text{Application for revocation within } 90 \text{ days from date of service of the cancellation order}
$$

$$
\text{Extendable by Additional/Joint Commissioner by up to a further } 180 \text{ days on sufficient cause} \Rightarrow \text{maximum } 270 \text{ days total}
$$

- Available only where registration was cancelled **suo motu by the proper officer** (not where the registered person applied for voluntary cancellation).
- All returns due for the period up to the date of cancellation must be furnished, along with payment of any tax/interest/penalty/late fee, **before** applying for revocation.
- Revocation is barred where cancellation was on account of failure to file returns *unless* the defaulting returns (and dues) are filed first.
- **Concept:** Revocation restores the GSTIN retrospectively to active status, as if it was never cancelled, correcting an officer-initiated cancellation once the underlying default is cured.
- **Pitfalls / exam tips:** The time limit was increased from **30 days to 90 days** by the Finance Act 2023 (effective 1.10.2023), with the extension power vesting in the Additional/Joint Commissioner (up to 180 more days) — do not quote the pre-2023 "30-day" figure.

---

### Non-Resident Taxable Person (NRTP) — Key Forms

| Form | Purpose |
|---|---|
| GST REG-09 | Application for registration by a Non-Resident Taxable Person |
| GST REG-06 | Registration certificate issued on grant of registration |
| GST REG-14 | Application for amendment (core fields) |
| GST REG-16 | Application for cancellation of registration |
| GST REG-17 | Show-cause notice for cancellation (suo motu) |
| GST REG-20 | Order dropping proceedings / revoking suspension |
| GST REG-21 | Application for revocation of cancellation |
| GST REG-22 | Order revoking cancellation of registration |

*(⚠️ VERIFY — the source page contained an unreadable/garbled listing purportedly running from GST REG-01 through GST REG-504; there is no such range of forms under the CGST Rules. The table above lists only the genuine, currently notified GST REG-series forms relevant to this chapter — cross-check the complete official list in Rule 10 / Notified Forms if a question names a specific form number not shown here.)*

---

### Unique Identification Number (UIN) — Section 25(9) r/w Rule 17

- **Key formula(s)/rule(s):**

$$
\text{Application (FORM GST REG-13)} \to \text{Recommendation from Ministry of External Affairs (MEA), Government of India} \to \text{UIN granted within } 3 \text{ working days of application}
$$

- UIN is granted to: (a) any specialised agency of the UNO or a multilateral financial institution/organisation notified under the UN (Privileges and Immunities) Act, 1947, a Consulate or Embassy of a foreign country, and (b) any other person(s) notified by the Commissioner.
- **Concept:** UIN-holders are not "taxable persons" transacting business — the UIN exists solely so they can claim a **refund of tax paid on their inward supplies** (Section 55).
- **Pitfalls / exam tips:** Do not confuse UIN with a regular GSTIN — a UIN holder generally does not charge/collect tax on outward supplies; its entire purpose is refund of tax borne on purchases.

### References

1. CBIC — CGST Rules, 2017, Rule 9 (Verification of application and approval) — taxinformation.cbic.gov.in.
2. CA Club India — "Simplified GST Registration Scheme under Rule 14A of the CGST Rules, 2017" (CGST Fourth Amendment Rules, 2025, effective 1.11.2025).
3. CA Club India / GST Gyaan — Section 27 CGST Act, Special provisions for Casual and Non-Resident Taxable Person (90-day validity, extension, advance tax deposit).
4. TaxGuru — Analysis of Section 29(2)(c) CGST Act, amendment via Finance Act 2022 (effective 1.10.2022) on continuous-period return-default triggers for cancellation.
5. CA Club India / ClearTax — Section 30 CGST Act, Finance Act 2023 amendment increasing revocation application period from 30 to 90 days (effective 1.10.2023), extendable up to 180 additional days.

## 08. Tax Invoice, Credit/Debit Notes, Accounts & Records and E-Way Bill
> **Where it fits:** This chapter covers the *documentation trail* of GST compliance — the tax invoice and its variants (bill of supply, receipt/refund/payment voucher, revised invoice, delivery challan), price-adjustment documents (credit/debit notes), e-invoicing, the books a registrant must keep and for how long, and the e-way bill that must accompany the physical movement of goods.

### Tax Invoice — Basics, Time Limit & Contents (Section 31, Rules 46–47)

- **Key formula(s)/rule(s):**
  - Time limit for issuing tax invoice:
$$
\text{Supply of Goods (with movement)} \Rightarrow \text{Invoice} \le \text{time of removal}
$$
$$
\text{Supply of Goods (no movement)} \Rightarrow \text{Invoice} \le \text{time of delivery / making available}
$$
$$
\text{Supply of Services} \Rightarrow \text{Invoice} \le 30 \text{ days from date of supply of service}
$$
$$
\text{Insurer / Banking Co. / FI / NBFC} \Rightarrow \text{Invoice} \le 45 \text{ days from date of supply}
$$
  - HSN digits on invoice (Notification 78/2020-CT):
    - Aggregate turnover **up to ₹5 crore** in preceding FY → **4-digit** HSN mandatory on B2B tax invoices (optional on B2C).
    - Aggregate turnover **more than ₹5 crore** → **6-digit** HSN mandatory on **all** tax invoices (B2B and B2C).
  - Number of copies: Goods supply → **triplicate** (Original-Recipient, Duplicate-Transporter, Triplicate-Supplier); Services supply → **duplicate** (Original-Recipient, Duplicate-Supplier).
  - Invoice serial number: consecutive, unique for a financial year, not exceeding **16 characters**, in one or multiple series.
  - Insurer/banking company/FI/NBFC and passenger transport agency: may issue a consolidated tax invoice/statement at the end of the month, and need not show recipient's address/serial number restriction in the same manner as a normal invoice.

- **Concept:** Section 31 fixes *when* a registered person supplying taxable goods/services must issue the invoice, and Rule 46 prescribes the *mandatory particulars* (supplier's/recipient's name, address, GSTIN/UIN, invoice no. & date, HSN/SAC, description, quantity, taxable value, rate & amount of tax, place of supply, signature, etc.).

- **Pitfalls / exam tips:**
  - Do not confuse "time of supply" (which fixes the tax period) with "time limit to issue invoice" (a Section 31 compliance requirement) — they interact but are conceptually distinct.
  - The 45-day limit is a **specific relaxation** only for insurer/banking company/FI/NBFC — everyone else gets 30 days.
  - HSN digit requirement is turnover-based, not supply-type based; check the *preceding* FY's aggregate turnover.

- **Definitions:**

| Term | Meaning |
|---|---|
| Aggregate Turnover | All-India turnover (taxable + exempt + export + inter-State supplies) of a person having the same PAN, excluding inward RCM supplies and taxes |
| HSN/SAC | Harmonised System of Nomenclature (goods) / Services Accounting Code |

---

### Bill of Supply, Receipt/Refund/Payment Voucher & Consolidated Invoice (Section 31(3), Rule 49)

- **Key formula(s)/rule(s):**
  - **Bill of Supply** — issued instead of tax invoice by: (a) a registered person supplying **exempted** goods/services, or (b) a person paying tax under the **composition scheme**.
  - **Consolidated tax invoice/bill of supply**: may be issued at the close of each day for all unregistered-recipient supplies where the invoice value is **less than ₹200** and the recipient does not require an invoice.
  - Document triggers on various events:

| Event | Document |
|---|---|
| Receipt of advance | Receipt Voucher |
| Refund of advance (no supply made) | Refund Voucher |
| Payment under Reverse Charge Mechanism (RCM) from unregistered supplier | Self-Invoice (inward) + Payment Voucher |

  - Where a supplier makes both taxable and exempt supplies to an unregistered person, a **single "invoice-cum-bill of supply"** may be issued for both, instead of separate documents.

- **Concept:** These are the alternate/supplementary documents GST prescribes for situations where a plain tax invoice does not fit — no tax on exempt/composition supply, advance receipts, or reverse-charge self-assessment.

- **Pitfalls / exam tips:**
  - Self-invoice + payment voucher under RCM is mandatory **only** when the supplier is **unregistered** (Section 31(3)(f)/(g)); for RCM supplies from a registered supplier, the registered supplier's own tax invoice is used and only a payment voucher is needed by the recipient.
  - The ₹200 consolidated-invoice threshold applies **per supply**, not per day's aggregate.

---

### Revised Tax Invoice & Delivery Challan (Section 31(3)(a), Rules 53 & 55)

- **Key formula(s)/rule(s):**
$$
\text{Revised Invoice must be issued} \le 1 \text{ month from date of issuance of Registration Certificate (RC)}
$$
  - Covers all tax invoices already issued during the period from the **effective date of registration** up to the **date of issuance of RC** (available only where application for registration was filed within the time limit prescribed, i.e., within 30 days of becoming liable).
  - **Delivery Challan** (Rule 55) is used in lieu of a tax invoice for: supply of liquid gas where quantity is unknown at removal, transportation of goods for job work, transportation for reasons other than supply (e.g. goods sent on approval), and other notified supplies.

- **Concept:** A revised invoice "regularises" the tax position for the gap between becoming liable to register and actually getting the registration certificate.

- **Pitfalls / exam tips:** A consolidated revised invoice may be issued for intra-State supplies to unregistered recipients (invoice-wise consolidation not required); inter-State supplies with invoice value ≤ ₹2,50,000 to unregistered persons may also be consolidated State-wise.

- **Definitions:**

| Term | Meaning |
|---|---|
| Revised Tax Invoice | Invoice issued to update/replace invoices raised between effective date of registration and date of grant of RC |
| Delivery Challan | Non-tax document accompanying goods movement where a tax invoice is not required at that point |

---

### Continuous Supply & Goods Sent on Approval (Section 31(4), 31(5), 31(7))

- **Key formula(s)/rule(s):**
  - **Continuous supply of goods**: invoice at the time each statement of accounts is issued or each payment is received, whichever is earlier.
  - **Continuous supply of services**:
    - Due date of payment ascertainable from contract → invoice **on or before** the due date of payment.
    - Due date not ascertainable → invoice at the time supplier **receives** payment.
    - Payment linked to completion of an event/milestone → invoice **on or before** the date of completion of that event.
  - **Goods sent on approval basis**:
$$
\text{Invoice} \le \min(\text{time of actual supply/acceptance},\ 6 \text{ months from date of removal})
$$

- **Concept:** These rules extend Section 31's basic timing principle to supplies that do not have a single, discrete point of delivery.

- **Pitfalls / exam tips:** For approval-basis goods, the 6-month backstop applies even if the recipient has not yet decided to buy — invoice (or return) is forced at 6 months regardless.

---

### E-Invoicing (Rule 48(4), (5))

- **Key formula(s)/rule(s):**
$$
\text{E-invoicing mandatory if Aggregate Turnover} > ₹5\text{ crore in any preceding FY (from 2017-18 onwards)}
$$
  - Effective **1 August 2023** (Notification No. 10/2023-CT dated 10.05.2023) — the threshold was reduced in stages from ₹500 crore down to ₹5 crore.
  - Applies to: B2B tax invoices, credit notes and debit notes, and export invoices (with/without payment of tax).
  - Process: supplier reports invoice to the **Invoice Registration Portal (IRP)** → IRP validates & returns an **Invoice Reference Number (IRN)** + digitally-signed QR code → this must be printed on the invoice. An invoice not reported to IRP is treated as **not a valid tax invoice**.
  - **Exempt from e-invoicing** even if turnover exceeds ₹5 crore: SEZ **units** (SEZ *developers* are NOT exempt), insurer/banking company/FI/NBFC, GTA, passenger transportation service supplier, supplier of services by way of admission to exhibition of cinematograph films in multiplex screens, and Government departments/local authorities.

- **Concept:** E-invoicing is a real-time, portal-based authentication of B2B invoices designed to curb fake invoicing/ITC fraud; it is layered on top of (not a replacement for) the Section 31 invoice requirement.

- **Pitfalls / exam tips:**
  - Aggregate turnover for this threshold is computed on an **all-India, same-PAN** basis — if any one GSTIN of the PAN crosses ₹5 crore, e-invoicing applies to **all** GSTINs of that PAN (subject to the specific exemptions above).
  - ⚠️ VERIFY — a 30-day reporting time-limit to the IRP (invoice must be reported to IRP within 30 days of invoice date) has been notified for taxpayers with aggregate turnover ≥ ₹10 crore; confirm current applicability/effective date against the latest CBIC advisory before the exam.

---

### Credit Note & Debit Note (Section 34)

- **Key formula(s)/rule(s):**
  - **Credit Note** — issued by supplier where taxable value/tax charged in the tax invoice **exceeds** the taxable value/tax payable (or goods returned, or deficiency in service):
$$
\text{Credit Note must be declared in return} \le \min\!\big(30^{th}\ \text{November following end of FY of supply},\ \text{date of filing Annual Return}\big)
$$
    (Deadline extended from 30th September to **30th November** by the Finance Act, 2022.)
  - **Debit Note** — issued by supplier where taxable value/tax charged in the tax invoice is **less than** the taxable value/tax payable:
$$
\text{Debit Note} \Rightarrow \text{no upper time limit for issuance; declared in return of the month in which it is issued}
$$
  - Tax liability reduction via credit note is subject to a corresponding reduction/reversal of ITC by the recipient (linked through the return/GSTR-2B ecosystem) — the earlier "incidence of tax passed on" bar was recast by the Finance Act, 2022 amendment.
  - A debit note (post the Finance Act 2020 amendment) is **de-linked** from its original invoice — one debit/credit note can be issued for **multiple invoices** issued in a FY.

- **Concept:** Credit/debit notes adjust the value/tax of an already-invoiced supply without needing to reverse and reissue the original invoice.

- **Pitfalls / exam tips:**
  - Students often wrongly apply the November-30 cap to debit notes too — it applies **only to credit notes**.
  - "One document can cover multiple invoices" — a frequently tested MCQ point post-2020 amendment.
  - Financial/commercial credit notes (discounts not linked to Section 15(3) conditions) do **not** reduce GST liability even though issued — they are outside Section 34.

- **Definitions:**

| Term | Meaning |
|---|---|
| Credit Note | Downward adjustment document (value/tax excess charged, sales return, deficiency in supply) |
| Debit Note | Upward adjustment document (value/tax short-charged) |

---

### Accounts & Records (Section 35, Rule 56)

- **Key formula(s)/rule(s):** Every registered person must maintain, at the **principal place of business**, true and correct records of:
  - Production/manufacture of goods
  - Inward and outward supply of goods/services
  - Stock of goods
  - Input tax credit availed
  - Output tax payable and paid
  - Other prescribed particulars (Rule 56): imports/exports, RCM supplies, advances received/paid/adjusted, invoices, credit/debit notes, delivery challans, etc.
  - **Sector-specific additional records (Rule 56):**

| Person | Additional records required |
|---|---|
| Agent | Authorisation particulars, goods/services received or supplied on behalf of principal, details of accounts furnished to principal |
| Manufacturer | Monthly production accounts — quantitative details of raw materials/services used and goods manufactured, including waste and by-products |
| Service provider | Quantitative details of goods used in providing services, input services utilised |
| Works contractor | Names/addresses of persons for whom contract executed, description/value/quantity of goods/services received & used, details of payment received, names/addresses of suppliers |

  - **Warehouse/godown owner-operator and every transporter** (registered or not) must maintain records of consignor, consignee and other relevant goods-movement details — Section 35(2) casts this duty even on unregistered transporters/warehouse-keepers.

- **Concept:** Section 35 is the "books of account" backbone that supports ITC claims, output-tax computation, and audit/assessment verification.

- **Pitfalls / exam tips:** GST audit by a Chartered/Cost Accountant (erstwhile Section 35(5)) stands **omitted** (Finance Act, 2021) — replaced by self-certified reconciliation statement in **GSTR-9C**, applicable currently to registered persons with aggregate turnover above ₹5 crore in the FY.

---

### Period of Retention of Accounts (Section 36)

- **Key formula(s)/rule(s):**
$$
\text{Normal retention period} = 72 \text{ months (6 years) from the due date of furnishing the Annual Return for that year}
$$
$$
\text{If under appeal/revision/investigation} \Rightarrow \text{retain until } 1 \text{ year after final disposal of such proceeding, or the above period, whichever is later}
$$

- **Concept:** Fixes the minimum period for which invoices, registers, and other GST records must be preserved and made available to officers.

- **Pitfalls / exam tips:** The 72-month clock runs from the **due date of the annual return**, not from the date of the transaction or the date the return was actually filed — a commonly tested distinction.

---

### E-Way Bill — Applicability & Consignment Value (Section 68, Rule 138)

- **Key formula(s)/rule(s):**
$$
\text{E-Way Bill required if Consignment Value} > ₹50{,}000
$$
  - Consignment value = value determined under **Section 15** (transaction value), **including** applicable GST/cess, but **excluding** the value of any exempt supply where a single invoice covers both exempt and taxable goods.
  - Trigger events: movement in relation to a supply, movement for reasons other than supply (e.g., branch transfer, return), or inward supply from an unregistered person.
  - **Mandatory irrespective of the ₹50,000 threshold** for: inter-State movement of goods by a principal to a job-worker (Section 143), and inter-State movement of handicraft goods by a person exempted from registration.
  - E-way bill has two parts: **Part-A** (invoice/GSTIN/HSN/value/reason for transport) and **Part-B** (vehicle/transporter details).
  - Part-B may be left blank where the distance between the consignor's/transporter's place of business and the consignee is **up to 50 km** within the same State/UT.
  - Generated by: registered person (as consignor or consignee), the transporter, or (in specified cases) the e-commerce operator/courier agency.

- **Concept:** The e-way bill is the electronic equivalent of a carrier's way-bill, letting the department track movement of goods above a value threshold in real time.

- **Pitfalls / exam tips:** "Movement" is the trigger, not "supply" — stock transfers and job-work movements (with no invoice, only a delivery challan) still need an e-way bill if value crosses ₹50,000 (or is mandatory regardless of value, as above).

- **Definitions:**

| Term | Meaning |
|---|---|
| Consignment Value | Section-15 value of goods in the invoice/bill of supply/delivery challan, including tax, excluding value of any exempt component |
| Part-A | Details of goods/parties in the e-way bill |
| Part-B | Vehicle/transporter details in the e-way bill |

---

### E-Way Bill — Validity Period (Rule 138(10))

- **Key formula(s)/rule(s):**
$$
\text{Validity (normal cargo)} = 1 \text{ day for every } 200 \text{ km (or part thereof)}
$$
$$
\text{Validity (Over Dimensional Cargo / multimodal shipment with a ship leg)} = 1 \text{ day for every } 20 \text{ km (or part thereof)}
$$
  - "Day" is counted from the date/time the e-way bill is generated.
  - Validity may be extended within **8 hours before** to **8 hours after** expiry, on furnishing reasons (transhipment delay, natural calamity, law & order issue, vehicle breakdown, etc.) and updating Part-B — subject to an overall cap.

- **Concept:** Ties the e-way bill's validity window to distance so that goods cannot travel indefinitely under one bill.

- **Pitfalls / exam tips:** Round *up* any part of the 200 km (or 20 km for ODC) slab — e.g., 310 km by normal vehicle = 2 days' validity (1 + 1), not 1.55 days.

---

### E-Way Bill — Exemptions, Blocking & Verification

- **Key formula(s)/rule(s):**
  - **No e-way bill required (Rule 138(14)), inter alia, for:**
    - Non-motorised conveyance
    - Goods under customs supervision/customs seal, or transported from customs port/airport/ICD/CFS for clearance
    - Transit cargo to/from Nepal or Bhutan
    - Empty cargo containers
    - Goods specified in the exempt Annexure — e.g., LPG for household/non-domestic supply, kerosene under the Public Distribution System (PDS), postal baggage transported by the postal department, jewellery/goldsmiths'/silversmiths' wares (Chapter 71) other than imitation jewellery, currency, used personal and household effects, worked/unworked coral
    - Defence formation movements (Ministry of Defence as consignor/consignee)
    - Movement of goods under a delivery challan to/from a weighbridge within 20 km, accompanied by the challan
    - Goods transported by rail where the consignor is Central/State Government or a local authority
  - **Blocking of e-way bill generation (Rule 138E)** — for the person as **consignor** (no restriction on receiving goods as consignee):
    - Composition taxpayer who has not furnished the return (CMP-08/GSTR-4) for **2 consecutive tax periods**
    - Regular taxpayer who has not furnished GSTR-3B / GSTR-1 for **2 consecutive tax periods**
    - Registered person whose registration is **suspended**
    - Commissioner may allow generation on sufficient cause shown.
  - **Verification (Rule 138B/138C):** Commissioner/empowered officer may authorise a proper officer to intercept any conveyance to verify the e-way bill (physically or via RFID); physical verification report (Part A of FORM GST EWB-03) recorded within **24 hours** of inspection, with a final report within **3 days** (extendable by a further **3 days** by the Commissioner for exceptional circumstances). No repeat physical verification of the same conveyance within a State unless specific information of tax evasion is received.
  - **Documents to be carried by the person in charge of the conveyance (Rule 138A):** invoice/bill of supply/delivery challan, and the e-way bill number (physical copy not compulsory if the number can be produced electronically, e.g., via RFID). For imported goods, Bill of Entry details must also be indicated in Part-A of the e-way bill.
  - **Godown of a transporter used as recipient's storage:** movement from supplier to the transporter's godown is covered by an e-way bill; the recipient must declare the transporter's godown as an **additional place of business (APOB)** to avoid a further e-way bill for onward internal movement.

- **Concept:** These provisions cover the "carve-outs" from the e-way bill regime, the consequences of GST-return default, and the field-verification safeguards.

- **Pitfalls / exam tips:** Blocking applies only to generation **as a supplier/consignor**; the same defaulting person can still receive goods (as consignee) with an e-way bill generated by the other party.

### References
1. CBIC Notification No. 10/2023–Central Tax, dated 10.05.2023 (e-invoicing threshold reduced to ₹5 crore w.e.f. 01.08.2023) — cross-checked via Lexology/TaxReply summaries.
2. CGST Rules, 2017, Rule 138 (E-Way Rules), CBIC e-way bill portal document (docs.ewaybillgst.gov.in) — consignment value ₹50,000 threshold and validity (200 km/day; 20 km/day for ODC).
3. CGST Act, 2017, Section 34 as amended by the Finance Act, 2022 — credit note reporting deadline extended to 30th November following end of financial year; debit note has no upper time limit.
4. CGST Act, 2017, Section 36 — retention of accounts for 72 months from due date of furnishing annual return (extended period for pending appeal/revision/investigation).
5. CBIC Notification No. 78/2020–Central Tax, dated 15.10.2020 — mandatory HSN digits (4-digit up to ₹5 crore turnover, 6-digit above ₹5 crore), effective 01.04.2021.

## 09. Payment of Tax, TDS/TCS, Returns & Refunds under GST
> **Where it fits:** After computing output tax and eligible ITC, this chapter covers *how* the liability is actually discharged (electronic ledgers, interest on delay), *who else* must deduct/collect tax at source (TDS/TCS), *how* compliance is reported (returns, QRMP), and *how* excess tax paid comes back to the taxpayer (refunds).

### Electronic Ledgers (Cash, Credit & Liability Register)

- **Key formula(s)/rule(s):**
  - Three ledgers maintained on the GST common portal for every registered person (Section 49 read with Rules 87–88):
    - **Electronic Cash Ledger** — records deposits made via challan (Form **GST PMT-06**) and all cash payments of tax/interest/penalty/fee/other amounts (major heads: IGST, CGST, SGST/UTGST, Cess; minor heads: Tax, Interest, Penalty, Fee, Others).
    - **Electronic Credit Ledger** — records ITC self-assessed in the return; can be used **only** to pay **output tax** (never interest, penalty, fee, or any other liability).
    - **Electronic Liability Register** — records all liabilities of the registered person (auto-populated from returns, notices, etc.).
  - A cash-ledger challan (PMT-06) generated online is valid for **15 days**.
  - Cross-utilization between major/minor heads within the cash ledger (e.g., excess IGST cash lying idle transferred to CGST) is done using **Form GST PMT-09**.
  - **Order of ITC utilization (Section 49A/49B, Rule 88A):** IGST credit must first be used to pay IGST, then the remainder can be used, in any order and in any proportion, to pay CGST and SGST/UTGST — but the **entire IGST credit must be fully exhausted** before any CGST or SGST/UTGST credit can be utilized.
- **Concept:** These three ledgers together form the taxpayer's running account with the department; every return (GSTR-3B) debits the liability register and credits it back via cash/credit ledger.
- **Pitfalls / exam tips:**
  - Credit ledger balance can never be used for interest, late fee, or penalty — a very common trick statement in MCQs.
  - IGST credit exhaustion is mandatory before touching CGST/SGST credit — sequence errors are a favourite examiner trap.
  - PMT-09 only moves money **within the cash ledger** across heads; it cannot convert credit ledger balance into cash.
- **Definitions:**

| Term | Meaning |
|---|---|
| GST PMT-06 | Challan for deposit into electronic cash ledger |
| GST PMT-09 | Form to transfer amount between major/minor heads of cash ledger |

---

### Interest on Delayed Payment of Tax [Section 50 read with Rule 88B]

- **Key formula(s)/rule(s):**

$$ \text{Interest} = \text{Tax paid late (net or gross)} \times 18\% \times \frac{\text{No. of days delay}}{365} $$

  - Interest runs **from the day next to the due date of payment** till the date of actual payment.
  - **On Net Cash Tax Liability** (i.e., only the portion discharged by debiting the **electronic cash ledger**) — applies only if **both**:
    - the return for that tax period has been filed **on time** (though belatedly is fine as long as before detection), and
    - no proceeding under **Section 73 / 74 / 74A** has been initiated in respect of that tax period.
  - **On Gross Tax Liability** — applies if tax for a period is paid through the return of a **later** tax period, or if proceedings under Section 73/74/74A have already been initiated.
  - **Interest on wrongly availed & utilized ITC [Section 50(3), Rule 88B(3)]** — chargeable only when ITC has been **both** wrongly availed **and** utilized (mere availment without utilization attracts no interest); rate notified is **18% p.a.** (statutory ceiling raised to 24% p.a., but the rate actually notified under Rule 88B(3) is 18% p.a.).
- **Concept:** Section 50 penalizes delay in cash payment of tax; Rule 88B (inserted by Notification 14/2022-CT, retrospective from 1.7.2017) codifies the day-count and net/gross mechanics that were earlier litigated.
- **Pitfalls / exam tips:**
  - If cash was already lying in the electronic cash ledger before the due date, that portion is **not** treated as a delay for interest purposes even if debited later, since the amount was available with the government.
  - "Net liability" relief is lost the moment 73/74/74A proceedings start — interest reverts to gross liability basis.
  - ⚠️ VERIFY — the OCR source is heavily garbled at this point; confirm the 18%/24% distinction and the exact wording of the net-liability proviso against the bare Act/Rule 88B before the exam, as amendment-heavy areas like this are examiner favourites.

---

### Tax Deducted at Source (TDS) [Section 51]

- **Key formula(s)/rule(s):**

$$ \text{TDS} = \text{Payment to supplier (excl. GST)} \times 2\% \; (1\% \text{ CGST} + 1\% \text{ SGST, or } 2\% \text{ IGST}) $$

  - Applicable only where the **total value of supply under a contract** exceeds **₹2,50,000** (contract value is taken **exclusive of tax**; invoice-wise splitting to defeat this threshold is disregarded).
  - Deductors: government departments/establishments, local authorities, government agencies, and other notified persons (e.g., PSUs, and certain categories notified for metal scrap etc.).
  - TDS deducted must be deposited to the government within **10 days after the end of the month** of deduction; deductor must file return in **Form GSTR-7** and issue a TDS certificate in **Form GSTR-7A**.
  - Amount deducted is credited to the **electronic cash ledger** of the deductee (supplier) based on the deductor's GSTR-7.
- **Concept:** A withholding mechanism so government/large buyers pre-collect GST from the supplier's payment, similar to income-tax TDS.
- **Pitfalls / exam tips:**
  - Threshold is on **contract value**, not invoice value — a single low invoice under a larger contract still attracts TDS.
  - No TDS where supplier and recipient (deductor) are both located in a State/UT different from the place of supply and it's an inter-State supply attracting IGST — actually TDS *does* apply, but the CGST+SGST vs IGST split changes; confirm supply type before choosing rate combination.
- **Definitions:**

| Term | Meaning |
|---|---|
| GSTR-7 | Monthly return filed by TDS deductor |
| GSTR-7A | TDS certificate issued to the deductee |

---

### Tax Collected at Source (TCS) [Section 52]

- **Key formula(s)/rule(s):**

$$ \text{TCS} = \text{Net value of taxable supplies made through the e-commerce operator} \times 1\% \; (0.5\% \text{ CGST} + 0.5\% \text{ SGST, or } 1\% \text{ IGST}) $$

  - "Net value of taxable supplies" = aggregate value of taxable supplies of goods/services (other than exempt/notified services) made through the operator by all registered suppliers **minus** the aggregate value of such supplies **returned** to suppliers during that month.
  - No minimum threshold — TCS applies on every operator facilitating supplies through its platform (subject to notified exclusions).
  - TCS collected must be deposited within **10 days after the end of the month**; e-commerce operator files monthly statement in **Form GSTR-8**; supplier claims credit of TCS in electronic cash ledger based on GSTR-8, reflected via **GSTR-2A/2B**.
- **Concept:** Ensures GST compliance by suppliers selling through online marketplaces, by making the platform itself collect and remit a slice of tax.
- **Pitfalls / exam tips:**
  - TCS is **not** a tax on the operator's own commission income — it's collected on the value of supplies made *by sellers* through the platform.
  - Do not confuse the 1% TCS rate (GST, Section 52) with the different TCS provisions under the Income-tax Act — a common cross-subject confusion in exams.
- **Definitions:**

| Term | Meaning |
|---|---|
| GSTR-8 | Monthly statement filed by e-commerce operator collecting TCS |

---

### Returns under GST — Overview

- **Key formula(s)/rule(s) — return map:**

| Return/Form | Purpose | Frequency |
|---|---|---|
| GSTR-1 | Outward supply details (invoice-wise) | Monthly (11th) / Quarterly under QRMP (13th, with optional IFF for month 1 & 2) |
| GSTR-3B | Summary self-assessed return + tax payment | Monthly (20th) / Quarterly under QRMP (22nd/24th, staggered by State) |
| GSTR-2A | Auto-populated (dynamic) inward supply statement from suppliers' GSTR-1/IFF | Continuously updated |
| GSTR-2B | Static, auto-drafted ITC statement for a period | Monthly |
| GSTR-4 | Annual return for composition taxpayers | Annual (30th April of next FY) |
| CMP-08 | Composition taxpayer's quarterly tax payment-cum-statement | Quarterly (18th of month after quarter) |
| GSTR-5 | Return by non-resident taxable person | Monthly |
| GSTR-6 | Return by Input Service Distributor | Monthly |
| GSTR-7 | TDS deductor's return | Monthly |
| GSTR-8 | TCS collector's (e-commerce operator) statement | Monthly |
| GSTR-9 | Annual return | Annual (31st Dec of next FY) |
| GSTR-9C | Self-certified reconciliation statement | Annual, along with/after GSTR-9 |
| GSTR-10 | Final return on cancellation of registration | Within 3 months of cancellation/cancellation order, whichever is later |
| GSTR-11 | Statement by UIN holders (embassies etc.) to claim refund | Monthly |

  - **GSTR-9** is mandatory for registered persons whose **aggregate annual turnover exceeds ₹2 crore** in the FY (optional below that, subject to periodic government relaxations); **GSTR-9C** (reconciliation statement) is mandatory where **aggregate annual turnover exceeds ₹5 crore**.
  - **Late fee** for GSTR-9: ₹50/day (₹25 CGST + ₹25 SGST) for taxpayers with turnover up to ₹5 crore, ₹100/day (₹50+₹50) for turnover between ₹5–20 crore, ₹200/day (₹100+₹100) for turnover above ₹20 crore — each capped at **0.04%** of turnover in the State/UT (0.5% for the highest slab, split 0.25% CGST + 0.25% SGST), per Notification 07/2023-CT.
  - **Late fee** for GSTR-1/GSTR-3B (general): NIL return — ₹500 total (₹250 CGST + ₹250 SGST); other returns capped by turnover slab — ₹2,000 (turnover ≤ ₹1.5 crore), ₹5,000 (₹1.5 cr–₹5 cr), ₹10,000 (> ₹5 crore) per Act.
  - **Rectification:** GST does not permit a "revised return." Errors/omissions in GSTR-1 of a tax period are corrected through **amendment tables** in the GSTR-1 of a subsequent month/quarter — but **not later than 30th November following the end of the financial year** to which the error relates (or actual date of filing the annual return, if earlier).
- **Concept:** GSTR-1 reports invoice-level outward supply data that flows (via GSTR-2A/2B) into the recipient's ITC; GSTR-3B is the actual self-assessment and payment return; GSTR-9/9C reconcile the year.
- **Pitfalls / exam tips:**
  - There is no revised-return concept in GST — always answer "amendment in subsequent period's return," not "revised return."
  - Distinguish GSTR-2A (dynamic, real-time) from GSTR-2B (static, frozen for the period) — a very frequently tested distinction.
  - ⚠️ VERIFY — exact current invoice-value thresholds for invoice-wise vs consolidated (B2C) reporting in GSTR-1 were illegible in the source OCR; confirm the current B2C inter-State invoice-value threshold (commonly cited as > ₹1 lakh/₹2.5 lakh depending on period) against the latest CBIC notification before relying on it in an answer.
- **Definitions:**

| Term | Meaning |
|---|---|
| IFF | Invoice Furnishing Facility — optional monthly upload of B2B invoices by QRMP taxpayers for month 1 & 2 of a quarter |
| AATO | Aggregate Annual Turnover |

---

### QRMP Scheme (Quarterly Return Monthly Payment)

- **Key formula(s)/rule(s):**
  - Available (optional, not mandatory) to registered persons with **aggregate annual turnover up to ₹5 crore** in the preceding FY; opted for at **GSTIN level**, not PAN level.
  - Under QRMP: **GSTR-1** and **GSTR-3B** are filed **quarterly**; tax for month 1 and month 2 of the quarter is still paid **monthly**, by the **25th of the following month**, via challan **Form GST PMT-06**.
  - Two methods to compute the monthly payment for month 1/month 2:
    - **Fixed Sum Method ("35% Challan"):** pay **35%** of the tax paid in cash in the **preceding quarter's** return (if the last return filed was quarterly), or **100%** of the tax paid in cash in the **last month** of the preceding quarter (if the last return filed was monthly, e.g., first quarter after opting in).
    - **Self-Assessment Method:** pay tax actually due for that month (based on outward supplies and available ITC) — no interest liability even if it later works out to be less than 35%, as long as correctly self-assessed.
  - **No monthly deposit required** for month 1/month 2 if: (a) the balance in electronic cash ledger + electronic credit ledger is adequate to cover that month's actual liability (i.e., liability is Nil), or (b) there is a Nil return for that month.
  - No interest is charged for month 1/month 2 short-payment **only** under the Fixed Sum Method when paid by the 25th; using the Self-Assessment Method, any shortfall attracts interest under Section 50.
- **Concept:** QRMP eases compliance frequency for small/medium taxpayers while still ensuring monthly cash flow to the government.
- **Pitfalls / exam tips:**
  - QRMP is opted GSTIN-wise; a person with multiple GSTINs can opt for QRMP for some and monthly filing for others.
  - The 35% figure applies to tax paid **in cash** in the last quarter, not total tax liability — do not confuse with gross liability.

---

### Refunds under GST [Section 54, Rules 89–92]

- **Key formula(s)/rule(s):**
  - **Time limit:** Application for refund must be filed in **Form GST RFD-01** before the expiry of **2 years from the "relevant date"** (relevant date varies by refund type — e.g., date of export, date of receipt of payment in convertible foreign exchange, date of judgment/order, etc.).
  - **Minimum refund claim:** No refund shall be granted if the amount is **less than ₹1,000** per tax head (this floor does **not** apply to refund of excess balance in the electronic cash ledger).
  - **Unjust enrichment — documentary evidence required with application:**
    - Refund claim **up to ₹2 lakh** → self-declaration that incidence of tax has not been passed on to any other person.
    - Refund claim **more than ₹2 lakh** → Certificate from a **Chartered Accountant/Cost Accountant** certifying no unjust enrichment.
  - **Exceptions where unjust enrichment need not be proved at all** (no certificate/declaration needed): refund of unutilized ITC on account of zero-rated supply or inverted duty structure; refund of tax on export of goods/services (zero-rated supply); refund of tax paid on a supply not provided (wholly/partially) where invoice has not been issued (or refund voucher issued); refund arising from Section 77 (tax wrongly paid as IGST instead of CGST+SGST, or vice versa); refund claimed by notified/specified classes of applicants (e.g., UN bodies, embassies, Canteen Stores Department); refund of tax on inward supplies used by SEZ unit/developer for authorized operations.
  - **Refund of unutilized ITC — Rule 89(4), zero-rated supply (without payment of tax):**

$$ \text{Refund Amount} = \left(\text{Turnover of zero-rated supply of goods} + \text{Turnover of zero-rated supply of services}\right) \times \frac{\text{Net ITC}}{\text{Adjusted Total Turnover}} $$

  where:
  - *Net ITC* = ITC availed on **inputs and input services** during the relevant period (excludes ITC on capital goods and any blocked credit under Section 17(5));
  - *Turnover of zero-rated supply of goods* = value of zero-rated supply of goods made without payment of tax, restricted to the **lower of** (a) actual value of such supply, or (b) **1.5 times** the value of like goods domestically supplied by the same/similarly placed supplier (an anti-over-invoicing safeguard);
  - *Adjusted Total Turnover* = turnover in the State/UT (as defined in Section 2(112)), reduced by the value of exempt supplies (other than zero-rated) and turnover for which refund is claimed under related sub-rules.
  - **Refund of unutilized ITC — Rule 89(5), inverted duty structure** (rate of tax on inputs higher than rate of tax on output supply):

$$ \text{Maximum Refund Amount} = \left[\frac{\text{Turnover of inverted-rated supply of goods and services} \times \text{Net ITC}}{\text{Adjusted Total Turnover}}\right] - \text{Tax payable on such inverted-rated supply} $$

  where *Net ITC* here = ITC availed on **inputs only** (input services are excluded from this specific formula).
  - **Provisional refund (Rule 91):** **90%** of the refund claimed on account of zero-rated supplies may be sanctioned provisionally within **7 days** of acknowledgement of the application (subject to specified risk-based exclusions), balance 10% after due verification.
  - **Interest on delayed refund [Section 56]:**
    - **6% p.a.** if refund (other than one arising from an appellate order) is not granted within **60 days** from the date of receipt of a complete refund application — interest runs from expiry of the 60 days till the date of refund.
    - **9% p.a.** if the refund arises pursuant to an order of an Appellate Authority/Appellate Tribunal/Court that has attained finality, and is not paid within 60 days of the (fresh) application.
- **Concept:** Refund provisions ensure exporters and inverted-duty-structure taxpayers are not permanently locked out of blocked working capital, while the unjust-enrichment doctrine prevents double benefit (tax refunded + tax already recovered from the customer).
- **Pitfalls / exam tips:**
  - Rule 89(5) excludes input **services** from Net ITC — students often wrongly carry over the Rule 89(4) definition of Net ITC (which includes input services) into the inverted-duty formula.
  - No refund of unutilized ITC is allowed for zero-rated supply of goods that are subject to **export duty**.
  - Interest under Section 56 is **automatic and mandatory** — no separate application is needed by the claimant to get it.
  - ⚠️ VERIFY — the OCR for the exact wording of "Adjusted Total Turnover" exclusions and the full illustrative list of unjust-enrichment exceptions was largely unreadable; cross-check the complete proviso list to Section 54(8) in the bare Act before an exam answer that hinges on a specific exception.
- **Definitions:**

| Term | Meaning |
|---|---|
| Relevant date | Date from which the 2-year limitation for a refund application is counted (varies by refund category) |
| Unjust enrichment | Doctrine presuming tax incidence has been passed on to the buyer unless proved otherwise |
| ZRS | Zero-Rated Supply (exports and supplies to SEZ unit/developer) |

### References
1. CGST Act, 2017 — Sections 49, 49A, 49B, 50, 51, 52, 54, 56 (bare act text, as amended up to Finance Act 2023/2024).
2. CGST Rules, 2017 — Rules 87, 88, 88A, 88B, 89, 91, 92 (as amended by Notification No. 14/2022-Central Tax and subsequent notifications).
3. CBIC, Rule 88B of the CGST Rules — interest computation mechanics: cleartax.in/s/rule-88b-of-cgst-rules-interest-calculation
4. TDS (Section 51) and TCS (Section 52) rate/threshold summary: vakilsearch.com/article/tds-and-tcs-in-gst
5. Rule 89(4) refund formula and Adjusted Total Turnover clarification (CBIC Circulars 147/03/2021-GST, 197/09/2023-GST): taxguru.in/goods-and-service-tax/determination-admissible-refund-exporter-cgst-rule-894.html
6. Late fee slabs for GSTR-9/9C under Notification No. 07/2023-Central Tax: cleartax.in/s/gstr-9-annual-return
7. QRMP Scheme — Fixed Sum Method / Self-Assessment Method mechanics: cleartax.in/s/quarterly-return-monthly-payment-qrmp-scheme-gst
8. Section 56 interest on delayed refund (6%/9%): patronaccounting.com/gst-refund-interest-section-56

## 10. Assessment, Audit, Inspection/Search/Seizure/Arrest, Demand & Recovery
> **Where it fits:** covers the department's toolkit for verifying and enforcing tax compliance under CGST Act 2017 — from self-assessment by the taxpayer, through departmental audit and physical enforcement (inspection/search/seizure/arrest), to the final adjudication of tax demand (Sections 73/74/74A) and its recovery. This is one of the highest-weightage, most amendment-heavy chapters in IDT — the FY 2024-25 merger of Sections 73 & 74 into new **Section 74A** is the single most important recent change here.

### Self-Assessment & Provisional Assessment (Sections 59 & 60)

- **Key formula(s)/rule(s):**
  - Self-assessment (Sec 59): every registered person self-assesses taxes payable and furnishes a return for each tax period — the default mode of assessment under GST.
  - Provisional assessment (Sec 60) — invoked when the registered person is unable to determine (a) value of supply, or (b) rate of tax:
$$
\text{Sequence: Written request} \rightarrow \text{Proper Officer permits payment on provisional basis} \rightarrow \text{Execution of a Bond + Security (Surety/Bank Guarantee)} \rightarrow \text{Final Assessment Order}
$$
  - Final assessment order to be passed **within 6 months** from the date of the provisional-assessment order.
  - Extension: Joint/Additional Commissioner may extend by **a further 6 months**; the Commissioner may extend further, **for a total period not exceeding 4 years** from the date of the provisional order.
  - Interest under Section 50 is payable on any additional tax found payable on final assessment, from the original due date of payment (not from date of provisional order) till the date of actual payment.
  - Interest on any refund arising on final assessment is payable to the taxpayer under Section 56.
  - Security/bond is released only on an application by the taxpayer after final assessment, once all dues are cleared.

- **Concept:** Provisional assessment is a stop-gap when a taxpayer genuinely cannot self-assess value/rate — it lets business continue while liability is finalised later against a bond/security.

- **Pitfalls / exam tips:**
  - Provisional assessment can be sought for reasons of value or rate **only** — not for any other reason (e.g., classification disputes covered indirectly via rate).
  - Remember the extension chain: 6 months → +6 months (JC/AC) → up to 4 years total (Commissioner) — a favourite numeric trap.
  - Do not confuse this timeline with the Section 65 audit timeline (3+6 months) — different chapter, different numbers.

- **Definitions:**

| Term | Meaning |
|---|---|
| Bond (Form GST ASMT-05) | Security instrument executed by taxpayer to cover the tax gap during provisional assessment |
| Final Assessment Order | Order under Sec 60(3) quantifying actual tax liability after the uncertainty is resolved |

### Scrutiny of Returns (Section 61)

- **Key formula(s)/rule(s):**
  - Proper Officer scrutinises **furnished returns** (and related particulars) to verify correctness — no power to demand a return that was never filed.
  - Discrepancy noticed → notice in **Form ASMT-10** seeking explanation.
  - Registered person replies in **Form ASMT-11** within the time specified (or such further period as permitted).
  - If explanation is acceptable → Proper Officer informs in **Form ASMT-12**, no further action.
  - If no satisfactory explanation / no corrective action within 30 days (or extended period) → Proper Officer may proceed with any of: audit (Sec 65), special audit (Sec 66), inspection/search/seizure (Sec 67), or determination of tax under **Section 73/74/74A**.

- **Concept:** A softer, desk-based first check on filed returns — a filter before heavier tools (audit, demand) are used.

- **Pitfalls / exam tips:** Scrutiny under Sec 61 is not an assessment in itself — it only identifies discrepancies; the actual tax demand still flows through Sec 73/74/74A.

### Best Judgment Assessment — Non-Filers (Section 62) & Unregistered Persons (Section 63)

- **Key formula(s)/rule(s):**
  - **Section 62 (failure to furnish return even after service of notice u/s 46):** Proper Officer may assess tax liability to the **best of his judgment**, taking into account all relevant material, within **5 years from the due date for furnishing the annual return** for the relevant financial year.
  - If the registered person furnishes a valid return **within 60 days** of service of the Sec 62 assessment order, the order is **deemed withdrawn**; a **further 60 days** is allowed (i.e., up to 120 days in total) on payment of additional late fee (₹100/day, subject to caps) — but interest under Sec 50 and late fee under Sec 47 continue to apply.
  - **Section 63 (unregistered / registration cancelled persons who were liable to register):** Proper Officer assesses to the best of judgment, **within 5 years from the due date for furnishing the annual return** for the FY to which the tax not paid relates; a **reasonable opportunity of being heard** must be given (notice + hearing mandatory, unlike the automatic Sec 62 route).

- **Concept:** Both are "best judgment" assessments — used only where the taxpayer's own return-based data is unavailable (non-filing, non-registration).

- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — the 60-day withdrawal window (extendable by a further 60 days with late fee) was introduced/confirmed by Finance Act 2023 amendments to Sec 62(2); older material may still show "30 days" — use 60+60 days for current syllabus but double-check the CBIC notification bringing this into force if the question specifically tests the applicable date.
  - The 5-year limitation for Sec 62/63 runs from the **annual-return due date**, not from the date of the default itself.

### Summary Assessment (Section 64)

- **Key formula(s)/rule(s):**
  - Invoked when the Proper Officer has evidence that a taxable person's tax liability exists and **any delay in assessing it is likely to adversely affect revenue interest**.
  - Order can be passed only with the **previous permission of Additional/Joint Commissioner**.
  - The affected taxable person (or, in case of a deceased/absconding person, any other person considered liable) may apply for **withdrawal of the summary assessment order within 30 days** of its service.
  - The Additional/Joint Commissioner may, on his own motion, **withdraw the order if he considers it erroneous**.

- **Concept:** An emergency, revenue-protection assessment — used sparingly, typically where the person is likely to disappear/dispose of assets before regular proceedings could be completed.

- **Pitfalls / exam tips:** Two separate withdrawal routes — taxpayer's application (30 days) vs suo motu by Addl/Joint Commissioner (no fixed time limit stated) — examiners test which route applies to whom.

### Audit by Tax Authorities (Section 65) & Special Audit (Section 66)

- **Key formula(s)/rule(s) — Departmental Audit (Sec 65):**
  - Conducted by the Commissioner or an officer authorised by him, of any registered person, at such frequency/manner as prescribed.
  - **Prior notice of 15 working days** (Form GST ADT-01) before conduct of audit.
$$
\text{Audit completion period} = 3 \text{ months from date of commencement of audit}
$$
  - Extendable by the Commissioner, **for reasons recorded in writing, by a further period not exceeding 6 months** (so maximum total ≈ **9 months**).
  - "Commencement of audit" = date books of account/records are made available, or the actual institution of the audit — whichever is later.
  - Findings communicated to the registered person in Form ADT-02; registered person may reply / take corrective action.

- **Key formula(s)/rule(s) — Special Audit (Sec 66):**
  - Can be directed at any stage of scrutiny/inquiry/investigation by an officer **not below the rank of Assistant Commissioner**, **with prior approval of the Commissioner**, where he is of the opinion that the value has not been correctly declared or the ITC availed is not within normal limits, having regard to the nature/complexity of the case and interest of revenue.
  - Conducted by a **Chartered Accountant or Cost Accountant nominated by the Commissioner** (not chosen by the taxpayer).
$$
\text{Special audit report period} = 90 \text{ days from date of direction (Form ADT-03)}
$$
  - Extendable, on application by the auditor/registered person or on the Commissioner's own motion, by **a further 90 days** — maximum total **180 days**.
  - Cost of special audit (including auditor's remuneration) is determined and paid by the **Commissioner** — the department bears the cost.
  - Registered person must be given an opportunity of being heard on findings used against him.

- **Concept:** Sec 65 = routine/general departmental verification of any registered person's records; Sec 66 = a targeted, deeper, independent (CA/CMA-led) probe ordered mid-proceedings when complexity/valuation/ITC concerns arise.

- **Pitfalls / exam tips:**
  - Do not confuse the Sec 65 timeline (3 + 6 = 9 months) with the Sec 66 timeline (90 + 90 = 180 days) — a classic mixing trap in MCQs.
  - Special audit can be ordered even while a Sec 65 audit or scrutiny is already in progress — it is not mutually exclusive.
  - GSTR-9C (self-certified reconciliation statement, threshold currently ₹5 crore turnover) is a **separate compliance requirement under Section 44/Rule 80**, distinct from the Sec 65/66 audits — don't conflate the two.

- **Definitions:**

| Term | Meaning |
|---|---|
| ADT-01 | Notice for conducting departmental audit u/s 65 |
| ADT-02 | Audit findings/report communicated to registered person |
| ADT-03 | Communication directing special audit u/s 66 |

### Inspection, Search, Seizure & Arrest (Sections 67–72)

- **Key formula(s)/rule(s):**
  - **Inspection (Sec 67(1)):** Joint Commissioner or above, having **"reasons to believe"** that a taxable person has suppressed transactions, claimed excess ITC/refund, or is contravening provisions to evade tax, may authorise (in writing) any other officer to inspect any place of business.
  - **Search & Seizure (Sec 67(2)):** Where the authorising officer (JC or above) has reasons to believe that goods liable to confiscation, or documents/books/things relevant to proceedings, are secreted at any place, he may authorise search of that place and seizure of such goods/documents.
  - Goods so seized, if **not confiscated/notice not issued within 6 months** of seizure, **must be returned** to the person from whom seized. This 6-month period is **extendable by the Commissioner (or an officer he authorises), for sufficient cause, by up to a further 6 months.**
  - **Perishable/hazardous/depreciating goods** seized may be released provisionally/immediately per prescribed list on payment of applicable tax, interest and penalty, or on execution of a bond.
  - A copy of the seizure order/list of goods (Panchnama-style inventory) and a **signature of the person in charge** of the seized documents/goods is a basic procedural safeguard.
  - **Arrest (Sec 69):** The Commissioner, having reasons to believe a person has committed an offence specified under Sec 132(1)(a)–(d) or (1)(f) [and punishable under Sec 132(1)(i)/(ii) or Sec 132(2)], may authorise arrest by written order. If the offence is **cognizable and non-bailable**, the arrested person must be produced before a Magistrate **within 24 hours**; if non-cognizable and bailable, the officer (Deputy/Assistant Commissioner) may grant bail.
  - **Summons (Sec 70):** Proper Officer (not below the rank prescribed) may summon any person to give evidence/produce documents; such proceedings are **deemed judicial proceedings** for the purposes of the applicable perjury/false-evidence provisions.
  - **Access to business premises (Sec 71)** and **duty of officers/other authorities to assist (Sec 72)** are the remaining supporting provisions in this cluster.

- **Concept:** A graduated enforcement ladder — inspection (least intrusive, just look) → search & seizure (physically take custody of goods/records) → summons (compel evidence) → arrest (personal liberty, used only for serious/specified offences with Commissioner's authorisation).

- **Pitfalls / exam tips:**
  - "Reasons to believe" (an objective, recorded satisfaction) is the trigger at both JC-level (inspection/search) and Commissioner-level (arrest) — the rank differs; don't interchange them.
  - The 6-month "return goods if no notice" rule under Sec 67 is a recurring numerical MCQ — remember it is extendable by another 6 months only for "sufficient cause" recorded in writing.
  - Arrest requires the offence to be one of the specified ones under Sec 132 **and** cross a monetary/severity threshold (see Sec 132 below) — arrest is not automatic for every GST offence.

- **Definitions:**

| Term | Meaning |
|---|---|
| INS-01 | Authorisation for inspection/search issued by proper officer |
| Cognizable offence | Police/officer can arrest without a warrant; here, tax evasion/ITC fraud ≥ ₹5 crore under Sec 132(1)(i) is cognizable & non-bailable |
| Non-cognizable offence | Arrest generally requires a warrant/magistrate involvement; bailable |

### Punishment for Offences & Power to Arrest — the monetary ladder (Section 132)

- **Key formula(s)/rule(s):** classification of specified offences (tax evasion, ITC wrongly availed/utilised, fraudulent refund, issuing invoice without supply, etc.) by amount involved:

| Amount of tax evaded / ITC wrongly availed-utilised / refund fraudulently obtained | Classification | Maximum imprisonment |
|---|---|---|
| Below ₹1 crore | No prosecution / arrest (departmental action only) — except specified invoice-fraud offences | — |
| ₹1 crore – ₹2 crore | Non-cognizable & bailable | Up to 1 year + fine |
| ₹2 crore – ₹5 crore | Non-cognizable & bailable | Up to 3 years + fine |
| Above ₹5 crore | **Cognizable & non-bailable** | Up to 5 years + fine |

- Prosecution requires the **previous sanction of the Commissioner**.
- Repeat offenders (second/subsequent conviction) face enhanced punishment (up to 5 years + fine) regardless of amount slab, for specified repeat offences.
- Post Finance Act 2023 "decriminalisation" amendments: the general prosecution threshold was raised (from ₹1 crore to **₹2 crore**) and certain offences (obstruction of officer, tampering with evidence, failure to supply information) were **removed** from prosecution exposure; compounding of offences was also liberalised.

- **Concept:** GST prosecution/arrest is strictly amount-linked and offence-specific — small-value defaults stay purely in the tax/penalty domain; only large-value fraud crosses into criminal law territory.

- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — exact current compounding amounts and the full list of decriminalised clauses under Sec 132(1) should be cross-checked against the amended bare Act text for the exam year, as compounding fee slabs have been revised more than once.
  - Sec 138 (compounding of offences) allows most offences to be compounded on payment of a compounding amount, generally **before institution/after institution of prosecution but before conviction** — a few serious repeat/high-value offences are excluded from compounding.

### Determination of Tax — Sections 73, 74 & new Section 74A (Demand)

- **Key formula(s)/rule(s):**

**(A) Old regime — applicable up to FY 2023-24 only:**

| | Sec 73 (non-fraud / bona fide error) | Sec 74 (fraud / wilful misstatement / suppression) |
|---|---|---|
| SCN time limit | At least 3 months before the time limit for order | At least 6 months before the time limit for order |
| Order time limit | 3 years from due date of furnishing annual return (or from date of erroneous refund) | 5 years from due date of furnishing annual return (or from date of erroneous refund) |
| Penalty if paid before SCN | NIL | 15% of tax |
| Penalty if paid within 30 days of SCN | NIL | 25% of tax |
| Penalty if paid within 30 days of order | 10% of tax or ₹10,000, whichever is higher | 50% of tax |
| Penalty if not paid (per order) | 10% of tax or ₹10,000, whichever is higher | 100% of tax |

**(B) New unified Section 74A — applicable for FY 2024-25 onwards** (inserted by Finance (No. 2) Act, 2024; notified w.e.f. 1 November 2024 vide Notification No. 17/2024–Central Tax): one common section for both fraud and non-fraud cases, with a common limitation period:
$$
\text{SCN time limit} = 42 \text{ months from due date of annual return (or from date of erroneous refund)}
$$
$$
\text{Order time limit} = 12 \text{ months from date of issue of SCN, extendable by the Commissioner by a further 6 months}
$$

| Penalty (non-fraud cases, Sec 74A(5)) | Penalty (fraud cases, Sec 74A(6)) |
|---|---|
| NIL if paid before SCN | 15% of tax if paid before SCN |
| NIL if paid within 60 days of SCN | 25% of tax if paid within 60 days of SCN |
| 10% of tax or ₹10,000 (whichever higher) if paid within 60 days of order | 50% of tax if paid within 60 days of order |
| 10% of tax or ₹10,000 (whichever higher), per order, if not paid | 100% of tax, per order, if not paid |

  - The "cure window" for reduced penalty is extended from **30 days (old Sec 73/74) to 60 days (new Sec 74A)**.
  - Amount of tax, interest and penalty confirmed in the order **cannot exceed** the amount specified in the SCN.
  - Once penalty is imposed under Sec 74A, **no separate penalty** shall be imposed for the same act under any other provision of the Act.
  - If the tax amount is modified by an Appellate Authority/Tribunal/Court, interest and penalty are recalculated accordingly.
  - Interest under Section 50 is charged **mandatorily**, even if not specifically mentioned in the order.

- **Concept:** Sec 73/74/74A are the substantive "show cause + adjudication" machinery for raising a GST demand — the FY2024-25 merger removes the fraud/non-fraud bifurcation for limitation purposes going forward, while still differentiating penalty rates based on fraud vs bona-fide conduct.

- **Pitfalls / exam tips:**
  - For **any period up to FY 2023-24**, continue applying old Sec 73 (3-year/30-day regime) or Sec 74 (5-year/30-day regime) as applicable — **Sec 74A applies only from FY 2024-25 onwards.** This split is the single most exam-tested nuance in this chapter currently.
  - Remember: 42 months (SCN) is common to both fraud and non-fraud under 74A — only the **penalty percentages** differ by fraud/non-fraud, not the limitation period.
  - Hierarchy of officers empowered to issue SCN/pass order under Sec 74A is based on the amount of tax involved (Superintendent/Assistant-Deputy Commissioner/Joint-Additional Commissioner/Principal Commissioner-Commissioner slabs as prescribed) — know that a monetary-based officer hierarchy exists, even if exact slab figures should be checked against the current CBIC circular before the exam.

- **Definitions:**

| Term | Meaning |
|---|---|
| SCN (Show Cause Notice) | Notice specifying the amount of tax, interest and penalty and asking the noticee why it should not be demanded/imposed |
| DRC-01 | Summary of SCN issued under Sec 73/74/74A |
| DRC-07 | Summary of the demand order |

### Recovery of Tax (Sections 78, 79) & Related Machinery (Sections 80, 81, 83)

- **Key formula(s)/rule(s):**
  - **Sec 78 — Initiation of recovery:** any amount payable under an order must be paid **within 3 months** from the date of service of the order; on default, recovery proceedings under Sec 79 begin. (Proper Officer may, for reasons recorded in writing, require payment in a period **shorter than 3 months**, where he considers it expedient in the interest of revenue.)
  - **Sec 79 — Modes of recovery:** proper officer may recover the defaulted amount by one or more of: deduction from money owed to the defaulter by the department; detaining/selling goods belonging to defaulter; garnishee-type recovery from third parties owing money to the defaulter; distraint and sale of movable/immovable property; recovery through the jurisdictional District Collector/Magistrate as arrears of land revenue; or by way of recovery through the Court (recovery certificate).
  - **Sec 80 — Payment in instalments:** on application, the Commissioner may allow payment of **any amount due (other than amounts due as per liability self-assessed in any return)** in **monthly instalments not exceeding 24**, subject to interest under Sec 50 and conditions; default in payment of any one instalment makes the **whole outstanding balance immediately payable**.
  - **Sec 81 — Transfer of property to be void:** any transfer (sale, mortgage, exchange, gift, delivery) of property by a taxable person, made **after any amount has become due**, is void as against any claim in respect of that tax, unless made for adequate consideration, in good faith, and without notice of the pending tax liability.
  - **Sec 83 — Provisional attachment:** during pendency of proceedings under specified sections (e.g., 62, 63, 64, 67, 73, 74/74A, etc.), the Commissioner, if of the opinion that it is necessary to do so to protect the interest of revenue, may **provisionally attach any property (including bank account)** of the taxable person.
$$
\text{Validity of provisional attachment} = 1 \text{ year from the date of the attachment order}
$$
  - The taxable person may file an objection (Form DRC-22A) and seek release of the attached property.

- **Concept:** Once a demand crystallises and remains unpaid, Sec 78/79 give the department coercive recovery tools; Sec 80/81/83 are the surrounding "protective" and "facilitative" machinery — instalments for genuine hardship, anti-alienation protection for revenue, and provisional attachment as a pre-emptive freeze during pending proceedings.

- **Pitfalls / exam tips:**
  - Sec 83 attachment is **provisional and time-bound (1 year)** — it automatically ceases unless a fresh order is passed; it is not a permanent seizure.
  - Sec 80 instalment facility explicitly **excludes self-assessed tax liability** shown in a return — that must be paid in full/on time regardless.
  - A single default in instalments under Sec 80 forfeits the entire instalment facility — the balance becomes due at once.

- **Definitions:**

| Term | Meaning |
|---|---|
| DRC-13 | Notice to a third party (garnishee) to pay money owed to the defaulter, to the department |
| DRC-16 | Notice for attachment and sale of movable/immovable property/shares under Sec 79 |
| DRC-20 | Application by taxpayer for deferred payment/instalments under Sec 80 |

### Confiscation & Penalty for Goods/Conveyance in Transit (Sections 129 & 130)

- **Key formula(s)/rule(s):**
  - **Sec 129 — Detention & Seizure in transit:** goods/conveyance transported (or stored) in contravention of the Act (e.g., without valid e-way bill/invoice) may be **detained or seized**; released on payment of applicable tax and penalty (as prescribed — generally 100% of tax payable, or 200% in certain no-document cases, subject to the current Act/notification wording) or on furnishing security equivalent thereto.
$$
\text{If tax + penalty not paid within 14 days of detention/seizure} \Rightarrow \text{further proceedings under Section 130 (confiscation) may be initiated}
$$
  - Proper officer must issue a notice specifying the penalty payable and, after giving an opportunity of being heard, pass an order **within 7 days** of the notice.
  - **Sec 130 — Confiscation:** goods/conveyance liable to confiscation where supply/receipt is with intent to evade tax, or contravenes provisions with such intent (e.g., non-accounted goods, fraudulent ITC-linked transport). Owner given option to pay a **fine in lieu of confiscation**, in addition to tax, penalty and charges payable.
  - Where the penalty/fine is not paid **within 15 days** from the date of the confiscation order, the goods/conveyance so confiscated **may be sold or disposed of** by the proper officer (this 15-day period can be reduced for perishable/hazardous or fast-depreciating goods).

- **Concept:** A dedicated, fast-track enforcement regime for goods physically in movement without proper documentation — separate from (and generally faster/stricter than) the general Sec 73/74/74A demand process, aimed at plugging revenue leakage at transit checkpoints.

- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — exact current penalty percentages under Sec 129(1)(a)/(b) (owner-came-forward vs owner-did-not-come-forward cases) and confiscation fine formula under Sec 130(2) should be cross-checked against the amended bare Act/Rule 138 as these percentages have been revised by past Finance Acts; the 14-day/7-day/15-day procedural timelines above are well-settled and safe to rely on.
  - Sec 129 is triggered even for **bona fide** transit issues (e.g., expired e-way bill); Sec 130 confiscation requires **intent to evade tax** — do not treat them as automatically sequential in every case.

### References
1. CBIC – CGST Act, 2017, Sections 59–74A, 78–83, 129–132 (as amended) — official bare Act text, https://taxinformation.cbic.gov.in
2. Finance (No. 2) Act, 2024 & Notification No. 17/2024–Central Tax dated 27-09-2024 — insertion and commencement of Section 74A w.e.f. 1 November 2024 (see TaxGuru: "Section 74A of CGST Act: A middle path between Section 73 and Section 74" and Metalegal: "GST Demand Notice Streamlining in the Finance Act 2024")
3. Section 132 CGST Act – monetary thresholds, cognizable/non-cognizable classification, and Finance Act 2023 decriminalisation changes (Metalegal: "Arrest and bail in GST law"; ConsultEase: "Section 132 of CGST Act – Punishment for certain offences")
4. Sections 65 & 66 audit timelines — TaxGuru: "Behind the Scenes of GST: The Power Audits – Sections 65 & 66"; ADCA: "Time Limit For GST Audit Under Section 65"
5. Sections 61–64 (Scrutiny, Best Judgment, Summary Assessment) — Studycafe/CA Arpit Haldia, "Assessment Provisions in GST – Section 61 to Section 64"; GST Gyaan, "Section 61 – Scrutiny of returns"
6. Sections 78–83 (Recovery, Instalments, Void Transfer, Provisional Attachment) — CGGST.com Section 78/79/83 commentary; Masters India, "Section 80 GST Act: Tax Instalments"; ClearTax, "Provisional Attachment of Property under GST – Section 83"
7. Sections 129–130 (Detention, Seizure, Confiscation in transit) — TaxGuru: "Detention & Seizure under CGST Act Section 129 & Legal Actions"; TaxScan: "A Navigation through the Interplay Between Sections 129 and 130"

## 11. Appeals and Revision

> **Where it fits:** Once an adjudicating officer passes an order (demand, refund rejection, registration cancellation, etc.), this chapter maps the entire dispute-resolution ladder under CGST Act, 2017 — Appellate Authority → Revisional Authority/GSTAT → High Court → Supreme Court — along with pre-deposit conditions, limitation periods and procedural rules that gate every stage.

### Appellate Hierarchy — Big Picture

- **Concept:** A person aggrieved by an order of an adjudicating authority (First Appellate stage) goes to the **Appellate Authority [Sec. 107]**; from there, either party may go to the **GST Appellate Tribunal, GSTAT [Sec. 112]**; from GSTAT (State Bench) to the **High Court [Sec. 117]** on a substantial question of law; and finally to the **Supreme Court [Sec. 118]**. Running parallel to the appeal chain is the **Revisional Authority [Sec. 108]**, which reviews orders suo motu (not on the taxpayer's initiative).
- **Pitfalls / exam tips:**
  - Orders of the **National Bench/Regional Benches of GSTAT** (which alone decide **place of supply** disputes) go directly to the **Supreme Court**, bypassing the High Court — a favourite trick in MCQs.
  - "Appeal" is taxpayer/department-driven and adversarial; "Revision" is departmental self-correction and can be exercised even if no appeal has been filed.

### Appeal to Appellate Authority [Section 107]

- **Key formula(s)/rule(s) — time limits:**
$$\text{Appellant (taxpayer): } 3 \text{ months from communication of order} + \text{condonation up to } 1 \text{ month (sufficient cause)}$$
$$\text{Department (review u/s 107(2), by Commissioner): } 6 \text{ months from communication of order} + \text{condonation up to } 3 \text{ months}$$
  - Appeal is filed in **FORM GST APL-01** (memorandum of appeal) with certified copy of the decision/order; acknowledgement in **FORM GST APL-02**.
  - Appellate Authority must, where possible, decide the appeal within **1 year** of filing (directory, not mandatory).
- **Concept:** First and mandatory stage of appeal against any adjudication/decision order; either the taxpayer appeals on his own behalf, or the Commissioner directs a subordinate officer to file a "departmental appeal" against an order he considers legally incorrect (a review, not a taxpayer grievance).
- **Pitfalls / exam tips:**
  - The 1-month condonation for the appellant is an **outer limit** — Appellate Authority cannot condone delay beyond 3+1 months (unlike some other statutes with "sufficient cause, no outer limit").
  - No appeal lies against certain orders listed in **Section 121** (non-appealable orders) — see below.

### Pre-Deposit for Appeal to Appellate Authority

- **Key formula(s)/rule(s):**
$$\text{Pre-deposit} = 100\% \text{ of admitted tax, interest, fine, fee \& penalty} + 10\% \text{ of the remaining disputed tax}$$
$$\text{Cap on the } 10\% \text{ component} = \text{₹20 crore} \text{ (reduced from ₹25 crore, effective 1 Nov 2024)}$$
- **Concept:** No appeal can even be *filed* unless this pre-deposit is paid; payment automatically **stays recovery** of the balance disputed amount pending disposal of appeal.
- **Pitfalls / exam tips:**
  - Where the dispute involves only penalty/late fee (no tax component), pre-deposit is 10% of the disputed penalty/fee, same ₹20 crore cap.
  - Pre-deposit is a jurisdictional condition, not merely procedural — appeal is liable to be rejected in limine if unpaid.

### Revisional Authority [Section 108]

- **Key formula(s)/rule(s) — time limits for passing revisional order:**
$$\text{Revisional order must be passed within: } \max\big(3 \text{ years from date of the order sought to be revised},\ 1 \text{ year from date of the appellate order on any point not decided in that appeal}\big)$$
  - Revision cannot be initiated until the **6-month** period for a departmental appeal under Sec. 107(2) has expired.
  - Period during which the order was **stayed by a court/Appellate Tribunal** is excluded while computing the above limitation.
- **Concept:** The Revisional Authority (an officer senior to/other than the one who passed the order, as notified) may, **on its own motion**, call for and examine the record of any proceeding and revise an order it finds **erroneous, prejudicial to revenue, or illegal/improper**.
- **Pitfalls / exam tips:** Revision is **barred** if the order (a) has already been appealed under Sec. 107/112/117/118, (b) is itself a revisional order, or (c) has already been taken up for revision earlier — no double jeopardy on revision.

### GST Appellate Tribunal (GSTAT) — Constitution [Sections 109–111]

- **Key rule(s):**
  - GSTAT has one **Principal Bench** (New Delhi) and **State Benches** — per Finance Act, 2023 restructuring, place-of-supply disputes lie exclusively with the **Principal/National Bench**; all other matters go to the jurisdictional State Bench.
  - Each Bench (other than a Bench of only Judicial Members) is composed of **Judicial Member(s)**, a **Technical Member (Centre)** and a **Technical Member (State)**.
  - GSTAT is **not bound by the Code of Civil Procedure**, 1908; it is guided by principles of **natural justice**, subject to the Act and Rules, and may regulate its own procedure — but has the same powers as a civil court under CPC for discovery, summoning witnesses, etc.
- **Concept:** GSTAT is the second appellate forum for GST disputes; India's GSTAT has been operationalised progressively across 2025–26 with the Principal Bench and State Benches becoming functional in phases.
- **Pitfalls / exam tips:** ⚠️ VERIFY — exact count/list of State Bench locations and their phased "go-live" dates change frequently as GSTAT rolls out; do not memorise a specific city list for the exam, only the Principal Bench vs. State Bench jurisdictional split (place of supply → Principal/National Bench).

### Appeal to Appellate Tribunal [Section 112]

- **Key formula(s)/rule(s) — time limits:**
$$\text{Appellant (taxpayer): } 3 \text{ months from date of communication of the order appealed against}$$
$$\text{Department: } 6 \text{ months from date of communication of the order}$$
$$\text{Cross-objections by the other party: } 45 \text{ days} + \text{condonable up to a further } 45 \text{ days}$$
  - Filed in **FORM GST APL-05**; Tribunal **may refuse to admit** an appeal where the amount of tax/ITC in dispute or the fine/fee/penalty determined **does not exceed ₹50,000**.
- **Key formula(s)/rule(s) — pre-deposit:**
$$\text{Additional pre-deposit} = 10\% \text{ of the remaining disputed tax (over and above the amount already paid u/s 107(6))}$$
$$\text{Cap} = \text{₹20 crore (reduced from 20\% / ₹50 crore cap by Finance (No. 2) Act, 2024)}$$
- **Concept:** Second appellate stage; either the taxpayer or the department may appeal an order of the Appellate Authority or the Revisional Authority to GSTAT.
- **Pitfalls / exam tips:**
  - Students commonly confuse the Sec. 112(8) pre-deposit as being *in addition to* the full Sec. 107(6) 10%, i.e., cumulatively 20% — it is **not**; it is a further 10% layered on the same disputed amount, capped independently at ₹20 crore.
  - The ₹50,000 threshold is a **discretionary** refusal power ("may refuse"), not an automatic bar.

### Orders of Appellate Tribunal & Withdrawal of Appeal

- **Key rule(s):**
  - GSTAT may **confirm, modify or annul** the decision/order appealed against, or may **refer the case back** to the Appellate/Revisional Authority or original adjudicating authority for fresh disposal.
  - An appeal, once filed and **final acknowledgement issued**, may be withdrawn only with the **permission of GSTAT** (Rule 113A / FORM GST APL-08 procedure) — withdrawal is not a matter of right after final acknowledgement.
- **Concept:** GSTAT's order is the last forum on facts; onward appeal (to HC/SC) is confined to substantial questions of law.
- **Pitfalls / exam tips:** ⚠️ VERIFY — precise rule number/FORM for withdrawal (post final acknowledgement) as printed in the OCR was illegible; the underlying principle (GSTAT permission required after final acknowledgement) is settled, confirm the rule/form number before quoting it in an answer.

### Appeal to High Court [Section 117]

- **Key formula(s)/rule(s):**
$$\text{Time limit to file appeal} = 180 \text{ days from the date on which the order appealed against is received}$$
  - High Court can **condone delay** beyond 180 days if satisfied there was sufficient cause.
  - Appeal lies only if the High Court is satisfied the case involves a **substantial question of law**.
- **Concept:** Appeal from an order of a **State Bench or Area Bench** of GSTAT (i.e., not from National/Regional Bench orders, which skip the High Court).
- **Pitfalls / exam tips:** The 180-day period runs from **receipt** of the order, not from the date the order is passed — watch for this distinction in numericals.

### Appeal to Supreme Court [Section 118]

- **Key rule(s):**
  - Appeal lies to the Supreme Court from: (a) any order passed by the **National Bench or a Regional Bench** of GSTAT (place-of-supply matters); or (b) a **judgment/order of the High Court** in an appeal under Section 117, in a case which the High Court **certifies to be a fit one for appeal** to the Supreme Court.
- **Concept:** Final appellate forum; largely restricted to substantial questions of law and place-of-supply determinations.
- **Definitions:**

| Term | Meaning |
|---|---|
| National/Regional Bench (GSTAT) | Benches exclusively empowered to decide disputes involving **place of supply** |
| State/Area Bench (GSTAT) | Benches for all other GST disputes; their orders route through the High Court |

### Sums Due Notwithstanding Appeal & Monetary Limits [Sections 119–120]

- **Key rule(s):**
  - **Sec. 119:** Amounts due under an order continue to be payable/recoverable notwithstanding that an appeal has been preferred, except to the extent stayed by the appellate forum or covered by pre-deposit.
  - **Sec. 120:** CBIC may, to regulate the filing of appeal by the **Department** and reduce litigation, fix **monetary limits** below which the department will not file an appeal. Non-filing due to such a limit does **not** amount to acquiescence, and does **not** preclude the department from filing an appeal on the same/similar issue in another case where the limit is crossed.
  - Current CBIC monetary limits for department appeals (Circular No. 207/1/2024-GST, 26-Jun-2024):
    - **₹20 lakh** — before GSTAT
    - **₹1 crore** — before High Courts
    - **₹2 crore** — before the Supreme Court
    - (These limits do **not** apply where a provision of the GST law has been held ultra vires the Constitution.)
- **Concept:** Sec. 120 is a litigation-management tool for the tax department, not a taxpayer right.
- **Pitfalls / exam tips:** ⚠️ VERIFY — monetary limits are set by circular/instruction (currently Circular No. 207/1/2024-GST) and are revised periodically by CBIC; reconfirm the figures against the latest circular applicable to your attempt before quoting them in the exam.

### Non-Appealable Decisions and Orders [Section 121]

- **Key rule(s) — no appeal lies against:**
  - An order to transfer proceedings from one officer to another;
  - An order pertaining to the seizure or retention of books of account/documents;
  - An order sanctioning prosecution; or
  - An order allowing payment of tax/other dues in **instalments**.
- **Concept:** These are essentially administrative/procedural orders, not orders determining tax liability, hence kept outside the appeal mechanism.

### Cross Empowerment of Officers [Section 6]

- **Key rule(s):**
  - Officers appointed under the **SGST/UTGST Act** are also authorised to act as proper officers for **CGST Act** purposes, and vice versa, subject to conditions notified on the recommendation of the GST Council.
  - Where a proper officer under one Act (say SGST) initiates any proceeding on a subject matter, the proper officer under the other Act (CGST) shall **not** initiate proceedings on the **same subject matter**.
  - If an order is passed by a CGST officer, any rectification, appeal, review or revision of that order lies **only with CGST authorities** (never SGST/UTGST authorities), and vice versa.
- **Concept:** Prevents parallel/duplicate proceedings by Centre and State tax authorities on the same taxpayer for the same issue, while enabling either administration's officers to act for the other.

### Authorised Representative — Disqualifications [Section 116]

- **Key rule(s) — a person is disqualified from acting as an authorised representative if he:**
  - Has been **dismissed or removed** from Government service; or
  - Has been **convicted** of an offence connected with any proceeding under GST/earlier indirect tax laws involving moral turpitude; or
  - Is found guilty of **misconduct** by the prescribed authority; or
  - Has been **adjudged insolvent** (disqualification continues, in relevant cases, until the disqualification period notified/prescribed expires).
- **Concept:** Section 116 lets a registered person appear personally or through an authorised representative (relative, employee, advocate, CA/CMA/CS, retired officer, GST practitioner, etc.) before any authority/Appellate Authority/GSTAT; Section 116 read with the disqualification rules screens out unfit representatives.
- **Pitfalls / exam tips:** ⚠️ VERIFY — the OCR source for this list was garbled; the categories above reflect the settled statutory position, but cross-check the exact wording/duration of each disqualification ground against the bare Act before an answer that quotes it verbatim.

### Relevant Forms (Quick Reference)

| Form | Purpose |
|---|---|
| GST APL-01 | Appeal to Appellate Authority (by taxpayer) |
| GST APL-02 | Acknowledgement of appeal filed with Appellate Authority |
| GST APL-03 | Appeal to Appellate Authority by the Department (Sec. 107(2)) |
| GST APL-04 | Summary of the demand after issue of order by Appellate Authority/Tribunal |
| GST APL-05 | Appeal to Appellate Tribunal (GSTAT) |
| GST APL-06 | Cross-objections before Appellate Tribunal |
| GST APL-08 | Withdrawal of appeal |

### References

1. CBIC, "CGST Act, 2017 — Chapter XVIII (Sections 107–121): Appeals and Revision," bare act text, cbic.gov.in.
2. Finance (No. 2) Act, 2024 and CBIC Circular/press coverage — reduction of pre-deposit cap under Sections 107(6)/112(8) to ₹20 crore and 10%, effective 1 Nov 2024 (Taxmann/ClearTax analysis).
3. CBIC Circular No. 207/1/2024-GST dated 26-06-2024 — monetary limits for department appeals before GSTAT (₹20 lakh), High Courts (₹1 crore) and Supreme Court (₹2 crore).
4. Finance Act, 2023 — constitution of GST Appellate Tribunal (Principal Bench + State Benches; place-of-supply matters to Principal/National Bench); GSTAT operationalisation updates 2025–26 (PIB press release; GSTAT official portal, gstat.gov.in).
5. Analysis of Section 108 (Revisional Authority) limitation — "later of 3 years from original order / 1 year from appellate order" (TaxTMI case-law commentary).

## 12. Liability to Pay in Certain Cases, Advance Ruling & Miscellaneous Provisions

> **Where it fits:** This chapter covers three distinct blocks under the CGST Act — (i) who is fastened with GST liability in special situations (business transfer, liquidation, death, agency, HUF partition, etc. — Sections 85–94), (ii) the Advance Ruling mechanism that lets a taxpayer get binding clarity before undertaking a transaction (Sections 95–106), and (iii) residual "housekeeping" provisions (confidentiality, service of notice, rounding off, anti-profiteering, track & trace) that recur as 1-2 mark objective/theory questions.

### Liability in Case of Transfer of Business [Section 85]

- **Key rule(s):**
  - Where a taxable person transfers business in whole or part by sale, gift, lease, licence, hire, or any other manner, or the business is transferred on account of **death** of a sole proprietor, the **transferor and transferee are jointly and severally liable** to pay tax, interest or penalty due up to the time of transfer, whether such dues are determined before or after the transfer.
  - If the transferee **carries on the business** (does not merely hold the transferred stock), the transferee is liable to be registered and pay tax on supplies made **on or after the date of transfer** as if it were the taxable person.
- **Concept:** Prevents dues from escaping recovery merely because the business changed hands; liability travels with the business.
- **Pitfalls / exam tips:**
  - Liability is joint & several for the *pre-transfer* period only, unless the transferee continues the business — for the *post-transfer* period only the transferee (now registered) is liable.
  - "Transfer" includes death of sole proprietor — do not assume Section 93 (death cases) alone covers this; Section 85 specifically deals with business transfer including transfer *by reason of* death.

### Liability of Agent and Principal [Section 86]

- **Key rule(s):**
  - Where an **agent supplies or receives goods on behalf of a principal**, the agent and the principal are **jointly and severally liable** to pay the tax payable on such goods.
- **Concept:** Protects revenue where goods move through an agent (e.g., commission agent, del credere agent) — both parties in the supply chain can be pursued.
- **Pitfalls / exam tips:** Distinguish from Section 91–94 "agent for a minor/incapacitated person" — Section 86 is about a *commercial* principal-agent relationship in the supply chain, not fiduciary agency.

### Liability in Case of Amalgamation/Merger of Companies [Section 87]

- **Key rule(s):**
  - Where two or more companies are amalgamated/merged under an order of court/Tribunal with effect from a date **earlier than the date of the order**, and the companies have supplied/received goods or services between themselves during the period from the effective date till the date of the order:
    $$\text{Two or more merging companies} \;=\; \text{treated as distinct companies for that intervening period}$$
  - Such transactions are **liable to tax** as supplies between distinct persons, notwithstanding the amalgamation order, and the transactions are included in the turnover of the respective companies. The two companies are deemed to be a single new/amalgamated company only **with effect from the date of the order** for GST purposes.
- **Concept:** Stops entities from arguing "no supply" for the interim period between the appointed date and the actual court order date, since GST registration/return filing continued separately in that window.
- **Pitfalls / exam tips:** Key exam trap — students assume amalgamation is retrospective for GST too; it is NOT — GST treats the entities as separate up to the date of the order.

### Liability in Case of Company in Liquidation [Section 88]

- **Key rule(s):**
  - Every person (liquidator) appointed as receiver of company assets/liquidator of a company must, **within 30 days** of appointment, give intimation of appointment to the Commissioner.
  - The Commissioner shall, **within 3 months** from the date of receipt of such intimation, notify the liquidator of the amount sufficient to provide for tax, interest and penalty payable by the company.
    $$\underbrace{\text{Intimation by liquidator}}_{\le 30\text{ days of appointment}} \;\longrightarrow\; \underbrace{\text{Commissioner notifies amount}}_{\le 3\text{ months of intimation}}$$
  - The liquidator must not part with the assets of the company until the above amount is set aside; if he contravenes this and tax/interest/penalty remains unrecovered, the liquidator is **personally liable** for such dues.
- **Concept:** Ring-fences GST dues against the assets of a company going into liquidation.
- **Pitfalls / exam tips:** Two distinct timelines — 30 days (liquidator → Commissioner) and 3 months (Commissioner → liquidator) — a favourite fill-in-the-blank in MCQs.

### Liability of Directors of Private Company [Section 89]

- **Key rule(s):**
  - Where tax, interest or penalty due from a **private company** cannot be recovered, **every person who was a director** of that company during the period to which the dues relate shall be **jointly and severally liable**, unless he proves that the non-recovery cannot be attributed to any **gross neglect, misfeasance or breach of duty** on his part.
  - This liability continues to apply even where the private company is **converted into a public company** — directors remain liable for dues relating to the period they were directors of the (then) private company.
- **Concept:** Pierces the corporate veil for GST dues, mirroring the Companies Act approach to director liability of private companies.
- **Pitfalls / exam tips:** Burden of proof is on the **director** to show absence of negligence/breach of duty — it is not for the department to prove fault.

### Liability of Partners of Firm [Section 90]

- **Key rule(s):**
  - A **firm and every partner** of the firm shall be **jointly and severally liable** for payment of tax, interest or penalty due from the firm.
  - Where a partner **retires**, he (or the firm) must intimate the retirement to the jurisdictional Commissioner **in writing**:
    - If intimated **within 1 month** of retirement → retiring partner is liable **only up to the date of retirement**.
    - If **not intimated within 1 month** → retiring partner remains liable **until the date such intimation is received** by the Commissioner.
- **Concept:** Prevents a retiring partner from silently exiting the firm to dodge accrued/future GST dues.
- **Pitfalls / exam tips:** The 1-month clock runs from the date of retirement, not from the date of the partnership deed change — and liability without timely intimation can extend well beyond the actual retirement date.

### Other Special Persons — Guardian, Trustee, Court of Wards, Death, HUF/Firm Dissolution [Sections 91–94]

- **Key rule(s) — Section 91 (Guardian/Trustee/Agent):** Where the business of a **minor or incapacitated person** is carried on by a guardian, trustee or agent on the minor's/incapacitated person's behalf, tax is leviable on, and recoverable from, such guardian/trustee/agent **in like manner and to the same extent** as it would be leviable on the minor/incapacitated person, had he been of full age or capacity.
- **Key rule(s) — Section 92 (Court of Wards, etc.):** Where the estate of a taxable person is under the control of a **Court of Wards, Administrator General, Official Trustee, Receiver or Manager** appointed by/under order of a court, tax is leviable on and recoverable from such person **to the same extent** as from the person whose estate is so controlled.
- **Key rule(s) — Section 93 (Special provision on death / discontinuance):**
  - Where a person liable to pay tax **dies**:
    - If the **business is continued** by the legal representative or any other person → such person is liable to pay tax, interest and penalty due.
    - If the **business is discontinued** → the legal representative is liable to pay dues out of the estate of the deceased, to the extent the estate is capable of meeting the liability.
  - **Partition of HUF/AOP** → every member/group is jointly and severally liable to the extent of dues remaining unpaid, calculated on the position immediately before partition.
  - **Dissolution of a firm** → every partner remains jointly and severally liable for dues up to the date of dissolution, whether determined before or after dissolution.
- **Key rule(s) — Section 94 (Guardianship/trust terminated):** Where a business is carried on by a guardian/trustee/agent on behalf of a minor or other incapacitated person and **the guardianship or trust is terminated**, the minor/incapacitated person (now of full age/capacity) is liable to pay tax, interest and penalty in respect of the period during which the business was so carried on, to the extent the assets received are sufficient to meet the liability.
- **Concept:** Together, Sections 91–94 ensure GST dues survive changes in the person actually controlling/operating the business — fiduciary or accidental (death, partition, dissolution, termination of guardianship).
- **Pitfalls / exam tips:** In death-of-proprietor cases, always first classify "business continued" vs. "business discontinued" — the liable person and the extent of recovery (from estate vs. from continuing business) differ.

| Term | Meaning |
|---|---|
| Court of Wards | A statutory body managing estates of persons legally incapable of managing their own affairs (e.g., minors, persons of unsound mind) |
| Legal representative | A person who in law represents the estate of a deceased person |

### Advance Ruling — Basics, Definitions & Constitution of AAR/AAAR [Sections 95–96, 99–100]

- **Key rule(s):**
  - "**Advance ruling**" means a decision provided by the AAR or AAAR to an applicant on matters/questions specified in Section 97(2) [for AAR] or Section 100(1) [on appeal, for AAAR], in relation to the **supply of goods and/or services being undertaken or proposed to be undertaken** by the applicant.
  - Questions on which a ruling can be sought (Section 97(2)): (a) classification of goods/services, (b) applicability of a notification, (c) determination of time and value of supply, (d) admissibility of ITC, (e) determination of tax liability, (f) whether the applicant is required to be registered, (g) whether a particular activity amounts to/results in a "supply".
  - **Authority for Advance Ruling (AAR):** constituted for every State/UT — comprising one member from CGST and one member from SGST/UTGST.
  - **Appellate Authority for Advance Ruling (AAAR):** constituted for every State/UT — comprising the Chief Commissioner of CGST (jurisdictional) and the Commissioner of SGST/UTGST.
- **Concept:** Advance ruling gives a taxpayer **binding certainty before undertaking a transaction**, avoiding future disputes on classification/rate/ITC/registration questions.
- **Pitfalls / exam tips:** Ruling can only be sought for supply "being undertaken or proposed to be undertaken" — not for a past, already-completed transaction.

### Application, Procedure & Fee for Advance Ruling [Sections 97–98]

- **Key formula(s)/rule(s):**
  $$\text{Application fee to AAR} = ₹5{,}000 \text{ (CGST)} + ₹5{,}000 \text{ (SGST/UTGST)} = ₹10{,}000 \text{ total, in FORM GST ARA-01}$$
  - AAR forwards a copy of the application to the concerned officer and, if necessary, calls for relevant records.
  - Applicant given opportunity of hearing; application may be **admitted or rejected** — rejection only after giving the applicant an opportunity of being heard, and by way of a **speaking order**.
  - Ruling (or rejection order) must be pronounced **within 90 days** of receipt of the application.
  - Where members of AAR differ in opinion on any point, the point is referred to AAAR for hearing and decision.
- **Concept:** A fast, time-bound (90-day) quasi-judicial process at the State/UT level.
- **Pitfalls / exam tips:** Application cannot be rejected without a hearing — an oft-tested principle of natural justice under GST.

### Appeal to AAAR & Rectification of Advance Ruling [Sections 100–102]

- **Key formula(s)/rule(s):**
  - Appeal to AAAR may be filed by the **applicant** or by the **concerned/jurisdictional officer**, aggrieved by an AAR ruling.
  - Time limit: $$\text{Appeal within } 30 \text{ days of communication of ruling} \; (+30 \text{ days condonable for sufficient cause})$$
  - Appeal fee (applicant only; NIL for officer): $$₹10{,}000 \text{ (CGST)} + ₹10{,}000 \text{ (SGST/UTGST)} = ₹20{,}000 \text{ total, FORM GST ARA-02 (applicant) / ARA-03 (officer, no fee)}$$
  - AAAR must pass its order **within 90 days** of filing of the appeal.
  - If AAAR members differ in opinion, it is deemed that **no advance ruling can be issued** on the question referred.
  - **Rectification of mistake apparent from record:** AAR/AAAR may amend its order within **6 months** from the date of the order — suo motu, or on being pointed out by the applicant/concerned officer/jurisdictional officer. If the rectification has the effect of enhancing tax liability or reducing ITC, the applicant must be given an opportunity of being heard.
- **Concept:** A single, time-bound appellate layer with a rectification safety valve for clerical/apparent errors.
- **Pitfalls / exam tips:** No further statutory appeal beyond AAAR under GST law (only writ jurisdiction of High Court in practice) — a commonly tested "gap" in the advance ruling scheme.

### Applicability, Validity & Powers of Advance Ruling [Sections 103–106]

- **Key rule(s):**
  - **Binding effect (Section 103):** An advance ruling is binding only on (a) the applicant who sought it, and (b) the concerned/jurisdictional officer(s) in respect of the applicant — **not on other taxpayers or as a general precedent** — unless the law, facts or circumstances supporting the ruling change.
  - **Advance ruling void ab initio (Section 104):** If obtained by **fraud, suppression of material facts, or misrepresentation of facts**, the ruling is declared void and treated as if it had never been made; the period between the date of the ruling and the date of the void order is **excluded** while computing the limitation period for any demand proceedings.
  - **Powers (Section 105):** AAR/AAAR have the same powers as vested in a **civil court under the Code of Civil Procedure, 1908**, for matters such as discovery/inspection, summoning persons, compelling production of documents, and issuing commissions.
  - **Procedure (Section 106):** AAR/AAAR are empowered to regulate their own procedure for the matters within their jurisdiction.
- **Concept:** Balances taxpayer certainty (binding on the specific applicant) against revenue protection (void if fraudulently obtained).
- **Pitfalls / exam tips:** A ruling is *persuasive*, not binding, on other taxpayers with identical facts — a very common conceptual MCQ.

### Confidentiality & Consent-Based Information Sharing [Sections 158, 158A]

- **Key rule(s):**
  - **Section 158 — Disclosure of information by a public servant:** All particulars in any statement, return, accounts, documents or evidence produced/given under the Act are **confidential** and shall not be disclosed, **except** with the previous written permission of the Commissioner (or an officer authorised) and subject to prescribed safeguards, or when required (i) for prosecution proceedings, (ii) in a civil suit for recovery of any GST dues, or (iii) to an officer of Customs/Income-tax/SGST/other government agency for the purposes of that law, or (iv) to a court in the course of proceedings under the Act.
  - **Section 158A — Consent-based sharing of information:** Inserted by the Finance Act 2023 (notified effective **1 October 2023** vide Notification No. 28/2023-CT), it enables sharing — with the **express consent** of the supplier/recipient — of details furnished by a registered person (e.g., in the registration application, GSTR-1/GSTR-3B, e-invoice, e-way bill) with such other systems as may be notified, in the manner and subject to conditions prescribed.
- **Concept:** Section 158 protects taxpayer data as confidential by default; Section 158A carves out a limited, consent-driven exception to enable data portability (e.g., to banks/fintechs for credit assessment).
- **Pitfalls / exam tips:** ⚠️ VERIFY — as of the current syllabus date, the *systems* to which data may be shared under Section 158A, and the detailed manner/format of obtaining consent, remained largely un-notified/not operationalised even though the section itself is in force from 1.10.2023 — students should treat this as an enabling provision awaiting full rollout rather than an actively used mechanism.

### Compliance Rating [Section 149]

- **Key rule(s):**
  - Every registered person **may** be assigned a GST compliance rating score, based on the record of compliance, and such rating is to be placed on the common portal.
- **Concept:** Intended as a public, scaled indicator of a taxpayer's compliance track record (analogous to a credit score) that other businesses could factor in before dealing with a supplier.
- **Pitfalls / exam tips:** ⚠️ VERIFY — this provision remains on the statute book but the compliance-rating scale/mechanism/rules have **not been notified/operationalised** on the GST portal as of the current syllabus; do not assume a "1–10" or any other specific scale is in force — the OCR source's reference to a 1–10 scale could not be corroborated from an authoritative source and should not be quoted as a settled fact in the exam.

### Service of Notice [Section 169]

- **Key rule(s):** Any decision, order, summons, notice or other communication under the Act may be served by any one of the following modes:
  - Giving/tendering it directly, or by a messenger/courier, to the addressee or his manager/authorised representative/advocate/tax practitioner or a person regularly employed by him, or to an adult member of his family residing with him.
  - By registered post/speed post/courier with acknowledgement, to the last known address of business/residence.
  - By e-mail.
  - By making it available on the common portal (after login).
  - By publication in a newspaper circulating in the locality where the addressee is last known to have resided/carried on business.
  - By affixing it in a conspicuous place at the last known place of business/residence, and, if that is not practicable, by affixture at some conspicuous place in the office of the concerned officer, and a copy on the notice board.
- **Concept:** Multiple, layered modes ensure a valid deemed service even where direct/personal service is not possible.
- **Pitfalls / exam tips:** Service by affixture/newspaper is a "last resort" mode — used only when the standard modes fail; exam questions test which mode is used *in a given fact pattern*.

### Rounding Off of Tax [Section 170]

- **Key formula(s)/rule(s):**
  $$\text{Amount of tax, interest, penalty, fine, refund or any other sum payable/refundable} \;\longrightarrow\; \text{rounded off to the nearest whole rupee}$$
  - **50 paise or more** → round **up** to the next whole rupee.
  - **Less than 50 paise** → **ignore** (round down).
- **Concept:** A simple normalising rule applied to every payable/refundable amount computed under GST law.
- **Pitfalls / exam tips:** Applies to *every* rupee-and-paise figure under the Act (tax, interest, penalty, fine, refund) — not tax alone; commonly tested via a numeric MCQ (e.g., ₹100.50 → ₹101; ₹100.49 → ₹100).

### Anti-Profiteering [Section 171]

- **Key rule(s):**
  - Any **reduction in rate of tax** on any supply of goods/services, or the **benefit of input tax credit**, must be passed on to the recipient by way of a **commensurate reduction in prices**.
  - Original enforcement chain: National Anti-profiteering Authority (NAA) → functions transferred to the **Competition Commission of India (CCI)** with effect from **1 December 2022** → jurisdiction further transferred to the **Principal Bench of the GST Appellate Tribunal (GSTAT)** with effect from **1 October 2024**.
  - **Sunset clause:** The Government has notified **1 April 2025** as the sunset date — **no new anti-profiteering application/complaint/investigation is to be accepted on or after this date**; matters already pending as on that date continue to be examined/adjudicated by the Principal Bench of GSTAT.
- **Concept:** A consumer-protection mechanism ensuring GST rate cuts/ITC benefits are not pocketed by suppliers as extra margin — now time-barred for new cases.
- **Pitfalls / exam tips:** For 2026 attempts, remember the provision itself is **not repealed** — only *new* references/complaints are barred after 1 April 2025; legacy cases still run their course before GSTAT. Do not confuse this sunset date with the transfer-of-jurisdiction date (1 October 2024).

### Track and Trace Mechanism for Certain Goods [Section 148A]

- **Key rule(s):**
  - Section 148A, **inserted by the Finance Act, 2025**, is an enabling provision empowering the Government, on the recommendation of the GST Council, to notify a **Track and Trace Mechanism** for specified goods (or classes thereof) that are prone to tax evasion.
  - It provides for a system of affixing a **Unique Identification Marking** (UIM) — a digital stamp/mark or similar identifier that is unique, secure and non-removable — on notified goods or their packages, and for the **electronic storage and access of information** relating to such marking.
  - A corresponding definition of "Unique Identification Marking" has been inserted as clause (116A) in Section 2.
  - Every person dealing in notified goods must record and furnish details of the UIM affixed, in the manner/on the documents (e.g., tax invoice) as may be prescribed; goods without a valid UIM (where required) become liable to detention/seizure/confiscation under the general provisions of the Act.
- **Concept:** A supply-chain traceability tool (similar in spirit to track-and-trace regimes for tobacco/pan masala) to curb evasion in high-risk commodity categories.
- **Pitfalls / exam tips:** This is a **fresh (Finance Act 2025) enabling section** — the specific goods to be covered and the detailed procedure are notified separately by the Government/GST Council from time to time; the section only lays down the *framework*, so do not expect it to itself list which goods are covered.

### References

1. CGST Act, 2017 — Sections 85 to 94 (Chapter XVI: Liability to Pay in Certain Cases) — Analysis of Sections 85-94, TaxGuru (taxguru.in/goods-and-service-tax/analysis-section-85-94-gst-liability-cgst-act-2017.html); Section 88, Teachoo (teachoo.com).
2. CGST Act, 2017 — Sections 95 to 106 (Chapter XVII: Advance Ruling); Rule 104/106 CGST Rules — Advance Ruling under GST, Masters India; application/appeal fee and Rule 106 text, GSTZen/Taxscan (taxscan.in/application-to-gst-aar-and-appeal-to-gst-aaar).
3. CGST Act, 2017 — Section 158 & Section 158A (inserted by Finance Act 2023, effective 1.10.2023 vide Notification No. 28/2023-CT) — ClearTax, GST Gyaan.
4. CGST Act, 2017 — Section 171 (Anti-Profiteering); Notification on sunset date 1 April 2025 — Business Standard ("Govt notifies Apr 1, 2025, as sunset date for GST anti-profiteering"); GSTAT/CCI jurisdiction transfer coverage, Patron Accounting/Tribune.
5. Finance Act, 2025 — Section 148A (Track and Trace Mechanism) and new Section 2(116A) — Taxscan ("Track And Trace Mechanism to Check GST Evasion: Finance Bill 2025"); GST Gyaan, Section 148A summary.
6. CGST Act, 2017 — Sections 149 (Compliance Rating), 169 (Service of Notice), 170 (Rounding Off of Tax) — bare Act provisions (statutory text, not yet operationalised for Section 149 as of current syllabus).

## 13. Customs - Basics, Levy, Types of Duty & Exemptions (incl. Baggage & Stores)

> **Where it fits:** This chapter lays the foundation of the Customs Act, 1962 — where the levy attaches, what duties can stack on an import, when the whole thing can be waived, and the special (concessional) regimes for passenger baggage and ship/aircraft stores. Everything you compute in Valuation (Ch.14) and Procedures (Ch.15) sits on top of the concepts here.

### Territorial Reach of Customs Law

- **Key formula(s)/rule(s):**
  - Territorial waters of India extend to **12 nautical miles** from the base line.
  - Exclusive Economic Zone (EEZ) extends to **200 nautical miles** from the base line.
  - "Indian Customs Waters" [Section 2(28)] = territorial waters of India **+** the EEZ (i.e., up to 200 NM) — customs officers' powers of search/seizure extend up to this limit.
  - Customs Act extends to the **whole of India** (and, per Section 1(2), to Indian Customs Waters as above for enforcement purposes).

- **Concept:** "India" for customs purposes is wider than the landmass — it includes territorial waters, and enforcement jurisdiction (chase, seizure) extends further into the EEZ.

- **Pitfalls / exam tips:**
  - Do not confuse 12 NM (territorial waters — sovereignty) with 200 NM (EEZ — economic/enforcement rights only, not full sovereignty).
  - Merely entering territorial waters does **not** by itself complete the taxable event of "import" — see next topic.

- **Definitions:**

| Term | Meaning |
|---|---|
| Nautical mile | 1 NM ≈ 1.852 km |
| Indian Customs Waters | Territorial waters of India and the EEZ (up to 200 NM) — Section 2(28) |

---

### Levy of Customs Duty — Charging Section & Taxable Event

- **Key formula(s)/rule(s):**
  - **Section 12** (charging section): duties of customs shall be levied on goods **imported into**, or **exported from**, India, at the rates specified under the Customs Tariff Act, 1975 (or any other applicable law).
  - "Import" [Section 2(23)] = bringing goods into India from a place outside India.
  - "Export" [Section 2(18)] = taking goods out of India to a place outside India.
  - Taxable event for **import** duty = when goods cross the **customs barrier**, not merely on entering territorial waters (settled by Supreme Court, e.g., *Kiran Spinning Mills* and *Garden Silk Mills*) — for warehoused goods this effectively lands on the date of clearance from the warehouse.
  - Taxable event for **export** duty = when goods actually leave Indian territory / the Let Export Order is passed.

- **Concept:** Section 12 is the "Section 9 of CGST" equivalent for Customs — it fixes *what* is taxed; Sections 15 & 16 (below) fix *when* (rate/valuation date) it is taxed.

- **Pitfalls / exam tips:**
  - Students often wrongly assume duty is levied the moment the vessel enters territorial waters — always cite the "customs barrier crossing" test.
  - For home-consumption goods vs warehoused goods, the *point of taxability* effectively shifts to the bill-of-entry / ex-bond clearance date (Section 15), not the date of physical arrival.

---

### Date for Determination of Rate of Duty & Valuation (Sections 15 & 16)

- **Key formula(s)/rule(s):**
  - **Section 15 — Imported goods**, rate/valuation applicable is that **in force on**:
    (a) the date of presentation of the Bill of Entry, for goods entered for home consumption (Section 46);
    (b) the date of actual removal of goods from the warehouse, for ex-bond clearance (Section 68);
    (c) the date of payment of duty, for any other goods.
    - *Proviso:* if the Bill of Entry is presented **before** the entry inwards of the vessel (or arrival of the aircraft/vehicle), it is deemed to have been presented on the date of such entry inwards/arrival.
  - **Section 16 — Export goods**, rate/valuation applicable is that **in force on**:
    (a) the date on which the proper officer makes an order permitting clearance and loading of goods for exportation (the **Let Export Order**), for goods entered for export (Section 51);
    (b) the date of payment of duty, for any other goods.
  - Sections 15 & 16 do **not** apply to baggage and goods exported/imported by post (separate rules apply there).

- **Concept:** These sections answer "which day's tariff rate applies" — critical whenever rates change between shipment and clearance.

- **Pitfalls / exam tips:**
  - Advance Bill of Entry filed early does **not** lock in the earlier (possibly lower) rate — the deeming proviso pushes it to the vessel's entry-inwards date.
  - For exports, it's the **Let Export Order date**, not the shipping bill filing date, that fixes the rate.

- **Definitions:**

| Term | Meaning |
|---|---|
| Bill of Entry (BOE) | Import declaration filed by importer for clearance under Section 46 |
| Let Export Order (LEO) | Proper officer's order under Section 51 permitting export clearance/loading |

- **References:** [1]

---

### Types of Customs Duty on Imports — Building the Duty Stack

- **Key formula(s)/rule(s):** (typical computation table, values illustrative)

$$
\begin{aligned}
A &= \text{Assessable Value (Section 14)} \\
B &= A \times \text{BCD rate (Basic Customs Duty)} \\
C &= B \times 10\% \quad \text{(Social Welfare Surcharge — SWS)} \\
D &= A + B + \text{(Safeguard/Anti-dumping/CVD, if any)} \quad \text{[base for IGST]} \\
E &= D \times \text{IGST rate} \\
F &= D \times \text{GST Compensation Cess rate (if applicable)} \\
\text{Total Duty Payable} &= B + C + E + F \, (+\, \text{Safeguard/ADD/CVD}) \\
\text{Landed Cost} &= A + \text{Total Duty Payable}
\end{aligned}
$$

  - **Social Welfare Surcharge (SWS)**: levied @ **10%** on the *aggregate of customs duties* (chiefly BCD), but its base **excludes** IGST, GST Compensation Cess, Safeguard Duty, Countervailing Duty (Section 9) and Anti-dumping Duty (Section 9A) — i.e., SWS is (in the plain-vanilla case) simply 10% of BCD.
  - **IGST on imports** [Section 3(7) of Customs Tariff Act, 1975] is levied on a value = Assessable Value **+** BCD **+** any other duty of customs chargeable (including Safeguard Duty/CVD/Anti-dumping Duty where applicable) — but **excluding** IGST and GST Compensation Cess themselves.
  - **GST Compensation Cess** [Section 3(9) of Customs Tariff Act] follows the same value base as IGST, where the imported goods are notified as cess-attracting (e.g., specified luxury/sin goods).

- **Concept:** Unlike SWS (narrow base), IGST/Cess have a *wider* base that picks up Safeguard/Anti-dumping/CVD — this asymmetry is a favourite trick in numericals.

- **Pitfalls / exam tips:**
  - Do **not** add Safeguard Duty/Anti-dumping Duty/CVD into the SWS base — they are specifically excluded by exemption notification.
  - IGST is **not** available as input tax credit for duty computation purposes here — that's a downstream ITC question, not a customs-duty-stack question.
  - Basic Customs Duty (BCD) itself is **not creditable** under GST (it is a cost); IGST paid on import **is** available as ITC to a registered importer.

- **Definitions:**

| Term | Abbrn. | Levied under |
|---|---|---|
| Basic Customs Duty | BCD | Section 12, Customs Act, 1962 |
| Social Welfare Surcharge | SWS | Finance Act, 2018 (replaced Education Cess/SHEC) |
| Integrated Tax on imports | IGST | Section 3(7), Customs Tariff Act, 1975 read with Section 5(1), IGST Act |
| Compensation Cess on imports | Cess | Section 3(9), Customs Tariff Act, 1975 read with GST (Compensation to States) Act |

- **References:** [2]

---

### Safeguard Duty (Section 8B, Customs Tariff Act, 1975)

- **Key formula(s)/rule(s):**
  - Central Government may impose safeguard duty where it is satisfied that **increased imports** of an article are causing or threatening **serious injury** to a domestic industry.
  - Safeguard duty is computed on the **assessable value** determined under Section 14 of the Customs Act.
  - **Provisional** safeguard duty can be levied pending final determination, for a **maximum of 200 days**.
  - **Overall time limit:** safeguard duty (including any extension) cannot continue beyond **10 years** from the date first imposed.
  - **Developing-country exemption:** no safeguard duty on an article originating from a developing country so long as:
    - imports of that article from that country are **less than 3%** of total imports of that article into India; **and**
    - where more than one developing country is involved, the **aggregate** of imports from all such developing countries (each individually below 3%) does **not exceed 9%** of total imports of that article into India.
  - Not applicable to articles imported by a 100% EOU/SEZ unit unless specifically made applicable, or unless such goods are cleared into the DTA.

- **Concept:** A temporary "shock absorber" duty for a genuine import surge, distinct from anti-dumping/CVD which target *unfair* trade practices (dumping/subsidy) rather than a mere volume surge.

- **Pitfalls / exam tips:**
  - Students often mix up the individual threshold (3%) with the aggregate threshold (9%) — remember "3 for one, 9 for many."
  - Safeguard duty is **not** subject to exemption under Section 25 general/specific exemption notifications in the way BCD is, and drawback/other duty exemptions generally do not extend to it either.

- **References:** [3]

---

### Anti-Dumping Duty (Section 9A) & Countervailing Duty (Section 9), Customs Tariff Act, 1975

- **Key formula(s)/rule(s):**
  - **Anti-dumping duty (ADD)** [Section 9A]: levied when an article is **exported to India at less than its normal value**, causing/threatening material injury to a domestic industry.

$$
\text{Margin of Dumping} = \text{Normal Value} - \text{Export Price}
$$

  - ADD imposed cannot exceed the margin of dumping.
  - **Validity:** ADD is normally valid for **5 years** from date of imposition, extendable for further period(s) of **5 years each** via sunset review (unless revoked earlier); if temporarily revoked, such revocation cannot exceed **1 year at a time**.
  - **Countervailing Duty (CVD)** [Section 9]: levied on **subsidised articles** imported into India, to offset the effect of an export subsidy given by the exporting country.
  - ADD/CVD are **product- and country/exporter-specific** and are additional to BCD; not applicable to goods imported by a 100% EOU/SEZ unit unless the goods are cleared to the DTA (subject to conditions), and generally not applicable to goods originating from certain WTO "most favoured nation" developing-country contexts as per the specific exemption clauses in each section.

- **Concept:** ADD counters *dumping* (below-normal-value pricing by the exporter); CVD counters *subsidisation* (export subsidy by the exporting government) — both are trade-remedy duties distinct from the volume-based Safeguard Duty.

- **Pitfalls / exam tips:**
  - Don't confuse "margin of dumping" (Normal Value − Export Price, for ADD) with "extent of subsidy" (basis for CVD quantum).
  - Appeals against ADD/CVD notifications lie with **CESTAT** under Section 9C of the Customs Tariff Act.

- **Definitions:**

| Term | Meaning |
|---|---|
| Normal Value | Comparable price of the like article in the ordinary course of trade in the exporting country |
| Export Price | Price at which the article is actually exported to India |
| Dumping Margin | Normal Value − Export Price |

- **References:** [3][4]

---

### Power to Grant Exemption (Section 25, Customs Act, 1962)

- **Key formula(s)/rule(s):**
  - **Section 25(1)** — General exemption: Central Government may, by **notification**, exempt goods (absolutely or subject to conditions) from the whole or part of the customs duty leviable.
  - **Section 25(2)** — Special order (ad hoc) exemption: in circumstances of an **exceptional nature**, by special order (not a notification), exempt duty on goods of strategic/secret nature or for charitable purposes, etc. — reasons must be recorded and the order must be published (unless impracticable).
  - **Section 25(4A)** (inserted by Finance Act, 2021): every **conditional** exemption notification issued under Section 25(1) shall, unless otherwise specified/varied/rescinded, be valid only **up to 31st March falling immediately after 2 years** from the date of the notification; it can be **extended** for further period(s) via a fresh notification. This sunset rule does **not** apply to *absolute* exemptions or where the notification itself states otherwise.

- **Concept:** Section 25 is the customs analogue of Section 11 (CGST)/Section 6 (IGST) exemption powers — it lets the government fine-tune the effective duty rate without amending the Customs Tariff Schedule itself.

- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — the 2-year sunset clock under Section 25(4A) runs from the date of the notification, ending on the *next* 31 March after 2 years elapse (not a flat 2-year anniversary date) — this "31 March" nuance is easy to state imprecisely; double-check against the current Bare Act/latest amendment before the exam.
  - The sunset rule (25(4A)) applies only to **conditional** exemptions — absolute exemptions are not time-bound by this sub-section.

- **References:** [5]

---

### Remission / Abatement of Duty — Pilfered, Damaged, Lost or Abandoned Goods

- **Key formula(s)/rule(s):**
  - **Section 13 — Pilfered goods:** no duty is payable on goods pilfered **after unloading but before the order for clearance for home consumption or deposit in a warehouse is made** — *unless* the pilfered goods are subsequently restored to the importer.
  - **Section 22 — Abatement of duty on damaged/deteriorated goods:** duty is abated proportionately where imported goods are found damaged/deteriorated before or during unloading, or (for warehoused goods) damaged before clearance, on account of an accident (not due to willful act/negligence of the importer).
  - **Section 23(1) — Remission of duty on lost/destroyed goods:** where imported goods are lost (otherwise than as a result of pilferage) or destroyed at any time **before clearance for home consumption**, the Assistant/Deputy Commissioner shall remit the duty.
  - **Section 23(2) — Relinquishment of title:** the owner may relinquish his title to imported goods at any time **before an order for clearance for home consumption is made**, and shall then not be liable to pay duty — but *only if* the goods are not already released for home consumption/warehousing, and the importer bears any resultant charges (rent/demurrage) already incurred.

- **Concept:** These four provisions cover the spectrum of "goods vanish/spoil/get abandoned" before the duty point crystallises — "Pilfered" (petty theft after unloading) is treated most leniently (no duty at all), while damage merely reduces (abates) duty proportionately.

- **Pitfalls / exam tips:**
  - "Pilferage" ≠ "loss/theft in bulk" — pilferage specifically means petty/small-quantity theft; large-scale loss falls under Section 23(1), not Section 13.
  - Relinquishment under Section 23(2) is a *pre-clearance* right only — once the importer files for home consumption and clears the goods, the right is lost.
  - If pilfered goods are later restored to the importer, duty becomes payable again on restoration.

- **Definitions:**

| Term | Meaning |
|---|---|
| Pilferage | Petty/small-scale theft of part of a consignment after unloading |
| Relinquishment of title | Importer voluntarily gives up ownership/claim to the goods, in lieu of duty liability |

- **References:** [1]

---

### Re-importation of Goods (Section 20)

- **Key formula(s)/rule(s):**
  - Goods re-imported into India (having been exported earlier) are chargeable to duty as if the re-import were a fresh import, at the rate applicable on the date of re-import, subject to any exemption notification (e.g., for goods re-imported after repair, or for reimport of goods exported earlier under bond/LUT/duty drawback claim) which may reduce the effective duty to a value proportionate to cost of repairs, freight/insurance, etc.

- **Concept:** Prevents "duty-free round tripping" while giving relief for genuine repair/return-for-repair movements via specific exemption notifications (not a blanket exemption under Section 20 itself).

- **Pitfalls / exam tips:**
  - Where goods were exported under an export-incentive scheme (drawback claimed / bond-LUT without IGST payment / rebate), reimport typically triggers a "duty on reimport" liability equal to the benefit originally availed, unless the specific exemption notification conditions are met.

---

### Stores (Sections 85–90, Customs Act)

- **Key formula(s)/rule(s):**
  - "Stores" [Section 2(38)] = goods for use in a vessel or aircraft, including fuel, spare parts and other articles of equipment (whether or not for immediate fitting).
  - Imported stores on board a vessel/aircraft proceeding to a foreign port may be consumed on board **without payment of duty** (Section 87), subject to conditions.
  - Stores may be **transhipped**/exported without payment of duty where the ship/aircraft is proceeding to a foreign destination (Sections 85–89 collectively deal with warehousing, transit, and export of stores).
  - Imported stores required as spares/equipment for the vessel/aircraft itself (not for the crew's personal consumption) get duty-free treatment under conditions specified by the CBIC.

- **Concept:** "Stores" recognises that a vessel/aircraft engaged in international traffic is like a "moving warehouse" — duty is deferred/exempted as long as the goods are genuinely used for/consumed on the vessel/aircraft in the course of its voyage, not diverted into the domestic market.

- **Pitfalls / exam tips:**
  - Stores provisions are frequently tested alongside Baggage as the "special persons/conveyances" chapter-end topic — don't confuse crew's personal baggage allowance (under Baggage Rules) with the vessel's "stores" (under Sections 85-90).

---

### Baggage — General Free Allowance & Restricted Items

- **Key formula(s)/rule(s)** (Baggage Rules, 2016):
  - **Rule 3 — GFA for Indian resident/foreigner residing in India/tourist of Indian origin** (not an infant), arriving from any country **other than Nepal, Bhutan or Myanmar**: duty-free bona fide baggage up to **₹50,000** in value.
  - **Rule 4 — GFA for passengers arriving from Nepal, Bhutan or Myanmar**: duty-free bona fide baggage up to **₹15,000** in value (carried on person / in accompanied baggage).
  - The free allowance of one passenger **cannot be pooled** with that of any other passenger.
  - Items listed in **Annexure I** (e.g., firearms; cartridges exceeding 50; cigarettes exceeding 100 sticks or cigars exceeding 25 or tobacco exceeding 125 g; alcoholic liquor/wine exceeding 2 litres; gold or silver in any form other than ornaments; flat panel TV) are **not eligible** for the GFA — they are separately dutiable/restricted regardless of value.
  - **Section 80 — Temporary detention of baggage:** where a passenger's baggage contains dutiable/prohibited articles that he does not wish to clear immediately, the proper officer may allow temporary detention of such articles (free of duty) for the passenger to collect on leaving India, or have them sent to another passenger/consignee.

- **Concept:** GFA is the customs-duty-free threshold for a bona fide traveller's personal effects/gifts, calibrated lower for the land-border-adjacent Nepal/Bhutan/Myanmar routes.

- **Pitfalls / exam tips:**
  - ⚠️ VERIFY — confirm the *current* Annexure-I quantity/value thresholds (cartridges, cigarettes, liquor, gold/silver) against the latest Baggage Rules text before the exam, since these limits are occasionally revised by CBIC notification.
  - GFA figures (₹50,000 / ₹15,000) are **per passenger**, non-poolable, and apply only to *bona fide* baggage — commercial quantities are excluded regardless of value.
  - Crew members get a much lower separate GFA (not the passenger ₹50,000/₹15,000 figure) — don't apply passenger limits to crew.

- **Definitions:**

| Term | Meaning |
|---|---|
| General Free Allowance (GFA) | Value-based duty-free threshold for bona fide baggage of an eligible passenger |
| Annexure I goods | Specified goods (firearms, excess liquor/tobacco, bullion, flat-panel TV, etc.) excluded from GFA benefit |
| Bona fide baggage | Personal effects and articles of a traveller, other than articles imported for trade/commercial purpose |

- **References:** [6]

---

### References

1. Customs Act, 1962 — Sections 12, 13, 15, 16, 20, 22, 23, 25 (Bare Act, indiacode.nic.in / CBIC Tax Information Portal, taxinformation.cbic.gov.in).
2. Customs Tariff Act, 1975 — Section 3(7)/3(9) (IGST & GST Compensation Cess on imports); Finance Act, 2018 (introduction of Social Welfare Surcharge in place of Education Cess/SHEC on imported goods).
3. Customs Tariff Act, 1975 — Section 8B (Safeguard Duty) — developing-country 3%/9% exemption thresholds and 10-year overall time limit, as reflected in Bare Act text (indiacode.nic.in) and CBIC/professional commentary.
4. Customs Tariff Act, 1975 — Section 9 (Countervailing Duty) and Section 9A (Anti-dumping Duty), including the 5-year validity/sunset-review rule.
5. Customs Act, 1962 — Section 25, including Section 25(4A) inserted by the Finance Act, 2021 (sunset clause for conditional exemption notifications).
6. Baggage Rules, 2016 (as amended) — Rules 3 & 4 (General Free Allowance) and Annexure I — CBIC Tax Information Portal (taxinformation.cbic.gov.in).

## 14. Customs - Valuation, Importation & Exportation Procedures

> **Where it fits:** After the charging sections (Customs Act, 1962) fix *what* is dutiable and *when* the taxable event occurs, this chapter fixes *what value* duty is charged on (Customs Valuation Rules, 2007 — import & export) and the *procedural sequence* goods must pass through at the border (arrival/departure of conveyance, manifest filing, Bill of Entry/Shipping Bill, assessment, clearance, transit/transhipment).

### Basics of Valuation — Transaction Value & INCOTERMS

- **Key formula(s)/rule(s):**

$$
\text{Assessable Value (Import)} = \text{FOB value} + \text{Freight up to place of importation} + \text{Insurance}
$$

  (i.e., **CIF value**, converted to INR — landing/handling charges are **NOT** separately added since Notification No. 91/2017-Cus (NT); only *actual* charges for delivery *to* the place of importation are includible, the old notional 1% landing charge has been withdrawn.)

$$
\text{Assessable Value (Export)} = \text{FOB value of export goods (transaction value under Rule 3)}
$$

- Section 14, Customs Act, 1962 lays down that value shall be the **transaction value** — the price actually paid or payable for the goods when sold for export to India / for export from India, for delivery at the time and place of importation/exportation, where buyer and seller are not related and price is the sole consideration, subject to Rule 10 adjustments.
- Rate of exchange for conversion: the rate **notified by CBIC** (not RBI) prevailing on the **date of filing of the Bill of Entry (import)** under Section 46, or the **date of filing of Shipping Bill/Bill of Export (export)** under Section 50 — not the date of the contract, LC, or actual payment.
- **Concept:** Transaction value is the primary (and first-preference) method of valuation for both imports and exports; only when it cannot be applied/accepted do the sequential fallback methods (Rules 4–9) kick in.
- **Pitfalls / exam tips:**
  - Always identify FOB vs CIF vs Ex-Works terms given in a problem before applying additions — many exam numericals give Ex-Factory/FOB price and expect the student to gross up to CIF using Rule 10.
  - Exchange rate to use is the **CBIC-notified rate on date of presentation of BOE/SB**, a very common trap (students wrongly use RBI reference rate or contract-date rate).
  - If exchange rate changes between contract and arrival, the transaction value itself does not change merely due to price fluctuation in the international market between contract date and importation — actual price paid/payable is taken.

- **Definitions:**

| Term | Meaning |
|---|---|
| Transaction value | Price actually paid or payable for goods when sold for export to India (import) / for export (export), adjusted per Rule 10, where buyer & seller are unrelated and price is sole consideration |
| FOB | Free on Board — seller's cost/risk ends once goods are loaded on the vessel/aircraft at the port of shipment |
| CIF | Cost, Insurance and Freight — price includes cost of goods + insurance + freight to the port of destination |
| Bill of Entry (BOE) | Document filed by importer under Section 46 for clearance of imported goods (home consumption or warehousing) |
| Let Export Order (LEO) | Order passed by the proper officer under Section 51 permitting clearance of goods for exportation |

---

### Related Person — Rule 2(2), Customs Valuation (Determination of Value of Imported Goods) Rules, 2007

- **Key formula(s)/rule(s):** Persons are deemed "related" only if one or more of the following applies:
  - They are officers or directors of one another's business.
  - They are legally recognised partners in business.
  - Employer and employee.
  - Any person directly or indirectly owns, controls or holds **5% or more** of the outstanding voting stock/shares of both.
  - One of them directly or indirectly controls the other.
  - Both of them are directly or indirectly controlled by a third person.
  - Together they directly or indirectly control a third person.
  - They are members of the same family.
  - Sole agent/sole distributor/sole concessionaire of the other is also deemed related (Explanation to Rule 2(2)).
- **Concept:** If buyer and seller are related, transaction value (Rule 3) can still be accepted if the relationship did not influence the price, or if the transaction value closely approximates a "test value" (identical/similar goods transaction value, deductive value, or computed value in comparable transactions); otherwise Rules 4–9 apply sequentially.
- **Pitfalls / exam tips:**
  - "Related person" test in customs is an **exhaustive 8-limb list** — do not confuse with the wider "related person"/"distinct person" concept under GST (Schedule I / Section 15 CGST).
  - Mere fact that one is the sole agent/distributor of the other does not automatically mean price is influenced — it only creates a rebuttable presumption of relationship.

---

### Additions to Transaction Value — Rule 10, Customs Valuation (Import) Rules, 2007

- **Key formula(s)/rule(s):**

$$
\text{Rule 10 additions (to the extent not already included in price)} =
\begin{cases}
\text{Commission \& brokerage (except buying commission)} \\
\text{Cost of container treated as one with goods} \\
\text{Cost of packing (labour + material)} \\
\text{Value of goods/services ("assists") supplied by buyer free/at reduced cost} \\
\text{Royalties \& licence fees related to goods, paid as a condition of sale} \\
\text{Value of subsequent resale/use proceeds accruing to seller} \\
\text{Any other payment made as a condition of sale}
\end{cases}
$$

- **Cost of transport, loading, unloading & handling up to the place of importation:**
$$
\text{Sea/Inland waterway freight} = \text{Actual freight}; \quad \text{if not ascertainable} = 20\% \text{ of FOB value}
$$
$$
\text{Air freight} = \min(\text{Actual air freight},\ 20\% \text{ of FOB value})
$$
- **Cost of insurance:**
$$
\text{Insurance} = \text{Actual}; \quad \text{if not ascertainable} = 1.125\% \text{ of FOB value}
$$
- **Concept:** Rule 10 lists the only items that can be added to a genuine transaction value to arrive at the assessable value — nothing else may be loaded onto price.
- **Pitfalls / exam tips:**
  - Post-2017 (Notification 91/2017-Cus NT), the old flat **1% notional landing charge** on CIF is **abolished** — do not add it in current-syllabus numericals.
  - Buying commission paid by the importer to his own agent is **NOT** added (only selling commission/brokerage paid to the seller's agent is added).
  - Air freight has a **statutory cap of 20% of FOB** even if actual freight is higher; sea freight has **no such cap** (only a substitute figure of 20% FOB when freight is unknown).
  - Post-importation charges (e.g., erection, installation, interest on deferred payment, duties/taxes in India) are **excluded**.

---

### Determining Method of Valuation — Sequential Scheme (Rules 3–9), Import Goods

- **Key formula(s)/rule(s):** The rules apply in strict sequence — a later rule is used only if the earlier one fails:
  1. **Rule 3** — Transaction value of the goods being imported (subject to Rule 10 adjustments and Rule 12 acceptability check).
  2. **Rules 4 & 5** — Transaction value of **identical goods** / **similar goods** sold for export to India, at or about the same time, at the same commercial level and quantity (with adjustments); if more than one value is available, the **lowest** is adopted.
  3. **Rule 7** — **Deductive Value Method**:
$$
\text{Deductive Value} = \text{Unit price at which goods sold in greatest aggregate quantity to unrelated buyers in India (within 90 days of importation)} - \text{Usual profit \& general expenses} - \text{Usual commission/transport/insurance in India} - \text{Customs duties \& other taxes payable in India}
$$
  4. **Rule 8** — **Computed Value Method**:
$$
\text{Computed Value} = \text{Cost of materials \& fabrication/processing} + \text{Profit \& general expenses (as in sales of goods of same class/kind for export to India)} + \text{Cost of transport, loading, unloading, handling \& insurance up to place of importation (Rule 10(2))}
$$
  5. **Rule 9** — **Residual/Fallback Method**: value determined using reasonable means consistent with the principles of Rules 1–8 and available data (importer may request Rule 7/8 order to be reversed on written request; officer permitting).
- **Concept:** These are GATT/WTO Valuation Agreement-based methods, adopted almost verbatim into Indian law; Rules 4 and 5 are of **equal rank** (either may be applied, in that order, based on availability of data) before moving to Rules 7, 8, 9.
- **Pitfalls / exam tips:**
  - Order is NOT strictly linear between Rule 7 and Rule 8 — **importer may request** application of Rule 8 before Rule 7 (with the proper officer's consent); absent such request, Rule 7 precedes Rule 8.
  - Rule 9 (residual method) **cannot** be based on: selling price of goods produced in India, a system providing for acceptance of the higher of two alternative values, price of goods in the domestic market of the exporting country, cost of production other than computed values, price for export to a country other than India, minimum customs values, or arbitrary/fictitious values.
  - "Identical goods" = same in all respects (physical characteristics, quality, reputation) including country of origin & manufacturer (minor differences in appearance ignored); "similar goods" = not alike in all respects but has like characteristics/components and performs the same functions, is commercially interchangeable.
  - Where design/engineering work etc. was undertaken in India and supplied free/at reduced cost, goods are **not** treated as identical/similar for Rules 4/5 comparison.

- **Definitions:**

| Rule | Method |
|---|---|
| Rule 3 | Transaction value method (primary) |
| Rules 4 & 5 | Transaction value of identical / similar goods |
| Rule 7 | Deductive value (resale price in India worked backwards) |
| Rule 8 | Computed value (cost-plus, build-up method) |
| Rule 9 | Residual/fallback (best judgment, consistent with Rules 1–8) |
| Rule 10 | Adjustments/additions to transaction value |
| Rule 12 | Rejection of declared value by proper officer |

---

### Rejection of Declared Value — Rule 12, Customs Valuation (Import) Rules, 2007

- **Key formula(s)/rule(s):** Proper officer may reject the declared transaction value where he has **reason to doubt** the truth or accuracy of the declared value, based on grounds such as:
  - Significantly higher value of identical/similar goods imported at or about the same time.
  - Sale involving an abnormal discount or abnormal reduction from ordinary competitive price.
  - Misdeclaration of description, quality, quantity, country of origin, year of manufacture/production.
  - Non-declaration of parameters listed in Rule 11 (which requires the importer to furnish a declaration disclosing full & accurate value particulars).
  - Fraudulent or manipulated documents.
- **Concept:** Rejection under Rule 12 shifts valuation to Rules 4–9 sequentially — Rule 12 itself is **not** a valuation method, only a trigger/gateway.
- **Pitfalls / exam tips:** Reasons for doubting the truth/accuracy of value **must be recorded**, and importer must be given a reasonable opportunity of being heard before final rejection — natural justice safeguard often tested.

---

### Valuation of Export Goods — Customs Valuation (Determination of Value of Export Goods) Rules, 2007

- **Key formula(s)/rule(s):** Sequential scheme, mirroring the import rules but simpler:
  1. **Rule 3** — Transaction value (FOB price actually paid/payable) is the assessable value; if buyer & seller are related and relationship influences the price, move to Rules 4–6.
  2. **Rule 4** — Value of goods of **like kind and quality** exported at or about the same time to other buyers in the same or another destination country, with reasonable adjustments (for e.g. quantity, level of trade, distance, mode of transport).
  3. **Rule 5** — **Computed Value Method**:
$$
\text{Computed Value (Export)} = \text{Cost of production/manufacturing/processing of export goods} + \text{Charges for design or brand} + \text{Profit usually earned on such exports of same class/kind}
$$
  4. **Rule 6** — Residual method: reasonable means consistent with the principles and general provisions of these rules and Section 14 of the Customs Act.
- **Concept:** Export valuation exists mainly to prevent under-invoicing where an **export duty/cess** or an export-incentive-linked value cap applies (most Indian exports currently attract nil export duty, so this is largely relevant for the few dutiable exports, e.g., certain ores/iron & steel items, and for incentive-eligibility caps).
- **Pitfalls / exam tips:**
  - Do not confuse export Rule 4/5/6 numbering with import Rule 4/5/7/8/9 numbering — the export rules have **only 6 rules total** and a different sequence/numbering.
  - Exchange rate for export transactions is CBIC rate on date of filing the **Shipping Bill/Bill of Export** (Section 50), not the date of Let Export Order.

---

### Importation Procedure

- **Key formula(s)/rule(s) (chronological sequence):**
  1. **Arrival of conveyance [Section 29]** — person-in-charge of an aircraft/vessel entering India shall not land/call at any place other than a customs port/airport, except in cases of accident, stress of weather, or other unavoidable cause — and must then report to the nearest customs officer and not permit unloading without permission.
  2. **Import Manifest / Import Report [Section 30]** — person-in-charge (or authorised agent) must deliver the **Import General Manifest (IGM)** electronically:
     - Before arrival, in case of a **vessel or aircraft**.
     - Within **12 hours** of arrival, in case of a **vehicle**.
     - Delay attracts penalty unless the proper officer is satisfied there was sufficient cause.
  3. **Bill of Entry [Section 46]** — importer (other than for transit/transhipment goods) must file BOE electronically **before the end of the next day (excluding holidays)** following the day of arrival of the aircraft/vessel/vehicle; may be filed in advance (up to prescribed period before expected arrival). Types: **BOE for home consumption** (white), **BOE for warehousing** (into-bond, yellow), **Ex-bond BOE** (for clearance from a warehouse).
     - ⚠️ VERIFY — Late-filing charges under the second proviso to Section 46(3) are commonly cited as ₹5,000/day for the first 3 days of default and ₹10,000/day thereafter, waivable by the proper officer for sufficient cause; confirm current rate before quoting in an answer as it is prescribed by regulation and subject to periodic revision.
  4. **Assessment [Sections 17 & 18]** — **Self-assessment** by importer is the default; proper officer may verify/**re-assess**; **provisional assessment** under Section 18 where duty cannot be finally assessed (e.g., document/test pending), against an importer's bond/security, to be finalised normally **within 2 months** (extendable by the Principal Commissioner/Commissioner by further periods not exceeding 6 months at a time, for reasons recorded).
  5. **Clearance for home consumption [Section 47]** — proper officer permits clearance once satisfied goods are not prohibited and duty/charges are paid; may be through the **Risk Management System (RMS)** with electronic clearance; **deferred payment of duty** available to eligible importers (notified classes incl. AEO Tier-Two/Tier-Three) — duty for BOEs filed 1st–last day of a month (other than March) payable by the **1st day of the following month**; for BOEs filed in March, payable by **31st March**. Default beyond one occasion in 3 consecutive months forfeits the deferred-payment facility (restorable on payment of duty with interest).
  6. **Warehousing** — where importer wants to defer duty payment, goods may be deposited in a licensed warehouse under a bond (Section 59) instead of immediate home-consumption clearance.
- **Concept:** The chain runs Arrival → Manifest → Bill of Entry → Assessment → Duty payment → Clearance (or Warehousing) — each stage is a distinct compliance/document trigger tested via MCQ-style "what happens if X is delayed" questions.
- **Pitfalls / exam tips:**
  - "Date of arrival" (for BOE due-date purposes) = date of entry inward granted to the vessel or date of arrival of aircraft/vehicle, not date of unloading.
  - Self-assessment does not remove the proper officer's power of verification/re-assessment (Section 17(4)) — a very frequently tested distinction.
  - Provisional assessment differs from self-assessment: it applies specifically where duty cannot be determined finally at the time (pending test results, valuation dispute, EOU documents, etc.).

- **Definitions:**

| Term | Meaning |
|---|---|
| IGM | Import General Manifest — statement of all goods carried on the conveyance, filed by person-in-charge |
| Home consumption BOE | Filed when importer wants immediate clearance of goods into India on duty payment |
| Warehousing (into-bond) BOE | Filed when importer wants to store goods in a bonded warehouse, deferring duty |
| Ex-bond BOE | Filed for clearance of warehoused goods at the time duty is finally paid |
| RMS | Risk Management System — selects consignments for scrutiny/examination based on risk parameters, enabling facilitation (no-check) clearance for low-risk imports |

---

### Exportation Procedure

- **Key formula(s)/rule(s) (chronological sequence):**
  1. **Entry of goods for exportation / Shipping Bill or Bill of Export [Section 50]** — exporter must file electronically on the customs automated system; **Shipping Bill** for export by vessel/aircraft, **Bill of Export** for export by vehicle (land customs station).
  2. **Assessment & Let Export Order (LEO) [Section 51]** — proper officer, once satisfied goods are not prohibited and export duty (if any) has been paid, passes the **Let Export Order** permitting clearance for loading.
  3. **Entry Outward & permission to load [Sections 39 & 40]** — no imported/warehoused goods can be loaded until **Entry Outward** is granted for the vessel (not required for aircraft/vehicle); goods can be loaded only after a duly passed Shipping Bill/Bill of Export exists and, where a vessel is used, entry outward has been granted.
  4. **Export Manifest / Export Report [Section 41]** — person-in-charge must deliver an **Export General Manifest (EGM)** before departure of the conveyance.
  5. **Departure of conveyance** — person-in-charge cannot depart from India without a written order from the proper officer ("port clearance").
- **Concept:** Exportation runs in reverse compliance order relative to import — assessment/LEO happens **before** loading, unlike import where assessment happens after the goods have already arrived.
- **Pitfalls / exam tips:**
  - Do not conflate **Entry Outward** (a vessel-specific permission under Section 39, akin to "berthing/loading clearance") with the **Let Export Order** (goods-specific clearance under Section 51) — they operate at different levels (conveyance vs. consignment).
  - Once LEO is granted for a Shipping Bill, department **cannot** merge/club multiple shipping bills for reassessing export duty after the fact — each Shipping Bill stands on its own for assessment purposes.

- **Definitions:**

| Term | Meaning |
|---|---|
| Shipping Bill | Export entry document for goods exported by vessel/aircraft |
| Bill of Export | Export entry document for goods exported by land vehicle |
| Let Export Order (LEO) | Section 51 order by proper officer permitting export clearance/loading |
| Entry Outward | Section 39 permission allowing a vessel to load export cargo |
| EGM | Export General Manifest — list of all goods loaded on the conveyance, filed before departure |

---

### Transit & Transhipment of Goods [Sections 53 & 54]

- **Key formula(s)/rule(s):**
  - **Transit [Section 53]** — goods imported in a conveyance and mentioned in the import manifest/report as "for transit" in the **same conveyance** may be allowed to transit without payment of duty, to any place outside India or to another customs station in India.
  - **Transhipment [Section 54]** — goods imported into a customs station may be allowed to be **transhipped** (transferred to another conveyance) without payment of duty, for further transport to another customs station in India or to a place outside India, on filing a **Bill of Transhipment** (or, for goods to be transhipped under an international treaty/bilateral agreement, a Declaration of Transhipment).
- **Concept:** Transit = goods remain on the **same conveyance** and merely pass through; Transhipment = goods move to a **different conveyance** at an intermediate customs station — both occur without payment of import duty since the goods are not being cleared for home consumption in India.
- **Pitfalls / exam tips:** A classic exam example: a machine arriving at Mumbai port destined for Nepal that is moved to another vessel at Mumbai for onward carriage is **transhipment**; if it continued on the very same vessel it would be **transit**.

### References
1. Section 14, Customs Act, 1962 — Valuation of goods (transaction value basis).
2. Customs Valuation (Determination of Value of Imported Goods) Rules, 2007, Rules 2–12, and Customs Valuation (Determination of Value of Export Goods) Rules, 2007, Rules 3–6 — indiacode.nic.in / howtoexportimport.com summaries.
3. Notification No. 91/2017-Customs (N.T.) dated 26-09-2017 (CBIC) — removal of notional 1% landing charge from assessable value; CBIC Circular No. 39/2017-Customs.
4. Customs Act, 1962 — Sections 29, 30, 39, 40, 41, 46, 47, 50, 51, 53, 54 (arrival/departure of conveyance, manifest, Bill of Entry/Shipping Bill, clearance, transit & transhipment) — indiankanoon.org / bareacts.
5. Deferred Payment of Import Duty Rules, 2016 and CBIC Circular No. 08/2026-Customs — due dates and eligibility (AEO Tier-Two/Tier-Three, Eligible Manufacturer Importers) for deferred duty payment under Section 47(1).

## 15. Customs - Warehousing, Classification of Goods & Refund
> **Where it fits:** covers what happens to imported goods *between* import and home-consumption clearance (bonded warehousing, Ch. IX of the Customs Act), how goods are slotted into the tariff (Customs Tariff Act & General Rules of Interpretation), and how excess duty paid comes back to the importer (Sections 27/27A refund and unjust enrichment).

### Warehousing — Types & Bond [Sections 57–61]

- **Key rule(s):**
  - Customs duty is payable only on clearance for **home consumption**; while goods sit in a bonded warehouse, duty is *deferred*, not waived — importer executes a bond and (where required) security to protect revenue.
  - **Public warehouse [Sec. 57]:** licensed by Principal Commissioner/Commissioner; any importer may warehouse goods there.
  - **Private warehouse [Sec. 58]:** licensed to warehouse goods imported by or on behalf of the licensee only.
  - **Special warehouse [Sec. 58A]:** for notified (sensitive) goods; kept under physical customs lock/control.
  - **Warehousing bond [Sec. 59(1)]:** importer executes a bond for a sum equal to **thrice the duty assessed** on the goods, binding him to (a) comply with all warehousing conditions, (b) pay duty + interest u/s 61(2), and (c) pay fines/penalties for contraventions.
  - Bill of entry for warehousing is filed under Section 46 and goods are assessed under Section 17/18; the order permitting deposit into the warehouse is passed under **Section 60** ("into-bond" order).

- **Concept:** Warehousing lets an importer legally postpone duty payment/clearance of imported goods (and, in a manufacturing-in-bond warehouse, even carry out manufacture) without paying duty upfront, in exchange for a bond/security.

- **Pitfalls / exam tips:**
  - Don't confuse the *bond amount* (thrice the duty, Sec. 59) with the *duty itself* — the bond is security, not a payment.
  - Public vs private vs special warehouse is purely about **who** can use it and the degree of customs control, not about duty rates.

- **Definitions:**

| Term | Meaning |
|---|---|
| Into-bond bill of entry | BOE filed u/s 46 for warehousing (not home consumption) |
| Ex-bond bill of entry | BOE filed u/s 68 to clear warehoused goods for home consumption |
| Relevant date (warehousing) | Date used to fix rate of duty/exchange rate for warehoused goods cleared |

---

### Warehousing Period & Interest [Section 61]

- **Key rule(s)/thresholds:**
  - **Capital goods and other goods intended for use in a 100% EOU/EHTP/STP unit**, and goods in a warehouse where manufacture/other operations under **Section 65** are permitted → may remain warehoused **till clearance for home consumption** (no fixed time limit) and **no interest** is charged during this period.
  - **Any other warehoused goods:** ordinarily **1 year** from the date of the Section 60 order, extendable by the competent officer (Commissioner, and beyond that by the Principal/Chief Commissioner in specified circumstances) on sufficient cause; if goods are found to be deteriorating, the period can be shortened.
  - **Interest on warehoused goods [Sec. 61(2)]:** first **90 days** from the date of deposit (i.e., the Sec. 60 order) are interest-free; interest is payable **from the expiry of 90 days** (or the extended interest-free period, if any) **till the date of payment of duty**, at a rate not exceeding the rate specified under **Section 47** — currently notified at **15% p.a.**
  - If goods remain warehoused beyond the *permitted* period without extension, they are deemed **improperly removed [Section 72]** and the proper officer can demand duty, interest, rent and charges as if cleared for home consumption on that date.

- **Concept:** The 90-day interest-free window rewards quick clearance; interest is the price of using the warehouse as a duty-payment-deferral tool beyond that.

- **Pitfalls / exam tips:**
  - If **no duty is payable** at the time of actual clearance (e.g., nil-rate final assessment), **no interest** is payable either — "no principal, no interest."
  - Interest runs on the **duty payable at the time of clearance**, not on the duty as originally assessed at into-bond stage.
  - **Rate-of-duty rule for improperly removed / overstayed goods (Kesoram Rayon principle):** where goods are not cleared within the permitted (or extended) warehousing period, the **date of expiry of that period** — not the date of actual clearance — is the relevant date for determining the rate of duty and rate of exchange (goods are treated as if removed on the day they ought to have been removed).
  - ⚠️ VERIFY — the OCR's numeric worked example (assessable value, exchange rates 14-May/21-Sep/14-Oct, BCD 15%/10%/20%) is too garbled/internally inconsistent to reproduce reliably; the *rule* it illustrates (Kesoram Rayon — use the date of expiry of the permitted warehousing period, not actual removal date, when goods overstay) is correctly stated above and independently verified.

- **Illustrative example (constructed, not from OCR):** Goods filed into bond on 1-Jan; into-bond order permits warehousing till 30-Apr. Importer actually clears the goods on 20-Jun (after expiry, without extension). Rate of duty/exchange rate applicable = rate in force on **30-Apr** (the date the goods should have been cleared), and interest u/s 61(2) runs from the 91st day after 1-Jan up to the date duty is actually paid.

---

### Manufacture and Other Operations in Warehouse [Section 65]

- **Key rule(s):**
  - A licensee may carry out manufacturing or other operations on warehoused (imported) goods with permission, without payment of duty on the imported material used, subject to conditions (bond, records, etc.).
  - **Duty on waste/refuse generated during such manufacture:** import duty is payable **only on the quantity of imported input contained in the waste/refuse relatable to the finished goods cleared for home consumption**; if the waste is destroyed with sanction of the proper officer, no duty is payable on it.

- **Concept:** This lets a bonded manufacturing warehouse (e.g., an EOU-type unit) import raw material duty-free, use it in manufacture, and pay duty only on the imported content actually embedded in goods that leave the warehouse for home consumption.

- **Pitfalls / exam tips:**
  - Apportion the imported input into waste using the **ratio of quantity cleared for home consumption to total output**, then find the imported-material content of that waste using the **input ratio** (imported input ÷ total input used).
  - ⚠️ VERIFY — the OCR's numeric waste-apportionment example (rubber/tyres, 1,500 kg imported rubber, 210 kg other inputs, 16.5 kg/tyre) contains contradictory figures (e.g., "100 tyres × 16.5 kg" yielding inconsistent waste and multiple restated "39.6 kg / 45 kg" answer lines) and could not be reliably reconstructed from the source; only the apportionment **method** above is reproduced with confidence.

---

### Refund of Customs Duty [Section 27] & Unjust Enrichment

- **Key rule(s)/thresholds:**
  - Application for refund of duty/interest paid must be made within **one year** from the "relevant date" (e.g., date of payment of duty, in most cases), in the prescribed form, along with documentary evidence that the incidence of duty has not been passed on to any other person.
  - **Principle of unjust enrichment:** customs duty is an indirect tax whose burden is presumed passed on to the buyer/consumer; therefore refund is **not paid to the applicant** but credited to the **Consumer Welfare Fund**, *unless* the importer proves the burden was not passed on.
  - **Refund paid directly to the applicant (exceptions to unjust enrichment)** typically include: import by an individual for personal use; refund of export duty; drawback; duty paid under protest; duty borne by the importer without passing it on (supported by CA certificate/documents); and refund arising from a **finalisation of provisional assessment** where the excess is shown not passed on.

- **Concept:** Refund is a statutory, time-bound remedy for excess duty paid; unjust enrichment stops a windfall to an importer who has already recovered the duty from his customer.

- **Pitfalls / exam tips:**
  - Refund **cannot be claimed as a substitute for, or a back-door route around, an appeal** against an assessment order — if the assessment itself is disputed, the remedy is appeal, not a refund application.
  - Mere fact that the **price of the product remained unchanged** before and after the duty was levied does **not**, by itself, prove that the duty burden was not passed on (burden of proof is on the importer to affirmatively establish non-passing).
  - If refund arises from an **order of an appellate authority, Tribunal, or court** in the importer's favour, the one-year limitation is reckoned from the date of that order/judgment.

- **Definitions:**

| Term | Meaning |
|---|---|
| Relevant date | Date used to compute the 1-year limitation for a refund claim (generally date of payment; varies for provisional assessment, appellate orders, exports etc.) |
| Consumer Welfare Fund | Fund to which refunds hit by unjust enrichment are credited, instead of being paid to the importer |

---

### Interest on Delayed Refund [Section 27A]

- **Key formula/rule:**
  - If duty ordered to be refunded under Section 27(2) is **not refunded within three months** from the date of receipt of the (complete) refund application, interest is payable on the refund amount **from the date immediately after expiry of three months till the date of refund**.
  - Interest rate is fixed by the Central Government by notification, within the statutory band of **not below 5% and not exceeding 30% p.a.**; the rate currently notified is **6% p.a.** (Notification No. 75/2003-Cus (NT) dated 12.09.2003).

$$
\text{Interest} = \text{Refund amount} \times 6\% \times \dfrac{\text{Days beyond 3 months from application}}{365}
$$

- **Concept:** Compensates the importer for delay by the department in actually paying out a sanctioned refund.

- **Pitfalls / exam tips:**
  - The three-month clock starts from **receipt of a complete/proper application**, not from the date duty was originally paid.
  - Do not confuse this 6% delayed-refund interest rate with the (different, higher) 15% p.a. warehousing interest rate under Section 61 — students often mix the two in exams.

---

### Classification of Imported & Export Goods — Customs Tariff Act

- **Key rule(s):**
  - Basic Customs Duty (BCD) is levied per the **First Schedule to the Customs Tariff Act, 1975**, which is based on the international **Harmonized System of Nomenclature (HSN)**.
  - First Schedule structure: **Section → Chapter → Heading → Sub-heading → Tariff item**, with Section Notes and Chapter Notes guiding interpretation of entries within their scope.
  - The First Schedule also carries **General Explanatory Notes** and the **General Rules for the Interpretation (GRI) of Import Tariff — Rules 1 to 6**.
  - Section and Chapter titles are provided **only for ease of reference** and have **no legal bearing** on classification.
  - The **Second Schedule** (export tariff) is outside the CA Final syllabus.

- **Concept:** Correct classification (which heading/sub-heading a good falls under) drives the rate of duty applicable — it is the foundational step before any duty computation.

- **Pitfalls / exam tips:** Always classify first by the **terms of the headings** and relevant Section/Chapter Notes (GRI 1); resort to GRI 2–6 only if that doesn't resolve classification.

---

### General Rules for Interpretation (GRI) of the Tariff — Rules 1 to 6

- **Key rule(s):**
  - **Rule 1:** Classification is determined according to the terms of the headings and any relative Section/Chapter Notes; Section/Chapter titles are for reference only.
  - **Rule 2(a):** Any reference to an article covers that article **incomplete or unfinished**, provided it has the **essential character** of the complete article; it also covers the article **unassembled or disassembled** — classified as if assembled.
    - *Example:* A motorcycle without a headlight is still classified as a motorcycle.
  - **Rule 2(b):** Any reference to a material or substance includes mixtures/combinations of that material with other materials; goods consisting of more than one material are classified per **Rule 3**.
  - **Rule 3** (when goods appear classifiable under two or more headings):
    - **3(a):** The heading giving the **most specific description** is preferred over one giving a more general description.
    - **3(b):** Mixtures, composite goods, and goods put up in sets for retail sale are classified per the material/component that gives them their **essential character**.
    - **3(c):** If neither 3(a) nor 3(b) resolves it, classify under the heading which occurs **last in numerical order** among the headings equally meriting consideration.
  - **Rule 4:** Goods not classifiable under Rules 1–3 are classified under the heading appropriate to the goods to which they are **most akin (most similar)**.
  - **Rule 5 — Packing:**
    - **5(a):** Cases/containers specially shaped or fitted for a specific article, suitable for long-term/repetitive use, and presented with the article, are classified with that article.
    - **5(b):** Packing materials/containers presented with goods are classified with those goods if of a kind normally used for packing such goods, **unless** they are clearly suitable for repetitive use (e.g., a reusable steel drum is classified separately; a disposable toothpaste tube is classified with the toothpaste).
  - **Rule 6:** Classification within sub-headings of a heading is determined per the terms of the sub-headings and related sub-heading notes, sub-headings being **comparable only at the same level**; Rules 1–5 apply mutatis mutandis.

- **Concept:** GRI is the mandatory, sequential fallback ladder (1 → 2 → 3 → 4 → 5 → 6) used whenever a good doesn't cleanly fit one heading.

- **Pitfalls / exam tips:**
  - Apply the rules **in sequence** — do not jump to Rule 3 if Rule 1/2 already settles classification.
  - Rule 3(c) ("last in numerical order") is a **tie-breaker of last resort**, used only when essential character (3(b)) cannot be determined either.
  - Rule 5(b)'s repetitive-use test is a favourite exam trap: a gas cylinder or a decorative tin box meant for reuse is **not** classified with the goods it contained.

---

### Project Imports [Heading 9801]

- **Key rule(s)/thresholds:**
  - Where a project involves many goods (machinery, instruments, apparatus, appliances, raw materials, components, etc. for **initial setting up of a unit, or substantial expansion of an existing unit**) each normally attracting different duty rates, the **Project Imports Regulations, 1986** allow all such goods to be assessed under a **single consolidated heading — 9801** of the Customs Tariff — at one applicable rate, instead of classifying each item separately.
  - **Spare parts, raw materials and consumables** for the initial setup/maintenance of the registered project are also eligible under Heading 9801, up to **10% of the value of the goods** (machinery/equipment) already imported/cleared under the project registration.
  - Benefit requires prior **registration of the contract** with the customs authorities before import.

- **Concept:** Simplifies customs clearance for large industrial/infrastructure projects by giving one uniform assessable rate instead of item-by-item classification.

- **Pitfalls / exam tips:** The 10% cap on spares is measured against the **value of the project goods**, not against the total project cost or contract value.

### References
1. Customs Act, 1962 — Sections 57–61 (warehousing, bond, warehousing period & interest), Section 65 (manufacture in warehouse), Section 72 (improper removal), Section 27/27A (refund & interest on delayed refund) — bare act text, indiankanoon.org / lawgist.in.
2. TaxGuru — "Amendment of Section 61 ... interest free warehousing period" and "Clarification on commencement of interest free period of 90 days u/s 61" (confirms 90-day interest-free period from date of deposit, 15% notified rate) — taxguru.in.
3. TaxGuru / 24law.in / lawx.in — Section 27A interest on delayed refunds, 3-month trigger, statutory band 5%–30% p.a., currently notified 6% p.a. under Notification No. 75/2003-Cus (NT) dated 12.09.2003.
4. Customs Tariff Act, 1975 — First Schedule, General Rules for Interpretation (GRI 1–6); CBIC Chapter 98 (Project Imports) and Project Imports Regulations, 1986 (Heading 9801, spares up to 10% of value) — dgciskol.gov.in / customsmangalore.gov.in / seair.co.in.

## 16. Foreign Trade Policy & Duty Drawback
> **Where it fits:** FTP (administered by DGFT under the FT(D&R) Act, 1992) tells an exporter/importer *what* incentive scheme to use (Advance Authorisation, DFIA, EPCG, EOU, Status Holder benefits); Duty Drawback (Sections 74 & 75, Customs Act, 1962 + Drawback Rules, 2017) is the *residual, cash-back* route when duty-free import schemes are not availed — this chapter is normally the shortest but a guaranteed 4-5 mark scoring area in CA Final IDT.

### 1. Legal Framework of FTP & DGFT
- **Key rule(s):**
  - Central Government formulates and announces Foreign Trade Policy (FTP) under powers of the **Foreign Trade (Development & Regulation) Act, 1992** [FT(D&R) Act].
  - **DGFT** (Directorate General of Foreign Trade), under the Ministry of Commerce & Industry, administers the FTP and issues the **Handbook of Procedures (HBP)**.
  - **Importer-Exporter Code (IEC)**: mandatory PAN-based 10-digit number for any person importing/exporting; one IEC per PAN; no periodic renewal required (only annual online updation between April-June each year).
- **Concept:** FTP is a statement of Government policy (currently **FTP 2023**, in force w.e.f. 1 April 2023, a policy with no fixed end-date, updated by periodic notifications) laying down schemes/procedures for cross-border trade.
- **Pitfalls / exam tips:**
  - Do not confuse FTP (policy document) with the FT(D&R) Act (the enabling statute) — a common MCQ trap.
  - IEC is not required for specified categories (e.g., import/export for personal use not connected with trade, manufacture or agriculture; Ministries/Departments of the Government).
- **Definitions:**

| Term | Meaning |
|---|---|
| DGFT | Directorate General of Foreign Trade — apex body implementing FTP |
| IEC | Importer-Exporter Code — identity number for importers/exporters |
| HBP | Handbook of Procedures — operational/procedural companion to FTP |

### 2. Classification of Import/Export Items
- **Key rule(s) (import/export policy per ITC(HS) classification):**
  - **Free** — no authorisation needed (default category for most goods).
  - **Restricted** — importable/exportable only against an authorisation/licence from DGFT.
  - **Prohibited** — import/export totally banned (e.g., specified wildlife products).
  - **State Trading Enterprises (STE) / Canalised items** — import/export only through a designated STE (e.g., certain petroleum products, urea) unless specifically permitted otherwise.
- **Concept:** Every item under the ITC(HS) is placed in one of these four categories; the category decides whether an ordinary IEC holder can trade in it directly.
- **Pitfalls / exam tips:**
  - Even a "restricted" second-hand good (e.g., second-hand laptop/AC) needs a specific import authorisation — this is a favourite objective-type question.
  - "Canalised" ≠ "Prohibited": canalised items *can* be traded, but only via the notified STE.

### 3. Denied Entry List (DEL)
- **Key rule(s):**
  - The concerned Regional Authority (RA) of DGFT can place a defaulting firm on the **Denied Entry List (DEL)**.
  - Consequence: no import/export authorisation, licence, certificate, scrip, or fiscal/financial benefit will be granted or renewed to a firm on the DEL.
  - Removal from DEL: on fulfilment of export obligation / payment of penalty / compliance with the demand notice issued by the RA.
- **Concept:** DEL is DGFT's blacklist mechanism to enforce compliance by exporters/importers who default on licence conditions (e.g., non-fulfilment of export obligation).
- **Pitfalls / exam tips:** ⚠️ VERIFY — the source OCR rendered this as "Penalized Entry List"; the correct FTP terminology is **Denied Entry List (DEL)** (used here based on domain knowledge, as the OCR term does not match any known FTP provision).

### 4. Status Holders (Star Export Houses)
- **Key rule(s) — export performance thresholds for status recognition (FOB/FOR value, current + previous 3 licensing years, in US$ million):**

| Status category | Export performance (US$ million) |
|---|---|
| One Star Export House | 3 |
| Two Star Export House | 15 |
| Three Star Export House | 50 |
| Four Star Export House | 200 |
| Five Star Export House | 800 |

  - Export performance is necessary in at least **2 out of the last 4 (current + previous 3) financial years** to qualify for a given status.
  - Status certificate is valid for **5 years** from date of issue (or till FTP validity, whichever is earlier).
- **Concept:** Status Holders are recognised exporters entitled to privileges such as self-certification of Certificate of Origin, exemption from furnishing bank guarantees, and various fast-track/priority customs clearances.
- **Pitfalls / exam tips:**
  - The book's original table figures were garbled by OCR (showed 15/50/200/800 against the wrong star categories); the verified DGFT/FTP-2023 figures are tabulated above — memorise the 3-15-50-200-800 progression.
  - Double-weightage is given to MSMEs and to specified sectors (e.g., fruits & vegetables exporters) in computing export performance.

### 5. Advance Authorisation (AA) Scheme
- **Key formula(s)/rule(s):**

$$ \text{Value Addition (\%)} = \dfrac{A - B}{B} \times 100 $$

  where **A** = FOB value of export realised/to be realised, **B** = CIF value of duty-free imported inputs (+ value of other inputs where duty free import is not availed).
  - **Minimum Value Addition** required: generally **15%** (special cases: e.g. tea — **50%**; some products have specified minimum VA or nil VA per Appendix).
  - **Export Obligation (EO) period**: exports to be completed within **18 months** from the date of issue of the Authorisation (extensions permissible per HBP).
  - Import validity of the Authorisation: **12 months** from date of issue (for effecting imports).
  - Authorisation is issued on **pre-import** basis, subject to **Actual User condition**, and is **non-transferable** even after export obligation is fulfilled.
- **Concept:** Allows duty-free import of inputs physically incorporated in the export product (making normal allowance for wastage), plus fuel/oil/catalyst consumed in producing the export product, before exports are made.
- **Pitfalls / exam tips:**
  - AA is **pre-export** (import first, then export); DFIA (topic 6) is **post-export** — a classic distinguishing question.
  - Duties exempted typically include BCD, IGST, Compensation Cess, Anti-dumping/Safeguard/CVD as per the specific exemption notification in force — students should tie this to the applicable customs notification, not assume blanket exemption of every duty.
- **Definitions:**

| Term | Meaning |
|---|---|
| SION | Standard Input Output Norms — notified ratio of input to output for a given export product |
| Actual User condition | Imported inputs can only be used by the license-holder itself, not transferred |

### 6. Duty Free Import Authorisation (DFIA)
- **Key rule(s):**
  - Minimum Value Addition required: **20%**.
  - DFIA is issued on **post-export** basis (export first, obtain authorisation after realisation of export proceeds), unlike Advance Authorisation.
  - DFIA (and/or the inputs imported against it) is **transferable** once export obligation is fulfilled and export proceeds are realised.
  - Only **Basic Customs Duty (BCD)** is exempted on imports under (transferable) DFIA — IGST/Cess is not exempted.
  - DFIA is issued only for products for which **SION** (Standard Input Output Norms) have been notified.
- **Concept:** A duty-exemption scheme similar to AA but operating post-export and freely transferable in the market — widely used because the transferable scrip itself has commercial value.
- **Pitfalls / exam tips:**
  - Do not confuse the 15% VA of AA with the **20% VA of DFIA**.
  - Because only BCD is exempted, DFIA is less attractive than AA where IGST-exemption matters, but its transferability is its unique commercial advantage.

### 7. Export Promotion Capital Goods (EPCG) Scheme
- **Key formula(s)/rule(s):**

$$ \text{Export Obligation (EO)} = 6 \times \text{Duty saved on capital goods imported} $$

  - EO to be fulfilled within **6 years** from the date of issue of the EPCG Authorisation.
  - **Block-wise EO**: minimum **50% of EO** to be fulfilled in **Block-1 (years 1-4)**; balance in **Block-2 (years 5-6)**.
  - Scheme permits import of capital goods (for pre-production, production and post-production) at **zero/concessional Customs duty**.
  - On failure to fulfil EO: exporter is liable to pay the duty saved (proportionate) **along with applicable interest** to Customs.
- **Concept:** Enables exporters to import capital goods for upgrading technology/capacity at zero duty, in exchange for a multiplied export commitment of the duty benefit availed.
- **Pitfalls / exam tips:**
  - EO is 6 **times** the duty saved, not 6 times the CIF value of capital goods — a frequent numerical-error trap.
  - EPCG authorisation holder must also maintain average export performance (of preceding 3 years) in addition to the incremental EO, in specified cases.

### 8. Export Oriented Units (EOU) / EHTP / STP / BTP
- **Key rule(s):**
  - Units under these schemes can import/procure capital goods and inputs without payment of duty, and are permitted duty-free domestic procurement as well, subject to fulfilling **positive Net Foreign Exchange (NFE)** earnings, monitored cumulatively over a block period (typically 5 years) by the jurisdictional Development Commissioner.
  - Limited sale of finished goods in the Domestic Tariff Area (DTA) is permitted on payment of applicable duties, subject to NFE fulfilment (percentage caps are notified separately and vary by sector). ⚠️ VERIFY — exact current DTA-sale percentage cap not independently verified in this session; confirm against the latest FTP/HBP notification before quoting a specific number in the exam.
- **Concept:** EOU/EHTP (Electronics Hardware TP)/STP (Software TP)/BTP (Bio-Technology Park) units are 100% export-oriented units set up under a single scheme umbrella to earn foreign exchange, enjoying duty exemptions in exchange for export/NFE commitments.
- **Pitfalls / exam tips:** EOU benefits are administered by the Development Commissioner (not DGFT directly) and by jurisdictional GST/Customs authorities for duty exemption compliance.

### 9. Deemed Exports
- **Key rule(s) — deemed export benefits (any one, as applicable):**
  - Duty Drawback on inputs used;
  - Refund of applicable IGST/CGST+SGST paid on supply (as deemed export refund, since actual physical export out of India does not occur);
  - Exemption from payment of duty / Advance Authorisation-EPCG export obligation discharge, where supplies are made against such authorisations.
- **Concept:** "Deemed Exports" refers to specified categories of supply of goods (manufactured in India) that do not leave the country but are treated as exports for benefit purposes — e.g. supplies to EOUs/SEZ developers, supplies against EPCG/AA to the domestic manufacturer, supplies to specified projects funded by multilateral agencies.
- **Pitfalls / exam tips:** Under GST, "deemed export" is separately defined in Section 147 of the CGST Act, 2017 read with the relevant deemed-export notification — link this FTP concept to its GST-law counterpart when answering integrated questions.

### 10. Duty Drawback – Legal Basis (Sections 74 & 75, Customs Act, 1962)
- **Key rule(s):**
  - **Section 74** — Drawback on **re-export of imported goods** (identifiable goods re-exported "as such" or after use): up to **98%** of the import duty paid is repayable as drawback if goods are re-exported without being taken into use; if goods were used, drawback is allowed at reducing percentages based on the period of use, as per a notified schedule.
  - **Section 75** — Drawback on **imported/excisable materials used in manufacture of goods which are exported**, operationalised through the **Customs and Central Excise Duties Drawback Rules, 2017**.
  - Post-GST, the drawback scheme largely covers only the **Customs duty component** (and, for specified items, Central Excise duty component, e.g. petroleum products), since GST paid on inputs is separately available as Input Tax Credit/refund — GST itself is *not* refunded through drawback.
- **Concept:** Drawback is the government's mechanism to neutralise (refund) customs/central excise duty suffered on inputs, so Indian exports remain duty-free/competitive in international markets.
- **Pitfalls / exam tips:** Section 74 (re-export of imported goods) is often confused with Section 75 (manufacture-and-export) — Section 74 needs no "manufacturing", only re-export of the same imported goods.

### 11. All Industry Rate (AIR) vs Brand Rate of Drawback
- **Key formula(s)/rule(s):**
  - **All Industry Rate (AIR)** — a general, average rate/amount (as % of FOB value, subject to a value cap per unit, or a specific rate per unit quantity) notified by CBIC under **Rule 3** of the Drawback Rules, 2017 for standard export product categories (via the Drawback Schedule).
  - **Cap on drawback amount (Rule 9):**

$$ \text{Drawback allowed} \le \dfrac{1}{3} \times \text{Market price of the export product} $$

    — no drawback is admissible if the amount so computed would exceed one-third of the market price of the goods.
  - **Minimum drawback threshold:** drawback is not paid where the amount payable is **less than ₹50** per shipment/claim.
  - **Brand Rate** — where AIR is not fixed for a product, or the AIR fixed is less than **80%** of the duties actually paid on inputs/materials used, the exporter can apply for a **special (brand) rate**:
    - **Rule 6** — application where no AIR is notified.
    - **Rule 7** — application where AIR notified is less than 80% of duties actually paid.
    - Application to be filed within **3 months from the "let export order" (LEO) date** (relevant date); extendable by **3 months** by the Assistant/Deputy Commissioner, and a **further 6 months** by the Principal Commissioner/Commissioner of Customs (on payment of specified fees for delayed filing, as prescribed).
- **Concept:** AIR is a quick, one-size-fits-all rate for common export products; Brand Rate is a case-specific, actual-duty-incidence-based rate fixed on the exporter's application when AIR under/over-compensates.
- **Pitfalls / exam tips:**
  - Remember the **80% threshold** — it is the trigger for shifting from AIR to Brand Rate (Rule 7), a very common numerical MCQ.
  - The 3-month (+3+6 months extension) timeline for brand rate application is examiner-favourite; sequence it correctly (AC/DC first, Pr. Commissioner/Commissioner thereafter).

### 12. Drawback Timelines, Interest & Recovery (Section 75A)
- **Key formula(s)/rule(s):**
  - Drawback claim is deemed to be filed on the date the exporter files the (EDI) **shipping bill** with the requisite declaration.
  - **Section 75A(1):** If drawback is **not paid within 1 month** from the date of filing the claim, interest is payable to the exporter at the rate applicable under **Section 27A** — currently **6% p.a.** — for the period of delay beyond that one month.
  - **Section 75A(2):** Where drawback has been paid **erroneously/in excess**, the exporter must repay the excess along with interest at the rate applicable under **Section 28AA** — currently **15% p.a.** — from the date of payment till the date of recovery.
- **Concept:** Section 75A protects the exporter against unreasonable delay (via interest compensation) and simultaneously protects revenue where drawback has been over-paid.
- **Pitfalls / exam tips:**
  - Two different rates apply to two different directions of interest — 6% (delay in paying exporter) vs 15% (recovery of excess from exporter) — do not interchange them in numerical answers.
  - ⚠️ VERIFY — these interest rates are fixed by periodic government notification under Sections 27A/28AA respectively; reconfirm the currently notified percentage against the latest CBIC notification applicable for your attempt, as rates are subject to revision.

### 13. Trade Facilitation Measures under FTP
- **Key rule(s) (illustrative, non-exhaustive):**
  - Free/priority passage for export consignments — export-related stock is not to be seized by enforcement agencies without due process.
  - Single-window facilitation for export of perishable agricultural produce.
  - **Niryat Bandhu Scheme** — mentoring scheme for new/potential exporters, along with various online facilitation tools.
  - **24x7 Helpdesk** facility to assist exporters with FTP-related queries.
- **Concept:** A cluster of administrative measures under FTP 2023 aimed at reducing transaction costs and time for exporters, particularly MSMEs and first-time exporters.
- **Pitfalls / exam tips:** ⚠️ VERIFY — the source OCR rendered the mentoring scheme name as "Nipp't Bardhu Scheme"; this has been reconstructed as **Niryat Bandhu Scheme** based on domain knowledge of FTP trade-facilitation initiatives — confirm the exact current scheme name/coverage against the latest FTP Handbook of Procedures before quoting it as a section-reference answer.

### References
1. Directorate General of Foreign Trade (DGFT) — Foreign Trade Policy 2023 and Handbook of Procedures 2023, issued under the Foreign Trade (Development & Regulation) Act, 1992.
2. Customs Act, 1962 — Sections 74, 75, 75A, 27A, 28AA (drawback and interest provisions).
3. Customs and Central Excise Duties Drawback Rules, 2017 (Rules 3, 6, 7, 8, 9) — CBIC.
4. TaxTMI / TaxGuru summaries of Drawback Rules, 2017 and Section 75A interest provisions (used to cross-verify the 3-month/6-month brand-rate timelines and 6%/15% interest rates).
5. DGFT / trade-advisory summaries (Razorpay, TaxTMI "Status Holder Scheme under FTP 2023") — used to verify Star Export House export-performance thresholds (US$ 3/15/50/200/800 million).
6. DGFT FAQs on Transferable DFIA; ClearTax/Credlix summaries of Advance Authorisation and EPCG scheme conditions — used to verify value-addition percentages (15% AA / 20% DFIA), export obligation periods (18 months AA; 6 years/6× duty saved EPCG).

## ⚠️ Formulas to double-check


**00. Basics of GST (Constitutional Background & Introduction)**
- GST Council recommendations are **not binding** in the sense of an ordinary statute — per Supreme Court (*Union of India v. Mohit Minerals*, 2022), they have persuasive value; Parliament/State Legislatures retain simultaneous legislative power under Art. 246A. ⚠️ VERIFY — this case-law point is well-established doctrine but was not present in the OCR source; include as a well-known SC ruling, cross-check against your update material if a newer ruling has refined it further for the 2026 attempt.

**01. Supply under GST, Charge/Levy, Composition Levy, Reverse Charge & Exemptions**
- "Turnover in State/UT" for the composition rate base **includes exempt supplies** and interest/discount on loans/deposits/advances — except for a trader, where the base is restricted to **taxable supplies of goods**. ⚠️ VERIFY — the OCR's phrasing on the trader carve-out was garbled; the settled position (Sec. 10(1) proviso, as clarified by CBIC) is that a trader pays 1% only on the value of **taxable supplies of goods**, while manufacturers/restaurant suppliers pay on total turnover in State including exempt supplies.

**03. Value of Supply**
- ⚠️ VERIFY — the OCR table on secondary discounts was heavily garbled; the summary above reflects the settled CBIC circular position but the specific illustration in the source could not be reliably reconstructed.
- ⚠️ VERIFY — the OCR's Del Credere Agent flowchart (numbered points (i)–(vi)) was almost entirely garbled; the summary above reflects the generally accepted treatment but the source's exact enumeration of "independent vs. composite" supplies could not be reliably reconstructed from this OCR pass.
- ⚠️ VERIFY — the OCR's worked forex example ("ABC Ltd sold 2,000 USD/EUR at 86, RBI reference rate 84 → VOS = (86−84) × 2,000 = 4,000") appears numerically consistent with Method-1 of Rule 32(2)(a) but the source's exact currency labels were garbled; treat the mechanics (not the specific currency names) as reliable.

**04. Place of Supply**
- ⚠️ VERIFY (amendment awareness) — the earlier **proviso** to Section 12(8), which fixed PoS at the **destination of goods** when the destination was **outside India**, has been **omitted w.e.f. 1 October 2023** (Finance Act, 2023). Post-amendment, PoS for transportation of goods follows only the two limbs above (recipient's location if registered; place where goods are handed over for transportation, otherwise) — destination is no longer relevant even for exports.
- ⚠️ VERIFY (structural change) — Section 13(9), which earlier fixed PoS for goods-transportation services (other than by mail/courier) at the **destination of the goods**, has been **omitted w.e.f. 1 October 2023** (Finance Act, 2023, Sec. 162). Transportation of goods (import/export leg) is therefore **no longer a "specific case"** and now falls back to the **general rule of Section 13(2)** — PoS = location of the recipient; if not available, location of the supplier.

**05. Import and Export under GST**
- ⚠️ VERIFY (amendment nuance, know for MCQs) — w.e.f. **1 October 2023** (Finance Act 2021 provision operationalised via Notification 27/2023-CT), supplies to a SEZ unit/developer are zero-rated **only if made for "authorised operations"** — the supply must be endorsed as such by the Specified Officer of the SEZ; supplies to SEZ not for authorised operations are NOT zero-rated.
- ⚠️ VERIFY — Rule 89(4A) (deemed export supplies received) and Rule 89(4B) (supplies received at concessional/notified rate, e.g. merchant-exporter inward supply) along with **Rule 96(10)** (restriction on IGST-refund route for those availing specified duty-exemption/concessional benefits on inputs) were **omitted w.e.f. 8 October 2024** by **Notification No. 20/2024-Central Tax** — students preparing for 2026 attempts should treat these restrictions as removed (this is a high-yield recent amendment).

**06. Electronic Commerce Transactions and TCS**
- ⚠️ VERIFY — item (2)/(3) in the OCR ("housekeeping services i.e. plumbing… local delivery services") suggested a possible 5th/6th notified category (e.g., "local delivery services"); confirm against the current consolidated notification (as amended) for the applicable assessment year before quoting it as a notified category in the exam.
- ⚠️ VERIFY — the OCR referenced a "matching mechanism" between ECO's GSTR-8 and supplier's GSTR-1/GSTR-3B with discrepancies added back to the supplier's output liability if unrectified; the underlying statutory matching provisions (old Section 52(9)/(10)/(11)) have largely been omitted from the Act — confirm current-syllabus status before relying on "matching/discrepancy" mechanics in an answer.
- **Annual statement:** ECOs are also required to furnish an annual statement (FORM GSTR-9B) for the financial year by the prescribed due date [Section 52(5)] — ⚠️ VERIFY — confirm from the latest CBIC notifications/press releases whether filing of GSTR-9B has been kept optional/deferred for the year(s) tested in the current exam attempt.

**07. Registration**
- ### Simplified / Fast-Track Registration Scheme — Rule 14A ⚠️ VERIFY — recently inserted provision, cross-check the exact monetary figure and effective date against the CGST Rules in force for your attempt
- *(⚠️ VERIFY — the source page contained an unreadable/garbled listing purportedly running from GST REG-01 through GST REG-504; there is no such range of forms under the CGST Rules. The table above lists only the genuine, currently notified GST REG-series forms relevant to this chapter — cross-check the complete official list in Rule 10 / Notified Forms if a question names a specific form number not shown here.)*

**08. Tax Invoice, Credit/Debit Notes, Accounts & Records and E-Way Bill**
- ⚠️ VERIFY — a 30-day reporting time-limit to the IRP (invoice must be reported to IRP within 30 days of invoice date) has been notified for taxpayers with aggregate turnover ≥ ₹10 crore; confirm current applicability/effective date against the latest CBIC advisory before the exam.

**09. Payment of Tax, TDS/TCS, Returns & Refunds under GST**
- ⚠️ VERIFY — the OCR source is heavily garbled at this point; confirm the 18%/24% distinction and the exact wording of the net-liability proviso against the bare Act/Rule 88B before the exam, as amendment-heavy areas like this are examiner favourites.
- ⚠️ VERIFY — exact current invoice-value thresholds for invoice-wise vs consolidated (B2C) reporting in GSTR-1 were illegible in the source OCR; confirm the current B2C inter-State invoice-value threshold (commonly cited as > ₹1 lakh/₹2.5 lakh depending on period) against the latest CBIC notification before relying on it in an answer.
- ⚠️ VERIFY — the OCR for the exact wording of "Adjusted Total Turnover" exclusions and the full illustrative list of unjust-enrichment exceptions was largely unreadable; cross-check the complete proviso list to Section 54(8) in the bare Act before an exam answer that hinges on a specific exception.

**10. Assessment, Audit, Inspection/Search/Seizure/Arrest, Demand & Recovery**
- ⚠️ VERIFY — the 60-day withdrawal window (extendable by a further 60 days with late fee) was introduced/confirmed by Finance Act 2023 amendments to Sec 62(2); older material may still show "30 days" — use 60+60 days for current syllabus but double-check the CBIC notification bringing this into force if the question specifically tests the applicable date.
- ⚠️ VERIFY — exact current compounding amounts and the full list of decriminalised clauses under Sec 132(1) should be cross-checked against the amended bare Act text for the exam year, as compounding fee slabs have been revised more than once.
- ⚠️ VERIFY — exact current penalty percentages under Sec 129(1)(a)/(b) (owner-came-forward vs owner-did-not-come-forward cases) and confiscation fine formula under Sec 130(2) should be cross-checked against the amended bare Act/Rule 138 as these percentages have been revised by past Finance Acts; the 14-day/7-day/15-day procedural timelines above are well-settled and safe to rely on.

**11. Appeals and Revision**
- **Pitfalls / exam tips:** ⚠️ VERIFY — exact count/list of State Bench locations and their phased "go-live" dates change frequently as GSTAT rolls out; do not memorise a specific city list for the exam, only the Principal Bench vs. State Bench jurisdictional split (place of supply → Principal/National Bench).
- **Pitfalls / exam tips:** ⚠️ VERIFY — precise rule number/FORM for withdrawal (post final acknowledgement) as printed in the OCR was illegible; the underlying principle (GSTAT permission required after final acknowledgement) is settled, confirm the rule/form number before quoting it in an answer.
- **Pitfalls / exam tips:** ⚠️ VERIFY — monetary limits are set by circular/instruction (currently Circular No. 207/1/2024-GST) and are revised periodically by CBIC; reconfirm the figures against the latest circular applicable to your attempt before quoting them in the exam.
- **Pitfalls / exam tips:** ⚠️ VERIFY — the OCR source for this list was garbled; the categories above reflect the settled statutory position, but cross-check the exact wording/duration of each disqualification ground against the bare Act before an answer that quotes it verbatim.

**12. Liability to Pay in Certain Cases, Advance Ruling & Miscellaneous Provisions**
- **Pitfalls / exam tips:** ⚠️ VERIFY — as of the current syllabus date, the *systems* to which data may be shared under Section 158A, and the detailed manner/format of obtaining consent, remained largely un-notified/not operationalised even though the section itself is in force from 1.10.2023 — students should treat this as an enabling provision awaiting full rollout rather than an actively used mechanism.
- **Pitfalls / exam tips:** ⚠️ VERIFY — this provision remains on the statute book but the compliance-rating scale/mechanism/rules have **not been notified/operationalised** on the GST portal as of the current syllabus; do not assume a "1–10" or any other specific scale is in force — the OCR source's reference to a 1–10 scale could not be corroborated from an authoritative source and should not be quoted as a settled fact in the exam.

**13. Customs - Basics, Levy, Types of Duty & Exemptions (incl. Baggage & Stores)**
- ⚠️ VERIFY — the 2-year sunset clock under Section 25(4A) runs from the date of the notification, ending on the *next* 31 March after 2 years elapse (not a flat 2-year anniversary date) — this "31 March" nuance is easy to state imprecisely; double-check against the current Bare Act/latest amendment before the exam.
- ⚠️ VERIFY — confirm the *current* Annexure-I quantity/value thresholds (cartridges, cigarettes, liquor, gold/silver) against the latest Baggage Rules text before the exam, since these limits are occasionally revised by CBIC notification.

**14. Customs - Valuation, Importation & Exportation Procedures**
- ⚠️ VERIFY — Late-filing charges under the second proviso to Section 46(3) are commonly cited as ₹5,000/day for the first 3 days of default and ₹10,000/day thereafter, waivable by the proper officer for sufficient cause; confirm current rate before quoting in an answer as it is prescribed by regulation and subject to periodic revision.

**15. Customs - Warehousing, Classification of Goods & Refund**
- ⚠️ VERIFY — the OCR's numeric worked example (assessable value, exchange rates 14-May/21-Sep/14-Oct, BCD 15%/10%/20%) is too garbled/internally inconsistent to reproduce reliably; the *rule* it illustrates (Kesoram Rayon — use the date of expiry of the permitted warehousing period, not actual removal date, when goods overstay) is correctly stated above and independently verified.
- ⚠️ VERIFY — the OCR's numeric waste-apportionment example (rubber/tyres, 1,500 kg imported rubber, 210 kg other inputs, 16.5 kg/tyre) contains contradictory figures (e.g., "100 tyres × 16.5 kg" yielding inconsistent waste and multiple restated "39.6 kg / 45 kg" answer lines) and could not be reliably reconstructed from the source; only the apportionment **method** above is reproduced with confidence.

**16. Foreign Trade Policy & Duty Drawback**
- **Pitfalls / exam tips:** ⚠️ VERIFY — the source OCR rendered this as "Penalized Entry List"; the correct FTP terminology is **Denied Entry List (DEL)** (used here based on domain knowledge, as the OCR term does not match any known FTP provision).
- Limited sale of finished goods in the Domestic Tariff Area (DTA) is permitted on payment of applicable duties, subject to NFE fulfilment (percentage caps are notified separately and vary by sector). ⚠️ VERIFY — exact current DTA-sale percentage cap not independently verified in this session; confirm against the latest FTP/HBP notification before quoting a specific number in the exam.
- ⚠️ VERIFY — these interest rates are fixed by periodic government notification under Sections 27A/28AA respectively; reconfirm the currently notified percentage against the latest CBIC notification applicable for your attempt, as rates are subject to revision.
- **Pitfalls / exam tips:** ⚠️ VERIFY — the source OCR rendered the mentoring scheme name as "Nipp't Bardhu Scheme"; this has been reconstructed as **Niryat Bandhu Scheme** based on domain knowledge of FTP trade-facilitation initiatives — confirm the exact current scheme name/coverage against the latest FTP Handbook of Procedures before quoting it as a section-reference answer.