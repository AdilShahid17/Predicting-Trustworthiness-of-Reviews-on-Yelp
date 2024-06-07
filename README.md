# Predicting-Trustworthiness-of-Reviews-on-Yelp
Categorizing reviewers on Yelp as 'Trustworthy' and 'Non-Trustworthy' based on a set criteria, and creating a Machine Learning model (Logistic Regression) to predict trustworthiness of reviews.

### Dataset:
The dataset contains 6,990,280 records of Yelp reviews from 150,346 different businesses. It can be accessed from [Yelp Dataset](https://www.yelp.com/dataset).

### Project Overview:
This project aims to predict the trustworthiness of Yelp reviews by classifying reviews as either 'trustworthy' or 'non-trustworthy' based on user characteristics and review features. The key steps in this project include data importing, cleaning, exploratory data analysis (EDA), defining trustworthiness, merging datasets, and building a machine learning model.

### Key Sections:

#### I. Background
- **Problem Definition and Objective**: To ascertain whether Yelp reviews are genuine or made by trolls/bot accounts by evaluating user ratings, the number of prior reviews, and user traction. The ultimate goal is to create a machine learning model to predict the trustworthiness of a review.
- **Introduction and Motivation**: Identifying unreliable reviews helps improve consumer experience and provides businesses with accurate feedback.

#### II. Report Summary
- Summary of steps: Importing and cleaning data, EDA, consolidating columns, defining trustworthy users, merging datasets, and building a machine learning model.

#### III. Importing Data
- Data schema definitions and loading datasets using PySpark.

#### IV. Data Cleaning
- Dropping duplicates and irrelevant columns, handling missing values.

#### V. Exploratory Data Analysis
- Summary statistics and key insights about the dataset.
- Visualizations exploring the distribution of reviews, ratings, and user behavior.

#### VI. Initial Questions about the Dataset
- Analyzing distribution of reviews, average ratings, relationship between review count and ratings, geographic differences, text length, and user engagement.

#### VII. Consolidating the Various Compliments Columns
- Merging compliment columns into a single column to simplify the dataset.

#### VIII. Predicting which Reviews are given by Trustworthy Reviewers
- **Defining Trustworthy Reviews**: Criteria for classifying users as trustworthy.
- **Merging Datasets**: Combining user and review data for analysis.
- **Machine Learning Model**: Creating a pipeline, training a logistic regression model, and evaluating the model performance.

#### IX. Conclusion
- Summary of findings and the importance of distinguishing trustworthy reviews to improve consumer decision-making and business insights.

#### X. Challenges
- Challenges faced in terms of dataset size, integration, and collaboration on PySpark.

#### XI. References
- A list of academic references used in the study.

### How to Run the Project:
1. **Clone the Repository**: Clone this repository to your local machine using `git clone`.
2. **Install Dependencies**: Ensure you have PySpark and required Python libraries installed.
3. **Download Dataset**: Download the Yelp dataset from the provided link and place it in the appropriate directory.
4. **Run the Notebook**: Open the notebook and run the cells sequentially. Ensure you have access to a Spark cluster if running on large datasets.

---

