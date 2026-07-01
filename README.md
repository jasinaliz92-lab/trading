# 🥇 GoldMaster PRO — XAUUSD Trading System

Professional Gold trading analysis tool with AI-powered signals.

## Features
- ⚡ Live Gold price (auto-refresh)
- 🧠 AI Signal: BUY / SELL / WAIT with confidence %
- 📊 Multi-timeframe analysis (Daily/4H/1H/15m)
- 🪤 Smart Money Concepts (Liquidity Sweep, Order Blocks, FVG)
- 📏 ATR-based dynamic Stop Loss
- 💰 Risk Calculator (lot size, profit targets)
- 📅 Economic Calendar + session guide
- 🤖 AI Chat assistant (Urdu/English)
- ⏰ Pakistan time sessions (Power Hour 6-10PM PKT)

---

## Vercel Pe Deploy Karna (Step by Step)

### Step 1 — GitHub Account
- github.com pe free account banao

### Step 2 — New Repository
- "New repository" click karo
- Name: `goldmaster-pro`
- Public select karo
- Create karo

### Step 3 — Files Upload
Yeh saari files GitHub repo mein upload karo:
```
goldmaster-pro/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   └── index.js
├── package.json
├── vercel.json
└── .env.example
```

### Step 4 — Vercel Deploy
1. vercel.com pe jao
2. GitHub se login karo
3. "New Project" → apna repo select karo
4. Environment Variables mein add karo:
   - `REACT_APP_ANTHROPIC_API_KEY` = your key
5. Deploy click karo!

### Step 5 — Live Link
```
https://goldmaster-pro.vercel.app
```

---

## Anthropic API Key Kahan Se Milega?

1. console.anthropic.com pe jao
2. Sign up (free)
3. "API Keys" → "Create Key"
4. Copy karo → Vercel mein paste karo

---

## Strategies Inside
1. EMA 9/21/50/200 Trend System
2. Liquidity Sweep / Fake Breakout Detection
3. Order Block (SMC)
4. Fair Value Gap (FVG)
5. RSI Oversold/Overbought
6. MACD Momentum
7. ATR Dynamic Stop Loss
8. London/NY Power Hour Filter
9. DXY Dollar Correlation
10. Partial Close (50% at 1:1 RR)
