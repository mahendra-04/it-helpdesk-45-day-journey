# Day 19 - Network Troubleshooting Project

**Status:** Lesson Completed

## Learning Objectives

- Combine networking concepts into complete support scenarios.
- Apply layered troubleshooting from device to destination.
- Create escalation-ready network documentation.

## Concepts Learned

- Layered troubleshooting across device, adapter, IP, DNS, gateway, VPN, and application.
- Scope analysis for single-user, multi-user, and site-wide issues.
- Evidence gathering with Windows network commands.
- Ticket documentation for network incidents.

## Real-World Help Desk Examples

- One user cannot access a file server while others can.
- An office area reports intermittent Wi-Fi drops.
- VPN users can sign in but cannot reach internal resources.

## Troubleshooting Workflows

1. Define scope by affected users, devices, location, and service.
2. Check local network status and IP configuration.
3. Test gateway, DNS, destination reachability, and application access.
4. Compare results with a known-working device or user.
5. Document evidence and escalate with a concise summary.

## Documentation Examples

- Include affected scope, network type, command results, and destination tested.
- Record time of issue and whether symptoms are intermittent.
- Provide escalation teams with enough detail to reproduce the failure.

## Ticket Note Examples

**Issue:** User could not reach internal file server.

**Technician notes:** Verified network connection, checked IP configuration, tested gateway ping, tested DNS lookup, and tried server path.

**Resolution:** File server path worked by IP but not hostname. Escalated as DNS-related issue with command evidence.

## Key Takeaways

- Network troubleshooting works best when each layer is tested in order.
- Scope determines whether a ticket stays with help desk or escalates.
- Clear network evidence reduces back-and-forth between support teams.
