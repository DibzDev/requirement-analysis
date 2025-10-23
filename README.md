
# Requirement Analysis in Software Development

This repository explains the process of **Requirement Analysis**, which is a vital phase in the Software Development Life Cycle (SDLC). It focuses on understanding, documenting, and managing user needs and system requirements to ensure successful software delivery.

## What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, understanding, and documenting the needs and expectations of stakeholders for a new or modified software system.  
It acts as a foundation for all future stages of development from design to deployment.

In the **Software Development Life Cycle (SDLC)**, this stage ensures that developers and stakeholders share a clear understanding of what needs to be built. Poorly defined requirements often lead to project delays, cost overruns, and software that fails to meet user expectations.

## Why is Requirement Analysis Important?

Requirement Analysis is crucial because it:

1. **Prevents Miscommunication:** It ensures that developers, clients, and other stakeholders share a common understanding of the system’s goals.
2. **Reduces Rework and Costs:** Clearly defined requirements reduce errors and unnecessary changes during later development stages.
3. **Improves Project Planning:** Accurate requirements help in estimating project scope, budget, and timelines effectively.

## Key Activities in Requirement Analysis

The main activities include:

- **Requirement Gathering:** Collecting needs from stakeholders through interviews, questionnaires, or observation.
- **Requirement Elicitation:** Clarifying and refining gathered information to understand what users truly need.
- **Requirement Documentation:** Writing a clear, structured document that describes system requirements.
- **Requirement Analysis and Modeling:** Analyzing relationships, priorities, and feasibility; often represented using diagrams and models.
- **Requirement Validation:** Ensuring all documented requirements align with business goals and stakeholder expectations.

## Types of Requirements

### 1. Functional Requirements
These define **what the system should do** the specific features and functions.

**Examples for the Booking Management Project:**
- Users can create an account and log in.
- Users can search for available rooms or services.
- Users can make, modify, or cancel bookings.
- The system sends booking confirmation emails to users.

### 2. Non-Functional Requirements
These define **how the system performs** focusing on quality attributes like speed, security, or usability.

**Examples for the Booking Management Project:**
- The system should respond to user actions within 2 seconds.
- The system should support up to 10,000 concurrent users.
- All customer data must be encrypted during transmission.
- The interface should be mobile-friendly and easy to use.

## Use Case Diagrams

A **Use Case Diagram** visually represents the interactions between users (actors) and the system.  
It helps stakeholders understand system functionality from a user’s perspective.

### Benefits:
- Clarifies system scope and user roles.
- Helps identify primary use cases early.
- Improves communication between business and technical teams.

### Booking Management System – Use Case Diagram

Below is the use case diagram for the booking system, showing the main actors and use cases:

<img width="802" height="762" alt="alx-booking-uc" src="https://github.com/user-attachments/assets/5c49473e-73f0-462d-ace2-1bd3fd365c52" />

## Acceptance Criteria

**Acceptance Criteria** are predefined conditions that a software feature must meet to be accepted by the client or user.  
They ensure that the delivered feature aligns with expectations and business requirements.

### Importance:
- Clarifies what “done” means for each feature.
- Reduces ambiguity between developers and clients.
- Acts as a checklist during testing and validation.

### Example: Checkout Feature (Booking Management System)
**Acceptance Criteria:**
1. User must be logged in to access the checkout page.
2. The system displays a summary of the selected booking details.
3. User can select a payment method (e.g., credit card, M-Pesa).
4. Payment must be processed successfully before confirmation.
5. A confirmation message and receipt email are sent after payment.
