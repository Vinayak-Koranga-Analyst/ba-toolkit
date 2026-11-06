# UAT Plan and Test Script

**Project:** _name_
**Version:** 0.1 | **Owner:** _BA / test lead_ | **Last updated:** _date_

---

## Part A: UAT plan

### 1. Purpose

User acceptance testing (UAT) confirms that the solution supports the business process and meets the agreed requirements, tested by the people who will use it.

### 2. Scope

| In scope | Out of scope |
|---|---|
| e.g. end-to-end returns process for online orders | e.g. performance testing (covered by system testing) |

### 3. Approach

- **Environment:** _UAT environment name, data refresh date_
- **Test data:** _how it's prepared; no live personal data unless approved_
- **Testers:** _names / roles from the business_
- **Schedule:** _start and end dates, daily triage time_
- **Tools:** _e.g. Jira / Excel tracker_

### 4. Entry criteria

- [ ] System and integration testing complete, with no open critical defects
- [ ] UAT environment and test data ready
- [ ] Test scripts reviewed and agreed by business leads
- [ ] Testers briefed and have access

### 5. Exit criteria

- [ ] All Must-have test cases run
- [ ] No open Critical or High defects (or agreed workarounds in place)
- [ ] Medium/Low defects logged with an agreed plan
- [ ] Business sign-off obtained

### 6. Defect severity

| Severity | Definition | Example |
|---|---|---|
| Critical | Process cannot be completed; no workaround | Refund cannot be issued |
| High | Major function wrong; workaround is difficult | Wrong refund amount calculated |
| Medium | Function works with a reasonable workaround | Status email has the wrong order number |
| Low | Cosmetic or minor | Typo on confirmation page |

### 7. Roles

| Role | Name | Responsibility |
|---|---|---|
| UAT lead | | Plans, tracks and reports progress |
| Business testers | | Run scripts, record results, raise defects |
| BA | | Writes scripts, clarifies requirements, triages defects |
| Dev / support | | Fixes and redeploys defects |
| Business sign-off | | Accepts the solution |

---

## Part B: Test script

| Field | Value |
|---|---|
| Test case ID | TC-XX |
| Title | |
| Requirement / story | BR-XX / US-XX |
| Priority | Must / Should / Could |
| Preconditions | e.g. customer account exists with a delivered order |
| Test data | |
| Tester | |
| Date run | |

| Step | Action | Expected result | Actual result | Pass / Fail | Defect ID |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |

**Overall result:** Pass / Fail / Blocked
**Tester comments:**

---

## Part C: Progress tracker

| Test case | Title | Priority | Tester | Status | Defects | Notes |
|---|---|---|---|---|---|---|
| TC-01 | | | | Not run / Pass / Fail / Blocked | | |

## Sign-off

| Name | Role | Decision | Date |
|---|---|---|---|
| | Business owner | Accepted / Accepted with conditions / Not accepted | |
