# QA Case Study – Reservation & Payment Flow Validation

## Overview
This case study demonstrates structured end-to-end validation of a reservation platform including payment gateway integration, reward logic, and administrative workflows.

The focus of this validation was financial accuracy, state consistency, and cross-module synchronization.

---

## Scope Covered

- Reservation creation (Admin & User side)
- Payment gateway integration validation (Niubiz simulation)
- Reward logic validation (70% rule enforcement)
- Multi-reservation scenarios
- Partial payments & cancellation flows
- Concurrency validation
- Room status synchronization
- UI/UX edge case validation
- Session persistence during payment interruptions

---

## Testing Approach

- Structured test case design
- Boundary Value Analysis (reward limits)
- Negative testing
- Cross-module state validation
- Severity & priority classification
- Regression validation per module

---

## Key Findings

- Critical synchronization issue between payment confirmation and room status update.
- Session persistence flaw during payment interruption.
- Context loss during partial payment attempts.
- UI inconsistency in responsive layouts.
- Payment flow instability when reward modal refreshes unexpectedly.

---

## Impact

The identified issues affected financial integrity, booking reliability, and user experience.

This case study reflects real-world QA analysis involving payment logic validation, business rule enforcement, and defect prioritization in a production-level environment.

## 📄 QA Case Study – Payment & Reservation Flow

This document includes:

- End-to-end test scenarios
- Critical bug analysis
- Payment gateway validation (Niubiz)
- Rewards logic validation (70% rule)
- Concurrency and multi-reservation scenarios
- UI and business logic findings

👉 Download the full case study here:
[Mauricio_Carrasquel_QA_Case_Study_Payment_Reservation_Flow.pdf](./Mauricio_Carrasquel_QA_Case_Study_Payment_Reservation_Flow.pdf)
