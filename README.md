# MT4_GOLD
**GOLD Price Prediction Version 1**

This repository contains an MQL4 script for MetaTrader 4 (MT4) designed for automated trading of gold (XAUUSD). It includes logic for placing buy and sell orders based on predefined conditions and uses key parameters for stop-loss, take-profit, and order management.

## Features
- Automates trade placement for XAUUSD (Gold) on MT4.
- Parameters include:
  - Lot sizes for buy/sell orders.
  - Stop-loss and take-profit settings.
  - Integration of indicators like SAR and Bollinger Bands (placeholders in code).

## Code Overview
The main script (`M1_GOLD_v1`) performs the following:
1. **Initializes trade settings**:
   - `lot_buy_01`, `lot_sell_01`, `lot_buy_02`, `lot_sell_02` define trade sizes.
   - `stoploss` and `takeprofit` manage risk and reward.
2. **Uses MetaTrader’s functions**:
   - `OrderSelect()` to loop through open trades.
   - `OrderType()` to determine trade type (buy/sell).
3. **Includes placeholders for indicators** like SAR and Bollinger Bands for future expansion.

## Usage Instructions
1. **Install the Script**:
   - Copy `M1_GOLD_v1` to the `MQL4/Experts` folder in your MT4 directory.
2. **Compile the Script**:
   - Open MetaEditor, load the script, and compile it to ensure no errors.
3. **Run on MT4**:
   - Drag the script onto the XAUUSD chart in MT4 to execute trades automatically.

## Note
This is an early version and may require further customization to fit specific trading strategies. Ensure thorough testing in a demo account before live trading.
