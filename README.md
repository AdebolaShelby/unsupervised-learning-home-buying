# Clustering National Home Markets

In this activity, I used the K-means algorithm to identify trends within a dataset of residential house prices in the US.

## Background

This model identifies how similar the national real estate market is at any point in time in comparison to real estate periods in the past. Quantifying today's real estate market against the past will help an institution better understand its lending risk as well as the potential for new growth.

I decided to use the K-means algorithm to segment different periods in the US market for national residential house prices.

## Setup

1. Review the Pandas DataFrame and plot associated with `national-home-sales.csv`.

2. Run the K-means algorithm identifying three clusters in the data.

   * Create and initialize the K-means model for three clusters. Use a `random_state` value of 1 for the model.

   * Fit, or train, the model by using the `home_sales_df` DataFrame.

   * Make predictions about the clustering by using the trained model. Save the predictions to a variable called `home_segment_3`, and print that variable.

   * Create a copy of the DataFrame and name it `home_sales_predictions_df`.

   * Add a column to the `home_sales_predictions_df` DataFrame called "home_segment_3", and add the `home_segment_3` information to the column.

   * Plot the data by using the DataFrame adjusted to include home market segment information for three clusters.

3. Run the K-means algorithm identifying four clusters in the data.

   * Create and initialize the K-means model for four clusters. Use a `random_state` value of 1 for the model.

   * Fit, or train, the model by using the `home_sales_df` DataFrame.

   * Make predictions about the clustering by using the trained model. Save the predictions to a variable called `home_segment_4`, and print that variable.

   * Add a column to the `home_sales_predictions_df` DataFrame called "customer_segment_4", and add the `home_segment_4` information to the column.

   * Plot the data by using the DataFrame adjusted to include customer segment information for four clusters.
