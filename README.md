# Analytics_Engineer_OA
## First Question:Review Existing Unstructured Data and Diagram a New Structured Relational Data Model
Please see file:Fetch_AE_OA_Q1/Q3-Jupyter Notebook.pdf
For diagram please refer to the file: Fetch_AE_OA_diagram
## Second Question:Write queries that directly answer predetermined questions from a business stakeholder
Please refer to file:Fetch_AE_OA_Q2.PDF
## Third: Evaluate Data Quality Issues in the Data Provided
Please see file:Fetch_AE_OA_Q1/Q3-Jupyter Notebook.pdf

Majority data quality issues:
  1.Duplicate Data: A large number of duplicate rows were found in the users.json data, with a total of 283 duplicate rows. This is a critical data quality issue as it can skew the analysis and lead to incorrect insights. Duplicates should be removed to ensure each user is only represented once.

  2.Missing Values: Across different datasets (users.json, brands.json, receipts.json), there were multiple instances of missing values in various columns, such as lastLogin, signUpSource, state in users.json, category, categoryCode, topBrand, and brandCode in brands.json, as well as bonusPointsEarned, bonusPointsEarnedReason, and others in receipts.json. Missing data can affect the completeness and reliability of analysis.

  3.Inconsistent Data Types: There are columns within the data that have inconsistent types. For example, topBrand in brands.json has both NaN and numeric values (0 and 1), which should be consistent booleans. In receipts.json, numeric values like pointsEarned and purchasedItemCount also had to be standardized.

  4.Unstandardized Formats: Dates in the datasets are not in a standardized format, as seen in users.json and receipts.json. While Standardization is important for accurate time-series analysis and comparisons over time.

## Fourth: Communicate with Stakeholders
Please see file:Message_to_stakeholders_.pdf
