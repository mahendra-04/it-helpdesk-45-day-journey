# Day 12 - Windows Troubleshooting Tools

**Status:** Lesson Completed

## Learning Objectives

- Learn the purpose of key Windows troubleshooting tools.
- Understand when to use logs, recovery options, and repair commands.
- Build skill reading system evidence before escalating.

## Concepts Learned

- Event Viewer, Reliability Monitor, Safe Mode, System Restore, Recovery, SFC, and DISM.
- Application, System, and Security log awareness.
- Crash timelines, error events, and reliability history.
- Repair commands and when escalation is appropriate.

## Real-World Help Desk Examples

- A workstation crashes after a driver update.
- An application fails repeatedly and logs errors.
- Windows files are suspected to be corrupted after repeated failures.

## Troubleshooting Workflows

1. Confirm the symptom timeline and recent changes.
2. Review Reliability Monitor for failures and update events.
3. Check Event Viewer for relevant errors.
4. Use safe repair tools when appropriate.
5. Document findings, commands used, and results.

## Documentation Examples

- Include event source, event ID, timestamp, and error summary.
- Record commands run, such as `sfc /scannow` or DISM checks.
- Note whether the issue was resolved or escalated with evidence.

## Ticket Note Examples

**Issue:** User reported application crashing several times per day.

**Technician notes:** Reviewed Reliability Monitor and Event Viewer. Identified repeated application fault at matching timestamps.

**Resolution:** Repaired application install and confirmed stable launch. Ticket documented event details for future reference.

## Key Takeaways

- Windows logs turn vague symptoms into support evidence.
- Reliability Monitor is useful for connecting failures to dates and changes.
- Repair commands should be documented with outcomes.
