# BorrowBox M0 Scope

BorrowBox is a small campus service for borrowing items. This scope keeps the
first version focused and easy to explain.

## Included features

- Students can browse, search, and filter lending items.
- Students can see item category and availability.
- Students can submit a borrow request.
- The server validates dates, the three-day maximum, and overlapping bookings.
- Valid requests are saved with a **Pending** status.
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

Browses items and submits borrow requests. Students cannot approve, reject, or
change loan tracking statuses.

### Staff

Reviews requests and manages approval, rejection, pickup, and return statuses.
