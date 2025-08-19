# BUG-001: Error icon overlaps password field on small window

Type: UI/Accessibility | Area: Auth/Login | Env: macOS, Chrome latest, window ~900×700

## Steps
1) Open https://www.saucedemo.com
2) Username: standard_user
3) Password: wrongpass
4) Click Login
5) Resize window to ~900×700

**Expected:** Error/inputs visible and readable.  
**Actual:** Error icon overlaps password input; text hard to read.  
**Evidence:** screenshots/login-error-overlap.png (placeholder)  
Severity: Minor | Priority: Medium

