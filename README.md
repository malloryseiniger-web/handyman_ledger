# 🛠️ Handyman Ledger

A Progressive Web App (PWA) for tracking handyman business expenses, income, mileage, materials, and client management.

## Features

- **Dashboard**: Overview of monthly income, expenses, mileage, and net profit
- **Entry Management**: Add expenses, income, mileage, materials, tools, and inventory
- **Receipt Management**: Photo capture with OCR text extraction
- **Mileage Tracking**: IRS-compliant mileage logging with automatic rate calculation
- **Client Management**: Track work by client with open/closed status
- **Reports**: Per-client summaries and tax categorization
- **Data Export**: CSV export and encrypted backup/restore functionality
- **Offline Support**: Works without internet connection (PWA)

## Usage

1. Open `index.html` in any modern web browser
2. The app stores all data locally on your device using IndexedDB
3. Use the backup feature to save your data before clearing browser data
4. Export CSV for tax preparation or accounting software

## Tax Features

- Automatic tax categorization for different expense types
- IRS mileage rate tracking (default $0.67/mile for 2024)
- Asset threshold tracking for tools and equipment
- Business vs. personal expense separation

## Installation

Simply download the `index.html` file and open it in your browser. No server required!

## Data Storage

All data is stored locally on your device. Use the backup feature regularly to prevent data loss.

## License

Open source - feel free to modify and use for your handyman business.
