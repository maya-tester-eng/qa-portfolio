# User Stories (Swag Labs demo)

**US-001 Login**  
As a shopper, I want to sign in so I can view inventory.

**Acceptance Criteria (high-level)**
1. Valid credentials show the Inventory page.
2. Invalid password shows a clear inline error; no session.
3. Locked-out user is blocked with a lock-out message; no session.
4. Empty username/password shows a validation message; user stays on Login.
5. Logout returns to the Login page and clears session.
