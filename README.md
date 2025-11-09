# Stock Predictor Dashboard

An AI-powered dashboard that analyzes market data and recent news to suggest 3 stocks with potential for gains in the next 3 days.

## 🎯 Project Overview

This project combines real-time market data, news sentiment analysis, and AI-powered insights to generate daily stock recommendations. Built as a learning project to explore AI integration in financial analysis.

## ⚠️ Disclaimer

**This is an educational project and NOT financial advice.**

- Do not use these recommendations for actual trading decisions
- Past performance does not guarantee future results
- Always do your own research and consult with financial advisors
- The creator assumes no responsibility for any financial losses

## 🚀 Features

- Real-time stock market data integration
- News sentiment analysis using AI
- Daily recommendations for 3 stocks
- Confidence scores and reasoning for each pick
- Historical tracking of predictions vs. actual performance

## 🛠️ Tech Stack

- **Frontend**: React / HTML/CSS/JavaScript
- **Backend**: Node.js / Python
- **AI Analysis**: Anthropic Claude API
- **Data Sources**:
  - Stock data: Alpha Vantage / Yahoo Finance API
  - News: NewsAPI / Google News
- **Deployment**: TBD (Vercel / Netlify / AWS)

## 📋 Prerequisites

- Node.js (v16+) or Python (3.8+)
- Git
- API Keys:
  - Anthropic API key
  - Stock market data API key
  - News API key

## 🔧 Installation

1. Clone the repository

```bash
git clone https://github.com/forgetsemicolon/stock-predictor.git
cd stock-predictor
```

2. Install dependencies

```bash
npm install
# or
pip install -r requirements.txt
```

3. Set up environment variables

```bash
cp .env.example .env
# Edit .env and add your API keys
```

4. Run the application

```bash
npm start
# or
python app.py
```

## 🔐 Environment Variables

Create a `.env` file with the following:

```
ANTHROPIC_API_KEY=your_claude_api_key
STOCK_API_KEY=your_stock_data_api_key
NEWS_API_KEY=your_news_api_key
```

## 📁 Project Structure

```
stock-predictor/
├── README.md
├── .gitignore
├── .env.example
├── package.json
├── src/
│   ├── api/
│   │   ├── stocks.js       # Stock data fetching
│   │   └── news.js         # News data fetching
│   ├── ai/
│   │   └── claude.js       # AI analysis logic
│   ├── components/
│   │   └── Dashboard.js    # Main dashboard UI
│   └── utils/
│       └── helpers.js      # Utility functions
└── public/
    └── index.html
```

## 🎯 Roadmap

- [ ] Set up project structure
- [ ] Integrate stock market data API
- [ ] Integrate news API
- [ ] Implement Claude AI analysis
- [ ] Build dashboard UI
- [ ] Add historical tracking
- [ ] Deploy to production
- [ ] Add backtesting feature

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are welcome! Feel free to open issues or submit pull requests.

## 📝 License

MIT License - feel free to use this project for learning purposes.

## 📧 Contact

GitHub: [@forgetsemicolon](https://github.com/forgetsemicolon)

---

**Note**: This project is under active development. Features and documentation will be updated regularly.
