# User Story and Acceptance Criteria

## Template

```text
ID:          US-XX
Title:       Short, action-based title
Epic:        EP-XX Epic name
Linked req:  BR-XX

As a        <type of user>
I want      <goal>
So that     <reason / benefit>

Acceptance criteria
  AC1  Given <context>
       When  <action>
       Then  <expected result>

  AC2  Given ...
       When  ...
       Then  ...

Priority:     Must / Should / Could / Won't
Estimate:     (set by the team)
Notes:        Business rules, edge cases, links to designs
Dependencies: Other stories, systems or teams
```

## Worked example

```text
ID:          US-07
Title:       Customer tracks refund status
Epic:        EP-02 Refunds
Linked req:  BR-05

As a        customer who has returned an item
I want      to see the status of my refund online
So that     I don't need to call customer services to find out

Acceptance criteria
  AC1  Given I am signed in and have a return in progress
       When  I open "My returns"
       Then  I see each return with its status: Requested, Received, Approved, Refunded or Rejected

  AC2  Given my refund has been issued
       When  I view the return
       Then  I see the refund amount, the payment method and the date it was issued

  AC3  Given my return was rejected
       When  I view the return
       Then  I see the reason and how to contact customer services

Priority:     Must
Notes:        Status wording to be agreed with Customer Services lead
```

## Quality checklist (INVEST)

- [ ] **Independent:** can be built and released without waiting on another story, where possible
- [ ] **Negotiable:** describes the need, not a fixed design
- [ ] **Valuable:** the "so that" names a real benefit to a user or the business
- [ ] **Estimable:** the team understands it well enough to size it
- [ ] **Small:** fits in one sprint
- [ ] **Testable:** every acceptance criterion has a clear pass/fail result

## Definition of Ready (example)

- [ ] Story meets INVEST
- [ ] Acceptance criteria agreed with the product owner
- [ ] Dependencies identified
- [ ] Designs or wireframes linked, if needed
- [ ] Data protection questions answered, if personal data is involved
