# synent-task3-netflixeda-krish\
# Netflix Dataset Exploratory Data Analysis (EDA)

## Problem Statement

With the rapid growth of online streaming platforms, understanding content distribution and viewing trends has become essential. The objective of this project is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify patterns, trends, and insights related to movies and TV shows available on Netflix.

---

## Dataset Details

**Dataset Name:** Netflix Movies and TV Shows Dataset

**Source:** Kaggle - Netflix Dataset

**Number of Records:** Approximately 8,800+

**Number of Features:** 12

### Features

* show_id
* type
* title
* director
* cast
* country
* date_added
* release_year
* rating
* duration
* listed_in
* description

### Dataset Characteristics

* Contains both Movies and TV Shows
* Includes content from multiple countries
* Covers various genres and release years
* Contains some missing values in director, cast, country, and date_added columns

---

## Approach

The following Exploratory Data Analysis steps were performed:

### 1. Data Loading

* Imported the dataset using Pandas.
* Displayed dataset dimensions and sample records.

### 2. Data Understanding

* Examined dataset structure using info().
* Checked data types of all columns.
* Identified missing values.
* Generated summary statistics.

### 3. Content Analysis

* Analyzed the distribution of Movies and TV Shows.
* Compared the quantity of different content types.

### 4. Country-wise Analysis

* Identified the top countries contributing content to Netflix.
* Visualized the top 10 countries by content count.

### 5. Trend Analysis

* Converted date_added into datetime format.
* Extracted year-wise content additions.
* Analyzed growth trends of Netflix content over time.

### 6. Correlation Analysis

* Examined relationships among available numerical variables.
* Evaluated potential patterns within the dataset.

---

## Results

### Key Findings

#### Content Distribution

* Movies significantly outnumber TV Shows on Netflix.
* Netflix maintains a diverse content library across multiple formats.

#### Top Content-Producing Countries

* The United States contributes the highest amount of content.
* India, the United Kingdom, and Canada are also major contributors.

#### Growth Trend

* Netflix experienced substantial growth in content additions after 2015.
* The number of titles added increased rapidly during the platform's expansion phase.

#### Data Quality

* Missing values were identified in:

  * Director
  * Cast
  * Country
  * Date Added
* These missing values should be addressed before advanced modeling.

#### Correlation Analysis

* Limited numerical features were available for strong correlation analysis.
* Trend analysis provided more meaningful insights than numerical correlation.

---

## Outcome

Successfully performed Exploratory Data Analysis on the Netflix dataset and identified important trends related to:

* Content Type Distribution
* Country-wise Content Production
* Netflix Growth Trends
* Data Quality Assessment

The generated visualizations and insights provide a better understanding of Netflix's content ecosystem and can support future business analysis and recommendation system development.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Author

Krish Kaneria

