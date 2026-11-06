# Requirements Traceability Matrix (RTM)

**Project:** _name_
**Version:** 0.1 | **Owner:** _BA name_ | **Last updated:** _date_

The RTM links each requirement back to the business objective it supports and forward to the stories, tests and sign-off that prove it was delivered. It answers two questions:

- **Forward:** has every requirement been built and tested?
- **Backward:** does everything we're building trace back to an agreed need? (This is how you spot scope creep.)

## Matrix

| Req ID | Requirement (short) | Priority | Objective | Source | User stories | Design / spec ref | Test case IDs | Test status | UAT sign-off | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| BR-01 | | M | OBJ-01 | Workshop 1 | US-01, US-02 | | TC-01, TC-02 | Not run / Pass / Fail | Y/N | Draft / Agreed / Built / Tested / Closed |
| BR-02 | | | | | | | | | | |

A CSV copy is in [`rtm-template.csv`](rtm-template.csv).

## Coverage checks

Run these before each stage gate (requirements sign-off, end of build, go/no-go):

| Check | Result |
|---|---|
| Requirements with no linked story | |
| Requirements with no linked test | |
| Stories with no linked requirement (possible scope creep) | |
| Must-have requirements with failed or unrun tests | |
| Requirements changed since baseline (check change log) | |

## Change log

| Date | Req ID | Change | Reason | Approved by |
|---|---|---|---|---|
| | | | | |
