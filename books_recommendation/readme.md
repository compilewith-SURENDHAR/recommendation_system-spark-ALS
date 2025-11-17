## Book recommendation system build using pyspark's ALS

* This project implements a collaborative filtering recommendation system using PySpark’s ALS (Alternating Least Squares) algorithm. It predicts user ratings for books and generates Top-N recommendations.
* The system uses historical user–book ratings to learn latent user and item features. The final model recommends books a user has not read, ranked by predicted preference.

## tech stack used
-- Python -- Pyspark -- Spark -- ALS -- Databricks

## Core steps:

1. Load data (ratings + books metadata)

2. Split into training and validation sets

3. Train ALS model

4. Tune hyperparameters using CrossValidator + ParamGridBuilder

5. Select best model based on RMSE

6. Train final optimized model

7. Generate Top-N recommendations for users and books
