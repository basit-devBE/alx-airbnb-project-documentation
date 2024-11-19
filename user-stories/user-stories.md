# Use-Case Story for Airbnb Clone

## Title: Property Booking and Management Platform

### Actors:
1. **Admin**: Responsible for managing property listings and monitoring user activities. 
2. **User**: Customers who browse, book properties, and leave reviews.
3. **System**: Backend system that handles core operations such as authentication, notifications, and payment processing.

---

## Scenario 1: Managing Property Listings

### Actor: Admin
- **Trigger**: Admin logs into the system to manage property listings.
- **Steps**:
  1. Admin authenticates into the platform.
  2. The system verifies the credentials and grants admin access.
  3. Admin navigates to the "Manage Properties" section.
  4. Admin can:
     - Create new property listings by providing details (e.g., location, price, features).
     - Update information on existing properties (e.g., pricing updates, availability).
     - Delete properties no longer available for booking.
  5. The system stores the changes and updates the property catalog visible to users.
- **Outcome**: Property listings are up-to-date, ensuring users only see relevant options.

---

## Scenario 2: Searching and Booking Properties

### Actor: User
- **Trigger**: User visits the platform to book a property.
- **Steps**:
  1. User browses the platform and uses filters (e.g., location, price, property type) to search for properties.
  2. The system displays a list of properties matching the user's criteria.
  3. User selects a property and initiates the booking process.
  4. The system authenticates the user (if not already logged in).
  5. User enters booking details and confirms payment.
  6. The system processes the payment and updates the property's booking status.
  7. The system sends a confirmation email to the user and notifies the admin of the booking.
- **Outcome**: User successfully books a property, and the system updates the records.

---

## Scenario 3: Leaving Reviews

### Actor: User
- **Trigger**: User completes their stay at a property and wants to leave feedback.
- **Steps**:
  1. User logs into the platform and navigates to their booking history.
  2. User selects the property they stayed at and submits a review.
  3. The system stores the review and updates the property’s review section.
  4. Admin receives a notification and can view or respond to the review.
- **Outcome**: Feedback is recorded, helping other users make informed decisions.

---

## Scenario 4: Payment and Notifications

### Actor: System
- **Trigger**: Any action requiring payment or communication (e.g., booking confirmation, admin notifications).
- **Steps**:
  1. During booking, the system validates and processes payment securely.
  2. Once payment is successful:
     - The user receives an email confirmation with booking details.
     - The admin is notified of the new booking.
  3. The system ensures seamless communication by sending notifications to all relevant parties.
- **Outcome**: Payments are processed securely, and all stakeholders are informed.

---

## Conclusion:
This use-case story captures the core interactions within the Airbnb Clone system. It demonstrates how admins, users, and the system collaborate to deliver a seamless property booking experience. By following these steps, the platform ensures efficient property management, booking, and user satisfaction.
