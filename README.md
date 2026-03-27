# MoringaProject Documentation
Project on how to leverage Gen AI
This is still a work in progress - the idea is to capture the idea of trading with automated bots
# Target Audience
Intermediate Python developers
Traders familiar with:
Candlestick analysis
Trend & momentum
Basic algorithmic trading
Run on Pycharm Or Visual Code
# Comprehensive Function
 1. Perform daily reset (trade counters, ICC state)
  2. For each symbol:
            - Detect volatility mode (SCALP or SWING)
            - Analyze ICC phase
            - Apply trend filter (moving averages)
            - Apply momentum confirmation (candle strength)
  3. Execute trades if all conditions are satisfied
  4. Monitor and manage open trades
  5. Sleep for a defined interval before repeating
# Prompting Strategies
The comprehensive README you generated using Prompt 1
The step-by-step guide you created using Prompt 2
The FAQ document you created using Prompt 3

# Code Structure Overview / Code Readability
detect_trade_mode() → Switch between SCALP/SWING
detect_icc_phase() → Market structure logic
detect_fvg() → Fair Value Gaps
detect_order_blocks() → Institutional zones
detect_liquidity() → Liquidity pools

# Prerequisites
Python 3.11 or higher
Pandas
MetaTrader5
# Framework
Flask,Fast API

# API Documentation
Endpoint
POST /api/v1/trade/execute
Purpose
This endpoint triggers the [BOT] Trading Engine powered by MetaTrader 5.

# Error and Debugging
[notice] A new release of pip is available: 25.3 -> 26.0.1
[notice] To update, run: C:\Users\HP\AppData\Local\Programs\Python\Python313-32\python.exe -m pip install --upgrade pip
ERROR: No matching distribution found for MetaTrader5
PS C:\Users\HP\PycharmProjects\PythonProject11>   

1.Debugging the error uninstall the numpy and reinstall it.
2.Change the Python Environment 

# Run test
python your_filename.py
