# NinjaScripts
I create NinjaScripts for fun and backtest parameters to find patterns that work for trading Futures. I specialize in NQ 1-minute, but they can be backtested on any instrument.

A collection of custom trading strategies built for NinjaTrader 8 using NinjaScript (C#). These scripts are designed to automate entries, exits, and risk management for futures trading, with a focus on compliance with prop firm evaluation rules (Apex, TopStep, etc.).

📌 Features

Pre-built strategies for futures trading (NQ, ES, YM, etc.).

Risk management tools: ATR stops, trailing stops, daily loss limits, auto-flatten logic.

Entry logic examples: moving average crossovers, VWAP pullbacks, RSI conditions, probability toggles.

Modular structure so you can plug in or modify your own setups.

Optimized for prop firm rule-sets (drawdown protection, scaling, max trades/day).

/strategies → NinjaScript .cs files ready to import into NinjaTrader.

Each file includes setup instructions in the header comments.

⚡ Installation

Open NinjaTrader 8.

Go to Tools → Import → NinjaScript Add-On.

Select the .cs file(s) from this repository.

Compile the script inside the NinjaScript Editor.

Apply the strategy to a chart.

🛠 Usage

Load a strategy from Strategies tab on your chart.

Adjust parameters (ATR period, stop loss, profit target, etc.) in the properties window.

Enable live simulation or real trading (at your own risk).

📖 Example Strategies

ATRStopStrategy → Uses Average True Range to set dynamic stops.

VWAPPullbackStrategy → Buys pullbacks into VWAP with defined exits.

PropFirmRiskControl → Enforces daily loss limits and auto-flattens trades.

ScalpingExample → Tick-based micro scalping system for NQ futures.

⚠️ Disclaimer

These strategies are provided for educational purposes only. Trading futures and derivatives involves substantial risk of loss and is not suitable for all investors. Use these scripts at your own discretion and always test in simulation before live trading.

🤝 Contributions

Pull requests are welcome for bug fixes, new setups, or optimization improvements.

Open an issue if you find a problem or have a feature request.
