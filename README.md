# Stock Trend Prediction using RecurrentNeualNetwok-RNN
Going to look at the stock price from 2005 to 2021. Then predict the trend for 2022, the test dataset has the data from the month of January-October 2022. Will compare to this test set data and see how good was our trend prediction.
Following examples are included in the processing:

  Load training dataset
  Scale the data using MinMaxScaler
  Create 60 row buckets - approximately 3 months
  Use first 60 rows are initial data (time t0)
  Instantiate a RNN model - set appropriate layers
  Train the model
  Make predictions using test dataset
  Plot trend prediction v/s actual 2022 data
NOT GOING TO PREDICT THE STOCK PRICE BUT PREDICT THE TREND - UP or DOWN or FLAT
