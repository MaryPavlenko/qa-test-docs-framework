# Equivalence Partitioning

## What is Equivalence Partitioning?

Equivalence Partitioning (EP) is a test design technique used to divide input data into groups called equivalence classes.
The idea behind this technique is:
> if one value from a class works correctly, other values from the same class are expected to behave similarly.
This helps reduce the number of test cases while maintaining good test coverage.

---

# When to use it

Equivalence Partitioning is useful for testing:

- input validation;
- form fields;
- numeric ranges;
- text length restrictions;
- required fields;
- login forms;
- API request parameters.

---

# Types of Equivalence Classes

## Valid Equivalence Class
Contains values that should be accepted by the system.

## Invalid Equivalence Class
Contains values that should be rejected by the system.

---

# Example

## Feature
Login form.

## Requirement
The password field must contain from 8 to 20 characters.

---

# Equivalence Classes
| Class Type | Description | Example |
|---|---|---|
| Valid | Password length from 8 to 20 characters | Password123 |
| Invalid | Password shorter than 8 characters | Pass12 |
| Invalid | Password longer than 20 characters | VeryLongPassword123456 |

---
# Example Test Cases
| Test Case ID | Input Value | Class Type | Expected Result |
|---|---|---|---|
| EP-01 | Password123 | Valid | Password accepted |
| EP-02 | Pass12 | Invalid | Validation error displayed |
| EP-03 | VeryLongPassword123456 | Invalid | Validation error displayed |

---

# Benefits of Equivalence Partitioning
- reduces the number of test cases;
- improves testing efficiency;
- helps organize test coverage;
- simplifies validation testing.
