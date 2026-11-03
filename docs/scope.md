# BorrowBox M0 Scope

BorrowBox is a small campus service for borrowing items. This scope keeps the
first version focused and easy to explain.

## Included features

- Students can browse, search, and filter lending items.
- Students can see item category and availability.
- Students can submit a borrow request.
- Students can view the status of their own requests.
- The server validates dates, the three-day maximum, and overlapping bookings.
- Valid requests are saved with a **Pending** status.
- Items and requests are stored in a database file so data survives a server restart.
- Request statuses: **Pending** → **Approved** → **Picked up** → **Returned**, or **Pending** → **Rejected**.
- Staff can approve or reject requests.
- Staff can mark items as picked up or returned.
- The system supports two roles: student and staff.

## Excluded features

- Payments
- Notifications
- University login
- Barcode scanning
- Cloud hosting

## Roles

### Student

Browses items and submits borrow requests. Students can view the status of their
own requests but cannot approve, reject, or change loan tracking statuses. The
server enforces these access rules.

### Staff

Reviews requests and manages approval, rejection, pickup, and return statuses.