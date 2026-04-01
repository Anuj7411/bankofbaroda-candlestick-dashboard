# Bank of Baroda Candlestick Dashboard

An interactive stock market visualization project built with `Python`, `Pandas`, and `Plotly` to explore Bank of Baroda price movement through a candlestick chart.

This project takes raw OHLCV stock data, cleans it, transforms the date series, and turns it into a clean interactive dashboard-style chart that can be viewed directly in Jupyter Notebook or exported as HTML for sharing.

## Why This Project Stands Out

- Converts raw market data into an interactive candlestick visualization
- Uses a clean notebook workflow that is easy to understand and reproduce
- Exports the final chart as a standalone HTML file
- Shows practical use of data cleaning, preprocessing, and visual storytelling

## Project Preview

The final output is an interactive candlestick chart saved as:

- `bank_baroda_candlestick.html`

It visualizes:

- open price
- high price
- low price
- close price
- time-based stock movement for Bank of Baroda

## Project Structure

- `index.ipynb` - main notebook containing the full project workflow
- `StockDataBANKBARODA_1.csv` - source stock dataset
- `bank_baroda_candlestick.html` - exported interactive Plotly chart
- `requirements.txt` - Python dependencies

## Tech Stack

- Python
- Pandas
- Plotly
- Jupyter Notebook

## Workflow

1. Import the required libraries.
2. Load the stock market CSV file.
3. Clean and preprocess the dataset.
4. Convert the date column into datetime format.
5. Prepare OHLC values for charting.
6. Build the candlestick chart with Plotly.
7. Export the chart as an interactive HTML file.

## Run Locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch the notebook:

```bash
jupyter notebook index.ipynb
```

Run all notebook cells to regenerate the visualization.

## Learning Highlights

This project demonstrates:

- working with real stock market data
- cleaning and transforming time-series datasets
- building financial visualizations with Plotly
- exporting notebook results into shareable interactive output

## Future Improvements

- add moving averages and technical indicators
- include volume charts below the candlestick plot
- support multiple stocks from different CSV files
- turn the notebook into a full Streamlit or Dash app

## Disclaimer

This project is for educational and portfolio purposes only. It is not financial advice.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
