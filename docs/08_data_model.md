# Data Model (High-Level)

## 📌 Overview

The payment system requires structured data to track transactions, failures, and settlements accurately.

---

## 🔑 Key Entities

### 1. Payments

* transaction_id
* order_id
* payment_status
* amount
* failure_reason
* retry_flag

### 2. Orders

* order_id
* order_status
* user_id

### 3. Settlements

* settlement_id
* transaction_id
* settlement_amount

---

## 🔗 Relationships

* One Order → One Payment
* One Payment → One Settlement

---

## 🧠 Why This Matters

* Enables reconciliation
* Ensures traceability
* Supports reporting and analytics
