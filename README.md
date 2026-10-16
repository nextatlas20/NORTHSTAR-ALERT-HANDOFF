# Northstar operations handbook

This handbook carries a short release panel for the on-call lead.

<!-- INCIDENT-PANEL:BEGIN -->
## Alert handoff — 18 March 2101
Rows: 9 physical | 5 valid | 4 invalid
Active alerts: 3 open | 1 acknowledged
Components: 1 escalate | 3 watch | 0 clear

| Component | Service | Criticality | Open | Acknowledged | Resolved | Active | Status |
| --- | --- | --- | ---: | ---: | ---: | ---: | ---: |
| DB-02 | Ledger Store | CRITICAL | 0 | 1 | 0 | 1 | ESCALATE |
| AP-01 | Edge API | HIGH | 1 | 0 | 1 | 1 | WATCH |
| MQ-03 | Event Bus | MEDIUM | 1 | 0 | 0 | 1 | WATCH |
| UI-04 | Member Portal | LOW | 1 | 0 | 0 | 1 | WATCH |
<!-- INCIDENT-PANEL:END -->

The service catalog is authoritative.
