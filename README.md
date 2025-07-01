# 🏏 IPL Auctioning Dashboard – Google Sheets + Apps Script

This project simulates an IPL-style live auction using **Google Sheets** and **Google Apps Script**, providing an interactive, real-time environment for team bidding and player management.

## 📌 Features

- 🧠 Real-time bidding system with dynamic budget updates per team
- 🎲 Randomized player selection and pop-up interface for each auction round
- 📊 Live status updates: players sold, remaining, and auction progress
- 🤖 Automated updates for "Sold To", "Selling Price", and budget deduction
- 🏷️ Player categories supported (Indian / Overseas)

## 🗂️ Project Structure

- `Code.gs` – Main automation logic for bidding, popups, and updates
- `Auction.gs` – Helper functions for auction control
- `Player List` Sheet – Database of all players with base price, category, etc.
- `Auction` Sheet – Live dashboard with team tables and bid interface

## 🎮 How It Works

- Teams are given equal starting budgets.
- A random player is shown in a pop-up with their base price.
- Teams click their respective logos to place a bid.
- The winning team’s budget is automatically reduced.
- Sold player info is updated across sheets and popups in real-time.

## 📷 Screenshots

![Dashboard Overview](screenshots/dashboard-overview.png)
![Bidding Popup](screenshots/bidding-popup.png)
![Player Status Tracker](screenshots/player-status-tracker.png)

## 🔧 Tech Stack

- Google Sheets
- Google Apps Script
- JavaScript (ES5-based syntax)
- Pop-ups and Spreadsheet UI Modals

## 📦 Setup Instructions

1. Copy the Google Sheet template (coming soon).
2. Open Apps Script Editor: `Extensions > Apps Script`.
3. Paste code from `Code.gs` and `Auction.gs`.
4. Connect the script to your sheets (adjust sheet names if needed).
5. Run and authorize the script on first use.

## 📜 License

MIT License – feel free to modify and use for educational or demo purposes.

---

### 🙌 Acknowledgments

Inspired by the dynamic and strategic nature of IPL auctions, this tool was built to make mock auctions more engaging and easy to manage using cloud-native tools.

---



