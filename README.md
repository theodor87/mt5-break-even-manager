# MT5 Break-Even Manager (MQL5)

A lightweight **MetaTrader 5 Expert Advisor** written in **MQL5**, designed to automatically manage open positions by moving the stop-loss to break-even once predefined conditions are met.

This tool is intended to support **risk management**, reduce manual intervention, and improve trade execution discipline.

---

## Features

- Automatically moves Stop Loss to **Break-Even**
- Configurable break-even trigger (in pips)
- Optional extra buffer (lock-in small profit)
- Works with manual trades
- Designed for **MT5 (MetaTrader 5)**

---

## Use Case

This Expert Advisor is suitable for:
- Swing and intraday trading
- Risk management automation
- Traders who want consistent execution rules
- Reducing emotional decision-making during active trades

---

## How It Works (High-Level)

1. The EA monitors open positions
2. Once the price reaches the defined profit threshold
3. Stop Loss is moved to the entry price (or entry + buffer)
4. Trade is protected from turning into a loss

---

## Installation

1. Copy `BreakEven Manager.mq5`
2. Paste into:
3. Compile the file in **MetaEditor**
4. Attach the EA to a chart

---

## Disclaimer

This project is provided for **educational and personal use only**.  
Trading financial markets involves risk.  
The author is not responsible for any financial losses resulting from the use of this software.

---

## Author

**Teodor Dujin**  
Forex & Crypto Trader | Trading Operations & Risk  
GitHub: https://github.com/theodor87
