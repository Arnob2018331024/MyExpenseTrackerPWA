# MyExpenseTrackerPWA

A simple, mobile-first Progressive Web App for tracking family expenses.

MyExpenseTrackerPWA provides a minimal, privacy-first way to log and review household spending. Data is stored locally in your browser (localStorage), so nothing leaves your device unless you export it as CSV.

Created with Vibe Coding.

## Features

- Dashboard showing the current month's total and recent entries
- Add, edit and delete expense entries (amount, category, date)
- History view grouped by month with per-month totals
- Export and import data as CSV
- Clear all data (danger zone)
- Responsive layout with a native-style bottom navigation bar
- Offline-capable as a simple PWA (manifest included)

## How it works

- The app is a single static HTML file (index.html) using plain JavaScript and CSS.
- Expenses are kept in localStorage under the `expenses` key as a JSON array.
- Use the Export button in Settings to download a CSV backup.
- Use the Import button to replace local data with a CSV file.

## Getting started

To run locally:

1. Clone the repository:

   git clone https://github.com/Arnob2018331024/MyExpenseTrackerPWA.git

2. Open `index.html` in your browser, or serve the folder with a simple static server such as:

   npx http-server .

3. Optionally install the PWA to your device from the browser "Install" prompt.

## Data and privacy

All data is stored locally in your browser. The app does not send data to any server.
Export and import are manual operations under your control.

## Contributing

Contributions are welcome — open an issue or submit a PR with improvements.

## License

This repository does not include a license file — add one if you plan to share or accept contributions.

---

Made with care. Created with Vibe Coding.
