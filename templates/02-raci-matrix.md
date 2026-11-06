# RACI Matrix

**Project:** _name_
**Version:** 0.1 | **Owner:** _BA name_ | **Last updated:** _date_

## Key

| Letter | Meaning | Rule of thumb |
|---|---|---|
| **R** | Responsible | Does the work. Can be more than one person |
| **A** | Accountable | Owns the outcome and signs it off. **Exactly one per activity** |
| **C** | Consulted | Gives input before the work is done (two-way) |
| **I** | Informed | Told about the outcome (one-way) |

## Matrix

| Activity / deliverable | Sponsor | Product owner | Business analyst | Project manager | Dev lead | Test lead | Business SMEs | Data protection |
|---|---|---|---|---|---|---|---|---|
| Approve business case | A | C | C | R | I | I | C | C |
| Define scope | A | R | R | C | C | I | C | I |
| Run requirements workshops | I | C | A/R | I | C | C | C | I |
| Write and baseline BRD | I | A | R | C | C | C | C | C |
| Write user stories and acceptance criteria | I | A | R | I | C | C | C | I |
| Prioritise backlog | C | A/R | C | C | C | I | C | I |
| Review data protection impact | I | C | C | I | C | I | I | A/R |
| Write UAT scripts | I | C | R | I | I | A | C | I |
| Run UAT | I | C | C | I | I | A | R | I |
| Sign off go-live | A | R | C | R | C | C | C | C |

_Replace the example rows and columns with your own. Keep roles as columns and activities as rows._

## Checks before you share it

- [ ] Every activity has **one** A, no more and no fewer
- [ ] Every activity has at least one R
- [ ] Nobody is C on so many rows that they become a bottleneck
- [ ] Each role column has at least one R or A (if not, do they need to be on the matrix?)
- [ ] The people named have seen and agreed their row
