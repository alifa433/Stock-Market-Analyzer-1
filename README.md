# Stock Market Analyzer

#### Video Demo: https://youtu.be/0Ct_qoVYS3A

#### Description:
The Stock Market Analyzer is a Python-based tool designed for investors, financial analysts, and enthusiasts to fetch, process, and visualize stock market data. This application simplifies the process of analyzing stock trends by providing a user-friendly interface to input a stock symbol and view its price trends over time.

## Features
- **Data Fetching**: The application fetches real-time stock data using a financial data API.
- **Data Processing**: Implements algorithms to process raw stock data into a more readable and useful format.
- **Data Visualization**: Visualizes the stock data in the form of a line graph, making it easier to understand stock trends.

## Files and Functionality

- `project.py`: This is the main file of the application. It includes functions to fetch stock data from an API, process this data, and visualize it using a line graph. The main function orchestrates the flow of the application by calling these functions in sequence.

- `test_project.py`: Contains unit tests for `project.py`. It tests each function independently to ensure they perform as expected. This file is crucial for maintaining the reliability of the application as it evolves.

## Usage
To use the application, run `project.py` and enter a stock symbol when prompted. The program will fetch the latest stock data for that symbol, process it, and display a graph showing the stock's price over time.

## Dependencies
- `requests`: Used for making HTTP requests to the stock data API.
- `matplotlib`: Utilized for creating the line graph visualization of stock data.

These dependencies can be installed using `pip install -r requirements.txt`.

## Testing
Run `test_project.py` to perform unit tests on the application. These tests are essential for ensuring that each function in `project.py` works correctly and as expected.

## Design Choices
- **API Selection**: The choice of API for fetching stock data was based on reliability, ease of use, and the richness of data provided.
- **Data Processing Logic**: The data processing algorithms were designed to handle various data inconsistencies and provide meaningful insights.
- **Visualization Technique**: The line graph was chosen for its simplicity and effectiveness in showing price trends over time.

## Future Enhancements
- Adding functionality to compare multiple stocks.
- Implementing more advanced data analysis features like moving averages and trend predictions.

## Conclusion
This project was an excellent opportunity to delve into the world of financial data analysis. It provided practical experience in working with APIs, data processing, and visualization in Python.

## Author
Ali Farhani
