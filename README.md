# Stock Data Extraction and Analysis Project

## Overview

This project involves extracting, cleaning, and analyzing financial data for Tesla and GameStop using Python. The data is extracted from Yahoo Finance and other online sources, and then prepared for analysis. The key focus is to demonstrate how to work with real-world financial data, including historical stock prices and quarterly revenue figures, using common Python data science libraries.

## Objectives

- Extract historical stock price data for Tesla (TSLA) and GameStop (GME) using the `yfinance` library.
- Extract quarterly revenue data from an HTML page using the `requests` and `BeautifulSoup` libraries.
- Clean and preprocess the extracted data for analysis.
- Prepare a consolidated view of the data for further analysis or visualization.

## Technologies and Tools

- **Python**: Core programming language used.
- **Jupyter Notebook**: Used for running and demonstrating the analysis.
- **Libraries**:
  - `yfinance`: For accessing historical stock price data.
  - `pandas`: For data manipulation and analysis.
  - `requests`: For making HTTP requests to download HTML data.
  - `BeautifulSoup`: For parsing HTML data and extracting revenue information.

## Project Steps

1. **Stock Data Extraction**: Using `yfinance`, the project extracts the historical stock data of Tesla and GameStop. The data is saved to Pandas DataFrames for further use.
2. **Revenue Data Extraction**: The revenue information is extracted from an HTML file using `requests` and `BeautifulSoup`. The table containing the revenue information is isolated and stored in a DataFrame.
3. **Data Cleaning**: The revenue column is cleaned to remove special characters like dollar signs and commas to prepare it for numerical analysis.
4. **Data Analysis and Visualization** (future work): The cleaned data can then be used for visualizing stock performance over time, finding correlations between stock prices and revenues, and more.

## Getting Started

### Prerequisites

To run the project, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python libraries: Install them using:
  ```
  pip install yfinance pandas requests beautifulsoup4 html5lib
  ```

### Running the Project

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/your-username/stock-analysis-project.git
   ```
2. Navigate to the project directory and open the Jupyter Notebook.
   ```
   cd stock-analysis-project
   jupyter notebook
   ```
3. Run the notebook cells sequentially to extract and analyze the stock and revenue data.

## File Structure

- `Stock_Analysis.ipynb`: Main Jupyter notebook containing the code and explanations.
- `README.md`: Project documentation.

## Data Sources

- **Yahoo Finance**: For historical stock price data of Tesla and GameStop.
- **IBM Developer Skills Network (HTML page)**: For quarterly revenue data.

## Future Improvements

- **Visualization**: Add visualizations to explore the trend of stock prices and revenue.
- **Machine Learning**: Use machine learning models to predict stock prices based on historical trends and revenue.
- **Automation**: Automate data extraction and analysis on a regular basis.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- The IBM Developer Skills Network for providing sample HTML data for revenue extraction.
- Yahoo Finance for providing stock data via API.

## Contact

If you have questions or suggestions, feel free to reach out:
- **Name**: Aman Jain
- **Email**: amanj120294@gmail.com
- **LinkedIn**: [linkedin.com/in/aman-jain-ab2b8b161](https://www.linkedin.com/in/aman-jain-ab2b8b161)
