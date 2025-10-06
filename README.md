# Sales Summary test

## Summary
This static web app fetches data from a CSV file, calculates the total sum of sales, and displays the result on the page. Bootstrap 5 is used for styling.

## Setup
To deploy the app on GitHub Pages:
1. Fork this repository.
2. Upload the `data.csv` file to the `attachments` directory.
3. Enable GitHub Pages for the `main` branch in repository settings.

## Usage
Access the page at: `https://your-username.github.io/your-repository/index.html`

Query Parameters:
- None

## Code Explanation
The app fetches the `data.csv` file and parses it to calculate the total sales. The CSV parsing is robust, handling trailing newlines and empty rows by ignoring them during the summing process.

## License
This project is licensed under the MIT License.