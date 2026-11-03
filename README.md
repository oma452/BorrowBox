# BorrowBox

BorrowBox is a campus micro-lending service for students and staff. Students
can find and request small items such as chargers, calculators, HDMI adapters,
and lab kits. Staff approve requests and track each loan.

## Team

| Name | ID | University email | GitHub |
|---|---:|---|---|
| Omar Shibl (team leader) | 231147 | omar.mohamed190@msa.edu.eg | oma452 |
| Ahmed Walid | 220953 | ahmed.walid5@msa.edu.eg | ahmedwalid00 |

## User journeys

### J1 Browse

- **User:** Student
- **Action:** Searches for an item and filters by category and availability.
- **Server/data:** The server reads the item data and applies the search and
  filter choices.
- **Visible result:** Matching available items are shown to the student.

### J2 Submit

- **User:** Student
- **Action:** Submits a request to borrow an item.
- **Server/data:** The server checks that the return date is after pickup, the
  loan is no more than 3 days, and there is no overlapping booking. If valid,
  it saves the request as **Pending**.
- **Visible result:** The student sees confirmation that the request is
  pending, or an explanation of the validation error.

### J3 Update

- **User:** Staff
- **Action:** Approves, rejects, marks picked up, or marks returned for a loan.
- **Server/data:** The server checks that the user is staff, then updates the
  loan status. Students are not allowed to perform these actions.
- **Visible result:** Staff see the updated status; students cannot make staff
  status changes.

## Setup

Coming in a later milestone.

## M0 files

- `README.md` explains the project, team, and user journeys.
- `docs/scope.md` defines what is included and excluded from the project.
- `.gitignore` prevents dependencies, secrets, databases, and OS files from
  being committed.