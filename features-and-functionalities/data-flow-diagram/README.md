# Data Flow Diagram – Airbnb Clone Backend

This directory contains the **Data Flow Diagram (DFD)** for the Airbnb Clone backend.  
The diagram illustrates how data moves between users, the backend system, and external services such as payment gateways.

---

## Key Components
1. **Users (Guests & Hosts)**
   - Provide input through registration, login, property listing, booking requests, and payments.

2. **Backend System**
   - Handles user authentication, property management, booking management, and notifications.
   - Validates input and applies business logic.

3. **Database**
   - Stores users, properties, bookings, reviews, and transactions.

4. **Payment Gateway (e.g., Stripe/PayPal)**
   - Processes secure payment transactions.
   - Sends confirmation of successful or failed payments.

---

## Workflow Summary
- A guest signs up or logs in → request goes to backend → validated and stored in **User DB**.  
- Host creates a property → backend saves it in **Property DB**.  
- Guest searches and makes a booking → backend checks **Property Availability DB** → booking stored in **Booking DB**.  
- Guest proceeds to payment → backend interacts with **Payment Gateway** → booking status updated.  
- Notifications are triggered for confirmations, cancellations, or updates.

---

## File Export
- **data-flow.png**: The DFD created using Draw.io and exported as a PNG.  
