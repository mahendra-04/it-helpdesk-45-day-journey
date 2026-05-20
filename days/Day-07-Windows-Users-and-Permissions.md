# Day 07 - Windows Users and Permissions

**Status:** Lesson Completed

## Learning Objectives

- Understand Windows user accounts, groups, and permissions.
- Learn how local permissions affect file access and application behavior.
- Apply least privilege thinking to support scenarios.

## Concepts Learned

- Standard users, administrators, local groups, UAC, and profile folders.
- NTFS permissions and shared folder permissions.
- Read, write, modify, and full control permission levels.
- Permission inheritance and access denied symptoms.

## Real-World Help Desk Examples

- A user cannot save files to a shared folder.
- An application requires administrator permission to install.
- A profile issue prevents a user from accessing desktop files.

## Troubleshooting Workflows

1. Confirm the user account, device, and folder or application affected.
2. Check whether the issue affects one user or multiple users.
3. Review group membership and folder permissions.
4. Test access after approved permission changes.
5. Document the access request, approval path, and result.

## Documentation Examples

- Record the username, folder path, permission level, and business reason.
- Note approval source for access changes.
- Avoid recording sensitive password details in the ticket.

## Ticket Note Examples

**Issue:** User could not modify files in a department folder.

**Technician notes:** Verified user identity, confirmed folder path, reviewed group membership, and checked NTFS permissions.

**Resolution:** Added user to approved department access group. User signed out and back in, then confirmed file access worked.

## Key Takeaways

- Permission troubleshooting requires identity, path, and access-level clarity.
- Least privilege protects systems while still supporting business needs.
- Access changes should always be documented with approval context.
