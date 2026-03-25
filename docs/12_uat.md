# User Acceptance Testing (UAT)

## 📌 Overview

UAT ensures that the system meets business requirements and works as expected before production release.

---

## 🎯 Objective

* Validate functional requirements
* Ensure system behavior matches business expectations
* Identify defects before release

---

## 🧪 Test Scenarios

### TS-1: Successful Payment

**Input:** Valid payment details
**Expected Result:** Payment successful, order confirmed
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

### TS-2: Payment Failure (Recoverable)

**Input:** Temporary failure (e.g., network timeout)
**Expected Result:** Retry option enabled
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

### TS-3: Payment Failure (Non-Recoverable)

**Input:** Invalid card details
**Expected Result:** No retry allowed, clear error message
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

### TS-4: Retry Logic

**Input:** Retry after failure
**Expected Result:** Retry allowed only for valid scenarios
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

### TS-5: Order Blocking

**Input:** Payment failure
**Expected Result:** Order should not remain blocked indefinitely
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

### TS-6: Data Validation

**Input:** Missing transaction fields
**Expected Result:** System should reject invalid data
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

### TS-7: Reconciliation Check

**Input:** Transaction vs settlement data
**Expected Result:** Values should match
**Actual Result:** [To be filled]
**Status:** Pass/Fail

---

## 🐞 Defect Tracking (Example)

| Defect ID | Description                      | Severity | Status      |
| --------- | -------------------------------- | -------- | ----------- |
| D1        | Retry allowed for invalid card   | High     | Open        |
| D2        | Order not released after failure | Medium   | In Progress |

---

## 🧠 My Role in UAT

* Defined test scenarios based on requirements
* Validated business logic
* Coordinated with QA and stakeholders
* Identified gaps and tracked defects

---

## 📊 Outcome

* Ensured system meets business expectations
* Reduced production issues
* Improved reliability of payment processing
