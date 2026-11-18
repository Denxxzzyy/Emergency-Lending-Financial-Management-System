# Emergency Lending Financial Management Demo

Presentation-ready static prototype for the accepted study title **Web-Based Loan and Financial Management System for an Emergency Lending Corporation**.

## Run locally

No installation or database is required.

1. Open the `dist` folder.
2. Double-click `index.html`.
3. Choose Manager, Borrower, or Financier on the demo login screen.

On Windows, you can also double-click `OPEN_DEMO.cmd` from the project folder.

## Open in Visual Studio Code

Open the complete project folder, not only the `dist` folder. The included `.vscode/settings.json` configures the common Live Server extension to serve `dist` on port 5500. Live Server is optional; `OPEN_DEMO.cmd` works without an extension.

For the most reliable browser behavior, serve the `dist` folder with any local static web server. Example with PHP:

```text
php -S localhost:8080 -t dist
```

Then open `http://localhost:8080`.

## Suggested 6-minute demo

1. Enter as **Manager** and review the dashboard.
2. Open **Collections** and generate a payment link.
3. Choose **Simulate GCash confirmation** to add a verified payment. No real payment occurs.
4. Show **Financier agreements**, **Manager advances**, and **Expenses**.
5. Open **Reports** and use **Print report**.
6. Switch roles through the profile button and demonstrate borrower and financier data isolation.
7. Finish on **Scope notes** to explain assumptions, exclusions, and the Study 3 citation mismatch.

## Important boundaries

- All people, amounts, terms, references, and transactions are fictional Philippine peso demo data.
- Payment links and GCash confirmation are simulated; there is no payment-provider connection.
- The prototype does not approve loans, certify audits, guarantee returns, or claim BIR compliance.
- Interest, penalty, payout, and reimbursement rules are assumptions pending the manager interview.
- Data changes live only in the current browser session and reset after refresh.

## Files

- `dist/index.html` — application shell
- `dist/styles.css` — responsive presentation styling
- `dist/app.js` — demo data and interactions
- `.openai/hosting.json` — private Sites deployment configuration
