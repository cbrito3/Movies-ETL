# Movies-ETL

# Purpose

Britta, my client, needs my help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I’ll need to refactor my current code to create one function that takes in the three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data— and performs the ETL process by adding the data to a PostgreSQL database.

# Four technical analysis deliverables are the following:
  * Deliverable 1: Write an ETL Function to Read Three Data Files
  * Deliverable 2: Extract and Transform the Wikipedia Data
  * Deliverable 3: Extract and Transform the Kaggle data
  * Deliverable 4: Create the Movie Database

# Write an ETL Function to Read Three Data Files 
 * An ETL function is written to read in the three data files.
   - The function converts the Wikipedia JSON file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file. 
   - The function converts the Kaggle metadata file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file. 
   - The function converts the MovieLens ratings data file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file. 
