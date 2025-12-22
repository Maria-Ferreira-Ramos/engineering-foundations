# Paid Lessons Flow

## Overview
This document describes how paid lessons work between tutors and students within the platform.

## Roles
- Tutor: A user who offers paid lessons.
- Student: A user who books and attends lessons.

## Lesson Listing
Tutors can create lesson listings that include:
- Discipline
- Skill level
- Price
- Duration
- Availability

Only tutors can create or edit their own lesson listings.

## Booking Flow
1. Student selects a lesson listing.
2. Student chooses an available time.
3. Student submits payment.
4. Payment is processed through Paypal.
5. Booking is confirmed.
6. Both users receive confirmation.

## Payment Handling
- Lesson price is set by the tutor.
- A 15% platform service fee is added at booking.
- The student pays the lesson price plus the service fee.
- Payments are processed through PayPal.
- The platform does not store payment information.

## Attendance Verification
- Lessons take place within the platform.
- Tutor and student attendance is tracked.
- Attendance is used to determine refunds and payouts.
- A lesson is considered attended when a user is active in the session for at least 80% of the lesson duration.



## Lesson Completion
- Tutor marks the lesson as completed.
- Payment is released to the tutor after completion.

## Cancellation and Failure Cases

### Tutor Cancellation or No-Show
- The student receives a full refund.
- The tutor is responsible for covering the platform service fee.

### Student Cancellation Before Deadline
- The student receives a full refund.

### Student Cancellation After Deadline
- The student receives a partial refund.
- Refund percentage is determined by platform rules.

### Student No-Show
- If the tutor attended the lesson and the student did not:
  - No refund is issued.

### Dispute Handling
- Attendance records are used to resolve disputes.

## Authorization Rules
- Only tutors can create lesson listings.
- Only the student who booked can cancel the booking.
- Only the tutor who owns the lesson can mark it as completed.

## Notes
- Lesson history is stored for both users.
- PayPal is used as the payment provider for the MVP.

