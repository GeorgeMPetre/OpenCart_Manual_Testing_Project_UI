# Test Plan — OpenCart Manual UI Testing

## 1. Objective

Define how manual UI testing was planned and executed for key customer flows in the OpenCart web app.

## 2. Scope

### In scope
- Registration  
- Login & logout  
- Product browsing  
- Cart add/change/remove  
- Checkout with address and payment  
- Cross-browser UI behaviour (Chrome, Firefox, Edge)

### Out of scope
- Test automation  
- Backend API testing  
- Third-party integrations

## 3. Test strategy

- Design detailed manual test cases per feature
- Execute step by step with expected results
- Log observations and defects where behaviour differs
- Track both positive (expected) and negative (failure) cases

## 4. Environment

- Local OpenCart installation on XAMPP  
- Browsers: Chrome, Firefox, Edge

## 5. Entry criteria

- OpenCart instance running
- Test cases prepared in `test_cases/`
- Defect reporting mechanism ready

## 6. Exit criteria

- All planned test cases are executed
- Defects logged and documented
- Summary of results prepared

## 7. Deliverables

- Manual test cases
- Bug report logs
- Test summary

8. Risks and mitigations

- Local environment differs from production
- Results may not fully reflect real user behaviour.
- Mitigation: Clearly document environment limits and treat findings as functional validation, not production benchmarks.

- Browser-specific UI differences
- Layout or behaviour may vary across browsers.
- Mitigation: Execute the same scenarios on Chrome, Firefox, and Edge and record any inconsistencies separately.
