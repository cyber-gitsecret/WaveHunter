# WaveHunter
Advanced Pine Script strategy combining Fibonacci retracements, RSI, volume, candlestick patterns, and dynamic support/resistance for precision intraday and swing trading.

# FibFusion-Strategy

FibFusion-Strategy is an all-in-one Pine Script strategy designed for intraday and swing traders who rely on confluence-based technical setups. This script intelligently combines key Fibonacci retracement levels (50%, 61.8%, 78.6%) with volume confirmation, RSI thresholds, and candlestick price action to generate accurate buy/sell signals. It also automatically plots real-time support and resistance zones based on pivot highs and lows, helping traders identify critical price reaction levels.Built using Pine Script v5 for TradingView, FibFusion gives traders an edge by providing visual and data-driven signals grounded in reliable market structure.

## 🔍 Features

- ✅ **Fibonacci Retracement Zones** (50%, 61.8%, 78.6%) plotted automatically
- ✅ **RSI Confirmation** to validate overbought/oversold zones
- ✅ **Volume Filter** to confirm trade strength
- ✅ **Candlestick Pattern Recognition** via candle coloring (green/red)
- ✅ **Dynamic Support & Resistance Levels** from pivot highs/lows
- ✅ **Buy & Sell Signals** with clear on-chart labels
- ✅ Fully compatible with **TradingView Pine Script v5**

---

## 🧠 Strategy Logic

**Buy Entry Conditions:**
- Price retraces to Fibonacci 50%–61.8% zone
- RSI is **below oversold threshold (e.g., < 40)**
- Volume is **above 20-bar average**
- Candle is **bullish** (green)

**Sell Entry Conditions:**
- Price pulls back to Fibonacci 50%–61.8% zone
- RSI is **above overbought threshold (e.g., > 60)**
- Volume is **above 20-bar average**
- Candle is **bearish** (red)

Support and resistance zones are plotted in **blue**, using recent swing highs and lows.

---

## 📌 Usage

1. Open TradingView → Pine Editor
2. Paste the full script
3. Add to chart
4. Use on 30m or higher timeframes
5. Adjust RSI & volume filters to fit your strategy

---

## 💡 Tip

Combine with additional filters (MACD, EMAs, multi-timeframe logic) for even stronger setups.

---

## 📎 License

Open-source for educational use. Feel free to fork, modify, and enhance.

---
