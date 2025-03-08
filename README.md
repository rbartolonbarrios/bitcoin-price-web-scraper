# Bitcoin Price Web Scraper

![](Bitcoin1.png)

This project is a **Python-based web scraper** that automatically fetches the latest **Bitcoin price** from [CoinMarketCap](https://coinmarketcap.com/currencies/bitcoin/) every hour and saves the data into a **CSV file**. This enables historical tracking of Bitcoin prices over time.

## Features

- Scrapes **Bitcoin's current price** using `requests` and `BeautifulSoup`
- Stores **timestamped price data** in a CSV file
- Implements **error handling** for network issues and website structure changes
- Designed to run **every hour** via automation (e.g., Windows Task Scheduler, cron jobs)

## Technologies Used

- **Python** (for scripting)
- **BeautifulSoup** (for web scraping)
- **Requests** (for HTTP requests)
- **Pandas** (for data handling)

## Example Output (CSV File)

```
Timestamp,Price
2025-02-28 12:00:00,$81,775.40
2025-02-28 13:00:00,$81,850.20
...
```

## Future Enhancements

- Store data in a **SQL database** instead of CSV
- Create **visualizations** using Matplotlib or Power BI
- Develop a **real-time dashboard**

