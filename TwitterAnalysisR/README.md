# TWITTER AND THE CROSS SECTION OF STOCK RETURNS

## 1. How to Run the Program

### File Provided:

-   **`TwitterAnalsyisR.Rmd`**
-   **`tweets.csv`**
-   **`sp500.csv`** - Available here: https://drive.google.com/file/d/1D4iuk3naIF1J2TXSDu82uh2ETdlexPW3/view?usp=share_link


> The file, `TwitterProjectWithDataset.Rmd`, is designed for analyzing an existing dataset of tweets. The dataset, contained in `tweets.csv`, ranges from 2022-11-06 to 2022-12-20 and includes tweets for the top 80% of S&P 500 companies by market cap. The `sp500.csv` file includes the corresponding weights as of 2022-12-20.

To run this file:

1.  Download the `tweets.csv` from my Google Drive
2.  Make sure `tweets.csv` and `sp500.csv` are in the same working directory and not renamed.
3.  Open `TwitterAnalsyisR.Rmd` with RStudio
4.  Clear the R environment, including hidden objects.
5.  Press the "Run All" button.

## The analysis will be performed as the code goes along

------------------------------------------------------------------------

### Packages Used

The following R packages are required and will be automatically installed:

-   rvest
-   dplyr
-   lubridate
-   xts
-   ggplot2
-   quantmod
-   stringr
-   stopwords
-   tidytext
-   tokenizers
-   calendR
-   syuzhet

# The Dataset was downloaded using the Academic Twitter Api

## <https://developer.twitter.com/en/portal/dashboard>
