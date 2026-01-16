# OpenCart Manual Testing Project (UI)

This repository contains a manual UI testing project for the OpenCart e-commerce application. I created it as part of my QA portfolio to show how I approach testing from a user point of view, how I document my work, and how I report issues clearly.

The focus of the testing was on the main customer journeys. I wanted to see if a normal user can register, log in, browse products, add items to the cart, and complete checkout without issues. I tested both happy paths and negative scenarios, not just what is supposed to work but also what could break.

I tested the registration flow using valid data, invalid inputs, and edge cases. One issue I found was that the first-name field accepted special characters, which showed missing input validation. This was logged as a defect and later closed after retesting.

Login testing covered correct and incorrect credentials, error messages, and basic session behaviour. Product browsing focused on layout consistency, navigation, and whether product information was displayed correctly across pages.

Cart testing included adding products, changing quantities, and removing items. During checkout testing, I verified address input, payment selection, and order summary behaviour. I found an issue where the payment method dropdown did not load due to missing configuration. This was logged as a major defect and closed after the setup was fixed.

In total, I executed 64 manual UI test cases. Most of them passed on the first run. Two tests failed initially, both coming from negative or edge-case scenarios. No critical issues were found, and all core shopping flows worked correctly after fixes and retesting.

All test cases are documented in xlsx format, with clear steps, inputs, and expected results. Test coverage is tracked in a separate file, and all defects are logged in an Excel bug report with screenshots as evidence. These files are included in this repository so the full testing process is transparent.

Testing was done manually using a local OpenCart installation running on XAMPP. I used Chrome, Firefox, and Edge to check basic cross-browser behaviour. The goal was not automation, but understanding the system and user experience through hands-on testing.

This project reflects how I work as a QA engineer: start from the user flow, test with intent, pay attention to details, and document findings in a way that helps others understand and fix issues.

Author: George Petre
GitHub: [https://github.com/GeorgeMPetre](https://github.com/GeorgeMPetre)
Portfolio: [https://georgempetre.github.io](https://georgempetre.github.io)
