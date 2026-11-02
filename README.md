# PocketWise — Student Expense Tracker

A responsive student expense tracker with a light green dashboard and INR currency support.

## Features
- Add, edit and delete expenses
- Monthly category budgets and remaining-budget calculations
- Daily spending chart and category breakdown
- Search, filtering, sorting and spending insights
- CSV export
- Clearly labelled sample data with a cleanup action
- Browser-local saving across refreshes

## Run locally
No npm installation is required. Serve the `dist` folder using a static web server, for example:

```sh
python -m http.server 8000 --directory dist
```

Then open http://localhost:8000.

## Project files
- `dist/index.html` — page structure and dialogs
- `dist/style.css` — responsive styling
- `dist/app.js` — expense tracking, budgets, charts and CSV export
- `.openai/hosting.json` — existing Sites hosting configuration

## Data storage
Expense records and budgets are saved in the current browser's localStorage. They are not uploaded to GitHub and do not synchronize between devices. Clearing browser storage removes those records. Export CSV to keep a copy.

## Existing website
https://student-pocket-expenses.singh-01-nidhi11.chatgpt.site
