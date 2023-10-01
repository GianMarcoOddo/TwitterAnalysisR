# Twitter and the Cross-Section of Stock Returns - R Programming Language

> # Please refer to the `README.md` file inside the `TwitterAnalysisR` folder for a detailed guide on how to test the code.

## Project Overview

This project aimed to examine the relationship between Twitter activity and stock market performance for companies listed in the S&P 500 index. Through a series of steps, we will investigate how tweet volume and sentiment relate to stock returns.

## Workflow

### Obtain the Current Weights of the S&P 500 Index

- Retrieved the current weightings of companies in the S&P 500 index to serve as a benchmark for our Twitter data analysis.

### Download Tweets About Companies in the Index

- Used the Twitter API to download tweets mentioning companies in the S&P 500, using their specific "cashtags" (e.g., `$AAPL` for Apple).

### Produce a Daily Time Series of Tweet Volume

- Generated a daily time series dataset that shows the number of tweets about each company.

### Analyze Tweet Cyclicality

- Conducted time series analysis on the aggregated tweet data to identify any cyclical patterns.

### Compare Tweet Market Share to S&P 500 Index Weights

- Calculateed the "market share" of tweets for each company and compare it to their weight in the S&P 500 index.
- Identified companies that are "overtweeted" and "undertweeted."
- Formed equally weighted portfolios of these companies and analyze their subsequent performance.

### Sentiment Analysis of Tweets 

- Implemented a simple method to categorize tweets as either "bullish" or "bearish."
- Re-formed equally weighted portfolios based on this categorization and evaluate their performance.

---
## Contact

- Email: gian.marco.oddo@usi.ch
- LinkedIn: https://www.linkedin.com/in/gian-marco-oddo-8a6b4b207/
- GitHub: https://github.com/GianMarcoOddo
> Feel free to reach out for any questions or further clarification on this code.
---



