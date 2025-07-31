# Cross - skilling 

This repository is part of my personal learning journey as I focus on cross-skilling in automation tools. It was inspired by the QE-led Cross-Skilling initiative and serves as a structured space for me to explore, practice, and deepen my understanding of Playwright.

Here, I’ll be working through various test scenarios and practice exercises as I move through different focus areas and gradually building confidence and expertise in using Playwright. This repository will grow and evolve over time, reflecting both my progress and the skills I’m developing along the way.


##  Setting Up Playwright and Running Tests

This section outlines how to install Playwright, set up the environment, and run tests in various modes.

### Step 1: Install Playwright and Dependencies

Use the official Playwright initializer to quickly set up your project:

```bash
npm init playwright@latest
```
### Step 2 :Running the test 

| Mode              | Command                                     | Description                                                 |
| ----------------- | ------------------------------------------- | ----------------------------------------------------------- |
| **Default**       | `npx playwright test`                       | Runs all test files in the project                          |
| **Specific file** | `npx playwright test tests/example.spec.js` | Runs a single test file                                     |
| **UI mode**       | `npx playwright test --ui`                  | Launches a test runner UI to visually explore and run tests |
| **With report**   | `npx playwright show-report`                | Opens an HTML report after tests complete                   |
| **With debug**    | `PWDEBUG=1 npx playwright test`             | Runs tests in debug mode with step-by-step control          |
| **Headed mode**   | `npx playwright test --headed`              | Runs tests in a visible browser window (not headless)       |




