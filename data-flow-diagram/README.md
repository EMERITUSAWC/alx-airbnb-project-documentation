# Data Flow Diagram – Airbnb Clone Backend

This diagram maps how data travels through the backend system.

## Key Entities
- **User** – provides registration and booking data.
- **Property** – stores listing details.
- **Booking** – manages reservation data.
- **Payment** – records transaction information.

## Core Processes
1. User submits credentials → Auth service validates → User data stored in DB.
2. User searches properties → Server queries DB → Filtered results returned.
3. Booking request → Availability check → Booking saved → Confirmation email sent.
4. Payment request → Stripe validates and charges → Confirmation recorded in DB.

**Diagram:**
