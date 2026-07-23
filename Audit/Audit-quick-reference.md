# Audit — CA Final Quick Reference

> Built from OCR'd concept notes (CA Shubham Keswani) and web-verified against Standards on Auditing / ICAI Code of Ethics sources. Any ⚠️ VERIFY flag means double-check that item against the original notes.

## Contents

1. [00. Basics of Audit (SA 200, Audit Evidence & Procedures, SA 210/230)](#00-basics-of-audit-sa-200-audit-evidence-procedures-sa-210230)
2. [01. SQC-1 & Standards on Auditing 200-700 Series (SA 220 through SA 720)](#01-sqc-1-standards-on-auditing-200-700-series-sa-220-through-sa-720)
3. [02. Professional Ethics (Fundamental Principles, Threats, NOCLAR, Schedules, Council Guidelines, ESB Decisions)](#02-professional-ethics-fundamental-principles-threats-noclar-schedules-council-guidelines-esb-decisions)
4. [03. CARO 2020 & Company Audit](#03-caro-2020-company-audit)
5. [04. Audit Planning, Risk Assessment & Internal Control](#04-audit-planning-risk-assessment-internal-control)
6. [05. Group Audit (SA 600)](#05-group-audit-sa-600)
7. [06. Bank Audit & NBFC Audit](#06-bank-audit-nbfc-audit)
8. [07. PSU Audit](#07-psu-audit)
9. [08. Internal Audit & SA 610 (Using the Work of Internal Auditors)](#08-internal-audit-sa-610-using-the-work-of-internal-auditors)
10. [09. Due Diligence, Forensic Accounting & Investigation](#09-due-diligence-forensic-accounting-investigation)
11. [10. SA 800 Series (SA 800/805/810 - Special Purpose & Single FS Audits)](#10-sa-800-series-sa-800805810---special-purpose-single-fs-audits)
12. [11. Standards on Review Engagements (SRE 2400 & 2410)](#11-standards-on-review-engagements-sre-2400-2410)
13. [12. Standards on Assurance Engagements (SAE 3400/3402/3420)](#12-standards-on-assurance-engagements-sae-340034023420)
14. [13. Standards on Related Services (SRS 4400 & 4410)](#13-standards-on-related-services-srs-4400-4410)
15. [14. SDG & ESG Assurance (Sustainability Reporting)](#14-sdg-esg-assurance-sustainability-reporting)
16. [15. Digital Audit & Emerging Areas](#15-digital-audit-emerging-areas)

## 00. Basics of Audit (SA 200, Audit Evidence & Procedures, SA 210/230)

> **Where it fits:** This is the conceptual foundation chapter — before an audit even begins (SA 210), while it is being performed (SA 200's objectives, audit risk model, evidence-gathering procedures), and after it is documented (SA 230). Everything in the rest of the SA series (240 onward) builds on the vocabulary defined here.

### SA 200 — Overall Objectives of the Independent Auditor

- **Key formula(s)/rule(s):**

  Audit risk as a function of its components (the standard conceptual/exam model taught for SA 200; SA 200 itself describes this as a functional relationship rather than a literal arithmetic formula):

  $$ \text{Audit Risk (AR)} = \text{Risk of Material Misstatement (ROMM)} \times \text{Detection Risk (DR)} $$

  $$ \text{ROMM (at assertion level)} = \text{Inherent Risk (IR)} \times \text{Control Risk (CR)} $$

  - Overall objectives of the auditor (two limbs): (a) obtain **reasonable assurance** that the FS as a whole are free from material misstatement (whether due to fraud or error), enabling the auditor to express an opinion on whether the FS are prepared, in all material respects, in accordance with an applicable financial reporting framework (AFRF); and (b) report on the FS, and communicate, as required by the SAs, in accordance with the auditor's findings.
  - Reasonable assurance is a **high, but not absolute**, level of assurance — never a guarantee.
  - To obtain reasonable assurance, the auditor must obtain **Sufficient Appropriate Audit Evidence (SAAE)** to reduce audit risk to an acceptably low level.

- **Concept:** SA 200 is the "root" standard — it sets out the auditor's overall objectives and explains how the other SAs are to be understood and applied (compliance with each requirement of a relevant SA is mandatory unless the entire SA is not relevant, or a requirement is conditional and the condition does not exist).

- **Pitfalls / exam tips:**
  - Do not write "absolute assurance" — reasonable assurance is always **high but not absolute**; this distinction is a favourite one-mark/theory trap.
  - Audit risk model (AR = IR × CR × DR) is a teaching/conceptual aid used across ICAI study material to link IR, CR and DR — present it as the relationship SA 200 describes, not as a mechanically computed number in professional practice.
  - "Sufficiency" (quantity) vs "Appropriateness" (quality = relevance + reliability) are frequently tested as a distinguish-between pair.

- **Definitions:**

  | Term | Meaning |
  |---|---|
  | Reasonable Assurance | High, but not absolute, level of assurance |
  | Sufficiency | Measure of the **quantity** of audit evidence; affected by the assessed ROMM and by the quality of evidence |
  | Appropriateness | Measure of the **quality** of audit evidence — i.e., its relevance and reliability |
  | Relevance | Logical connection between the purpose of the audit procedure and the assertion being tested |
  | Reliability | Depends on the nature, source, and circumstances in which the evidence was obtained (see reliability hierarchy below) |
  | Misstatement | A difference between the amount, classification, presentation, or disclosure of a reported FS item and what is required under the AFRF; can arise from fraud or error; material if it could reasonably influence the economic decisions of users |
  | AFRF | Financial reporting framework adopted by management/TCWG that is acceptable given the nature of the entity and objective of the FS, or required by law/regulation — either a "fair presentation framework" or a "compliance framework" |
  | TCWG | Those Charged With Governance — person(s)/body responsible for overseeing the entity's strategic direction and accountability obligations (e.g., audit committee, board, CFO) |
  | Audit Risk | Risk that the auditor expresses an inappropriate opinion when the FS are materially misstated |
  | Detection Risk | Risk that the procedures performed by the auditor will not detect a misstatement that exists and could be material |
  | Inherent Risk | Susceptibility of an assertion to a misstatement that could be material, before consideration of related controls |
  | Control Risk | Risk that a material misstatement will not be prevented, or detected and corrected, on a timely basis by the entity's internal control |

### Reliability Hierarchy of Audit Evidence

- **Key formula(s)/rule(s):** (bullet-rule form, since this is a hierarchy, not a numeric formula)
  - Evidence from **independent external sources** is more reliable than evidence generated internally.
  - Internally generated evidence is more reliable when **related controls are effective**.
  - Evidence obtained **directly** by the auditor is more reliable than evidence obtained indirectly or by inference.
  - **Documentary** evidence (paper or electronic) is more reliable than evidence obtained orally.
  - Evidence from **original documents** is more reliable than photocopies, faxes, or digitised/electronic copies.

- **Concept:** Used to judge appropriateness (reliability limb) of evidence when planning NTE (Nature, Timing, Extent) of procedures.

- **Pitfalls / exam tips:** These are generalisations, not absolute rules — SA 500 notes exceptions exist (e.g., strong general/IT controls can make internally generated evidence highly reliable).

### Inherent Limitations of an Audit (ILA)

- **Key formula(s)/rule(s):**
  - The auditor is not, and cannot be, expected to reduce audit risk to zero, and therefore **cannot obtain absolute assurance**.
  - Reasons: (1) Nature of financial reporting — involves management judgment (e.g., accounting estimates); (2) Nature of audit procedures — practical/legal limits (management may not provide complete information; fraud may involve sophisticated concealment; the auditor is not an official investigator and has no legal powers of search); (3) Need for the audit to be conducted within a reasonable time and at reasonable cost — timeliness of reporting vs. balance between benefit and cost; (4) Certain matters have particularly significant inherent limitations to detection — fraud involving senior management/collusion; existence and completeness of related party relationships and transactions; occurrence of non-compliance with laws and regulations (NOCLAR); future events/conditions affecting going concern.
  - Subsequent discovery of a material misstatement, by itself, does **not** indicate an audit was not conducted per SAs.
  - ILA is never a justification for the auditor to be satisfied with less-than-persuasive evidence.

- **Concept:** Explains why audit evidence is generally **persuasive rather than conclusive**, and why "reasonable" (not absolute) assurance is the ceiling.

- **Pitfalls / exam tips:** A very common theory question ("Why can't the auditor guarantee the FS are correct?") — structure the answer around these four reasons, not just "auditor is human."

### Professional Skepticism (PS)

- **Concept:** An attitude comprising: (1) a **questioning mind**, (2) being **alert to conditions** that may indicate possible misstatement (due to error or fraud), and (3) a **critical assessment** of audit evidence.
- **Pitfalls / exam tips:** PS must be maintained throughout the audit, particularly when evaluating management's estimates/representations and when assessing fraud risk — auditors are frequently criticised (in ICAI disciplinary/ESB cases and NFRA orders) for lack of PS, not lack of technical procedure.

### Assertions (per SA 315)

- **Key formula(s)/rule(s):** Traditional three-category classification used in ICAI study material and widely tested:

  | Category | Assertions |
  |---|---|
  | Classes of Transactions & Events (for the period) | Occurrence, Completeness, Accuracy, Cut-off, Classification |
  | Account Balances (at period end) | Existence, Rights & Obligations, Completeness, Valuation (and allocation) |
  | Presentation & Disclosure | Combination of the above categories (occurrence & rights and obligations; completeness; classification & understandability; accuracy & valuation) — excludes cut-off and existence as standalone heads |

  ⚠️ VERIFY — the Revised SA 315 (effective for audits of periods beginning on/after 1 April 2022) technically **folds disclosure assertions into the "classes of transactions/events" and "account balances" categories** rather than treating "Presentation & Disclosure" as a fully separate third category; the source notes above follow the older/simplified three-column teaching structure still commonly used for revision — confirm the exact current-syllabus presentation against the latest ICAI SA 315 (Revised) material before quoting the third column verbatim in an answer.

- **Concept:** Assertions are management's representations, embodied in the FS, that the auditor uses to identify the different types of potential misstatements that could occur, which in turn drive the design of audit procedures.

- **Pitfalls / exam tips:** Mnemonic — Transactions: **OCACC** (Occurrence, Completeness, Accuracy, Cut-off, Classification); Balances: **ERCV** (Existence, Rights & Obligations, Completeness, Valuation).

### Audit Procedures for Obtaining Audit Evidence

- **Key formula(s)/rule(s):** Two broad categories of audit procedures:
  1. **Risk assessment procedures**
  2. **Further audit procedures**, comprising:
     - (i) Tests of Controls (TOCs)
     - (ii) Substantive procedures — Tests of Details (TODs) and Substantive Analytical Procedures

- **Concept / Definitions:**

  | Procedure | Meaning |
  |---|---|
  | Inspection | Examining records, documents, or physical examination of an asset |
  | Observation | Looking at a process/procedure being performed by others (e.g., observing inventory count by entity staff) — evidence only of the moment observed |
  | External Confirmation | Audit evidence obtained as a direct written response to the auditor from a third party, in paper or electronic form |
  | Recalculation | Checking the mathematical accuracy of documents or records |
  | Reperformance | Independent execution by the auditor of procedures/controls originally performed by the entity's internal control |
  | Analytical Procedures | Evaluations of financial information through study of plausible relationships among financial and non-financial data |
  | Inquiry | Seeking information from knowledgeable persons, financial or non-financial, inside or outside the entity — ranges from formal written to informal oral inquiries; used extensively throughout the audit alongside other procedures |

- **Pitfalls / exam tips:**
  - Inquiry alone is **never sufficient** — evaluating the response is an integral part of the inquiry process; responses may corroborate or may conflict with other evidence (e.g., indicating management override of controls).
  - For inquiries about management's **intent**, corroborating evidence may be limited — understanding management's past history/track record of carrying out stated intentions and its ability to pursue a specific course of action becomes relevant supporting evidence.
  - The auditor may obtain **written representations** from management/TCWG to confirm responses given orally to inquiries — links directly to SA 580.

### SA 210 — Agreeing the Terms of Audit Engagements

- **Key formula(s)/rule(s):** Objective — accept or continue an audit engagement only when the basis on which it is to be performed has been agreed, by:
  1. Establishing whether the **preconditions for an audit** are present, and
  2. Confirming a common understanding between the auditor and management/TCWG of the terms of the engagement.

  **Preconditions for an audit:**
  - The financial reporting framework to be applied is **acceptable** (assessed considering: nature of the entity; purpose of the FS; nature of the FS — complete set vs. single FS; and whether law/regulation prescribes the AFRF).
  - Management agrees that it acknowledges and understands its responsibility: (i) for preparation of the FS in accordance with the AFRF; (ii) for such internal control as management determines necessary to enable preparation of FS free from material misstatement (due to fraud or error); and (iii) to provide the auditor with — (a) access to all information relevant to preparation of the FS, (b) any additional information the auditor may request, and (c) unrestricted access to persons within the entity to obtain audit evidence.
  - If preconditions are **not present**, the auditor shall discuss the matter with management and **shall not accept** the proposed engagement (unless required by law/regulation to do so).
  - If management/TCWG impose a **scope limitation before acceptance** such that the auditor believes it would result in disclaiming an opinion, the auditor shall **not accept** such a limited engagement unless required by law or regulation.

  **Engagement letter — required contents:**
  - (a) Objective and scope of the audit of the FS
  - (b) Responsibilities of the auditor
  - (c) Responsibilities of management
  - (d) Identification of the AFRF for preparation of the FS
  - (e) Reference to the expected form and content of any reports to be issued, and a statement that there may be circumstances in which a report may differ from its expected form and content

  **Change in terms:** Auditor shall **not agree** to a change without reasonable justification; if requested to change to an engagement conveying a lower level of assurance, the auditor considers whether there is reasonable justification. If unable to agree and not permitted to continue on the original terms, the auditor shall: (a) withdraw where possible under applicable law/regulation, and (b) determine whether there is any obligation to report the circumstances to TCWG, owners, or regulators.

  **Recurring audits:** A new engagement letter/agreement each period is not mandatory, but should be considered/revised where there is: entity misunderstanding of objective/scope; recent change of senior management; significant change in ownership; significant change in nature/size of business; change in legal/regulatory requirements; change in the FRF adopted; or change in other reporting requirements.

- **Concept:** SA 210 is the "gatekeeping" standard — governs acceptance/continuance decisions at the start of (or before) an engagement.

- **Pitfalls / exam tips:** Distinguish "preconditions not present" (do not accept the engagement) from "scope limitation imposed before acceptance leading to disclaimer" (also do not accept) — both lead to non-acceptance but for different reasons; students often conflate the two triggers.

### SA 230 — Audit Documentation

- **Key formula(s)/rule(s):**
  - Audit documentation ("working papers") = record of audit procedures performed, relevant audit evidence obtained, and the conclusions the auditor reached.
  - Must be sufficient to enable an **experienced auditor**, having no previous connection with the audit, to understand:
    1. The **Nature, Timing and Extent (NTE)** of audit procedures performed to comply with SAs and applicable legal/regulatory requirements;
    2. The **results** of the audit procedures performed and the audit evidence obtained; and
    3. **Significant matters** arising during the audit, the conclusions reached, and significant professional judgments made in reaching those conclusions.
  - In documenting the NTE of procedures performed, the auditor records: the characteristics of the specific items/matters tested; who performed the audit work and the date such work was completed; and who reviewed the work performed, together with the date and extent of review.
  - ⚠️ VERIFY — the source excerpt (OCR) ends before covering the final-assembly and retention timelines. Per SA 230 as issued by ICAI, the auditor ordinarily should assemble the final audit file **not later than 60 days** after the date of the auditor's report, and should retain audit documentation for a period of **not less than 7 years** from the date of the auditor's report (or, if later, the date of the group auditor's report) unless a longer period is specified by law or regulation — these two figures could not be cross-checked against a live source this session; confirm against the current ICAI SA 230 text before quoting in an answer.

- **Concept:** Documentation is the auditor's principal evidence that the audit was actually planned and performed in accordance with SAs and applicable legal/regulatory requirements — "if it isn't documented, it wasn't done."

- **Pitfalls / exam tips:**
  - Documentation is not to be used to assess individual auditors' performance; nor should it be a substitute for the entity's own accounting records.
  - Timely preparation of documentation (as the work progresses, not after the fact) enhances audit quality and facilitates effective review.

### References
1. Standards on Auditing (SA) 200, *Overall Objectives of the Independent Auditor and the Conduct of an Audit in Accordance with Standards on Auditing* — ICAI (as applicable for the current CA Final syllabus).
2. Standard on Auditing (SA) 210, *Agreeing the Terms of Audit Engagements* — ICAI.
3. Standard on Auditing (SA) 230, *Audit Documentation* — ICAI.
4. Standard on Auditing (SA) 315 (Revised), *Identifying and Assessing the Risks of Material Misstatement* — ICAI (assertions framework).

Note: Web-search verification could not be completed in this session (search tool budget exhausted); the above content and figures reflect domain knowledge of the SAs as issued by ICAI. Items not independently re-confirmed this session are marked ⚠️ VERIFY.

## 01. SQC-1 & Standards on Auditing 200-700 Series (SA 220 through SA 720)

> **Where it fits:** This chapter is the "engine room" of the Audit paper — it lays down the quality-control architecture (SQC-1), the conduct-of-audit standards (fraud, laws, materiality, risk, evidence, sampling, estimates, related parties, going concern, representations, using others' work) and finally the reporting standards (SA 700 series) that every audit report, CARO note, and case-study answer in later chapters builds on.

### SQC-1 & SA 220 — Quality Control (Firm Level & Engagement Level)

- **Key formula(s)/rule(s):**
  - Six elements of a firm's System of Quality Control (SQC-1):
    a) Leadership responsibilities for quality within the firm
    b) Ethical requirements
    c) Acceptance & continuance of client relationships and engagements
    d) Human resources
    e) Engagement performance
    f) Monitoring
  - Firm's CEO/managing partners assume ultimate responsibility for the firm's system of quality control (SQC-1); the Engagement Partner (EP) takes responsibility for quality on each specific audit (SA 220).
  - Firm obtains **annual written confirmation** of compliance with independence policies from all personnel.
  - Engagement Quality Control Review (EQCR) is **mandatory for listed entity audits**; for other engagements the firm sets its own criteria.
  - Engagement file assembly: complete not later than **60 days** after the date of the auditor's report.
  - Retention of engagement documentation: ordinarily **not shorter than 7 years** from the date of the auditor's report (or the group auditor's report, if later).
  - ⚠️ VERIFY — Familiarity threat safeguard: rotation of the engagement partner on listed-entity audits after **7 years** of continuous association, followed by a "cooling-off" period before re-engagement (the exact cooling-off duration is not stated in the source notes; cross-check the current ICAI Code of Ethics provision before quoting a number in the exam).
- **Concept:** SQC-1 builds the quality-control system for the **whole firm** across all assurance engagements; SA 220 operationalises that same system for **one specific audit**. SA 220 is premised on the firm already being SQC-1 compliant.
- **Pitfalls / exam tips:**
  - Classic MCQ/theory trap: SQC-1 fixes responsibility on CEO/managing partner, SA 220 fixes it on the EP — don't swap these.
  - EQCR reviews *significant judgments*, not every working paper; review must complete **before** the report is dated.
  - Remember the reviewer-of-junior-staff checklist (PRL compliance, matters raised, consultations documented, NTE revision needed, conclusions supported, evidence sufficiency, objectives achieved) — frequently tested as a 6-8 mark question.

| Term | Meaning |
|---|---|
| SQC-1 | Standard on Quality Control governing firms performing audits, reviews & other assurance/related services engagements |
| EQCR | Engagement Quality Control Reviewer — partner/qualified person(s) who objectively evaluates significant judgments before report issuance |
| Engagement Partner (EP) | Partner responsible for the audit engagement and its performance, and for the auditor's report |

| SQC-1 | SA 220 |
|---|---|
| Applies to entire firm; CEO/managing partner responsible | Applies to one audit engagement; EP responsible |
| Covers audits, reviews of historical financial info & related services | Covers audit engagements only |
| Sets up the QC system (policies & procedures) | Implements QC procedures within that system for the specific engagement |

### Peer Review & Quality Review Board (QRB)

- **Key formula(s)/rule(s):**
  - Peer Review Board is constituted by the **Council of ICAI**; reviews whether Practice Units (PUs) have systems/procedures ensuring quality per Technical, Professional & Ethical (TPE) standards.
  - Outcome: **unqualified report → Peer Review Certificate issued**; **qualified report → certificate withheld**, PU informed with reasons and a follow-on review due date.
  - QRB is set up by the **Central Government**; members nominated by CG & ICAI.
- **Concept:** Peer Review is a quality-assurance mechanism run by the profession (ICAI) itself; QRB is a government-backed body reviewing audit quality (including risk-based selection of statutory auditors) and recommending improvements to Council.
- **Pitfalls / exam tips:** Don't confuse Peer Review (ICAI-run, PU-level systems review) with QRB (CG-constituted, statutory-audit quality review) or with NFRA (independent regulator with investigative/disciplinary powers over specified companies' auditors).

### National Financial Reporting Authority (NFRA)

- **Key formula(s)/rule(s):**
  - NFRA duties include: monitor & enforce compliance with accounting and auditing standards; oversee quality of service of the profession; investigate auditors of listed companies, and of unlisted public companies/other bodies corporate **specified under Rule 3 of the NFRA Rules, 2018**.
  - ⚠️ VERIFY — The Rule 3 monetary thresholds (commonly cited as paid-up capital ≥ ₹500 crore, or annual turnover ≥ ₹1,000 crore, or aggregate outstanding loans/debentures/deposits ≥ ₹500 crore, as at the end of the immediately preceding financial year, apart from listed companies, banks, insurers, and electricity companies) could not be re-verified against a live source this session — confirm exact figures from NFRA Rules, 2018 before quoting them in an answer.
  - QRB may review audit quality of entities **not** covered under Rule 3, if referred to it by NFRA.
- **Concept:** NFRA is the independent audit regulator (replacing ICAI's disciplinary monopoly for specified large/listed entities), while QRB/Peer Review continue to operate for the remaining universe of audits.
- **Pitfalls / exam tips:** A recurring theory question is "NFRA vs QRB vs Peer Review — jurisdiction & who constitutes whom" — tabulate this before the exam.

### SA 240 — Auditor's Responsibilities Relating to Fraud in an Audit of FS

- **Key formula(s)/rule(s):**
  - Two fraud types: **Fraudulent Financial Reporting (FFR)** — intentional misstatement to deceive users; **Misappropriation of Assets** — theft, usually smaller/immaterial amounts.
  - Fraud risk factors classified under **Incentive/Pressure, Opportunity, Attitude/Rationalisation** — for both FFR and misappropriation.
  - **Presumption of fraud risk in revenue recognition** — a rebuttable presumption; if rebutted, auditor must document the reasons.
  - Mandatory response to management-override risk: (a) test journal entries & other adjustments, (b) review accounting estimates for bias, (c) evaluate business rationale of significant unusual transactions.
- **Concept:** Primary responsibility for fraud prevention/detection rests with **management & TCWG**; the auditor's responsibility is limited to obtaining reasonable assurance that the FS as a whole are free from material misstatement due to fraud or error, applying professional scepticism throughout.
- **Pitfalls / exam tips:**
  - Risk of not detecting fraud is **higher than for error** (concealment, collusion, forgery) and **management fraud risk > employee fraud risk** (override ability).
  - If auditor concludes it is not possible to continue the engagement due to fraud: (i) determine professional/legal reporting duty, (ii) consider withdrawal, (iii) if withdrawing, discuss reasons with mgt/TCWG and consider reporting requirement to the appointing authority/regulators.

| Term | Meaning |
|---|---|
| FFR | Intentional misstatement/omission in FS to deceive users, e.g., manipulating journal entries, misapplying accounting principles |
| Misappropriation of Assets | Theft of entity assets, often concealed via false documentation |

### SA 250 — Consideration of Laws & Regulations (NOCLAR)

- **Key formula(s)/rule(s):**
  - Two categories of laws & regulations:
    1. Direct-effect L&Rs (e.g., tax, labour laws) → obtain **SAAE** of compliance.
    2. Other L&Rs fundamental to operations but no direct effect on amounts → **limited, specified audit procedures** (inquiry of management + inspection of correspondence with regulators) to identify non-compliance that may materially affect FS.
  - Reporting NOCLAR: material & intentional → communicate to TCWG **as soon as practicable**; if mgt/TCWG suspected of involvement → escalate to next higher authority (audit committee/supervisory board) or obtain legal advice.
- **Concept:** Mnemonic from the notes: **Understanding → SAAE (direct-effect L&Rs) → Inquiry/Inspection (other L&Rs) → Stay Alert → Written Representation**.
- **Pitfalls / exam tips:** Reporting impact on opinion — material & not adequately reflected in FS → Qualified/Adverse; precluded from obtaining SAAE → Qualified/Disclaimer; genuine scope limitation (not mgt-imposed) → evaluate as per SA 705.
- **Definitions:**

| Term | Meaning |
|---|---|
| NOCLAR | Non-compliance with Laws And Regulations — acts of omission/commission, intentional or not, contrary to prevailing laws/regulations |

### SA 260 — Communication with Those Charged With Governance (TCWG)

- **Key formula(s)/rule(s):**
  - Matters to be communicated: (a) auditor's responsibilities re: FS audit, (b) planned scope & timing of audit, (c) significant findings from the audit, (d) auditor independence (listed entities — **in writing**, including total fees for audit & non-audit services by firm & network firms, and safeguards applied).
  - Circumstances requiring additional report content, cross-referenced to their respective SAs: expected modification of opinion (SA 705), material uncertainty related to going concern (SA 570), Key Audit Matters (SA 701), Emphasis of Matter/Other Matter paragraphs (SA 706), uncorrected material misstatement of other information (SA 720).
- **Concept:** Two-way, timely communication — helps the auditor obtain audit-relevant information and helps TCWG discharge their oversight of the financial reporting process.
- **Pitfalls / exam tips:** For listed entities, the independence communication in writing is a favourite exam point — don't forget it must cover **total fees** for both audit and non-audit services, entity-wide (including controlled components).

### SA 265 — Communicating Deficiencies in Internal Control to TCWG & Management

- **Key formula(s)/rule(s):**
  - Deficiency in IC = a control fails to prevent/detect/correct misstatements on a timely basis, **or** a necessary control is missing.
  - Significant deficiency = deficiency/combination of deficiencies that, in the auditor's professional judgment, merit TCWG's attention.
  - Timing of communication: **listed entities — before approval of the FS**; **other entities — before assembly of the audit file** (i.e., within the SQC-1 60-day window).
  - Factors to judge significance (mnemonic **Likelihood-Interaction-Volume-FS amounts-Loss/fraud-Importance of controls**).
- **Concept:** Communication must be **in writing** to TCWG for significant deficiencies; deficiencies not previously communicated but still noteworthy go to management.
- **Pitfalls / exam tips:** A significant deficiency can exist even where no misstatement has actually occurred — likelihood and potential magnitude matter, not just actual occurrence.

### SA 299 — Joint Audit of Financial Statements

- **Key formula(s)/rule(s):**
  - Enabling provision: **Section 139(3), Companies Act 2013** — members may resolve that the audit be conducted by more than one auditor (joint auditors).
  - Responsibility split: **divided work → individual responsibility of the joint auditor to whom allocated**; **undivided work, joint decisions on common audit areas (planning-stage NTE), FS-compliance matters & disclosure/report compliance → joint & several responsibility** of all joint auditors.
  - Disagreement → each joint auditor free to express opinion in a **separate audit report**; not bound by majority view; cross-reference under an Other Matter (SA 706) paragraph.
- **Concept:** Joint auditors jointly plan (overall strategy, risk assessment communicated to each other, joint engagement letter & joint management representation letter) but individually execute their allocated area.
- **Pitfalls / exam tips:** Each joint auditor is entitled to **assume** (without independently verifying) that other joint auditors carried out their work as per SAs and would flag departures/observations — this "mutual trust" principle is commonly tested.

### SA 315 — Identifying & Assessing Risks of Material Misstatement (RoMM)

- **Key formula(s)/rule(s):**
  - Risk assessment procedures (RAP) mandatorily include: (a) inquiries of management & others, (b) analytical procedures, (c) observation & inspection.
  - Auditor's process: identify risks → assess whether pervasive to FS or specific to assertions → relate to what can go wrong at the assertion level, considering relevant controls → consider likelihood & magnitude of potential misstatement.
  - Significant risk = identified & assessed RoMM that, in the auditor's judgment, requires special audit consideration (drivers: fraud risk, significant economic/regulatory developments, transaction complexity, significant related-party transactions, high measurement subjectivity/estimation uncertainty, unusual/out-of-course transactions).
- **Concept:** Understand the entity & its environment (industry/regulatory factors, nature of entity, accounting policy choices, objectives/strategies/business risks, financial performance measurement) as the foundation for a risk-based audit.
- **Pitfalls / exam tips:** Significant risk assessment must always factor in **inherent risk**, not merely control reliance; per SA 330 controls over significant risks must be tested in the **current period** (no roll-forward from a prior audit).

### SA 320 — Materiality in Planning & Performing an Audit

- **Key formula(s)/rule(s):**
  $$ \text{Performance Materiality (PM)} < \text{Materiality for the FS as a whole} $$
  - PM is set below overall materiality (and, where applicable, below materiality level(s) for particular classes of transactions/balances/disclosures) to reduce the probability that the aggregate of uncorrected + undetected misstatements exceeds overall FS materiality.
  - Benchmark selection is a matter of **professional judgment** — SA 320 prescribes no fixed percentage; common benchmarks are profit before tax (profit-oriented entities; or gross profit/total revenue if PBT is volatile), total revenue, total expenses, total equity, or net assets (asset-custody entities) / total or net cost (public utility/not-for-profit projects).
  - Materiality is **revised** during the audit when new information, a change in circumstances, or a changed understanding of the entity indicates a different amount should have been used initially; if a **lower** materiality is concluded, reassess whether performance materiality and the NTE of further audit procedures remain appropriate.
- **Concept:** Two-stage materiality: (1) overall FS materiality (and specific materiality for sensitive classes/disclosures), (2) performance materiality — the working threshold actually used to design procedures.
- **Pitfalls / exam tips:** Do **not** quote a specific "5%/10% of PBT" rule as an ICAI-mandated figure in theory answers — SA 320 deliberately leaves the percentage to professional judgment; only the benchmark-selection *factors* (nature of entity, ownership/financing structure, focus of FS users, volatility, life-cycle stage) are examinable as fixed content.

### SA 330 — Auditor's Responses to Assessed Risks

- **Key formula(s)/rule(s):**
  - Further audit procedures = **Tests of Controls (TOC)** + **Substantive Procedures** (tests of details + substantive analytical procedures).
  - Substantive procedures are **mandatory for every material class of transactions, account balance and disclosure**, irrespective of assessed RoMM (risk assessment is judgmental and controls have inherent limitations, including management override).
  - Using prior-period audit evidence on controls: if no significant changes have occurred, test the control **at least once in every third audit**; controls addressing a **significant risk** must always be tested in the **current period**.
- **Concept:** The higher the assessed RoMM, the more persuasive the audit evidence required (link back to SA 315's risk assessment).
- **Pitfalls / exam tips:** TOC are performed when the auditor's risk assessment expects controls to operate effectively (planned reliance) OR when substantive procedures alone cannot provide SAAE — a frequently tested "when to perform TOC" MCQ.

### SA 402 — Audit Considerations Relating to an Entity Using a Service Organisation (SO)

- **Key formula(s)/rule(s):**
  - Report types: **Type 1** — description & design of controls at a specified date; **Type 2** — description, design & **operating effectiveness** of controls throughout a period.
  - If sufficient understanding cannot be obtained from the user entity: (a) obtain a Type 1/2 report, (b) contact SO through user entity, (c) visit the SO, or (d) use another auditor to perform procedures at the SO.
  - Reliance on a Type 2 report for operating effectiveness requires evaluating: description/design/operating effectiveness at the appropriate period, complementary user-entity controls, adequacy of the time period covered and time elapsed since testing, and relevance of TOC results to the user entity's assertions.
- **Concept:** SA 402 relevance test — do the SO's services affect the entity's **significant classes of transactions, the procedures that initiate/record/process/report them, related records, the information system, the financial reporting process, or journal entries** (mnemonic: SCoTs → Procedures + Records → Info system → FRP + JEs)?
- **Pitfalls / exam tips:** Failure to obtain SAAE about SO-relevant controls → modify opinion under **SA 705**; do not name the service auditor in an unmodified opinion unless required by law/regulation.

### SA 450 — Evaluation of Misstatements Identified During the Audit

- **Key formula(s)/rule(s):**
  - Accumulate all misstatements other than those that are **clearly trivial** (a wholly different, smaller order of magnitude than "not material" — any uncertainty means treat as *not* clearly trivial).
  - Three misstatement types: **Factual** (no doubt), **Judgmental** (mgt's estimate/policy judgment auditor finds unreasonable/inappropriate), **Projected** (sample-based extrapolation to the population).
  - Auditor **reassesses materiality** (per SA 320) before evaluating the effect of uncorrected misstatements, then evaluates size & nature (individually/aggregate) plus the effect of uncorrected prior-period misstatements.
- **Concept:** Evaluate whether the strategy/plan need revision as misstatements accumulate — trigger points: nature/circumstances suggest more misstatements may exist, or the accumulated total *approaches* materiality.
- **Pitfalls / exam tips:** Always request a **Written Representation** from mgt/TCWG that they believe the effects of uncorrected misstatements are immaterial, individually and in aggregate, to the FS as a whole.

### SA 500 — Audit Evidence (including Management's Expert)

- **Key formula(s)/rule(s):**
  - Evaluate a management's expert's work via **CCO** → Understanding of the expert's work → Appropriateness as evidence (source data / assumptions & methods / findings).
  - Threats to a management expert's objectivity — mnemonic **SSAFI**: Self-interest, Self-review, Advocacy, Familiarity, Intimidation threats.
- **Concept:** Info produced by the entity (or a management's expert) used as audit evidence must itself be evaluated for reliability, completeness and accuracy before being relied upon.
- **Pitfalls / exam tips:** An expert **employed** by the entity can never be regarded as more objective than any other employee (permanent intimidation/familiarity threat exists); this contrasts with an **engaged** external expert, where safeguards can meaningfully reduce threats.

| Term | Meaning |
|---|---|
| CCO | Competence, Capabilities & Objectivity — the three-way evaluation criteria for a management's expert |

### SA 501 — Audit Evidence: Specific Considerations for Selected Items

- **Key formula(s)/rule(s):**
  - **Inventory:** attend physical count (unless impracticable) — evaluate mgt's counting instructions, observe count procedures, inspect inventory, perform test counts; if attendance is impracticable, perform alternative procedures (e.g., inspect subsequent-sale documentation); if SAAE still unobtainable → modify opinion (SA 705).
  - "General inconvenience" (cost/time/difficulty) is **not** a valid basis to treat attendance as impracticable (per SA 200's principle that difficulty/cost never justifies omitting a procedure with no alternative).
  - **Litigation & claims:** identify via inquiry of mgt/in-house counsel, review of TCWG minutes, review of legal expense accounts, then seek **direct communication with External Legal Counsel (ELC)** via a letter of inquiry (general, then specific if no response).
  - **Segment information:** obtain SAAE on presentation & disclosure via understanding of mgt's determination methods + analytical/other procedures.
- **Concept:** Existence & condition of inventory, completeness of litigation/claims, and presentation & disclosure of segment info are the three specific-item objectives of SA 501.
- **Pitfalls / exam tips:** Inventory held by a **3rd party**: obtain confirmation from the 3rd party **and/or** perform inspection; if doubts exist about the 3rd party's integrity/objectivity, attend/arrange attendance at the 3rd-party count or obtain another auditor's/service auditor's report on the 3rd party's controls.

### SA 505 — External Confirmations

- **Key formula(s)/rule(s):**
  - Factors in designing confirmation requests — mnemonic **LAPRMM**: Layout & presentation, Assertions addressed, Prior experience, specific identified RoMM (fraud risk), Management authorisation, Method of communication.
  - **Negative confirmation requests (NCR)** cannot be the *sole* substantive procedure for an assertion unless **all four** conditions hold: (a) assessed RoMM is low & operating effectiveness of related controls is evidenced, (b) population is large & homogeneous, small balances, (c) very low exception rate expected, (d) no circumstance causes recipients to disregard the request.
  - Mgt refuses a confirmation request → (a) inquire reasons & seek evidence of validity, (b) evaluate implication for RoMM/fraud risk & NTE of other procedures, (c) perform alternative procedures; if refusal unreasonable or alternative evidence unobtainable → communicate with TCWG (SA 260) and consider effect on opinion (SA 705).
- **Concept:** Positive confirmation is more persuasive than negative; a "blank" positive confirmation (no amount stated) reduces the risk of rubber-stamping but tends to lower response rates.
- **Pitfalls / exam tips:** Non-response ≠ Exception. Non-response → perform alternative procedures (e.g., subsequent cash receipts for receivables, subsequent disbursements for payables). Exception → investigate to determine if it indicates a misstatement, then assess its effect on the whole population.

### SA 510 — Initial Audit Engagements — Opening Balances

- **Key formula(s)/rule(s):**
  - Objective: obtain SAAE that (a) opening balances contain no misstatement materially affecting the current period, and (b) prior-period accounting policies have been consistently applied/appropriately changed & disclosed.
  - Procedures: read most recent FS & audit report; determine whether closing balances were correctly brought forward (or adjustments disclosed as prior period items); if the prior period was audited, perusing the audited FS is itself an acceptable procedure.
  - Reporting: unable to obtain SAAE → Qualified/Disclaimer; opening balances materially misstated & not corrected/disclosed → Qualified/Adverse; predecessor's modified opinion still relevant & material to current FS → modify current-period opinion too.
- **Concept:** For current-asset/liability items (debtors/creditors), current-year collection/payment itself provides audit evidence about the opening balance; inventory needs additional procedures since the current count doesn't evidence the *opening* balance.
- **Pitfalls / exam tips:** SA 510 applies whenever prior-period FS were **not audited, or were audited by a predecessor auditor** — not just to genuinely "new" companies.

### SA 520 — Analytical Procedures

- **Key formula(s)/rule(s):**
  - Substantive Analytical Procedure (SAP) design steps — mnemonic **Suitability → Reliability → Expectation → Investigation**: (a) determine suitability of the SAP for the assertion given assessed RoMM, (b) evaluate reliability of underlying data, (c) develop a sufficiently precise expectation, (d) set the acceptable difference threshold before investigating.
  - Mandatory near-end-of-audit analytical procedures to form the overall conclusion that the FS are consistent with the auditor's understanding of the entity.
- **Concept:** Analytical procedures = evaluations of financial information through analysis of plausible relationships among financial **and** non-financial data.
- **Pitfalls / exam tips:** Unexpected fluctuations must be investigated by (a) inquiry of mgt + corroboration of the response, then (b) other audit procedures if the explanation is inadequate or unavailable — inquiry alone is never sufficient.

### SA 530 — Audit Sampling

- **Key formula(s)/rule(s):**
  $$ \text{Sampling Interval} = \dfrac{\text{Population Size}}{\text{Sample Size}} $$
  (e.g., 5,000 items, 100 samples required → interval = 50; pick a random start within the first 50, then every 50th unit thereafter — this is **systematic selection**.)
  - Tolerable Misstatement (TM) = performance materiality applied to a sampling procedure; may equal or be lower than performance materiality.
  - Sampling risk — two error types: (i) auditor concludes controls are more effective / misstatement doesn't exist when in fact it does → **effectiveness risk**, wrong opinion; (ii) auditor concludes controls are less effective / misstatement exists when it doesn't → **efficiency risk**, unnecessary extra work.
  - Detection risk = **Sampling risk + Non-sampling risk**.
- **Concept:** Sample selection methods: random (simple/stratified), systematic, monetary unit sampling (value-weighted), haphazard; **block selection cannot be used** in audit sampling.
- **Pitfalls / exam tips:** A misstatement/deviation treated as an "anomaly" is excluded from projection **only** in extremely rare circumstances with a high degree of certainty it's non-representative — if uncorrected, it's still added back to the projected misstatement total.

### SA 540 — Auditing Accounting Estimates, Including Fair Value Accounting Estimates & Related Disclosures

- **Key formula(s)/rule(s):**
  - Estimation-making process to understand — mnemonic **MACC**: Method used, Assumptions, whether an expert/Control (relevant controls) used, and how mgt assessed estimation uncertainty (Change from prior period, if any, and why).
  - For accounting estimates with **significant risk**, additionally evaluate: how mgt considered alternative assumptions/outcomes; whether significant assumptions are reasonable; mgt's intent & ability to carry out a course of action; if inadequately addressed, the auditor develops **a range** to evaluate reasonableness.
  - Objective: obtain SAAE that (a) accounting estimates (incl. FV estimates) are reasonable, and (b) related disclosures are adequate, as per the AFRF.
- **Concept:** Higher estimation uncertainty (unobservable inputs, entity-specific models, litigation outcomes) → higher RoMM and often a **significant risk**; management bias (unintentional or intentional/fraudulent) is often visible only in aggregate or over multiple periods, not at a single estimate.
- **Pitfalls / exam tips:** Difference between the *outcome* of an estimate and the amount originally recognised is **not automatically a misstatement** — especially for fair value estimates, since the outcome is affected by events *after* the measurement date.

| Term | Meaning |
|---|---|
| Estimation Uncertainty | Susceptibility of an accounting estimate to an inherent lack of measurement precision |
| Management Bias | Lack of neutrality in making an accounting estimate — may be unintentional or, where there is intent to mislead, fraudulent |

### SA 550 — Related Parties (RP)

- **Key formula(s)/rule(s):**
  - Definition layers: RP as per the applicable FRF; or (if the FRF has minimal/no RP definition) a party with control/significant influence over the entity, an entity the reporting entity controls/significantly influences, or an entity under common control (common ownership, close family owners, or common key management).
  - Government-controlled entities exception (Ind AS 24): not automatically "related" **unless** significant transactions occur or significant resources are shared; disclosure still required of the government's relationship and the nature/amount of individually and collectively significant transactions.
  - Documents to inspect for **undisclosed** RP — mnemonic focus: bank/legal/3rd-party confirmations, minutes of shareholder & TCWG meetings, tax returns, internal audit reports, regulator filings, shareholder registers, investment/pension records, conflict-of-interest statements, key-mgt contracts, renegotiated or unusual/out-of-course significant contracts.
- **Concept:** Domination of management by a single person/small group without compensating controls is itself a **fraud risk factor** under SA 550.
- **Pitfalls / exam tips:** Newly identified undisclosed RP transaction → sequence is **Prompt communication to engagement team → Management (identify all transactions + inquire why controls failed) → Perform substantive procedures → Evaluate implications if non-disclosure appears intentional**.

### SA 560 — Subsequent Events

- **Key formula(s)/rule(s):**
  - Two categories of events: (1) between the **date of FS** and the **date of the audit report** — obtain SAAE that all requiring adjustment/disclosure have been identified; (2) facts becoming known **after** the report date (before/after FS issuance) — no ongoing obligation to actively search, but if a fact would have changed the report, act.
  - Facts known after the report date but before FS issuance, if mgt amends FS: extend procedures to the date of the new report and date the new/amended report **not earlier than the approval date of the amended FS**; if restricted-amendment is permitted by law, use **dual dating** or an EOM/OM (SA 706) paragraph restricting procedures to the amendment.
  - Mgt refuses to amend when required → if report not yet provided, modify opinion (SA 705) & provide it; if already provided, notify mgt/TCWG not to issue FS to third parties, and take action (including legal advice) to prevent reliance if they issue anyway.
- **Concept:** No auditor obligation to perform procedures on FS **after** the audit report is issued — the trigger is always a fact "becoming known," not an active re-audit requirement.
- **Pitfalls / exam tips:** A frequently tested sequence: discuss with mgt/TCWG → determine if FS need amendment → inquire how mgt intends to address it → carry out audit procedures on the amendment → obtain WR that all subsequent events have been adjusted/disclosed.

### SA 570 — Going Concern (GC)

- **Key formula(s)/rule(s):**
  - Management's GC assessment period must cover **at least 12 months** from the date of the FS; if mgt's assessment covers less, the auditor requests an extension to at least 12 months.
  - Reporting matrix:
    - GC basis **inappropriate** → **Adverse opinion** (even if mgt discloses this in the FS).
    - GC basis appropriate, **material uncertainty (MU) exists**, adequately disclosed → **unmodified opinion** + separate **"Material Uncertainty Related to Going Concern"** section (drawing attention to the FS note, stating the MU, and that the opinion is not modified).
    - GC basis appropriate, MU exists, **not** adequately disclosed → **Qualified or Adverse opinion** (SA 705), with the MU description added to the Basis for Opinion section.
    - Mgt unwilling to make/extend its GC assessment → consider **Qualified opinion or Disclaimer of opinion**.
  - A material uncertainty related to going concern is, **by its nature, always a Key Audit Matter (SA 701)**.
- **Concept:** MU exists when the magnitude of impact and likelihood of occurrence of the identified events/conditions make appropriate disclosure necessary; the auditor can never guarantee an entity's going-concern status.
- **Pitfalls / exam tips:** Financial/operating/other indicators (mnemonic groups: financial ratios & liquidity; operating — key mgt loss, market/customer loss; other — non-compliance, litigation, uninsured catastrophe) are a favourite "identify going-concern indicators from a case study" question — memorise the three buckets.

### SA 580 — Written Representations (WR)

- **Key formula(s)/rule(s):**
  - WR are dated **as near as practicable to, but not after,** the date of the audit report, and must cover **all periods** referred to in the auditor's opinion — even where current management wasn't present in a prior period.
  - WR alone are **not** sufficient appropriate audit evidence about the matters they address — they support, but never replace, other audit evidence.
  - If WR are inconsistent with other evidence, or mgt refuses to provide requested WR → reassess mgt's diligence/integrity/competence/ethical values → consider effect on reliability of representations generally → take appropriate action, up to and including **Disclaimer of Opinion** (SA 705).
- **Concept:** A written statement from management, addressed to the auditor, confirming matters or supporting other evidence — but explicitly excluding the FS themselves or the books/records underlying them.
- **Pitfalls / exam tips:** Distinguish "WR not provided" (procedural failure → SA 580 response) from "WR provided but unreliable" (substantive doubt → also SA 580, but pivots on reassessing management integrity).

### SA 600 — Using the Work of Another Auditor

- **Key formula(s)/rule(s):**
  - Acceptance-as-Principal-Auditor (PA) factors — mnemonic **MDRA**: Materiality of the portion PA itself audits, Degree of PA's knowledge of the component's business, RoMM in the component's financial info, Additional procedures needed given PA's participation.
  - PA's procedures: right to visit the component & examine records if necessary; evaluate the other auditor's competence (if not an ICAI member); obtain SAAE that the other auditor's work is adequate; advise/coordinate at planning stage; inform on inter-component transactions, timetable, areas of special consideration, and reporting requirements.
  - Documentation: must record components audited by other auditors, procedures performed, and — if the other auditor's report is other than unmodified — **how the PA dealt with the qualification/adverse remarks** in framing the PA's own report.
- **Concept:** SA 600 does **not** apply to joint audits (SA 299) or to the predecessor-auditor relationship (SA 510/710).
- **Pitfalls / exam tips:** PA is entitled to a **limited-liability "division of responsibility"** disclosure in the report, but remains responsible for the overall opinion except in circumstances of suspicion about the reliability of the other auditor's work — a common trap answer wrongly makes the PA fully liable for the other auditor's work.

### SA 620 — Using the Work of an Auditor's Expert

- **Key formula(s)/rule(s):**
  - Considerations to decide whether to use an auditor's expert: whether mgt used a mgt's expert, nature/significance/complexity of the matter, RoMM involved, expected NTE of procedures & auditor's own experience with experts, availability of alternative evidence sources.
  - Mandatory **written agreement** with the auditor's expert covering: nature/scope/objectives of the work, roles & responsibilities, nature/timing/extent of communication (including report form), and confidentiality.
  - Evaluating adequacy of the expert's work: inquiries of the expert, review of working papers/reports, corroborative procedures (observation, published data, 3rd-party confirmation, analytical procedures, re-performance), discussion with another expert if findings conflict with other evidence.
  - Inadequate work & unresolved → **modify opinion (SA 705)** for inability to obtain SAAE.
- **Concept:** Threats to an auditor's **external** expert's objectivity are evaluated the same way as for a management's expert (SSAFI threats + safeguards), but reference to the expert in an **unmodified** opinion report is prohibited unless required by law/regulation.
- **Pitfalls / exam tips:** NSRA factors (Nature of the matter, Significance in context of the audit, auditor's own experience/knowledge with the expert, whether subject to the firm's own QC policies) drive **how extensive** the auditor's procedures on the expert's work must be — more extensive where the expert is external/not firm-QC-subject and the matter is significant & judgmental.

### SA 700 — Forming an Opinion & Reporting on Financial Statements

- **Key formula(s)/rule(s):**
  - Basic elements of the audit report (mandatory sequence/content): Title ("Independent Auditor's Report"), Addressee, Opinion section (identify entity, state FS audited, identify each statement, refer to notes/accounting-policy summary, specify period covered), Basis for Opinion (SA compliance, independence & ethics statement referencing the ICAI Code of Ethics, SAAE statement), [Material Uncertainty re: GC — SA 570], Key Audit Matters (listed entities — SA 701), Responsibilities of Management for FS, Auditor's Responsibilities for the Audit, Other Reporting Responsibilities, Signature (personal name + firm name + membership/FRN + **UDIN**), Place of signature, Date of report.
  - **Date of audit report** must not be earlier than the date the auditor (a) obtained SAAE, (b) the FS were prepared, and (c) those with authority took responsibility for the FS.
  - Fair presentation framework wording: *"present fairly, in all material respects"* or *"give a true and fair view"* (treated as equal); compliance framework wording: *"prepared, in all material respects, in accordance with [AFRF]."*
- **Concept:** SA 700 is the "assembly standard" — it pulls together the conclusions of every earlier SA (fraud, materiality, risk, evidence, going concern, KAM, other information) into the final unmodified/modified report shell.
- **Pitfalls / exam tips:** UDIN is mandatory for **both manually and digitally signed** reports/certificates — a common one-mark trap.

### SA 701 — Communicating Key Audit Matters (KAM) in the Independent Auditor's Report

- **Key formula(s)/rule(s):**
  - Applicability: complete sets of general-purpose FS of **listed entities**, and other cases where the auditor decides to communicate KAM or law/regulation requires it.
  - KAM determination factors: areas of higher assessed RoMM/significant risk (SA 315); significant auditor judgments on areas involving significant management judgment (incl. high estimation-uncertainty estimates); effect of significant events/transactions during the period.
  - Placement in the report: **after** the Basis for Opinion paragraph and **before** Management's Responsibility paragraph; if a Material Uncertainty Related to Going Concern section exists, KAM is placed **after** it; an EOM paragraph (SA 706) may sit directly before or after the KAM section, per auditor's judgment.
  - Communicating KAM is **not** a substitute for: disclosures required by the AFRF, a modified opinion (SA 705), or SA 570 reporting on going-concern material uncertainty; nor is it a separate opinion on individual matters.
- **Concept:** KAM are selected from matters already **communicated with TCWG** — not a fresh universe of issues.
- **Pitfalls / exam tips:** If there are genuinely no other KAM beyond a Basis-for-Qualified/Adverse-Opinion matter or a Material-Uncertainty-re-GC section, the report must still carry a **"Key Audit Matters"** heading stating there are no other KAM to communicate — don't omit the heading.

### SA 705 — Modifications to the Opinion in the Independent Auditor's Report

- **Key formula(s)/rule(s):**
  - Modification matrix:

| Auditor's conclusion | Material only | Material & Pervasive |
|---|---|---|
| FS contain a misstatement (SAAE obtained) | **Qualified Opinion** | **Adverse Opinion** |
| Unable to obtain SAAE (possible effects) | **Qualified Opinion** | **Disclaimer of Opinion** |

  - "Pervasive" = not confined to specific elements/accounts (or, if confined, represents a substantial proportion of the FS), or fundamental to users' understanding for disclosures.
  - Disclaimer wording change: auditor states they were only "**engaged to audit**" the FS (not that they "have audited" the FS), and the report omits the standard SAAE-sufficiency statement and the cross-reference to the auditor's responsibilities section.
  - Mgt-imposed scope limitation *after* engagement acceptance → request removal → if refused, communicate TCWG & attempt alternative procedures → if still unresolved: material-not-pervasive → Qualified; material-and-pervasive → **withdraw if practicable, else Disclaim**.
  - **SEBI provisions on auditor resignation (listed entities):** if the auditor proposes to resign **within 45 days** from the end of a quarter, it must first issue a Limited Review (LR) Report for that quarter; if resigning **after 45 days** from quarter-end, issue an Audit/LR Report for that quarter **and** the next one; if LR reports were already issued for the first three quarters, issue the full-year Audit Report before resigning.
- **Concept:** SA 705 governs *how* to phrase and structure a modified opinion once SA 200/315/330/other SAs have already established that a misstatement (or scope limitation) is material.
- **Pitfalls / exam tips:** "Professional pre-occupation" is **not** an acceptable stated reason for an unlisted company auditor's resignation per ICAI's clarification — the resignation letter must state the actual reason.

### SA 706 — Emphasis of Matter (EOM) & Other Matter (OM) Paragraphs

- **Key formula(s)/rule(s):**
  - **EOM paragraph** — refers to a matter **already appropriately presented/disclosed in the FS** that is, in the auditor's judgment, fundamental to users' understanding; permitted only if (a) it does not itself require a modified opinion under SA 705, and (b) it is not already a KAM under SA 701 (where SA 701 applies).
  - **OM paragraph** — refers to a matter **other than** what is presented/disclosed in the FS, relevant to users' understanding of the audit, the auditor's responsibilities, or the report; permitted only if not prohibited by law/regulation and not already a KAM.
  - Neither paragraph is a substitute for: a modified opinion (SA 705), required FS disclosures, or SA 570 going-concern reporting.
- **Concept:** EOM = "look again at something already disclosed"; OM = "here's something relevant that isn't in the FS at all" (e.g., prior-period auditor identity, unaudited branch FS, comparative-period issues).
- **Pitfalls / exam tips:** Always communicate the **expectation** and proposed **wording** of an EOM/OM paragraph to TCWG in advance, and always close with "our opinion is not modified in respect of this matter."

### SA 710 — Comparative Information: Corresponding Figures & Comparative Financial Statements

- **Key formula(s)/rule(s):**
  - Two reporting approaches: **Corresponding figures** — the auditor's opinion refers to the **current period only**; **Comparative FS** — the opinion refers to **each period presented** separately.
  - Corresponding-figures reporting: opinion refers to them only when (1) an unresolved prior-period modification continues to affect the current period (Basis-for-Modification section refers to both current & corresponding figures, or explains the effect on comparability), or (2) a material misstatement is discovered in prior-period FS that carried an unmodified opinion and remains unresolved (→ qualify/adverse the current-period opinion).
  - Common requirement for both approaches: if prior-period FS were audited by a **predecessor auditor**, state in the Other Matter paragraph: that a predecessor audited them, the type of opinion expressed, and its date; if prior-period FS were **unaudited**, state that the corresponding/comparative figures are unaudited (this does not relieve the auditor of the SA 510 obligation on opening balances).
- **Concept:** Auditor still applies SA 560 and SA 580 (WR for all periods referred to, plus specific WR on any prior-period item reclassified through current-year P&L) regardless of which reporting approach is used.
- **Pitfalls / exam tips:** Don't confuse "comparative FS" (full re-opinion each period) with "corresponding figures" (single current-period opinion, prior year is just context) — India predominantly uses the corresponding-figures approach.

### SA 720 — The Auditor's Responsibility in Relation to Other Information

- **Key formula(s)/rule(s):**
  - Scope: "other information" = financial or non-financial information in the Annual Report, **other than the FS and the auditor's report thereon**; the auditor's opinion does **not** cover it. Does **not** apply to preliminary announcements of financial info or prospectuses.
  - Procedure: read & consider other information for **material inconsistency** with the FS or with the auditor's audit knowledge; remain alert for indications the other information may itself be materially misstated.
  - If materially misstated & mgt refuses to correct → communicate with TCWG → if still uncorrected: obtained before report date → consider implications for the auditor's report / withdraw if possible; obtained after report date → take appropriate action per legal rights/obligations to bring the uncorrected misstatement to users' attention.
  - Reporting: a mandatory separate **"Other Information"** section is required when, at the report date, the auditor has (or, for listed entities, expects to) obtain some/all of the other information (also required for unlisted corporate entities if any other information was obtained).
- **Concept:** SA 720 is a "read-and-flag" standard, not an assurance standard — the auditor never expresses an opinion on the Annual Report's non-FS content.
- **Pitfalls / exam tips:** For **listed entities**, the Other Information section must also identify information the auditor **expects to obtain after** the report date — a detail frequently missed for unlisted-entity answers where this forward-looking identification isn't required.

### References
1. Standard on Quality Control (SQC) 1, "Quality Control for Firms that Perform Audits and Reviews of Historical Financial Information, and Other Assurance and Related Services Engagements," ICAI.
2. Standards on Auditing SA 220, SA 240, SA 250, SA 260, SA 265, SA 299, SA 315, SA 320, SA 330, SA 402, SA 450, SA 500, SA 501, SA 505, SA 510, SA 520, SA 530, SA 540, SA 550, SA 560, SA 570, SA 580, SA 600, SA 620, SA 700, SA 701, SA 705, SA 706, SA 710, SA 720, as issued by the Institute of Chartered Accountants of India (ICAI), applicable for the current CA Final syllabus.
3. Companies Act, 2013 — Section 139(3) (joint audit enabling provision) and related audit provisions referenced within the above SAs.
4. NFRA Rules, 2018 (referenced for NFRA jurisdiction under Rule 3 — figures flagged for verification above) and NFRA constitution/duties as discussed in ICAI study material.
5. SEBI (LODR) framework / SEBI circular on statutory auditor resignation timelines for listed entities, as summarised in ICAI study material.
6. ICAI Code of Ethics — independence & engagement-partner rotation provisions referenced under SQC-1/SA 220 (familiarity threat).

## 02. Professional Ethics (Fundamental Principles, Threats, NOCLAR, Schedules, Council Guidelines, ESB Decisions)

> **Where it fits:** This chapter is the "conduct law" of the CA profession — the ICAI Code of Ethics (fundamental principles, threats/safeguards, NOCLAR), the Chartered Accountants Act, 1949 (membership, COP, First & Second Schedules on misconduct), Council General Guidelines, 2008 (tax-audit/company-audit ceilings, fee rules, UDIN, networking), and recent ESB clarifications — it is tested heavily as practical "guilty/not guilty" case-study questions.

### Fundamental Principles of Ethics (ICAI Code of Ethics)

- **Key rule(s):**
  - Five fundamental principles — mnemonic **"I-O-P-C-B"**: **I**ntegrity, **O**bjectivity, **P**rofessional Competence & Due Care, **C**onfidentiality, **B**ehaviour (Professional).
  - Confidentiality survives the end of the professional relationship — a member may disclose only when: (a) disclosure is required by law, (b) disclosure is permitted by law and authorised by the client/employer, or (c) there is a professional duty/right to disclose (peer/quality review, responding to an inquiry by a regulatory body, protecting professional interests in legal proceedings, complying with technical/ethical standards).

**Concept:** These are the baseline behavioural standards every member (in practice or service) must meet in every professional/business relationship; a conflict between two principles is resolved by consulting others within the organisation, TCWG, ICAI, or legal counsel.

**Pitfalls / exam tips:**
- Do not confuse "Professional Behaviour" (compliance with laws/regulations, no conduct discrediting the profession, no exaggerated advertising claims) with "Professional Competence & Due Care" (technical competence + diligence + supervision of staff).
- In case studies, always name the specific principle(s) breached before concluding "guilty."

**Definitions:**

| Term | Meaning |
|---|---|
| Integrity | Straightforward and honest in all professional and business relationships; not associated with materially false, negligent, or misleading information |
| Objectivity | Professional/business judgment not compromised by bias, conflict of interest, or undue influence |
| Professional Behaviour | Compliance with laws/regulations; avoiding conduct that discredits the profession |

### Threats to Fundamental Principles and Safeguards

- **Key rule(s):** Five threat categories — mnemonic **SAFAI**: **S**elf-interest, **A**dvocacy, **F**amiliarity, **A**ccountant's Self-review (Self-review), **I**ntimidation.

$$
\text{Threat present} \;\Rightarrow\; \text{Evaluate significance} \;\Rightarrow\; \text{Apply safeguard} \;\Rightarrow\; \text{Threat eliminated / reduced to acceptable level}
$$

**Concept:** A threat is a circumstance that could compromise compliance with the fundamental principles; safeguards are actions (individually or in combination) that eliminate the threat or reduce it to an acceptable level.

**Pitfalls / exam tips:**
- Classic self-interest examples: direct financial interest in client, quoting an abnormally low fee ("lowballing"), close business relationship, access to confidential info for personal gain, contingent fees.
- Classic self-review: auditing your own firm's earlier work (e.g., certifying effectiveness of a system the firm designed, or auditing books the firm helped prepare).
- Classic advocacy: promoting client shares, acting as advocate in client litigation, lobbying for client legislation.
- Classic familiarity: long association of engagement team member with client, close family member as director/officer of client.
- Classic intimidation: threat of dismissal/replacement, pressure to accept an inappropriate accounting treatment.
- Safeguard examples: independent reviewer (not engagement team member); separate teams/reporting lines for non-assurance services; involving another firm for part of the engagement; additional time and qualified personnel.

**Definitions:**

| Threat | Trigger |
|---|---|
| Self-interest | Financial or other interest inappropriately influencing judgment/behaviour |
| Self-review | Failure to appropriately evaluate results of a previous judgment/service by self/firm |
| Advocacy | Promoting a client's/employer's position to the point objectivity is compromised |
| Familiarity | Long/close relationship leading to being too sympathetic to client's/employer's interests |
| Intimidation | Deterred from acting objectively by actual or perceived pressures |

### NOCLAR — Non-Compliance with Laws and Regulations

- **Key rule(s):**
  - Applicability to CAiP (practice): audit engagements of entities listed on a **recognised stock exchange in India** with **net worth ≥ ₹250 crore**.
  - Applicability to members in service: senior professional accountants (directors, officers, senior employees) employed by listed entities.
  - 7-step response framework: (1) Obtain understanding of the matter → (2) Address the matter with management/TCWG → (3) Seek advice (legal/professional body) → (4) Determine if further action is needed → (5) Determine whether to disclose to an appropriate authority → (6) Consider imminent breach → (7) Document.
  - Documentation must record: how management/TCWG responded, the course of action considered and judgments/decisions taken, and how the accountant is satisfied the public-interest responsibility has been discharged.

**Concept:** NOCLAR sets out the professional accountant's responsibility on becoming aware of an actual or suspected act of non-compliance (fraud, corruption, bribery, money-laundering, tax evasion, environmental/public-health breaches, securities-law and data-protection violations, etc.) by the client/employer, its management, TCWG, or other persons working for them.

**Pitfalls / exam tips:**
- The accountant is **not** required to investigate or ensure complete compliance with all laws; is **not** expected to have legal expertise beyond ordinary knowledge and professional judgment; matters that are "clearly inconsequential" or personal misconduct unconnected to the client's business are out of scope; disclosure that is itself contrary to law is not required.
- In exceptional circumstances of an **imminent breach** causing substantial harm to investors, creditors, employees, or the public, the accountant may, after discussing with management/TCWG, exercise judgment and disclose immediately to an appropriate authority — this disclosure is expressly *permitted* under NOCLAR (there is no equivalent provision under SA 250).

**Definitions:**

| Term | Meaning |
|---|---|
| NOCLAR vs SA 250 | SA 250 applies only to audits and covers laws with a direct effect on FS amounts/disclosures + other laws fundamental to the business; NOCLAR applies to accountants in both service and practice, and additionally covers non-compliance causing substantial harm (financial/non-financial) to stakeholders — a concept SA 250 does not define |

### Membership of ICAI — CA Act, 1949

- **Key rule(s) (Section 8 — Disabilities for Membership):**
  - Under 21 years of age
  - Of unsound mind (as adjudged by a competent court)
  - An undischarged insolvent
  - An discharged insolvent who has not obtained a court certificate that the insolvency was caused by misfortune without misconduct
  - Convicted by a court of an offence involving moral turpitude (unless the disability is removed by the Central Government)
  - Removed from ICAI membership for professional or other misconduct

$$
\text{Fellow membership} = \text{Associate member continuously in practice} \geq 5 \text{ years, OR possessing equivalent prescribed experience}
$$

- **Section 24 — Penalty for falsely claiming to be a member:**
  - Not a member but represents himself as one / uses the designation "CA" → punishable on **1st conviction: fine up to ₹1,000**; on **subsequent conviction: imprisonment up to 6 months, or fine up to ₹5,000, or both**.
- **Section 6 — Certificate of Practice (COP):** No member shall practise in India or elsewhere without a COP from the Council; annual fee payable; COP may be cancelled by the Council in prescribed circumstances.
  - COP is cancelled if: name removed from Register; member ceases to practise; COP was obtained on incorrect/misleading/false information or by mistake; annual COP fee not paid by **30th September** of the relevant year.
- **Section 27 — Branch office:** If a CAiP/firm has more than one office in India, each office must be in the separate charge of a member who resides at, or attends, that office for **not less than 182 days** in that year.
  - Exemption from separate charge for a 2nd office if it is: (a) in the same premises, or (b) in the same city, or (c) within **50 km** of the municipal limits of the city where the 1st office is located (member must declare which is the main/professional address).
- **Effective date of restoration of membership:** if application + fee is made within the **same year** of removal → restored with effect from the date of removal; if removal was under orders of the Board of Discipline/Disciplinary Committee/Appellate Authority/High Court → restoration as per such orders; in other cases → restoration from the date application and fee are received.

**Concept:** These sections govern who may call themselves a "Chartered Accountant," who may practise (needs a COP), and the consequences of misusing the designation or practising without authority.

**Pitfalls / exam tips:**
- A CAiP whose COP is suspended/surrendered **cannot** take up any other work that is separable from the CA capacity (e.g., income-tax representation) — because such work is "normally the work of a CA," he remains bound by the CA Act. He *may*, however, take up work in a genuinely distinct professional capacity (e.g., as a registered Data Privacy consultant) that does not require CA qualification.
- "Member deemed to be in practice" per **Section 2(2)**: engaging in accountancy practice; performing/offering audit, verification, or certification of FS; rendering professional services on accounting/financial matters; or any other service the Council notifies (this is the gateway to "Management Consultancy & Other Services," MCS, under Sec 2(2)(iv)).
- MCS **excludes** statutory/tax audit, representation in tax matters, and acting as liquidator/trustee/executor/arbitrator/receiver — but **includes** financial management/planning, capital structure advice, project reports, valuation of shares/business (registered valuer role; valuation of plant & machinery is **not** allowed), systems/EDP services, recovery consultancy in banking (NPAs), and acting as Insolvency Professional.
- ⚠️ VERIFY — the source lists "portfolio management, underwriting & broking (PUB)" as explicitly **not permitted** as MCS — this is well established, but double-check the exact current wording in the latest Code of Ethics before quoting verbatim in an answer.

### Designations, Advertisement & Website Guidelines (Council Guidelines under Clauses 6 & 7)

- **Key rule(s):**
  - No solicitation of clients/work by circular, advertisement, personal communication, or interview — **except** (a) approaching another CAiP for work, or (b) responding to tenders/enquiries from users of professional services.
  - Responding to tenders in areas **exclusively reserved for CAs** (e.g., audit/attestation) is permitted only where the tender **prescribes a minimum fee**.
  - A "write-up" advertisement must be: honest & truthful; no exaggerated claims; no disparaging comparisons; no testimonials; **font size up to 14**; no logo/monogram other than the official CA logo; membership/firm registration number stated; date of setting up the firm **not** to be mentioned on letterheads (website disclosure of this date is permitted).
  - Designations **not permitted** alongside "CA": Income-tax Consultant, Cost Accountant, Company Secretary, Cost Consultant, Management Consultant, Corporate Lawyer, "Member of Parliament"/"Municipal Councilor." Designations **permitted**: "Insolvency Professional," "Registered Valuer" (titles recognised by CG).
  - Firm website: must be **pull-model** (visitor-initiated), not push (unsolicited email/circulation); may disclose firm name, year of establishment, address/contact details, nature of services (on specific pull request), partner details, job vacancies, passport-size photos; client names/fees **cannot** be disclosed unless required by a regulator, and if disclosed, a specific attribution note must appear in italics below the disclosure.

**Concept:** These clarify how far a member may go in making the public aware of the firm without crossing into prohibited solicitation/advertisement under Clauses (6) and (7) of Part I, First Schedule.

**Pitfalls / exam tips:**
- A CA who is a director in a company whose prospectus/public announcement highlights his professional attainments is guilty under Clauses (6) & (7) — he must proactively ask the company to avoid such wording.
- Application-based aggregator platforms (e.g., listing CAs alongside unrelated service categories) are **not permissible**; specialised "Who's Who"-type directories with alphabetical, non-prominent listing are permitted.
- Sponsoring events directly is **not permitted**; sponsoring a Continuing Professional Education (CPE) Programme Organising Unit event, with prior CPE Directorate approval, **is** permitted; CSR activity mention is allowed with the "CA" prefix but **not** the firm name/logo.

### KYC Norms (Council-approved)

- **Key rule(s):** Documentation required varies by client type:
  - **Individual/Proprietor** — name, PAN/Aadhaar, business description, last audited FS, type of engagement.
  - **Corporate entity** — name & address, business description, parent company name, last audited FS, PAN, CIN, directors' names/addresses & DIN, type of engagement.
  - **Non-corporate entity** — name & address, PAN, business description, partners' names/addresses (PAN/Aadhaar/DIN), last audited FS, type of engagement.

**Concept:** Minimum client-identification documentation a CAiP must obtain before/at acceptance of an engagement — non-compliance can itself expose the member to disciplinary action under Section 21.

### First Schedule, Part I — Professional Misconduct of a CA in Practice (CAiP)

- **Key rule(s) — Clauses (1)–(12):**

| Clause | Misconduct if the CAiP… |
|---|---|
| (1) | Allows a non-CA (other than a CAiP partner/employee) to practise in his name |
| (2) | Pays/shares fees or profits, directly or indirectly, with anyone other than a member of ICAI, a partner/retired partner/legal representative of a deceased partner, or a member of a prescribed professional body (e.g., CS, CMA, Advocate, Architect, Actuary, Engineer) |
| (3) | Accepts a share of professional profits of a non-member (subject to the same exception as Clause 2) |
| (4) | Enters into a partnership (in/outside India) with anyone other than a CAiP or a member of a prescribed professional body |
| (5) | Secures professional business through a non-employee/non-partner, or by means not open to a CA |
| (6) | Solicits clients/work directly or indirectly by circular, advertisement, personal communication, or interview (subject to exceptions above) |
| (7) | Advertises professional attainments/services, or uses a designation other than "CA" (other than a recognised degree/title) |
| (8) | Accepts a position as auditor previously held by another CA without first communicating with him **in writing** |
| (9) | Accepts appointment as company auditor without first ascertaining that Sections 139 & 140, Companies Act 2013 have been complied with |
| (10) | Charges/accepts fees based on a percentage of profits or contingent on findings/results, except as permitted under Regulation 192 |
| (11) | Engages in any business/occupation other than the CA profession, unless permitted by the Council (a CA may still be a non-MD/non-WTD director of a company where he/his partners are not interested as auditor) |
| (12) | Allows a non-member, or a member who is not his partner, to sign on his/the firm's behalf any Balance Sheet, P&L Account, report, or FS |

$$
\text{Regulation 192 exceptions to Clause (10)}:\; \text{Receiver/liquidator (\% of realisation)},\ \text{Co-op society auditor (\% of capital/income)},\ \text{Direct-tax valuer (\% of value)},\ \text{Mgt consultancy (contingent fee)},\ \text{Fund-raising/debt-recovery/cost-optimisation services (\% of outcome)}
$$

**Concept:** Part I is the core "misconduct while practising" list — most CA Final case studies test one or more of these 12 clauses.

**Pitfalls / exam tips:**
- **Clause (8):** communication must give positive evidence of delivery — Registered Post AD, hand delivery with acknowledgment, acknowledged email to the ICAI-registered/last-known email address, or UDIN. **Certificate of Posting alone is NOT valid evidence.** If premises are found locked, or the firm is not found at its ICAI-registered address (as on the date of dispatch), communication is *deemed* delivered unless the retiring auditor proves otherwise.
- **Clause (9):** the incoming auditor must independently verify Companies Act Sections 139/140 compliance — a management certificate alone is insufficient; if the company won't allow verification, decline the engagement.
- **Clause (10):** the prohibition is against contingent/percentage fees for "professional employment" generally — but Regulation 192 carves out specific engagements (liquidator, cooperative-society auditor, tax valuer, management consultancy, fund-raising, debt recovery, cost optimisation, Insolvency Professional work, and non-assurance services to non-audit clients).
- **Clause (11):** Regulation 190A gives blanket ("general") permission for certain occupations (private tutorship, authorship, LIC agency for renewal commission only, holding elected public office, honorary charitable leadership, Notary Public, part-time ICAI-coaching tutorship, examiner/paper-setter roles, editorship of professional journals, surveyor/loss assessor under Insurance Act 1938, banking recovery consultant, agriculture); other occupations (e.g., employment in a business concern, MD/WTD of a body corporate, full-time lectureship elsewhere) need **specific, prior Council approval** — engaging *before* approval is obtained is misconduct even if approval is later granted.
- A CA cannot be a director of the **holding company** of a company he audits as **subsidiary's auditor** — ESB view: independence would be compromised.

### First Schedule, Parts II, III & IV — Members in Service / Generally / Other Misconduct

- **Key rule(s):**
  - **Part II (members in service), Clause (1):** pays/agrees to pay, directly/indirectly, any share of employment emoluments to another person (sharing with relatives/dependents is fine if *not* consideration for procuring/retaining the job).
  - **Part II, Clause (2):** accepts/agrees to accept a part of fees/profits/gains from a lawyer, CA, or broker engaged by the employer, or from the employer's agent/customer, by way of commission.
  - **Part III (all members), Clause (1):** not being a Fellow, acts as a Fellow.
  - **Part III, Clause (2):** fails to supply information/comply with requirements of ICAI, Council, its Committees, Director (Discipline), Board of Discipline, Disciplinary Committee, Quality Review Board, or Appellate Authority.
  - **Part III, Clause (3):** gives false information while inviting professional work, responding to tenders/enquiries, or advertising under Clauses (6)/(7) of Part I.
  - **Part IV (other misconduct), Clause (1):** held guilty by a civil/criminal court of an offence punishable with imprisonment **≤ 6 months**.
  - **Part IV, Clause (2):** in the Council's opinion, brings disrepute to the profession/Institute — whether or not connected to professional work.

**Concept:** Part II targets members who are employees; Parts III & IV apply to every member (practice or service) and cover non-cooperation with disciplinary bodies, false statements, and conduct (even personal) that brings disrepute.

**Pitfalls / exam tips:**
- Examples of "Other Misconduct" (Part IV/2): retaining a client's books/documents without reasonable cause; misusing articled/audit assistants for non-professional work (e.g., election campaigning); coercive methods to get a personal loan sanctioned; a cheque dishonoured with "Refer to Drawer" **due to insufficiency of funds** (mere dishonour is not automatically misconduct — the *reason* must be insufficiency of funds).
- Imprisonment **> 6 months** for an offence moves the matter from **First Schedule Part IV** to **Second Schedule Part III** (more severe schedule).

### Second Schedule, Part I — Professional Misconduct of a CAiP (Higher-Severity)

- **Key rule(s) — Clauses (1)–(10):**

| Clause | Misconduct if the CAiP… |
|---|---|
| (1) | Discloses information acquired during a professional engagement to anyone other than the client, without the client's consent or a legal requirement |
| (2) | Certifies/submits a report on an examination of FS unless the examination was made by himself, a partner/employee of his firm, or another CAiP |
| (3) | Permits his/the firm's name to be used with an earnings forecast in a way suggesting he vouches for its accuracy |
| (4) | Expresses an opinion on FS of an entity in which he, his firm, or a partner has a **substantial interest** |
| (5) | Fails to disclose a known material fact, non-disclosure of which would make the FS misleading |
| (6) | Fails to report a known material misstatement appearing in the FS |
| (7) | Fails to exercise due diligence, or is grossly negligent, in the conduct of professional duties |
| (8) | Fails to obtain sufficient information necessary for an opinion, or the exceptions taken are sufficiently material to negate the opinion |
| (9) | Fails to invite attention to a material departure from the generally accepted procedure of audit (GAPA — SAs, Guidance Notes, Technical Guides, etc.) |
| (10) | Fails to keep clients' moneys (other than fees due) in a separate bank account, or fails to use such moneys for the intended purpose within a reasonable time |

$$
\text{Substantial interest (Clause 4)} = 20\% \text{ or more shareholding, held by self or specified relative (spouse, sibling, lineal ascendant/descendant)}
$$

**Concept:** The Second Schedule addresses the most serious breaches — confidentiality, independence-destroying financial interest, gross negligence, and misuse of client funds — and carries harsher potential punishment (up to removal of name / higher-forum hearing) than the First Schedule.

**Pitfalls / exam tips:**
- **Clause (4)** independence-breaking examples: a liquidator auditing the same company's FS; a CA auditing an entity where he is employed, a part-time lecturer's college, or a trust where his partner is trustee/employee; a statutory auditor cannot simultaneously be internal auditor of the same entity, and an internal auditor cannot be appointed as tax auditor of the same entity.
- **Clause (7)** examples: stock audit without visiting the site (relying only on management reports); certifying raw-material consumption from BOD minutes alone; sharing a Digital Signature Certificate password with the client; certifying newspaper circulation figures from an MIS report without examining underlying records.
- **Clause (10)**: money received in a fiduciary capacity (advance for expenses to be incurred shortly is excluded) must go into a **separate bank account**; depositing client investment money in the firm's own savings account and not investing it is a textbook Clause (10) violation.

### Second Schedule, Part II & III — Members Generally / Other Misconduct

- **Key rule(s):**
  - **Part II, Clause (1):** contravenes any provision of the Act, Regulations, or Council guidelines.
  - **Part II, Clause (2):** being an employee, discloses confidential information acquired in employment (except when required by law or permitted by the employer).
  - **Part II, Clause (3):** includes false particulars in any information/statement/return/form submitted to ICAI/Council/its committees or disciplinary bodies.
  - **Part II, Clause (4):** defalcates or embezzles money received in a professional capacity (linked to **SA 240** — fraud).
  - **Part III:** held guilty by a civil/criminal court of an offence punishable with imprisonment **> 6 months**.

**Concept:** Mirrors First Schedule Parts II–IV but at the higher-severity Second Schedule level (false ICAI filings, embezzlement, and serious criminal convictions).

**Pitfalls / exam tips:** Distinguish carefully by imprisonment length — **≤ 6 months → First Schedule Part IV(1)**; **> 6 months → Second Schedule Part III** — a frequently tested distinction.

### Council General Guidelines, 2008 — Numeric Ceilings & Compliance Chapters

- **Key rule(s):**

$$
\text{Tax audit ceiling (Ch. VI)}:\; \text{Firm limit} = 60 \times \text{No. of partners (per financial year, u/s 44AB, Income-tax Act 1961)}
$$

- Audits under presumptive taxation (Sections 44AD, 44ADA, 44AE) are **not counted**; HO + branch of the same concern = **1 assignment**; each year's audit is a separate assignment; a part-time practising partner **cannot** accept any tax audit assignment.
- **Ch. VII — Non-payment of undisputed fees:** a CAiP shall not accept a new statutory audit if the undisputed audit fee of the previous auditor (for a Companies Act/other statutory audit) remains unpaid — **except** for a "sick unit."

$$
\text{Sick unit} = \text{Unit registered} \geq 5 \text{ years} \;\text{AND}\; \text{Accumulated losses} \geq \text{Net worth}
$$

- **Ch. VIII — Specified number of audit assignments:** a CAiP shall not hold, at any time, more than the specified number of company audits under Section 141, Companies Act 2013.

$$
\text{Specified no. of company audits (Sec 141(3)(g))} = 20 \text{ companies per person/partner}
$$

⚠️ VERIFY — the source concept-book states **"30 audits per CA in full time practice allowed."** The figure well established in the current CA Final syllabus and under Section 141(3)(g), Companies Act 2013, is **20** companies per person (excluding One Person Companies, dormant companies, small companies, and private companies with paid-up share capital below ₹100 crore) — this guide uses **20** as the correct/verified figure; confirm against the latest Study Material/RTP before quoting the exact number in an exam answer, since I could not complete a live web-verification for this specific figure in this session.

- **Ch. IX — Statutory auditor of PSU/Govt/Listed/large Public Companies:** a CAiP shall not accept the statutory audit of a PSU, Government company, listed company, or other public company with **turnover ≥ ₹50 crore** in a year, if he also accepts other work/assignments from the same entity for a **total remuneration exceeding the statutory audit fee** (audits under other statutes, tax representation, and specified certification work are excluded from this "other work" cap).
- **Ch. X — Indebtedness:** a member/partner/relative shall not accept a company audit while indebted to it, or having given a guarantee/security for a third party's indebtedness to it, beyond statutory limits.

$$
\text{Indebtedness limit} = \text{₹5,00,000} \qquad \text{Guarantee/security limit} = \text{₹1,00,000}
$$

- **Ch. XI:** an incoming auditor shall not accept appointment where the removal of the earlier auditor(s) was unjustified.
- **Ch. XIV — UDIN:** mandatory for all certificates, tax audit reports, and other audit/assurance/attestation functions, to curb false certification by unauthorised persons.
- **Ch. XV — Networking:** a network firm may be a mutual entity, a partnership (max. **20 partners**), an LLP, or a company (per corporate-practice guidelines); a firm may join **only one** network; Non-audit fee ceiling for the statutory-auditor network firm mirrors the standard notification limit, while **other firms of the same network collectively** are capped at **3× the statutory audit fee**.
- **Ch. XVI — Logo:** "CA" letters in blue with an upside-down tricolour tick mark on white background — no change of font/spacing/colour/dimensions; no rotation/tilting/shrinking/distortion; 1-year transition period for existing stationery.
- **Ch. XVII — Corporate form of practice:** a CAiP may be MD/WTD/Manager of a body corporate exclusively engaged in permitted MCS under Sec 2(2)(iv), with no restriction on equity holding; the company must not accept internal audit/bookkeeping from an entity where the practitioner/firm is the statutory auditor, and it is subject to the non-audit fee ceiling and Clauses (6)/(7), Part I, First Schedule.

- **Fee disclosure to ICAI:**

$$
\text{Disclosure trigger} = \text{Gross annual fee from one audit client} > 20\%\ (\text{PIE}) \;\text{or}\; 40\%\ (\text{other entities})\ \text{of total firm fees, for 2 consecutive years}
$$

⚠️ VERIFY — these 20%/40% fee-concentration disclosure percentages are as transcribed from the source material; confirm the exact current percentages and the precise Council Guideline reference against the latest ICAI Study Material, as this could not be cross-checked with a live source in this session. Exemptions: total firm fees ≤ ₹20 lakh; or audits of Government companies/public undertakings/nationalised banks/public financial institutions/regulators where the auditor is Government-appointed.

**Concept:** These are ICAI's own numeric self-regulatory ceilings (distinct from, but often layered on top of, Companies Act 2013 statutory limits) — almost every one of these numbers has appeared in a "guilty/not guilty" MCQ or case study.

**Pitfalls / exam tips:**
- Always distinguish the **statutory** ceiling (Sec 141(3)(g) — company audits; Sec 141(3)(d) — indebtedness/substantial interest) from the **ICAI Council Guideline** ceiling (tax audits, undisputed fees, PSU/turnover-based restriction) — both can apply to the same fact pattern.
- Branch audit / joint audit self-regulatory (non-binding) recommendations: branch audits of a company should not be done by statutory auditors having **10 or more members**, but by smaller local firms (unless the branch's records are kept at HO or the branch has insignificant operations); large companies should practise joint audits using firms with **< 5 members**.
- Recommended staffing ratio: at least **1 qualified member for every 5 non-members** (excluding articled/audit assistants and non-professional staff).

### Ethical Standards Board (ESB) — Recent Decisions (rapid-fire)

- **Key rule(s) / rapid facts:**
  - Statutory auditor **cannot** prepare the BRSR study for an audit client (advisory services on BRSR are allowed); **can** be "Assurance Provider of BRSR Core" for the same client; **cannot** undertake a compilation engagement (SRS 4410) for its own audit client.
  - CAiP **can**: undertake performance audits of Skill Development Centres (as MCS u/s 2(2)(iv)); accept "Mystery Audit" assignments; mention Promoter/Director position on a company's web portal (without professional attainments/firm name); become a professional director on the Board of Management of a Co-operative Bank; set up practice in IFSC/GIFT City and serve IFSC units from offices outside IFSC; act as a Registration Authority for client Digital Signature Certificates; act as a mediator in court; act as settlor of a trust; hold a bank credit card (even as that bank's auditor) provided the outstanding balance beyond the due date does not exceed ₹1 lakh.
  - CAiP **cannot**: simultaneously be Internal Auditor and Procurement Officer of the same organisation; be internal auditor and statutory auditor of the same entity, or vice versa (though a firm may be internal auditor of a company **and** statutory auditor of its EPF — not vice versa); be statutory auditor of a bank and also do its stock/inspection audit for the same FY; be concurrent auditor of Bank X and statutory auditor of Bank Y sponsored by X; be Trademark/Patent Attorney (though routine IPR advisory is permitted); hold a Customs Broker licence; act as a Financial Advisor earning commission from mutual funds/insurance companies/NBFCs; exercise a lien over client documents for non-payment of fees; print a "vision/values" statement on visiting cards (amounts to solicitation).
  - A non-executive director in a company should not let his firm accept statutory audit of that company's joint venture (independence impact); a "Director Simplicitor" (non-executive, board-meeting attendance only, sitting fees only, no day-to-day involvement) is generally permitted even where residence-in-India rules for directors apply.
  - Firm vision/mission statements may go on a firm profile shared **only** in response to a specific client query — not on letterhead/visiting cards/stationery.

**Concept:** ESB decisions are the "latest case law" layer of ethics — they resolve fact patterns not explicitly covered by the Schedules/Guidelines, and are a favourite source of short "is this permitted?" exam questions.

**Pitfalls / exam tips:** These are tested as one-liner "permitted/not permitted" MCQs — learn the *pattern* (independence conflict = not permitted; genuinely separate professional/advisory capacity = generally permitted) rather than memorising every bullet verbatim.

### Disciplinary Mechanism (Sections 21–22G, CA Act 1949) — Overview

- **Key rule(s):**
  - A complaint/information against a member is examined by the **Director (Discipline)**, who forms a *prima facie* opinion and places it before the **Board of Discipline** (for First Schedule/lesser matters) or the **Disciplinary Committee** (for Second Schedule/more serious matters, or a combination of both Schedules).
  - If **not found guilty** → the matter is closed.
  - **Appeal:** may be filed by the member or the Director (Discipline) within **90 days** to the **Appellate Authority**.
  - Appellate Authority's powers: confirm, modify, or set aside the order; remit the case to the Board of Discipline/Disciplinary Committee for reconsideration; impose, set aside, reduce, or enhance the penalty; or pass any other order it thinks fit.

**Concept:** This is the procedural backbone that operationalises the First and Second Schedule misconduct clauses discussed above — a complaint travels: **Director (Discipline) → Board of Discipline / Disciplinary Committee → (if appealed) Appellate Authority.**

**Pitfalls / exam tips:** ⚠️ VERIFY — the source material available for this chapter only summarised the closing stages of the disciplinary flow (finding, appeal, and Appellate Authority orders); the finer jurisdictional split between the Board of Discipline and Disciplinary Committee, and the exact composition/quorum of each, should be cross-checked against the standalone "Disciplinary Mechanism" topic in the Study Material, as it was not fully legible in the source and could not be independently web-verified in this session.

### References

1. ICAI, *Code of Ethics* (as applicable for CA Final 2026 syllabus) — Fundamental Principles, Threats & Safeguards, NOCLAR (Sections 260/360).
2. The Chartered Accountants Act, 1949 — Sections 2(2), 6, 7, 8, 21–22G, 24, 27; First Schedule (Parts I–IV) and Second Schedule (Parts I–III).
3. The Companies Act, 2013 — Sections 139, 140, 141(3) (auditor eligibility/disqualification, including the specified-number-of-audits and indebtedness limits).
4. ICAI, *Council General Guidelines, 2008* (Guidelines No. 1-CA(7)/02/2008, as amended) — Chapters I–XVII (tax-audit ceiling, undisputed-fee restriction, specified number of audit assignments, indebtedness, UDIN, Networking, Logo, Corporate form of practice, self-regulatory measures, fee disclosure).
5. ICAI Ethical Standards Board — published FAQs/recent clarifications on independence and permitted occupations, as summarised in the source concept book (Shubham Keswani Concept Book, Chapter 02).

## 03. CARO 2020 & Company Audit

> **Where it fits:** CARO 2020 is the reporting order under Sec 143(11) that makes an auditor comment on 21 specified matters (Para 3, clauses (i)–(xxi)) for most companies; this chapter also covers the Companies Act, 2013 audit-reporting duties (Sec 143, 144, 145) that sit alongside it in every statutory audit report.

### CARO 2020 – Applicability & Exemptions

- **Key formula(s)/rule(s):**
  - CARO 2020 applies to **every company, including a foreign company**, EXCEPT:
    - Banking company (LFAR applicable instead)
    - Insurance company
    - Sec 8 company (licensed for charitable objects)
    - One Person Company (OPC) and **Small Company**
    - A private company (not being a subsidiary or holding company of a public company) satisfying **all three** of:
$$
\text{Paid-up capital + Reserves \& Surplus} \le \text{₹1 crore (on Balance Sheet date)}
$$
$$
\text{Borrowings from any bank or FI} \le \text{₹1 crore (at any point during the FY)}
$$
$$
\text{Revenue (as per Sch III, incl. discontinued ops)} \le \text{₹10 crore (as per FS)}
$$
  - CARO is **not applicable to Consolidated Financial Statements (CFS)**, except that the auditor must still report under **clause (xxi)** in the CFS auditor's report.

- **Concept:** CARO is a Sec 143(11)-mandated order requiring auditors to answer specific yes/no + detail questions in their report; the exemptions target very small / regulated / non-profit entities where such reporting adds little value.

- **Pitfalls / exam tips:**
  - All three private-company conditions must be satisfied simultaneously — failing even one makes CARO applicable.
  - Test the private-company exemption on a **standalone** basis; a subsidiary/holding relationship with a public company disqualifies the exemption regardless of size.
  - Remember clause (xxi) is the lone survivor of CARO reporting in a CFS context.

### Small Company (Sec 2(85))

- **Key formula(s)/rule(s):**
  - A company (other than a public company) is "small" if:
$$
\text{Paid-up share capital} \le \text{₹4 crore}
$$
$$
\text{Turnover (as per preceding FY's P\&L)} \le \text{₹40 crore}
$$
  - Exceptions (never "small" regardless of size): holding company, subsidiary company, Sec 8 company, and a company/body corporate governed by a special Act.
  - A small company is exempt from CARO even if it does **not** independently meet the private-company (₹1cr/₹1cr/₹10cr) exemption criteria.

- **Concept:** "Small company" is a size-based relaxation category under the Companies Act, 2013 that eases compliance burden (board meetings, cash flow statement, rotation, etc.), and CARO piggybacks on this definition as a direct exemption.

- **Pitfalls / exam tips:**
  - Both limits (capital AND turnover) must be met — it is an "and" test, not "or".
  - Note the current thresholds reflect the 2022 amendment (raised from ₹2cr/₹20cr) — always apply the figure applicable for the year under audit.

### Clause (i) – PPE, Intangibles, Title Deeds, Revaluation, Benami Property

- **Key formula(s)/rule(s):**
  - Whether the company maintains proper records (with full quantitative & location particulars) of (A) Property, Plant & Equipment and (B) Intangible assets.
  - Whether PPE physically verified by management at reasonable intervals; discrepancies (if any) properly dealt with in books.
  - Title deeds of all immovable property (other than those held as lessee, with agreements executed in the lessee's favour) must be held in the company's own name — if not, tabulate: Description, Gross carrying value, Held in name of, Whether promoter/director/relative/employee, Period held, Reason for not being in company's name.
  - Revaluation of PPE (including Right-of-Use assets) or intangibles: report if done by a **Registered Valuer**, and specify the amount of change if the change is **10% or more** in the aggregate net carrying value of any class of PPE/intangibles.
  - Report on any proceedings initiated/pending against the company for holding **benami property** under the Prohibition of Benami Property Transactions Act, 1988, and whether disclosed in FS.

- **Concept:** This clause tests asset-record integrity, title ownership evidence, and revaluation/benami disclosures — a common area of financial statement misstatement.

- **Pitfalls / exam tips:**
  - The 10% materiality trigger applies to revaluation reporting, not to the title-deeds disclosure (which is required irrespective of amount, if title isn't in the company's name).
  - "Lessee" exception for title deeds is frequently tested — leased property held under a duly executed lease agreement is NOT to be reported even if not in company's name.

### Clause (ii) – Inventory & Working Capital

- **Key formula(s)/rule(s):**
  - Whether physical verification of inventory conducted at reasonable intervals, and whether coverage/procedure adopted by management is appropriate; discrepancies of **10% or more** in aggregate for any class of inventory must be reported along with treatment in books.
  - Whether the company was sanctioned **working capital limits in excess of ₹5 crore, in aggregate**, from banks/FIs on the basis of security of current assets — and whether quarterly returns/statements filed with such lenders agree with the books of account (details required if not in agreement).

- **Concept:** Confirms existence/valuation controls over inventory and cross-checks that stock/debtor statements given to lenders for working-capital facilities match the books.

- **Pitfalls / exam tips:**
  - The ₹5 crore threshold is tested "in aggregate" — sum sanctioned limits across all banks/FIs, not per lender.
  - 10% materiality is per class of inventory, not overall inventory value.

### Clause (iii) & (iv) – Loans, Investments, Guarantees, Securities (LIGS) and Sec 185/186

- **Key formula(s)/rule(s):**
  - Reportable if the company, during the year, made investments in, or provided guarantee/security, or granted loans/advances in the nature of loans (secured/unsecured) to companies, firms, LLPs or other parties [exemption: companies whose principal business is to give loans]. Report separately:
    - (A) Aggregate amount during the year & balance outstanding at BS date — to **subsidiaries, joint ventures & associates**
    - (B) Same — to **parties other than** subsidiaries, joint ventures & associates
  - Whether terms are prejudicial to the company's interest; whether repayment/interest schedule stipulated and repayments regular.
  - If overdue, state total amount overdue for **more than 90 days** and whether reasonable steps taken for recovery.
  - Whether loans renewed/extended, or fresh loans granted to settle existing loans to the same parties (evergreening) — report aggregate amount and % of aggregate to total loans granted during the year.
  - Whether loans/advances granted repayable on demand or without specifying any repayment terms/period — report aggregate amount, % of total loans granted, and amount granted to **Promoters and related parties** (as defined u/s 2(76)).
  - Clause (iv): whether Sec 185 (loans to directors) and Sec 186 (loans/investments by company) have been complied with — if not, give details.

- **Concept:** Tests both the commercial prudence of intercompany/related-party lending and statutory compliance with the loans-to-directors and inter-corporate investment provisions.

- **Pitfalls / exam tips:**
  - The 90-day overdue test and the evergreening test are distinct sub-clauses — don't conflate them.
  - "Repayable on demand" loans to promoters/related parties is a frequently examined red flag.

### Clause (v) – Deposits

- **Key formula(s)/rule(s):**
  - In respect of deposits accepted (or amounts deemed to be deposits), report whether directives issued by RBI and **Sec 73 to 76** (or other applicable provisions/rules of the Companies Act) have been complied with.
  - If not complied, state the nature of contravention.
  - If an order has been passed by the CLB/NCLT/RBI/any court/tribunal, whether it has been complied with.

- **Concept:** Verifies compliance with the statutory deposit-acceptance framework, which protects depositors from unregulated fund mobilisation.

- **Pitfalls / exam tips:** "Amounts deemed to be deposits" is wider than actual deposits — includes advances, loans from directors/shareholders not meeting exemption conditions under the Deposit Rules.

### Clause (vi) – Cost Records

- **Key formula(s)/rule(s):** Whether maintenance of cost records has been specified by the Central Government under **Sec 148(1)** of the Companies Act, and whether such accounts and records have been so made and maintained.

- **Concept:** A threshold check — applicable only where the CG has notified the company's class/product under the Companies (Cost Records and Audit) Rules.

- **Pitfalls / exam tips:** Auditor is not expected to conduct a detailed examination of cost records — only to comment on whether they are maintained.

### Clause (vii) – Statutory Dues

- **Key formula(s)/rule(s):**
  - (a) Whether the company is regular in depositing undisputed statutory dues (GST, PF, ESI, income-tax, sales-tax, service tax, customs duty, excise duty, VAT, cess, and other statutory dues) with appropriate authorities; if not, state the extent of arrears **outstanding for a period of more than 6 months** from the date they became payable, as on the last day of the financial year.
  - (b) Where statutory dues are not deposited on account of a dispute, state the amount involved and the forum where the dispute is pending (a mere representation to the department is NOT treated as a dispute).

- **Concept:** Flags chronic non-payment of statutory dues (going-concern/penalty risk indicator) separately from genuine, forum-pending disputes.

- **Pitfalls / exam tips:** The 6-month test applies only to undisputed dues; disputed dues are reported irrespective of the amount or duration, with the forum name mandatory.

### Clause (viii) – Undisclosed Income

- **Key formula(s)/rule(s):** Whether any transactions not recorded in the books of account have been surrendered or disclosed as income during the year in tax assessments under the Income-tax Act, 1961; if so, whether previously unrecorded income has been properly recorded in the books during the year.

- **Concept:** Tests whether income disclosed to tax authorities (e.g., in search/survey assessments) has also found its way correctly into the statutory books.

- **Pitfalls / exam tips:** Focus is on the accounting treatment of the surrendered income, not on the tax assessment outcome itself.

### Clause (ix) – Repayment of Loans / Borrowings

- **Key formula(s)/rule(s):**
  - Whether the company has defaulted in repayment of loans/borrowings or interest to any lender; report period and amount of default in the format: Nature of borrowing (incl. debt securities) | Name of lender | Amount not paid on due date | Principal or interest | No. of days delay/unpaid | Remarks (lender-wise details required for banks, FIs and Government).
  - Whether the company has been declared a **wilful defaulter** by any bank/FI/lender.
  - Whether term loans were applied for the purpose for which they were obtained; if diverted, state amount and purpose of actual use.
  - Whether funds raised on a short-term basis were utilised for long-term purposes.
  - Whether the company took funds from any entity/person to meet obligations of its subsidiaries/associates/joint ventures — give details.
  - Whether the company raised loans during the year on the pledge of securities held in its subsidiaries/JV/associate companies, and whether it defaulted on such loans.

- **Concept:** A comprehensive default and fund-diversion check spanning borrowings, term loans, short-term/long-term mismatch, and pledge of group-company securities.

- **Pitfalls / exam tips:** Lender-wise details are mandatory only for defaults to banks, FIs and Government — not necessarily for every private lender.

### Clause (x) – IPO/FPO and Preferential Allotment

- **Key formula(s)/rule(s):**
  - (a) Whether money raised by IPO/FPO (including debt instruments) during the year was applied for the purposes for which it was raised; if not, report details with delays/default and subsequent rectification.
  - (b) Whether the company made any preferential allotment or private placement of shares/convertible debentures during the year; if so, whether requirements of **Sec 42 and Sec 62** of the Companies Act, 2013 have been complied with, and whether funds raised were used for the stated purposes; if not, give details of amount involved and nature of non-compliance.

- **Concept:** Verifies end-use of capital-market/private-placement funds matches the stated objects in the offer document/resolution.

- **Pitfalls / exam tips:** Sec 42 governs private placement procedure; Sec 62 governs further issue of share capital (rights/preferential) — both must be checked for preferential allotments.

### Clause (xi) – Fraud Reporting (CARO)

- **Key formula(s)/rule(s):**
  - Whether any fraud **by** the company or **on** the company has been noticed or reported during the year; if yes, state the nature and amount involved.
  - Whether a report under **Sec 143(12)** has been filed by the auditors in **Form ADT-4** as prescribed under **Rule 13 of the Companies (Audit and Auditors) Rules, 2014** with the Central Government.
  - Whether the auditor has considered whistle-blower complaints, if any, received during the year.

- **Concept:** CARO clause (xi) is the disclosure counterpart to the substantive fraud-reporting duty under Sec 143(12) (covered later in this chapter) — every fraud noticed must be reported here regardless of amount, even if the ₹1 crore CG-reporting threshold under Sec 143(12) is not crossed.

- **Pitfalls / exam tips:** A classic exam trap: fraud below ₹1 crore still requires CARO clause (xi) disclosure and Board/Audit-Committee reporting — only the CG (ADT-4) reporting is skipped.

### Clause (xii) – Nidhi Company

- **Key formula(s)/rule(s):**
  - Whether the Nidhi company has complied with the **Net Owned Funds (NOF) to Deposits ratio of 1:20** to meet its liability.
  - Whether the Nidhi company is maintaining **10% unencumbered term deposits** to meet its liability.
  - Whether there has been any default in payment of interest on deposits or repayment thereof, and if so, the period and details.

- **Concept:** Nidhi companies mobilise deposits only from members; these are prudential ratios under the Nidhi Rules, 2014 that the auditor must specifically confirm.

- **Pitfalls / exam tips:** Remember it's a ceiling (NOF : Deposits **not to exceed** 1:20) and a floor (unencumbered term deposits **at least** 10% of deposits) — don't invert the two tests.

### Clause (xiii) – Related Party Transactions

- **Key formula(s)/rule(s):** Whether all transactions with related parties are in compliance with **Sec 177** (Audit Committee approval) and **Sec 188** (Board/shareholder approval for specified RPTs) of the Companies Act, where applicable, and whether details have been disclosed in the FS as required by applicable Accounting Standards.

- **Concept:** Cross-checks statutory approval trail (Sec 177/188) against AS 18 / Ind AS 24 related-party disclosures in the financial statements.

- **Pitfalls / exam tips:** Sec 177 (Audit Committee) applies to listed and prescribed classes of companies; Sec 188 applies more broadly to specified contracts/arrangements with related parties — test both, not just one.

### Clause (xiv) – Internal Audit

- **Key formula(s)/rule(s):**
  - Whether the company has an internal audit system **commensurate with the size and nature of its business**.
  - Whether reports of the Internal Auditors for the period under audit were considered by the statutory auditor.

- **Concept:** Statutory auditor must specifically evaluate adequacy of internal audit function and factor internal audit reports into the statutory audit approach.

- **Pitfalls / exam tips:** "Commensurate with size and nature" is a qualitative/professional-judgement test — no numeric threshold to memorise here.

### Clause (xv) – Non-Cash Transactions with Directors

- **Key formula(s)/rule(s):** Whether the company has entered into any non-cash transactions with directors or persons connected with them, and if so, whether the provisions of **Sec 192** of the Companies Act have been complied with.

- **Concept:** Sec 192 requires prior members' approval (by resolution) for arrangements where a director/connected person acquires assets from, or the company acquires assets from such a person, for non-cash consideration.

- **Pitfalls / exam tips:** Applies to arrangements involving assets, not routine cash remuneration/expense reimbursements.

### Clause (xvi) – RBI Registration / NBFC / CIC

- **Key formula(s)/rule(s):**
  - (a) Whether the company is required to be registered u/s **45-IA of the RBI Act, 1934**, and if so, whether such registration has been obtained.
  - (b) Whether the company conducted Non-Banking Financial or Housing Finance activities without a Certificate of Registration from RBI.
  - (c) Whether the company is a **Core Investment Company (CIC)** as defined in RBI regulations, and if so, whether it continues to fulfil the criteria of a CIC (including for exempted/unregistered CICs).
  - (d) Whether the Group has more than one CIC as part of the Group, and if so, indicate the number of CICs in the Group.

- **Concept:** Tests whether the entity is carrying on regulated NBFC/HFC/CIC business without the mandatory RBI registration/exemption compliance.

- **Pitfalls / exam tips:** ⚠️ VERIFY — the OCR source does not state the numeric CIC qualifying criteria (asset size / investment pattern thresholds under RBI's CIC Master Directions); do not assume a figure — confirm against the current RBI Master Direction – Core Investment Companies before quoting any number in an answer.

### Clause (xvii) – Cash Losses

- **Key formula(s)/rule(s):** Whether the company has incurred cash losses in the financial year and in the **immediately preceding financial year**; if so, state the amount of cash losses (a cash loss in even one of the two years must be disclosed).

- **Concept:** "Cash loss" = reported loss adjusted for non-cash items (e.g., depreciation) — a leading indicator relevant to the going-concern clause (xix) that follows.

- **Pitfalls / exam tips:** Both years must be checked — a cash profit in the current year does not exempt reporting if the preceding year had a cash loss.

### Clause (xviii) – Resignation by Statutory Auditors

- **Key formula(s)/rule(s):** Whether there has been any resignation of the statutory auditors during the year; if so, whether the incoming auditor has taken into consideration the issues, objections or concerns raised by the outgoing auditor.

- **Concept:** Ensures continuity of audit concerns is not lost on auditor turnover — the successor auditor must specifically evidence consideration of the predecessor's concerns.

- **Pitfalls / exam tips:** Applies whenever a resignation occurred in the year, even if the successor auditor is unrelated to the reasons for resignation.

### Clause (xix) – Going Concern

- **Key formula(s)/rule(s):** Based on: (a) financial ratios, (b) ageing and expected dates of realisation of financial assets and payment of financial liabilities, (c) other information accompanying the FS, and (d) auditor's knowledge of the Board of Directors' and management's plans — whether the auditor is of the opinion that no material uncertainty exists as on the date of the audit report that the company is capable of meeting its liabilities existing at the balance sheet date, as and when they fall due **within a period of one year from the balance sheet date**.

- **Concept:** A forward-looking, evidence-based conclusion distinct from (and feeding into) any going-concern qualification under SA 570.

- **Pitfalls / exam tips:** The look-forward period is exactly **one year from the balance sheet date**, not from the audit report date — a commonly confused distinction with SA 570's own assessment period.

### Clause (xx) – CSR Unspent Amount

- **Key formula(s)/rule(s):**
  - For other than ongoing projects: whether the company transferred the unspent CSR amount to a Fund specified in **Schedule VII** within **6 months of the expiry of the financial year**, in compliance with the second proviso to **Sec 135(5)**.
  - For ongoing projects: whether any amount remaining unspent u/s **135(5)**, pursuant to an ongoing project, has been transferred to the special **Unspent CSR Account** in compliance with **Sec 135(6)**.

- **Concept:** Distinguishes the two unspent-CSR treatments: non-ongoing project shortfalls go straight to a Schedule VII fund; ongoing-project shortfalls are ring-fenced in a special bank account for utilisation over the project period.

- **Pitfalls / exam tips:** ⚠️ VERIFY — the OCR does not carry the further sub-timelines under Sec 135(6) (e.g., the requirement to spend the Unspent CSR Account balance within 3 financial years, failing which transfer to a Schedule VII fund within 30 days of expiry of the third year); confirm the exact day-counts against Sec 135(6) before citing them.

### Clause (xxi) – Qualifications in CFS

- **Key formula(s)/rule(s):** Whether there have been any qualifications or adverse remarks by the respective auditors in the CARO reports of companies included in the Consolidated Financial Statements; if yes, indicate the details of the companies and the paragraph numbers of the CARO reports containing such qualifications/adverse remarks.

- **Concept:** This is the sole CARO clause reproduced in the CFS auditor's report (per the exception noted under Applicability above).

- **Pitfalls / exam tips:** The CFS auditor need not re-audit each component but must aggregate/reference CARO qualifications already reported by component auditors.

### Company Audit – Sec 143(1) Duty to Enquire

- **Key formula(s)/rule(s):** Under Sec 143(1), the auditor must enquire (though not necessarily report unless there is an adverse finding) whether:
  - Loans/advances made on the basis of security have been properly secured, and whether the terms are prejudicial to the interests of the company or its members.
  - Transactions represented merely by book entries are prejudicial to the interests of the company.
  - Where the company is not an investment/banking company, whether its assets consisting of shares, debentures and other securities have been sold at a price less than the purchase price.
  - Loans and advances made by the company have been shown as deposits.
  - Personal expenses have been charged to the revenue account.
  - Where shares have been allotted for cash, whether cash has actually been received, and if not, whether the position as stated in the books and the Balance Sheet is correct, regular and not misleading.

- **Concept:** A statutory checklist of "duty to enquire" matters — the auditor must specifically make these enquiries during the audit, and reports on them only if the answer is unfavourable (Sec 143(1) is a negative-reporting provision, unlike CARO's positive reporting).

- **Pitfalls / exam tips:** The OCR source lists only 5 of the 6 standard Sec 143(1) matters (the shares-allotted-for-cash-consideration point is the commonly omitted sixth) — always recall all six in the exam.

### Rule 11 CAAR 2014 – Other Matters in Auditor's Report

- **Key formula(s)/rule(s):** Under Rule 11 of the Companies (Audit and Auditors) Rules, 2014, the auditor's report must additionally state:
  - (a) Whether the company has disclosed the impact of pending litigations on its financial position in its financial statements.
  - (b) Whether the company has made provision, as required under any law or accounting standards, for material foreseeable losses on long-term contracts including derivative contracts.
  - (c) Whether there has been any delay in transferring amounts to the **Investor Education and Protection Fund (IEPF)**.
  - (d)(i) Whether management has represented that no funds have been advanced/loaned/invested by the company in any person/entity (including foreign entities), with the understanding that the intermediary shall lend/invest/provide guarantee or security on behalf of the company to/in an "Ultimate Beneficiary".
  - (d)(ii) Whether management has represented that no funds have been received by the company from any person/entity (including foreign "Funding Parties"), with the understanding that the company shall lend/invest in another entity or provide guarantee/security on behalf of the Funding Party.
  - (d)(iii) Whether the auditor has found any material misstatement in the above representations.
  - (e) Whether dividend declared/paid is in compliance with **Sec 123**.
  - (f) Whether the company has used accounting software with an **audit trail (edit log) feature** that was operated throughout the year for all transactions, and whether the audit trail has not been tampered with and has been preserved as per statutory retention requirements.

- **Concept:** Rule 11 supplements the auditor's opinion with pointed disclosures on litigation, long-term contract losses, IEPF compliance, "layering"/money-laundering type fund flows, dividend legality, and (from FY 2023-24) the mandatory accounting-software audit-trail feature.

- **Pitfalls / exam tips:** The audit-trail requirement [clause (f)] and the "Ultimate Beneficiary"/"Funding Party" reporting [clause (d)] are the more recently introduced clauses and are exam favourites for current-syllabus attempts.

### Sec 145 – Duty to Sign Audit Report

- **Key formula(s)/rule(s):**
  - Where the auditor is a firm (including an LLP), only the **partners who are practising Chartered Accountants** can act and sign on behalf of the firm.
  - Qualifications, observations or comments on financial transactions that have an adverse effect on the functioning of the company must be **read before the company in general meeting** and shall be open for inspection by any member of the company.

- **Concept:** Fixes accountability for the signature (only a CA-partner, never a non-CA partner in an LLP structure) and mandates transparency of adverse remarks to members.

- **Pitfalls / exam tips:** A non-CA designated partner of an audit LLP cannot sign the audit report even though he is a partner of the firm.

### Sec 143(12) – Fraud Reporting to the Central Government (with Rule 13, CAAR 2014)

- **Key formula(s)/rule(s):**
  - If the auditor has reason to believe that an offence of fraud involving an amount of **₹1 crore or above** has been committed in/against the company by its officers or employees, the auditor must report it to the **Central Government (CG)**.
  - Manner of reporting (Rule 13):
    1. Report the matter to the Board or Audit Committee, immediately but **not later than 2 days** of knowledge, seeking their reply/observations **within 45 days**.
    2. On receipt of the reply/observations, forward the report along with the reply and his comments to the CG **within 15 days of receipt** of such reply.
    3. If no reply is received within the 45 days, forward the report to the CG without waiting for the reply, along with a note that no reply/observation was received, within 15 days of expiry of the 45-day period.
    4. Sent to the Secretary, MCA, in a **sealed cover by Registered Post with Acknowledgement Due (RPAD)** or by Speed Post, **followed by an e-mail**.
    5. Report format: **Form ADT-4**.
  - If the fraud amount is **below ₹1 crore**: report to the Audit Committee or Board within **2 days**, specifying the nature of fraud, amount involved, and parties involved — no CG reporting required.
  - Disclosure in Board's Report (for frauds below ₹1 crore): nature of fraud, amount, parties involved — required only if remedial action has not been taken.
  - **Sec 143(13)** gives the auditor a safeguard: no liability by way of breach of confidentiality for a fraud reported in good faith.
  - The fraud-reporting requirement applies equally to the **Cost Auditor and Secretarial Auditor**.
  - Penalty for non-compliance by the auditor (Sec 143(15)):
$$
\text{Listed company} \Rightarrow \text{Penalty of ₹5,00,000}
$$
$$
\text{Any other company} \Rightarrow \text{Penalty of ₹1,00,000}
$$
  - Cross-reference: CARO 2020 clause (xi) also requires reporting whether an ADT-4/Sec 143(12) report was filed — a fraud below ₹1 crore must still be disclosed under clause (xi) even though CG reporting/ADT-4 is not triggered.

- **Concept:** A graded, amount-based fraud-escalation mechanism: below ₹1 crore stays internal (Board/AC + Board's Report); ₹1 crore and above goes external to the CG via a strict, time-bound, dual-channel (post + e-mail) process.

- **Pitfalls / exam tips:**
  - Common numeric trap: 2 days (to Board/AC) → 45 days (for reply) → 15 days (to forward to CG after receipt of reply, or after expiry of 45 days if no reply) — sequence these correctly in application-type answers.
  - Illustration to remember: a senior manager entering fake purchase invoices worth ₹95 lakh (i.e., below ₹1 crore) still requires reporting to the Board/Audit Committee within 2 days and disclosure in the Board's Report, and CARO clause (xi) reporting — but NOT a report to the CG in Form ADT-4.

- **Definitions:**

| Term | Meaning |
|---|---|
| AC | Audit Committee |
| RPAD | Registered Post with Acknowledgement Due |
| ADT-4 | Prescribed e-form for reporting fraud (₹1 crore or above) to the Central Government under Sec 143(12) |

### Sec 144 – Prohibited Non-Audit Services

- **Key formula(s)/rule(s):** An auditor of a company shall not, directly or indirectly, render the following services to the company, its holding company, or subsidiary company:
  1. Accounting and book-keeping services
  2. Internal audit
  3. Design and implementation of any financial information system
  4. Actuarial services
  5. Investment advisory services
  6. Investment banking services
  7. Rendering of outsourced financial services
  8. Management services
  9. Any other kind of services as may be prescribed

- **Concept:** Preserves auditor independence by barring services that would place the auditor in a self-review or management-role conflict with the audit client group.

- **Pitfalls / exam tips:** The prohibition extends beyond the audit client itself to its **holding company and subsidiary company** — a common trap in MCQs that test only the direct client relationship.

### References

1. CARO 2020 (Companies (Auditor's Report) Order, 2020) — Ministry of Corporate Affairs, Order dated 25 February 2020, Para 2 (Applicability) and Para 3, clauses (i)–(xxi).
2. Companies Act, 2013 — Sec 2(85) (Small Company, as amended by the Companies (Specification of Definitions Details) Amendment Rules, 2022), Sec 135(5)/(6) (CSR), Sec 143(1)/(11)/(12)/(13)/(15), Sec 144, Sec 145, Sec 148(1), Sec 177, Sec 185, Sec 186, Sec 188, Sec 192.
3. Companies (Audit and Auditors) Rules, 2014 — Rule 11 (Other matters in the auditor's report) and Rule 13 (Manner of reporting fraud, Sec 143(12)), including the audit-trail amendment applicable from FY 2023-24.
4. Nidhi Rules, 2014 — Net Owned Funds to Deposits ratio and unencumbered term deposit requirements applicable to Nidhi companies under CARO clause (xii).

*(Note: this session's live web-verification budget was exhausted before the dedicated CARO/Companies Act searches could run; the figures above rest on the faculty source cross-checked against the reviewer's standing domain knowledge of CARO 2020, the Companies Act, 2013 and CAAR 2014 as in force for the 2026 CA Final syllabus. The two items explicitly marked ⚠️ VERIFY — RBI CIC qualifying criteria and the Sec 135(6) sub-timelines — could not be numerically confirmed from the OCR and should be cross-checked by the student against the current RBI Master Direction and Sec 135(6) text respectively before exam use.)*

## 04. Audit Planning, Risk Assessment & Internal Control
> **Where it fits:** Bridges the pre-engagement chapters (SA 200 objectives, engagement acceptance) to the execution chapters — SA 300 tells the auditor *how* to plan, SA 315/330 tell him *how* to identify and respond to risk, and understanding Internal Control is the foundation on which the entire risk-based audit (RBA) strategy is built.

### 1. Audit Planning — Nature, Benefits & Continuous Process (SA 300)
- **Key formula(s)/rule(s):**
  - Planning is **not a discrete phase** — it is a continual and iterative process that begins after (or in connection with) the completion of the previous audit and continues until the completion of the current audit engagement.
  - Nature and extent of planning varies with: (i) size & complexity of the entity, (ii) prior experience with the entity ("past experience of engagement team"), and (iii) change in circumstances during the engagement.
- **Concept:** Good planning helps the auditor devote appropriate attention to important areas, identify and resolve potential problems timely, organise and manage the engagement properly, assist in selection of engagement team members and direction/supervision, and coordinate work of component auditors and experts.
- **Pitfalls / exam tips:**
  - A very common exam trap: students say planning "ends" once the audit strategy/plan is finalised — SA 300 explicitly treats it as continuing till the audit is complete.
  - Reasons requiring **revision** of planned NTE (Nature, Timing, Extent) of Further Audit Procedures: unexpected events, changes in conditions, or audit evidence obtained from performed procedures (e.g., substantive procedure results contradicting Test of Controls results).

### 2. Overall Audit Strategy vs. Audit Plan (SA 300)
- **Key formula(s)/rule(s):**
  - Sequence: **Overall Audit Strategy → Overall Audit Plan → Audit Programme.**
  - The Audit Plan is **more detailed** than the strategy — it converts the strategy into a specific plan of the nature, timing and extent (NTE) of RAP (Risk Assessment Procedures under SA 315) and FAP (Further Audit Procedures under SA 330).
  - They are **inter-related**: a change in one (e.g., materiality lowered due to IC weaknesses) necessitates a corresponding change in the other.
- **Concept:** The strategy sets the scope, timing and direction of the audit and guides the development of the more detailed plan.
- **Pitfalls / exam tips:**
  - Memory peg for the case-study logic: **High Control Risk → Lower Materiality → Increased Testing → Strategy Modified → Plan Revised.**
  - Factors in establishing the overall audit strategy (mnemonic "SDR" style): (a) characteristics of the engagement defining its **S**cope, (b) reporting objectives to plan timing & communications, (c) factors significant in **D**irecting engagement team's efforts, (d) results of preliminary engagement activities/prior knowledge, (e) nature, timing & extent of **R**esources.
- **Definitions:**

| Term | Meaning |
|---|---|
| Overall Audit Strategy | Sets the scope, timing & direction of the audit; guides development of the audit plan |
| Audit Plan | More detailed than the strategy; converts strategy into specific planned NTE of RAP & FAP |
| Audit Programme | Detailed list of audit procedures & instructions allocated to team members to execute the plan |

### 3. Documenting the Plan & Developing the Audit Programme
- **Key formula(s)/rule(s):**
  - Documentation required: (a) the **overall audit strategy** — record of key decisions; (b) the **audit plan** — record of NTE of RAP and FAP at the assertion level; (c) any **significant changes** made during the audit to the strategy/plan and the reasons for such changes.
  - Audit programme is developed in **3 stages**: (1) broad outline drawn up; (2) filled in with details of IC deficiencies as internal control is reviewed; (3) special procedures (e.g., first-year/opening balance checks, independent confirmation of debtors/creditors, physical verification of fixed assets) determined after detailed checking.
- **Concept:** The audit programme allocates work to team members with a step-by-step list of procedures — it operationalises the audit plan.
- **Pitfalls / exam tips:**
  - Circumstances requiring **alteration of the Audit Programme** [Nov'23 exam point]: substantial increase in turnover/volume beyond what the programme was designed for; extraordinary increase in book debts or stock vs. previous year; significant changes in accounting organisation/procedures/personnel; IC found less effective than assumed when the programme was framed; suspicion/information of asset misappropriation.
  - Key phases of audit execution: **Execution Planning → Risk & Control Evaluation → Testing → Reporting (per SA 700)**.

### 4. Materiality and Audit Risk — Interplay (SA 320, SA 450, SA 200)
- **Key formula(s)/rule(s):**
  - Materiality (SA 320) is applied both in **planning and performing** the audit and in **evaluating the effect of**: (i) identified misstatements on the audit, and (ii) uncorrected misstatements on the financial statements and on the auditor's opinion (per **SA 450**).
  - Materiality and audit risk are considered throughout the audit: while identifying/assessing RoMM (Risk of Material Misstatement), while determining NTE of Further Audit Procedures, and while evaluating the effect of uncorrected misstatements on the FS/opinion.
- **Concept:** Materiality and audit risk are inversely and jointly used to calibrate how much evidence is enough — lower materiality or higher assessed risk both drive more extensive procedures.
- **Pitfalls / exam tips:** Do not confuse SA 320 (materiality in planning/performing) with SA 450 (evaluating misstatements identified during the audit) — examiners frequently test the correct SA number.

### 5. The Audit Risk Model — Inherent, Control & Detection Risk (SA 200)
- **Key formula(s)/rule(s):**

$$
\text{Audit Risk (AR)} = \text{Risk of Material Misstatement (RoMM)} \times \text{Detection Risk (DR)}
$$

$$
\text{RoMM (at assertion level)} = \text{Inherent Risk (IR)} \times \text{Control Risk (CR)}
$$

$$
\therefore \; \text{Audit Risk} = \text{IR} \times \text{CR} \times \text{DR}
$$

  - **Detection Risk varies inversely with RoMM**: the higher the assessed RoMM, the lower the detection risk the auditor must accept (by doing more/better substantive work) to hold audit risk at an acceptably low level.
- **Concept:**
  - **Inherent Risk** — susceptibility of an assertion to a misstatement that could be material, *before* considering any related controls; assessed at both the FS level and the assertion level (arises from entity size, complexity, operations, objectives, regulatory environment).
  - **Control Risk** — the risk that the entity's internal control system will not prevent, or detect and correct, a material misstatement on a timely basis; some control risk always exists due to the *inherent limitations of IC*.
  - **Detection Risk** — the risk that the auditor's own procedures will not detect a misstatement that exists; arises from selecting an inappropriate procedure, misapplying an appropriate procedure, or misinterpreting results.
- **Pitfalls / exam tips:**
  - IR and CR exist **independently of the audit** — the auditor cannot change them, only *assess* them; DR is the only risk component the auditor can control by varying the NTE of substantive procedures.
  - RoMM at the **FS level** relates pervasively to many assertions (e.g., an incompetent finance team causing errors across completeness, accuracy, existence, valuation together); RoMM at the **assertion level** is specific (e.g., valuation risk high for inventory subject to obsolescence but low for receivables).
  - Risks of particular concern indicating high inherent risk: lack of working capital to continue operations, complex calculations, high-value inventory, accounting estimates with high measurement uncertainty, a declining industry with business failures.

### 6. Risk Identification, Assessment & Indicators of Misstatement (SA 315)
- **Key formula(s)/rule(s):** Steps for risk identification/assessment: (1) determine likelihood of the risk occurring and its impact on audit procedures; (2) document assertions affected — **Completeness, Existence/Occurrence, Accuracy, Valuation, Rights & Obligations, Presentation & Disclosure**; (3) identify "significant risks" needing separate auditor attention and response; (4) consider existing internal controls and their effectiveness in mitigating the risk; (5) assess significance of the risk and revise materiality for the specific account balance if warranted.
- **Concept:** SA 315 requires the auditor to identify and assess RoMM at both the FS level and the assertion level for classes of transactions, account balances and disclosures, through understanding the entity and its environment, including its internal control.
- **Pitfalls / exam tips:** Indicators of possible misstatement by assertion — Completeness (transaction not identified/source document not captured); Existence (fictitious/unauthorised transactions, duplicate/overstated source documents); Accuracy (errors in capturing/processing/adjustments in subsidiary ledger); Cut-off (transactions recorded in wrong period).
  - Applied illustration [MTP May'23]: ~40% of purchases made without valid POs, some POs raised after actual purchase, no reconciliation of goods received vs. goods ordered → assertion affected is **Validity/Occurrence** of purchases; balances affected are **Purchases and Accounts Payable**. Recommended procedures: review vendor correspondence & purchase requisitions, vendor ageing/reconciliation review, follow-up of early payments, inquiry with purchase officer, discuss exceptions with client.

### 7. Risk-Based Audit (RBA) Approach
- **Key formula(s)/rule(s):** RBA has **3 broad steps**: (1) Assess the RoMM in the financial statements; (2) Design and perform Further Audit Procedures that respond to the assessed risks and reduce audit risk to an acceptably low level; (3) Issue the audit report based on the audit findings.
- **Concept:** RBA allocates a *larger portion of audit resources/effort to high-risk areas*, rather than spreading effort evenly, making the audit efficient and effective.
- **Pitfalls / exam tips:** Matters to consider in the "risk response" phase when planning further procedures: assertions not addressable by substantive procedures alone (e.g., highly automated processing with little manual intervention); controls that, if tested, would reduce the need for substantive work; substantive analytical procedures reducing the need for other procedures; incorporating an element of unpredictability; performing procedures to address management override of controls/other fraud risk; specific procedures for identified "significant risks."

### 8. Internal Control — Meaning, Objectives & Limitations (SA 315)
- **Key formula(s)/rule(s):**
  - Internal Control objectives — mnemonic **SCoRE**: **S**afeguarding of assets; **C**ompliance with applicable laws & regulations; **R**eliability of financial reporting; **E**ffectiveness & efficiency of operations.
  - Basic accounting control objectives — transactions should be: **recorded, real (occurred), properly valued, timely recorded, properly posted & summarised, and properly classified & disclosed.**
- **Concept:** Internal control is the process designed, implemented and maintained by those charged with governance (TCWG), management and other personnel to provide **reasonable** (not absolute) assurance about achievement of the entity's objectives.
- **Pitfalls / exam tips — Inherent Limitations of IC** (a classic short-answer question):
  - Management's consideration that the cost of a control should not exceed the benefit expected from it.
  - Most controls are not directed at unusual/non-routine transactions; potential for human error/mistakes always exists.
  - Possibility of circumvention through collusion between employees or with third parties.
  - Possibility that a person responsible for exercising control could abuse that responsibility (management override).
  - Manipulation by management regarding transactions, estimates and judgements in preparing the FS.
  - Controls designed to be manual are more suitable for judgement-heavy situations: large/unusual/non-recurring transactions; errors that are hard to define/predict; changed circumstances requiring a response outside the scope of existing automated controls; and monitoring the effectiveness of automated controls themselves.

### 9. Components of Internal Control (SA 315 / COSO)
- **Key formula(s)/rule(s):** Five components, always tested in this order:
  **Control Environment → Entity's Risk Assessment Process → Information System & Communication → Control Activities → Monitoring of Controls.**
- **Concept:**
  - **Control Environment** elements: integrity & ethical values, commitment to competence, participation by TCWG, management's philosophy & operating style, organisational structure, assignment of authority & responsibility.
  - **Entity's Risk Assessment Process**: identify business risks relevant to FS preparation → assess likelihood & significance → decide actions to respond to and manage the risks. Circumstances that can change risk: new technology, new/revamped information systems, new personnel, rapid growth, changes in operating environment, corporate restructuring, new accounting pronouncements.
  - **Control Activities** cover: performance reviews; information processing (General IT Controls + Application Controls); physical controls; segregation of duties.
  - **Information System relevant to Financial Reporting**: identifies & records all valid transactions, describes them in sufficient detail for proper classification, measures their value correctly, determines the correct time period, and presents transactions/disclosures properly in the FS.
  - **Monitoring of Controls**: an ongoing process of assessing whether controls are operating as intended and modifying them for changed conditions.
- **Pitfalls / exam tips:** Key practical components used to assess the control environment: Standard Operating Procedures (SOPs), delegation-of-financial-powers documentation, Enterprise Risk Management process, segregation of job responsibilities, job rotation in sensitive areas, and embedding IT-based controls rather than relying on manual/human controls.
- **Definitions:**

| Term | Meaning |
|---|---|
| General IT Controls | Controls over program changes, access restriction, and implementation of new software/applications that support the proper functioning of application controls |
| Application Controls | Controls specific to individual applications, e.g., edit checks on input data, numerical sequence checks, arithmetical accuracy checks |

### 10. Internal Check System
- **Key formula(s)/rule(s):** Objectives of an internal check system: prevent/avoid misappropriation or embezzlement of cash and falsification of accounts; minimise possibility of errors and fraud; detect errors and frauds easily; locate the responsibility/stage where fraud or error occurred; increase staff efficiency; protect business integrity through continuous scrutiny.
- **Concept:** Internal check is a sub-set of internal control achieved primarily through the *arrangement and allocation of duties* such that no one person handles a transaction from start to finish, and the work of one person is automatically checked by another in the normal course of business.
- **Pitfalls / exam tips — general conditions for an effective internal check system** (classic scenario question — e.g., cashier also handling sales ledger and cash receipts is a control failure):
  - No single person should have complete control over any important business operation; every employee's actions should be subject to review by another.
  - Staff duties should be **rotated** periodically.
  - Every staff member should be required to take **leave at least once a year** (surprise substitution can reveal concealment).
  - A person with physical custody of an asset must have **no access to the related books/records**.
  - Separate accounting control should exist for each class of asset with periodic physical inspection.
  - Budgetary controls should be exercised and material deviations reconciled; mechanical/technological devices used to prevent cash misappropriation; year-end inventory-taking done by staff from several sections, with trading activity suspended.

### 11. Internal Control Questionnaire (ICQ), Checklist & Flow Charts
- **Key formula(s)/rule(s):** Basic assumptions underlying a good, standardised ICQ: (i) certain procedures used by most business concerns are essential to reliable IC (e.g., daily banking of receipts, periodic bank reconciliations); (ii) proper division of duties/responsibilities — no single person completes a transaction start-to-finish, custodial and accounting functions are segregated, and work of one is reviewed by another; (iii) proper documentation and recording of every transaction.
- **Concept:** ICQ and check-list are both IC-evaluation tools but differ in scope and use.
- **Pitfalls / exam tips:**
  - For **first-year** engagements, issuing a fresh ICQ is necessary; in **subsequent years**, the auditor may instead ask the client to confirm whether any change in business necessitated a change in controls.
  - Flow charts document: where a document originates (internal/external), number of copies raised, intermediate stages the document/activity passes through, distribution to departments, authorisation/matching checkpoints, filing, and final disposal.
- **Definitions:**

| Term | ICQ | Checklist |
|---|---|---|
| Nature of questions | Large number of detailed questions | Questions related to the main control objectives only |
| Answered by | Company executives | Auditor / audit staff |
| Weakness disclosure | A "No" answer indicates a weakness but not its significance | A specific statement is required describing the material weakness |

### 12. Material Weakness & Management Letter
- **Key formula(s)/rule(s):** Material weakness is defined as an **absence of adequate internal controls** that increases the possibility of errors and frauds in the financial statements (e.g., no age-wise analysis of debtors performed → inadequate provision for bad debts).
- **Concept:** Auditors communicate identified control weaknesses to management/TCWG through a letter of weakness (management letter), which lists the weaknesses and offers suggestions for improvement.
- **Pitfalls / exam tips:** The letter must clearly state that the examination covers only weaknesses that came to the auditor's attention and is **not designed to determine the overall adequacy of IC for management's purposes** — this disclaimer is frequently tested. It also serves as a valuable reference document for revising the system and helps minimise the auditor's legal liability arising from a major defalcation/loss traceable to a control weakness.

### 13. International Internal Control Frameworks
- **Key formula(s)/rule(s):**
  - **COSO Framework** (Committee of Sponsoring Organisations of the Treadway Commission): 5 components — Control Environment, Risk Assessment, Control Activities, Information & Communication, Monitoring; 3 categories of objectives — Operations, Reporting, Compliance.
  - **CoCo Framework** (Canadian Institute of Chartered Accountants): 4 areas of criteria for effective control — Purpose, Commitment, Capability, Monitoring & Learning.
  - ⚠️ VERIFY — **COBIT Framework** (Control Objectives for Information and Related Technology, issued by ISACA/IT Governance Institute): the source states "34 high-level IT processes covering 210 control objectives." This figure corresponds to the older **COBIT 4.1** structure commonly cited in ICAI study material; the current **COBIT 2019** framework instead organises around 40 governance/management objectives — confirm which version's figures your attempt's syllabus expects before quoting the number in an exam.
  - **Sarbanes-Oxley (SOX) Section 404**: management must perform an assessment of Internal Control over Financial Reporting (ICFR), including tests of controls, and include that assessment in the annual report; for an integrated audit, the external auditor provides **two opinions** — an independent opinion on the effectiveness of the ICFR system, and the traditional opinion on the financial statements.
- **Concept:** These frameworks are referenced (mostly for MCQ/short-note purposes) to show how internal control concepts are formalised internationally, alongside the SA 315 five-component model used in Indian auditing practice.
- **Pitfalls / exam tips:** Do not confuse COSO's 5 components (used for SA 315 IC evaluation) with COBIT (an *IT-governance*-specific framework) or CoCo (a distinct 4-area Canadian model) — exam MCQs often test matching the framework to its issuing body and number of components/areas.

### References
1. SA 300, "Planning an Audit of Financial Statements" — ICAI Standards on Auditing (Auditing Pronouncements applicable to CA Final/current syllabus).
2. SA 315 (Revised), "Identifying and Assessing the Risks of Material Misstatement through Understanding the Entity and Its Environment" — ICAI, including the five components of internal control.
3. SA 320, "Materiality in Planning and Performing an Audit" and SA 450, "Evaluation of Misstatements Identified during the Audit" — ICAI Standards on Auditing.
4. SA 200, "Overall Objectives of the Independent Auditor" — Glossary definitions of Audit Risk, Inherent Risk, Control Risk and Detection Risk — ICAI.
5. SA 330, "The Auditor's Responses to Assessed Risks" — ICAI Standards on Auditing.
6. ICAI Study Material / RTP-MTP references for Risk-Based Audit approach, case studies (movie theatre, entertainment centre) and MTP May'23 (purchases without POs), Nov'23 (alteration of audit programme).
7. COSO "Internal Control — Integrated Framework" (Committee of Sponsoring Organisations of the Treadway Commission); CoCo Framework (CICA); COBIT (ISACA/IT Governance Institute); Sarbanes-Oxley Act, 2002, Section 404 — general domain references for the international frameworks note.

## 05. Group Audit (SA 600)

> **Where it fits:** Covers audit of Consolidated Financial Statements (CFS) — statutory basis under Sec 129(3)/(4) Companies Act 2013, the consolidation mechanics under AS 21/23/27 (or Ind AS 110/28/111/103), and the auditor's responsibilities under SA 600 when relying on component/other auditors.

### CFS — Statutory Requirement (Sec 129(3)/(4), Companies Act 2013)

- **Key formula(s)/rule(s):**
  - Where a company has one or more subsidiaries (including associates & JVs), it **must** prepare CFS of itself and all subsidiaries — in the **same form and manner** as its own standalone FS (SFS), as per **Sec 129(3)**.
  - Provisions on preparation, adoption and audit of the FS of a holding company apply **mutatis mutandis** to the CFS — **Sec 129(4)**.
  - CFS must be approved by the Board along with SFS and laid before the AGM along with SFS.
  - A separate statement containing salient features of the FS of each subsidiary/associate/JV must be attached in **Form AOC-1** (first proviso to Sec 129(3), read with Rule 5, Companies (Accounts) Rules, 2014).
  - CFS must comply with **Schedule III** and the applicable Accounting Standards (AS or Ind AS as applicable to the company).
  - A company not required to prepare CFS "as per AS" must still comply with Schedule III requirements for CFS.
- **Concept:** Sec 129(3)/(4) is the trigger provision — presence of even one subsidiary/associate/JV makes CFS mandatory; the audit of CFS is treated as an extension of the SFS audit process.
- **Pitfalls / exam tips:**
  - Do not confuse "subsidiary" definition here with SA 600's "component" — Sec 129 covers subsidiary + associate + JV; SA 600's "component" is broader (division, branch, subsidiary, JV, associate, or any entity whose financial info is included).
  - Students often forget the mutatis mutandis application of audit provisions (Sec 129(4)) — this is why the CFS auditor's report also draws on Sec 143(1)/143(3).

### Exemption from Preparing CFS

- **Key formula(s)/rule(s):** A company is **exempt from preparing CFS only if ALL of the following conditions are cumulatively satisfied** (Rule 6, Companies (Accounts) Rules, 2014 — as referenced under Sec 129(3) proviso) [tested May'25]:
  1. It is a **wholly-owned subsidiary**, or a **partially-owned subsidiary** of another company and **all its other members** (including those otherwise not entitled to vote) have been **intimated in writing**, and **proof of delivery** of such intimation is available with the company, and they **do not object** to the company not presenting CFS;
  2. Its securities are **not listed** and **not in the process of listing** on any stock exchange, whether in India or outside India; **and**
  3. Its ultimate or any intermediate **holding company files CFS with the ROC** which is in compliance with the applicable Accounting Standards.
  - **Additional note:** An **Investment Entity** need not present CFS if it measures **all** its subsidiaries at **Fair Value through Profit & Loss (FVTPL)** as per the applicable Ind AS.
  - **Investment Entity** = an entity that (a) obtains funds from investors to provide investment management services, (b) has a business purpose of investing funds solely for returns from capital appreciation, investment income, or both, and (c) measures & evaluates performance of substantially all its investments on a fair value basis.
  - The **parent of an Investment Entity must still prepare CFS**, unless that parent is itself also an Investment Entity.
- **Concept:** This is a narrow, cumulative (AND, not OR) exemption — losing even one condition (e.g., security gets listed) removes the exemption prospectively.
- **Pitfalls / exam tips:**
  - Exam case-lets (like the "Parent Ltd / Child Ltd temporary control" illustration) test whether **Ind AS 110 permits any exemption for "temporary control"** — it does **not**. Consolidation is mandatory from the date control is obtained until the date control is lost, irrespective of intention to dispose of the stake shortly after (Ind AS 110, control-based consolidation).
  - Where the company is not required to prepare CFS "under AS" per Sec 129(3), it must still comply with the Schedule III CFS format — this is a separately tested nuance.

### Auditor's Objectives & Responsibility of Parent's Management (CFS Audit)

- **Key formula(s)/rule(s) — Management's responsibilities (Parent):**
  - Identifying components and the financial information of components to be included in CFS
  - Obtaining accurate & complete financial information from components
  - Making appropriate consolidation adjustments
  - Harmonization of accounting policies and accounting framework across components
  - GAAP conversion, where applicable
  - Identifying reportable segments for segmental reporting
  - Identifying related parties and RPTs for reporting
  - *Memory flow:* Identify components → Obtain info → Consolidation adjustments → Harmonize a/c policies + GAAP conversion → Segment & RPT reporting
- **Key formula(s)/rule(s) — Auditor's objectives (audit of CFS):**
  - Satisfy that CFS have been prepared as per the Applicable Financial Reporting Framework (AFRF)
  - Express an opinion on the true & fair view presented by CFS
  - Enquire into matters specified in **Sec 143(1)**
  - Report on matters given in **Sec 143(3)**
  - Validate the requirement itself of preparing CFS for the company as per AFRF
- **Concept:** Management (not the auditor) owns the consolidation process; the auditor's job is to obtain sufficient appropriate audit evidence (SAAE) that management's consolidation is correctly done and to opine on the CFS as a whole.
- **Pitfalls / exam tips:** In theory answers, always open with "preparation & presentation of CFS is management's responsibility" before listing audit procedures — examiners specifically reward this framing.

### Materiality in Group Audits

- **Key formula(s)/rule(s):**
  - For audit of **SFS**: materiality is computed for **each component on a standalone basis**.
  - For audit of **CFS**:
    - Compute **materiality for the group as a whole** — used to assess the appropriateness of consolidation adjustments (both permanent & current period) made by management.
    - Group materiality can also be used to determine whether a component's FS are material to the group, to decide whether additional components should be scoped in and whether to use the work of other (component) auditors.
    - Separately, **materiality is also computed and communicated to each component auditor**, for their component-level work.
    - The auditor also obtains **confirmations from the component auditor** — e.g., on independence, compliance with the Code of Ethics, information required for consolidation and disclosure requirements.
  - ⚠️ VERIFY — the OCR does not spell out a numeric benchmark/percentage for setting component materiality relative to group materiality; the underlying principle (component materiality is set **lower** than group materiality, to reduce the risk that the aggregate of uncorrected/undetected misstatements across components exceeds group materiality) is a well-established SA 600/SA 320 concept but no specific percentage should be quoted without the primary text.
  - Modifications/EOM/Other Matter paragraphs in the **component auditor's own report on the SFS** must be evaluated by the group auditor with reference to **group materiality** — this is a principle under **SA 600**.
- **Concept:** Group materiality governs the CFS opinion; component materiality governs the depth of work at each component — the two are linked but distinct.
- **Pitfalls / exam tips:** A common trap is to apply the *component's own standalone* materiality when evaluating a component auditor's qualification for CFS purposes — the correct benchmark is **group materiality**.

### Group Audit Risk Assessment & Completeness of Components (CFS ARA)

- **Key formula(s)/rule(s) — Risk assessment activities:**
  - Understand group structure and group-wide controls, including IT systems/applications relevant to the consolidation process
  - Understand accounting policies of the parent & its components, and the consolidation process
  - Determine the nature, timing & extent (NTE) of audit procedures based on risk assessment in the consolidation process
  - Determine the extent of use of other (component) auditors' work
  - Coordinate the work to be performed with component auditors
- **Key formula(s)/rule(s) — Procedures to ensure completeness of components in CFS:**
  - Review prior-year working papers for known components
  - Review parent's own procedures for identifying components
  - Make inquiries of management to identify any new component, or any component that has gone out of the CFS
  - Review investments of parent & its components to determine shareholding in other entities
  - Review joint ventures and joint arrangements
  - Review other arrangements entered into by the parent not included in CFS
  - Identify changes in shareholding during the reporting period
- **Concept:** Completeness of the "population" of components is a foundational risk — if a component is missed at the identification stage, no amount of audit work on the consolidation itself will catch the omission.
- **Pitfalls / exam tips:** List these as a checklist in theory answers — examiners test "how would the auditor ensure completeness of components" as a standalone 4-5 mark question.

### Consolidation Methods — AS vs Ind AS [tested May'24]

- **Key formula(s)/rule(s):**

| Relationship | Method under AS | Method under Ind AS |
|---|---|---|
| Subsidiary | Line-by-line consolidation (add assets, liabilities, income, expenses, cash flows) per **AS 21**; determine goodwill/capital reserve & minority interest; eliminate intra-group transactions, balances & unrealised profits | Line-by-line consolidation per **Ind AS 110**; recognise goodwill/capital reserve (or gain on bargain purchase) & NCI per **Ind AS 103**; eliminate intra-group transactions, balances, unrealised profits & deferred tax |
| Associate | Equity method — **AS 23** | Equity method — **Ind AS 28** |
| Joint Venture (jointly controlled entity) | **Proportionate consolidation** — **AS 27** | Equity method — **Ind AS 28** (Ind AS 111 classifies as "joint venture") |
| Joint Operation | Not separately defined under AS | Interests in assets, liabilities, revenues & expenses accounted for as part of the entity's own separate FS — **Ind AS 111** |
| Common control combinations | — | Pooling of interests method — **Ind AS 103** |
| Business combination achieved in stages | — | Acquirer remeasures previously-held equity interest at acquisition-date fair value; recognises resulting gain/loss in P&L or OCI — **Ind AS 103** |

  - **De facto control**: an investor holding **less than a majority** of voting rights but with the **practical ability to unilaterally direct** the relevant activities of the investee is still considered to have control (Ind AS 110 control model).
- **Concept:** The single biggest AS-vs-Ind AS difference tested is **JV treatment** — proportionate consolidation (AS 27) vs equity method (Ind AS 28/111).
- **Pitfalls / exam tips:** Do not say "Ind AS 111 uses proportionate consolidation" — that is the old AS 27 method; Ind AS classifies joint arrangements into Joint Ventures (equity method) and Joint Operations (share of assets/liabilities/income/expense), never proportionate consolidation of a whole entity.

### Consolidation Adjustments — Permanent vs Current Period

- **Key formula(s)/rule(s) — Permanent consolidation adjustments** (made on first consolidation, or subsequently on a change in shareholding of a consolidated entity):
  - Determination of Goodwill or Capital Reserve on consolidation
  - Determining equity attributable to Minority/Non-Controlling Interest (NCI)
  - Auditor verification: determine pre-acquisition reserves of components (date of investment is key); verify pre-acquisition reserves are correctly split between parent and NCI; verify changes in permanent adjustments arising from subsequent acquisition/disposal of shares (e.g., stake reduced from 70% to 55%)
  - Where one subsidiary yields goodwill and another yields a capital reserve, management may net the two off for the Balance Sheet — but the auditor must verify that the **gross** amounts of goodwill and capital reserve are shown in the **notes** to CFS
- **Key formula(s)/rule(s) — Current period consolidation adjustments** (made in the period for which CFS is prepared; mainly intra-group items):
  - Intra-group interest paid/received, or management fees, etc.
  - Elimination of unrealised intra-group profit on assets acquired/transferred between subsidiaries
  - Recording deferred tax on unrealised inter-company profits eliminated — as per **Ind AS 12**
  - Intra-group indebtedness between parent and subsidiary
  - Harmonizing different accounting policies followed by parent & its components
  - Recognising subsequent events/transactions occurring between the Balance Sheet date and the date of the audit report on CFS
  - Effects of significant transactions/events between a component's Balance Sheet date (not yet recognised) and the audit report date, where the component's FS are not drawn up to the same Balance Sheet date as the parent
  - Foreign component adjustments to convert local GAAP figures to the GAAP used for CFS
  - Movement in equity of minority interest/NCI since the date of acquisition of the subsidiary
  - **Note:** Under Ind AS, NCI **can be a negative balance** (unlike under AS) — if a subsidiary's net worth is negative, NCI can show a deficit balance.
- **Concept:** Permanent adjustments relate to the *acquisition/ownership structure*; current period adjustments relate to *ongoing intra-group activity* each year.
- **Pitfalls / exam tips:** "Netting off goodwill against capital reserve" is a favourite trick question — remember the **gross** figures must still appear in the notes.

### Reporting Date Gap & Impairment of Goodwill

- **Key formula(s)/rule(s):**
  - Difference between the reporting date of a component's FS and the date of the CFS should **not exceed 6 months** under **AS** (AS 21).
  - Difference between the reporting date of a component's FS and the date of the CFS should **not exceed 3 months** under **Ind AS** (Ind AS 110).
  - Goodwill arising on consolidation is tested for **impairment on every Balance Sheet date** (not amortised).
  - Where an impairment loss on a foreign component's goodwill is determined in a foreign currency, verify whether the loss amount (translated to local/reporting currency) needs adjustment through the **Foreign Currency Translation Reserve (FCTR)** for exchange rate movements.
- **Concept:** These are two of the most frequently tested numeric thresholds in this chapter — always state the AS figure (6 months) and Ind AS figure (3 months) together, since exam questions often ask "under which framework" the entity reports.
- **Pitfalls / exam tips:** Do not swap the two figures — a very common error is to write "3 months under AS, 6 months under Ind AS" (it is the reverse).

### Additional CFS Verification & Disclosure Requirements

- **Key formula(s)/rule(s) — Auditor's other verification steps (beyond memorandum records review):**
  - Verify intra-group transactions & account balances have been eliminated
  - Verify CFS uses uniform accounting policies for like transactions & events; where impracticable to harmonize, verify adequate disclosure of the fact and the different policy applied (per AS 21) — "impracticable" means the entity cannot apply the policy after making every reasonable effort; under Ind AS, appropriate adjustments must instead be made to conform to group policies (Ind AS 110)
  - Verify adjustments made to convert a component's FS from its local GAAP to the GAAP used for CFS
  - Verify calculation of minority/non-controlling interest
  - Verify deferred tax adjustments for temporary differences arising from elimination of intra-group P&L (where parent's accounts are under Ind AS)
  - Verify that a subsidiary's income & expenses are included in CFS only **from the date control is gained to the date control is lost**, and that such income/expenses are based on the assets/liabilities recognised in CFS at the acquisition date
- **Key formula(s)/rule(s) — Component-level disclosures required separately in CFS** (for parent and each component, including foreign components):
  1. Amount of net assets, and net assets as a percentage of consolidated net assets
  2. Amount of share in P&L, and as a percentage of consolidated P&L
  3. Amount of OCI, and as a percentage of consolidated OCI
- **Key formula(s)/rule(s) — Items disclosed in SFS of parent/subsidiaries that need NOT be repeated in CFS:**
  - Source of bonus shares (e.g., capitalisation of profits/reserves/securities premium)
  - Disclosure of unutilised money out of an issue and the form in which it is invested
  - Disclosure under the MSME Development Act, 2006
  - Value of imports on CIF (Cost, Insurance, Freight) basis for raw material / components & spare parts / capital goods
  - Expenditure in foreign exchange during the year (royalty, know-how, etc.)
  - Value of imported vs indigenous raw material/spares/components consumed, and % of each to total consumption
  - Dividend remitted in foreign currency — number of non-resident shareholders, shares held, and the year to which the dividend relates
  - Statement of investments — names of bodies corporate and nature/extent of investment
- **Concept:** These "not required in CFS" items are SFS-only disclosures (largely FEMA/MSME/statutory-origin disclosures) that examiners like to test as a "which of these need NOT be given in CFS" MCQ/list question.

### Management Representations — CFS

- **Key formula(s)/rule(s):** In addition to SFS-level representations, the auditor obtains **written representations from parent's management** covering:
  1. Completeness of components included in CFS
  2. Appropriateness & completeness of permanent & current period consolidation adjustments, including elimination of intra-group transactions
  3. Identification of reportable segments for segmental reporting
  4. Identification of related parties and RPTs for reporting
- **Concept:** Management representation letters do not substitute for audit evidence but are mandatory corroborative evidence under SA 580 principles, applied here to the CFS-specific assertions above.
- **Pitfalls / exam tips:** A "list the CFS-specific management representations" question is common — answer with these four points, not generic SA 580 boilerplate.

### Reporting on CFS

- **Key formula(s)/rule(s) — When parent's auditor is also the auditor of ALL components:**
  - Report whether the procedures for preparation & presentation of CFS as per the applicable AS/Ind AS have been followed
  - Where there is a departure/deviation, consider **SA 705** in the audit report so users are made aware
  - Issue an audit report giving an opinion on whether the CFS gives a true & fair view of the state of affairs of the Group as at the Balance Sheet date, and whether the consolidated P&L gives a true & fair view of the Group's results
  - Where CFS also includes a cash flow statement, also opine on the true & fair view of cash flows
- **Key formula(s)/rule(s) — When parent's auditor is NOT the auditor of all components:**
  - Apply the requirements of **SA 600**
  - Per **SA 706**, where the auditor makes reference to the work of another auditor in the CFS audit report, clearly disclose the magnitude of the portion of FS audited by the other auditor — typically as **aggregate amounts or percentages of total assets, revenues & cash flows** included in the CFS that were not audited by the parent's auditor
  - These aggregate amounts/percentages should be presented **before giving effect to permanent & current period consolidation adjustments**
  - Reference to (an)other auditor(s) in the audit report is **not a qualification of opinion** — it merely indicates a division of responsibility between the auditors of the parent and its components
- **Concept:** Reference to a component auditor's work is disclosure of divided responsibility, never grounds by itself for modifying the opinion.
- **Pitfalls / exam tips:** Students frequently (incorrectly) treat "reference to other auditor" as automatically triggering a qualified opinion — it does not; it is a plain disclosure of responsibility-sharing.

### Component Auditor Under a Different Accounting or Auditing Framework

- **Key formula(s)/rule(s) — Different Accounting Framework (GAAP):**
  - Foreign components may prepare FS under a different Financial Reporting Framework (a well-known framework such as US GAAP/IFRS, or local GAAP)
  - Local component auditors may be unable to report on FS prepared under the parent's GAAP due to unfamiliarity with it
  - Parent's management performs the **conversion** of the component's audited FS to the FRF used for CFS; these **conversion adjustments are audited by the principal (group) auditor**
  - Alternatively, the component may prepare FS as per the parent's accounting policies based on a **Group Accounting Manual**, which the local component auditor can then audit directly
  - The parent's (group) auditor must check that the group accounting policies comply with the GAAP applicable to the parent
  - **Components not audited:** ideally all components should be audited/subjected to audit procedures in a multi-location group audit (by either the group auditor or the component's own auditor); where one or more components remain unaudited, the group auditor must evaluate a possible modification to the CFS report (since SAAE cannot be obtained for those amounts), weighing qualitative & quantitative factors as per **SA 705**
  - **Key formula(s)/rule(s) — Different Auditing Framework:** audits (including CFS) are performed as per audit standards generally accepted in India ("Indian GAAS" — i.e., the SAs). To maintain consistency and allow the group auditor to rely on and refer to a component auditor's report in the CFS audit report, the component's FS should also be audited under a framework that **corresponds to Indian GAAS**.
- **Concept:** Mismatched accounting frameworks are handled via management's conversion (audited by the group auditor); mismatched auditing frameworks are handled by requiring the component auditor's work to be performed under a framework equivalent to Indian SAs.
- **Pitfalls / exam tips:** A classic scenario question gives a foreign subsidiary audited under a different national GAAS/GAAP — answer structure: (1) identify accounting-framework mismatch vs auditing-framework mismatch separately, (2) explain management's conversion + group auditor's audit of the conversion adjustments, (3) conclude on whether the group auditor can rely on/refer to the component auditor's report.

### Definitions

| Term | Meaning |
|---|---|
| Component | A division, branch, subsidiary, joint venture, associate, or other entity whose financial information is included in the financial information audited by the principal/group auditor |
| Principal auditor / Group auditor | The auditor responsible for reporting on the FS of an entity when that FS includes the financial information of one or more components audited by another auditor |
| Other auditor / Component auditor | An auditor, other than the principal/group auditor, responsible for reporting on the financial information of a component included in the FS audited by the group auditor |
| CFS | Consolidated Financial Statements — FS of a parent and its subsidiaries/associates/JVs presented as a single economic entity |
| SFS | Standalone (separate) Financial Statements of an individual entity |
| Investment Entity | An entity whose business is to invest funds for investors purely for capital appreciation/investment income and which measures substantially all investments at fair value (defined above) |
| Permanent consolidation adjustment | Adjustment made on first consolidation, or on a subsequent change in shareholding, e.g. goodwill/capital reserve, NCI determination |
| Current period consolidation adjustment | Adjustment made each period for intra-group transactions/balances, e.g. elimination of unrealised profit, intra-group interest |
| De facto control | Control arising from the practical (unilateral) ability to direct relevant activities despite holding less than majority voting rights |

### References

1. Companies Act, 2013 — Section 129(3) and 129(4) (CFS requirement and mutatis mutandis application), read with Rule 5 & Rule 6 of the Companies (Accounts) Rules, 2014 (Form AOC-1; conditions for CFS exemption).
2. Standard on Auditing (SA) 600 — "Using the Work of Another Auditor" / "Special Considerations — Audits of Group Financial Statements (Including the Work of Component Auditors)", ICAI (definitions of principal/other auditor and component; group vs component materiality principle).
3. Accounting Standard (AS) 21 — Consolidated Financial Statements (line-by-line consolidation; 6-month reporting-date gap; goodwill/capital reserve treatment), and AS 23/AS 27 for associates/joint ventures.
4. Ind AS 110 — Consolidated Financial Statements (control model, de facto control, 3-month reporting-date gap); Ind AS 28 — Investments in Associates and Joint Ventures; Ind AS 111 — Joint Arrangements; Ind AS 103 — Business Combinations (goodwill/NCI/common control/step acquisitions).

## 06. Bank Audit & NBFC Audit
> **Where it fits:** Sector-specific audit chapter — applies the general SA framework (risk assessment, ICs, SA 505 confirmations, fraud reporting) to the two most heavily RBI-regulated entities: Banking Companies (Banking Regulation Act, 1949) and NBFCs (RBI Act, 1934, Ch. III-B). Expect a mix of theory (legal framework, LFAR, CARO applicability) and practical/numerical questions (NPA classification, provisioning %, CRAR).

### Legal Framework & Special Audit Considerations
- **Key rule(s):**
  - Governing statutes: Companies Act 2013, Banking Regulation Act 1949, RBI Act 1934, SBI Act 1955, Prevention of Money Laundering Act 2002, IT Act 2000.
  - Form & content of bank FS: Balance Sheet — **Form A**; Profit & Loss — **Form B** of the **Third Schedule to the Banking Regulation Act, 1949**.
  - Authority appointing auditor: Banking company → shareholders at AGM; Nationalised bank → Board of Directors, with RBI approval.
- **Concept:** Banks differ from other commercial entities due to custody of monetary items, huge transaction volumes, geographically dispersed branches, heavy IT dependence, and evolving products (net/mobile banking) — this drives the extra audit considerations layered on top of the standard SA-based audit.
- **Pitfalls / exam tips:**
  - Don't confuse "Form A/B" — Form A is Balance Sheet, Form B is P&L (easy 1-mark trap).
  - Most banks appoint 4 or more CA firms as **Statutory Central Auditors (SCAs)**; **Statutory Branch Auditors (SBAs)** are appointed as a single firm per branch.
- **Definitions:**

| Term | Meaning |
|---|---|
| SCA | Statutory Central Auditor — audits at Head Office / consolidation level |
| SBA | Statutory Branch Auditor — audits at branch level, reports to SCA |
| LFAR | Long Form Audit Report — detailed questionnaire-format report (see below) |

### Initial Engagement, Understanding & Risk Assessment
- **Key rule(s):**
  - Terms of audit engagement agreed **as per SA 210**.
  - Communication with previous auditor **as per Clause 8 of Part I of the First Schedule to the Chartered Accountants Act, 1949**.
  - Auditor obtains a written **Declaration of Indebtedness** — confirming auditor/family are not wilful defaulters — before accepting appointment.
  - Auditor must not accept the statutory audit if performing internal assignments of the same bank in the same year (independence threat).
- **Concept:** Initial considerations (acceptance/continuance) → Understanding the bank & its risk management process (oversight by TCWG, risk ID/measurement/monitoring, control activities, MIS) → Risk assessment (ROMM at FS/assertion level, fraud & money-laundering risk per RBI KYC/AML norms, outsourcing risk, IT risk) → Execution → Reporting.
- **Pitfalls / exam tips:** In an IT environment, overall IT policy review happens at HO level; branch auditors typically lack access to IT policy/processes and instead perform data review, tests of controls and substantive testing at branch level on SCA guidance.
- **Definitions:**

| Term | Meaning |
|---|---|
| RBIA | Risk Based Internal Audit — bank's internal audit function assessing business risk × control risk per branch, headed by Chief Audit Executive |
| TCWG | Those Charged With Governance (Board/CEO approving risk policies) |

### Internal Controls — Cash, Clearing, Advances, Bills
- **Key rule(s)/thresholds:**
  - Cash must be in **joint custody of two responsible officers**; cashier must have no access to customer ledgers/day book.
  - **CTS (Cheque Truncation System):** electronic cheque image transmitted with MICR/date/presenting-bank details; per RBI, branch should call/e-mail the customer for any inward-clearing cheque of **₹5 lakh and above** (verify on test-check basis). ⚠️ VERIFY — figure/practice matches CA-Final material but confirm against the current RBI cheque-clearing/risk-mitigation circular for the exact monetary limit.
  - Advances kept within **Drawing Power (DP) and sanctioned limit**; temporary excess limit, if any, restricted to **20% of existing limit for a maximum of 90 days**.
  - Stock statements used to compute DP should **not be older than 3 months** — else DP treated as irregular.
  - Ad hoc/regular limits not reviewed within **180 days** from due date → account treated as NPA.
- **Concept:** Standard "internal control checklist" areas tested for banks — Cash → Clearings → Bills for Collection → Bills Purchased → Loans & Advances → Demand Drafts → Credit Cards — each with its own set of control points (segregation of duties, documentation, margins, registers).
- **Pitfalls / exam tips:**
  - Bills purchased outstanding at year-end: discount apportioned between two accounting years.
  - If the collecting/paying branch fails to verify drawer's signature on a cheque, **liability falls on the paying bank**.
  - Case-study trap: cash-credit accounts fully utilised only in March, with FDs created from the utilised funds and liquidated in the first week of the next FY, is a classic **window dressing** fact pattern — report as qualification in the main audit report and in LFAR; also a violation under the Banking Regulation Act, 1949.

### SLR / CRR & Demand and Time Liabilities (DTL)
- **Key rule(s):**
  - **CRR (Cash Reserve Ratio):** minimum fraction of Net Demand & Time Liabilities (NDTL) to be kept as cash/balance with RBI.
  - **SLR (Statutory Liquidity Ratio):** minimum fraction of NDTL to be maintained in cash/gold/approved govt. securities/other liquid assets.
  - Compliance verified on **12 odd dates in different months of the year, not being Fridays**.
  - Exclusions from liabilities when computing NDTL include: paid-up capital & reserves, credit balance in P&L, RBI/EXIM/NABARD refinance, recoveries from bad/doubtful debts already written off, margins in sundry deposits, un-adjusted inter-branch (link branch) balances, etc.
- **Concept:** SLR/CRR compliance is examined by reviewing weekly Friday trial balances consolidated at HO, cross-checked against branch DTL returns (Form A for CRR, Form VIII for SLR).
- **Pitfalls / exam tips:** Watch for foreign-currency conversion rules — forex assets/liabilities in USD, GBP, EUR, JPY converted to INR at RBI reference rate; other currencies converted via New York rate; FBIL reference rate used where available.
- **Definitions:**

| Term | Meaning |
|---|---|
| NDTL | Net Demand & Time Liabilities — the base on which CRR/SLR % is applied |
| DTL | Demand & Time Liability |

### Investments — Classification, Valuation & Verification
- **Key rule(s)/thresholds:**
  - Investment portfolio classified into **3 categories**: **HTM** (Held to Maturity), **HFT** (Held for Trading), **AFS** (Available for Sale).
  - Shifting of investments from AFS to HTM requires **prior approval of the Board of Directors**.
  - **Non-Performing Investment (NPI):** interest/principal overdue for **more than 90 days**; income on NPIs not recognised and provision made for depreciation in value.
  - Half-yearly review of investment portfolio (**30th September & 31st March**); concurrent audit of treasury transactions with results shared with the CMD **at least once a month**.
- **Concept:** Auditor tests (a) investment policy/board approval, (b) segregation of front/middle/back office (execution, settlement/monitoring, accounting), (c) physical verification/independent confirmation as per **SA 505**, (d) classification & valuation compliance with RBI guidelines.
- **Pitfalls / exam tips:** For govt. securities where SGL facility is available, no BR (Balance Receipt/holding confirmation) is issued — auditor instead relies on statement download from **E-Kuber** in the auditor's presence.
- **Definitions:**

| Term | Meaning |
|---|---|
| HTM | Held to Maturity |
| HFT | Held for Trading |
| AFS | Available for Sale |
| SGL | Subsidiary General Ledger (RBI govt. securities holding) |

### Advances — Substantive Procedures & Drawing Power
- **Key rule(s):**
  - Auditor seeks evidence that: advances are outstanding on BS date, represent amounts due to the bank, are supported by loan documents, no advances are unrecorded, valuation basis is appropriate, and RBI/GAAP-compliant provisions are made.
  - **Quick/early mortality account:** an advance that slips to NPA within **12 months of sanction** — needs special scrutiny.
  - **SMA-1 / SMA-2:** "Special Mention Accounts" — early-warning categories before an account actually becomes NPA.
- **Concept:** Beyond documentation checks, DP is verified against extant credit policy (Board-approved, agreed by statutory auditors in sanction letters); for consortium accounts, DP calculation/allocation is the lead bank's responsibility.
- **Pitfalls / exam tips:** Declared stock for DP purposes must not include goods already covered by sundry creditors/LCs/guarantees — a common numerical-adjustment trap in DP computation questions.

### NPA Classification & Provisioning (Banks)
- **Key formula(s)/rule(s):**

$$
\text{NPA (general norm)} = \text{Interest or instalment of principal remains overdue for} > 90 \text{ days}
$$

- Asset classification categories (general advances): **Standard → Sub-Standard (NPA ≤ 12 months) → Doubtful (NPA > 12 months) → Loss**.
- **Accounts regularised near BS date:** genuine regularisation before BS date need not be classified NPA; but if funds are re-lent to enable "regularisation," or the account shows inherent weakness, it is still deemed NPA — classification is based on the **Past Due/Overdue concept, not merely the BS date position**.
- **Government-guaranteed advances:** overdue > 90 days but **NOT classified NPA** for asset-classification/provisioning purposes as long as the **Central Government** guarantee has not been repudiated when invoked (income recognised on realisation basis). ⚠️ VERIFY exception does **not** apply to State Government guarantees — SG-guaranteed advances **are** treated as NPA once overdue beyond 90 days, per the source material; confirm current wording in the applicable RBI Master Direction/Master Circular on Income Recognition, Asset Classification & Provisioning (IRACP) for banks.
- **Agricultural advances:**
  - Long Duration Crops (crop season > 1 year): NPA if principal/interest overdue for **1 crop season**.
  - Short Duration Crops (crop season ≤ 1 year): NPA if principal/interest overdue for **2 crop seasons**.
  - Crop season determined by the State Level Bankers' Committee (SLBC) of each state.
- **Concept:** Restructuring downgrades a standard account to sub-standard (already-NPA accounts stay in the same category); restructuring cannot be done with retrospective effect.
- **Pitfalls / exam tips:**
  - **Sale of NPA:** only an NPA that has remained in the books for **at least 2 years** can be sold; sale is on a cash basis only (no contingent price), without recourse, and the bank assumes no residual risk after sale. Shortfall (sale < net book value) is charged to P&L; excess (sale > net book value) is retained (not reversed) to meet losses on sale of other NPAs.
  - **Purchase of NPA:** 100% risk weight applies for capital-adequacy purposes on NPAs purchased from other banks; provisioning follows the purchasing bank's own classification.

### Verification of Other Assets, Fixed Assets & Non-Banking Assets
- **Key rule(s):**
  - **Sec 9, Banking Regulation Act, 1949:** a bank cannot hold any immovable property for a period **exceeding 7 years** from the date of acquisition, except as required for its own use (RBI extension possible).
  - Non-banking assets acquired in satisfaction of claims are recorded, on the date of acquisition, at the **lower of net book value of the advance or Net Realisable Value (NRV)**.
  - Inoperative/dormant account: a savings/current account with **no transactions for 2 years**.
- **Concept:** Other-asset heads (inter-branch adjustments, interest accrued, TDS/advance tax, stationery & stamps, staff advances, suspense a/c, prepaid expenses) each carry their own verification checklist — mostly reconciliation + ageing + authorisation checks.
- **Pitfalls / exam tips:** Inoperative accounts are a high-fraud-risk area — verify authority for any revival/withdrawal, especially where balances have significantly reduced versus the prior year.

### Verification of Liabilities — Deposits, Borrowings, Bills Payable
- **Key rule(s)/thresholds:**
  - **Bulk deposits:** verify correct (higher) rate of interest offered on single Rupee term deposits of **₹2 crore and above** for scheduled commercial banks. ⚠️ VERIFY — RBI has periodically revised the bulk-deposit threshold (reported at ₹3 crore effective January 2024 in more recent RBI instructions); confirm the figure applicable for the year under audit against the latest RBI Master Direction on interest rates on deposits before quoting in the exam.
  - Interest on deposits paid on the basis of **360 days in a year**.
  - **NRE accounts are repatriable; NRO accounts are not repatriable.**
  - Interest accrued but not due is **not** included under "deposits" — shown under "Other Liabilities & Provisions".
  - As per **SA 505**, external confirmation of borrowings/balances provides audit evidence.
- **Concept:** Contingent liabilities (guarantees, LCs, forward exchange/derivative contracts, claims not acknowledged as debt) require testing of authorisation, completeness and valuation, plus review of subsequent events and legal correspondence; provision under **AS 29** where a claim has crystallised.
- **Pitfalls / exam tips:** Distinguish rediscount (does not appear under "Borrowings") from refinance (does).

### Capital Adequacy — CRAR & Basel III (Banks)
- **Key formula(s)/rule(s):**

$$
\text{CRAR} = \frac{\text{Eligible Total Capital Funds (Tier I + Tier II)}}{\text{Risk-Weighted Assets} + \text{Risk-Weighted Off-Balance-Sheet Items}} \times 100
$$

- RBI requires banks to maintain a **minimum CRAR of 9%** of risk-weighted assets (Basel III minimum, before the Capital Conservation Buffer). ⚠️ VERIFY — with the Capital Conservation Buffer (2.5%) layered on, the effective minimum for most banks works out higher; confirm the exact figure(s) quoted in the current RBI Master Circular on Basel III Capital Regulations before an exam answer.
- **Concept:** **Basel III** norms strengthen capital adequacy, risk management/governance, and transparency/disclosure to improve the banking sector's ability to absorb financial/economic shocks and protect depositors & shareholders. **Stress testing** checks whether the bank holds enough capital to survive adverse economic conditions.

### Bank Audit Reports & Fraud Reporting
- **Key rule(s):**
  - **CARO 2020 is not applicable to banking companies**; instead, **Sec 143(3)(j)** read with the reporting requirements under the Companies Act 2013 applies, along with **Sec 143(3)(i)** (reporting on Internal Financial Controls over Financial Reporting).
  - For nationalised banks, the auditor's report to the **Central Government** must state: BS shows a true & fair view; P&L shows true profit/loss; information/explanations obtained were satisfactory; transactions were within the bank's powers; branch returns were adequate for the audit; and any other matter for CG's attention — including the number of unaudited branches and the quantum of advances/deposits/interest income/expense they represent.
  - **LFAR (Long Form Audit Report):** given by both Statutory Branch Auditors (to SCAs) and Statutory Central Auditors; consolidated LFAR (by SCAs) is placed before the **Audit Committee of the Board (ACB)**, and a copy of the ACB's views is submitted to **RBI within 60 days** of submission of the LFAR.
  - **Fraud reporting:** on detecting fraud, report to **RBI, the Chairman/MD/CEO of the bank, and the Central Government under Sec 143(12) of the Companies Act, 2013**.
  - Reports required in addition to the main audit report: IFC over Financial Reporting (Sec 143(3)(i)); LFAR; compliance with SLR requirements; compliance with income recognition/asset classification/provisioning (IRACP) norms; serious irregularities under Sec 143(12); treasury operations compliance; compliance with the **Ghosh Committee** (frauds) and **Jilani Committee** (internal control systems) recommendations.
- **Concept:** Multiple, overlapping reporting layers exist for bank auditors precisely because banks are systemically important and heavily RBI-regulated — CARO is replaced by these bank-specific reports.

### Concurrent Audit in Banks
- **Key rule(s):**
  - Scope covers: Cash, Deposits, Advances, Investments, Foreign Exchange, House-Keeping, and Other items.
  - Coverage/scope of concurrent audit and the choice of auditor (in-house official vs external CA) is at the **discretion of the Head of Internal Audit, with approval of the Audit Committee of the Board (ACB)**.
  - For an external concurrent auditor: tenure/remuneration decided by ACB; ordinarily **not more than 5 years total**, and no auditor continues at the same branch/business unit for **more than 3 years**.
- **Concept:** Concurrent audit is a **near-real-time, transaction-level** audit (distinct from the periodic statutory audit) aimed at early detection of irregularities in high-risk areas.
- **Pitfalls / exam tips:** Serious irregularities go to the controlling office/HO; on fraud detection, immediately report to the Inspection & Audit Department (HO), the Chief Vigilance Officer, and Branch Managers (unless the branch manager is implicated).

### NBFC — Definition, Registration & the 50:50 Test
- **Key formula(s)/rule(s):**

$$
\text{Company qualifies as NBFC if (audited BS of last FY):}\\
\text{Financial Assets} > 50\% \text{ of Total Assets (excl. intangible assets)} \quad \textbf{AND} \\
\text{Income from Financial Assets} > 50\% \text{ of Gross Income}
$$

- Both limbs must be satisfied ("50:50 test") — only then is RBI registration under **Sec 45-IA of the RBI Act, 1934** required.
- **Minimum Net Owned Fund (NOF): ₹10 crore** for companies newly applying for NBFC registration in most categories (raised from the earlier ₹2 crore).
- **Phased NOF glide path for existing NBFCs (RBI, Feb 2022):**

| NBFC category | Current NOF | By 31.3.2025 | By 31.3.2027 |
|---|---|---|---|
| NBFC-ICC | ₹2 Cr | ₹5 Cr | ₹10 Cr |
| NBFC-MFI | ₹5 Cr | ₹7 Cr | ₹10 Cr |
| NBFC-Factor | ₹5 Cr | ₹7 Cr | ₹10 Cr |

- **Exceptions:** NBFC-P2P, NBFC-AA, and NBFCs with no public funds and no customer interface → NOF of **₹2 crore**; NBFC-IFC (Infrastructure Finance Companies) and IDF-NBFC → NOF of **₹300 crore**.
- **Concept:** Companies exempt from RBI registration despite doing financial-type business (regulated by another regulator instead) include: Mutual Benefit Cos., Venture Capital Funds (SEBI), Chit Cos. (Chit Fund Act), Securitisation & Reconstruction Cos., Housing Finance Institutions (National Housing Bank), Alternate Investment Funds, Stock Exchanges/brokers/merchant bankers (SEBI), Nidhi Cos. (MCA), Insurance Cos. (IRDAI), Mortgage Guarantee Cos., and specified Micro-Finance Cos.
- **Pitfalls / exam tips:** A common case-study pattern: a company below the NOF threshold and without a Certificate of Registration but engaged in financing business — auditor must examine and report under **CARO 2020 Clause (xvi)**.

### NBFC Classification — Scale Based Regulation (SBR)
- **Key rule(s):**
  - **Base Layer (NBFC-BL):** non-deposit-taking NBFCs with asset size **below ₹1,000 crore**, plus NBFC-P2P, NBFC-AA, Non-Operative Financial Holding Cos. (NOFHC), and NBFCs with no public funds & no customer interface — **regardless of asset size**.
  - **Middle Layer (NBFC-ML):** all deposit-taking NBFCs (irrespective of size); non-deposit-taking NBFCs with asset size **≥ ₹1,000 crore**; and Core Investment Companies (CICs), Standalone Primary Dealers (SPDs), Housing Finance Companies (HFCs), Infrastructure Debt Fund-NBFCs (IDF-NBFCs), and Infrastructure Finance Companies (NBFC-IFCs) — **regardless of asset size**.
  - **Upper Layer (NBFC-UL):** NBFCs specifically identified by RBI using a scoring methodology; the **top 10 eligible NBFCs by asset size are always placed in the Upper Layer**, irrespective of any other factor.
  - **Top Layer:** ideally remains empty; populated only if RBI perceives a substantial increase in potential systemic risk from an Upper-Layer NBFC.
  - NBFC-ICC, NBFC-MFI, NBFC-Factor, and NBFC-MGC (Mortgage Guarantee Cos.) can fall in **any layer** depending on size/parameters; government-owned NBFCs are placed only in the **Base or Middle Layer**, never Upper Layer.
- **Concept:** SBR (effective Oct 2022) replaces the earlier "systemically important / non-systemically important" NBFC dichotomy with a four-tier, size-and-risk-based regulatory ladder — higher layers face progressively stricter prudential norms.
- **Pitfalls / exam tips:** Asset size alone doesn't decide layer placement for activity-based categories — e.g., an HFC with ₹800 crore assets still falls in the **Middle Layer** (not Base) because HFCs are always Middle/Upper regardless of size.
- **Definitions:**

| Term | Meaning |
|---|---|
| CIC | Core Investment Company |
| SPD | Standalone Primary Dealer |
| HFC | Housing Finance Company |
| IDF-NBFC | Infrastructure Debt Fund – NBFC |
| NBFC-IFC | Infrastructure Finance Company |
| NBFC-MGC | Mortgage Guarantee Company |

### NBFC Prudential Norms — Capital Adequacy (CRAR)
- **Key formula(s)/rule(s):**

$$
\text{CRAR (NBFC)} = \frac{\text{Tier I Capital} + \text{Tier II Capital}}{\text{Risk-Weighted Assets} + \text{Risk-Adjusted Value of Off-BS Items}} \times 100 \;\ge\; 15\%
$$

- **Tier I capital must not be less than 10%** at any point of time (except for NBFC-MFI, and lending against gold jewellery cases below).
- If loans against gold jewellery constitute **≥ 50% of financial assets**, minimum **Tier I capital = 12%**.
- **Tier I capital** = Owned Fund (reduced by specified inter-group investments/exposures exceeding 10% of owned fund in aggregate) **+** perpetual debt instruments (capped at 15% of aggregate Tier I capital as on the previous 31 March).
- **Tier II capital** = preference shares (other than compulsorily convertible), revaluation reserves (discounted at **55%**), general/standard-asset provisions & loss reserves (up to **1.25% of RWA**), hybrid debt capital instruments, subordinated debt, and perpetual debt instruments not counted in Tier I — capped so that **aggregate Tier II does not exceed Tier I**.
- NBFC-BL is **not eligible** to include perpetual debt instruments in either Tier I or Tier II capital.
- **Concept:** Risk weights applied to specific asset heads for computing RWA — e.g., 0% for cash/bank balances, approved securities, fully-secured loans and CG-guaranteed claims; 20% for SG securities/guarantees and PSU bank bonds; 50% for PPP/toll infrastructure projects post-COD with >1 year of commercial operations; 125% for specified consumer-credit exposure and credit-card receivables; 100% as the residual/default weight.
- **Pitfalls / exam tips:** Don't apply bank CRAR rules (9%) to NBFCs — NBFC minimum CRAR is **15%**, a frequently tested distinction.

### NBFC Asset Classification & NPA Norms
- **Key rule(s)/thresholds (applies to all NBFCs except NBFC-MFI, which follows separate norms):**
  - **Standard Asset:** no default perceived in repayment of principal/interest; does not carry more than normal risk.
  - **Sub-Standard Asset:** NBFC-BL → NPA for a period **≤ 18 months**; NBFC-ML & above → NPA for a period **≤ 12 months**. Also includes accounts whose terms have been renegotiated/rescheduled/restructured, until 1 year of satisfactory performance under the revised terms.
  - **Doubtful Asset:** NBFC-BL → sub-standard for **> 18 months**; NBFC-ML & above → sub-standard for **> 12 months**.
  - **Loss Asset:** identified as a loss by the NBFC/internal or external auditor/RBI inspection, uncollectible with negligible realisable value.
  - **NPA Glide Path (transition to the uniform 90-day norm):**

| Overdue norm | Compliance deadline |
|---|---|
| > 150 days overdue | By 31 March 2024 |
| > 120 days overdue | By 31 March 2025 |
| > 90 days overdue | By 31 March 2026 |

  ⚠️ VERIFY — this glide path (RBI's phased move to the 90-day NPA norm) applied to specific NBFC categories that were earlier on a 180-day norm; confirm which layer(s)/category of NBFC it currently applies to, and that the final 90-day norm milestone (31 March 2026) is still the operative date for the 2026 attempt, against the latest RBI Master Direction on NBFC-SBR / IRACP norms.
- **Concept:** Income on an NPA is recognised only when actually realised (cash basis); any interest recognised on accrual basis before the asset became an NPA, if still unrealised, must be reversed.
- **Pitfalls / exam tips:** Note the BL vs ML threshold flips (18 vs 12 months) — a favourite objective-type/MCQ trap.

### NBFC Provisioning Norms
- **Key rule(s)/rates (% of outstanding, applies to all NBFCs except NBFC-MFI):**

| Asset category | Provision |
|---|---|
| Standard Asset | 0.40% (NBFC-ML & above) / 0.25% (NBFC-BL) |
| Sub-Standard Asset | 10% |
| Doubtful Asset — Unsecured portion | 100% |
| Doubtful Asset — Secured, outstanding up to 1 year | 20% |
| Doubtful Asset — Secured, outstanding 1–3 years | 30% |
| Doubtful Asset — Secured, outstanding > 3 years | 50% |
| Loss Asset | 100% |

- **Concept:** Provision for standard assets is **not netted off from gross advances** — it is shown separately in the Balance Sheet as "**Contingent Provisions against Standard Assets**."
- **Pitfalls / exam tips:** Learn the provisioning table exactly as above — it is a recurring 4–8 mark numerical/theory question; do not confuse it with the (different) bank IRACP provisioning slabs.

### NBFC Audit Procedures & Specific Categories
- **Key rule(s):**
  - Auditor ascertains principal business activity via MOA/AOA, business policy and Board minutes — classification of the NBFC depends on this activity.
  - **Public Deposits** — ceiling on quantum linked to credit rating from an approved credit rating agency; on downgrade below minimum investment grade: no fresh deposits accepted/renewed, existing deposits allowed to run off till maturity, and the matter reported to the **Regional Office of RBI within 15 working days**.
  - **NBFC-P2P:** verify the company only provides an online marketplace connecting lenders & borrowers, does **not lend on its own account**; check Certificate of Registration, Board policy on participant eligibility/pricing/grievance redressal, and RBI reporting compliance.
  - **NBFC-ICC:** physically verify shares/securities held; verify no loan is advanced against security of the NBFC's own shares; dividend income recognised on **cash basis**; compliance with **AS 13** (Accounting for Investments).
  - **Classification of frauds by NBFC:** misappropriation & criminal breach of trust; fraudulent encashment via forged instruments/fictitious accounts; unauthorised credit facilities for illegal gratification; negligence & cash shortages; cheating & forgery; forex irregularities; other frauds. **Cash shortage is treated as fraud** if it exceeds **₹10,000**, or exceeds **₹5,000** and is detected by management/auditor/inspector but not reported by the cashier.
- **Concept:** The **Auditor's Report to the Board of Directors (Para 3 of the NBFC Auditor's Report Directions)** requires the auditor to comment on CoR/50:50-test compliance, NOF compliance, public-deposit compliance, CRAR compliance, and prudential-norm compliance — with an **exception report to the RBI's Regional Office (Dept. of Non-Banking Supervision)** required wherever any of these statements is unfavourable/qualified or non-compliance with Ch. III-B of the RBI Act / applicable RBI Directions is noted. The auditor's duty is limited to **reporting contraventions**, not certifying overall compliance.
  - Note: NBFCs comply with **Ind AS** per Rule 4(1)(iv) of the Companies (Indian Accounting Standards) Rules, 2015 (as amended); Division III of Schedule III applies (vs. Division II for other companies) — key differences include liquidity-order BS presentation, a lower (>1% of total income) materiality threshold for disclosing "other income/expense," and separate disclosure of receivables from group LLPs.
- **Pitfalls / exam tips:**
  - **CARO 2020 applicability to NBFC:** Clause (iii) of Para 3 applies **except sub-clauses (a) and (e)** (these two are specifically excluded for companies whose principal business is granting loans), **plus Clause (xvi)** (registration under Sec 45-IA, and reporting if required but not obtained).
  - Classic case-study: an NBFC accepting public deposits without a Certificate of Registration, with NOF below the prescribed limit (even if it has since applied) — report under CARO 2020 Clause (xvi), stating whether registration was required, whether obtained, and reasons if not.

### References
1. Reserve Bank of India, *Master Circular on Basel III Capital Regulations* — minimum CRAR for banks (9% of RWA, before Capital Conservation Buffer).
2. Reserve Bank of India, *Master Direction – Reserve Bank of India (Non-Banking Financial Company – Scale Based Regulation) Directions, 2023* — NBFC layer classification, CRAR/Tier I & II capital, asset classification & provisioning norms.
3. Reserve Bank of India, Press Release/Circular (Feb 2022) on revision of Net Owned Fund requirements for NBFC-ICC, NBFC-MFI, NBFC-Factor and phased timelines.
4. Reserve Bank of India Act, 1934 — Sec 45-IA (registration of NBFCs) and Chapter III-B provisions.
5. Banking Regulation Act, 1949 — Third Schedule (Form A/B), Sec 9 (restriction on holding immovable property).
6. Companies Act, 2013 — Sec 143(3)(i) (IFC over Financial Reporting), Sec 143(3)(j), Sec 143(12) (fraud reporting).
7. Companies (Auditor's Report) Order, 2020 (CARO 2020) — Para 3, Clause (iii) exceptions and Clause (xvi) for NBFCs; non-applicability to banking companies.
8. Standards on Auditing — SA 210 (Agreeing the Terms of Audit Engagements), SA 505 (External Confirmations), as issued by ICAI.
9. ICAI Guidance Note on Audit of Banks (relevant edition) — LFAR format, concurrent audit scope, verification of assets/liabilities checklists.
10. Companies (Indian Accounting Standards) Rules, 2015 (as amended) and Schedule III, Division III — Ind AS presentation requirements for NBFCs.

## 07. PSU Audit

> **Where it fits:** Covers Government Audit conducted by the C&AG under Constitutional/statutory mandate — appointment & audit of Government Companies under the Companies Act 2013, the Parliamentary committees that oversee C&AG reports, and the substantive scope of PSU audit (Financial, Compliance, Performance, Comprehensive & Propriety audit).

### Constitutional & Statutory Framework of C&AG

- **Key formula(s)/rule(s):**

$$
\text{Term of C\&AG} = \min\big(\,6\text{ years from date of assuming office},\ \ \text{age }65\text{ years}\,\big)
$$

  - **Article 148** — Appointment of C&AG by the President; removed only on ground of **proven misbehaviour or incapacity** (special procedure, same as removal of a Supreme Court Judge); salary & conditions of service determined by Parliament and cannot be varied to his disadvantage after appointment.
  - **Article 149** — The **C&AG's (Duties, Powers and Conditions of Service) Act, 1971 (DPC Act, 1971)** defines the functions and powers of the C&AG.
  - **Article 150** — On the advice of the C&AG, the President prescribes the **form of accounts** of the Union and of the States.
  - **Article 151** — Audit Reports of the C&AG relating to accounts of the **Union** are submitted to the **President**; relating to accounts of a **State** are submitted to the **Governor**; each is thereafter laid before Parliament / the State Legislature respectively.

- **Concept:** The C&AG is an independent constitutional authority (not part of any Ministry) whose reports are the primary basis on which Parliament/State Legislatures hold the Executive financially accountable.

- **Pitfalls / exam tips:**
  - Do not confuse "term of office" (6 yrs / age 65, whichever is earlier — from the DPC Act, 1971) with the Article numbers, which deal with appointment/removal/accounts form/report submission, not tenure.
  - Sequence to remember: **148**(appointment/removal) → **149**(powers via 1971 Act) → **150**(form of accounts) → **151**(report submission & laying before legislature).

- **Definitions:**

| Term | Meaning |
|---|---|
| SAI | Supreme Audit Institution — in India, comprises the C&AG + the Indian Audit & Accounts Department (IAAD) |
| Accountant General | Senior functionary of the SAI representing the C&AG at State level |

---

### Organisations Subject to C&AG Audit

- **Key formula(s)/rule(s):** Coverage = **Departments & Offices** + **Commercial & Non-commercial bodies** + **Substantially financed bodies**, specifically:
  - All Union & State Government departments/offices, **including Railways, Posts & Telecom**.
  - Public commercial enterprises controlled by Union/State Governments — i.e., **Government Companies & Corporations**.
  - Non-commercial autonomous bodies/authorities owned or controlled by the Union/States.
  - Authorities & bodies **substantially financed** from Union/State revenues.

- **Concept:** C&AG's audit jurisdiction extends well beyond core government departments to any entity where public money/control is involved.

- **Pitfalls / exam tips:** Memory peg — *"Dept & Offices >> Commercial + Non-Commercial >> Substantially financed."*

---

### Audit of Government Companies

- **Key formula(s)/rule(s):**

$$
\text{Government Company (Sec. 2(45), Companies Act, 2013)} \iff \text{Govt. shareholding (CG and/or SG(s))} \geq 51\% \text{ of paid-up share capital}
$$

  (includes a company that is a **subsidiary** of a Government Company)

  - **Section 139(5)/(7)** — Auditor of a Government Company (or a company owned/controlled by CG, or by CG and one or more SG) is **appointed by the C&AG**.
  - **Section 143(5)** — The C&AG directs the manner in which the accounts are to be audited; the auditor submits a copy of the audit report to the C&AG, which shall include: directions (if any) issued by the C&AG, action taken thereon, and their impact on the accounts and FS of the company.
  - **Section 143(6)(a)** — The C&AG has the right to conduct a **supplementary audit** of the FS within **60 days** from the date of receipt of the audit report, and may comment upon/supplement the report; such comments are sent to the company and placed before the AGM.
  - **Section 143(7)** — The C&AG may order a **test audit**, in accordance with **Section 19A of the DPC Act, 1971**.

- **Concept:** For Government Companies, statutory audit is a two-tier check — the Company Auditor (appointed by C&AG) does the primary audit; the C&AG can additionally conduct supplementary/test audit.

- **Pitfalls / exam tips:**
  - The **60-day** window for supplementary audit under Sec. 143(6)(a) is a favourite objective-type question.
  - Do not say the C&AG "appoints" the auditor loosely — technically it flows through Sec. 139(5) (first auditor) / 139(7) (subsequent auditor).

- **Definitions:**

| Term | Meaning |
|---|---|
| Government Company | Co. with ≥ 51% paid-up capital held by CG/SG(s) (Sec. 2(45)) |
| Deemed Government Company | Includes subsidiaries of a Government Company |
| Supplementary Audit | Additional audit by C&AG on the FS already audited by the Company Auditor, within 60 days of receiving the report |
| Test Audit | Selective/sample audit ordered by C&AG under Sec. 19A of DPC Act, 1971 |

---

### Parliamentary Committees Reviewing C&AG Reports

- **Key formula(s)/rule(s):** Three committees, constituted by Parliament/State Legislature, examine C&AG's Audit Reports:

  1. **Public Accounts Committee (PAC)** — satisfies itself that:
     - monies were disbursed legally for the service/purpose for which they were applied;
     - expenditure incurred was authorised;
     - re-appropriation was made as per provisions (redistribution of funds);
     - also examines accounts of autonomous/semi-autonomous bodies audited by the C&AG.

  2. **Estimates Committee** — examines estimates to:
     - report on economies, improvements in organisation, and efficiency consistent with the underlying policy;
     - suggest alternative policies;
     - examine whether money is well laid out within the limits;
     - suggest the form in which estimates are presented to Parliament.

  3. **Committee on Public Undertakings (COPU)** — exercises over PSUs the same financial control that PAC exercises over Govt. departments:
     - examines reports & accounts of PSUs;
     - examines C&AG's reports on public undertakings;
     - examines whether PSUs are managed per sound business principles & prudent commercial practices (autonomy & efficiency);
     - other functions of PAC/Estimates Committee not covered above, as allotted by the Speaker.

- **Concept:** The C&AG acts as *"Friend, Philosopher & Guide"* to these committees — his report forms the basis of their working; he scrutinises ministry notes to check correctness of submissions. Committees present their Report (with observations/recommendations) to Parliament/Legislature; ministries report back on action taken; committees then present **Action Taken Reports**. Where a report cannot be discussed in detail, a written answer is obtained from the department so the report is not taken lightly even if not fully discussed.

- **Pitfalls / exam tips:**
  - Mnemonic for Estimates Committee: *"Economies/efficiency → alternate policies → money laid out? → form."*
  - Mnemonic for COPU: *"Examine a/cs + C&AG report → Autonomy & efficiency (SBP+PCP) → Other functions."*
  - Do not mix up PAC (Govt. departments) with COPU (PSUs) — same nature of scrutiny, different subject.

---

### Objective & Scope of PSU Audit — Overview

- **Key formula(s)/rule(s):** PSU audit is **not limited to Financial & Compliance audit** — it also covers **Performance audit**. Broader accountability split:
  - **Fiscal Accountability** — audit of provision of funds, sanctions, compliance and propriety.
  - **Managerial Accountability** — Efficiency, Economy & Effectiveness (i.e., **Performance audit**).

- **Concept:** PSU audit aims to help government by bringing out financial & operational deficiencies, analysing causes, and highlighting scope for more efficient & economic operations.

- **Pitfalls / exam tips:** Remember the umbrella — Financial + Compliance + Performance (+ Propriety & Comprehensive as specialised forms of the above) = full scope of PSU audit.

- **Definitions (Engagement elements, per Government Auditing Standards):**

| Term | Meaning |
|---|---|
| Auditor | The SAI (India) and persons delegated for the audit |
| Responsible Party | Entity and its TCWG responsible for the subject matter information (e.g., the FS) |
| Intended Users | Individuals/organisations for whom the auditor prepares the audit report (e.g., Parliament) |
| Subject Matter | Information, condition or activity measured/evaluated against criteria |
| Criteria | Benchmarks used to evaluate the subject matter (e.g., the AFRF) |
| Subject Matter Information | The outcome of evaluating/measuring the subject matter against the criteria |
| Attestation Engagement | Responsible party measures subject matter against criteria and presents subject matter information; auditor gathers SAAE to express a conclusion on it |
| Direct Reporting Engagement | Auditor itself measures/evaluates the subject matter against the criteria |

  - **Financial audits** are attestation engagements (based on financial information presented by the responsible party); **Performance & Compliance audits** are generally **direct reporting** engagements.

---

### Principles of PSU Audit

- **Key formula(s)/rule(s):**
  - **General Principles:** Ethics & Independence, Professional Judgement/due care & scepticism, Quality Control, Audit Team management & skill, Audit Risk, Materiality, Documentation, Communication.
  - **Principles relating to the Audit Process:**
    1. **Planning the audit** — agreeing terms of engagement, understanding the entity, developing the audit plan.
    2. **Conducting the audit** — performing audit procedures, evaluating evidence, drawing conclusions.
    3. **Reporting & follow-up** — reporting based on conclusions and following up on reported matters.

- **Concept:** These mirror the SA-based framework (planning → execution → reporting) that ICAI students already know, adapted for the public-sector/direct-reporting context.

- **Pitfalls / exam tips:** These 3 process-stages recur across Financial, Compliance and Performance audit descriptions below — use them as the common skeleton.

---

### Financial Audit

- **Key formula(s)/rule(s):** C&AG expresses an opinion on whether the FS are prepared, **in all material respects, as per the Applicable Financial Reporting Framework (AFRF)**.

- **Concept:** Conducted to express an audit opinion on FS and enhance the confidence of intended users — conceptually identical to a company statutory audit opinion, adapted to government entities.

- **Pitfalls / exam tips:** Financial audit = attestation engagement (see table above).

---

### Compliance Audit

- **Key formula(s)/rule(s):** Compliance audit is concerned with:
  - **Regularity** — adherence of the subject matter to the relevant laws, regulations & agreements applicable to the entity.
  - **Propriety** — observance of general principles of sound financial management & ethical conduct of public officials.

  It may be conducted:
  - in relation to the audit of FS, or
  - separately, as an individual compliance audit, or
  - in combination with performance auditing.

  **Compliance Audit Process** (mirrors a normal audit):
  1. General principles & Annual Compliance Audit Plan — consider ethics-relevant principles, determine auditable entities, develop the annual plan.
  2. Planning — determine objective & scope, audit strategy/plan, understand the entity & environment/IC/materiality, assess risk, plan procedures.
  3. Performing & Gathering Evidence — gather evidence, continually update planning/risk assessment, consider non-compliance with laws.
  4. Evaluating Evidence & Forming Conclusions — evaluate whether SAAE obtained, consider materiality for reporting, form conclusions; documentation, communication & quality control.
  5. Reporting — prepare report, obtain entity responses, follow up on previous reports.

- **Concept:** Assesses whether activities, financial transactions and information comply with applicable regulatory and other rules.

- **Pitfalls / exam tips:** Regularity = "did they follow the rules?"; Propriety = "was it the right/ethical thing to do, even if technically within the rules?" — a favourite distinction in theory questions.

---

### Performance Audit

- **Key formula(s)/rule(s):** Assessed on the **3 Es**:
  - **Economy** — minimise the cost of resources used for an activity, having regard to appropriate quantity, quality and best price.
  - **Efficiency** — the input-output ratio: maximum output for a given input, **or** minimum input for a given quantity & quality of output.
  - **Effectiveness** — the extent to which objectives are achieved and the relationship between the intended and actual impact of an activity.

- **Concept:** An objective & systematic examination of evidence for independent assessment of the performance of a government organisation/programme, to improve public accountability and facilitate corrective decision-making. Conducted by the C&AG through subordinate offices of the IAAD, guided by the C&AG's manual & auditing standards.

- **Pitfalls / exam tips:**
  - 3 Es checklist for Economy/Efficiency: sound procurement policy, proper protection/maintenance of resources, efficient utilisation of physical/financial/HR resources, efficient management & operating procedures.
  - Effectiveness checks: are objectives/means proper & policy-consistent; extent of results achieved; whether social/economic impact is attributable to the policy (vs. other causes); effectiveness of the programme/components; ways to make the programme work better.
  - **Case study (ICAI):** Performance audit of Minimum Wages Act enforcement — auditor should know the industries/labour contracts involved; evaluate standard of living before/after the Act; evaluate EEE (Economy, Efficiency, Effectiveness) of the welfare system; study coordination gaps between labour dept./ESI/EPF; point out gaps in existing law.

**Planning for Performance Audit**

- **Key formula(s)/rule(s):** Sequence: **Understand the entity/programme → Define objectives & scope → Determine audit criteria → Decide audit approach → Develop audit questions → Assess team skills/need for experts → Prepare Audit Design Matrix → Establish timetable & resources.**

- Sources for **understanding the entity**: documents of the entity, legislative documents, policy documents, academic/special research, past audits, media coverage.
- Sources for **audit criteria**: procedure manuals of the entity; policies/standards/directives/guidelines; criteria used by the same/similar entities; independent expert opinion; new/established scientific knowledge; general management & subject-matter literature.
- Methods/means for the **audit approach**: analysis of procedures, examination of documents, case studies, use of existing data, surveys, analysis of results, quantitative analysis (sampling may be used where complete data isn't available).
- **Audit Design Matrix** columns: Audit Objective | Audit Questions | Audit Criteria | Evidence | Data Collection & Analysis Method.

- **Concept:** A structured planning approach ensures the performance audit has clear, evidence-based objectives before fieldwork begins.

- **Pitfalls / exam tips:** The Accountant General may use the work of an expert but **retains full responsibility** for the opinion expressed in the audit report — do not say responsibility shifts to the expert.

---

### Comprehensive Audit

- **Key formula(s)/rule(s):** = **Efficiency-cum-performance audit** — locates areas of weakness & extravagance for management information. Typical issues examined:
  - Was overall cost of capital substantially higher than the approved/planned cost?
  - Was there extravagance or unnecessary expenditure?
  - Were cost-control measures adequate; wastage in raw-material consumption?
  - Was planned production/operational output achieved; was there under-utilisation of installed capacity, and its cause?
  - Was the planned rate of return achieved?
  - Are systems of project formulation & implementation sound, or are there inadequacies?
  - Does the enterprise have an adequate Research & Development programme?
  - Does the enterprise have an adequate system of Repair & Maintenance?

- **Concept:** A broader appraisal that combines financial scrutiny with an efficiency/performance lens, aimed at surfacing management-actionable weaknesses.

- **Pitfalls / exam tips:** Comprehensive audit ≠ Performance audit exactly — it's specifically pitched as "efficiency-cum-performance" with a strong capital-expenditure/capacity-utilisation flavour.

---

### Propriety Audit

- **Key formula(s)/rule(s):** Brings out cases of **improper, avoidable, or infructuous expenditure — even where incurred in accordance with the existing rules & regulations**.
  - Example: a building constructed for a telephone exchange but never used for that purpose = infructuous expenditure; a school building used only 5 years after completion = avoidable expenditure.

  **Principles of Propriety** (4 classic principles):
  1. Expenditure should not, prima facie, be more than what the occasion demands; the official should exercise the same degree of vigilance as a person of ordinary prudence would with his own money.
  2. The authority exercising the power to sanction expenditure should not do so in a way that benefits itself.
  3. Public funds should not be utilised for the benefit of a particular person or set of persons.
  4. Apart from agreed remuneration/reward, no other indirect benefit should accrue to management or employees.

  **Functions of the Auditor in Propriety Audit:**
  - See that expenditure is properly planned.
  - See that the size of expenditure is justified and expected to give maximum results.
  - Appraise whether the expenditure is likely to give optimum results.
  - See whether a substitute plan of action could improve the return on the capital expenditure.
  - Examine whether management's actions/decisions are conducive to public interest and meet standards of conduct.

- **Concept:** Propriety audit goes beyond legality/regularity to test whether expenditure was *wise, faithful and economical* — the money could have been spent legally yet still improperly.

- **Pitfalls / exam tips:** The "4 principles of propriety" and "5 functions of the auditor" are classic 4-5 mark theory questions (RTP/past exams) — list them exactly as above.

---

### Parts of the C&AG's Audit Report on Government Companies

- **Key formula(s)/rule(s):** The Audit Report of the C&AG comprises **4 parts**:
  1. **Introduction** — a general review of the working results of Government Companies/deemed Government Companies.
  2. **Results of comprehensive appraisals** of selected undertakings conducted by the Audit Board.
  3. **Resume of the Company Auditors' reports** submitted under directions of the C&AG, with comments on the accounts of Government Companies.
  4. **Significant results** of the audit of undertakings not taken up for appraisal by the Audit Board.

- **Concept:** This 4-part structure is how the C&AG's consolidated commentary on the PSU sector is presented to Parliament.

- **Pitfalls / exam tips:** Memory peg "4M": **I**ntroduction → **A**ppraisal results → **R**esume of Co. Auditor's reports → **S**ignificant other results (not taken up for appraisal).

---

### References

1. Constitution of India — Articles 148, 149, 150, 151 (appointment, powers via DPC Act 1971, form of accounts, submission/laying of audit reports).
2. Comptroller and Auditor-General's (Duties, Powers and Conditions of Service) Act, 1971 — term of office (6 years/age 65), Section 19A (test audit).
3. Companies Act, 2013 — Section 2(45) (Government Company definition, ≥51% Govt. shareholding), Section 139(5)/(7) (appointment of auditor by C&AG), Section 143(5)/(6)/(7) (directions by C&AG, supplementary audit within 60 days of receipt of report, test audit).
4. ICAI Study Material / C&AG's Auditing Standards on Government Audit (framework for Financial, Compliance & Performance audit; attestation vs. direct-reporting engagements; the 3 Es — Economy, Efficiency, Effectiveness) — current CA Final Advanced Auditing & Professional Ethics syllabus.

⚠️ VERIFY — the OCR reference to "(Nov 31/4)" against Functions of Auditor in Propriety Audit could not be reliably matched to a specific exam attempt/marks allocation; treat as an indicative past-exam tag only, not a confirmed citation.

## 08. Internal Audit & SA 610 (Using the Work of Internal Auditors)

> **Where it fits:** Internal Audit is a management-appointed assurance/consulting function over governance, risk management & internal controls (GRC); SA 610 (Revised) governs how the *external/statutory* auditor may rely on, or take direct assistance from, that internal audit function while retaining sole responsibility for the audit opinion.

### 1. Meaning, Objectives & Scope of Internal Audit

- **Key formula(s)/rule(s):**
  - Internal Audit = an **independent assurance function** on the effectiveness of internal controls and risk management processes, aimed at enhancing governance and helping achieve organisational objectives.
  - Indicative objectives (mnemonic — **M-E-R-R-R-G**): **M**onitoring of ICs, **E**xamination of financial & operating info., **R**eview of operating activities, **R**eview of compliance with laws/regulations, **R**isk management, **G**overnance assessment.
- **Concept:** Internal audit is a managerial control tool — it evaluates and strengthens the control environment; it is not restricted to financial matters like a statutory audit.
- **Pitfalls / exam tips:**
  - Do not confuse Internal Audit's *objective* (independent assurance to enhance governance) with the *statutory auditor's* objective (opinion on true & fair view of FS) — see comparison table under Topic 10.
  - In case studies, always tie the example back to one of the six objectives (e.g., 3-way PO/GRN/Invoice matching → "Monitoring of ICs").

---

### 2. Applicability of Internal Audit — Section 138 & Rule 13

- **Key formula(s)/rule(s):**

$$
\text{Listed Company} \Rightarrow \textbf{Always required to appoint Internal Auditor (no threshold)}
$$

$$
\text{Unlisted Public Co. appoints IA if:}\quad (PUSC \ge ₹50\text{ cr, preceding FY}) \;\lor\; (T/O \ge ₹200\text{ cr, preceding FY}) \;\lor\; (\text{Borrowings from Banks/PFI} > ₹100\text{ cr, at any point of preceding FY}) \;\lor\; (\text{Outstanding Deposits} \ge ₹25\text{ cr, at any point of preceding FY})
$$

$$
\text{Private Co. appoints IA if:}\quad (T/O \ge ₹200\text{ cr, preceding FY}) \;\lor\; (\text{Borrowings from Banks/PFI} > ₹100\text{ cr, at any point of preceding FY})
$$

  - A company newly triggering any of the above criteria must **comply within 6 months of commencement of the FY** in which the criterion first applies.
  - Legal basis: **Section 138, Companies Act, 2013 read with Rule 13, Companies (Accounts) Rules, 2014.**
- **Concept:** Determines whether internal audit is *mandatory*; below these thresholds, internal audit may still be voluntarily adopted as good governance practice.
- **Pitfalls / exam tips:**
  - Turnover & paid-up share capital are tested using the figure of the **preceding financial year** (a point-in-time single figure), whereas loans/borrowings and deposits are tested **"at any point of time during the preceding FY"** (peak balance, not year-end balance) — a very common trap in numerical MCQs/case studies.
  - Private companies do **not** have a deposit or paid-up capital criterion — only turnover and borrowings apply to them.
  - Classic exam numbers: if turnover of the immediately preceding FY ≥ ₹200 cr (even if paid-up capital is small), internal audit becomes mandatory regardless of management's opinion that "no internal system exists."

---

### 3. Appointment — Who Can Be Internal Auditor

- **Key formula(s)/rule(s):**
  - Internal Auditor may be an **individual, a partnership firm, or a body corporate**.
  - Must be a **Chartered Accountant** or **Cost Accountant** (whether in practice or not), **or such other professional** as decided by the Board.
  - May or may not be an **employee of the company**.
- **Concept:** Unlike the statutory auditor, the eligibility net is wider (practising or non-practising CA/CMA, or Board-approved professional), and independence-in-appearance requirements are lighter (can be an employee).
- **Pitfalls / exam tips:** A practising Cost Accountant CAN validly be appointed internal auditor of a private company crossing the borrowings/turnover threshold — a frequently tested "comment on validity" question.

---

### 4. Critical Activities of the IA Function & Main Responsibilities of the Internal Auditor

- **Key formula(s)/rule(s):** Critical activities of the Internal Audit Function (mnemonic — **P-O-S-E-C**):
  - **P**lan overall scope & methodology periodically
  - **O**versee/monitor audit assignments (planning, execution, reporting, closure)
  - **S**taff — plan, engage, review performance & training of professional staff
  - **E**xperts — identify/engage external experts & technical solutions where needed
  - **C**ommunicate & engage with key stakeholders on progress/objectives
  - (also: develop & maintain a quality evaluation/improvement programme)
- **Concept:** Main responsibilities of the internal auditor re: accounting/financial records: maintain an adequate system of internal control to safeguard assets, operate independently of accounting staff, avoid executive functions, report facts management would otherwise not know, stay current on the business, and preserve independent status at all times.
- **Pitfalls / exam tips:** Approach to developing the Internal Audit Plan must balance four factors: (i) coverage of all auditable areas within a defined time cycle, (ii) value IA can add, (iii) effort involved, and (iv) the underlying business risk and the entity's **risk appetite**.

---

### 5. Scope of Internal Auditor's Work (Review Areas)

- **Key formula(s)/rule(s):** Review coverage typically includes:
  1. **IC systems & procedures** — assess design/operating effectiveness; reduce residual risk; review 3-way matching (PO–GRN–Invoice) to prevent over-invoicing/overpayment/short-receipt; weigh cost-benefit, collusion & human-error limitations of IC.
  2. **Safeguarding of assets** — verify existence, review segregation of duties, ensure completeness of asset records, review controls over intangible assets.
  3. **Compliance** with policies, plans, procedures & regulations — flag weaknesses and suggest remedial action.
  4. **Relevance & reliability of information** — evaluate accuracy of MIS; check "reporting by exception" highlights significant/distinctive items.
  5. **Organisation structure** — check for simplicity, no undue dominance of one function, no overlap of HQ vs operating-unit responsibilities, reasonable **span of control**, and **unity of command** (each person reports to only one superior).
  6. **Utilisation of resources** — check operating standards/norms are specific enough to be tied to responsibilities; investigate wide variances (e.g., idle machines, idle cash, unoccupied space, idle manpower).
  7. **Accomplishment of goals & objectives** — objectives should be clearly stated, quantifiable, attainable, with flexibility for improvement.
- **Concept:** This is essentially a checklist syllabus tests as "review of ___ under internal audit scope" — map each fact pattern in a case study to one of the 7 headings above.
- **Pitfalls / exam tips:** A separate credit-control department is **not** automatically necessary — if the objective (minimise credit risk/DSO) can be met via controls already built into the accounting & sales systems, especially for small/medium concerns, a standalone department is not justified.

---

### 6. Integrity, Objectivity, Independence & Qualities of Internal Auditor

- **Key formula(s)/rule(s):**
  - Independence required both **in mind and in appearance**; must resist undue pressure; reporting line/status of the Chief Internal Auditor and delegated authority establish independence.
  - Must not review an activity for which he/she was previously responsible (avoids conflict of interest / self-review threat).
  - For a **listed company**, the internal auditor may report directly to those charged with governance (e.g., the Audit Committee) instead of the CEO/CFO.
  - Qualities required: accounting/financial expertise, ability to evaluate operational (non-monetary) controls, working knowledge of commerce, laws, taxation, cost accounting, economics, EDP/IT systems, management principles, and interpersonal skills; must maintain confidentiality.
- **Concept:** These are the qualitative "soft" attributes tested typically as short notes / one-mark objective questions.
- **Pitfalls / exam tips:** Any conflict of interest noticed by the internal auditor must be **immediately brought to management's attention** so corrective action can be taken.

---

### 7. Conducting the Internal Audit Engagement — 5 Steps

- **Key formula(s)/rule(s):** Standard 5-step engagement flow:
  1. **Obtain knowledge of the business & its environment** — meetings with stakeholders, understand SOPs/FS, IT landscape, ERP/MIS.
  2. **Perform audit planning** — scope approved by the Audit Committee/BOD; detailed work plan by audit managers, approved by Head of Internal Audit/Chief Internal Auditor (ChIA), after evaluating major risks.
  3. **Gather required information** — obtain info directly from source; check correctness/integrity; give advance intimation for interim data needs.
  4. **Perform audit checks** — analytical procedures (trends/outliers), sampling, evidence gathering & documentation, interim reporting.
  5. **Reporting of internal audit issues** — draft report with scope, coverage/exclusions, period, summary of gaps & recommendations; agree Management Action Plan (with responsibility & timelines); review status of prior-audit actions; circulate final report to the Audit Committee.
- **Concept:** Mirrors the statutory audit cycle (understand entity → plan → gather evidence → test → report) but is management/Audit-Committee driven rather than shareholder driven.
- **Pitfalls / exam tips:** Audit scope is approved at two levels — first by the **Audit Committee & Board**, and then the detailed work plan is separately approved by the **Head of IA/ChIA**.

---

### 8. Reporting by Internal Audit — Two-Stage Reporting & Report Contents

- **Key formula(s)/rule(s):**
  - ⚠️ VERIFY — OCR references **"SIA 370 – Reporting"** (a Standard on Internal Audit issued by ICAI's Internal Audit Standards Board) as the source of the two-stage reporting requirement below; confirm the exact SIA number/title against the current ICAI Internal Audit Standards Board publication before quoting it in an exam.
  - **Two-stage reporting under SIA 370:**
    1. At the **end of each assignment** — a report on the specific area/function is issued, highlighting key observations and how the assignment was conducted, sent to Audit (with copies to local management agreed during planning).
    2. On a **periodic (normally quarterly) basis**, at the close of the plan period — a **comprehensive report** covering the whole entity for the period is prepared by the **Chief Internal Auditor** (or the Engagement Partner, for an external service provider) and submitted to the Audit Committee.
  - Typical **Internal Audit Report contents**: audit scope performed, period covered, executive summary, summary of critical findings, detailed findings with business impact/root cause, **rating of issues (e.g., High/Medium/Low)** per criteria approved by the Audit Committee, recommendations, management's response/action plan, and target timelines.
  - Key elements per the Standard: (a) overview of scope/objective/approach, (b) confirmation that the audit was completed as per the Standard on Internal Audit, (c) executive summary of key observations, (d) summary of corrective actions agreed by management, (e) nature of any assurance that can be derived from the observations.
- **Concept:** Internal audit reporting is a *management communication*, not a public opinion — hence the twin-track design (assignment-level + periodic roll-up to TCWG/Audit Committee).
- **Pitfalls / exam tips:** Don't confuse this with SA 260 (statutory auditor's communication with TCWG) — SIA 370 governs the *internal* auditor's own reporting cadence, distinct from any reliance the external auditor separately places on it under SA 610.

---

### 9. Follow-Up & Action Taken Report (ATR)

- **Key formula(s)/rule(s):**
  - The **Chief Internal Auditor (ChIA)** is responsible for continuously monitoring closure of **Prior Audit Issues (PAI)** — responsibility to *implement* action plans rests with **management**, but responsibility to *monitor & report* (via the **Action Taken Report**) rests with Internal Audit.
  - Typical ATR contents: reference to the earlier reported issue, the implementation action agreed by management with a target date, current status (Implemented / Not Implemented), residual risk rating for unimplemented items, ageing of long-pending findings, and any critical finding needing immediate action.
- **Concept:** Closes the loop of the audit cycle — ensures recommendations aren't left on paper.
- **Pitfalls / exam tips:** If management has not acted within a reasonable time, the internal auditor must **draw management's attention**; where management disagrees or only partly implements a recommendation, the internal auditor should ascertain and report the reasons.

---

### 10. Internal Audit vs External (Statutory) Audit & Their Relationship

- **Key formula(s)/rule(s):**
  - There is **significant overlap** between IA and EA work since both review the accounting system/IC and examine financial & operating information — hence the external auditor's work on IA under **SA 610** is important.
  - The external auditor is obligated to **examine the scope and effectiveness of the internal audit function** — its staffing, qualifications, powers, and the degree of independence/status the IA enjoys in the organisation — as inputs to determining the nature, timing & extent (NTE) of the external auditor's own procedures.
- **Definitions:**

| Basis | Internal Audit | External (Statutory) Audit |
|---|---|---|
| Performed by | In-house IA function, or an external body engaged by management | Independent body, not part of the organisation |
| Examination focus | Operational efficiency of the organisation | Accuracy & validity (true & fair view) of Financial Statements |
| Appointment by | Audit Committee / Board of Directors | Members (shareholders) |
| Users of report | Top management & (indirectly) the statutory auditor | All stakeholders |
| Nature of reporting | On weaknesses of ICs and effectiveness of operational activities | On truth & fairness of Financial Statements |
| Status of auditor | Could be an employee of the company | Cannot be an employee of the company |

- **Concept:** Internal audit is a control tool serving management; external audit is a statutory assurance service serving shareholders/stakeholders — SA 610 is the bridge that lets the latter rely on the former without diluting the sole responsibility for the audit opinion.
- **Pitfalls / exam tips:** "Status of auditor" is the most commonly tested row — internal auditor **can** be an employee; statutory auditor **can never** be an employee of the auditee (independence requirement under the Companies Act/Code of Ethics).

---

### 11. Internal Audit as a Management Function; Audit Trail

- **Key formula(s)/rule(s):**
  - Management performs 5 general functions: **planning, organising, staffing, directing (leading) and controlling**; planning/organising/staffing/directing help *create and grow* stakeholder wealth, while controlling helps *preserve* it — Internal Audit is an important element of the **controlling** function.
  - **Audit Trail:** every company using accounting software for maintaining its books of account must use software that has a feature of recording an **audit trail of each transaction**, creating an **edit log** of each change made, and ensuring the audit trail feature **cannot be disabled** — mandatory for financial years commencing on or after **1 April 2023** under the (thrice-deferred) proviso to **Rule 3(1), Companies (Accounts) Rules, 2014**.
  - Illustrative audit-trail controls the auditor evaluates: feature not disabled/deactivated; access to the audit trail (and its backups) is restricted with access logs maintained; configuration changes to the audit trail are authorised and logged; User IDs are unique (not shared); periodic backups of audit trails are retained per the statutory retention period.
- **Concept:** Audit trail (edit log) is the visible trail of evidence linking reported figures back to their original source transaction — auditors must specifically evaluate whether this IC was functional and undisabled throughout the year (also reported on under **CARO 2020, Clause 3(f)**).
- **Pitfalls / exam tips:** Do not describe the audit-trail requirement only as an "IT control" — it is a **statutory books-of-account requirement** under the Companies Act framework, separately reported on by the statutory auditor under CARO.

---

### 12. SA 610 (Revised) — Scope, Objectives & Definitions

- **Key formula(s)/rule(s):**
  - Sole responsibility for the audit opinion always rests with the **External Auditor (EA)** — using IA's work never dilutes this.
  - The external auditor must obtain **sufficient appropriate audit evidence (SAAE)** that the work of the Internal Audit Function, or of internal auditors providing direct assistance, is **adequate for the purposes of the audit**.
  - Scope of SA 610 (Revised) covers two situations: (a) using the work of the **Internal Audit Function** in obtaining audit evidence, and (b) using **internal auditors to provide direct assistance** under the direction, supervision and review (**DSR**) of the external auditor.
  - **SA 610 does not apply** if the entity has no internal audit function/internal auditor.
- **Concept:** SA 610 (Revised) is the governing Standard on Auditing whenever the statutory/external auditor wishes to place reliance on, or borrow manpower from, the entity's internal audit function.
- **Definitions:**

| Term | Meaning |
|---|---|
| Internal Audit Function | A function of the entity performing assurance & consulting activities to evaluate/improve the effectiveness of the entity's governance, risk management & internal controls (GRC). |
| Direct Assistance | Use of internal auditors to perform audit procedures under the direction, supervision and review (DSR) of the external auditor. |

- **Pitfalls / exam tips:** Objectives of the auditor under SA 610 are threefold: (1) determine whether the work of the IA function, or direct assistance of internal auditors, can be used at all; (2) if using the IA function's work, determine whether that work is adequate for audit purposes; (3) if using internal auditors for direct assistance, direct, supervise and review their work.

---

### 13. SA 610 (Revised) — Using the Work of the Internal Audit Function

- **Key formula(s)/rule(s):** Three criteria to **evaluate whether the IA function's work can be used at all**:
  1. Extent to which the IA function's **organisational status** and relevant policies & procedures support the **objectivity** of internal auditors.
  2. **Level of competence** of the IA function.
  3. Whether the IA function applies a **systematic and disciplined approach**, including quality control.
- Factors determining the **nature & extent of use** of the IA function's work (less IA reliance / more direct EA work when):
  - (a) more judgment is involved in planning/performing audit procedures and evaluating evidence gathered;
  - (b) the assessed **risk of material misstatement (RoMM)** at the assertion level is higher — with special consideration for **significant risks**;
  - (c) the IA function's organisational status/P&P less adequately support objectivity; and
  - (d) the level of competence of the IA function is lower.
  - The external auditor must make **all significant judgments** in the audit and must be **sufficiently involved** in the audit overall; must **communicate with TCWG** how the use of the IA function's work was planned, as part of sharing the planned scope & timing of the audit.
  - Illustrative types of IA function work that **can** be used: testing operating effectiveness of controls; substantive procedures involving limited judgment; observation of inventory counts; tracing transactions through the information system relevant to financial reporting; testing compliance with regulatory requirements; and (subject to SA 600) audits/reviews of non-significant subsidiaries' financial information.
  - Before using the work: **discuss and coordinate** the planned use with the IA function; **read** its reports relevant to the work to be used, to understand the nature/extent of procedures performed and findings; then perform **sufficient audit procedures on the body of work as a whole** to evaluate whether it was properly planned, performed, supervised, reviewed & documented, whether SAAE was obtained to draw reasonable conclusions, and whether conclusions/reports are consistent with the results of the work performed.
  - The external auditor must **re-evaluate**, as the audit progresses, whether the conclusions about the IA function and the planned NTE of reliance remain appropriate.
- **Concept:** This is a graduated reliance model — more judgment/risk ⇒ less reliance on IA and more direct EA testing; the reverse holds when IA is more objective and competent.
- **Pitfalls / exam tips:** The external auditor **cannot** simply adopt IA's conclusions — SA 610 requires the EA to independently test the *adequacy* of IA's work (re-perform/observe a sample), not merely read the IA report.

---

### 14. SA 610 (Revised) — Using Internal Auditors to Provide Direct Assistance

- **Key formula(s)/rule(s):**
  - The external auditor **may use** internal auditors to provide direct assistance, **if not prohibited** by law/regulation, after evaluating the **existence and significance of threats to objectivity** and the **level of competence** of the specific internal auditors concerned.
  - Evaluating threats to objectivity must include **inquiry of the internal auditors** regarding interests and relationships that may create a threat to their objectivity.
  - ⚠️ VERIFY — the OCR's detailed list of "factors to be considered while evaluating the existence & significance of threats to objectivity of the Internal Auditor" is illegible ("[Unreadable]") in the source; per SA 610 (Revised), such factors generally include threats arising from self-review, familiarity, or undue reliance on management, and whether the IA function's policies/rotation practices safeguard objectivity — confirm the complete factor-list against the ICAI SA 610 (Revised) text before using it verbatim in an answer.
  - Even where competence/objectivity are adequate, the external auditor must **not** use internal auditors for direct assistance on procedures that: (a) involve making significant judgments in the audit; (b) relate to higher assessed RoMM where more than limited judgment is required; (c) relate to work the internal auditor has been/will be involved in reporting to management/TCWG; or (d) relate to the external auditor's own decisions about the IA function's use under SA 610.
  - Before direct assistance begins, the external auditor obtains **written agreement**: from an **authorised representative of the entity**, that internal auditors will be allowed to follow the external auditor's instructions and that the entity will not intervene in the work the internal auditor performs for the external auditor; and from the **internal auditors themselves**, that they will keep specified matters confidential as instructed and inform the external auditor of any threat to their objectivity.
  - The external auditor must **direct, supervise and review** the work performed by internal auditors on the engagement (consistent with SA 220 principles for engagement team members).
- **Concept:** Direct assistance effectively "deputises" internal auditors as extra hands for the external audit team — but only within a tightly ring-fenced set of lower-judgment procedures, and always under the EA's DSR.
- **Pitfalls / exam tips:** A frequent case-study twist: internal auditors cannot be used for direct assistance on **related-party** transactions, **going concern**, or **significant risk areas** — these require more-than-limited judgment and fall within the prohibited list above.

---

### References

1. Companies Act, 2013 — Section 138 (Internal Audit).
2. Companies (Accounts) Rules, 2014 — Rule 13 (class of companies required to appoint internal auditor) and the proviso to Rule 3(1) (accounting software audit-trail requirement, effective FY 2023-24 onward).
3. Standards on Auditing (SAs) as issued by ICAI — SA 610 (Revised), "Using the Work of Internal Auditors."
4. Companies (Auditor's Report) Order, 2020 (CARO 2020) — Clause 3(f) (audit trail) and Clause 3(xiv) (internal audit system), referenced for cross-linkage with statutory reporting.
5. Domain/professional knowledge of ICAI's Standards on Internal Audit (SIA) framework issued by the Internal Audit Standards Board, used to reconstruct the two-stage reporting content (flagged ⚠️ VERIFY above for the exact SIA number/title, as this session's web-verification budget was unavailable).

## 09. Due Diligence, Forensic Accounting & Investigation
> **Where it fits:** these are three *non-statutory-audit* assurance/consulting engagements a Chartered Accountant is frequently engaged for — DD before a deal, forensic accounting when fraud/dispute is suspected, and investigation (often statutory, under the Companies Act, 2013) when an authority orders a probe into a company's affairs; none of them results in a "true & fair" opinion the way a statutory audit does.

### Due Diligence — Meaning, Objective & Nature
- **Key formula(s)/rule(s):**
  - Due diligence = the analysis and risk assessment of a proposed business transaction, carried out **before** acquiring a controlling interest in a company, to confirm business/financial conditions of the target; it equally applies to a recommendation for investment or advancing a loan/credit.
  - **Who can perform DD:** any person / any professional the acquirer chooses to engage — DD is **not restricted to a Chartered Accountant** and is **not governed by a Standard on Auditing**, unlike a statutory audit.
  - DD is described as "the care that a reasonable person should exercise before entering into an agreement with another party" — i.e., a standard of prudence, not a statutory opinion.
- **Concept:** DD is a fact-confirmation exercise for a proposed transaction (M&A, investment, lending) — it tells the acquirer what it is buying/lending against, not whether the target's financial statements give a true and fair view.
- **Pitfalls / exam tips:**
  - Classic MCQ trap: "Only a CA can conduct due diligence" — **False**; any competent person can.
  - Do not confuse DD's output with an audit opinion — DD produces a **report of findings/facts**, never a true-and-fair opinion.
  - Areas commonly tested for where DD is undertaken: corporate restructuring (mergers/acquisitions/demergers), venture capital/private equity financing, public offerings (IPO/FPO).

### Due Diligence vs. Audit vs. Investigation
- **Key formula(s)/rule(s):**

| Aspect | Statutory Audit | Due Diligence | Investigation |
|---|---|---|---|
| Objective | Independent examination of FS to **express an opinion** on true & fair view | Confirm material facts of a **prospective** business opportunity/transaction | Establish a specific fact or suspected wrongdoing for a defined purpose |
| Who performs | Only a qualified Chartered Accountant (statutory) | Any person/professional engaged by the acquirer | Inspector/professional appointed under statute or by the client for a specific probe |
| Governing framework | Standards on Auditing (SAs), Companies Act audit provisions | No mandatory SA; ICAI Technical Guides for guidance | Companies Act, 2013 provisions (ss. 210–229) where statutory; FAIS where a CA conducts it |
| Nature of report | Opinion (unmodified/modified) | Findings/observations report — no opinion | Findings of fact, often used as evidence |

- **Concept:** the three engagements sit on a spectrum — audit is recurring & opinion-based; DD is transaction-specific & fact-based; investigation is trigger-specific (fraud/mismanagement suspicion) & evidence-based.
- **Pitfalls / exam tips:** examiners frequently ask a "distinguish between" question on this triad — always anchor the answer on **objective, who can perform, governing framework, and nature of report**.

### Reasons for Due Diligence
- **Key formula(s)/rule(s):** (why DD is undertaken — descriptive, list as-is)
  - To identify potential "deal-killer" defects in the target and avoid a bad business transaction.
  - To verify that the transaction complies with the acquirer's investment/acquisition criteria.
  - To confirm that the business is what it appears to be.
  - To gain information useful for valuing assets, negotiating price concessions, and drafting representations & warranties in the transaction agreement.
- **Concept:** DD exists to protect the acquirer/investor/lender from unpleasant surprises (financial, legal, operational) after the deal is signed.
- **Pitfalls / exam tips:** a descriptive question ("Why is due diligence undertaken?") expects at least 3–4 of the above points with a one-line explanation each.

### Financial Due Diligence — Review Checklist
- **Key formula(s)/rule(s):** areas typically reviewed in a Financial DD:
  - Accounting policies — check appropriateness and whether changed in the recent past (policy changes can flatter results).
  - Review of financial statements — whether prepared per the applicable financial reporting framework/AS, and treatment of extraordinary/one-off items (adjust for normalisation).
  - Is the company able to honour its commitments to trade payables, banks, government dues & other stakeholders?
  - How well does the company perform vis-à-vis budget/industry benchmarks?
  - Are funds lying idle, or is the company deploying funds to reap maximum benefit?
  - What is the investment pattern of the company, and are those investments easily realisable?
  - Financial projections — for the next 5 years, with stated assumptions & workings.
  - Management & employees — retention of the workforce, impact of pending labour litigation, ESOPs/sales incentives, and key employees who may not continue post-acquisition.
  - Statutory compliance — non-compliance may crystallise into penalties post-acquisition.
- **Concept:** Financial DD goes beyond the audited numbers to test whether reported profit is **sustainable and normalised**, and whether off-balance-sheet risks exist.
- **Pitfalls / exam tips:** frequently tested together with the "Hidden Liabilities" list below in a single practical/theory question.

### Hidden Liabilities — Key Checklist (High-Frequency Topic)
- **Key formula(s)/rule(s):** items that may not appear (or appear adequately) in the target's books and must specifically be probed in DD:
  - Contingent liabilities from show-cause notices that have not yet matured into a demand — may be more material than disclosed.
  - Letters of comfort given to banks/financial institutions — since these are not guarantees, they may not be reflected in the books.
  - Tax liabilities under direct and indirect taxes not yet crystallised (e.g., pending assessments/appeals).
  - Long-pending sales tax / GST assessments.
  - Pending final assessment of customs duty where only a provisional assessment has been completed.
  - Agreements to buy back shares at a stated price.
  - Future lease liabilities.
  - Unresolved labour litigation and pending labour wage-settlement claims.
  - Liabilities/indemnities assumed on sale of erstwhile subsidiaries/businesses (the company may have agreed to indemnify the buyer for pre-transfer liabilities — not reflected in its own books).
  - Product & other liability claims — warranty claims, product returns/discounts, liquidated damages for late deliveries, and related litigation.
  - Environmental claims/third-party claims not provided for.
  - Incorrect or outdated actuarial/gratuity valuations.
- **Concept:** these are the "off-book" exposures a target may not disclose voluntarily — the DD team must actively probe for them (management inquiry, legal confirmations, bank confirmations) rather than rely only on the balance sheet.
- **Pitfalls / exam tips:** this list is a favourite 8–10 marker; write it as a clean bulleted list in the exam, grouped logically (tax, legal/contractual, HR, product/environmental) for better presentation marks.

### Conducting Due Diligence — Process
- **Key formula(s)/rule(s):** broad process:
  1. Reviewing & reporting on financials submitted by the target company.
  2. Assessing the business first-hand via a site visit (where applicable).
  3. Working through the DD process to completion.
  4. Helping the acquirer prepare an offer based on the completed DD.
  - Practical tips for the DD team: start with an open mind — don't assume anything; learn by talking to experts and asking for explanations; assemble the best possible DD team (may include external DD/domain experts); talk directly to customers, business partners & employees; take calculated (not blind) risks; prepare a comprehensive report detailing compliance and substantive risks/issues found.
- **Concept:** DD is an iterative, evidence-gathering exercise culminating in a report that feeds directly into deal pricing/structuring — not a checklist ticked off in isolation.
- **Pitfalls / exam tips:** if asked "how would you conduct due diligence," structure the answer as **Plan → Site visit/first-hand assessment → Execute DD procedures → Report → Assist in offer/negotiation**.

### Forensic Accounting — Meaning & Role of the Forensic Accountant
- **Key formula(s)/rule(s):** a forensic accounting professional is typically involved in:
  1. **Fraud detection** — investigating and analysing financial evidence.
  2. **Computer/digital forensics** — developing/using computerised applications to assist in recovery, analysis & presentation of financial (digital) evidence.
  3. **Fraud prevention** — evidence collection & analysis to strengthen controls going forward.
  4. **Providing expert testimony** — assessing and presenting financial evidence, including as an expert witness before a court/tribunal.
- **Concept:** forensic accounting blends accounting, auditing and investigative skills to establish facts that will withstand scrutiny in a legal/dispute-resolution setting — the end-user of the work is often a court, arbitrator, or regulator, not a general body of shareholders.
- **Pitfalls / exam tips:** distinguish forensic accounting from a statutory audit — forensic work is **fact/fraud specific and litigation-oriented**; it does not culminate in a true-and-fair opinion.

### Forensic Investigation — Evidence, Chain of Custody & Analysis
- **Key formula(s)/rule(s):**
  - Evidence must be gathered and preserved in a stipulated time frame while keeping a **clear, unbroken chain of custody** until it is produced before the court.
  - If evidence is inconclusive, or there are gaps in the chain of custody, the evidence may be **challenged in court or rendered inadmissible**.
  - The forensic accountant must stay alert to documents being **falsified, damaged or destroyed** by the suspect(s).
  - Analysis techniques commonly used: calculating economic damages; performing present value (PV) calculations at an appropriate discount rate; summarising a large volume of transactions; using charts/graphics to explain findings; using computerised tools (spreadsheets, databases, computer-assisted analysis models).
  - Present value formula used for economic-damages calculations:
$$
PV = \frac{FV}{(1+r)^{n}}
$$
    where $FV$ = future economic loss/damage amount, $r$ = appropriate discount rate, $n$ = number of periods.
- **Concept:** unlike audit evidence (gathered to support an opinion), forensic evidence must be legally admissible — its integrity (chain of custody) is as important as its content.
- **Pitfalls / exam tips:** "chain of custody" and "inadmissibility of evidence on gaps" is a recurring conceptual question — always link admissibility to the unbroken custody trail.

### Forensic Accounting — Reporting
- **Key formula(s)/rule(s):**
  - Reporting is the **final step** of a forensic accounting engagement.
  - The report must include: findings of fraudulent activity (if any); the conclusion on the amount of loss and identification of persons involved; sections covering nature of assignment, scope, approach, limitations, findings and opinions; supporting schedules/graphics; and a discussion of how the fraudster set up the scheme and how (if at all) existing controls were circumvented.
  - **The report must be based on facts, and not on the personal opinion of the person writing it.**
- **Concept:** the forensic report is a fact-finding document meant to support legal/disciplinary action or a negotiated settlement — its credibility rests entirely on being evidence-driven.
- **Pitfalls / exam tips:** "report should be based on facts, not opinion" is a frequently quoted line in exam answers — always include it verbatim-style when asked about forensic reporting principles.

### Forensic Accounting & Investigation Standards (FAIS) — Report Contents
- **Key formula(s)/rule(s):**
  - ⚠️ VERIFY — ICAI's Digital Accounting and Assurance Board (DAAB) has issued a set of Forensic Accounting and Investigation Standards (FAIS) applicable to members conducting forensic accounting and investigation engagements (widely cited effective date: **1 July 2023**); the exact standard numbering/count should be cross-checked against the current ICAI FAIS publication before quoting specific standard numbers in the exam.
  - There is **no single mandated format** for a forensic/investigation report, but where the engagement terms/stakeholders mandate a format, the report must be issued per those requirements. Key elements ordinarily expected in the report:
    - Title, addressee(s) and distribution list (if any).
    - Scope and objectives of the assignment.
    - Approach and broad work procedures undertaken.
    - Executive summary of results, covering the important aspects and essence of the findings.
    - Reference to use of an expert, where applicable.
    - A statement of whether the assignment was conducted per FAIS (or applicable standards), and disclosure of any material departure.
    - List of findings, supported by key evidence, sources of evidence and other relevant matter.
    - Assumptions, limitations & disclaimers of the assignment.
    - Conclusions (if any) drawn from the assessment.
- **Concept:** FAIS brings the same discipline to forensic engagements that SAs bring to statutory audits — a documented, evidence-referenced, standard-compliant report.
- **Pitfalls / exam tips:** if the exam names a specific FAIS number, treat the number itself with caution unless independently confirmed — the *structure/contents of the report* above is the safer, well-established answer to lean on.

### Investigation under the Companies Act, 2013
- **Key formula(s)/rule(s):**
  - ⚠️ VERIFY — Investigation into the affairs of a company can be ordered by the Central Government under **Section 210**, Companies Act 2013 (on Registrar's/inspector's report, on a company's special resolution, or in the public interest).
  - ⚠️ VERIFY — **Section 211** establishes the **Serious Fraud Investigation Office (SFIO)**; **Section 212** deals with investigation by SFIO into a company's affairs, which becomes mandatory in specified circumstances (e.g., Central Government direction, report under s. 208, or public interest) and, once assigned to SFIO, no other investigating agency may proceed with a parallel probe into the same matter.
  - ⚠️ VERIFY — **Section 213** empowers the Tribunal (NCLT) to order an investigation into a company's affairs on application by members (commonly cited threshold: not less than 100 members, or members holding not less than one-tenth of total voting power for a company with share capital; not less than one-fifth of persons on the register for a company without share capital) or by any other person, where the Tribunal is satisfied of circumstances suggesting fraud, oppression, or non-disclosure of full information to members — this threshold figure should be cross-checked against the bare Act before being quoted as an exact number in the exam.
  - ⚠️ VERIFY — **Section 216** empowers the Central Government to appoint inspectors to investigate and report on the **true persons** who are or have been financially interested in, or in control of, the company's policy — i.e., investigation of beneficial ownership.
- **Concept:** statutory investigation is a coercive, authority-driven fact-finding power distinct from DD/forensic engagements undertaken voluntarily by a client — its findings can trigger prosecution, winding up, or other regulatory action.
- **Pitfalls / exam tips:** because the exact section numbers/member-thresholds are easy to mix up with the oppression-and-mismanagement provisions (s. 241–246), always double-check the specific section before citing a number in a written answer; focus theory answers on **who can order it, who conducts it (SFIO/inspector), and the consequence (report to Central Government/Tribunal)** rather than memorising every numeric threshold.

### Definitions

| Term | Meaning |
|---|---|
| Due Diligence | Analysis/risk assessment of a proposed transaction undertaken before acquiring a controlling interest, investment, or advancing a loan, to confirm the target's business/financial conditions |
| Hidden Liabilities | Obligations (contingent, tax, legal, contractual) not adequately reflected in the target's books, which DD must specifically uncover |
| Forensic Accounting | Application of accounting, auditing & investigative skills to establish facts for use in a legal/dispute-resolution context |
| Chain of Custody | The unbroken, documented trail of possession/handling of evidence from collection to production in court, essential for admissibility |
| SFIO | Serious Fraud Investigation Office — statutory body under the Companies Act, 2013 for investigating serious corporate frauds |
| FAIS | Forensic Accounting and Investigation Standards issued by ICAI's Digital Accounting and Assurance Board, governing CA members' forensic engagements |

### References
1. ICAI Study Material — Advanced Auditing & Professional Ethics — Chapter on Due Diligence, Forensic Accounting & Investigation (basis for DD meaning, reasons, hidden liabilities checklist, forensic reporting principles).
2. Companies Act, 2013 — Sections 210–216 (Investigation into affairs of a company; SFIO) — cited from domain knowledge; exact section text/thresholds should be cross-checked against the bare Act (⚠️ web verification unavailable this session — search budget exhausted).
3. ICAI Forensic Accounting and Investigation Standards (FAIS), Digital Accounting and Assurance Board — cited from domain knowledge for the report-content structure; exact standard numbers/effective date should be cross-checked against the current ICAI publication (⚠️ web verification unavailable this session).

## 10. SA 800 Series (SA 800/805/810 - Special Purpose & Single FS Audits)
> **Where it fits:** These three SAs adapt the "general" audit/reporting framework (SA 200–720) to three special situations — audits under a Special Purpose Framework (SA 800), audits of a single financial statement or a specific element/account/item (SA 805), and engagements to report on summary financial statements derived from already-audited FS (SA 810).

### SA 800 — Special Considerations: Audits of FS Prepared as per Special Purpose Frameworks (SPF)

- **Key formula(s)/rule(s):**
  - No numeric formula; the standard turns on a classification rule:
$$
\text{FRF} =
\begin{cases}
\text{General Purpose Framework} & \text{if designed to meet common FS needs of a wide range of users}\\
\text{Special Purpose Framework (SPF)} & \text{if designed to meet FS needs of specific users}
\end{cases}
$$
  - Acceptability of the SPF (Applicable Financial Reporting Framework, AFRF) is judged under **SA 210**, with the **information needs of the intended users** as the key determining factor for a SPF (unlike GPFS, where common needs of a wide range of users govern).

- **Concept:** SA 800 applies whenever a complete set of FS (including related notes) is prepared under a framework designed for specific users rather than the general public — e.g., cash basis / cash-flow-only statements for creditors, FR provisions prescribed by a regulator, or FR provisions of a contract (bond indenture, loan agreement, project grant). SA 200 still requires compliance with all relevant ethical requirements and all SAs relevant to the engagement; SA 800 only layers special considerations on top.

- **Examples of SPFs (learn as a list):**
  - Cash basis of accounting / cash flow information required for creditors.
  - FR provisions established by a regulator to meet regulatory requirements.
  - FR provisions of a contract (e.g., bond indenture, loan agreement, project grant).

- **Special considerations while planning/performing the audit:**
  - **SA 320 (Materiality):** judged with reference to the financial information needs of the *intended users* (not "common" needs as in GPFS).
  - **SA 315:** obtain understanding of significant interpretations of contract terms made by management where FS are prepared per a contract; an interpretation is "significant" if another reasonable interpretation would have produced a material difference. A contractually agreed correction/adjustment threshold does **not** relieve the auditor of determining materiality under SA 320.
  - **SA 260 (Communication with TCWG):** the person(s) overseeing SPFS preparation may differ from the TCWG responsible for the entity's GPFS.
  - **SA 700 / SA 706 / SA 701 / SA 720:** apply as in a normal audit — evaluate whether FS adequately describe the AFRF (and, if per contract, significant interpretations of it); if KAMs are communicated, SA 701 applies in its entirety; if the SPFS report is meant to inform owners/similar stakeholders, SA 720 (Other Information) applies in full.

- **Reporting — mandatory alert:**
  - Auditor's report must include an **Emphasis of Matter (EOM)** paragraph, under a heading that includes the term "Emphasis of Matter" (per **SA 706**), stating that: (i) the FS are prepared per an SPF, and (ii) therefore may not be suitable for another purpose.
  - Where use/distribution is meant to be restricted to specific users, the EOM may be expanded / a **Restriction on Distribution or Use** paragraph added, with the heading modified accordingly.

- **Pitfalls / exam tips:**
  - Do not confuse "Special Purpose Framework" (a type of AFRF) with "Special Purpose Financial Statements" (SPFS) — SPFS are FS *prepared under* an SPF.
  - The EOM on basis of accounting is **mandatory**, not optional, whenever SPFS may be used/placed on public record for purposes beyond the original intent.
  - Materiality basis (intended users, not "common" users) is a favourite conceptual MCQ trap.

- **Definitions:**

| Term | Meaning |
|---|---|
| SPF | A Financial Reporting Framework designed to meet the financial information needs of specific users (may be fair presentation or compliance framework) |
| SPFS | Complete set of FS (with related notes) prepared as per an SPF |
| GPFS | FS prepared to meet common financial information needs of a wide range of users |
| AFRF | Applicable Financial Reporting Framework adopted by management (and, where appropriate, TCWG) in preparing FS |

---

### SA 805 — Special Considerations: Audits of Single FS and Specific Elements, Accounts or Items of a FS (SEFS)

- **Key formula(s)/rule(s) — the "adverse/disclaimer carry-over" rule (high-yield):**
  - If the auditor expresses an **adverse opinion or disclaimer of opinion** on the entity's complete set of FS, **SA 705 does not permit** an unmodified opinion on a single FS or SEFS in the *same* auditor's report (it would contradict the adverse/disclaimer).
  - **Exception** — an unmodified opinion on a *specific element* may still be given (in a separate report) **only if all three conditions are met**:
    1. It is **not prohibited by law or regulation**;
    2. That opinion is expressed in an auditor's report that is **not published together with** the adverse/disclaimer report; **and**
    3. The specific element **does not constitute a major portion** of the entity's complete set of FS.
  - **No such exception for a single financial statement** — a single FS (e.g., the Balance Sheet or the Statement of P&L alone) is deemed to constitute a **major portion** of the complete set of FS, so an unmodified opinion on it can never be given if the complete-set opinion is adverse/disclaimed — even if published separately.
  - **Special carve-out:** a disclaimer of opinion on results of operations & cash flows *combined with* an unmodified opinion on the state of affairs (Balance Sheet) **is permitted**, because the disclaimer relates only to the P&L/Cash Flow Statement and not to the FS "as a whole."

- **Concept:** SA 805 governs audits of (a) a **single financial statement** (e.g., Cash Flow Statement alone) or (b) a **Specific Element, Account or Item of an FS (SEFS)** — e.g., receivables, allowance for doubtful debts, inventory, schedule of net tangible assets — each including related notes. Note: SA 805 does **not** apply to a component auditor's report issued at the request of the principal (group) auditor for a consolidated FS audit (that is governed by SA 600).

- **Application of SAs / practicability:**
  - **SA 200** requires compliance with all relevant SAs regardless of whether the auditor also audits the complete set of FS. If not engaged for the complete set, the auditor must determine whether such compliance is **practicable**.
  - Practicability may be reduced because the auditor (i) lacks the same understanding of the entity/environment/IC as an auditor of the complete FS, and (ii) lacks audit evidence on the general quality of accounting records — so more corroborative evidence may be needed.
  - Some SAs may demand **disproportionate effort** for a single element (e.g., full SA 570 going-concern procedures just for an audit of receivables) — if compliance isn't practicable, discuss with management whether **another type of engagement** is more suitable.
  - **SA 210** governs acceptability of the framework — must give adequate disclosures so intended users understand the element/FS and the effect of material transactions/events on it.
  - Even for a SEFS audit, **SA 240 (fraud), SA 550 (related parties) and SA 570 (going concern)** remain relevant — an element could be misstated by fraud, related-party effects, or an incorrect going-concern basis.
  - **Materiality** for the SFS/SEFS may be **lower** than materiality for the complete set of FS, affecting NTE of procedures and evaluation of uncorrected misstatements.
  - **Audit evidence:** where both a complete-set audit and an SFS/SEFS audit are performed, evidence from the complete-set audit may be used — but SAAE must still support the SFS/SEFS opinion specifically ("inter-relation" of FS items may require additional procedures).

- **Form of opinion:** Consider (per SA 210 agreed terms) whether "presents fairly, in all material respects" / "true and fair view" is appropriate, given whether the AFRF was designed for a complete set of FS or explicitly addresses single-FS/element presentation, and whether full compliance + necessary additional disclosures/departures are achieved.

- **Reporting — special points:**
  - **Separate opinion:** if reporting on SFS/SEFS alongside the complete set of FS, express a **separate opinion for each engagement**.
  - **Differentiation:** the auditor must ensure the SFS/SEFS presentation is clearly differentiated from the complete set of FS, and the opinion likewise differentiated — if not, ask management to rectify and **do not issue** the report until satisfied.
  - **Implications of complete-set report matters:** where the complete-set report has a modified opinion / EOM / OM / MURG / uncorrected misstatement of Other Information, judgment is needed on implications for the SFS/SEFS report — factors include nature and pervasiveness of the matter, differences between the two AFRFs, differing periods covered, and time elapsed since the complete-set report date.
  - Even where there's **no implication**, the auditor **may still refer** (via an Other Matter paragraph per SA 706) to the complete-set report, e.g., cross-referencing an MURG section.

- **Pitfalls / exam tips:**
  - The "major portion" rule (single FS = always major portion; specific element = may or may not be) is the most frequently tested numeric/qualitative distinction in this SA — do not mix up the two.
  - Remember all **three** conditions of the exception together — dropping any one is a common trap in MCQs.
  - "SA 805 doesn't apply to component auditor's report" is a standalone one-liner often asked directly.

- **Definitions:**

| Term | Meaning |
|---|---|
| Single Financial Statement (SFS) | One statement out of what would otherwise be a complete set, e.g., a Cash Flow Statement alone |
| SEFS | An element, account or item of a FS (e.g., trade receivables, inventory, allowance for doubtful debts), including related notes |
| Major portion | Qualitative threshold — no fixed %; a single FS is *deemed* to always be a major portion; a specific element must be assessed case-by-case |

---

### SA 810 — Engagements to Report on Summary Financial Statements

- **Key formula(s)/rule(s) — date of report:**
  - Auditor's report on summary FS shall be dated **no earlier than the later of**:
$$
\text{Date of report on summary FS} \;\geq\; \max\big(\text{Date SAAE obtained (incl. evidence mgmt/those with authority have accepted responsibility)},\; \text{Date of A/R on audited FS}\big)
$$
  - **Form of unmodified opinion** — one of exactly two prescribed phrases:
    1. "the summary financial statements are **consistent, in all material respects**, with the audited financial statements, in accordance with [the applied criteria]"; **or**
    2. "the summary financial statements are a **fair summary** of the audited financial statements, in accordance with [the applied criteria]."
  - **Modified opinion rule:** if summary FS are **not** consistent with / not a fair summary of the audited FS, as per applied criteria, and management refuses to make necessary corrections → auditor expresses an **Adverse Opinion** on the summary FS.

- **Concept:** Summary FS present historical financial information derived from audited FS, in less detail, but still giving a structured picture of the entity's financial position/performance. SA 810 lets an auditor separately opine on such a summary, provided it is derived from FS the *same* auditor has already audited under the SAs.

- **Engagement acceptance conditions:**
  - Auditor shall **ordinarily accept only if also engaged to audit (under SAs) the FS from which the summary is derived** — otherwise the auditor lacks the necessary knowledge to report on the summary.
  - **Applied criteria** (criteria management used to prepare the summary FS) must be assessed for **acceptability** — factors: nature of the entity, purpose of summary FS, information needs of intended users, and whether the criteria will yield summary FS that are not misleading. Criteria set by a standard-setter/law-regulation may be **presumed acceptable**.
  - If criteria are unacceptable (or agreement can't be reached) → **do not accept** unless required by law/regulation, in which case: the report must **not** state that the engagement was conducted per SA 810, and this fact must be referenced in the terms of engagement.
  - **Agreement with management** must cover: (a) responsibility for preparing summary FS per applied criteria; (b) making the audited FS available to intended users without undue difficulty (or describing the law/regulation exempting this); (c) including the auditor's report on summary FS in any document containing the summary FS; and (d) the agreed form of opinion.

- **Auditor's procedures (minimum, plus any others needed):**
  - Evaluate that summary FS adequately disclose their summarized nature and identify the audited FS.
  - Evaluate that they contain sufficient information at an appropriate level of aggregation to avoid being misleading.
  - Evaluate that they adequately disclose the applied criteria and are prepared per those criteria.
  - Evaluate that the audited FS are accessible to intended users (or, if not accompanied, that the summary clearly states where to obtain them / cites the exempting law).
  - **Recompute/agree:** compare summary FS to related information in the audited FS to confirm agreement or re-computability.

- **Report elements (SA 810 specific, beyond usual SA 700 elements):** title, addressee (evaluated for appropriateness if different from the audited-FS report), identification of the summary FS and of the audited FS, the opinion, a statement that summary FS do not contain all disclosures required by the FRF applied to the audited FS and are **not a substitute for reading the audited FS**, reference to the audited-FS report (date + fact that an unmodified opinion was expressed on it), management's responsibility for the summary FS, auditor's responsibility statement, signature with membership no., firm registration no. and UDIN, date, and place of signature.

- **Effect of matters in the audited-FS report:**
  - **Qualified opinion / EOM / OM / MURG / KAM / uncorrected misstatement of Other Information** on the audited FS, where the auditor is still satisfied the summary FS are consistent/fair summary → the summary-FS report must **state that fact and describe** the basis for qualification / the matter referred to / the uncorrected misstatement's effect.
  - **Adverse opinion or disclaimer of opinion** on the audited FS → the summary-FS report must state that fact, describe its basis, and state that **it is inappropriate to express an opinion** on the summary FS.
  - **Restriction on distribution/use or SA 800 alert** on the audited-FS report → carry a **similar restriction/alert** into the summary-FS report.
  - **Comparatives (SA 710):** if audited FS have comparatives but summary FS omit them, assess reasonableness of the omission and its effect on the summary-FS report; if comparatives were reported on by another auditor, include the SA 710 matters in the summary-FS report too.
  - **Unaudited supplementary information (SA 700 principles):** must be clearly differentiated from the summary FS; if management refuses to differentiate, state in the report that such information is not covered by it.
  - **Other information (SA 720/730 principles):** read information in any document containing the summary FS + report for material inconsistency; if found, discuss with management and pursue revision; if revision refused, consider implications for the summary-FS report.

- **Timing / subsequent events:**
  - No obligation to obtain additional audit evidence on the audited FS, or report on post-audited-FS-date events, purely because the summary-FS report is dated later — **unless** the auditor becomes aware of facts existing at the date of the audited-FS report of which they were previously unaware (then apply **SA 560** before issuing the summary-FS report).
  - If the summary-FS report is dated later than the audited-FS report, it must **state** that the summary FS and audited FS do not reflect the effects of events occurring after the date of the audited-FS report.

- **Pitfalls / exam tips:**
  - The precondition — auditor must have audited the underlying FS themselves — is an easy 1-mark MCQ; a different auditor cannot take up an SA 810 summary-FS engagement alone.
  - Memorize the **two exact unmodified-opinion phrases** ("consistent, in all material respects" vs "fair summary") — exams test verbatim recognition.
  - Adverse/disclaimer on audited FS → auditor states it is **inappropriate** to opine on summary FS (does NOT automatically mean adverse opinion on summary FS — that's reserved for the "not consistent + management won't fix" scenario).

- **Definitions:**

| Term | Meaning |
|---|---|
| Summary FS | Historical financial information derived from FS, less detailed but structured consistently with FS, of an entity's resources/obligations/changes therein |
| Applied criteria | Criteria applied by management in preparing the summary FS (may be set by a standard-setting body/law-regulation, or developed by management, e.g., industry practice) |
| SAAE | Sufficient Appropriate Audit Evidence |

### References
1. Standard on Auditing (SA) 800, "Special Considerations—Audits of Financial Statements Prepared in Accordance with Special Purpose Frameworks," ICAI (as included in the current Standards on Auditing volume applicable to CA Final).
2. Standard on Auditing (SA) 805, "Special Considerations—Audits of Single Financial Statements and Specific Elements, Accounts or Items of a Financial Statement," ICAI.
3. Standard on Auditing (SA) 810, "Engagements to Report on Summary Financial Statements," ICAI.
4. Cross-referenced SAs relied upon within the above: SA 200, SA 210, SA 260, SA 315, SA 320, SA 560, SA 570, SA 600, SA 700, SA 701, SA 705, SA 706, SA 710, SA 720.

⚠️ VERIFY — This chapter's content was reconstructed primarily from the source concept-book OCR plus standing subject-matter knowledge of SA 800/805/810; the web-search verification pass could not be completed in this session (search budget exhausted before any query ran). Before relying on this chapter for the exam, cross-check the exact wording of the two SA 810 opinion phrases and the SA 805 "major portion" exception conditions against the current ICAI SA text/study material.

## 11. Standards on Review Engagements (SRE 2400 & 2410)

> **Where it fits:** Review is a **limited assurance** engagement (lower than audit's reasonable assurance) built mainly on **inquiry + analytical procedures**; SRE 2400 covers review of historical FS by a practitioner who is *not* the entity's auditor, while SRE 2410 covers review of *interim* FS by the entity's *own* statutory auditor.

### What is "Review"? — Nature & Positioning

- **Key formula(s)/rule(s):**
  - Assurance spectrum (level of engagement risk accepted, high → low):
$$
\text{Audit (Reasonable Assurance)} \;>\; \text{Review (Limited Assurance)} \;>\; \text{No Assurance (Compilation/AUP)}
$$
  - Limited assurance = engagement risk reduced to a level **acceptable in the circumstances of the engagement, but greater than** in a reasonable assurance (audit) engagement.
  - Review relates to FS prepared on the basis of **historical financial information**, same as audit.
  - Primary evidence-gathering toolkit: **Inquiry + Analytical Procedures** (fewer procedures than audit; SAE, not SAAE in the audit sense, is the review-appropriate sufficiency test).

- **Concept:** Review provides a *negatively worded* conclusion ("nothing has come to our attention…") rather than a *positively worded* opinion ("in our opinion, the financial statements give a true and fair view…") because far less evidence is gathered than in an audit.

- **Pitfalls / exam tips:**
  - Do not confuse "limited assurance" with "no assurance" — compilation/agreed-upon-procedures engagements give **no assurance**; review gives **some (limited)** assurance.
  - A special purpose framework FS (e.g., FS required quarterly under a contract) **can** validly be reviewed under SRE 2400 even though not audited — a favourite MCQ/case-study trap (the "Roma Ltd–Dorma Ltd" pattern).

- **Definitions:**

| Term | Meaning |
|---|---|
| SAE | Sufficient & Appropriate Evidence (review-engagement evidence standard) |
| AFRE / AFRF | Applicable Financial Reporting Framework |
| Limited assurance | Assurance lower than reasonable assurance but higher than nil |

---

### SRE 2400 — Scope, Objectives & Client/Engagement Acceptance

- **Key formula(s)/rule(s) — Objectives of the practitioner:**
  - Obtain limited assurance, primarily through inquiry and analytical procedures, that FS as a whole are free from material misstatement, enabling the practitioner to state whether anything has come to their attention causing them to believe FS are **not** prepared in all material respects as per the AFRF.
  - Report on FS, and communicate, as per SRE 2400.
  - If limited assurance cannot be obtained and a modified conclusion is insufficient in the circumstances: **disclaim a conclusion** or **withdraw**, if withdrawal is possible under applicable law/regulation (L/R).
- **Rules — do NOT accept a review engagement (unless required by L/R) if practitioner is not satisfied that:**
  1. There is a **rational purpose** for the engagement (e.g., significant scope limitation exists; risk of the practitioner's name being associated with FS inappropriately; or L/R actually requires an audit, not a review).
  2. A **review** engagement (rather than audit/compilation/other service) would be appropriate in the circumstances.
  3. Relevant **ethical requirements, including independence**, will be satisfied.
  4. Preliminary understanding indicates info. needed for the review is **available and reliable**.
  5. There is **no doubt over management's integrity** likely to affect proper performance of the review.
  6. Management/TCWG will **not impose a scope limitation** that would result in a disclaimer of conclusion.

- **Concept:** These are essentially "gatekeeper" conditions mirroring SA 210 (audit) logic, adapted to review — the practitioner must be satisfied the engagement is meaningful and performable before accepting it.

- **Pitfalls / exam tips:** Frequently tested as "should the practitioner accept this review engagement" case studies — check each of the 6 conditions systematically; a scope limitation known *before* acceptance is a bar to acceptance, but one arising *after* acceptance triggers a different response (discuss → resolve/continue/report — see Preconditions below).

---

### Preconditions for Accepting & Agreeing Terms of a Review Engagement

- **Key formula(s)/rule(s) — Preconditions (mirrors SA 210 for audit):**
  - Determine that the **FRF applied is acceptable** (for special purpose FS, also understand the purpose and intended users).
  - Obtain **management's agreement** that it acknowledges and understands its responsibility:
    1. For preparation of FS as per the AFRF, including fair presentation.
    2. For such internal control as is necessary to enable FS free from material misstatement (fraud or error).
    3. To provide the practitioner with: (a) access to all information relevant to FS preparation, (b) any additional information requested, and (c) unrestricted access to persons within the entity necessary to obtain evidence.
  - If not satisfied on any of the above **before** acceptance → discuss with management/TCWG; if not resolved, **do not accept** the engagement (unless required by L/R).
  - If not satisfied **after** acceptance → discuss with management/TCWG and determine (a) whether the matter can be resolved, (b) whether it remains appropriate to continue, and (c) whether/how to communicate the matter in the report.
- **Rules — Agreeing terms of engagement:**
  - Terms must be agreed with management/TCWG **before** performing the engagement and recorded in an **engagement letter** or other written agreement.
  - On recurring engagements, evaluate whether circumstances require revising terms; remind management/TCWG of existing terms.
  - Do not agree to a change in terms **without reasonable justification**; if the change is to a *lower*-assurance engagement, assess whether reasonable justification exists.
  - If terms change during the engagement, practitioner and management/TCWG must agree and record the **new terms**.

- **Concept:** Preconditions ensure the practitioner is not accepting an engagement on an unacceptable framework or without management cooperation — same philosophy as SA 210 for audits.

- **Pitfalls / exam tips:** Note the phrase "Same as SA 210" appears repeatedly in coaching material — useful memory hook, but write the review-specific wording (FS, not just financial statements audit) in the exam.

---

### Performing the Review — Materiality, Understanding, Inquiry & Analytical Procedures

- **Key formula(s)/rule(s) — 5-step overview after acceptance:**
  1. Determine **materiality** for the FS as a whole and apply it in designing procedures and evaluating results; **revise** materiality on becoming aware of information that would have caused a different determination initially.
  2. Obtain an **understanding of the entity and its environment and the AFRF** to identify areas of possible material misstatement (basis for designing procedures).
  3. Design and perform **Inquiry** and **Analytical Procedures**.
  4. Perform procedures to address **specific circumstances** (related parties, fraud/NOCLAR, going concern, use of others' work).
  5. Perform **other procedures**, if necessary, depending on circumstances (professional judgment).
  - Materiality judgment for a review is made on the **same basis** as for an audit, regardless of the lower level of assurance being obtained.

- **Concept — Inquiry:** Seeking information from management and others within the entity on matters such as fraud, related parties, accounting estimates, subsequent events, and going concern; evaluating the reasonableness/consistency of management's responses (applying professional scepticism) is integral to the process.

- **Concept — Analytical Procedures:** Used to (a) obtain/update understanding of the entity, (b) identify inconsistencies or unusual variances from expected trends, (c) act as an additional procedure when the FS may be materially misstated, and (d) corroborate evidence already obtained from inquiry.

- **Pitfalls / exam tips:**
  - Mnemonic in the source notes for why inquiry/analytical procedures matter: management's **P**ast history, **R**easons, **A**bility (evidence about management **intent**) — apply professional scepticism throughout.
  - A practitioner becoming aware of, say, a significant contract may read the contract as an *additional* procedure — this does **not** change the objective of obtaining only limited (not reasonable) assurance.

---

### Procedures for Specific Circumstances

- **Key formula(s)/rule(s):**
  - **Related parties:** Remain alert to RP relationships/transactions management has not identified/disclosed; for significant transactions outside the normal course of business, inquire about nature, possible RP involvement, and business rationale.
  - **Fraud & NOCLAR:** On any indication, communicate to senior management/TCWG and request management's assessment of the effect on FS; consider the effect on the practitioner's conclusion and report, and any responsibility to report to a party outside the entity.
  - **Going concern:** If events/conditions cast significant doubt on GC, inquire about management's plans and their feasibility, and evaluate whether responses provide sufficient basis to continue using the GC basis or to conclude FS are materially misstated regarding GC.
  - **Use of work of others / group review:** May use the work of an expert (in a field other than accounting/assurance) after checking it is adequate; for a **group** review engagement, direct the nature, timing and extent (NTE) of procedures to achieve the review objective but for the **group** FS.
- **Rule — Additional procedures when practitioner suspects material misstatement:**
  - Design and perform additional procedures until able to either (a) **conclude** the matter is not likely to cause material misstatement, or (b) **determine** it does cause material misstatement.
  - Additional procedures may be more detailed/focused inquiry & analytical procedures, or other procedures such as substantive tests of detail or external confirmations.
  - If unable to reach (a) or (b) → a **scope limitation** exists and the practitioner is **unable to form an unmodified conclusion**.

- **Concept:** These are the "trigger points" where a plain-vanilla inquiry/analytical-procedure review must escalate into more audit-like substantive work, but only on the *specific* matter of concern — it does not convert the whole engagement into an audit.

- **Pitfalls / exam tips:** Classic case study — "material past-due debtors with no allowance" — practitioner's inquiry response can (a) resolve the doubt, (b) confirm material misstatement (no further work needed, conclusion is modified), or (c) still leave doubt unresolved (perform further procedures, e.g. checking post-year-end receipts).

---

### Subsequent Events, Written Representations & Evaluating Evidence

- **Key formula(s)/rule(s) — Subsequent events:**
  - **Between date of FS and date of report:** if aware of events requiring adjustment/disclosure, request management to correct the misstatement.
  - **After the report date:** no obligation to perform procedures; but if a fact becomes known **before FS are issued** that might have caused the practitioner to amend the report had it been known at the report date — discuss with management/TCWG, determine whether FS need amendment, and inquire how management intends to address it. If management refuses to amend and the report has already been given, notify management/TCWG not to issue the FS to third parties until amended; if issued anyway, take action to prevent reliance on the report.
- **Rule — Written Representations:** Request management's WR that it has fulfilled its responsibility for FS preparation (AFRF, fair presentation) and provided all agreed access/information, that all transactions are reflected in the FS, and that it has disclosed: identity/RP relationships & transactions, significant fraud/suspected fraud facts, known actual/possible NOCLAR, and all information relevant to the GC assumption, subsequent events requiring adjustment/disclosure, material commitments/contingencies, and material non-monetary/no-consideration transactions.
  - If management does not provide requested WRs: discuss with management/TCWG, re-evaluate management's integrity and the reliability of representations generally, and take appropriate action (including effect on the conclusion).
  - **Disclaim a conclusion / withdraw** (if possible under L/R) if there is sufficient doubt about management's integrity such that WRs are unreliable, or management does not provide WRs on its basic responsibilities.
- **Rule — Evaluating evidence:** If evidence obtained is not SAE to form a conclusion, the practitioner may extend work or perform other necessary procedures; if neither is practicable, a **scope limitation** exists — discuss its effect with management/TCWG. Inability to perform *one specific* procedure is **not** by itself a scope limitation if SAE can be obtained by other means.

- **Concept:** Same escalation logic as an audit's SA 580 (WR) and SA 560 (subsequent events), scaled down to the review context.

- **Pitfalls / exam tips:** Note the asymmetry — no *active* duty to search for post-report-date events, but a *reactive* duty exists if a relevant fact happens to come to the practitioner's attention before FS issuance.

---

### Forming the Conclusion & the Practitioner's Report (SRE 2400)

- **Key formula(s)/rule(s) — Types of conclusion:**

| Conclusion | When expressed |
|---|---|
| Unmodified | Nothing has come to attention causing belief FS are not prepared, in all material respects, as per AFRF |
| Qualified | Effects of the matter(s) are material but **not pervasive** |
| Adverse | Effects of the matter(s) are both material **and pervasive** (FS materially misstated) |
| Disclaimer | Possible effects of undetected misstatements (inability to obtain SAE) could be **material and pervasive** |

  - **Unmodified conclusion wording** (use unless L/R requires otherwise):
    - Fair presentation framework: *"Based on our review, nothing has come to our attention that causes us to believe that the FS do not give a true and fair view (or do not present fairly, in all material respects), as per [AFRF]."*
    - Compliance framework: *"Based on our review, nothing has come to our attention that causes us to believe that the FS are not prepared, in all material respects, as per [AFRF]."*
  - **Qualified conclusion** — because of a material misstatement: *"…except for the effects of the matter(s) described in the Basis for Qualified Conclusion paragraph, nothing has come to our attention…"*; if due to an inability to obtain SAE, substitute **"possible effects"** for "effects."
  - **Adverse conclusion**: *"…due to the significance of the matter(s) described in the Basis for Adverse Conclusion paragraph, the FS do not give a true and fair view / are not prepared, in all material respects, as per [AFRF]."*
  - **Disclaimer of conclusion**: state that, due to the significance of the matter(s) described in the Basis for Disclaimer paragraph, the practitioner is unable to obtain SAE to form a conclusion, and accordingly does **not** express a conclusion on the FS.
  - **Withdrawal** is required (where possible under L/R) if: a scope limitation is imposed by management **after** acceptance, AND the possible effects of undetected misstatements are **both material and pervasive**.
  - **Basis-for-conclusion paragraph content**, matched to the type of misstatement:
    - Amounts/quantitative disclosures → describe & **quantify** the financial effect (unless impracticable).
    - Narrative disclosures → explain how the disclosure is misstated.
    - Omitted disclosure → describe the nature of the omission (include the omitted disclosure itself where practicable and not prohibited by L/R).
    - Inability to obtain SAE → state the reason(s).

- **Concept:** The report structure mirrors SA 700/705/706 logic (heading "Qualified/Adverse/Disclaimer of Conclusion," a "Basis for …" paragraph placed **before** the conclusion paragraph) but every phrase is *negatively* worded ("nothing has come to our attention") rather than the audit's positive opinion language.

- **Rule — EOM & OM paragraphs:**
  - **Emphasis of Matter (EOM):** for a matter appropriately presented/disclosed in the FS that is, in the practitioner's judgment, fundamental to users' understanding — include only if SAE has been obtained that the matter is not materially misstated; place immediately **after** the conclusion paragraph under the heading "Emphasis of Matter."
  - **Other Matter (OM):** for a matter **not** presented/disclosed in the FS but relevant to users' understanding of the review, the practitioner's responsibilities, or the report — include (unless prohibited by L/R) under the heading "Other Matter."

- **Pitfalls / exam tips:**
  - Do not mix up "material but not pervasive" (→ Qualified) with "material and pervasive" (→ Adverse/Disclaimer) — identical pervasiveness test to SA 705 in audits.
  - Exam answers must reproduce the **negatively worded** conclusion phrases verbatim-ish — examiners award marks for the "nothing has come to our attention" construction, not a positively worded "in our opinion" (that would be an audit opinion, a common error).

---

### Documentation & Audit vs Review

- **Key formula(s)/rule(s) — Documentation must enable an experienced practitioner with no prior connection to the engagement to understand:**
  1. The **nature, timing and extent (NTE)** of procedures performed (including who performed the work, when it was completed, and who reviewed it and the extent of that review).
  2. The **results obtained** and the practitioner's **conclusions** formed.
  3. **Significant matters** arising during the engagement, conclusions reached thereon, and significant professional judgments made (including discussions with management/TCWG/others on significant matters, and their nature).

- **Key rule — Audit vs Review comparison:**

| Audit | Review |
|---|---|
| Provides **reasonable** assurance | Provides **limited** assurance (lower than reasonable) |
| Elaborate, extensive procedures — tests of controls (TOC) **and** substantive procedures | Fewer procedures — mainly **inquiry and analytical procedures** |
| Draws reasonable conclusions on the basis of SAAE | Draws limited conclusions on the basis of SAE |
| Provides an assurance **opinion**, **positively** worded | Provides an assurance **conclusion**, **negatively** worded |

- **Concept:** This table is a favourite direct 4–5 mark theory question — memorise the four contrast points (assurance level, procedures, evidence sufficiency term, wording direction).

- **Pitfalls / exam tips:** "Positively worded" (audit: "in our opinion, FS give a true and fair view") vs "negatively worded" (review: "nothing has come to our attention…") is the single most tested distinction from this table.

---

### SRE 2410 — Review of Interim Financial Information by the Entity's Own Auditor

- **Key formula(s)/rule(s):**
  - SRE 2410 applies when the review of **interim financial information** is performed by the **independent auditor of the entity's (annual) FS** — this is the key distinguishing feature from SRE 2400 (where the practitioner is *not* the entity's auditor).
  - **Interim financial information** = financial information prepared/presented as per the AFRF comprising a complete or condensed set of FS for a period **shorter than the entity's full financial year** (e.g., a quarter).
  - Terms of engagement should be agreed with the client and recorded in an **engagement letter**, covering objective/scope of review, management's and auditor's responsibilities, assurance obtained, and nature/form of the report.

- **Concept:** Because the same practitioner is also the annual statutory auditor, SRE 2410 leverages and updates the auditor's **existing knowledge** of the entity (from the annual audit) rather than starting from scratch — this is its central efficiency rationale versus SRE 2400.

- **Pitfalls / exam tips:** A very common exam distinction: *"is the SRE 2400 practitioner the entity's auditor?"* → **No** (2400) vs **Yes** (2410, own auditor doing interim review, e.g. quarterly results under SEBI LODR).

- **Definitions:**

| Term | Meaning |
|---|---|
| Interim financial information | Complete/condensed FS for a period shorter than the FY, per AFRF |
| NTE | Nature, Timing & Extent (of procedures) |

---

### SRE 2410 — Understanding, Inquiry & Analytical Procedures

- **Key formula(s)/rule(s) — Understanding the entity/environment/IC to identify potential MM and to select inquiries/analytical/other review procedures:**
  - Reading documentation of the **prior year's audit** and reviews of prior interim period(s), to identify matters that may affect the current period.
  - Considering **significant risks** (including management-override-of-controls risk) identified in the prior year's audit, and the nature of corrected/uncorrected misstatements in the prior FS.
  - Considering materiality (to determine NTE of procedures and evaluate misstatement effects), results of any audit procedures on the current year's FS to date, and results of internal audit work and management's follow-up action.
  - Inquiring of management about changes in business activities, changes in IC and their effect on preparing interim information, and the process by which interim information is prepared.
- **Rule — Typical inquiry/analytical/other review procedures ordinarily performed:**
  - Reading minutes of shareholders'/TCWG/committee meetings; inquiring about matters discussed where minutes are unavailable.
  - Considering the effect of matters that gave rise to a modified audit/review report previously.
  - Communicating with other auditors reviewing interim information of the entity's significant components (group situations).
  - Inquiring of finance/accounting personnel about: compliance of interim information with the AFRF; RP transactions being appropriately accounted/disclosed; significant assumptions for fair value measurements; changes in accounting principles/methods; new transactions needing a new accounting principle; known uncorrected misstatements; unusual/complex situations (e.g. business combination/disposal); compliance with debt covenants; significant changes in commitments/contingent liabilities/litigation; matters arising while applying review procedures; significant transactions near period-end; knowledge of actual/suspected fraud or allegations thereof; knowledge of actual/possible NOCLAR.
  - Applying **analytical procedures** to the interim information to identify unusual relationships/items.
  - Reading the interim information and considering whether anything indicates it is not prepared, in all material respects, as per the AFRF.
- **Rule — Direct communication with entity's lawyer (per SA 501 logic):** not automatically required; appropriate if a matter comes to attention causing the auditor to question whether interim information is prepared per the AFRF, and the auditor believes the entity's lawyer may have relevant information.
- **Rule — Subsequent events:** consider whether management has identified all events up to the date of the review report requiring adjustment/disclosure; **no obligation** to perform other procedures to identify events occurring **after** the date of the review report.

- **Concept:** SRE 2410's procedure list is essentially SRE 2400's inquiry/analytical toolkit *tailored* by leveraging annual-audit knowledge already held by the same auditor.

- **Pitfalls / exam tips:** The debt-covenants and litigation/contingent-liability inquiry items are commonly examined as standalone MTP/RTP one-liners — know them as a checklist.

---

### SRE 2410 — Going Concern, Misstatements, WRs & Communication

- **Key formula(s)/rule(s):**
  - **Going concern:** inquire whether management's GC assessment has changed; if events/conditions cast significant doubt, inquire about management's plans, their feasibility, and whether management believes the plans will improve the situation; consider adequacy of GC disclosure. Auditor is **not required to corroborate** the feasibility of management's plans.
  - **Doubtful accounting treatment:** if a matter raises doubt whether a material adjustment is needed for the interim information to comply with the AFRF, make additional inquiries/perform additional procedures (e.g., discuss transaction terms with senior personnel, read the underlying contract).
  - **Evaluation of misstatements:** evaluate whether uncorrected misstatements are material, individually and in aggregate, exercising professional judgment.
  - **Written representations** should include, among others: management's acknowledgment of responsibility for IC design/implementation to prevent/detect fraud & error; belief that uncorrected misstatements are immaterial (with a summary attached); disclosure of all frauds/suspected frauds and the fraud risk assessment results; disclosure of all known actual/possible NOCLAR; and disclosure of all significant subsequent events requiring adjustment/disclosure.
- **Rule — Communication:**
  - If auditor believes a material adjustment is necessary → communicate to the **appropriate level of management** on a timely basis; if management does not respond timely, inform **TCWG**.
  - Communication may be oral or written (factors: nature, sensitivity/significance of the matter, and timing); if oral, **document** it.
  - If TCWG do not respond timely, consider: whether to modify the report, possibility of withdrawing from the engagement, and possibility of resigning from the appointment to audit the annual FS.
  - If fraud/NOCLAR is believed to exist → communicate to management, report to TCWG, and consider implications for the review; also communicate matters relevant to TCWG's oversight of the financial reporting process.

- **Concept:** This mirrors SA 260/SA 265/SA 240 communication logic scaled to the interim-review context, with the added lever of "resigning from the annual audit appointment" as an escalation option unique to the auditor-is-also-reviewer relationship under SRE 2410.

- **Pitfalls / exam tips:** The escalation ladder (communicate → inform TCWG → consider report modification → consider withdrawal from *review* → consider resignation from the *annual audit*) is a distinctive SRE 2410 feature often tested as a "what should the auditor do next" sequencing question.

---

### SRE 2410 — Auditor's Report, UDIN & Limitation on Scope

- **Key formula(s)/rule(s) — Report ordinarily includes:**
  - Title, addressee, and an introductory paragraph identifying the interim financial information reviewed.
  - A statement that management is responsible for the preparation and presentation of the interim financial information as per the AFRF (including, for a fair presentation framework, fair presentation), and for such internal control as necessary.
  - A statement that the auditor's responsibility is to express a conclusion on the interim information based on the review.
  - A statement that the review was conducted as per **SRE 2410**, and a statement that such a review consists of making inquiries, primarily of persons responsible for financial and accounting matters, and applying analytical and other review procedures.
  - A statement that a review is **substantially less in scope than an audit** conducted as per SAs, and that accordingly the auditor does **not express an audit opinion** on the interim financial information.
  - The auditor's **conclusion**: if nothing has come to attention (unmodified) — a negatively worded statement that nothing causes the auditor to believe the interim financial information does not give a true and fair view (or does not present fairly, in all material respects) as per the AFRF; where modified, appropriate qualified/adverse conclusion wording with reasons.
  - Date of the report, auditor's signature (with **membership number** assigned by ICAI), place of signature, and the firm's registration number.
- **Rule — UDIN:** ⚠️ VERIFY — per the source notes, **UDIN must be generated and stated** for review engagements performed under SRE 2400 or SRE 2410 (review reports fall within ICAI's UDIN mandate for assurance/attest functions) — confirm the current UDIN circular/applicability at the time of the attempt, as ICAI periodically updates the UDIN mandate list.
- **Rule — Limitation on scope:**
  - When the auditor is **unable to complete the review**, communicate in **writing** to management/TCWG the reason, and consider whether it is appropriate to issue a report.
  - **Do not accept** the engagement if the auditor would be unable to complete the review because of a scope limitation imposed by management. If such a limitation is imposed **after** acceptance, request its removal; if management refuses, the auditor is unable to complete the review — communicate the reason in writing and consider L/R reporting obligations. If a report must still be issued, the auditor **disclaims** a conclusion, stating the reason the review could not be completed.
  - If a limitation is confined to specific matters that are **material but not pervasive**, modify the review report — indicate that except for the matter described in an explanatory paragraph the review was conducted per SRE 2410, and **qualify** the conclusion. Also reconsider whether a similar limitation noted in the latest annual audit opinion still exists and its implication for the review report.
- **Rule — Going concern / material uncertainty (MU) in interim review:**
  - If a MU exists and is **adequately disclosed**, modify the review report by adding an **Emphasis of Matter (EOM)** paragraph highlighting the MU (including where a prior audit/review report already carried such an EOM and the MU continues).
  - If the MU is **not adequately disclosed**, express a **qualified or adverse conclusion**, as appropriate, with specific reference to the fact of the MU.
- **Rule — Auditor's responsibility for accompanying/other information:** read other information accompanying the interim financial information to consider material inconsistency; if identified, consider whether the interim information or the other information needs amendment. If amendment is refused: for interim information, consider implications for the review report; for other information, consider including a description of the inconsistency in the report, withholding issuance, or withdrawing from the engagement. Similarly, for an apparent **material misstatement of fact** in other information, discuss with management and, if unresolved, consider notifying TCWG/obtaining legal advice.
- **Rule — Report accompanying published interim information:** agree with management that where a document indicates the interim information has been reviewed, the review report will be included in that document; if management omits it, or issues a modified-report situation without inclusion, seek legal advice and consider the possibility of resigning from the annual audit.

- **Concept:** The SRE 2410 report is structurally close to a limited-review certificate seen in SEBI LODR quarterly-results reporting practice in India — scope paragraph explicitly states the review is **"substantially less in scope than an audit."**

- **Pitfalls / exam tips:**
  - Do not let students write "we conducted our audit as per SAs" for an SRE 2410 report — the explicit **"substantially less in scope than an audit… accordingly we do not express an audit opinion"** sentence is a mandatory, frequently tested phrase.
  - Distinguish EOM-for-continuing-MU (going concern) from a qualified/adverse conclusion for **inadequately disclosed** MU — same qualitative/pervasiveness logic as SA 570/706 in audits.

### References
1. ICAI, Standard on Review Engagements (SRE) 2400 (Revised), "Engagements to Review Historical Financial Statements" — objectives, acceptance/continuance, procedures, and report wording (conclusion, EOM/OM, documentation) as summarized above.
2. ICAI, Standard on Review Engagements (SRE) 2410, "Review of Interim Financial Information Performed by the Independent Auditor of the Entity" — scope, inquiry/analytical procedure checklist, going concern, communication, report content and limitation-on-scope provisions.
3. Cross-referenced concepts from SA 210 (Agreeing the Terms of Audit Engagements), SA 501 (communication with entity's lawyer), SA 560 (subsequent events), SA 570 (going concern), SA 580 (written representations), SA 705/706 (modifications, EOM/OM) — used by SRE 2400/2410 as the conceptual parallel for review-engagement equivalents, per standard CA Final Audit curriculum treatment.
4. ⚠️ VERIFY — UDIN applicability to SRE 2400/2410 review reports: confirm against the current ICAI UDIN Directorate FAQ/circular in force for the attempt, as this session's live web verification could not be completed (search budget exhausted) — reconstructed from the source notes' explicit statement that UDIN is mandatory for SRE 2400/2410 engagements.

## 12. Standards on Assurance Engagements (SAE 3400/3402/3420)

> **Where it fits:** These are the "other assurance engagements" issued under ICAI's Framework for Assurance Engagements — they extend assurance beyond the historical-FS audit to prospective financial information (SAE 3400), controls at a service organisation (SAE 3402), and pro forma financial information in a prospectus (SAE 3420).

### 12.1 Framework Overview — What is an Assurance Engagement?

- **Key formula(s)/rule(s):**

$$\text{Assurance Engagement} = \text{Practitioner's Conclusion} \; \big[\text{Subject Matter vs. Criteria}\big] \rightarrow \text{Enhanced confidence of intended users (other than the responsible party)}$$

  - Two assurance levels exist under the Framework: **Reasonable assurance** (high level, opinion expressed in the *positive* form — "in our opinion... presents fairly") and **Limited/Moderate assurance** (opinion expressed in the *negative* form — "nothing has come to our attention...").
  - Of the three SAEs: **SAE 3400 is a limited (moderate) assurance engagement** (negative-form conclusion, because PFI evidence is inherently future-oriented and speculative); **SAE 3402 and SAE 3420 are reasonable assurance engagements** (practitioner expresses a positive-form opinion).

| SAE | Full title | Subject matter |
|---|---|---|
| SAE 3400 | The Examination of Prospective Financial Information | Forecasts/projections (PFI) |
| SAE 3402 | Assurance Reports on Controls at a Service Organisation | Design/operation of controls at a service organisation (SO) |
| SAE 3420 | Assurance Engagements to Report on the Compilation of Pro Forma Financial Information Included in a Prospectus | Pro forma financial information (PFFI) |

- **Concept:** An assurance engagement is not restricted to auditing historical financial statements — it can cover future-oriented information, third-party controls, or hypothetical "as-if" financial information, provided a suitable-criteria/subject-matter relationship exists.
- **Pitfalls / exam tips:**
  - Do not assume every SAE gives negative assurance — only SAE 3400 does; SAE 3402/3420 give an opinion (reasonable assurance). This distinction is a favourite trap in MCQs.
  - Remember the engagement performed under an SAE **need not be performed by the entity's statutory auditor**.

- **Definitions:**

| Term | Meaning |
|---|---|
| Assurance engagement | Engagement where a practitioner expresses a conclusion to enhance the degree of confidence of intended users (other than the responsible party) about the outcome of evaluating a subject matter against criteria |
| Reasonable assurance | High (but not absolute) level of assurance; opinion expressed positively |
| Limited/moderate assurance | Lower level of assurance; opinion expressed negatively |

---

### 12.2 SAE 3400 — The Examination of Prospective Financial Information (PFI)

- **Key formula(s)/rule(s):**

$$\text{PFI} = \text{Forecast} \;\cup\; \text{Projection} \;\cup\; (\text{Forecast} + \text{Projection combined})$$

  - **Forecast** = PFI prepared on **best-estimate assumptions** — mgt's expectation of future events and the actions it expects to take (no provision for adverse deviation).
  - **Projection** = PFI prepared on **hypothetical assumptions** (about future events/actions not necessarily expected to occur) — or a mixture of best-estimate and hypothetical assumptions.
  - **Clause 3, Part I, Second Schedule to the Chartered Accountants Act, 1949**: a member is deemed guilty of professional misconduct if he permits his or his firm's name to be used in connection with an estimate of earnings contingent upon future transactions in a manner that may lead to a belief that he vouches for the accuracy of the forecast.
  - Auditor must obtain **sufficient appropriate audit evidence (SAAE)** on 4 points before reporting:
    a. Best-estimate assumptions are not unreasonable and hypothetical assumptions are consistent with the purpose of the info;
    b. PFI is properly prepared on the basis of the assumptions;
    c. PFI is properly presented and all material assumptions are adequately disclosed (incl. whether best-estimate or hypothetical);
    d. PFI is prepared on a consistent basis with historical FS, using appropriate accounting principles.
  - **This SAE does not apply** to PFI expressed in general/narrative terms (e.g., MD&A commentary in an annual report).

- **Concept:** SAE 3400 governs how an auditor examines and reports on forecasts/projections (e.g., for a bank loan, a prospective equity investor, or a start-up business plan) — since future outcomes cannot be vouched for, the report gives only negative (limited) assurance on whether the assumptions provide a reasonable basis for the PFI.

- **Pitfalls / exam tips:**
  - Never confuse "opinion on achievability of results" with the actual opinion given — the auditor **never** opines that the forecast **will** be achieved; only that assumptions provide a reasonable basis.
  - Presentation & disclosure checklist mnemonic — **A-B-C-D-E**: **A**ccounting policies disclosed in notes; **B**est-estimate/hypothetical nature of assumptions disclosed with sensitivity for high-uncertainty areas; **C**hange in accounting policy (reason & effect) disclosed; **D**ate as of which PFI was prepared, disclosed; **E** — presentation is informative and not misleading.
  - Precautions before accepting the engagement: intended use, general vs. limited distribution, nature of assumptions, elements included, and period covered.
  - Decline/withdraw if assumptions are clearly unrealistic or PFI would be inappropriate for its intended use.
  - **Modified opinion:** qualified/adverse opinion (or withdrawal) if presentation/disclosure is inadequate, or if one or more significant assumptions do not provide a reasonable basis for the PFI; **disclaimer of opinion / withdrawal** if a scope limitation precludes application of necessary procedures.
  - Report must always carry an appropriate **caveat on achievability** — actual results are likely to differ, and for a range, there is no assurance actuals will fall within the range.

- **Definitions:**

| Term | Meaning |
|---|---|
| PFI | Financial information based on assumptions about future events and possible actions of the entity |
| Best-estimate assumption | Assumption reflecting anticipated experience, with no provision for risk of adverse deviation |
| Hypothetical assumption | Assumption about future events/actions not necessarily expected to take place |
| Negative assurance | "Nothing has come to our attention that causes us to believe assumptions do not provide a reasonable basis for the PFI" |

---

### 12.3 SAE 3402 — Assurance Reports on Controls at a Service Organisation (SO)

- **Key formula(s)/rule(s):**

$$\text{Reasonable Assurance} = \text{Description of System} + \text{Design of Controls} + \text{Operating Effectiveness} \;\rightarrow\; \text{Service Auditor's Report}$$

  - **Scope:** applies only when the SO is responsible for, or can make an assertion about, the suitable design of controls. It does **not** cover engagements that report only on whether controls operated as described, or on controls unrelated to a service relevant to user entities' internal control over financial reporting.
  - **Type 1 vs Type 2 report:**

| Type 1 Report | Type 2 Report |
|---|---|
| Description of system + written assertion that description fairly presents the system **as at a specified date**, and controls were suitably designed **as at that date** | Description of system + written assertion that description fairly presents the system, controls were suitably designed, **and** controls operated effectively — all **throughout a specified period** |
| Service auditor's report conveys reasonable assurance on the above | Service auditor's report conveys reasonable assurance **and** includes a description of tests of controls (TOCs) performed and results |

  - **Objectives of service auditor** — obtain reasonable assurance whether, in all material respects, based on suitable criteria: (i) the SO's description of the system fairly presents the system as designed & implemented; (ii) controls related to the stated control objectives were suitably designed; (iii) (where in scope) controls operated effectively to achieve the control objectives — then report accordingly.

- **Concept:** Used when a user entity outsources a process (e.g., payroll processing) to a service organisation; SAE 3402 governs the service auditor's report on that SO's controls, which the user auditor can then rely upon under SA 402.

- **Pitfalls / exam tips:**
  - 12-step process to remember in sequence: (1) comply with ethical requirements incl. independence; (2) determine mgt/TCWG and communicate; (3) engagement acceptance & changes in terms; (4) assess suitability of criteria; (5) determine materiality; (6) obtain understanding of SO's system incl. controls; (7) obtain & read SO's description, evaluate fair presentation; (8) determine controls achieving control objectives & assess design; (9) [Type 2 only] test controls & assess operating effectiveness throughout the period; (10) understand the internal audit function (to assess reliance); (11) obtain written representations from SO; (12) inquire about subsequent events.
  - **Written representations** from the SO must cover: reaffirmation of the assertion on the description; that all relevant info/access was provided; and disclosure of any NOCLAR/fraud/uncorrected deviations, design deficiencies, instances of controls not operating as described, and significant subsequent events.
  - **Modified opinion** triggers: description doesn't fairly present the system; controls not suitably designed; (Type 2) tested controls did not operate effectively; or service auditor unable to obtain SAAE — in each case give reasons for the modification.
  - Complementary user-entity controls: if the SO's description says control objectives can only be met with complementary controls at the user entity, the service auditor's report must state that it has **not** evaluated the design/operating effectiveness of those user-entity controls.

- **Definitions:**

| Term | Meaning |
|---|---|
| Service Organisation (SO) | Entity that provides services to user entities relevant to those entities' internal control over financial reporting |
| Sub-service organisation (SSO) | An organisation used by the SO to perform some of the services provided to user entities |
| Control objective | The aim/purpose stated by, or agreed with, the SO for the controls at the SO |

---

### 12.4 SAE 3420 — Assurance Engagements to Report on Compilation of Pro Forma Financial Information (PFFI) Included in a Prospectus

- **Key formula(s)/rule(s):**

$$\text{PFFI} = \text{Unadjusted Financial Information} + \text{Pro Forma Adjustments}$$

$$\text{Compilation process: } \text{Identify \& extract source} \;\rightarrow\; \text{Apply pro forma adjustments} \;\rightarrow\; \text{Present PFFI with disclosures}$$

  - **Objective:** obtain reasonable assurance whether the PFFI has been compiled, in all material respects, by the responsible party on the basis of the applicable criteria, and to report accordingly — this is a **reasonable assurance** engagement, expressed as an opinion.
  - **Practitioner's responsibility:** the practitioner has **no responsibility for compiling** the PFFI — that rests solely with the responsible party. The practitioner's sole role is to report on whether the compilation was performed correctly.
  - **Pro forma adjustments** include: (a) adjustments to unadjusted financial info that illustrate the impact of the significant event/transaction as if it had occurred/been undertaken at an earlier date; and (b) adjustments necessary to align the PFFI with the applicable financial reporting framework and the entity's accounting policies.
  - **Opinion:**
    - **Unmodified** — PFFI compiled, in all material respects, on the basis of the applicable criteria.
    - **Modified** — if law/regulation *prevents* publication of a prospectus containing a modified opinion, the practitioner must discuss with the responsible party and, if not resolved, **withdraw from the engagement or seek legal advice**; if law/regulation *permits* a modified opinion in the prospectus, apply the modified-opinion requirements of the Framework for Assurance Engagements.
    - **Emphasis of Matter paragraph** may be added only for a matter presented/disclosed in the PFFI or its notes, fundamental to users' understanding, provided the practitioner has obtained SAAE about it.

- **Concept:** PFFI shows, e.g. via a pro forma P&L/Balance Sheet, how a significant transaction (acquisition, disposal, restructuring) *might have* affected the entity's assets, liabilities, and earnings had it occurred earlier — used in offer documents/prospectuses to help investors understand the transaction's impact. **PFFI does not represent the entity's actual financial position, performance, or cash flows.**

- **Pitfalls / exam tips:**
  - Engagement acceptance checks: practitioner's competence/capability; suitability of applicable criteria (unlikely PFFI misleading); ability to word the opinion per this SAE; where source financial info was modified/qualified or carries an EOM, check whether law/regulation permits referencing that in the practitioner's report; if historical FI was never audited/reviewed, assess whether sufficient understanding of the entity (or acquiree, in a business combination) can still be obtained.
  - Obtain the responsible party's **written agreement** acknowledging responsibility for disclosing applicable criteria, compiling PFFI on that basis, and providing full access (including to an acquiree's information/advisors in a business combination).
  - Obtain **written representations** confirming: (a) all appropriate pro forma adjustments have been identified; (b) PFFI has been compiled, in all material respects, on the basis of the applicable criteria.
  - Don't confuse this with a compilation engagement under SRS 4410 (no assurance) — SAE 3420 is a **reasonable assurance** engagement with an opinion.

- **Definitions:**

| Term | Meaning |
|---|---|
| PFFI | Financial information showing the application of pro forma adjustments to unadjusted financial information to illustrate the impact of an event/transaction, as if it had occurred at an earlier date |
| Unadjusted financial information | The financial information used as the base to which pro forma adjustments are applied |
| Responsible party | The party responsible for compiling the PFFI (not the practitioner) |

### References

1. ICAI, Standard on Assurance Engagements (SAE) 3400, "The Examination of Prospective Financial Information."
2. ICAI, Standard on Assurance Engagements (SAE) 3402, "Assurance Reports on Controls at a Service Organisation."
3. ICAI, Standard on Assurance Engagements (SAE) 3420, "Assurance Engagements to Report on the Compilation of Pro Forma Financial Information Included in a Prospectus."
4. The Chartered Accountants Act, 1949 — Second Schedule, Part I, Clause 3 (professional misconduct re: vouching for accuracy of a forecast).
5. ICAI, Framework for Assurance Engagements (basis for the reasonable-assurance/limited-assurance distinction applied above).

*Note: This chapter was cross-checked against standard ICAI SAE text and the CA Act, 1949 using verified professional/domain knowledge of the current (2026) CA Final syllabus; live web-search verification could not be completed this session as the search tool's query budget was already exhausted. No figures/section numbers were invented — where the OCR was garbled, the reconstruction above follows the well-established, examined position on these SAEs.*

## 13. Standards on Related Services (SRS 4400 & 4410)

> **Where it fits:** These are the two "Related Services" standards — engagements a practitioner performs that are **not audits, not reviews, and not assurance engagements at all** (no opinion, no conclusion). SRS 4400 covers Agreed-upon Procedures (AUP); SRS 4410 covers Compilation. Both sit outside the assurance framework, alongside tax-return preparation and management/tax consulting.

### Overview: Related Services vs Assurance Engagements

- **Key rule(s):**
  - Not every engagement a practitioner performs is an assurance engagement. Common **non-assurance** engagements include: preparation of tax returns (no assurance expressed); consulting/advisory engagements (management & tax consulting); and engagements covered by the SRSs — Agreed-Upon Procedures (SRS 4400) and Compilations (SRS 4410).
  - The person performing an AUP or compilation engagement **need not be the statutory auditor** of the entity's financial statements.

- **Concept:** Frame every question in this chapter around one test — "does the practitioner express an opinion/conclusion, or only report facts / assist in preparation?" If no opinion/conclusion is given, it is a related service, not assurance.

- **Pitfalls / exam tips:**
  - Do not confuse AUP/Compilation with a "review" (SRE 2400/2410) — a review gives limited assurance (negative conclusion); AUP and Compilation give **no assurance at all**.
  - Exam favourite: "Is independence mandatory?" — answer is the same for both SRS 4400 and SRS 4410: **independence is NOT required**, but the practitioner **must still comply with other relevant ethical requirements** (integrity, objectivity, professional competence, confidentiality, professional behaviour) under the ICAI Code of Ethics. Terms of the specific engagement may additionally require independence.

- **Definitions:**

| Term | Meaning |
|---|---|
| Assurance engagement | Practitioner expresses a conclusion/opinion giving a level of assurance (reasonable/limited) to intended users |
| Related service | Engagement under the SRSs (AUP, Compilation) where **no assurance** is expressed |
| AFRF | Applicable Financial Reporting Framework used to prepare the financial information |
| TCWG | Those Charged With Governance |

---

### SRS 4400 — Engagements to Perform Agreed-Upon Procedures Regarding Financial Information

- **Key rule(s):**
  - **Objective:** Carry out procedures of an audit nature to which the auditor, the entity, and any appropriate third parties have agreed, and report on the **factual findings**. **No assurance is expressed.**
  - Users of the report assess the procedures and findings themselves and **draw their own conclusions** — the practitioner draws none.
  - The report is **ordinarily restricted** to the parties who agreed to the procedures, since others — unaware of why the procedures were performed — may misinterpret the results.
  - **Independence:** Not mandatory for AUP engagements; other ethical requirements (per the Code of Ethics) must still be complied with; the engagement terms may specifically require independence.

- **Concept:** AUP is a "you tell me what to check, I check it and report only facts" engagement — e.g., comparing supplier balances in the trial balance to confirmations received, and reporting the variances found, without saying whether the payables balance is "fairly stated."

- **Terms of Engagement — matters to be agreed:**
  - Nature of the engagement, including that the procedures performed will **not constitute an audit or a review** and accordingly **no assurance will be expressed**.
  - Stated purpose of the engagement.
  - Identification of the financial information to which the agreed-upon procedures will be applied.
  - Nature, timing and extent (NTE) of the specific procedures to be applied.
  - Limitations on distribution of the report of factual findings — if this conflicts with a legal requirement, the auditor should **not accept** the engagement.
  - Engagement letter should also list the agreed procedures and state that distribution of the report is restricted to the specified parties who agreed to the procedures.

- **Procedures typically applied (may include):**
  - Inquiry and analysis
  - Inspection
  - Observation
  - Obtaining confirmations
  - Re-computation, comparison and other clerical accuracy checks

- **Reporting — elements of the report of factual findings:**
  - Title
  - Addressee (ordinarily the appointing authority)
  - Identification of the specific financial/non-financial information to which the agreed-upon procedures were applied
  - Statement that the procedures performed were those agreed with the recipient
  - Statement that the engagement was performed as per SRS 4400
  - Identification of the purpose of the engagement
  - Listing of the specific procedures performed
  - Description of the practitioner's factual findings, including sufficient details of errors and exceptions found
  - Statement that the procedures performed do **not** constitute an audit or review, and **no assurance is expressed**
  - Statement that had the practitioner performed additional procedures, an audit, or a review, other matters might have come to light that would have been reported
  - Statement that the report is restricted to the parties who agreed to the procedures performed
  - Statement (where applicable) that the report relates only to the specified elements/accounts/items or financial and non-financial information, and does **not extend to the entity's financial statements as a whole**
  - Date of report, place of signature, and auditor's signature

- **Pitfalls / exam tips:**
  - Memory anchor for the AUP vs Audit distinction: **Audit → opinion + assurance; AUP → facts only, no assurance, users conclude themselves.**
  - A very common short-answer question: "State any four matters to be agreed as terms of an AUP engagement" — pick straight from the bulleted list above.
  - The report must explicitly disclaim that it is not an audit/review and that additional procedures might have revealed other matters — do not drop this clause when listing report elements.

---

### SRS 4410 — Compilation Engagements

- **Key rule(s):**
  - **Objective:** (a) Apply accounting expertise to assist management in the preparation and presentation of financial information as per the applicable financial reporting framework (AFRF), based on information provided by management; and (b) report as required by SRS 4410.
  - Applies to compilation engagements for **historical financial information**; compilation of *other* information can be performed under this SRS after necessary adaptation.
  - **SQC 1 applies to compilation engagements too** (firm-level quality control).
  - **Independence:** Not required for the practitioner, but ethical requirements under the Code of Ethics must still be complied with.
  - Compilation is **not an assurance engagement** — hence **no opinion or conclusion is ever expressed**.

- **Concept:** In a compilation, the accountant essentially helps "write up" the financial statements from the client's records and figures — a bookkeeping/presentation assistance service — and then reports only that this compilation was carried out, without vouching for the figures' accuracy or fair presentation.

- **Why compilation engagements are needed (purposes of the financial information):**
  - To comply with mandatory periodic financial reporting requirements under law/regulation, **or**
  - For purposes unrelated to mandatory reporting, e.g.:
    - For management/TCWG on a basis suited to their internal purposes;
    - For periodic reporting to external parties under a contract/agreement (e.g., reporting to a funding body to support a grant);
    - For transactional purposes (e.g., to support a merger/acquisition or a change in ownership/financing structure).

- **Engagement Acceptance & Continuance — terms to be agreed with management (and engaging party, if different):**
  - Intended use and distribution of the financial information and any restrictions on its use/distribution.
  - Identification of the AFRF.
  - Objective and scope of the compilation engagement.
  - Responsibilities of the practitioner, including complying with relevant ethical requirements.
  - Responsibilities of management for: (i) the financial information's preparation/presentation as per the acceptable FRF; (ii) design, implementation and maintenance (DIM) of internal control to enable preparation of financial statements free from material misstatement due to fraud or error; (iii) accuracy and completeness of records, documents, explanations and other information provided; and (iv) judgments needed in preparation/presentation of the financial information.
  - Expected form and content of the report.
  - All of the above must be recorded in an **engagement letter or other written agreement** *before* the engagement begins.

- **Performing the Engagement — sequence (mnemonic: Understand → Compile → Discuss → Read → Issues → Withdraw):**
  1. Obtain an understanding of (a) the entity's business & operations, including its accounting system and records, and (b) the AFRF, including its application in the entity's industry.
  2. Compile the financial information using records, documents, explanations and other information (including significant judgments) provided by management.
  3. Discuss with management/TCWG the significant judgments for which the practitioner provided assistance while compiling.
  4. Prior to completion, read the compiled financial information in light of the understanding obtained of the entity's business, operations and the AFRF.
  5. If records/explanations/information provided are incomplete, inaccurate, or unsatisfactory, bring this to management's attention and request additional/corrected information.
  6. If unable to complete the engagement because management fails to provide the required information, **withdraw** and inform management and TCWG of the reasons.

- **Key rule(s) — if issues are noted during the engagement:**
  - If the practitioner becomes aware that: (i) the compiled financial information does not adequately refer to or describe the AFRF; (ii) amendments are required so that the information is not materially misstated; or (iii) the compiled financial information is otherwise misleading —
  - → the practitioner **shall propose appropriate amendments** to management.
  - If management declines or does not permit the practitioner to make the proposed amendments → **withdraw** and inform management and TCWG of the reason.
  - If withdrawal is not possible → determine professional and legal responsibilities applicable in the circumstances.
  - Before issuing the report, obtain **acknowledgement from management/TCWG** that they have taken responsibility for the final version of the compiled financial information.

- **Practitioner's Report — elements:**
  - Report title
  - Addressee(s), as required by the terms of engagement
  - Statement that the practitioner has compiled the financial information based on information provided by management
  - Description of management's/TCWG's responsibilities in relation to the compilation engagement and to the financial information
  - Identification of the AFRF and, if a special purpose framework (SPF) is used, description of/reference to that SPF in the financial information
  - Identification of the financial information, including the title of each element if it comprises more than one element, and the date/period to which it relates
  - Description of the practitioner's responsibilities, including that the engagement was performed as per SRS 4410 and that ethical requirements were complied with
  - Description of what a compilation engagement entails as per SRS 4410
  - Explanations that: since compilation is **not an assurance engagement**, the practitioner is **not required to verify the accuracy or completeness** of the information provided by management for compilation; and accordingly, the practitioner does **not express an audit opinion or review conclusion** on whether the financial information is prepared as per the AFRF
  - If a special purpose framework is used, an explanatory paragraph that: describes the purpose for which the information is prepared and its intended users (or refers to a note in the financial information disclosing this), and draws readers' attention to the fact that the information is prepared as per an SPF and may not be suitable for other purposes
  - Date of report + signature + place of signature

- **Engagement-Level Quality Control:**
  - The **engagement partner** shall take responsibility for: (a) the overall quality of each compilation engagement to which they are assigned, and (b) the engagement being performed as per the firm's quality control policies and procedures (in line with SQC 1).

- **Engagement Documentation — should include:**
  - Significant matters and how they were addressed.
  - A record of how the compiled financial information reconciles with the underlying records, documents, explanations and other information provided by management.
  - A copy of the final version of the compiled financial information (for which management/TCWG has acknowledged responsibility) and the practitioner's report.
  - May include a copy of the trial balance, summary of significant accounting records, or other information used in the compilation.

- **Pitfalls / exam tips:**
  - The recurring "no assurance" clause appears **twice** in the report — once as a general statement, and again (if applicable) tied to the special-purpose framework paragraph; do not merge them into one point when writing report elements in the exam.
  - Distinguish the **practitioner's** duty to propose amendments (SRS 4410) from an **auditor's** duty to modify an opinion (SA 700 series) — in compilation, if management refuses amendments, the remedy is to **withdraw**, not to qualify a report (there is no opinion to qualify).
  - Remember SQC 1 (firm-level) applies to compilation engagements exactly as it does to audits — a common one-line objective/true-false question.

---

### References

1. ICAI, *Standard on Related Services (SRS) 4400 (Revised), "Engagements to Perform Agreed-upon Procedures Regarding Financial Information"* — objective, terms of engagement, procedures and reporting requirements as summarised above.
2. ICAI, *Standard on Related Services (SRS) 4410, "Compilation Engagements"* — objective, scope, engagement acceptance, performance, reporting, and documentation requirements as summarised above.
3. ICAI, *Standard on Quality Control (SQC) 1* — applicability to compilation engagements and engagement-level quality control responsibility of the engagement partner.
4. ICAI, *Code of Ethics* — fundamental ethical principles applicable even where independence is not mandated (AUP and compilation engagements).

⚠️ VERIFY — the effective date of the Revised SRS 4400 (applicable to AUP reports issued on or after a specified date) is not stated in the source material and was not independently re-verified in this session (web search budget was exhausted); confirm the applicability date against the current ICAI Study Material/RTP before relying on it in an exam answer if the question specifically tests the effective date.

## 14. SDG & ESG Assurance (Sustainability Reporting)

> **Where it fits:** the newest chapter in the syllabus — covers non-financial (ESG/sustainability) reporting frameworks (BRSR, GRI, IIRC), the assurance standards ICAI has issued for them (SSAE 3000, SSAE 3410), and how climate-related risk is factored into a conventional SA-based financial statement audit.

### Sustainability Reporting — Meaning & Benefits

- **Concept:** Sustainability reporting is the practice of publicly reporting economic, environmental, and social (EES) impacts and contributions (positive or negative) towards sustainable development — i.e., non-financial performance disclosed on a regular, structured basis alongside financial performance.
- **Key benefits (rule/list form):**
  - **Understand performance** — links financial and non-financial performance so stakeholders can assess performance vis-à-vis sustainability impacts.
  - **Long-term value** — helps entities focus on long-term value creation by addressing Environmental, Social & Governance (ESG) issues.
  - **Investing** — investors increasingly use ESG disclosures (risks & opportunities) to make investment decisions.

**Pitfalls / exam tips**
- Do not confuse "sustainability reporting" (the disclosure practice) with "sustainability assurance" (the independent check on that disclosure, covered later under SSAE 3000/3410) — examiners test both as separate MCQ/theory angles.

---

### The Three Pillars of ESG

| Pillar | Covers |
|---|---|
| **E — Environment** | Corporate climate policies, energy use, waste, pollution, natural resource conservation, treatment of animals; use of natural resources (coal, water, etc.) |
| **S — Social** | Relationships & reputation with people/institutions; labour relations, diversity & inclusion |
| **G — Governance** | Internal controls & procedures to govern the entity, make effective investment decisions, comply with law, and meet stakeholder needs |

**Concept:** ESG reporting discloses information, data and metrics explaining the value added in these 3 areas; it can be **qualitative** (strategy/policy narrative) or **quantitative** (metrics/KPIs against goals) — a **mixed approach using both** improves disclosure quality.

**Pitfalls / exam tips**
- If asked to classify a given disclosure item as E, S or G, anchor on: natural-resource/climate items → E; people/labour/community items → S; board/IC/compliance items → G.

---

### 17 Sustainable Development Goals (SDGs) — Quick Read

- No Poverty | Zero Hunger | Good Health & Well-Being | Quality Education | Gender Equality | Clean Water & Sanitation | Affordable & Clean Energy | Decent Work & Economic Growth | Industry, Innovation & Infrastructure | Reduced Inequalities | Sustainable Cities & Communities | Responsible Consumption & Production | Climate Action | Life Below Water | Life on Land | Peace, Justice & Strong Institutions | Partnerships for the Goals
- **Concept:** Corporates can contribute to SDGs due to their capacity to provide solutions for meeting these goals — companies can lead in innovation and contribute to SDG achievement.

**Pitfalls / exam tips**
- Only the count (17) and a rough theme recall are exam-relevant — rote-memorizing the exact wording of each goal has low marks-per-minute value; skim-read only.

---

### Integrated Reporting (IR) — The 6 Capitals

- **Key rule:** Integrated Reporting (per the International ⟨IR⟩ Framework, IIRC) is built around **6 capitals ("6 Cs")** that an organisation draws on and impacts.

| Capital | Meaning |
|---|---|
| **Financial Capital** | Pool of funds available for producing goods/services — obtained via financing (debt, equity, grants) or generated through operations/investments |
| **Manufactured Capital** | Human-created production equipment & tools available for production of goods/services |
| **Natural Capital** | Input to production of goods/services; org's activities also impact it — e.g., water, land, minerals, forests, biodiversity |
| **Human Capital** | People's skills, experience, capacity & motivations — alignment with governance/ethical values, ability to implement strategy, loyalty/motivation to improve processes |
| **Social Capital** | Institutions & relationships within/between communities, stakeholder groups & networks — common values/behaviour, key relationships (trust/loyalty with customers, suppliers, partners), social license to operate |
| **Intellectual Capital** | Key element of future earning potential — R&D investment, innovation, external relationships determining competitive advantage |

**Concept:** Integrated Reporting is **voluntary for the top 500 listed companies** (by market capitalisation) in India.

**Pitfalls / exam tips**
- Do not confuse IR's voluntary top-500 regime with BRSR's mandatory top-1000 regime (next topic) — a favourite trap in MCQs.

---

### BRSR — Business Responsibility & Sustainability Report

- **Key rule/threshold:**
  - BRSR is **mandatory for the top 1,000 listed companies by market capitalisation** in India (per SEBI's BRSR framework, introduced vide SEBI Circular SEBI/HO/CFD/CMD-2/P/CIR/2021/562 dated 10 May 2021, applicable from FY 2022-23).
- **Structure — 3 Sections:**

| Section | Content |
|---|---|
| **A — General Disclosures** | Details of the listed company — products, services, operations, employee details, holding/subsidiary/associate companies, etc. |
| **B — Management & Process Disclosures** | Questions on policy & management processes, governance, leadership & oversight |
| **C — Principle-wise Performance Disclosures** | KPIs reported in alignment with the **9 Principles of NGRBC** (National Guidelines on Responsible Business Conduct) |

- **KPI categories under Section C (2 categories):**
  - **Essential Indicators** — mandatory disclosures (e.g., training program data, environmental data on energy/emissions/water/waste management).
  - **Leadership Indicators** — voluntary, more advanced disclosures (e.g., life-cycle assessments, conflict-management policy, additional biodiversity/energy-consumption/supply-chain data).

**Pitfalls / exam tips**
- Remember the 1,000 (BRSR, mandatory) vs 500 (IR, voluntary) distinction.
- Essential = mandatory; Leadership = voluntary — do not swap these labels.

---

### Nine Principles of NGRBC (as reported in BRSR Section C)

- ⚠️ VERIFY — the source notes state the 9 principles split as **"2 in Environment, 3 in Social & 4 in Governance."** This E/S/G mapping is not uniformly stated the same way across all ICAI study material/SEBI guidance notes (some categorise P4 and P9 differently); use the principle names/content below with confidence, but treat the exact 2-3-4 numeric split as needing a cross-check against your institute's current module before quoting it as a standalone MCQ answer.

| # | Principle | Essence |
|---|---|---|
| **P1** | Ethics, Transparency & Accountability | Business decisions should be ethical, transparent & accountable; core elements — Policies; Share with stakeholders; disclose Adverse effects transparently; Encourage value-chain partners to adopt; Proactively respond to violators |
| **P2** | Safe & Sustainable Goods & Services | Goods/services/operations should improve consumers' lives; core elements — Minimise resource use in design/production; Spread awareness among consumers; **RRR** — reduce, reuse, recycle |
| **P3** | Well-being of Employees (incl. value chain) | Core elements — Compliance with regulatory requirements; Dignity & Freedom (association/collective bargaining); prevent Child/bonded Labour; Work-life balance; Timely payment of wages; pay Living wages; Harassment-free workplace |
| **P4** | Respect Stakeholders' Interests & Responsiveness | Core elements — Disclose Impact of operations transparently; Determine Context/identify interested parties; Share Benefits equitably |
| **P5** | Respect & Promote Human Rights | Core elements — Understanding of human rights (Constitution, national law, International Bill of Human Rights); integrate into Mgt systems; Respect all stakeholders incl. vulnerable/marginalised groups |
| **P6** | Protection & Restoration of the Environment | Core elements — Policies covering full product life-cycle; Optimum use of natural/man-made resources; Measure performance (pollution, deforestation, waste, energy, land use); Climate-change initiatives (Paris Agreement, National Action Plans); adopt Best practices in reduce/reuse/recycle |
| **P7** | Influence Public & Regulatory Policy | Contribute to policy formulation/advocacy; use collective associations (trade/industry bodies); advocacy should encourage fair competition & prevent human-rights abuses |
| **P8** | Promote Inclusive Growth & Equitable Development | Core elements — Systems to identify/address social-cultural-economic impacts (e.g., land acquisition); track Adverse impacts & mitigate; Creativity for marginalised communities; align CSR with local/regional priorities; avoid unfair Displacement of communities (fair compensation where unavoidable) |
| **P9** | Provide Value to Consumers Responsibly | Core elements — Reduce negative impact of products/services; preserve Freedom of choice & fair competition; Transparency on adverse impacts; Privacy of customer data; Inform customers on safe use/disposal; avoid Misleading ads; provide Grievance redressal; ensure Universal access to essential goods/services |

**Pitfalls / exam tips**
- Mnemonic hooks used in class notes: P4 = "POS" (disclose impact, determine context, share benefits); P5 = "UMR" (understanding, mgt systems, respect all).
- P6 (Environment) is the clearest "pure E" principle — if a question mentions climate change/Paris Agreement, it is testing P6.

---

### Assurance in BRSR — SSAE 3000 & SSAE 3410

- **Key rule:** ICAI has issued **Standard on Sustainability Assurance Engagements (SSAE) 3000** — "Assurance Engagements on Sustainability Information." It applies to **all assurance engagements on sustainability information**, providing either **reasonable or limited assurance**.
- **Intended users of SSAE 3000:**
  - Assurance providers giving assurance on sustainability information.
  - Entities seeking to engage a professional auditor.
  - Regulators, investors & other users of sustainability reporting data.
- **Effective date of application:**
  - **Voluntary basis** — for assurance reports covering periods ending on **31.03.2023**.
  - **Mandatory basis** — for assurance reports covering periods ending **on or after 31.03.2024**.
- **SSAE 3410** — "Assurance Engagements on Greenhouse Gas Statements" — deals with assurance on an entity's sustainability information, **including assurance of BRSR** (India's equivalent of the international ISAE 3410).

**Methodology to provide assurance on BRSR (sequence):**
1. Preliminary review of ESG report & parameters.
2. On-site assessment / verification of the ESG report.
3. Submission of findings of on-site assessment & document review.
4. Review of management's responses/clarifications on findings.
5. Preparation of Assessment/Verification report, incl. results & recommendations.
6. Issuance of the Assessment Report & Assessment Statement.

**Definitions**

| Term | Meaning |
|---|---|
| SSAE 3000 | ICAI standard governing assurance engagements on sustainability information (reasonable/limited assurance) |
| SSAE 3410 | ICAI standard governing assurance on GHG statements/sustainability info incl. BRSR |
| Reasonable assurance | Higher level of assurance — auditor's opinion expressed positively ("in our opinion...") |
| Limited assurance | Lower level of assurance — opinion expressed negatively ("nothing has come to our attention...") |

**Pitfalls / exam tips**
- Remember exact cut-off dates: **31.03.2023 = voluntary**, **31.03.2024 onward = mandatory** — a classic date-based MCQ.
- SSAE 3000 = general sustainability info; SSAE 3410 = specifically GHG statements (but also usable for BRSR assurance) — don't conflate the two standard numbers.

---

### Role of the Auditor — Climate-Related Risks in a Financial Statement Audit

- **Concept:** The auditor's core objective (per the SA 200 series) remains to obtain reasonable assurance that the FS are free from material misstatement (fraud or error) and to report whether they are prepared, in all material respects, per the applicable financial reporting framework (AFRF). Climate-related risk is layered onto this existing objective, not a separate assurance regime.
- **How climate risk feeds into the audit:**
  - While **understanding the entity** (SA 315), the auditor considers climate-related risks and how they are relevant to the audit (e.g., impact on going concern, asset impairment, provisions/contingencies).
  - **Sector relevance** — climate-related risks are more significant in: banks & insurance, energy, transportation, materials & buildings, agriculture, food & forestry.
  - The audit report, in addition to the opinion, may need to communicate **Key Audit Matters (KAM)** where climate-related matters were of most significance (SA 701 concept — "matters of most significance... and how they were addressed").
  - An **Emphasis of Matter (EOM)** paragraph (SA 706) may be used to draw attention to disclosures fundamental to users' understanding, where relevant.
  - The auditor determines whether the entity has **appropriately disclosed climate-related information** in the FS as required by the AFRF (e.g., Ind AS/AS).
  - Under **SA 720** ("The Auditor's Responsibilities Relating to Other Information"), the auditor reads *other information* — e.g., the management report in the annual report, press releases, investor updates — for consistency with the audited FS and with the auditor's knowledge obtained during the audit.

**Pitfalls / exam tips**
- The audit report must still follow the **applicable SAs** — there is no separate "climate SA"; climate risk is assessed *through* SA 315 (risk assessment), SA 701 (KAM), SA 706 (EOM), and SA 720 (other information).
- A common exam trap: students think SSAE 3000/3410 apply to the *financial statement* audit — they don't; SSAE 3000/3410 are for the *separate* sustainability-information assurance engagement (e.g., on the BRSR), while climate risk in the FS audit is handled entirely within the standard SA framework.

---

### Global Trends in Sustainable Reporting

- **Concept:** Mandatory sustainability reporting is mostly associated with the public sector/government-run companies, large corporations, MNCs, and listed companies on stock exchanges; smaller/private entities mostly report voluntarily.

**Three major global frameworks:**

| Framework | Focus | Addressed to |
|---|---|---|
| **GRI — Global Reporting Initiative** Sustainability Reporting Standards | Economic, Environmental & Social impacts; most widely used global framework, used in 100+ countries; independent international org. headquartered in Amsterdam, Netherlands, with regional operations in Brazil, China, Colombia, India, South Africa & the US | All stakeholders of the entity |
| **CDP — Carbon Disclosure Project** | Environmental performance data on GHG emissions, water, forests & supply chain; key reported details — climate change, forests, water security | Investors, buyers & other stakeholders |
| **IIRC — International ⟨IR⟩ Framework** | Guiding principles & content elements enabling companies to produce integrated reports — organisational overview, governance structure, business model, risks & opportunities, strategy, performance, outlook | General purpose — all report users |

- ⚠️ VERIFY — the source notes state **"93% of the world's largest 250 corporates report through GRI."** A widely cited independent figure (KPMG Survey of Sustainability Reporting, 2022) instead puts GRI adoption among the G250 (world's 250 largest companies by revenue) at approximately **78%**. The exact percentage varies by survey/year (KPMG's N100/G250 surveys are published every 2 years) — quote the underlying "most widely used framework" fact confidently, but verify the specific percentage against your current ICAI module/latest KPMG survey before using it as a standalone numeric answer.

**Pitfalls / exam tips**
- Distinguish the 3 frameworks by their *addressee* and *focus*: GRI → all stakeholders/broad EES; CDP → investors/climate-and-water-specific; IIRC → integrated value-creation story (the 6 capitals).

### References
1. ICAI, Standard on Sustainability Assurance Engagements (SSAE) 3000, "Assurance Engagements on Sustainability Information" — effective dates (voluntary for periods ending 31.03.2023; mandatory for periods ending on/after 31.03.2024) and SSAE 3410 "Assurance Engagements on Greenhouse Gas Statements," as issued by ICAI's Sustainability Reporting Standards Board.
2. SEBI Circular No. SEBI/HO/CFD/CMD-2/P/CIR/2021/562 dated 10 May 2021 — "Business Responsibility and Sustainability Reporting by Listed Entities" (BRSR framework; applicability to top 1,000 listed companies by market capitalisation).
3. Standards on Auditing (SAs) as issued by ICAI — SA 315 (Risk Identification & Assessment), SA 701 (Key Audit Matters), SA 706 (Emphasis of Matter Paragraphs), and SA 720 (The Auditor's Responsibilities Relating to Other Information).
4. KPMG, "Survey of Sustainability Reporting" (2022 edition) — cited (via secondary source) for GRI adoption rate among the world's 250 largest companies (G250); used here only to flag the OCR's "93%" figure for verification.
5. International Integrated Reporting Council (IIRC), International ⟨IR⟩ Framework — the 6 capitals model and India's voluntary top-500 IR practice.

## 15. Digital Audit & Emerging Areas
> **Where it fits:** Covers how the auditor responds to an automated/digital business environment — CAATs and audit-analytics tools, and the audit implications of IoT, AI, Blockchain, RPA, Drones and the Metaverse — read together with SA 315 (Revised) "understanding the entity's IT environment," SA 330 and SA 500.

### 15.1 Digital Audit — Meaning, Advantages & Considerations
- **Key rule(s):**
  - Digital audit = use of technology tools/automation to perform audit procedures on entity data, replacing manual, sample-based routines with system-driven, full-population procedures.
  - Advantages: (i) Enhanced effectiveness & efficiency through standardised, automated processes and controls; (ii) Better analytics — scanning trends/patterns across full populations; (iii) Improved risk assessment — testing effort directed by data-driven insights (higher ROI on procedures); (iv) Better audit quality — rapid, accurate evaluation of large data volumes highlights areas needing more testing; (v) Lower costs of auditing through automation; (vi) Increased transparency — audit-trail features in new ERPs/tools make transactions easier to trace.
  - Considerations/challenges before automating: think people first (change management is hard); target and standardise the right process before automating it; automation must be part of a broader digitalisation strategy, not a standalone fix; invest in training/digital upskilling.
- **Concept:** Digital audit is the shift from sample-based, manual testing to technology-enabled, full-population, analytics-driven auditing.
- **Pitfalls / exam tips:**
  - Don't automate a broken/non-standardised process — automation only scales what already works.
  - In exam answers, always pair "advantage" with the matching "challenge/consideration" — examiners test both sides.
- **Definitions:**

| Term | Meaning |
|---|---|
| Digital Audit | Use of technology/automation tools to plan and perform audit procedures on entity data |
| ROI (audit context) | Return on the investment of audit effort/tool cost measured against risk coverage achieved |

### 15.2 Data Analytics & CAATs
- **Key rule(s)/tools:**
  - CAATs (Computer Assisted Audit Techniques) = data extraction and analysis software used by auditors to discover and analyse patterns, identify anomalies, and extract other useful information from an entity's data — enabling full-population testing instead of sampling.
  - Commonly used CAAT tools:
    - **ACL (Audit Command Language) Analytics** — data extraction & analysis software used for fraud detection/prevention and risk management; scans large data sets for irregularities/patterns indicating control weaknesses or fraud; used e.g. for Trial Balance reconciliation where the entity provides a GL dump and system TB.
    - **Alteryx** — workflow-based analytics automation tool; transparent audit trail of every step performed (as a workflow), easy to learn (no coding/scripting needed); used to automate recurring procedures (reconciliations, consolidations) and apply machine learning to detect patterns of fraud/irregularities.
    - **Power BI** — a Business Intelligence (BI) platform for non-technical users to aggregate, analyse, visualise and share data; from an audit perspective, used to identify outliers in a population and for reporting to management.
    - **CaseWare** — audit engagement/data-analysis software; helps conduct engagements quickly, accurately and consistently; streamlines routine tasks, links to client data, and supports assurance/reporting workflows.
  - Illustrative CAAT test types set by auditors:
    - *Identify exceptions* — transactions breaching a set criterion, e.g. cash transactions above ₹10,000.
    - *Identify errors* — data that is inconsistent or erroneous, e.g. a non-numeric account number.
    - *Verify calculations* — re-perform computations (e.g. TDS rate applied per criteria) and reconcile with the application software's results.
    - *Data completeness* — check whether all mandatory fields are populated (no nulls in date, invoice number, value, name, etc.).
    - *Data consistency* — check data conforms to the expected format/sequence, e.g. invoices out of the required numbering sequence.
- **Concept:** CAATs let the auditor apply audit procedures (recalculation, exception-testing, pattern analysis) across 100% of the population using software, rather than a sample.
- **Pitfalls / exam tips:**
  - CAATs are a technique to gather audit evidence, not a substitute for professional judgement in evaluating that evidence (SA 500 considerations on evaluating information produced by the entity still apply).
  - In numericals/case studies, match the tool's stated feature to the fact pattern (e.g. "workflow with no coding" → Alteryx; "outlier dashboard for management" → Power BI).
- **Definitions:**

| Term | Meaning |
|---|---|
| CAATs | Computer Assisted Audit Techniques — software-based data extraction/analysis techniques used in audit |
| Full population testing | Applying audit procedures to every item in a population instead of a sample |

### 15.3 Internet of Things (IoT)
- **Key rule(s):**
  - IoT = the concept of connecting any device (phones, appliances, sensors, etc.) to the internet.
  - Key components: data collection, analytics, connectivity, and people & process.
  - Audit implications:
    - New transaction/payment paths (e.g. mobile/contactless payment at retail locations) — auditor must consider volume of transactions, processes, and related contracts.
    - **Control testing:** the shift to connected devices/systems means auditors cannot rely on manual controls alone; new (automated) systems must be scoped into the audit, and auditors need training/upskilling to evaluate the design and operating effectiveness of automated controls.
  - Common risks: device hijacking, data snooping/leakage, denial-of-service (DoS) attacks, data breaches, and device theft.
- **Concept:** IoT expands the entity's IT boundary to networked devices, so the auditor's scope and control-testing approach must expand with it.
- **Pitfalls / exam tips:** In case studies, always link an IoT risk (e.g. device theft) to the specific control response (physical + access controls over the device fleet), not just a generic "IT risk" answer.
- **Definitions:**

| Term | Meaning |
|---|---|
| IoT | Network of physical devices connected to and exchanging data over the internet |

### 15.4 Artificial Intelligence (AI)
- **Key rule(s):**
  - AI = systems/machines that can "think and learn"; they use data analysis and algorithms to make decisions based on predictive methods, with complex algorithms proposing decisions from patterns/behaviour learned over time.
  - Examples: self-driving cars, manufacturing robots, smart assistants, virtual travel-booking agents (predicting the lowest fare/hotel price from historical data), automated hiring tools.
  - Illustrative shift AI/automation brings to processes (e.g. recruitment, and by extension audit):

| From | To |
|---|---|
| Sampling | Full population analysis |
| Multiple datasets | One (integrated) dataset |
| Disconnected tools | Integrated ecosystem/services |
| Manual/static risk assessment | Dynamic, data-driven risk assessment |
| Separate communication | Embedded communication |
| Repetitive tasks | High-value work & capacity for growth |
| Manual work | Automation |
| Ad hoc insight | Insight from the broader audit |

- **Concept:** AI moves decision-support from static, sample-based judgement to dynamic, pattern-driven prediction across full data sets.
- **Pitfalls / exam tips:** AI-based automated hiring/decision tools raise their own control questions (bias in the algorithm, data used to train it) — treat the algorithm itself as a "system" whose inputs, logic and outputs need audit consideration, not a black box to be trusted blindly.
- **Definitions:**

| Term | Meaning |
|---|---|
| Artificial Intelligence | A system/machine that learns from data and proposes/ makes decisions using predictive algorithms |

### 15.5 Blockchain (incl. NFTs)
- **Key rule(s):**
  - Blockchain = a decentralised and distributed ledger secured through cryptography/encryption. Each transaction is validated by network participants, creating a "block" of information that is replicated and distributed to all participants; blocks are sequenced (chained) so that modifying or deleting any one block invalidates the related chain.
  - Examples: Bitcoin/cryptocurrency, money-transfer applications, blockchain-based smart contracts, NFTs.
  - Audit implications:
    - **Governance & security** — assess governance and security measures around transactions, including cryptographic key management and related risks.
    - Blockchain interacts with legacy systems/business partners via APIs — data confidentiality and privacy concerns cannot be ignored; weaknesses in the blockchain application's development process cannot be overlooked.
    - **Data privacy/residency** — where data sits on the blockchain (which jurisdiction/nodes) can expose the entity to liability, including reporting considerations under NOCLAR (SA 250 (Revised)).
  - Common risks (the strengths of blockchain are also its weaknesses):
    - Inability to reverse transactions and inaccessibility of data without the private key make the system secure — but this also means the organisation needs specific protocols/contingency plans so it is not permanently locked out (e.g. of a lost key).
    - Operating through distributed network nodes also exposes the organisation to cyber-attacks and data theft.
  - NFTs (Non-Fungible Tokens): unique digital-ownership tokens exchanged/traded on specialised platforms; key challenges — ownership/copyright disputes, security risks, market-value instability, and fraud.
- **Concept:** Blockchain's audit relevance is less about the algorithm and more about governance, key/access controls, and third-party/API interfaces around it.
- **Pitfalls / exam tips:** Do not describe blockchain as "un-hackable" in an answer — frame the risk correctly as key-management/access-control risk and node-level cyberattack risk.
- **Definitions:**

| Term | Meaning |
|---|---|
| Blockchain | Decentralised, distributed, cryptographically-secured ledger of chained, replicated transaction blocks |
| Smart Contract | Self-executing contract terms coded onto a blockchain |
| NFT | Non-Fungible Token — a blockchain-based unique digital ownership record |

### 15.6 Robotic Process Automation (RPA)
- **Key rule(s):**
  - RPA = software technology ("bots") that automates repetitive, rule-based, high-volume tasks (data extraction, aggregation, information gathering) the way a human user would — operating around the clock, faster, and with high reliability/precision.
  - Audit implications:
    - It is important to understand the RPA process (data extraction, aggregation, sensitisation/classification) — without this understanding, the auditor cannot properly plan the audit of a bot-driven process.
    - A comprehensive assurance procedure may require review of the bot's underlying logic/"source code."
    - Review logs, configuration controls, privileges, and access controls over the bots.
  - Common risks: operational and execution risk (bots processing exceptions/errors without human judgement, or being misconfigured).
- **Concept:** RPA bots replace manual, repetitive transaction processing — audit focus shifts from "who did this" to "what is the bot configured to do, and who can change that configuration."
- **Pitfalls / exam tips:** Treat RPA controls like IT general controls — access, change-management (configuration) and monitoring/logging controls are the three areas examiners typically test.
- **Definitions:**

| Term | Meaning |
|---|---|
| RPA | Robotic Process Automation — software bots automating rule-based, repetitive digital tasks |

### 15.7 Auditor's Response to a Changing Technology Environment
- **Key rule(s)/control considerations:**
  1. Gain a holistic understanding of changes in the industry and the entity's IT environment, to properly evaluate the process for initiating, processing and recording transactions, and design appropriate audit procedures accordingly.
  2. Consider risks resulting from the implementation of new technologies, and how these risks may differ from those arising in more traditional/legacy systems.
  3. Consider whether digital upskilling of the audit team, or involvement of a specialist (e.g. cybersecurity expert, IT specialist — per SA 620 read with SA 315), is necessary to assess and understand new technologies and the operating effectiveness of related controls.
  4. Perform a cybersecurity risk assessment and understand the operating effectiveness of related controls.
  - Categories of risk arising from IT that auditors test for (SA 315 (Revised)):
    - Reliance on systems/programs that inaccurately process data.
    - Unauthorised access to data that may result in destruction of, or improper changes to, data.
    - Unauthorised or erroneous changes to master data or to systems/programs.
    - Potential loss of data, or inability to access data as required.
    - Inappropriate manual intervention.
- **Concept:** As the IT environment gets more complex, the auditor's response shifts from testing manual controls to testing IT general controls (access, change management, operations) and considering specialist involvement.
- **Pitfalls / exam tips:** In theory answers, always link each new-technology risk back to one of the five SA 315 IT-risk categories above — examiners reward this mapping.
- **Definitions:**

| Term | Meaning |
|---|---|
| IT General Controls (ITGCs) | Controls over access, program change, computer operations and program development that support reliable functioning of application controls |

### 15.8 Drone Technology
- **Key rule(s):**
  - Drones are used in remote/large/hazardous locations to assist physical verification (e.g. inventory stock counts); their payload capacity allows carrying sensors/cameras to photograph and physically examine large quantities.
  - Data captured by drones can be combined with other data-intensive analytics services for reconciliation with book records.
- **Concept:** Drones extend the auditor's ability to perform physical observation/verification (SA 501) where manual attendance is impractical or unsafe.
- **Pitfalls / exam tips:** Drone footage is still audit evidence — the auditor must evaluate its reliability, ensure appropriate cut-off, and corroborate with other procedures; it does not by itself satisfy completeness/existence assertions.

### 15.9 Metaverse & Emerging Considerations
- **Key rule(s)/considerations for the future:**
  - The Metaverse is an immersive, persistent digital environment (built on AR/VR, cryptographic and networking technology) blending real and virtual personal/business experiences.
  - Key considerations auditors/entities must think through:
    - **Governance** — balancing openness and user contribution against the platform's strategic direction and control, including governance over digital assets (e.g. digital land, in-platform currencies).
    - **Identity** — verifying identity in a historically pseudonymous digital world raises KYC-type challenges.
    - **Synchrony** — the ability of aspects of the Metaverse to occur simultaneously/in real time depends on the underlying network and computing infrastructure of the digital economy.
    - **Data privacy and analytics** — visualisation/analytics support decision-making but also raise data-privacy questions over personal/behavioural data captured in the environment.
- **Concept:** The Metaverse is an emerging-risk area rather than a settled audit topic — current guidance is directional (governance, identity, synchrony, privacy), not yet standard-prescribed.
- **Pitfalls / exam tips:** ⚠️ VERIFY — ICAI has not (as of the current syllabus) issued a dedicated Standard on Auditing for Metaverse/digital-asset engagements; treat this sub-topic as descriptive/professional-judgement material rather than a source of testable numeric rules, and confirm against the latest ICAI study material before the exam.

### References
1. SA 315 (Revised), *Identifying and Assessing the Risks of Material Misstatement Through Understanding the Entity and Its Environment* — ICAI (basis for the IT-environment risk categories and auditor's response in section 15.7).
2. SA 330, *The Auditor's Responses to Assessed Risks* — ICAI (design of audit procedures in an automated/IT environment).
3. SA 500, *Audit Evidence* — ICAI (evaluating information produced by the entity, including CAAT-extracted data, per section 15.2).
4. SA 250 (Revised), *Consideration of Laws and Regulations* — ICAI (NOCLAR reporting angle referenced under Blockchain data-residency risk, section 15.5).
5. ICAI Guidance Note on Audit in an Automated Environment — ICAI (background for CAATs, IT general controls, and digital-audit tooling discussed across this chapter).

## ⚠️ Formulas to double-check


**00. Basics of Audit (SA 200, Audit Evidence & Procedures, SA 210/230)**
- ⚠️ VERIFY — the Revised SA 315 (effective for audits of periods beginning on/after 1 April 2022) technically **folds disclosure assertions into the "classes of transactions/events" and "account balances" categories** rather than treating "Presentation & Disclosure" as a fully separate third category; the source notes above follow the older/simplified three-column teaching structure still commonly used for revision — confirm the exact current-syllabus presentation against the latest ICAI SA 315 (Revised) material before quoting the third column verbatim in an answer.
- ⚠️ VERIFY — the source excerpt (OCR) ends before covering the final-assembly and retention timelines. Per SA 230 as issued by ICAI, the auditor ordinarily should assemble the final audit file **not later than 60 days** after the date of the auditor's report, and should retain audit documentation for a period of **not less than 7 years** from the date of the auditor's report (or, if later, the date of the group auditor's report) unless a longer period is specified by law or regulation — these two figures could not be cross-checked against a live source this session; confirm against the current ICAI SA 230 text before quoting in an answer.
- Note: Web-search verification could not be completed in this session (search tool budget exhausted); the above content and figures reflect domain knowledge of the SAs as issued by ICAI. Items not independently re-confirmed this session are marked ⚠️ VERIFY.

**01. SQC-1 & Standards on Auditing 200-700 Series (SA 220 through SA 720)**
- ⚠️ VERIFY — Familiarity threat safeguard: rotation of the engagement partner on listed-entity audits after **7 years** of continuous association, followed by a "cooling-off" period before re-engagement (the exact cooling-off duration is not stated in the source notes; cross-check the current ICAI Code of Ethics provision before quoting a number in the exam).
- ⚠️ VERIFY — The Rule 3 monetary thresholds (commonly cited as paid-up capital ≥ ₹500 crore, or annual turnover ≥ ₹1,000 crore, or aggregate outstanding loans/debentures/deposits ≥ ₹500 crore, as at the end of the immediately preceding financial year, apart from listed companies, banks, insurers, and electricity companies) could not be re-verified against a live source this session — confirm exact figures from NFRA Rules, 2018 before quoting them in an answer.

**02. Professional Ethics (Fundamental Principles, Threats, NOCLAR, Schedules, Council Guidelines, ESB Decisions)**
- ⚠️ VERIFY — the source lists "portfolio management, underwriting & broking (PUB)" as explicitly **not permitted** as MCS — this is well established, but double-check the exact current wording in the latest Code of Ethics before quoting verbatim in an answer.
- ⚠️ VERIFY — the source concept-book states **"30 audits per CA in full time practice allowed."** The figure well established in the current CA Final syllabus and under Section 141(3)(g), Companies Act 2013, is **20** companies per person (excluding One Person Companies, dormant companies, small companies, and private companies with paid-up share capital below ₹100 crore) — this guide uses **20** as the correct/verified figure; confirm against the latest Study Material/RTP before quoting the exact number in an exam answer, since I could not complete a live web-verification for this specific figure in this session.
- ⚠️ VERIFY — these 20%/40% fee-concentration disclosure percentages are as transcribed from the source material; confirm the exact current percentages and the precise Council Guideline reference against the latest ICAI Study Material, as this could not be cross-checked with a live source in this session. Exemptions: total firm fees ≤ ₹20 lakh; or audits of Government companies/public undertakings/nationalised banks/public financial institutions/regulators where the auditor is Government-appointed.
- **Pitfalls / exam tips:** ⚠️ VERIFY — the source material available for this chapter only summarised the closing stages of the disciplinary flow (finding, appeal, and Appellate Authority orders); the finer jurisdictional split between the Board of Discipline and Disciplinary Committee, and the exact composition/quorum of each, should be cross-checked against the standalone "Disciplinary Mechanism" topic in the Study Material, as it was not fully legible in the source and could not be independently web-verified in this session.

**03. CARO 2020 & Company Audit**
- **Pitfalls / exam tips:** ⚠️ VERIFY — the OCR source does not state the numeric CIC qualifying criteria (asset size / investment pattern thresholds under RBI's CIC Master Directions); do not assume a figure — confirm against the current RBI Master Direction – Core Investment Companies before quoting any number in an answer.
- **Pitfalls / exam tips:** ⚠️ VERIFY — the OCR does not carry the further sub-timelines under Sec 135(6) (e.g., the requirement to spend the Unspent CSR Account balance within 3 financial years, failing which transfer to a Schedule VII fund within 30 days of expiry of the third year); confirm the exact day-counts against Sec 135(6) before citing them.
- *(Note: this session's live web-verification budget was exhausted before the dedicated CARO/Companies Act searches could run; the figures above rest on the faculty source cross-checked against the reviewer's standing domain knowledge of CARO 2020, the Companies Act, 2013 and CAAR 2014 as in force for the 2026 CA Final syllabus. The two items explicitly marked ⚠️ VERIFY — RBI CIC qualifying criteria and the Sec 135(6) sub-timelines — could not be numerically confirmed from the OCR and should be cross-checked by the student against the current RBI Master Direction and Sec 135(6) text respectively before exam use.)*

**04. Audit Planning, Risk Assessment & Internal Control**
- ⚠️ VERIFY — **COBIT Framework** (Control Objectives for Information and Related Technology, issued by ISACA/IT Governance Institute): the source states "34 high-level IT processes covering 210 control objectives." This figure corresponds to the older **COBIT 4.1** structure commonly cited in ICAI study material; the current **COBIT 2019** framework instead organises around 40 governance/management objectives — confirm which version's figures your attempt's syllabus expects before quoting the number in an exam.

**05. Group Audit (SA 600)**
- ⚠️ VERIFY — the OCR does not spell out a numeric benchmark/percentage for setting component materiality relative to group materiality; the underlying principle (component materiality is set **lower** than group materiality, to reduce the risk that the aggregate of uncorrected/undetected misstatements across components exceeds group materiality) is a well-established SA 600/SA 320 concept but no specific percentage should be quoted without the primary text.

**06. Bank Audit & NBFC Audit**
- **CTS (Cheque Truncation System):** electronic cheque image transmitted with MICR/date/presenting-bank details; per RBI, branch should call/e-mail the customer for any inward-clearing cheque of **₹5 lakh and above** (verify on test-check basis). ⚠️ VERIFY — figure/practice matches CA-Final material but confirm against the current RBI cheque-clearing/risk-mitigation circular for the exact monetary limit.
- **Government-guaranteed advances:** overdue > 90 days but **NOT classified NPA** for asset-classification/provisioning purposes as long as the **Central Government** guarantee has not been repudiated when invoked (income recognised on realisation basis). ⚠️ VERIFY exception does **not** apply to State Government guarantees — SG-guaranteed advances **are** treated as NPA once overdue beyond 90 days, per the source material; confirm current wording in the applicable RBI Master Direction/Master Circular on Income Recognition, Asset Classification & Provisioning (IRACP) for banks.
- **Bulk deposits:** verify correct (higher) rate of interest offered on single Rupee term deposits of **₹2 crore and above** for scheduled commercial banks. ⚠️ VERIFY — RBI has periodically revised the bulk-deposit threshold (reported at ₹3 crore effective January 2024 in more recent RBI instructions); confirm the figure applicable for the year under audit against the latest RBI Master Direction on interest rates on deposits before quoting in the exam.
- RBI requires banks to maintain a **minimum CRAR of 9%** of risk-weighted assets (Basel III minimum, before the Capital Conservation Buffer). ⚠️ VERIFY — with the Capital Conservation Buffer (2.5%) layered on, the effective minimum for most banks works out higher; confirm the exact figure(s) quoted in the current RBI Master Circular on Basel III Capital Regulations before an exam answer.
- ⚠️ VERIFY — this glide path (RBI's phased move to the 90-day NPA norm) applied to specific NBFC categories that were earlier on a 180-day norm; confirm which layer(s)/category of NBFC it currently applies to, and that the final 90-day norm milestone (31 March 2026) is still the operative date for the 2026 attempt, against the latest RBI Master Direction on NBFC-SBR / IRACP norms.

**07. PSU Audit**
- ⚠️ VERIFY — the OCR reference to "(Nov 31/4)" against Functions of Auditor in Propriety Audit could not be reliably matched to a specific exam attempt/marks allocation; treat as an indicative past-exam tag only, not a confirmed citation.

**08. Internal Audit & SA 610 (Using the Work of Internal Auditors)**
- ⚠️ VERIFY — OCR references **"SIA 370 – Reporting"** (a Standard on Internal Audit issued by ICAI's Internal Audit Standards Board) as the source of the two-stage reporting requirement below; confirm the exact SIA number/title against the current ICAI Internal Audit Standards Board publication before quoting it in an exam.
- ⚠️ VERIFY — the OCR's detailed list of "factors to be considered while evaluating the existence & significance of threats to objectivity of the Internal Auditor" is illegible ("[Unreadable]") in the source; per SA 610 (Revised), such factors generally include threats arising from self-review, familiarity, or undue reliance on management, and whether the IA function's policies/rotation practices safeguard objectivity — confirm the complete factor-list against the ICAI SA 610 (Revised) text before using it verbatim in an answer.
- 5. Domain/professional knowledge of ICAI's Standards on Internal Audit (SIA) framework issued by the Internal Audit Standards Board, used to reconstruct the two-stage reporting content (flagged ⚠️ VERIFY above for the exact SIA number/title, as this session's web-verification budget was unavailable).

**09. Due Diligence, Forensic Accounting & Investigation**
- ⚠️ VERIFY — ICAI's Digital Accounting and Assurance Board (DAAB) has issued a set of Forensic Accounting and Investigation Standards (FAIS) applicable to members conducting forensic accounting and investigation engagements (widely cited effective date: **1 July 2023**); the exact standard numbering/count should be cross-checked against the current ICAI FAIS publication before quoting specific standard numbers in the exam.
- ⚠️ VERIFY — Investigation into the affairs of a company can be ordered by the Central Government under **Section 210**, Companies Act 2013 (on Registrar's/inspector's report, on a company's special resolution, or in the public interest).
- ⚠️ VERIFY — **Section 211** establishes the **Serious Fraud Investigation Office (SFIO)**; **Section 212** deals with investigation by SFIO into a company's affairs, which becomes mandatory in specified circumstances (e.g., Central Government direction, report under s. 208, or public interest) and, once assigned to SFIO, no other investigating agency may proceed with a parallel probe into the same matter.
- ⚠️ VERIFY — **Section 213** empowers the Tribunal (NCLT) to order an investigation into a company's affairs on application by members (commonly cited threshold: not less than 100 members, or members holding not less than one-tenth of total voting power for a company with share capital; not less than one-fifth of persons on the register for a company without share capital) or by any other person, where the Tribunal is satisfied of circumstances suggesting fraud, oppression, or non-disclosure of full information to members — this threshold figure should be cross-checked against the bare Act before being quoted as an exact number in the exam.
- ⚠️ VERIFY — **Section 216** empowers the Central Government to appoint inspectors to investigate and report on the **true persons** who are or have been financially interested in, or in control of, the company's policy — i.e., investigation of beneficial ownership.

**10. SA 800 Series (SA 800/805/810 - Special Purpose & Single FS Audits)**
- ⚠️ VERIFY — This chapter's content was reconstructed primarily from the source concept-book OCR plus standing subject-matter knowledge of SA 800/805/810; the web-search verification pass could not be completed in this session (search budget exhausted before any query ran). Before relying on this chapter for the exam, cross-check the exact wording of the two SA 810 opinion phrases and the SA 805 "major portion" exception conditions against the current ICAI SA text/study material.

**11. Standards on Review Engagements (SRE 2400 & 2410)**
- **Rule — UDIN:** ⚠️ VERIFY — per the source notes, **UDIN must be generated and stated** for review engagements performed under SRE 2400 or SRE 2410 (review reports fall within ICAI's UDIN mandate for assurance/attest functions) — confirm the current UDIN circular/applicability at the time of the attempt, as ICAI periodically updates the UDIN mandate list.
- 4. ⚠️ VERIFY — UDIN applicability to SRE 2400/2410 review reports: confirm against the current ICAI UDIN Directorate FAQ/circular in force for the attempt, as this session's live web verification could not be completed (search budget exhausted) — reconstructed from the source notes' explicit statement that UDIN is mandatory for SRE 2400/2410 engagements.

**13. Standards on Related Services (SRS 4400 & 4410)**
- ⚠️ VERIFY — the effective date of the Revised SRS 4400 (applicable to AUP reports issued on or after a specified date) is not stated in the source material and was not independently re-verified in this session (web search budget was exhausted); confirm the applicability date against the current ICAI Study Material/RTP before relying on it in an exam answer if the question specifically tests the effective date.

**14. SDG & ESG Assurance (Sustainability Reporting)**
- ⚠️ VERIFY — the source notes state the 9 principles split as **"2 in Environment, 3 in Social & 4 in Governance."** This E/S/G mapping is not uniformly stated the same way across all ICAI study material/SEBI guidance notes (some categorise P4 and P9 differently); use the principle names/content below with confidence, but treat the exact 2-3-4 numeric split as needing a cross-check against your institute's current module before quoting it as a standalone MCQ answer.
- ⚠️ VERIFY — the source notes state **"93% of the world's largest 250 corporates report through GRI."** A widely cited independent figure (KPMG Survey of Sustainability Reporting, 2022) instead puts GRI adoption among the G250 (world's 250 largest companies by revenue) at approximately **78%**. The exact percentage varies by survey/year (KPMG's N100/G250 surveys are published every 2 years) — quote the underlying "most widely used framework" fact confidently, but verify the specific percentage against your current ICAI module/latest KPMG survey before using it as a standalone numeric answer.

**15. Digital Audit & Emerging Areas**
- **Pitfalls / exam tips:** ⚠️ VERIFY — ICAI has not (as of the current syllabus) issued a dedicated Standard on Auditing for Metaverse/digital-asset engagements; treat this sub-topic as descriptive/professional-judgement material rather than a source of testable numeric rules, and confirm against the latest ICAI study material before the exam.