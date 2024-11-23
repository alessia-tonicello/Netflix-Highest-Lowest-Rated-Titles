# Netflix Highest and Lowest Rated Titles

This project analyzes the highest and lowest rated titles on Netflix. By processing data from Netflix’s catalog, it identifies the 10 top-rated and the 10 lowest-rated movies and TV shows, providing valuable insights into viewer preferences.
This project demonstrates practical skills in data cleaning, analysis, and visualization using Python.

## Dataset 
The dataset used for this project includes:
- Title
- Available Globally?
- Release Date
- Hours Viewd
- Number of Ratings
- Ratings
- Genre
- Key Words
- Description

The dataset is publicly available at Kaggle.com

## Methodology 
1. Data Loading and Exploration
   - Imported the dataset into a Pandas DataFrame.
   - Inspected data types, missing values, and basic statistics.
   
2. Data Cleaning
   - Removed titles with missing or invalid ratings.

3. Data Analysis
   - Sorted titles based on ratings.
   - Extracted the top 10 highest-rated and 10 lowest-rated titles.

4. Visualization
   - Used Matplotlib to visualize the data.
   - Created horizontal bar charts to display the results.

5. Insights
   - Interpreted the findings to understand the characteristics of highly-rated vs. least-rated titles.


## Usage
1. Prepare the Dataset:
   Ensure the file Netflix_Engagement.csv is located in the same folder as analyze_netflix_ratings.py (or update the file path in the script).

2. Install Python Libraries:
   You only need Python installed with the pandas library. Install it with:
   pip install pandas

3. Run the Script:
   Use the following command in your terminal to execute the analysis:
   python analyze_netflix_ratings.py

4. View the Output:
   The script will display the top 10 highest-rated and 10 lowest-rated Netflix titles directly in the terminal. 

## Results 
Top 10 Highest-Rated Titles

| Title                       | Rating | Genre          | Release Year |
|-----------------------------|--------|----------------|--------------|
| Big Time Rush:Season 1      | 10.0   | Short, Comedy  | 2009         |
| Big Time Rush:Season 4      | 10.0   | Short, Comedy  | 2013         |
| Big Time Rush:Season 2      | 10.0   | Short, Comedy  | 2010         |

Top 10 Lowest-Rated Titles

| Title                       | Rating | Genre                   | Release Year |
|-----------------------------|--------|-------------------------|--------------|
| Smoleńsk                    | 1.2    | Drama, Thriller         | 2016         |
| Debt Fees                   | 1.4    | Comedy                  | 2019         |
| Untold: Caitlyn Jenner      | 1.4    | Documentary, Biography  | 2021         |



## Technologies Used
- **Python**: The primary language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Jupyter Notebook**: For an interactive environment to run and display code.

