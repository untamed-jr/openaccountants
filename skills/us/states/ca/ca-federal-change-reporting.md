---
name: ca-federal-change-reporting
description: >
  Reporting IRS changes and federal amended returns to the California Franchise
  Tax Board (FTB) for individuals and corporations: the six-month reporting
  duty after a final federal determination (R&TC 18622), what counts as the
  final federal determination (the IRC 6203 assessment date), who must report
  (individuals only when California tax goes up; corporations every change),
  how to report (amended Form 540 with Schedule X, Form 100X, Form 109,
  notification letter or fax, with the federal report attached), what timely,
  late or no reporting does to FTB's assessment window (two years, four years,
  or open: R&TC 19059, 19060), and the two-year refund window for federal
  decreases (R&TC 19311), including the multi-year trap where an unclaimed
  overpayment cannot offset an assessment. Not partnership-level (BBA) audit
  reporting under R&TC 18622.5, which SB 1435 (2026) amended, or the federal
  audit itself. Trigger on "IRS audit California report", "final federal
  determination", "R&TC 18622", "FTB Publication 1008", "RAR to FTB",
  "Schedule X federal changes", "six months report IRS changes California".
version: 0.1
jurisdiction: US-CA
category: state-tax
tax_year: 2026
last_updated: 2026-11-23
tier: 2
domain: tax
type: computation
---

# Reporting federal changes to California, R&TC 18622 (2026) v0.1

> **General reference only.** This skill is general tax/accounting reference material for AI-assisted workflows. It has not been reviewed for any specific person's facts, documents, elections, deadlines, residency, filing status, or local procedures. Do not rely on it to file, pay, amend, or take a tax position without review by a qualified professional in the relevant jurisdiction.

> **Source-cited draft.** Built from Revenue and Taxation Code (R&TC) 18622, 18622.5 (scope only), 19059, 19060 and 19311, read in the official California Legislature bulk data archive, together with SB 1435 (Stats. 2026, Ch. 236) in the same archive; FTB Publication 1008, Federal Tax Adjustments and Your Notification Responsibilities to California (revised 05/2020); and FTB's federal changes page (last updated 09/24/2025). All were read on 2026-11-23 (California, Pacific time). No accountant has reviewed it.

