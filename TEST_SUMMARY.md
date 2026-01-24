# Test Summary — OpenCart Manual UI Testing

## What was tested

Manual UI tests focused on the core user journey in OpenCart:

- Registration
- Login
- Product browsing
- Cart operations
- Checkout

Cross-browser UI behaviour was validated.

## Execution results

- Total manual test cases executed: 66
- Passed: 64
- Failed: 2
- Blocked: 0 
- Browsers: Chrome, Firefox, Edge  
- Major observations:
  - Registration accepted special characters in first-name field.
  - Payment method dropdown did not load initially.
- Most tests passed as expected.

## Environment

- Local OpenCart site (XAMPP)
- Browsers: Chrome, Firefox, Edge

## Defects logged

See `bug_reports/` for all defect details with steps and evidence.

## Conclusion

The main customer journeys work reliably. A small number of edge-case issues were identified and documented. Most flows passed after retesting once defects were resolved.
