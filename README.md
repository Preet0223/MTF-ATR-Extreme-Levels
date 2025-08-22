# MTF ATR Extreme Levels - Pine Script Indicator

A powerful Pine Script indicator for TradingView that identifies extreme price levels across multiple timeframes using ATR-based calculations. Perfect for spotting high-probability reversal zones and confluence areas.

## 🎯 Features

- **Multi-Timeframe Analysis**: Monitors 6 timeframes simultaneously (1D, 4H, 1H, 30M, 15M, 5M)
- **Dynamic ATR Calculations**: Each timeframe calculates its own ATR and EMA independently
- **4-Level System**: L1, L2, L3, L4 extreme levels with cascading logic
- **Real-Time Matrix Display**: Visual table showing active levels across all timeframes
- **Smart Level Detection**: Automatically checks lower levels when higher levels are reached
- **Fully Customizable**: Enable/disable any timeframe or level individually
- **High Probability Zones**: Identify potential reversal areas when multiple timeframes align

## 📊 How It Works

The indicator calculates ATR-based deviation levels for each timeframe:
- **Level 1**: 0.5x ATR from EMA (default)
- **Level 2**: 1.0x ATR from EMA (default)  
- **Level 3**: 1.5x ATR from EMA (default)
- **Level 4**: 2.0x ATR from EMA (default)

When price reaches any level, the matrix displays checkmarks (✓) for that level and all lower levels, providing instant visual feedback on market extremes.

## 🚀 Use Cases

- **Reversal Trading**: Identify potential turning points when multiple timeframes show extreme levels
- **Risk Management**: Gauge market volatility and position sizing
- **Confluence Analysis**: Spot areas where multiple timeframe levels align
- **Market Structure**: Understand price behavior across different time horizons

## ⚙️ Customizable Settings

- ATR and EMA periods
- ATR multipliers for each level
- Individual timeframe toggles
- Individual level toggles
- Color customization
- Label display options

## 📈 Perfect For

- Swing traders looking for reversal zones
- Day traders seeking confluence areas
- Risk managers monitoring volatility
- Anyone wanting multi-timeframe level analysis

## 🔧 Installation

1. Copy the Pine Script code
2. Open TradingView Pine Editor
3. Paste the code and save
4. Add to your chart
5. Customize settings as needed

## 📝 Version

Pine Script v6 compatible

---

*Created for traders who want to see the bigger picture across multiple timeframes simultaneously.*
