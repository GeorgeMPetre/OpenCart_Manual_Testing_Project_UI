# OpenCart Manual Testing Project (UI)

## About this project

This repository showcases a hands-on manual UI testing project for the OpenCart e-commerce platform. The main focus is on how a real user interacts with the system and whether the core shopping flows behave as expected.

The project was created as a portfolio piece to demonstrate practical QA skills, clear documentation, and structured defect reporting. Industry best practices based on IEEE 829 (2008) were followed, but the goal was always practical testing rather than theory.

---

## What I tested

I focused on the most important customer-facing areas of the store:

* **Registration**
  Creating accounts using valid, invalid, and edge-case inputs

* **Login**
  Authentication flow, validation messages, and failure handling

* **Product browsing**
  Page layout, product listings, navigation, and basic responsiveness

* **Cart management**
  Adding products, updating quantities, and removing items

* **Checkout**
  Address entry, payment selection, and order summary behaviour

* **UI and UX checks**
  Alignment, readability, spacing, and general consistency

---

## How the testing was done

* Manual, black-box testing
* Functional, UI, negative, and boundary scenarios
* Tests executed on a local OpenCart installation
* Browsers used: Chrome, Firefox, and Edge

The emphasis was on realistic user behaviour rather than scripted clicks only.

---

## Test assets in this repo

You will find the following files and folders:

* **OpenCart_Manual_Test_Cases.csv**
  64 detailed test cases with steps, inputs, and expected results

* **OpenCart_Test_Coverage_Summary.csv**
  A simple coverage matrix showing what was tested and where

* **OpenCart_Bug_Report.xlsx**
  Logged defects with severity, priority, and screenshots

* **Screenshots/**
  Visual proof from key test executions

---

## Test results (short version)

| Metric           | Result |
| ---------------- | ------ |
| Total test cases | 64     |
| Passed           | 62     |
| Failed           | 2      |
| Defects raised   | 2      |
| Critical issues  | 0      |

Both failed tests were expected findings from negative and edge-case testing and were fixed after retesting.

---

## Defects found

| ID         | Issue                                                 | Severity | Status |
| ---------- | ----------------------------------------------------- | -------- | ------ |
| BUG-REG-01 | Registration accepts special characters in first name | Minor    | Closed |
| BUG-CHK-02 | Payment method dropdown not loading during checkout   | Major    | Closed |

More details and screenshots are available in **OpenCart_Bug_Report.xlsx**.

---

## Key takeaways

* Input validation on the registration form needs improvement.
* Checkout issues were caused by configuration rather than UI logic.
* The UI is generally consistent across supported browsers.
* All critical shopping flows worked as expected after fixes.

---

## Tools and setup

* OpenCart v4.1.0.3
* Localhost environment using XAMPP
* Chrome, Firefox, Edge
* Test cases and reports maintained in CSV and Excel

---

## How to review this project

If you are reviewing this repo:

1. Start with the test cases to understand coverage
2. Check the bug report to see how issues were documented
3. Review screenshots for execution evidence

---

## Author

**George Petre**
QA Engineer

* GitHub: [https://github.com/GeorgeMPetre](https://github.com/GeorgeMPetre)
* Portfolio: [https://georgempetre.github.io](https://georgempetre.github.io)

---

## Final note

This project reflects how I approach manual testing in real scenarios: understand the user flow, test with intent, document clearly, and report issues in a way that helps teams fix them quickly.
