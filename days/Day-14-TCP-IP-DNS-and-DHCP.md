# Day 14 - TCP/IP, DNS, and DHCP

**Status:** Lesson Completed

## Learning Objectives

- Understand core TCP/IP concepts used in help desk troubleshooting.
- Learn how DNS and DHCP support user connectivity.
- Recognize common symptoms of addressing and name-resolution issues.

## Concepts Learned

- IP address, subnet mask, default gateway, DNS server, MAC address, and lease.
- DHCP lease assignment and renewal.
- DNS name resolution and common failure patterns.
- Difference between reaching an IP address and reaching a hostname.

## Real-World Help Desk Examples

- A device has an APIPA address and cannot reach the network.
- A website opens by IP address but not by name.
- A user loses access after moving between networks.

## Troubleshooting Workflows

1. Run `ipconfig /all` to review IP, gateway, DNS, and DHCP details.
2. Test gateway reachability with `ping`.
3. Test name resolution with `nslookup`.
4. Renew DHCP settings if appropriate.
5. Document network details and test results.

## Documentation Examples

- Record IP address, gateway, DNS servers, DHCP status, and error messages.
- Include ping and DNS lookup results.
- Note whether the issue points to device, DHCP, DNS, or network infrastructure.

## Ticket Note Examples

**Issue:** User could connect to Wi-Fi but could not reach websites.

**Technician notes:** Checked IP configuration, gateway response, and DNS lookup. IP address was valid, but DNS lookup failed.

**Resolution:** Updated DNS settings through approved network profile refresh. Websites loaded successfully by name.

## Key Takeaways

- DNS and DHCP are common causes of network support tickets.
- Command output provides clear evidence for escalation.
- Name-resolution testing helps separate DNS issues from general connectivity.
