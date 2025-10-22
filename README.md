# CBRE Group Shares Outstanding

## Overview
This project fetches and displays the common stock shares outstanding for CBRE Group from the SEC API.

## Features
- Displays maximum and minimum shares outstanding values.
- Supports dynamic fetching of data based on CIK query parameter.

## Setup Instructions
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
- The page will display the shares outstanding for CBRE Group by default.
- You can change the company by adding a CIK parameter to the URL, e.g., `index.html?CIK=0001018724`.

## Code Explanation
- The HTML structure includes sections for displaying the maximum and minimum shares.
- JavaScript fetches data from the SEC API and updates the DOM accordingly.

## License
This project is licensed under the MIT License.