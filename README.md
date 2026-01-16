# OpenCart Manual Testing Project (UI)

## Project Overview

This repository contains a manual UI testing project for the OpenCart e-commerce application. The goal is to validate usability, visual consistency, and core customer workflows such as registration, login, cart, and checkout.

All tests were designed and executed using structured QA practices aligned with the IEEE 829 (2008) standard, with clear traceability between test cases, coverage, and defects.

---

## What Was Tested

The following customer-facing modules were covered:

* **Registration**

  * Positive, negative, and boundary input validation
* **Login**

  * Authentication behaviour and error messages
* **Product Browsing**

  * Layout consistency, product listing, navigation
* **Cart Management**

  * Add, remove, and update quantity actions
* **Checkout Process**

  * Address entry, payment selection, order summary
* **UI & UX Validation**

  * Alignment, readability, responsiveness

---

## Test Approach

* **Testing type:** Manual UI / Functional
* **Method:** Black-box testing
* **Test types:** Functional, UI, Negative, Boundary, Regression
* **Documentation standard:** IEEE 829 (2008)

Tests were executed against a local OpenCart deployment with predefined test data.

---

## Test Artifacts

This repository includes:

* **OpenCart_Manual_Test_Cases.csv**

  * 64 detailed test cases with steps, inputs, expected and actual results
* **OpenCart_Test_Coverage_Summary.csv**

  * Module-level coverage and traceability
* **OpenCart_Bug_Report.xlsx**

  * Logged defects with severity, priority, and evidence
* **Screenshots/**

  * Visual proof of executed test scenarios

---

## Test Execution Summary

| Metric                        | Result |
| ----------------------------- | ------ |
| Total test cases              | 64     |
| Passed                        | 62     |
| Failed                        | 2      |
| Defects logged                | 2      |
| Critical defects              | 0      |
| Closed defects (after retest) | 2      |

---

## Defects Overview

| ID         | Title                                                 | Severity | Status |
| ---------- | ----------------------------------------------------- | -------- | ------ |
| BUG-REG-01 | Registration accepts special characters in first name | Minor    | Closed |
| BUG-CHK-02 | Payment method dropdown not loading during checkout   | Major    | Closed |

Full details are available in `OpenCart_Bug_Report.xlsx`.

---

## Key Observations

* Registration form lacks proper input sanitisation for special characters.
* Checkout payment dropdown failed due to configuration, not UI logic.
* UI alignment and responsiveness are consistent across major browsers.
* All core workflows passed after fixes and retesting.

---

## Tools and Environment

* **Application:** OpenCart v4.1.0.3
* **Execution environment:** Localhost (XAMPP)
* **Browsers:** Chrome, Firefox, Edge
* **Test documentation:** Excel and CSV templates
* **Defect tracking:** Excel-based bug report
* **Evidence:** Screenshots per module

---

## How to Use This Repository

1. Review the test cases in `OpenCart_Manual_Test_Cases.csv`
2. Check coverage in `OpenCart_Test_Coverage_Summary.csv`
3. Inspect logged defects in `OpenCart_Bug_Report.xlsx`
4. Review screenshots for execution evidence

---

## Author

**George Petre**
QA Engineer

* GitHub: [https://github.com/GeorgeMPetre](https://github.com/GeorgeMPetre)
* Portfolio: [https://georgempetre.github.io](https://georgempetre.github.io)

---

## Notes

This project demonstrates end-to-end manual UI test design, execution, defect reporting, and traceability for a real-world e-commerce application. It is intended as a portfolio and learning project rather than a production release.
