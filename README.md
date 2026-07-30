# Day 3 - Salesforce Flow Builder

## Topics Learned

### 1.Validation Rules
Created a validation rule on the Member object.
Restricted users from creating members whose age is below 18 years.

Displayed the error message:

"Member age must be 18 years or above."

### 2. Before-Save Record-Triggered Flow
- Triggered when a new Member record is created.
- Automatically sets the Registration Date to the current date.

### 3. After-Save Record-Triggered Flow
- Automatically creates a Membership Details record.
- Copies Member, Membership Plan, and Trainer.
- Sets Status as Active.
- Sets Start Date as Current Date.
- Sets End Date as Current Date + 365 Days.

### 4. Flow Debugging
- Learned how to debug Record-Triggered Flows.
- Verified that records are ready to be created during flow execution.

## Outcome
Successfully learned Validation Rules, Before-Save Flow, After-Save Flow, Flow Debugging, and automation using Salesforce Flow Builder.
