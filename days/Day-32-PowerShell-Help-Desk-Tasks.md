# Day 32 - PowerShell Help Desk Tasks

**Status:** Lesson Completed

## Learning Objectives

- Apply PowerShell basics to common help desk tasks.
- Review services, processes, event logs, and network details with commands.
- Document PowerShell findings in a professional support format.

## Concepts Learned

- `Get-Service`, `Restart-Service`, `Get-Process`, `Get-EventLog`, `Get-NetIPConfiguration`, and `Test-Connection`.
- Service status checks and controlled restarts.
- Process review for performance issues.
- Network and event log evidence collection.

## Real-World Help Desk Examples

- A print service needs status verification.
- A process is consuming high CPU and affecting user work.
- A network configuration summary is needed for escalation.

## Troubleshooting Workflows

1. Identify the support question before running commands.
2. Use read-only commands to collect system state.
3. Use approved commands for service restart or repair when appropriate.
4. Verify the user-facing result after the command.
5. Document commands and outcomes.

## Documentation Examples

- Include service name, previous state, action taken, and final state.
- Summarize event log errors by source, ID, and timestamp.
- Record network configuration details without excessive output.

## Ticket Note Examples

**Issue:** User could not print from Windows laptop.

**Technician notes:** Used PowerShell to check Print Spooler service status and restart the service.

**Resolution:** Print Spooler restarted successfully. Test page printed and user confirmed normal printing.

## Key Takeaways

- PowerShell can speed up common support checks.
- Commands should be tied to a clear troubleshooting purpose.
- Ticket notes should include both command action and user result.
