# Contributing to Santa Ana Equity KPI Repository

Thank you for your interest in helping maintain and improve the Santa Ana Equity KPI project. This document explains how to update data and documentation.

## Updating Quarterly KPI Data
1. Navigate to the `data/kpi` directory (create it if it doesn't exist).
2. Add a new CSV file named in the format `YYYY_Q#.csv` (e.g., `2024_Q1.csv`).
3. Include all relevant KPI metrics in the CSV. Use consistent column headers across quarters.
4. Commit the new file with a message describing the update, e.g., `Add Q1 2024 KPI data`.

## Maintaining Equity Agreements and Profit Distribution Files
1. Store equity agreement documents in `docs/equity-agreements/` as PDF files.
2. Profit distribution reports belong in `docs/profit-distribution/`.
3. When updating or adding documents, use clear filenames that include the date (e.g., `equity_agreement_2024-01.pdf`).
4. Keep historical files intact—never overwrite existing agreements or distribution reports.

## Contributing to Documentation or Data
1. Fork the repository and create a feature branch for your changes.
2. Make your edits or additions in the appropriate directory.
3. Ensure that Markdown files follow basic Markdown syntax for headings and lists.
4. Before submitting a pull request, run any available tests (if present) and ensure your branch is up to date with `main`.
5. Describe the purpose of your change clearly in the pull request description.

We appreciate all contributions that help us maintain accurate data and thorough documentation!
