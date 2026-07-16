# Generated Reports

**This is an orphan branch. It shares no history with `main` and contains no code.**

Every file here is written by the `Reports` workflow on `main` and committed by
`github-actions[bot]`. To change what a report contains, change the script on
`main` — edits made here are overwritten by the next run.

## Layout

```
Payroll-Report/
  Payroll_Report_July_2026_H2.xlsx     <- current
  archive/
    Payroll_Report_July_2026_H1.xlsx   <- everything it replaced
Utilization-Report/
Receivables-Report/
Revenue-Report/
WIP-Report/
```

Each folder holds one current workbook, with every period it replaced in
`archive/`.

## The reporting period

`<Report>_<Month>_<Year>_<H1|H2>.xlsx` is named for the fortnight it **covers**,
not the day it ran. A run on 1 August produces `July_2026_H2` (15–31 July); a run
on 15 August produces `August_2026_H1` (1–14 August).

Payroll, Utilization and Revenue are filtered to that window. Receivables and WIP
are snapshots taken at run time and are not period-filtered — a debt is owed as
of now regardless of when it was billed. Each workbook's **About** sheet states
which it is.

## Why a separate branch

Reports are generated output, not source. Keeping them off `main` leaves that
branch's history to code, and lets this branch be deleted and recreated whenever
the accumulated workbooks stop being worth their space — without rewriting a
single commit on `main`.

Note that this branch's objects still live in the same repository: a plain
`git clone` fetches them. Use `git clone --single-branch` to skip them.

## This branch must stay private

These workbooks contain customer names, phone numbers and licence plates,
employee pay rates, and revenue. They are committed on a schedule, so the
exposure would be continuous rather than one-off.
