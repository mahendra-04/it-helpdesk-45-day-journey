# Day 31 - PowerShell Basics

**Status:** Lesson Completed

## Learning Objectives

- Understand the role of PowerShell in Windows support.
- Learn safe command discovery and basic command structure.
- Use PowerShell to collect support information.

## Concepts Learned

- Cmdlets, verbs, nouns, parameters, pipeline basics, and command output.
- `Get-Help`, `Get-Command`, `Get-ComputerInfo`, and `Get-Service`.
- Difference between viewing information and making system changes.
- Importance of running commands with appropriate permissions.

## Real-World Help Desk Examples

- A technician needs quick system information for a ticket.
- A service status must be checked without opening Services.
- A user device needs evidence collected before escalation.

## Troubleshooting Workflows

1. Open PowerShell with the correct permission level.
2. Use `Get-Help` or `Get-Command` to confirm command syntax.
3. Run read-only checks first.
4. Capture relevant output for documentation.
5. Avoid changes unless approved and understood.

## Documentation Examples

- Record command used and a concise summary of output.
- Note whether PowerShell was run as standard user or administrator.
- Include device name, Windows version, and service status when relevant.

## Ticket Note Examples

**Issue:** Technician needed system details for escalation.

**Technician notes:** Ran `Get-ComputerInfo` and reviewed OS version, device name, and system type.

**Resolution:** Added system details to escalation notes for accurate troubleshooting by the next support tier.

## Key Takeaways

- PowerShell is valuable for fast evidence gathering.
- Read-only commands are a safe starting point.
- Command output should be summarized clearly in tickets.
