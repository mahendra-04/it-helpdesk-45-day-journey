# Day 38 - Network and VPN Support Scenarios

**Status:** Lesson Completed

## Learning Objectives

- Apply network and VPN troubleshooting to realistic support cases.
- Separate local connectivity, DNS, VPN, and resource access issues.
- Create escalation-ready notes for network teams.

## Concepts Learned

- Connectivity scope, adapter status, DHCP, DNS, gateway, VPN tunnel, and internal resource testing.
- Home network vs corporate network support boundaries.
- Command-line evidence for network and VPN tickets.
- Priority considerations for remote users.

## Real-World Help Desk Examples

- A remote user can browse the internet but cannot connect to VPN.
- VPN connects but mapped drives do not work.
- A user loses Wi-Fi intermittently in a specific office area.

## Troubleshooting Workflows

1. Confirm location, connection type, and affected resources.
2. Test local internet before VPN.
3. Verify VPN authentication, MFA, tunnel status, and internal DNS.
4. Test resource access by name and path where appropriate.
5. Escalate with command results, timestamps, and scope.

## Documentation Examples

- Record VPN client version, error message, IP details, DNS lookup result, and resource path.
- Note whether issue occurs on one network or multiple networks.
- Include outage scope if multiple users are affected.

## Ticket Note Examples

**Issue:** Remote user could not access mapped drive while connected to VPN.

**Technician notes:** Confirmed VPN connected, internet worked, internal DNS failed, and server path by hostname was unreachable.

**Resolution:** Escalated to network team with VPN IP, DNS test result, and affected drive path.

## Key Takeaways

- Remote access issues need clear separation between VPN sign-in and resource access.
- DNS is a common factor in VPN support.
- Network escalations should include command evidence and scope.
