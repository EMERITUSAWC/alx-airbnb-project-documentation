# System Flowchart – Booking Process

This flowchart represents the backend logic for a complete booking workflow.

## Steps
1. User logs in.
2. User selects property and desired dates.
3. Backend checks availability.
4. If available → proceed to payment.
5. Payment processed via Stripe.
6. On success → booking stored and confirmation sent.
7. On failure → error message returned.

**Diagram:**