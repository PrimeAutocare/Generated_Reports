# PrimeAutocare — AI Review

- **Period:** July 2026 H1
- **Model:** gemini-flash-latest
- **Generated (UTC):** 2026-07-23 08:16:38
- **Source reports:** Payroll, Utilization, Receivables, Revenue, WIP, Attendance

---

# PrimeAutocare Fortnightly Operational Review
**Period:** July 2026 H1 (2026-07-01 to 2026-07-14)

---

### Executive Summary
PrimeAutocare suffers from severe workshop productivity bottlenecks, weak credit collection controls, and critical customer data gaps. Despite paying for 1,710.90 attendance hours across 29 employees, technicians logged only 196.90 billable job hours, resulting in an effective labor billable utilization rate of just 13.53% among workshop technical staff. This labor drag is exacerbated by open jobs sitting idle for up to 20 days in Work-In-Progress (WIP), even while multiple technicians remain completely unassigned. Concurrently, credit risk is escalating rapidly: outstanding receivables stand at $448,800.81 (a 68.1% collection rate), with $95,266.43 owed by anonymous customer records and over $165,000 concentrated among just four repeat accounts.

---

### Key Operational Findings

#### 1. Labor Utilization & Capacity Realization
* **Extreme Unbilled Attendance Hours:** Total workshop attendance reached 1,710.90 hours across 214 shifts, but only 196.90 hours were logged on billable completed or in-progress work. Excluding administrative personnel (EM0017: 66.77 hrs, EM0027: 59.39 hrs) and supervisory attendance (EM0019: 61.99 hrs, EM0028: 68.13 hrs), the 25 technicians clocked 1,454.62 attendance hours, achieving a billable efficiency of only **13.53%**.
* **Zero-Output Technicians:** Three full-time technicians logged zero billable hours during the fortnight despite clocking full attendance:
  * **EM0008 (Angela Long):** 8 shifts, 66.96 attendance hours, $0 payroll, 0 jobs logged (Idle).
  * **EM0001 (Jessica Mitchell):** 8 shifts, 60.20 attendance hours, $0 payroll, 0 jobs logged (Idle).
  * **EM0005 (Cynthia Richardson):** 7 shifts, 56.95 attendance hours, $0 payroll, 0 jobs logged (Idle).
  * *Combined impact:* 184.11 attendance hours paid in physical presence with zero completed output.
* **Severe Billable Friction Among Clocked Techs:** Several active technicians logged less than 6% of their clocked shift time to jobs:
  * **EM0003 (Richard Foster):** 65.46 attendance hours vs. 3.48 logged hours (5.3% efficiency; $5,720.98 pay).
  * **EM0020 (Anthony Ward):** 59.47 attendance hours vs. 1.79 logged hours (3.0% efficiency; $3,105.24 pay).
  * **EM0012 (Carol Murray):** 63.59 attendance hours vs. 1.84 logged hours (2.9% efficiency; $2,780.20 pay).

#### 2. Work-in-Progress (WIP) & Workshop Bottlenecks
* **Severe Job Stagnation (20-Day Aging):** 23 jobs remain open in WIP, with 13 in-progress jobs averaging 10.2 days open.
  * **JB0001 (Mercedes A180):** In-progress for 20 days (created 2026-07-03) assigned to EM0018 (Michael Cook), who clocked 59.96 attendance hours but completed 0 jobs and logged 0.00 hours on this vehicle.
  * **JB0009 (Honda CR-V):** In-progress for 20 days assigned to EM0020 (Anthony Ward), with 0.00 hours logged.
  * **JB0020 (Mercedes GLA)** & **JB0022 (VW Tiguan):** Both in-progress for 17 days with 0.00 hours logged.
* **Unassigned Stalled Jobs:** Two jobs marked as "Pending" have been stalled for over a week without any technician assigned, despite three technicians sitting completely idle in the workshop:
  * **JB0002 (Kia Rio - Cabin Filter Replacement):** Pending for 20 days (created 2026-07-03), unassigned.
  * **JB0075 (VW Tiguan - Timing Belt Replacement):** Pending for 8 days (created 2026-07-15), unassigned.

#### 3. Customer Master Data Integrity & Anonymous Revenue
* **Massive Unidentified Revenue Concentration:** The single largest customer entry in the Revenue report is **unnamed/blank** (no Customer ID or Name), generating **$207,540.76 across 13 completed jobs** — accounting for **24.87%** of total workshop revenue ($834,356.16).
* **Uncollectible Anonymous Receivables:** 11 open invoices in the Receivables register have no associated Customer ID or Name, representing **$95,266.43** in outstanding balances (e.g., IN0091 for $20,211.81, IN0059 for $16,865.83, IN0086 for $15,544.04, IN0052 for $9,757.85). Without customer records, these debts cannot be legally enforced or collected.
* **Incomplete WIP Intake:** 6 out of 23 open WIP jobs (JB0009, JB0072, JB0091, JB0119, JB0126, JB0131) lack Customer IDs and Names.

