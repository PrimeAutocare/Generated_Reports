# PrimeAutocare — AI Review

- **Period:** July 2026 H1
- **Model:** gemini-flash-latest
- **Generated (UTC):** 2026-07-24 08:08:42
- **Source reports:** Payroll, Utilization, Receivables, Revenue, WIP, Attendance

---

## Executive Summary

PrimeAutocare generated gross revenue of 834,356.16 across 59 completed jobs during the first half of July 2026, but operations suffer from severe labor inefficiency and sluggish cash conversion. Employees logged 1,710.90 shift attendance hours, yet only 196.90 hours were recorded as direct billable labor on jobs, resulting in an effective billable utilization rate of just 11.51%. Cash flow is constrained by 448,800.81 in outstanding receivables (a collection rate of 68.1%), alongside 207,540.76 in completed revenue tied to unassigned/blank customer profiles. Furthermore, 23 jobs remain stuck in Work in Progress (WIP)—including 10 unassigned pending jobs and two stalled jobs open for 20 days—highlighting major floor scheduling and tracking bottlenecks.

## Financial Review

As a financial analyst reviewing Revenue and Receivables, PrimeAutocare demonstrates strong revenue generation undercut by significant collection lags and profile attribution risks:

* **Revenue & Profitability:** Total revenue from completed jobs reached 834,356.16 across 59 jobs (average revenue of 14,141.63 per job), against direct job payroll expenses of 378,473.87 (representing direct labor cost at 45.36% of gross revenue). The top-performing service by total yield was Annual Service Inspection (JO0025) at 81,133.33 across 5 completed jobs, while Wheel Alignment (JO0003) delivered 79,148.98 across 6 jobs.
* **Receivables & Collection Risk:** Out of 1,406,146.13 billed across 102 invoices in the invoice register snapshot, only 957,345.32 has been collected, leaving 448,800.81 outstanding across 47 active invoices (a 68.1% collection rate). Although all outstanding receivables fall within the 0–30 day aging bucket, individual account concentration presents clear default risks:
  * Susan Peterson (CU0005) holds 58,030.47 in total unpaid balances across four invoices (IN0002 for 22,365.70 [20 days old], IN0019 for 9,475.33 [16 days old], IN0065 for 23,598.22 [7 days old], and IN0066 for 2,491.22 [7 days old]).
  * Dorothy Jones (CU0016) has 26,093.57 outstanding across IN0012 (3,197.97 [18 days old]) and IN0029 (22,895.60 [14 days old]).
* **Customer Attribution & Data Integrity:** A critical financial risk is the presence of 207,540.76 in revenue (24.87% of total period revenue across 13 completed jobs) recorded under blank/unidentified customer accounts in the Revenue report. Similarly, 18 invoices in the Receivables register lack customer IDs (e.g., IN0018 billed at 23,496.30 and IN0056 billed at 24,985.59), which threatens customer account reconciliation, auditing, and targeted debt recovery.
* **Payment Methods:** Settlement is distributed across Bank Transfer (301,964.50 across 26 payments), Cash (243,711.78 across 23 payments), Cheque (241,626.94 across 19 payments), and Card (170,042.10 across 14 payments).

## HR & Workforce Review

From an HR perspective evaluating Payroll, Attendance, and Utilization, the workshop faces a severe disconnect between presence hours and billable output, alongside an uneven labor distribution:

* **Labor Presence vs. Direct Production:** Across 214 total employee shifts, staff recorded 1,710.90 attendance hours with zero missing clock-outs, demonstrating high attendance compliance. However, total billable job labor logged across the workshop was only 196.90 hours. This reveals 1,514.00 non-billable presence hours (88.49% of paid employee attendance), creating a massive efficiency drag where total payroll expense (378,473.87) translates to an effective total labor cost of 1,922.16 per direct billable hour worked.
* **100% Idle Technicians:** Three full-time technicians logged zero job hours in the Utilization report despite logging full attendance shifts during the 14-day period:
  * Angela Long (EM0008): 8 shifts, 66.96 attendance hours, 0 billable hours.
  * Jessica Mitchell (EM0001): 8 shifts, 60.20 attendance hours, 0 billable hours.
  * Cynthia Richardson (EM0005): 7 shifts, 56.95 attendance hours, 0 billable hours.
  Together, these three technicians were paid for 184.11 attendance hours without contributing to logged job throughput. (Note: Admin user EM0030 recorded no attendance shifts).
