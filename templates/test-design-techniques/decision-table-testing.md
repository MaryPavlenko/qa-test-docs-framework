# Decision Table Testing

## What is Decision Table Testing?

Decision Table Testing is a test design technique used to verify system behavior for different combinations of input conditions.

It is especially useful when:

- multiple conditions affect the result;
- business rules depend on combinations of inputs;
- the number of possible scenarios grows quickly.

Decision tables help ensure that all important combinations are tested.

---

# When to use it

Decision Table Testing is useful for:

- login logic;
- checkout flows;
- discounts and promotions;
- access permissions;
- payment methods;
- form validation;
- feature flags.

---

# Example from Swag Labs

## Feature

Checkout process.

## Business Rule

The user can complete checkout only if:

- First Name is заполнено;
- Last Name is заполнено;
- Postal Code is заполнен.

If at least one required field is missing, the system must display a validation error.

---

# Conditions

| Condition ID | Condition |
|---|---|
| C1 | First Name entered |
| C2 | Last Name entered |
| C3 | Postal Code entered |

---

# Actions

| Action ID | Action |
|---|---|
| A1 | Allow checkout |
| A2 | Display validation error |

---

# Decision Table

| Rule | C1 | C2 | C3 | A1 | A2 |
|---|---|---|---|---|---|
| R1 | Y | Y | Y | Y | N |
| R2 | N | Y | Y | N | Y |
| R3 | Y | N | Y | N | Y |
| R4 | Y | Y | N | N | Y |
| R5 | N | N | Y | N | Y |
| R6 | N | Y | N | N | Y |
| R7 | Y | N | N | N | Y |
| R8 | N | N | N | N | Y |

---

# Example Test Cases

| Test Case ID | First Name | Last Name | Postal Code | Expected Result |
|---|---|---|---|---|
| DT-01 | John | Smith | 12345 | Checkout allowed |
| DT-02 | empty | Smith | 12345 | Validation error |
| DT-03 | John | empty | 12345 | Validation error |
| DT-04 | John | Smith | empty | Validation error |

---

# Benefits of Decision Table Testing

- helps cover complex combinations;
- reduces missed scenarios;
- improves test coverage;
- simplifies business rule validation.
