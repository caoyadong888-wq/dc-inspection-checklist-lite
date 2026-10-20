# DC-A walk, short slice — 2026-03-18

Site code DC-A, hall H1, inspector Chen Yu, 08:10–08:55. This slice is power, cooling, and the cage door. Eight rows. The other five areas are in the full pack.

Locations are hall codes such as DC-A / Rack-01. Not a street address. Sample mailbox: facilities@example.com.

## Severity

Critical: before you leave the aisle. Major: this shift. Minor: next business day. Info: record only.

In these eight rows the Critical items are W-06 (CRAC-02 supply 24.8 C) and W-15 (Row-C cage door wedged open).

## Power and UPS indicators

Do not transfer a UPS to bypass on a walk. A battery banner is Major. A branch at or above 80 percent of the 32 A breaker is Major.

| ID | Location | Result | Severity | Reading |
| --- | --- | --- | --- | --- |
| W-01 | DC-A / UPS-A | Pass | Info | Load 41 percent, bypass dark |
| W-02 | DC-A / UPS-B | Fail | Major | String 2 amber, banner BATTERY WEAK |
| W-03 | DC-A / Rack-01 | Pass | Info | Closed, branch 2 at 11.4 A |
| W-04 | DC-A / Rack-12 | Fail | Major | Branch 3 at 26.2 A, 82 percent of 32 A |

## Cooling and CRAC temperatures

House supply band is 18.0–22.0 C. Supply at or above 24.0 C is Critical. Do not change the setpoint on the walk.

| ID | Location | Result | Severity | Reading |
| --- | --- | --- | --- | --- |
| W-05 | DC-A / CRAC-01 | Pass | Info | Supply 18.6 C, return 26.4 C |
| W-06 | DC-A / CRAC-02 | Fail | Critical | Supply 24.8 C, valve at 100 percent |

## Door and security

A wedge on a cage door is Critical, including a floor tile "just for a minute".

| ID | Location | Result | Severity | Reading |
| --- | --- | --- | --- | --- |
| W-14 | DC-A / Door-D1 | Pass | Info | Interlock held, alarm log empty |
| W-15 | DC-A / Row-C | Fail | Critical | Cage door wedged open with a floor tile |

## What this slice leaves out

Humidity, aisle cleanliness, cable strain, the fire panel, and spare parts. On the full day those sections add W-17 (FACP-1 zone 4 DIRTY DETECTOR, Critical) and the cardboard under Rack-14.
