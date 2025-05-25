# IMDB Movies Data Analysis

In this Python data analysis project, the IMDB Movie Dataset is explored to derive insights into various movie aspects. Essential Python libraries such as Pandas, Seaborn, and Matplotlib are employed for efficient data manipulation and visualization.

## Dataset Overview

The dataset consists of 1000 entries, each representing a movie, featuring 12 columns providing information such as title, genre, director, year, runtime, rating, votes, revenue, and metascore.

## Data Cleaning

The initial step involves checking the dataset's Shape(Rows, Columns) then identification of missing values, visualized through a heatmap, prompts their removal to ensure data integrity.

## Handling Duplicates

Duplicate entries are examined and removed to enhance the dataset's clarity and avoid redundancy.

## Exploratory Data Analysis (EDA)

EDA is conducted to unveil patterns and trends. It includes displaying overall statistics, identifying lengthy movies, determining the highest average voting and revenue per year, and assessing the rating's impact on revenue.

![image](https://github.com/user-attachments/assets/91a25286-5498-460b-88bc-c33128d7ab2b)

![image](https://github.com/user-attachments/assets/3b39b382-00c9-4dbd-9f22-c4c7a54b8d37)

![image](https://github.com/user-attachments/assets/69ac073b-662c-4c95-a46b-8788892a96e0)

![image](https://github.com/user-attachments/assets/4b53808c-8b18-4dfc-978b-2f807b859f8a)

## Top Movies Analysis

The identification of the most popular movies based on revenue and highest ratings is performed. Additionally, movies are classified into categories like "Excellent," "Good," or "Average" based on their ratings.

## Genre Analysis

An exploration of genre information involves counting the number of action movies and finding unique genre values.

List of functions used in the "IMDB Movies Data Analysis" project:

1. **Pandas Functions:**
   - `pd.read_csv()`: Reads the dataset from a CSV file.
   - `isnull().sum()`: Counts the missing values in the dataset.
   - `dropna()`: Drops rows with missing values.
   - `duplicated().any()`: Checks for duplicate rows.
   - `describe(include='all')`: Provides overall statistics about the dataframe.

2. **Seaborn Functions:**
   - `heatmap()`: Visualizes missing values using a heatmap.
   - `barplot(x, y, data, hue, dodge)`: Plots bar graphs for various analyses.
   - `scatterplot(x, y, data)`: Creates a scatter plot for analyzing the relationship between two variables.

3. **Matplotlib Functions:**
   - `plt.title()`: Adds a title to the plot.
   - `plt.show()`: Displays the plot.
