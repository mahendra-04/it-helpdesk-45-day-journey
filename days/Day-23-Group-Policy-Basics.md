# Day 23 - Group Policy Basics

**Status:** Lesson Completed

## Learning Objectives

- Understand what Group Policy does in Windows domain environments.
- Learn common user impacts caused by policy settings.
- Recognize what help desk technicians should document before escalation.

## Concepts Learned

- Group Policy Objects, OUs, policy refresh, computer settings, and user settings.
- Common policies for password rules, mapped drives, desktop settings, security, and software restrictions.
- Policy update timing and sign-in effects.
- Support boundaries for troubleshooting policy-related symptoms.

## Real-World Help Desk Examples

- A mapped drive appears for one department but not another.
- A security setting prevents a user from changing a system option.
- A desktop shortcut or printer mapping is missing after sign-in.

## Troubleshooting Workflows

1. Confirm user, device, OU or department, and affected policy behavior.
2. Compare with a known-working user or device.
3. Run approved policy refresh steps when appropriate.
4. Check whether the issue follows the user or device.
5. Escalate with clear scope and policy symptom details.

## Documentation Examples

- Record username, device name, department, expected behavior, and actual behavior.
- Include policy refresh result if performed.
- Note comparison results with another user or device.

## Ticket Note Examples

**Issue:** User reported mapped drive missing after sign-in.

**Technician notes:** Verified user department, checked network access, compared with peer access, and refreshed policy.

**Resolution:** Drive mapping appeared after policy refresh and sign-out/sign-in. User confirmed access to required folder.

## Key Takeaways

- Group Policy explains many consistent environment settings.
- Comparing affected and unaffected users helps narrow policy issues.
- Good policy escalation notes include user, device, department, and expected behavior.
