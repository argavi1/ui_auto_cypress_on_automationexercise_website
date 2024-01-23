# UI Automation with Cypress

Automated UI tests for the AutomationExercise website using Cypress in JavaScript.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/get-npm)

## Installation

```bash
git clone https://github.com/your-username/ui-automation-cypress.git
cd ui-automation-cypress
npm install
Running Tests
bash
Copy code
npm run test
This command will open the Cypress Test Runner, allowing you to run individual test cases or the entire suite.

Test Structure
UI tests are located in cypress/integration.
Custom commands and utilities are defined in cypress/support.
Configuration
Open cypress.json to configure settings such as the base URL.
json
Copy code
{
  "baseUrl": "https://automationexercise.com"
}
Test Cases
Each test file (*.spec.js) focuses on specific UI scenarios.
Test cases cover various functionalities such as navigation, form submissions, and interactions.
Reporting
Cypress generates test reports in the cypress/reports directory by default.
Open the HTML report (mochawesome.html) in a browser for detailed test results.
