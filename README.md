# Generated Reports

Published output from
[autocare-data-pipeline](https://github.com/PrimeAutocare/autocare-data-pipeline).

**Nothing here is written by hand.** Every file is produced by the `Reports`
workflow in that repository and committed by its GitHub App. To change what a
report contains, change the script there — edits made here are overwritten by
the next run.

Reports live in their own repository so the pipeline's history stays code-only,
and so this repository can be reset without touching a commit of it.

## Layout

```
Payroll Report/
  Payroll_Report_July_2026_H2.xlsx     <- current
  archive/
    Payroll_Report_July_2026_H1.xlsx   <- everything it replaced
Utilization Report/
Receivables Report/
Revenue Report/
WIP Report/
```

Each folder holds one current workbook, with every period it replaced in
`archive/`.

## The reporting period

`<Report>_<Month>_<Year>_<H1|H2>.xlsx` is named for the fortnight it **covers**,
not the day it ran. A run on 1 August produces `July_2026_H2` (15–31 July); a run
on 15 August produces `August_2026_H1` (1–14 August). `H1` is the 1st–14th, `H2`
the 15th to the end of the month.

**Payroll, Utilization and Revenue are filtered to that fortnight.** Work counts
against the period it was completed in.

**Receivables and WIP are snapshots** taken when the run happened, and are *not*
period-filtered — a debt is owed as of now regardless of when it was billed, and
a car is on the ramp as of now or it isn't. The period only names the file.

Each workbook's **About** sheet states which it is, the window it covers, and the
formulas behind its numbers, so a file found later can be traced back to its run.

## This repository must stay private

These workbooks contain customer names, phone numbers and licence plates,
employee pay rates, and revenue. They are committed on a schedule, so the
exposure would be continuous rather than one-off.
