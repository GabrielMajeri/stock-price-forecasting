# Stock price forecasting using machine learning

## Description

This repository contains [our](#authors) entry to the "Quant World 2022" challenge organized by [LSEG](https://lseg.com) Romania for the students at the [Faculty of Mathematics and Informatics](https://fmi.unibuc.ro/en/), [University of Bucharest](https://unibuc.ro/?lang=en).

The objective was to predict the short-term evolution of the closing price for five different stocks, using historical data starting from about 2012. Since the input dataset contained no other information about the companies except for opening/closing prices and trading volumes, we had to rely on [technical analysis](https://en.wikipedia.org/wiki/Technical_analysis) to predict future changes in the stocks' values. We've won second place for our analysis and modelling of the data.

The data loading, exploratory data analysis, data preprocessing, feature engineering and model building and selection code is included in [the Jupyter notebook included in the repo](Stock_price_forecasting.ipynb).

## Dataset

Unfortunately, due to copyright reasons we are not allowed to disclose the original dataset given to us by the contest organizers. That being said, any other source of historical market data should work fine, provided that the input is available in `.xlsx` format with the following columns, in order: `date`, `open`, `high`, `low`, `close`, `adj_close`, `volume`. The "high" and "low" columns refer to the maximum/minimum values attained by the stock during that respective trading day, while `adj_close` refers to [the adjusted closing price](https://www.investopedia.com/terms/a/adjusted_closing_price.asp).

## Authors

- [Gabriel Majeri](https://github.com/GabrielMajeri)
- [Mihai Condrat](https://github.com/CondratMihai)

## Reuse

The Python code is licensed under the permissive [MIT license](LICENSE.txt).
