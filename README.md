# Bitcoin Price Data Pipeline

![](Bitcoin1.png)

This project demonstrates the development of an automated data collection workflow using Python. The application retrieves the latest Bitcoin price from [CoinMarketCap](https://coinmarketcap.com/currencies/bitcoin/) on a scheduled basis and stores timestamped observations in a CSV file, creating a historical dataset that can be used for trend analysis and visualization.

The project illustrates practical concepts in web scraping, automation, and data collection while emphasizing reliable acquisition of external data for downstream analytics.


## Technologies

- **Python**
- **Requests**
- **BeautifulSoup**
- **Pandas**
  
## Project Features

- Developed an automated Python workflow for scheduled cryptocurrency price collection.
- Retrieved real-time Bitcoin price data from CoinMarketCap using HTTP requests and HTML parsing.
- Generated timestamped historical datasets suitable for downstream analysis.
- Implemented basic error handling to improve reliability during automated execution.
- Designed the workflow to support scheduled execution using operating system task schedulers.

## Sample Dataset

```
Timestamp,Price
2025-02-28 12:00:00,$81,775.40
2025-02-28 13:00:00,$81,850.20
...
```

## Potential Enhancements

- Store data in a relational database instead of CSV.
- Integrate with a cloud scheduling platform for continuous execution.
- Build an interactive Power BI dashboard for historical price analysis.
- Extend the pipeline to support multiple cryptocurrency assets.

