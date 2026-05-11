# dailysum

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A small web app for recording amounts and free-text types with timestamps. It provides at-a-glance daily totals, historical charts, quick-entry shortcuts, and CSV data management.

Live demo: [https://code4fukui.github.io/dailysum/](https://code4fukui.github.io/dailysum/)

## Features

-   **Record Data**: Log an amount and an optional type with the current timestamp.
-   **Dashboard Stats**: View key metrics at a glance: today's total, the latest entry, and the total number of days with records.
-   **Data Visualization**: Analyze trends with two charts: a stacked bar chart of daily totals by type, and a line chart of intra-day accumulation over the last week.
-   **Quick Entry**: Automatically creates shortcut buttons for your 5 most recent unique amount-and-type combinations.
-   **History Management**: View all records in a table with options to edit timestamps or delete individual entries.
-   **Data Portability**: Import and export all your data as a CSV file.
-   **Local First**: All data is stored privately in your browser's `localStorage`—no server or account required.

## Files

-   `index.html` - The application's HTML structure and UI layout.
-   `style.css` - All UI styling, including colors, layout, and chart appearance.
-   `main.js` - Core application logic, including data handling, `localStorage` interaction, chart rendering, and CSV operations.

## Usage

Open `index.html` in a modern web browser, or use the live demo link above.

## Data Format

-   **Storage**: Data is stored in `localStorage` under the key `daily-sum-records`.
-   **CSV Format**: The CSV file uses three columns: `timestamp,type,amount`.

## License

MIT