# fpna-bot
“A Streamlit-based FP&A; Assistant using ChatGPT and Excel files”
# .gitignore
__pycache__/
*.pyc
*.pyo
*.pyd
*.DS_Store
.env
.env.*
.idea/
.vscode/
*.xls*
*.pdf

---

# README.md

# 📊 FP&A Bot

A powerful, AI-driven Financial Planning & Analysis assistant built with Streamlit and ChatGPT. Upload Excel financial data, ask questions, generate charts, and export insights to PDF — all in one simple web interface.

## 🚀 Features

- 💬 Chat-based financial analysis using GPT-4
- 📁 Upload and preview Excel files (multiple sheets supported)
- 📈 Generate line and bar charts from your data
- 📄 Export responses to PDF
- 🎯 Built for business analysts, finance teams, and executives

## 📦 Requirements

Install required packages:

```bash
pip install -r requirements.txt
```

## 🧪 Run the App Locally

```bash
streamlit run fpna_bot.py
```

Replace your OpenAI key in `fpna_bot.py`:
```python
openai.api_key = "YOUR_OPENAI_API_KEY"
```

## 🌐 Deploy on Streamlit Cloud

1. Push this repo to GitHub
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud)
3. Connect your GitHub repo and deploy
4. Add your OpenAI API key under Secrets:
```
OPENAI_API_KEY=your-key-here
```

---

## 📋 Sample Excel Format

| Year | Revenue | Expenses | Profit |
|------|---------|----------|--------|
| 2023 | 500000  | 300000   | 200000 |
| 2024 | 600000  | 350000   | 250000 |

---

## 🔐 Notes
- GPT-4 API is required
- Only `.xlsx` or `.xls` files are supported
- The app is stateless (no file/data storage)

---

## 🙋‍♂️ Need help?
Feel free to open an issue or connect with me for custom enhancements.
