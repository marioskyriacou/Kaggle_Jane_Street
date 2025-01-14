# Kaggle_Jane_Street

In this competition, hosted by Jane Street, you'll build a model using real-world data derived from production systems, which offers a glimpse into the daily challenges of successful trading. This challenge highlights the difficulties in modeling financial markets, including fat-tailed distributions, non-stationary time series, and sudden shifts in market behavior.
# Data 
* train.parquet - The training set, contains historical data and returns. For convenience, the training set has been partitioned into ten parts.
* date_id and time_id - Integer values that are ordinally sorted, providing a chronological structure to the data, although the actual time intervals between time_id values may vary.
* symbol_id - Identifies a unique financial instrument.
* weight - The weighting used for calculating the scoring function.
* feature_{00...78} - Anonymized market data.
* responder_{0...8} - Anonymized responders clipped between -5 and 5. The responder_6 field is what you are trying to predict.
