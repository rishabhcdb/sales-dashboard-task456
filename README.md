# sales-dashboard-task456

## Overview
The sales-dashboard-task456 project is a web application that utilizes Bootstrap to create a dynamic sales dashboard. It loads data from `sales.csv` and `regions.json` to display total sales, a breakdown of sales by category, and calculates the total tax based on regional tax rates.

## Features
- Loads `sales.csv` and `regions.json` for data input.
- Displays total sales in the `#total-sales` element.
- Shows a breakdown table `#sales-by-category` with each category's total.
- Calculates and displays the total tax in the `#total-tax` element using regional tax rates.
- Ensures Bootstrap is included via `document.querySelector("link[href*='bootstrap']")`.
- Validates at least two rows in the sales breakdown table.
- Verifies the total sales value is approximately 4717.72.
- Uses PapaParse for CSV parsing.

## How to Use
1. Clone the repository using `git clone https://github.com/yourusername/sales-dashboard-task456.git`.
2. Navigate to the project directory.
3. Open `index.html` in a web browser to view the dashboard.

## Technology Stack
- Bootstrap for styling and layout.
- PapaParse for parsing CSV files.
- Vanilla JavaScript for data manipulation and DOM manipulation.

## Project Structure
```
sales-dashboard-task456/
├── index.html
├── sales.csv
├── regions.json
└── styles.css
```

## Local Development
To run the project locally:
1. Clone the repository: `git clone https://github.com/yourusername/sales-dashboard-task456.git`.
2. Navigate to the project directory: `cd sales-dashboard-task456`.
3. Open `index.html` in your preferred web browser.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).