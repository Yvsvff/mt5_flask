MT5 Flask Integration 🚀

Overview

mt5_flask is a Python-based project that integrates MetaTrader 5 (MT5) with Flask to create a REST API for financial data retrieval and trade execution. The project will expand by incorporating AI agents (CrewAI), automation (n8n), and a Next.js frontend to build a comprehensive financial system.

📌 Features

Automated MT5 Terminal: Python script will automatically start and connect to the MT5 terminal.

REST API: Flask will expose endpoints for retrieving financial data and executing trades.

AI Agents (CrewAI): AI agents will interact with the exposed API to provide financial insights.

Automation (n8n): Workflows will automate trading and decision-making processes.

WebSocket Integration: Real-time updates and market data streaming.

Next.js Frontend: A web interface to display market insights, trade execution, and automation logs.

🎯 Project Goals

Facilitate collaboration and critique before implementing trading strategies.

Allow users to query financial data such as:

“What is the price of gold?”

“What’s the margin cost?”

“How much will I make in 50 pips?”

“What economic news is coming out?”

Build a financial AI-powered company with agents managing market analysis and trade execution.

🔧 Tech Stack

Backend: Python, Flask, MetaTrader5 (MT5), WebSockets

AI Agents: CrewAI

Automation: n8n

Frontend: Next.js

🚀 Installation & Setup

Prerequisites

Python 3.9+

MetaTrader 5 installed

Flask & required dependencies

n8n for automation

Setup Steps

Clone the repository

git clone https://github.com/your-username/mt5_flask.git
cd mt5_flask

Create a virtual environment & install dependencies

python -m venv venv
source venv/bin/activate  # On Windows use 'venv\Scripts\activate'
pip install -r requirements.txt

Run the MT5 Flask Server

python main.py

Access the API Endpoints (Example: Get account balance)

curl http://127.0.0.1:5000/api/balance

📡 WebSocket Integration

WebSockets will enable real-time price updates and trade execution notifications.

🧠 Future Enhancements

Implement AI-driven risk management & trade analysis.

Expand n8n workflows for automated trade execution.

Enhance Next.js UI for better visualization.

🤝 Contribution

Critiques, discussions, and contributions are welcome! Let’s build together. 🚀

📜 License

This project is licensed under MIT License.

