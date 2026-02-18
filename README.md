# Ads.txt Checker & Line Matcher

![GitHub license](https://img.shields.io/github/license/OstinUA/Matcher-ads.txt-app-ads.txt)
![GitHub repo size](https://img.shields.io/github/repo-size/OstinUA/Matcher-ads.txt-app-ads.txt)
![GitHub last commit](https://img.shields.io/github/last-commit/OstinUA/Matcher-ads.txt-app-ads.txt)

A client-side utility for validating ads.txt and app-ads.txt files against SSP partner lists and specific line entries. This tool operates entirely in the browser, ensuring data privacy and ease of use for AdOps professionals.

## Features

- **Platform Check**: Validates SSP partner lists against the main authorization file.
  - Supports bulk input parsing (text or spreadsheet copy-paste).
  - Identifies status (Found/Missing), environment type, and occurrence count.
- **Line Check**: Verifies the existence of specific `ads.txt` lines (e.g., `google.com, pub-000, DIRECT`).
  - Normalizes input to ignore whitespace differences.
  - Handles comments and formatting variations.
- **Local Persistence**: Automatically saves input data to `localStorage`, preserving state between page reloads.
- **Privacy Focused**: Zero server-side processing; all validation logic executes locally.

## Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/OstinUA/Matcher-ads.txt-app-ads.txt.git](https://github.com/OstinUA/Matcher-ads.txt-app-ads.txt.git)
