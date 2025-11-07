# ParaBank Epics, User Stories, and Acceptance Criteria

## Epic: Authentication

### PBANK-JAVA-101 – Valid Login
- Story: As a user, I want to log in with correct credentials
- Acceptance: Redirects to Accounts Overview

### PBANK-JAVA-102 – Invalid Login
- Story: As a user, I want to be notified when login fails
- Acceptance: Error message displayed

### PBANK-JAVA-103 – Logout
- Story: As a user, I want to log out securely
- Acceptance: Session cleared and redirected to login

---

## Epic: Account Overview

### PBANK-JAVA-201 – View Account Summary
- Story: As a user, I want to view my account number and balance
- Acceptance: Account list and balance displayed

### PBANK-JAVA-202 – View Transaction History
- Story: As a user, I want to see recent transactions
- Acceptance: Transaction table visible

---

## Epic: Fund Transfer

### PBANK-JAVA-301 – Valid Transfer
- Story: As a user, I want to transfer funds between accounts
- Acceptance: Confirmation message shown

### PBANK-JAVA-302 – Invalid Amount
- Story: As a user, I want to be blocked from transferring invalid amounts
- Acceptance: Validation error displayed

### PBANK-JAVA-303 – Empty Form Submission
- Story: As a user, I want to be notified when required fields are missing
- Acceptance: Form blocked and error shown

---

## Epic: Bill Payment

### PBANK-JAVA-401 – Valid Bill Pay
- Story: As a user, I want to pay bills with correct info
- Acceptance: Success message displayed

### PBANK-JAVA-402 – Missing Fields
- Story: As a user, I want to see validation errors for empty fields
- Acceptance: Error messages shown

---

## Epic: Profile Management

### PBANK-JAVA-501 – Update Contact Info
- Story: As a user, I want to update my address and phone
- Acceptance: Profile updated confirmation

---

## Epic: Loan Request

### PBANK-JAVA-601 – Valid Loan Request
- Story: As a user, I want to request a loan with valid details
- Acceptance: Loan status shown as approved

### PBANK-JAVA-602 – Invalid Loan Inputs
- Story: As a user, I want to be warned about invalid loan amounts
- Acceptance: Validation error displayed

---

## Epic: Negative Scenarios

### PBANK-JAVA-701 – Session Expiry
- Story: As a user, I want to be redirected to login after timeout
- Acceptance: Access blocked and redirected

### PBANK-JAVA-702 – Unauthorized Access
- Story: As a user, I want to be blocked from accessing pages without login
- Acceptance: Login prompt shown
