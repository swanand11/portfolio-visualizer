# Portfolio Visualizer

## Description
Portfolio Visualizer is a Python application that allows users to manage and visualize their investment portfolios. The application supports buying and selling stocks, displaying portfolio details, and generating visualizations for risk metrics and stock performance.

## Features
- Load and save portfolio data from a CSV file.
- Buy and sell stocks using real-time market data.
- View current portfolio status and stock holdings.
- Visualize risk metrics and performance using charts.
- Calculate and display beta for individual stocks and the entire portfolio.

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - yfinance
  -seaborn
  -csv
### How to Use
- To buy stocks, select option 1 from the main menu and follow the prompts.
- To sell stocks, select option 2 and provide the necessary details.
- To view your portfolio, select option 3.
- For visualization, select option 4.
- To exit the application, select option 5.
## Challenges Addressed

During the development of the Portfolio Visualizer, several challenges were encountered and resolved:

1. **Real-Time Data Fetching**:
   - Integrating real-time stock prices was challenging due to API limitations. The `yfinance` library was utilized for seamless data retrieval, with error handling for API failures.

2. **Dynamic Portfolio Management**:
   - Maintaining accurate share counts and values required careful updates. A structured DataFrame allowed for efficient tracking of transactions and real-time calculations.

3. **Data Visualization**:
   - Creating effective visualizations for risk metrics and portfolio performance was complex. `matplotlib` was used to generate informative charts, including scatter plots for individual stock betas.

4. **User Interaction**:
   - Designing a user-friendly command-line interface was essential for usability. A simple menu-driven approach was implemented to streamline user navigation.

5. **Error Handling**:
   - Validating user inputs and managing errors during transactions was crucial. Input validation and comprehensive error handling were integrated to ensure robust functionality.

These challenges have led to a more refined application that enhances user experience and data accuracy.

### Acknowledgements
- yfinance for fetching stock data.
- Matplotlib for visualizations.
