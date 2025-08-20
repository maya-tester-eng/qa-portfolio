# BUG-001: Misleading login error message ("and" vs "or")

**Links:** US-001, TC-002  
**Type:** UI / Content  
**Area:** Authentication / Login  
**Env:** macOS, Chrome latest  
**URL:** https://www.saucedemo.com

## Steps to Reproduce
1) Open the login page  
2) Username: `standard_user`  
3) Password: `wrongpass`  
4) Click **Login**

## Expected
- Error message should be clear and generic: **"Username or password is incorrect."**  
  (Common practice: do not reveal which one is wrong.)

## Actual
- Error message says: **"Username and password do not match."**  
  → This wording suggests both are wrong and can confuse users.

## Impact
- Confusing UX; not aligned with common login wording patterns.
- Related test: **TC-002** under **US-001**.

## Evidence
- Screenshot attached in repo: `screenshots/bug-001-login-error-wording.png`

