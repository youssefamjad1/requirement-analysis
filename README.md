# Requirement Analysis in Software Development

This repository is dedicated to the Requirement Analysis phase of a booking management system project.

The primary objective is to document and analyze all necessary requirements—both functional and non-functional—to establish a solid foundation for software development. This includes identifying system actors, drafting use case diagrams, and defining clear acceptance criteria.

By following industry-standard practices, this repository aims to simulate a real-world project scenario and prepare for effective and scalable software design and development.

---

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) that involves gathering, analyzing, and documenting the requirements of a software system. This process ensures a clear understanding between stakeholders, project managers, and developers about what the system is expected to do.

The goal of Requirement Analysis is to identify the exact needs of users and stakeholders and translate them into detailed functional and non-functional requirements that guide the design, development, and testing of the system.

### Importance of Requirement Analysis in SDLC:

- **Clear Communication**: It acts as a bridge between clients and developers by establishing a common understanding of project goals.
- **Risk Reduction**: By identifying problems early, it minimizes the risk of project failure or costly changes later in development.
- **Scope Management**: Clearly defined requirements help control project scope and avoid feature creep.
- **Foundation for Design and Testing**: It serves as a blueprint for software architecture, coding, and quality assurance processes.
- **Customer Satisfaction**: When requirements are well-defined and understood, the final product is more likely to meet user expectations.

---

## Why is Requirement Analysis Important?

Requirement Analysis plays a crucial role in the success of any software project. It ensures that the project goals are clearly understood and provides a strong foundation for design, development, and testing. Here are three key reasons why it’s important:

### 1. Prevents Miscommunication and Errors
Thorough analysis ensures all stakeholders have a shared understanding of the project, reducing miscommunication and minimizing costly errors.

### 2. Ensures Project Alignment with Business Goals
It aligns technical development with business needs, increasing the chances that the final product delivers real value to the users.

### 3. Saves Time and Resources
Identifying problems early prevents rework during development, saving time, money, and effort.

---

## Key Activities in Requirement Analysis

The requirement analysis phase includes several key activities:

- **Requirement Gathering**  
  Collect information from stakeholders, end users, and domain experts to understand what the system should do.

- **Requirement Elicitation**  
  Use techniques like interviews, surveys, brainstorming, and observation to uncover both expressed and hidden needs.

- **Requirement Documentation**  
  Organize and record all collected requirements in a structured format such as user stories, requirement specs, or use cases.

- **Requirement Analysis and Modeling**  
  Analyze requirements for feasibility, consistency, and completeness. Use diagrams and models (e.g., use case diagrams) to visualize interactions and structure.

- **Requirement Validation**  
  Confirm that the documented requirements meet stakeholder expectations and are correct, clear, and testable.

---

## Types of Requirements

Requirements are broadly classified into two types: functional and non-functional.

### Functional Requirements

These define what the system should do. They describe the specific behaviors, features, and functions.

**Examples for a booking management system:**
- Users can create an account and log in.
- Customers can search for available rooms by date and location.
- Users can make and cancel reservations.
- Admin can manage bookings and view reports.

### Non-functional Requirements

These describe how the system should perform. They relate to quality attributes like speed, usability, security, and reliability.

**Examples for a booking management system:**
- The system should handle 1000+ concurrent users.
- Booking confirmation emails must be sent within 1 minute.
- The website must be mobile-responsive.
- All personal data must be encrypted and stored securely.

---

## Use Case Diagrams

Use Case Diagrams are a visual representation of the system’s functionality from the user’s perspective. They illustrate the interactions between actors (users or other systems) and the use cases (services or functions the system performs).

### Benefits of Use Case Diagrams:
- Help visualize the system scope.
- Clarify user interactions and system functionality.
- Serve as a guide for writing detailed functional requirements.

### Booking System Use Case Diagram:

![Use Case Diagram](./alx-booking-uc.png)

---

## Acceptance Criteria

Acceptance Criteria define the conditions that a software product must satisfy to be accepted by stakeholders. They ensure that features are implemented as expected and meet business and user needs.

### Importance:
- Provide a shared understanding of what "done" means.
- Help developers build what users want.
- Act as a reference during testing and validation.

### Example – Checkout Feature Acceptance Criteria:
- The user must be logged in to access the checkout page.
- The system must display a summary of the booking with total cost.
- The user must be able to apply a discount or coupon code.
- Payment must be processed securely and confirmed within 10 seconds.
- A confirmation message and booking details must be emailed to the user upon successful payment.

---

