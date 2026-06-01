# Blaze Diagnostics App: Initial User Stories

## Epic 1: Authentication and User Access

### User Story: User Login

As a workshop user, I want to log in securely so that I can access the correct dashboard.

Acceptance criteria:

- User can enter email and password.
- Invalid login shows a clear error.
- Valid login redirects to the correct dashboard.
- Passwords are not stored in plain text.

### User Story: Role-Based Access

As a workshop owner, I want users to have different roles so that staff only access the areas they need.

Roles:

- Workshop Admin
- Service Advisor
- Mechanic
- Customer
- System Admin

## Epic 2: Customer and Vehicle Management

### User Story: Create Customer Profile

As a service advisor, I want to create customer profiles so that vehicles and jobs can be linked to the correct clients.

### User Story: Add Vehicle

As a service advisor, I want to add a customer's vehicle so that repair jobs can be tracked against the correct vehicle.

## Epic 3: Job Card Management

### User Story: Create Job Card

As a service advisor, I want to create a job card for a vehicle so that work can be tracked from booking to completion.

Suggested statuses:

- Booked In
- Inspection Started
- Quote Required
- Awaiting Quote Approval
- Quote Approved
- Parts Ordered
- Awaiting Parts
- Parts Received
- In Progress
- Quality Check
- Ready for Collection
- Completed
- Cancelled

### User Story: Update Job Status

As a mechanic or service advisor, I want to update the job status so that the customer knows what is happening with the vehicle.

## Epic 4: Quote Management

### User Story: Create Quote

As a service advisor, I want to create a quote for a job so that the customer can review costs before work continues.

### User Story: Approve or Reject Quote

As a customer, I want to approve or reject a quote so that the workshop knows whether to continue.

## Epic 5: Parts and Progress Updates

### User Story: Add Parts to Job

As a service advisor, I want to add required parts to a job so that the workshop and customer can track what is needed.

### User Story: Mechanic Progress Updates

As a mechanic, I want to update the work progress on a vehicle so that the service advisor and customer know what stage the job is in.

## Epic 6: Customer Tracking Page

### User Story: View Job Progress

As a customer, I want to view the progress of my vehicle so that I do not need to keep phoning the workshop for updates.

## Epic 7: Notifications and Invoicing

### User Story: Send Customer Updates

As a workshop, I want customers to receive updates when important job events happen so that communication is improved.

### User Story: Generate Invoice

As a service advisor, I want to generate an invoice from an approved quote so that the customer can be billed accurately.

## Epic 8: Security and Audit Trail

### User Story: Track Important Changes

As a workshop admin, I want important changes to be logged so that there is accountability in the system.

### User Story: Protect Customer and Workshop Data

As a workshop owner, I want customer and workshop data to be protected so that private information is not exposed.
