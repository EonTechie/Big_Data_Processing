# Spark SQL Based Tasks

This module contains data processing and analysis tasks implemented using **Apache Spark SQL and DataFrames**.  
The datasets are structured and queries are executed in a distributed manner using SQL-like operations.

### 📌 Included Notebooks

- **Tag-Based Average Rating Analysis**  
  Computes average ratings of movies for each user-defined tag using the MovieLens dataset. Demonstrates the use of joins, groupBy, and aggregation functions with Spark SQL.

- **User Similarity Engine (MovieLens)**  
  Builds a user-user similarity engine based on movie ratings. Uses Spark DataFrames to prepare user vectors and applies a similarity metric (e.g. cosine) to identify top-10 most similar users for each user.
