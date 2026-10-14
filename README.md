# MRML Sorting — Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **MRML — Rice Sorting**, covering **Boiled Unit 1–2** and **Aromatic Unit 1**, shifts A–C.

## Features
- **Toggle:** Last completed day and Month-to-date
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs targets **A90 / P86 / Q97 / OEE75**
- Where time is going; OEE by unit; Find-the-bottleneck
- Top downtime + downtime by category (min) — unplanned only (Sorting section)
- **Opportunity Loss = NPT min ÷ cycle time (min/MT)** → lost output (MT)
- Production & OEE trend (last 16 days)
- Shift Action Board — downtime reasons with responsible-team tagging
- Shift OEE and Gemba walk

## Data source
`Sorting Production Report` (gid=1366867245) and `Breakdown` (gid=482789258) tabs of the MRML OEE sheet. Breakdown is filtered to the **Sorting** section.

## Notes
- OEE = Availability × Performance × Quality.
- Availability = Actual Run Time ÷ Planned Production Time (planned downtime excluded).
- Live: pulls the sheet on page open.
