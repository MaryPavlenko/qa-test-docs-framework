# Defect Life Cycle Example

## Overview

Defect Life Cycle describes the path a defect follows from the moment it is found to the moment it is resolved and closed.

It helps the team understand:

- who is responsible for the defect at each stage;
- what action is expected next;
- whether the defect is still active, fixed, verified or closed.

---

## Defect Life Cycle Stages

| Status | Description |
|---|---|
| New | The defect has been found and reported by QA |
| Assigned | The defect has been assigned to the responsible developer or team |
| Open | The defect has been reviewed and accepted for investigation or fixing |
| Fixed | The developer has implemented a fix |
| Ready for Retest | The fix is available in the test environment |
| Retest | QA is verifying whether the defect has been fixed |
| Verified | QA confirms that the defect no longer reproduces |
| Closed | The defect is fully resolved and no further action is required |
| Reopened | The defect still reproduces after the fix or the fix caused another issue |
| Rejected | The reported issue is not considered a valid defect |
| Duplicate | The same defect has already been reported |
| Deferred | The defect is valid but postponed to a later release |

---

## High-Level Explanation

A defect usually starts as `New` when QA reports it during testing.

After review, it is assigned to a developer and moved to `Open`. Once the developer implements a fix, the defect moves to `Fixed` or `Ready for Retest`.

QA then retests the issue. If the fix works correctly, the defect becomes `Verified` and then `Closed`.

If the issue still reproduces, QA moves the defect to `Reopened` so the developer can continue investigation.

Some defects may also be marked as `Rejected`, `Duplicate` or `Deferred` depending on the team decision.

---

## Why Defect Life Cycle Matters

A clear defect life cycle helps the team:

- track defect ownership;
- understand the current status of each defect;
- avoid losing reported issues;
- improve communication between QA, developers and product managers;
- support release decisions;
- reduce the risk of unresolved defects reaching production.