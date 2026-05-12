# Day 12 - Windows Troubleshooting Tools

Day 12 lesson completed in study mode.

## Topics Covered

- Event Viewer
- Reliability Monitor
- Event levels
- Safe Mode
- System Restore
- Windows recovery options
- SFC
- DISM
- Windows troubleshooters
- Blue screen basics
- App crash troubleshooting
- System crash troubleshooting

## Key Notes

Event Viewer is a Windows log tool. It records app errors, Windows errors, driver errors, security events, startup problems, shutdown problems, warnings, and hardware-related errors.

Reliability Monitor is easier to read than Event Viewer. It shows system stability over time and helps identify app failures, Windows failures, driver failures, update failures, and unexpected shutdowns by date.

Safe Mode starts Windows with only basic drivers and services. It helps isolate whether a problem is caused by startup apps, drivers, services, or third-party software.

System Restore can return Windows system settings to an earlier restore point. It should not be used on a company device without approval.

SFC means System File Checker. It checks and repairs Windows system files.

DISM means Deployment Image Servicing and Management. It repairs the Windows image used to repair system files.

Blue screen means Windows crashed seriously. Stop codes, recent updates, drivers, hardware changes, and timing are important clues.

## Common Tickets

- PC keeps crashing
- App keeps closing
- Windows is acting strange
- Laptop became slow after an update
- Computer shows blue screen
- Windows tools will not open
- Computer randomly restarts
- Application failure appears in Reliability Monitor

## Safe Troubleshooting Order

1. Ask when the issue started.
2. Ask what changed recently.
3. Check user impact.
4. Restart app or computer if safe.
5. Check Reliability Monitor.
6. Check Event Viewer if deeper logs are needed.
7. Check Windows Update history.
8. Check Device Manager.
9. Use built-in troubleshooters if relevant.
10. Use SFC or DISM only when appropriate.
11. Escalate if the issue repeats or involves system failure.

## Example Ticket Note

User reported random laptop restarts. Checked Reliability Monitor and found multiple unexpected shutdown events. Reviewed Windows Update history and Device Manager. No obvious driver warning found. Escalated for deeper hardware and system log review.

## Status

Day 12 completed in lesson mode.
