## Extracting and Visualizing Stock Data
Extracting essential data from a dataset and displaying it is a necessary part of data science, enabling individuals to make informed decisions based on the data. This project involves extracting stock data and visualizing it through graphs.

### Table of Contents
1. Define a Function that Makes a Graph
2. Use yfinance to Extract Stock Data for Tesla
3. Use Web Scraping to Extract Tesla Revenue Data
4. Use yfinance to Extract Stock Data for GameStop
5. Use Web Scraping to Extract GameStop Revenue Data
6. Plot Tesla Stock Graph
7. Plot GameStop Stock Graph

### Estimated Time Needed
30 minutes

### Steps
1. **Define a Function that Makes a Graph**:
   - Create a function `make_graph` to plot stock and revenue data.

2. **Extract Stock Data for Tesla using yfinance**:
   - Use the `yfinance` library to extract Tesla stock data.
   - Store the data in a DataFrame named `tesla_data`.

3. **Extract Tesla Revenue Data using Web Scraping**:
   - Use the `requests` library to download the relevant webpage.
   - Use `BeautifulSoup` to parse the HTML and extract the Tesla revenue data.
   - Store the data in a DataFrame named `tesla_revenue`.

4. **Extract Stock Data for GameStop using yfinance**:
   - Use the `yfinance` library to extract GameStop stock data.
   - Store the data in a DataFrame named `gme_data`.

5. **Extract GameStop Revenue Data using Web Scraping**:
   - Use the `requests` library to download the relevant webpage.
   - Use `BeautifulSoup` to parse the HTML and extract the GameStop revenue data.
   - Store the data in a DataFrame named `gme_revenue`.

6. **Plot Tesla Stock Graph**:
   - Use the `make_graph` function to plot Tesla stock and revenue data.

7. **Plot GameStop Stock Graph**:
   - Use the `make_graph` function to plot GameStop stock and revenue data.

### Note
If you are working locally using Anaconda, please ensure to install the following libraries before running the project:
- yfinance
- pandas
- nbformat
- bs4

### Acknowledgements
This project leverages the following libraries:
- `yfinance` for stock data extraction
- `requests` and `BeautifulSoup` for web scraping
- `plotly` for graph visualization