#### 4. Receivables & Credit Concentration Risk
* **Low Overall Collection Efficiency:** Total receivables outstanding sit at **$448,800.81** against $1,406,146.13 billed, yielding a low collection rate of **68.1%** across 47 uncollected invoices.
* **Extreme Credit Exposure on Specific Accounts:**
  * **CU0005 (Susan Peterson):** Billed $52,511.01 in H1 revenue, but holds **$57,930.47** in outstanding debt across 4 unpaid invoices (IN0002: $22,365.70 [20d old], IN0019: $9,475.33 [16d old], IN0065: $23,598.22 [7d old], IN0066: $2,491.22 [7d old]).
  * **CU0027 (Paul Cox):** Billed $32,249.02 in H1 revenue, but holds **$46,442.92** in outstanding debt across 4 unpaid/partially paid invoices (IN0047: $7,492.53, IN0067: $15,486.81, IN0074: $11,517.71, IN0078: $11,945.87).
  * **CU0021 (Kenneth Harris):** Owes **$31,470.79** across 4 open invoices (IN0004, IN0025, IN0068, IN0073).
  * **CU0016 (Dorothy Jones):** Owes **$29,953.47** across 3 open invoices (IN0012, IN0029, IN0085).
  * *Combined impact:* These 4 customers alone represent **$165,797.65** (36.9%) of all outstanding workshop receivables.

#### 5. Payroll Overhead & Supervisory Output
* **High Average Effective Hourly Cost:** Total completed job payroll was $378,473.87 across 196.90 completed job hours, translating to an average labor payout of **$1,922.16 per logged billable hour**.
* **Supervisory Cost vs. Floor Management:** Supervisors **EM0019 (Michelle Murphy)** at $2,977.20/hr ($27,687.96 pay) and **EM0028 (Ronald Carter)** at $3,162.79/hr ($25,808.37 pay) drew a combined **$53,496.33 in payroll** for 17.46 logged hours, yet failed to prevent 20-day WIP stalls or assign idle floor technicians.

---

### Prioritized Recommendations

1. **Immediate Reallocation of Idle Technicians to Stalled WIP (Operations)**
   * **Action:** Direct supervisors EM0019 and EM0028 to immediately assign idle technicians (EM0008 Angela Long, EM0001 Jessica Mitchell, EM0005 Cynthia Richardson) to open pending jobs (JB0002, JB0075) and takeover stagnant 20-day in-progress jobs (JB0001, JB0009).
   * **Target:** Clear all 9 WIP jobs aged >8 days within 48 hours.

2. **Enforce Mandatory Customer Data Capture at Job Intake (IT & Administration)**
   * **Action:** Audit and update the Point-of-Sale / Postgres database schema to make `Customer ID`, `Name`, and `Phone Number` mandatory fields before any Job (JB) or Invoice (IN) can be saved or set to 'In-progress'.
   * **Target:** Resolve and link missing customer profiles for the 13 unassigned revenue jobs ($207,540.76) and 6 open WIP jobs using vehicle registration matching.

3. **Institute Credit Hold on Overdue Accounts (Finance & Credit Control)**
   * **Action:** Implement an automatic credit stop on work orders for accounts with outstanding balances older than 10 days. Specifically freeze further vehicle releases/services for **CU0005 (Susan Peterson - $57,930.47 outstanding)** and **CU0027 (Paul Cox - $46,442.92 outstanding)** until aging invoices (IN0002, IN0019, IN0047) are settled.

4. **Recover $95.2k in Anonymous Receivables (Finance)**
   * **Action:** Cross-reference vehicle registration numbers on unassigned invoices (BAC-3608, KA-1128, CAR-9900, CAB-1960, QA-3532, PC-1685) against historical completed jobs and vehicle registration logs to attach responsible party names and send immediate debt collection notices for the $95,266.43 outstanding.

5. **Implement Shift-to-Job Time Tracking & Supervisory KPIs (Management)**
   * **Action:** Transition from job-only hour logging to clock-in/clock-out job tracking. Require floor supervisors (EM0019, EM0028) to review daily unbilled labor hours per technician.
   * **Target:** Raise technician billable utilization from 13.53% to a benchmark minimum of 65% by H2 July.