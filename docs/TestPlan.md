# Test Plan — Swag Labs (Login & Basic Flows)

## 1. Objective
- Validate core flows: **login** (positive/negative/edge), **logout**, **inventory visible**.

## 2. Scope
- **In**: Chrome desktop (EN), UI behavior, simple accessibility notes.
- **Out (phase 1)**: Mobile, checkout/payment, performance, i18n.

## 3. Approach
- Manual functional tests (case-based + exploratory).
- Light regression/smoke on each change.
- Evidence via screenshots/GIFs.

## 4. Test Data & Environment
- URL: https://www.saucedemo.com
- Users: `standard_user`, `locked_out_user` (public demo).
- Desktop macOS + Chrome latest.

## 5. Entry / Exit Criteria
- **Entry**: Site reachable; demo users work.
- **Exit**: Planned tests executed; high/critical defects logged; summary updated.

## 6. Deliverables
- CSV test cases with status.
- Markdown bug reports with steps/evidence.
- Final notes in README.

## 7. Risks & Mitigation
- Demo site may change or throttle → document test date; retry once; capture evidence.
- Network/browser flakiness → re-run and note versions.

## 8. Roles & Tools
- Role: Individual tester (Maya).
- Tools: GitHub (repo), Jira (if available), Chrome, macOS screenshots.

## 9. Reporting
- Daily update via CSV “Status” + bug links.
- Summary comment in README after each session.

