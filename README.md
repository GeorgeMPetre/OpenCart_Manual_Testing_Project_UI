OpenCart Manual Testing Project (UI)
Project Overview

The OpenCart Manual Testing Project (UI) focuses on verifying the user interface, usability, and key functional workflows of the OpenCart e-commerce application.
All tests were designed and executed following the IEEE 829 (2008) standard to ensure consistency, traceability, and completeness across the testing lifecycle.


Objectives

Validate that the OpenCart UI meets functional and usability expectations.

Confirm the correct behavior of core customer-facing workflows (registration, login, cart, and checkout).

Detect and document UI layout inconsistencies and validation issues.

Provide complete traceability between test cases, coverage, and defect reports.


Scope of Testing
Module	Description:
Registration	Validate account creation with positive, negative, and boundary inputs.
Login	Verify authentication and error message accuracy.
Product Browsing	Check layout, product listing, and page responsiveness.
Cart Management	Ensure add/remove/update quantity functionality works correctly.
Checkout Process	Validate address entry, payment selection, and order summary.
UI & UX Validation	Verify design alignment, readability, and element positioning.


Project Deliverables
Artifact	Description:
OpenCart__Manual_Test_Cases.csv	All 64 test cases with steps, inputs, expected/actual results, and status.
OpenCart_Test_Coverage_Summary.csv	Module-wise coverage matrix linking requirements to test cases.
OpenCart_Bug_Report.xlsx	Detailed defect log including severity, priority, and screenshots.
Screenshots	Visual evidence of registration and checkout tests executed successfully.


Test Design & Execution

Testing Approach: Black-box

Documentation Standard: IEEE 829 (2008)

Test Types: Functional, UI, Negative, Boundary, Regression

Environment: Localhost (XAMPP), OpenCart v4.1.0.3

Entry Criteria: Application deployed, test data prepared

Exit Criteria: All high-priority modules executed, results recorded

Test Execution Summary:
Metric	Result
Total Test Cases	64
Passed	62
Failed	2
Defects Logged	2
Critical Defects	0
Closed Defects	2 (after retest)

Defects Summary:
ID	Title	Severity	Status
BUG-REG-01	Registration form accepts special characters in the first-name field	Minor	Closed
BUG-CHK-02	Payment method dropdown not loading on checkout page	Major	Closed

(Full details available in OpenCart_Bug_Report.xlsx.)


Test Evidence
Screenshot	Description
	Registration with special characters accepted — defect confirmed
	Checkout process after editing cart quantity — defect confirmed

  
Observations

The registration form lacks input sanitization for special characters.

The payment dropdown intermittently failed to load until configuration was updated.

UI alignment and responsiveness are consistent across major browsers.

All critical workflows (register, login, cart, checkout) passed after retest.


Tools & Environment
Category	Tool / Environment
Testing Type	Manual (UI / Functional)
Documentation Tools	Excel, CSV Templates
Application Version	OpenCart v4.1.0.3
Execution Environment	Localhost via XAMPP
Defect Tracking	Excel Bug Report
Evidence	Screenshots attached per module


Author

George Petre
Sturry, CT2 0HN, UK
george.petre23@gmail.com

georgempetre.github.io

This project demonstrates complete manual test design, execution, and reporting for the OpenCart UI — verifying functional workflows, detecting UI defects, and documenting results using IEEE 829 best practices.
