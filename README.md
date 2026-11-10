# Fieldwork

A small fictional course enrollment website for a QA interview exercise.

## Run

Open `index.html` in a modern browser. No installation, build, or backend is required.

Read the candidate brief below for the exercise and expected behavior. Use **Reset demo** before each interview. Browser-local storage retains the enrollment cart across refreshes.

Use invented learner details. This demo makes no payments, sends no emails, and creates no real enrollments.

The interviewer answer key is maintained separately and is deliberately excluded from this repository.

---

# Fieldwork — candidate exercise

## Your task
Test a fictional course-enrollment website for 25–35 minutes. Use invented learner details. No real payments, accounts, or enrollments occur.

Explore course search, categories, sorting, enrollment cart, seat quantities, discounts, and checkout. Report issues with a title, reproduction steps, expected and actual results, severity, and a screenshot if helpful. Prioritize your top three issues and explain what you would test next. Finding every issue is not required.

Expected behavior:
- Search matches course titles regardless of letter case.
- Category filters include all matching courses. Price sorting is numeric.
- Courses marked “Cohort full” cannot be added or booked.
- Each cart line represents seats on that course; quantities must be whole numbers from 1 to 99.
- Removing a course removes only the selected course.
- Subtotal equals the sum of course price × seats.
- WELCOME10 applies 10% off the merchandise/course subtotal once.
- A $5 booking fee applies to nonempty carts, waived at a subtotal of $75 or more before discount.
- Checkout requires a learner name and a valid email address. No payment details are needed for this demo.
- Cart state survives refresh. Reset demo clears the cart, coupon and confirmation.



