# Spendwise

Spendwise is a personal expense tracker that makes a monthly plan easier to understand without requiring a bank connection. Enter a monthly take-home salary, set category limits, and add income or expense transactions. The overview calculates what remains and a weekly spending pace from your entries.

## Preview

Open the `expense-tracker` folder in Visual Studio Code and launch `index.html` with the Live Server extension. No build step or package installation is required. The page starts blank so you can enter your own numbers.

## Features

- Edit a separate monthly salary plan and category limits for each month
- Create, edit, and delete income and expense transactions
- Monthly income, spending, remaining balance, and weekly pace summaries
- Category breakdown and progress against your own budget limits
- Search and category filtering for transactions
- CSV export for the selected month's transactions
- Browser `localStorage` persistence with a clear data option
- Responsive layout for desktop and mobile

## Privacy and scope

Your salary, budgets, and transactions are stored in the current browser's local storage. The app does not connect to a bank or send financial data to a server. Export the selected month's transactions as CSV if you want a separate backup. This is a personal tracking tool, not financial advice.

## Files

```text
expense-tracker/
├── index.html
├── styles.css
├── app.js
└── README.md
```
