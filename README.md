# BC/DR Case Study: Northbridge Skills Institute

A business continuity and disaster recovery (BC/DR) plan for a fictional training institute after a flood and power failure close its main site for 72 hours. Written as a BC/DR Coordinator report for the course *GRC205 Incident Management and Business Continuity* (International Cybersecurity and Digital Forensics Academy).

> **Note:** The scenario and all data are fictional and the work is educational. Parts of the report were drafted with AI assistance (Claude), which is acknowledged in Appendix B of the report. I reviewed the content and checked the calculations.

## Scenario

At 08:00 on a Monday, flooding and a power failure make the main site and its local systems unavailable. Five business functions are affected (teaching and assessment, fees, admissions, payroll, records). A 120-candidate exam is due at 11:00. The institute has two technicians, a 25-workstation alternate facility and an annual recovery budget limit of NGN 3,000,000.

## What the report covers

| Task | Content |
|---|---|
| 1. Business Impact Analysis | Five-function BIA, 8-hour and 24-hour cost calculations, priorities, dependency risks |
| 2. Recovery objectives and backups | RTO, RPO and MTD targets, checkpoint-age analysis, backup design (3-2-1 plus an immutable copy), verification |
| 3. Strategy and budget | Cold, Warm and Hot site comparison, itemised budget, recommendation, residual risks |
| 4. BC/DR plan | Activation, roles, RACI, temporary procedures, DR runbook, communication plan, safe return |
| 5. Schedule and exercise | Two-technician recovery schedule, 45-minute tabletop with four injects, corrective actions |
| 6. Governance and KPIs | Testing calendar, NIST SP 800-34 and ISO 22301 mapping, KPI dashboard, maturity target |

## Key results (modelled baseline, not a live test)

- Estimated disruption cost: NGN 1,200,000 over 8 hours and NGN 3,360,000 over 24 hours.
- Recommended strategy: **Warm** site at NGN 2,100,000 per year (NGN 900,000 headroom).
- Earliest assessment restoration: 11:45. All five functions restored by 12:15. Every RTO is met in the baseline.
- The 11:00 exam cannot be saved by restoration alone, so a continuity workaround is planned (secure Microsoft 365 assessment, with a second sitting for candidates who need a workstation).
- Main weaknesses found: AUTH01 and FS01 checkpoints older than their RPOs, a shared backup administrator identity, and unverified provider access controls.
- Current maturity assessed at Level 2, with a realistic 12-month target of Level 3.

## Skills demonstrated

Business impact analysis, recovery objective setting, backup and recovery architecture, cost-benefit reasoning, incident response and BC/DR integration, RACI design, runbook writing, tabletop exercise design, KPI definition, and alignment to NIST SP 800-34 Rev. 1 and ISO 22301:2019.

## References

- NIST SP 800-34 Rev. 1, *Contingency Planning Guide for Federal Information Systems*
- ISO 22301:2019, *Security and resilience: Business continuity management systems: Requirements*, and Amendment 1:2024 (climate action changes)

## Author

OUABO KAMDEM DERRICK ARNAUD | https://www.linkedin.com/in/ouabo-derrick-409531a3/
