# Day 21 - AD Users, Groups, and Permissions

**Status:** Lesson Completed

## Learning Objectives

- Understand how Active Directory users and groups control access.
- Learn why group-based access is preferred in support environments.
- Document access requests with business context and approval.

## Concepts Learned

- User accounts, security groups, distribution groups, group nesting, and role-based access.
- Shared folder access, application access, and department-based permissions.
- Least privilege and access review awareness.
- Difference between granting access directly and using approved groups.

## Real-World Help Desk Examples

- A user needs access to a department shared drive.
- A manager requests access removal for a transferred employee.
- A new team member needs the same access as a peer in the same role.

## Troubleshooting Workflows

1. Confirm requested resource and business reason.
2. Verify approval from the proper owner or manager.
3. Review current group membership and required access group.
4. Apply approved group change and allow replication or sign-in refresh.
5. Test access and document confirmation.

## Documentation Examples

- Include requester, approver, resource name, access level, and group updated.
- Record when access was tested and confirmed.
- Note any replication or sign-out/sign-in requirement.

## Ticket Note Examples

**Issue:** User requested access to Finance shared folder.

**Technician notes:** Confirmed manager approval and identified approved Finance access group.

**Resolution:** Added user to approved group. User signed out and back in, then confirmed folder access.

## Key Takeaways

- Group-based access keeps permissions manageable and auditable.
- Access tickets require approval details.
- Testing after access changes confirms the request is fully resolved.
