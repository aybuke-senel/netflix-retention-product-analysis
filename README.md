# Netflix User Behavior, Churn & Retention Analysis

## Project Overview

This project analyzes Netflix user behavior to understand engagement, retention, and churn patterns using real user activity data.

The main objective is to identify why users stop using the platform, detect early churn signals, and generate product recommendations that can improve user retention and engagement.

The project follows a product analytics approach by transforming raw behavioral data into business insights through SQL, PostgreSQL, Python, and data visualization techniques.

Key areas covered in the project:

- User engagement analysis
- Churn analysis
- Retention and cohort analysis
- User segmentation
- Behavioral pattern analysis
- Product recommendations based on data insights

Rather than focusing only on dashboards or machine learning models, this project emphasizes data-driven product decision making and user behavior understanding.

## Business Problem

Streaming platforms heavily rely on user retention and long-term engagement. Understanding why users become inactive or leave the platform is critical for improving user experience and reducing churn.

This project focuses on analyzing user behavior patterns to identify the factors that influence engagement and retention. By examining viewing activity, search behavior, session frequency, and user interactions, the project aims to detect early churn signals and understand which behaviors are associated with highly engaged users.

The main business questions addressed in this project are:

- Why do some users stop using the platform?
- Which user behaviors are linked to higher retention?
- What are the early indicators of churn risk?
- How can product decisions improve user engagement and retention?

The insights generated from this analysis can help support data-driven product strategies such as personalized recommendations, onboarding improvements, and user re-engagement mechanisms.

## Dataset

## Dataset

This project uses the [Netflix Watch Log](https://www.kaggle.com/datasets/arjunajn/netflix-watch-log) dataset from Kaggle.

The dataset contains multiple CSV files related to Netflix user activity and platform interactions. These files were imported into PostgreSQL and analyzed using SQL and Python workflows.

### Included Data Files

- **Viewing Activity**
  - User watch history and viewing timestamps

- **Clickstream Data**
  - User interaction and navigation activity

- **Search History**
  - Search queries and search behavior patterns

- **Profiles**
  - User profile-related information

- **Devices**
  - Device usage and interaction data

The datasets were combined to analyze user engagement, retention behavior, churn patterns, and overall platform activity.

## Tech Stack

### Database & Querying
- PostgreSQL
- SQL
- DBeaver

### Data Analysis & Visualization
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Development Environment
- Jupyter Notebook
- MiniConda

### Analysis Techniques
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Cohort Analysis
- Retention Analysis
- Churn Analysis
- User Segmentation
- Behavioral Analytics

## Data Pipeline / Workflow

```text
Raw CSV Files
    ↓
PostgreSQL Database
    ↓
SQL Queries
    ↓
Data Cleaning & Feature Engineering
    ↓
EDA & Behavioral Analysis
    ↓
Retention / Churn Insights
    ↓
Product Recommendations
