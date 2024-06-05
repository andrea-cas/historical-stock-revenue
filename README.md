
# Tesla and GameStop Stock Analysis

This project retrieves and visualizes historical stock prices and revenue data for Tesla (TSLA) and GameStop (GME). It uses data from yfinance and web scraping to generate plots that compare stock prices and revenue over time.

## Installation

To run this project, you need to have Python installed along with the following libraries:

`pip install yfinance==0.1.67`
`mamba install bs4==4.10.0 -y`
`pip install nbformat==4.2.0`
`pip install pandas==1.3.5`

## Usage

To run the script, simply execute it in a Python environment. The script performs the following steps:

- Retrieves historical stock data for Tesla and GameStop using yfinance.
- Scrapes historical revenue data for Tesla and GameStop from provided URLs.
- Cleans and processes the data.
- Generates and displays line plots for stock prices and revenue over time.

`python your_script.py`

## Data Sources

Stock Data: Retrieved using yfinance.
Revenue Data:
- Tesla: [Revenue Data URL](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)
- GameStop: [Revenue Data URL](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html)

## Outputs

The script generates the following visualizations:

Tesla Stock Price and Revenue:

- Historical share price plot.
- Historical revenue plot.

GameStop Stock Price and Revenue:

- Historical share price plot.
- Historical revenue plot.

The plots are saved and displayed, showing trends over time for both stock prices and revenues.
