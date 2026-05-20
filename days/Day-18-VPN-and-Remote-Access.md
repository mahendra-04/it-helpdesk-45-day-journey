# Day 18 - VPN and Remote Access

**Status:** Lesson Completed

## Learning Objectives

- Understand VPN and remote access support basics.
- Learn common VPN failure points involving credentials, MFA, internet, and client configuration.
- Document remote access issues with useful technical details.

## Concepts Learned

- VPN client, authentication, MFA, tunnel, split tunnel, and remote resource access.
- Difference between VPN connection failure and resource access failure after connection.
- Remote support etiquette, identity verification, and user consent.
- Common home network factors that affect VPN reliability.

## Real-World Help Desk Examples

- A user cannot complete MFA during VPN sign-in.
- VPN connects but internal shared drives are unavailable.
- A remote user has unstable internet causing repeated disconnects.

## Troubleshooting Workflows

1. Confirm internet access before VPN connection.
2. Verify VPN client status, error message, username, and MFA prompt behavior.
3. Test internal resource access after connection.
4. Check DNS, mapped drives, and account access as needed.
5. Document VPN status, error text, and resource test results.

## Documentation Examples

- Record VPN client name, error message, connection time, and affected resource.
- Note whether MFA completed successfully.
- Include whether the issue occurs on one network or multiple networks.

## Ticket Note Examples

**Issue:** User reported VPN connected but shared drive would not open.

**Technician notes:** Confirmed VPN tunnel active, tested internet access, checked internal DNS lookup, and attempted drive access by path.

**Resolution:** Internal DNS resolution failed. Escalated with VPN IP, DNS test result, and affected shared drive path.

## Key Takeaways

- VPN support should separate sign-in issues from resource access issues.
- MFA and home internet quality are common remote access factors.
- Clear command results make VPN escalations stronger.
