# State Transition Testing

## What is State Transition Testing?
State Transition Testing is a test design technique used to verify how a system behaves when moving between different states.
A state represents a specific condition or status of the system at a given moment.
This technique focuses on:
- valid transitions between states;
- invalid transitions;
- actions that trigger state changes.

---

# When to use it
State Transition Testing is useful for testing:
- login/logout flows;
- shopping carts;
- order statuses;
- payment flows;
- user account states;
- booking systems;
- workflow-based applications.

---

# Key Concepts
| Term | Description |
|---|---|
| State | Current condition of the system |
| Transition | Movement from one state to another |
| Event | Action that triggers a transition |

---

# Example from Swag Labs
## Feature
Shopping cart and checkout flow.

---

# States
| State ID | State |
|---|---|
| S1 | User logged in |
| S2 | Product added to cart |
| S3 | Checkout started |
| S4 | Order completed |

---

# Valid Transitions
| Current State | Event | Next State |
|---|---|---|
| S1 | Add product to cart | S2 |
| S2 | Start checkout | S3 |
| S3 | Complete order | S4 |

---

# Invalid Transitions
| Current State | Invalid Action | Expected Result |
|---|---|---|
| S1 | Complete order without cart | Error / action blocked |
| S2 | Complete order without checkout | Error / action blocked |
| S4 | Complete checkout again | Action blocked |

---

# Example Test Cases
| Test Case ID | Initial State | Action | Expected State |
|---|---|---|---|
| ST-01 | Logged in | Add product to cart | Product added to cart |
| ST-02 | Product in cart | Start checkout | Checkout page opened |
| ST-03 | Checkout started | Complete order | Order completed |
| ST-04 | Logged in | Complete order without cart | Error displayed |

---

# Benefits of State Transition Testing
- helps validate workflow logic;
- improves coverage of user flows;
- detects invalid state changes;
- useful for complex systems with multiple statuses.