**Answer first.** When the IRS changes an item on a federal return, the taxpayer "shall report each change or correction ... within six months after the date of each final federal determination of the change or correction ... and shall concede the accuracy of the determination or state wherein it is erroneous" (R&TC 18622(a)). The same six months applies after filing a federal amended return: the taxpayer "shall also file within six months thereafter an amended return with the Franchise Tax Board" (R&TC 18622(b)). For individuals, both duties apply only if the change would "increase the amount of tax payable" (R&TC 18622(a), (b)); FTB: "Your entity must report all changes or corrections to gross income or deductions, even if the changes or corrections do not result in an increase in tax payable to California for any year" for corporations ([FTB Pub. 1008](https://www.ftb.ca.gov/forms/misc/1008.html)). The clock starts on "the date on which each adjustment or resolution resulting from an Internal Revenue Service examination is assessed pursuant to Section 6203 of the Internal Revenue Code" (R&TC 18622(d)); Pub. 1008 calls it "the date the IRS examination adjustment is assessed on the account transcript".

What reporting does to the time FTB has to assess:

| What happened | FTB's assessment window | Basis |
| --- | --- | --- |
| Reported within six months (by the taxpayer or the IRS) | 2 years from the report, or the normal period if later | R&TC 19059(a) |
| Reported after six months | 4 years from the report | R&TC 19060(b) |
| Never reported | "at any time" | R&TC 19060(a) |

A federal decrease that produces a California refund must be claimed. R&TC 19311 as amended by SB 1435 (for taxable years beginning on or after 1 January 2025) reads: "within two years from the date of the final federal determination ... or within the period provided in Section 19306, 19307, 19308, or 19316, whichever period expires later" (R&TC 19311(a)(1)). FTB says a taxpayer due a California refund "must claim the refund within 2 years of the final federal determination" ([FTB federal changes page](https://www.ftb.ca.gov/file/after-you-file/amend-a-return/irs-changed-your-federal-tax-return.html)).

**Tax year.** This skill applies the rules in force in 2026 to federal determinations of any open year. In the official archive, R&TC 18622, 19059 and 19060 were last amended in 1999 (applying to federal determinations final on or after 1 January 2000), and R&TC 18622.5 and 19311 were amended by SB 1435, effective 14 September 2026 and applicable to taxable years beginning on or after 1 January 2025. In 19311 as it now reads, subdivision (c) substitutes "partnership" for "taxpayer" for tax imposed on a partnership under 18622.5(c)(1); this skill does not identify what else SB 1435 changed in either section (no version comparison was read). Pub. 1008 is a 2020 revision.

**Circular 230 disclosure.** This material is general information, not written advice on a specific transaction under 31 CFR 10.37. It is not intended to be used, and cannot be used, to avoid penalties.

## Scope and who this is for

In scope: individuals (Form 540, 540NR) and corporations (Form 100, 100X), and exempt organizations at the level of where to report, after an IRS examination, a math-error or credit adjustment, a federal amended return, or a renegotiated federal contract; and their preparers.

Out of scope, and where it goes:

| Topic | Where |
| --- | --- |
| Partnership-level (BBA) audits, the partnership's own report, elections and tax under R&TC 18622.5 | not covered here; FTB, Pub. 1008 partnership section |
| The federal examination, appeal or Tax Court case itself | not covered here; refer |
| Computing the amended California return | ca-540-individual-return for individuals; not covered here for corporations |
| Late filing and late payment penalties on the resulting assessment | not covered here; R&TC 19131(f) presumes no California late filing penalty in some federal reasonable cause cases |
| Exempt organization reporting detail (revocation of exempt status) | Pub. 1008 |

## Ask the client first

- Which years did the IRS change, and what is the date each adjustment was assessed on the IRS account transcript (not the date of the audit report or the letter)?
- Did the changes increase or decrease federal taxable income, credits or tax for each year? Do they carry into California (state and federal differences)?
- Is the taxpayer an individual, a corporation, an exempt organization, or a partnership or LLC (partnership-level audit)?
- Was a federal amended return filed, and on what date?
- Has anything been sent to FTB yet, by the taxpayer or by the IRS?
- Is any year still under federal review or in litigation (for a protective claim)?
- For refund years, when was the original California return filed and when was the tax paid?

## The method, step by step

### Rates, bands and thresholds

| Item | Figure | Conditions | Source |
| --- | --- | --- | --- |
| Reporting deadline after a final federal determination | 6 months | from the IRC 6203 assessment date; individuals only if California tax increases | [R&TC 18622(a), (d) (archive)](https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip); [FTB Pub. 1008](https://www.ftb.ca.gov/forms/misc/1008.html) |
| Amended California return after a federal amended return | 6 months | from filing the federal amended return; individuals only if California tax increases | [R&TC 18622(b) (archive)](https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip) |
| FTB assessment window after a timely report | 2 years from the report | or the periods in R&TC 19057, 19058 or 19065 if later | [R&TC 19059 (archive)](https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip); [FTB Pub. 1008](https://www.ftb.ca.gov/forms/misc/1008.html) |
| FTB assessment window after a late report | 4 years from the report | from receipt of "sufficiently-detailed" information (Pub. 1008) | [R&TC 19060(b) (archive)](https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip); [FTB Pub. 1008](https://www.ftb.ca.gov/forms/misc/1008.html) |
| FTB assessment window if never reported | no limit | "at any time" | [R&TC 19060(a) (archive)](https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip) |
| Refund claim after a federal change | 2 years from the final federal determination | or the normal refund periods if later | [R&TC 19311(a) (archive)](https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip); [FTB federal changes page](https://www.ftb.ca.gov/file/after-you-file/amend-a-return/irs-changed-your-federal-tax-return.html) |

### Steps

1. **Find the final federal determination date.** It is the date each adjustment "is assessed pursuant to Section 6203 of the Internal Revenue Code" (R&TC 18622(d)); Pub. 1008: "the date the IRS examination adjustment is assessed on the account transcript". Get the IRS account transcript for each year. Each year, and each assessment, can have its own date ("each final federal determination").
2. **Decide whether a report is required.**
   - **Individuals:** report only if the change would increase California tax for any year (R&TC 18622(a)). FTB: "You do not have to amend your return if the federal changes do not affect your California tax liability" (FTB federal changes page).
   - **Corporations:** report every change to gross income or deductions, whether or not California tax goes up (Pub. 1008).
   - **What to include:** Pub. 1008 asks for "any IRS assessed penalties, adjustments or corrections resulting from math errors, tax credit adjustments, other tax adjustments, or supplemental income from an IRS audit", and "other tax adjustments even if the IRS did not examine these adjustments".
   - **Federal amended returns:** the same rule, six months after filing the federal amended return (R&TC 18622(b)).
3. **Concede or contest.** The report must "concede the accuracy of the determination or state wherein it is erroneous" (R&TC 18622(a)), and be "sufficiently detailed to allow computation of the resulting California tax change" (R&TC 18622(c)).
4. **Report in writing.** Pub. 1008 lists what to do: "Tell us that a final federal determination or IRS change has been made", "Identify the adjusted tax year", "Fully explain all adjustments" and "Provide federal documentation showing the adjustments made to taxable income", with the complete audit report, original and revised schedules, state and federal returns for years older than three years, a phone number, and FTB 3520 PIT for a representative.
   - **Individuals:** for tax year 2016 and earlier, FTB 540X; FTB's page says "For tax year 2017 file an amended return and" Schedule X, and the Schedule X instructions say an individual "filing an amended personal income tax return" uses it "to provide reason(s) for amending" (year-specific forms from 2023); or a notification letter, or a fax to 916-843-2269 (FTB federal changes page; Pub. 1008).
   - **Corporations:** Form 100X, a letter to Corporation RAR MS F310, or fax (Pub. 1008).
   - **Exempt organizations:** Form 109 (Form 100X for homeowners' associations and political organizations) or a letter (Pub. 1008).
5. **Interest.** Pub. 1008: when FTB is not told in time, "Interest accrues from the original tax year due date until you fully pay the tax liabilities and penalties".
6. **Work out FTB's window.** Timely report: FTB may assess "within two years from the date when the notice is filed with the Franchise Tax Board by the taxpayer or the Internal Revenue Service, or within the periods provided in Section 19057, 19058, or 19065, whichever period expires later" (R&TC 19059(a)). After a timely California amended return following a federal amended return, FTB may assess more than "the self-assessed tax on the amended return" within two years of that filing, or the normal period if later (R&TC 19059(b)). Late report: "within four years from the date the taxpayer or the Internal Revenue Service notifies the Franchise Tax Board" (R&TC 19060(b)). No report: "at any time" (R&TC 19060(a)). An IRS report to FTB within six months counts as timely (R&TC 19059(a)).
7. **Claim refunds separately.** A federal decrease does not refund California tax by itself; "you must file a claim for refund if you want to have the overpayment refunded", within the normal statute, one year from the overpayment, or "Two years after the final federal determination (whichever is later)" (Pub. 1008; R&TC 19311(a)). For a year still in federal review or litigation, write "PROTECTIVE CLAIM" at the top of Schedule X or Form 100X (Pub. 1008).
8. **Check multi-year cases.** Pub. 1008: where one year is an assessment and another an overpayment, FTB can still assess the first under the open-ended rule, "However, if you do not file a claim for refund within two years of the final federal determination, there is no open statute to allow the overpayment" and "The overpayment cannot offset against any amounts due and no refund can be issued."

**AUDIT FLASH POINT** (the open statute). An unreported federal change leaves the year open to FTB assessment with no time limit (R&TC 19060(a)), and the interest runs from the original due date. An IRS report to FTB starts the two-year window only if it arrives within the six months (R&TC 19059(a)). The opposite trap is a federal decrease: the refund is lost if no claim is filed within two years of the final federal determination or the normal period, even where another year of the same audit produces an assessment (Pub. 1008).

## Boundary and exception table

| Situation | Result | Basis |
| --- | --- | --- |
| Individual; IRS increases federal income but California tax does not change (for example an item California does not tax) | No report required | R&TC 18622(a); FTB federal changes page |
| Corporation; IRS decreases income | Report anyway; claim any refund | Pub. 1008; R&TC 19311 |
| Final federal determination assessed 9 March 2026, reported 15 June 2026 | Timely; FTB has until 15 June 2028 or the normal period, whichever is later | R&TC 18622; 19059(a) |
| Same, reported 1 December 2026 | Late; FTB has until 1 December 2030 | R&TC 19060(b) |
| Never reported | FTB may assess at any time | R&TC 19060(a) |
| IRS sends the change to FTB within six months, taxpayer does nothing | Two-year window runs from the IRS report | R&TC 19059(a) |
| Federal amended return increasing tax, filed 4 May 2026 | California amended return due by 4 November 2026 | R&TC 18622(b) |
| Year still under federal appeal | File a protective claim to keep the refund period open | Pub. 1008 |
| Partnership audited at the partnership level | R&TC 18622.5 and the partnership rules apply, not this skill | R&TC 18622.5(a); Pub. 1008 |

## Worked cases

Both cases are made up for illustration.

**Case 1: an individual reports on time, and what late or no reporting would have meant.**

- **Facts:** the IRS examined an individual's 2022 federal return and increased income. The IRS account transcript shows the adjustment assessed on Monday 9 March 2026, so the six-month reporting deadline is 9 September 2026. The amended 2022 Form 540 with Schedule X shows California taxable income up USD 20,000 and California tax up USD 1,860 (the figure on the amended return). It is filed with the IRS report and payment on Monday 15 June 2026.
- **Report:** timely. FTB may issue a further assessment on the change until 15 June 2028 (two years from the report), or longer if a normal period runs later (R&TC 19059(a)).
- **If reported on 1 December 2026 instead:** late, so FTB's window would run to 1 December 2030 (R&TC 19060(b)). If never reported: no limit.
- **Interest:** Pub. 1008 says that without timely notice "Interest accrues from the original tax year due date until you fully pay the tax liabilities and penalties". Interest is not computed here.

```oa-check
name: Federal change report, 2022 individual, windows by reporting date
inputs:
  ca_tax_increase_on_return: 1860
  months_allowed: 6
  report_month_offset: 3
  late_report_month_offset: 9
  timely_window_years: 2
  late_window_years: 4
steps:
  - ca_tax_increase: ca_tax_increase_on_return
  - reported_on_time: 1 - min(1, ceil(max(0, report_month_offset - months_allowed)))
  - late_report_on_time: 1 - min(1, ceil(max(0, late_report_month_offset - months_allowed)))
  - window_years_if_timely: timely_window_years * reported_on_time + late_window_years * (1 - reported_on_time)
  - window_years_if_late: timely_window_years * late_report_on_time + late_window_years * (1 - late_report_on_time)
expected:
  ca_tax_increase: 1860.00
  reported_on_time: 1
  late_report_on_time: 0
  window_years_if_timely: 2
  window_years_if_late: 4
```

**Case 2: a two-year audit with an increase in one year and a decrease in the other.**

- **Facts:** an IRS examination covers 2021 and 2022 for an individual. Both adjustments are assessed on Tuesday 17 February 2026. For California, 2021 tax goes up USD 2,400 and 2022 tax goes down USD 900. The 2022 California return's original due date was in April 2023 and it was filed by then; no 2022 tax was paid after April 2023. So the normal refund period for 2022, "4 years after the original return due date" ([FTB Claim for refund](https://www.ftb.ca.gov/help/disagree-or-resolve-an-issue/claim-for-refund.html)), ended in April 2027, and the one-year-from-overpayment period ended in 2024. The two-year window after the final federal determination ends 17 February 2028 (Pub. 1008 and FTB's federal changes page, both written before SB 1435; R&TC 19311 as now amended applies by its Sec. 46 to taxable years beginning on or after 1 January 2025).
- **Timely route:** report 2021 by Monday 17 August 2026 and file a 2022 claim (amended 540 with Schedule X) by 17 February 2028. Net cost: 2,400 - 900 = **USD 1,500** (before interest).
- **Missed claim:** the taxpayer reports 2021 but files the 2022 claim on 1 March 2028, after all three refund periods. FTB still collects USD 2,400 for 2021, and "The overpayment cannot offset against any amounts due and no refund can be issued" (Pub. 1008). Net cost: **USD 2,400**, USD 900 more.

```oa-check
name: Multi-year federal audit, refund claim filed in time or too late
inputs:
  year1_increase: 2400
  year2_decrease: 900
  claim_within_window: 0
steps:
  - net_if_claimed: year1_increase - year2_decrease
  - net_actual: year1_increase - year2_decrease * claim_within_window
  - lost_by_missing_claim: net_actual - net_if_claimed
expected:
  net_if_claimed: 1500
  net_actual: 2400
  lost_by_missing_claim: 900
```

## When to refuse or refer

- **Partnership-level audits (BBA).** R&TC 18622.5 has its own reporting, elections and partnership-level tax: refer.
- **Contesting the federal change.** The California report may "state wherein it is erroneous", but disputes about the federal determination itself go to a federal adviser.
- **Protests and appeals of FTB's resulting assessment.** Refer.
- **Residency, apportionment or California-only adjustments arising alongside the federal change.** Refer to the relevant skills.

## Filing and payment

- **Individuals:** amended Form 540 (or 540NR) with Schedule X and the federal report, mailed to Franchise Tax Board, PO Box 942867, Sacramento CA 94267-0001; or a notification letter with all federal information to RAR/VOL MS F310, Franchise Tax Board, PO Box 1998, Rancho Cordova CA 95741-1998; or fax 916-843-2269. Phone 916-845-4028 for help (FTB federal changes page).
- **Corporations:** Form 100X, or a letter to Corporation RAR MS F310, Franchise Tax Board, PO Box 942857, Sacramento CA 94257-0501, or fax 916-843-2269 (Pub. 1008).
- **Exempt organizations:** Form 109 (Form 100X for homeowners' associations and political organizations), or a letter to Exempt RAR MS F120, Franchise Tax Board, PO Box 1286, Rancho Cordova CA 95741-1286 (Pub. 1008).
- **Representatives:** FTB 3520 PIT on file (Pub. 1008).

## Completion checklist

- [ ] IRS account transcript obtained; IRC 6203 assessment date found for each year and each assessment.
- [ ] For each year: does the change increase California tax (individuals), or is the taxpayer a corporation (report all)?
- [ ] Report filed within six months with the complete federal report, conceding or stating the error.
- [ ] Additional California tax paid.
- [ ] Refund claims (including protective claims) filed for decrease years within two years of the final federal determination or the normal period.
- [ ] Federal amended returns followed by a California amended return within six months where tax increases.

## Sources

Read dates are California (Pacific time) local dates: all sources for this skill were opened on 23 November 2026, Pacific time.

| Source | URL | Read on |
| --- | --- | --- |
| R&TC 18622, 19059, 19060 and 19311 and their section histories, LAW_SECTION_TBL.dat in the official California Legislature bulk data archive. Read in full, for the reporting duty, the final federal determination date, the assessment windows and the refund window. | https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip | 2026-11-23 |
| R&TC 18622.5 in the same archive. Read for its scope (partnership-level audits) and definitions; its elections and tax computation were not analyzed. | https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip | 2026-11-23 |
| SB 1435 (Stats. 2026, Ch. 236), BILL_VERSION_TBL.dat in the same archive. Read for the sections amended (including 18622.5 and 19311), the digest and Sec. 46 (application to taxable years beginning on or after 1 January 2025). | https://downloads.leginfo.legislature.ca.gov/pubinfo_2025.zip | 2026-11-23 |
| FTB Publication 1008, Federal Tax Adjustments and Your Notification Responsibilities to California (revised 05/2020). Read in full (every paragraph printed unabridged), for who must report, the six-month rule, the two-year and four-year windows, refunds, protective claims, the multi-year warning, the method of notification and the addresses. | https://www.ftb.ca.gov/forms/misc/1008.html | 2026-11-23 |
| FTB, Schedule X instructions (2024). Read for its purpose on amended individual returns, year-specific forms from 2023 and the protective claim box. | https://www.ftb.ca.gov/forms/2024/2024-540-x-instructions.html | 2026-11-23 |
| FTB, Claim for refund. Read for the normal refund statute of limitations. | https://www.ftb.ca.gov/help/disagree-or-resolve-an-issue/claim-for-refund.html | 2026-11-23 |
| FTB federal changes page, titled for changes the federal agency made to a return (last updated 09/24/2025). Read in full, for the six-month and two-year rules, the forms and the addresses. | https://www.ftb.ca.gov/file/after-you-file/amend-a-return/irs-changed-your-federal-tax-return.html | 2026-11-23 |

Not yet confirmed: what SB 1435 changed in R&TC 18622.5 and 19311 beyond their current text, and the text of 19311 that governs taxable years before 2025 (no prior version compared; for those years this skill relies on Pub. 1008 and FTB's federal changes page); the normal assessment and refund periods in R&TC 19057, 19058, 19065, 19306, 19307, 19308 and 19316 (named in 19059 and 19311 but not read); whether a reporting deadline that falls on a weekend or holiday moves (no rule read); whether a federal math-error or credit adjustment that is not an "examination" assessment starts the six-month clock under 18622(d), which refers to an "Internal Revenue Service examination" (Pub. 1008 asks for math-error and credit adjustments to be reported); any penalty for failing to report (none read beyond the open statute and interest); and whether Pub. 1008 (2020) reflects current FTB procedure.

**Disclaimer.** This skill and its outputs are provided for informational and computational purposes only and do not constitute tax, legal, or financial advice. Open Accountants and its contributors accept no liability for any errors, omissions, or outcomes arising from the use of this skill. All outputs must be reviewed and signed off by a qualified professional (such as a CPA, EA, tax attorney, or equivalent licensed practitioner in your jurisdiction) before filing or acting upon. The most up-to-date version of this skill is maintained at [openaccountants.com](https://www.openaccountants.com).
