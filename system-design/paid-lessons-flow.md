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
- A platform service fee equal to 15% of the lesson price is added at booking, with a maximum fee cap of $5.
- The student pays the lesson price plus the service fee.
- Payments are processed through PayPal.
- The platform does not store payment information.

## Attendance Verification
- Lessons take place within the platform.
- Tutor and student attendance is tracked independently.
- Attendance is used to determine refunds and payouts.
- A lesson is considered attended for each user if that user is active in the session for at least 80% of the lesson duration.

## Lesson Completion
- Lesson completion is determined automatically by the system based on attendance verification rules.
- Payment is released to the tutor if the lesson is completed according to attendance verification rules.
- Tutors are paid for lessons they attended, even if the student did not attend without cancelling.
- If the student cancels or the tutor does not attend, payment follows the cancellation and failure rules.

## Ratings and Reputation

### Rating Eligibility
- Tutors and students can rate each other only after a lesson is completed.
- Ratings are not allowed for cancelled or incomplete lessons.

### System Reputation Signals
- The platform tracks behavior patterns independently of user ratings.
- Repeated late cancellations or no-shows by students negatively impact student reputation.
- Repeated tutor cancellations or no-shows negatively impact tutor reputation.
- These impacts are applied automatically by the system and are visible on user profiles.

### Rating Purpose
- Ratings reflect the quality of a completed lesson from each user's perspective.
- System reputation signals reflect objective behavioral reliability.
  
### Reputation Impact
- Ratings contribute to a user's overall reputation.
- Reputation may be used to surface trustworthy users and reduce disputes.

### Note
- Ratings represent direct interaction quality, while system reputation signals represent behavioral reliability.


## Cancellation and Failure Cases

### Tutor Cancellation or No-Show
- The student receives a full refund.
- The tutor is responsible for covering the platform service fee.

### Student Cancellation Before Deadline
- The student receives a full refund.

### Student Cancellation After Deadline
- The student receives a 50% refund.
- The 50% refund applies only to the lesson price, not the service fee.

### Student No-Show
- If the tutor attended the lesson and the student did not, the tutor is still paid.
- No refund is issued for the lesson price.

### Student and Tutor No-Show
- If both the tutor and the student fail to attend a scheduled lesson, the tutor will not be paid.  
- The student will receive platform credit, which can be used to discount future lessons or enroll in paid championships.  
- No real money refund will be issued.  
- These actions are applied automatically by the system.

### Dispute Handling
- Attendance records are used to resolve disputes.

## Authorization Rules
- Only tutors can create lesson listings.
- Only the student who booked can cancel the booking.
- Lesson completion status is determined automatically by the system based on attendance rules.

## Notes
- Lesson history is stored for both users, including completed, cancelled, and no-show lessons.
- PayPal is used as the payment provider for the MVP.

