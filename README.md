# 💰 Smart Expense Tracker (MCP)

A powerful, minimalist, and intelligent expense tracking system built using the **Model Context Protocol (MCP)**. This tool allows AI agents to seamlessly help you manage your finances, categorize spending, and generate insights directly through your favorite AI interfaces.

![License](https://img.shields.io/github/license/username/repo?style=for-the-badge)
![Python](https://img.shields.io/badge/python-3.10+-blue.svg?style=for-the-badge&logo=python)
![FastMCP](https://img.shields.io/badge/framework-FastMCP-orange.svg?style=for-the-badge)

---

## ✨ Features

- **🤖 AI-First Integration**: Built on FastMCP for seamless use with Claude, ChatGPT, and other LLMs.
- **📁 Structured Categorization**: 20+ top-level categories with hundreds of subcategories for granular tracking.
- **📊 Smart Summaries**: Instantly generate spending reports by date range or category.
- **🔒 Private & Local**: Stores everything in a local SQLite database—your financial data never leaves your machine.
- **🛠️ Extensible Schema**: Easy to modify and adapt to your personal budgeting needs.

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python 3.10+ and `uv` or `pip` installed.

### 2. Installation
```bash
git clone https://github.com/YOUR_USERNAME/expense-tracker.git
cd expense-tracker
pip install -r requirements.txt
```

### 3. Running the Server
To start the MCP server locally:
```bash
python main.py
```

---

## 🛠️ Usage

### Available Tools
Once connected to an MCP client, the following tools become available:

- `add_expense`: Log a new transaction (amount, category, note).
- `list_expenses`: Retrieve transactions within a specific timeframe.
- `summarize`: Get a breakdown of spending by category.

### Category Management
The system uses a `categories.json` file for dynamic categorization. You can edit this file to add or remove subcategories without restarting the server.

---

## 📂 Project Structure

```text
.
├── main.py           # Core MCP server logic
├── categories.json   # Hierarchy of spending categories
├── schema.sql        # Database schema definition
├── requirements.txt  # Project dependencies
└── README.md         # You are here!
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Created with ❤️ for the AI Era.*
