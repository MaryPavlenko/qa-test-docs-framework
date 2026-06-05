# Bug Status Workflow

**Overview**: Bug Status Workflow describes how a bug moves through different statuses from creation to closure. The exact workflow may differ between teams and tools, but the core logic is usually similar.

**Standard Bug Workflow**

```text
New → Assigned → Open → Fixed → Ready for Retest → Retest → Verified → Closed
```
**Workflow Description**

| Status | Owner | Description |
|---|---|---|
| New | QA | Bug is reported and waiting for review |
| Assigned | QA Lead / Manager | Bug is assigned to a responsible developer or team |
| Open | Developer | Bug is accepted and work has started |
| Fixed | Developer | Code fix has been implemented |
| Ready for Retest | Developer / QA | Fix is deployed to a test environment |
| Retest | QA | QA verifies the fix |
| Verified | QA | QA confirms that the defect is fixed |
| Closed | QA / QA Lead | Bug is fully resolved |

---

**Additional Statuses**

| Status | Description |
|---|---|
| Reopened | Bug still reproduces after the fix |
| Rejected | Bug is not valid or expected behavior |
| Duplicate | Same issue has already been reported |
| Cannot Reproduce | Team cannot reproduce the issue |
| Deferred | Bug is valid but postponed |
| Won’t Fix | Team decides not to fix the issue |

---

**Example: Successful Bug Fix**

1. QA reports a bug: cart counter does not update after item removal.
2. Bug status: `New`.
3. Developer accepts the bug.
4. Bug status: `Open`.
5. Developer fixes the issue.
6. Bug status: `Fixed`.
7. Fix is deployed to the test environment.
8. Bug status: `Ready for Retest`.
9. QA retests the scenario.
10. Bug status: `Verified`.
11. Bug is closed.

---

**Example: Bug Reopened**

1. Developer marks the bug as `Fixed`.
2. QA retests the issue.
3. The issue still reproduces.
4. QA changes status to `Reopened`.
5. Developer investigates and fixes the issue again.

---

**Good Practices**

- Use clear and consistent bug statuses.
- Add comments when changing bug status.
- Attach screenshots, videos or logs when reopening a bug.
- Do not close bugs without retesting.
- Link related test cases and requirements when possible.