* **Workload Concentration & Pay Skew:** Job hours are concentrated among a small subset of technicians. Melissa Green (EM0015) recorded the highest direct billable output with 22.27 hours across 7 completed jobs (earning 37,845.64 at 1,699.40/hr, representing 11.31% of total workshop direct hours), followed by Laura Ross (EM0021, 14.12 hours across 5 jobs) and Nancy Lee (EM0009, 13.72 hours across 3 jobs). Conversely, 12 of the 23 paid technicians logged fewer than 7 billable hours total across the entire fortnight.

## Operations Review

As an operations manager examining Workshop Work in Progress (WIP), floor management is hampered by unassigned jobs, long cycle times, and real-time labor tracking gaps:

* **Floor Work in Progress:** The workshop currently holds 23 open jobs in WIP (13 In-progress, 10 Pending). In-progress jobs average 10.2 days open, while Pending jobs average 3.8 days open.
* **Stalled Jobs & Cycle Time Outliers:** Two pending jobs meet the criteria for stalled status (>7 days pending without work):
  * JB0002 (Cabin Filter Replacement on Kia Rio KB-5351 for Kenneth Harris): Pending for 20 days (created 2026-07-03).
  * JB0075 (Timing Belt Replacement on VW Tiguan WP-3938 for Dorothy Jones): Pending for 8 days (created 2026-07-15).
  In addition, two active jobs have been stuck In-progress for 20 days: JB0001 (Wheel Alignment on Mercedes A180 BAC-5616, assigned to Michael Cook) and JB0009 (Coolant Flush on Honda CR-V WP-1058, assigned to Anthony Ward).
* **Scheduling & Assignment Bottleneck:** All 10 Pending jobs in the WIP report (JB0002, JB0075, JB0096, JB0111, JB0119, JB0126, JB0128, JB0129, JB0130, JB0132) currently have **no assigned technician**. This unassigned queue accounts for 43.48% of total open WIP.
* **Service Offerings vs. Execution:** Four listed services recorded zero completed jobs during the fortnight in the Revenue report: AC Compressor Repair (JO0019), Brake Disc Skimming (JO0005), Transmission Fluid Service (JO0012), and Air Filter Replacement (JO0007). However, Transmission Fluid Service is actively sitting in WIP (JB0079, open 7 days), indicating floor delays in specialty job progression.
* **WIP Data Tracking Deficit:** All 23 open jobs in the WIP table report 0.00 logged hours and 0.00 accrued cost. Labor hours are only being captured upon final job completion (status = 'C'), eliminating real-time visibility into active job labor accumulation and stage completion.

## Recommendations

1. **(Operations)** Immediately assign technicians to the 10 pending WIP jobs (particularly stalled job JB0002 open 20 days and JB0075 open 8 days) and establish daily floor supervision to clear the 13 in-progress jobs averaging 10.2 days open.
2. **(Financial)** Institute strict credit controls and direct collections outreach targeting overdue customer accounts, prioritizing Susan Peterson (CU0005, 58,030.47 total unpaid across IN0002, IN0019, IN0065, IN0066) and Dorothy Jones (CU0016, 26,093.57 total unpaid across IN0012, IN0029).
3. **(HR)** Investigate and reallocate duty schedules for the three 100% idle technicians—Angela Long (EM0008), Jessica Mitchell (EM0001), and Cynthia Richardson (EM0005)—who accumulated 184.11 shift attendance hours with zero billable output.
4. **(Financial)** Enforce mandatory customer profile linking in the POS/ERP software at vehicle drop-off to eliminate anonymous revenue (currently 207,540.76 across 13 jobs) and incomplete invoice records (e.g., IN0009, IN0018).
5. **(HR)** Audit workshop shift activities to identify non-billable task time and address the 1,514.00-hour gap between clocked attendance (1,710.90 hrs) and direct job labor (196.90 hrs).
6. **(Operations)** Implement mandatory real-time floor clocking for active WIP jobs so hours and costs update dynamically prior to job closure.