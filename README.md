# Fintech Review Analytics

Ethiopian mobile banking review analysis for Omega Consultancy.

## Project Overview

Structured analysis of Google Play Store reviews for three Ethiopian banks:
- **CBE** (Commercial Bank of Ethiopia)
- **BOA** (Bank of Abyssinia)
- **Dashen Bank**

## Project Structure

fintech-review-analytics/
├── .vscode/           # VS Code settings
├── .github/           # GitHub Actions CI/CD
├── data/              # Data files (gitignored)
├── notebooks/         # Jupyter notebooks
├── src/               # Source code modules
├── tests/             # Unit tests
├── scripts/           # Standalone scripts
├── .gitignore         # Git exclusions
├── requirements.txt   # Python dependencies
└── README.md          # This file

## Setup

1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Linux/Mac)
4. Install dependencies: `pip install -r requirements.txt`

## Tasks

- **Task 1**: Data Collection & Preprocessing
- **Task 2**: Sentiment & Thematic Analysis
- **Task 3**: PostgreSQL Database
- **Task 4**: Insights & Visualization

## CI/CD

GitHub Actions runs `pytest` on every push/PR to `main`.