# 🧠 SoSoPulse AI: Market Intelligence Telegram Bot

An advanced, zero-maintenance AI agent that fetches live crypto market capital flows and sector momentum to generate 24-hour predictive intelligence theses directly on Telegram.

## 🚀 Features
- **Real-Time Data Layer:** Automatically pulls live sector-spotlight and flow data via SoSoValue API.
- **AI Synthesis Layer:** Utilizes **Gemini Flash** with specialized prompt engineering for zero-latency, institutional-grade market reports.
- **Telegram Interface:** Beautifully formatted HTML output with automatic HTML escaping for error-free delivery.
- **Serverless Automation:** Built on Make.com for 24/7 autonomous polling and instant response execution.

## 🛠️ Architecture & Tech Stack
- **Google Gemini AI** (Gemini 3.5/3.1 Flash)
- **SoSoValue API** (Market Intelligence Data)
- **Make.com** (Workflow Automation & Orchestration)
- **Telegram Bot API** (User Interface)

## 📦 How to Replicate (Deployment Instructions)
1. Download the `blueprint.json` file from this repository.
2. Go to your **Make.com** dashboard and create a new scenario.
3. Click the three dots `...` at the bottom menu and select **Import Blueprint**. Upload the JSON file.
4. **Important Note:** Inside the HTTP module, you will need to replace the placeholder `YOUR_SOSOVALUE_API_KEY` with your actual SoSoValue API Key. Also, re-link your own Telegram Bot Token and Google AI Studio Key in their respective modules.
5. Turn the scenario **ON**.
