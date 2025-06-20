### Backend Setup (Project name: cypress_stripe_testing)

This project is an automated testing suite using **Cypress**, designed to test **Stripe PaymentIntent** endpoints through direct API calls.

🛠️ Tech Stack
- Cypress (E2E Testing Framework)
- Node.js & NPM
- Stripe API (Test Mode)
- JavaScript (test scripting)

🚀 Getting Started

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/cypress_stripe_testing.git
   cd cypress_stripe_testing
   ```
2. Extract cypress.zip (I zipped the file to safeguard my Stripe API key, as Git’s security features prevent pushing sensitive information like API keys to the repository).
3. Install dependencies (using below command)
   ```sh
    npm install
   ```
4. Open Cypress Test runner
    ```sh
   npx cypress open
   ```
5. Choose E2E Testing and select any browser (e.g., Chrome, Edge, Firefox)

6. Inside the Cypress test runner, locate and click on: **payment_intent.cy.js**
