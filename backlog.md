# ShiftSwap Product Backlog

## Sprint 1 Goal

Employees can post and request to pick up open shifts, and managers can approve or deny each request before a swap is finalized.

## Sprint 1 MVP

Items are ordered by workflow dependency and priority.

### 1. Confirm MVP shift and approval rules

**User story:** As Operations and HR, we want to agree on the minimum shift information and approval rules so employees and managers can use a consistent workflow.

**Acceptance criteria**

- Operations and HR agree on the information needed to identify a shift.
- Any eligibility rules needed for the MVP are documented.
- Cases without an agreed rule are left for manager review, as stated in the charter.

### 2. Post a shift needing coverage

**User story:** As an hourly employee, I want to post a shift I cannot work so a coworker can request to pick it up.

**Acceptance criteria**

- An employee can enter the agreed shift information and submit it for coverage.
- Missing required information is clearly identified before submission.
- A successfully posted shift is visible among open shifts.

### 3. View and request an open shift

**User story:** As an hourly employee, I want to view open shifts and request to pick one up.

**Acceptance criteria**

- Employees can view shifts available for coverage.
- An employee can submit a request to pick up an open shift.
- The request is shown as awaiting a manager decision and is not treated as a final swap.

### 4. Review and decide on requests

**User story:** As a manager, I want to review shift-pickup requests and approve or deny them so swaps follow the required approval process.

**Acceptance criteria**

- Managers can find pending requests and the shift details needed to review them.
- A manager can approve or deny a request.
- Approval finalizes the swap; denial does not.

### 5. Show request status

**User story:** As an employee involved in a request, I want to see its current status so I know whether the manager has made a decision.

**Acceptance criteria**

- Employees can see whether each request is pending, approved, or denied.
- The displayed status reflects the manager's decision.

### 6. Verify and demonstrate the core workflow

**User story:** As the project team, we want to verify the end-to-end workflow so stakeholders can review the MVP by the end of Sprint 1.

**Acceptance criteria**

- The team tests posting a shift, requesting to pick it up, and the manager's approval and denial paths.
- Request status is visible after each manager decision.
- The core workflow is demonstrated in a web browser before Sprint 1 ends.

## Deferred: Out of Scope for v1

- **Third-party integrations:** Defer until the core workflow is validated; integrations add setup and support work.
- **Single sign-on (SSO):** Defer to avoid coupling the MVP to organization-specific identity-provider configuration.
- **Payroll and overtime integration or calculations:** Defer because pay rules require additional HR/payroll validation and are outside shift-request handling.
