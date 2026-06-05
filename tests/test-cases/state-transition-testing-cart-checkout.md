# State Transition Testing — Cart & Checkout Flow

## Objective

Verify cart and checkout behavior using State Transition Testing technique.

---

## State Transitions

| Current State | Action | Next State | Expected Result |
|---|---|---|---|
| Empty Cart | Add product | Product Added | Product appears in cart |
| Product Added | Remove product | Empty Cart | Cart becomes empty |
| Product Added | Start checkout | Checkout Started | Checkout form opens |
| Checkout Started | Complete checkout | Checkout Completed | Success message displayed |

---

## Notes

State Transition Testing validates how the application behaves when moving between different system states.