# 🐦 Tweet Generator using Google Gemini AI 🔥

This project is a simple and elegant Tweet Generator built using **Google Gemini AI**, **Python**, and a minimal **UI with ipywidgets**.  
It takes user inputs like topic, tone, audience, and hashtags to generate a Twitter-friendly post within 280 characters.

> ✨ Ideal for content creators, marketers, and developers learning how to integrate LLMs with Python UIs.

---

## 🚀 Features

- Generates smart and catchy tweets under 280 characters
- Supports different tones: *Professional, Casual, Motivational, Informative*
- Clean, interactive UI using `ipywidgets`
- Integrates securely with **Gemini 2.5 Flash** model using API key
- Keeps your API key safe using `.env` and `python-dotenv`

## 🛠️ Tech Stack

| Tool               | Purpose                           |
|--------------------|------------------------------------|
| Python             | Core programming language          |
| Google Generative AI (Gemini) | AI model for generating text |
| ipywidgets         | Interactive UI in Jupyter/VS Code  |
| dotenv             | For securely loading environment variables |
| Jupyter Notebook / VS Code | For development and execution |


## 📦 Setup Instructions

### 1. Clone the Repository

git clone https://github.com/PriyanshPorwal999/IBM_Agentic_AI.git
cd IBM_Agentic_AI

### 2. Create Virtual Environment
python -m venv .venv

Windows: .\.venv\Scripts\activate
macOS/Linux:  source .venv/bin/activate


### 3. Install Dependencies
pip install -r requirements.txt

### 4. Create .env File
In the root folder, create a file named .env with this content:
GEMINI_API_KEY=your-actual-api-key-here

Never share this file. It’s excluded from GitHub using .gitignore.

### 5. Run the Notebook
Open Priyansh_Simple_agent.ipynb in VS Code or Jupyter Notebook.

Click "Run All Cells" or interact with it one cell at a time.

# Resources 
[IBM Quick Start](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/videos-wx.html?context=wx&audience=wdp).
