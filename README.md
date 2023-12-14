# MACD Dashboard Scanner MT4 ReadMe File

This code is a MACD Dashboard Scanner for MT4, developed by the Forex Robot Easy Team. It allows users to scan multiple symbols and display the MACD values on a dashboard.

## Customizable Parameters

- `NumberOfSymbols`: The number of symbols to be copied from the market watch.
- `CustomSymbols`: Custom symbols to be displayed.

## Global Variables

- `gNumberOfSymbols`: Number of symbols to be displayed on the dashboard.
- `gSymbols`: Array to store the selected symbols.
- `gMACD`: Array to store MACD values for each symbol.

## Initialization

The `OnInit()` function initializes the global variables and copies the symbols from the market watch. If the number of symbols to be copied exceeds the total number of symbols in the market watch, an error message is displayed. Custom symbols are also added to the array.

## Start Function

The `OnStart()` function updates the MACD values and displays them on the dashboard for each symbol.

## Custom Functions

- `ArrayCopyMACD(string symbol)`: This function performs the MACD calculation for the specified symbol and returns the MACD values.
- `DisplayOnDashboard(string symbol, double[] macd)`: This function displays the MACD values on the dashboard.

## MACD Calculation Function

This function is not implemented in the provided code. It needs to be implemented separately based on the desired MACD calculation method.

## Dashboard Display Function

This function is not implemented in the provided code. It needs to be implemented separately based on the desired dashboard display method.

## Market Trend Analysis Function

This function is not implemented in the provided code. It needs to be implemented separately based on the desired market trend analysis method.

## Real-Time Updates Function

This function is not implemented in the provided code. It needs to be implemented separately based on the desired real-time updates method.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work in a similar manner to the product described. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, you can visit [Forex Robot Easy's review of MACD Dashboard Scanner MT4](https://forexroboteasy.com/forex-robot-review/macd-dashboard-scanner-mt4-review-multi-timeframe-forex-trend-indicator/).
