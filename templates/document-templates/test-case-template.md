# Test Case Template

This template can be used to document manual test cases, including functional test cases and test cases based on test design techniques.

---

# General Test Case Template

## Test Case ID
[Unique identifier]

## Title
[Short, descriptive title]

## Related Requirement
[Requirement ID, e.g. FR-01]

## Objective
[What is being tested?]

## Priority
[Low / Medium / High]

## Preconditions
[Required setup or initial state]

## Test Data
[Input data used during the test]

## Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | [Action] | [Expected result] |
| 2 | [Action] | [Expected result] |
| 3 | [Action] | [Expected result] |

## Actual Result
[Observed result during execution]

## Status
- [ ] Passed
- [ ] Failed
- [ ] Blocked
- [ ] Not Run

## Postconditions
[Expected state after test execution]

## Notes
[Additional comments, risks or related defect IDs]

---

# Boundary Value Analysis Test Case Template

## Test Case ID
[Unique identifier]

## Title
[Short, descriptive title]

## Objective
[What is being tested?]

## Preconditions
[Required setup or initial state]

## Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | [Action] | [Expected result] |
| 2 | [Action] | [Expected result] |

## Boundary Values

| Scenario | Input Value | Expected Result |
|---|---|---|
| Just Below Minimum | [value] | [expected outcome] |
| Minimum Boundary | [value] | [expected outcome] |
| Just Above Minimum | [value] | [expected outcome] |
| Just Below Maximum | [value] | [expected outcome] |
| Maximum Boundary | [value] | [expected outcome] |
| Just Above Maximum | [value] | [expected outcome] |

## Postconditions
[Expected state after execution]

## Reference
Myers et al. (2011)

---

# Equivalence Partitioning Test Case Template

## Test Case ID
[Unique identifier]

## Title
[Short, descriptive title]

## Objective
[What is being tested?]

## Preconditions
[Required setup or initial state]

## Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | [Action] | [Expected result] |
| 2 | [Action] | [Expected result] |

## Input Partitions

| Partition Type | Input Example | Expected Result |
|---|---|---|
| Valid | [example input] | [expected outcome] |
| Invalid | [example input] | [expected error/result] |

## Postconditions
[Expected state after execution]

---

# Decision Table Testing Test Case Template

## Test Case ID
[Unique identifier]

## Title
[Short, descriptive title]

## Objective
[What is being tested?]

## Preconditions
[Required setup or initial state]

## Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | [Action] | [Expected result] |
| 2 | [Action] | [Expected result] |

## Decision Table

| Rule | Condition 1 | Condition 2 | Condition 3 | Expected Action / Result |
|---|---|---|---|---|
| R1 | [value] | [value] | [value] | [expected outcome] |
| R2 | [value] | [value] | [value] | [expected outcome] |

## Postconditions
[Expected state after execution]

---

# State Transition Testing Test Case Template

## Test Case ID
[Unique identifier]

## Title
[Short, descriptive title]

## Objective
[What is being tested?]

## Preconditions
[Required setup or initial state]

## Test Steps

| Step | Action | Expected Result |
|---|---|---|
| 1 | [Action] | [Expected result] |
| 2 | [Action] | [Expected result] |

## State Transitions

| Current State | Action / Event | Next State | Expected Result |
|---|---|---|---|
| [state] | [event] | [state] | [expected outcome] |
| [state] | [event] | [state] | [expected outcome] |

## Postconditions
[Expected state after execution]