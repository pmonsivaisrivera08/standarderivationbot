🤖 Standard Deviation Trading Bot
This is a Jupyter Notebook (Standard_Deviation_Trading_Bot.ipynb) designed for technical analysis and generating automatic trading signals primarily based on Standard Deviation and the Relative Strength Index (RSI).
The bot uses historical stock data to simulate a trading strategy, plot the results, and evaluate performance.
🌟 Features
* Data Download: Retrieves historical stock price data directly using yfinance.
* Technical Analysis: Calculates key indicators such as Standard Deviation, Bollinger Bands (implied), and RSI.
* Signal Generation: Implements a simple trading logic to generate Buy (BUY) or Sell (SELL) signals.
* Basic Backtesting: Simulates the performance of the strategy over time.
* Visualization: Generates clear charts showing closing prices and trading signals.
🛠️ Requirements
To run this program, you will need Python installed (preferably Python 3.x) and the following libraries:
pip install yfinance pandas numpy matplotlib

🚀 Usage and Installation
1. Clone or Download the Repository
git clone [https://github.com/pmonsivaisrviera08/nombre-del-repositorio.git](https://github.com/pmonsivaisrviera08/nombre-del-repositorio.git)
cd nombre-del-repositorio


(Note: Replace nombre-del-repositorio with the actual name of your GitHub repository.)
2. Open the Notebook
Start Jupyter Notebook or JupyterLab and open the file Standard_Deviation_Trading_Bot.ipynb.
3. Parameter Configuration
Within the first cells of the notebook, you can easily modify the following parameters:
   * ticker: Stock ticker symbol (e.g., 'AAPL', 'GOOG').
   * start_date: Start date for the analysis (format 'YYYY-MM-DD').
   * end_date: End date for the analysis (format 'YYYY-MM-DD').
   * window_val: Period for Standard Deviation and RSI calculation (usually 20 or 14).
   4. Execution
Run all cells in the notebook in order to download data, calculate indicators, generate signals, and visualize the backtesting results.
🛑 Ownership and License
Ownership: This program is an original creation and is the total and exclusive property of its author, pmonsivaisrviera08.
License: This software does not have any Open Source license. Copying, distribution, modification, or commercial use of this code is prohibited without the explicit written permission of the owner.