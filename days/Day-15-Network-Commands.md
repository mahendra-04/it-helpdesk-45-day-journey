# Day 15 - Network Commands

**Status:** Lesson Completed

## Learning Objectives

- Learn common Windows network commands used in help desk support.
- Interpret command output in practical troubleshooting scenarios.
- Document command results clearly in tickets.

## Concepts Learned

- `ipconfig`, `ping`, `tracert`, `nslookup`, `netstat`, and `hostname`.
- Packet loss, latency, hop path, DNS lookup results, and active connections.
- Local adapter details, gateway tests, and external reachability checks.
- How command-line evidence supports escalation.

## Real-World Help Desk Examples

- A user can access internal apps but not external websites.
- VPN connects, but a file server cannot be reached.
- A website outage needs evidence before escalation.

## Troubleshooting Workflows

1. Start with `ipconfig` to confirm current network configuration.
2. Ping loopback, gateway, internal resources, and external resources as needed.
3. Use `nslookup` to test DNS resolution.
4. Use `tracert` to identify where traffic stops.
5. Save concise command results in the ticket.

## Documentation Examples

- Record command, target, result, and timestamp.
- Include packet loss, DNS response, and unreachable hop details.
- Avoid pasting excessive output when a summary is enough.

## Ticket Note Examples

**Issue:** User could not reach internal file server over VPN.

**Technician notes:** Verified VPN connection, ran `ipconfig`, pinged gateway, and tested file server name resolution.

**Resolution:** DNS lookup failed for internal server name. Escalated to network team with VPN IP details and command results.

## Key Takeaways

- Network commands provide fast, objective troubleshooting evidence.
- Testing should move from local device to gateway to destination.
- Good command summaries make escalations easier to act on.
