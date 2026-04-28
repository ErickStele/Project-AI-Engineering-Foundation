# AI Engineering Foundations Portfolio Project

## Project Title
SMS Spam Dataset Analysis

## Project Overview
This project is a beginner-friendly exploratory data analysis of the SMS Spam Collection dataset using Python, pandas, and matplotlib. The notebook investigates structural patterns in the dataset and compares ham and spam messages through simple statistics and visualizations.

## Project Goal
The goal of this project is to answer a small set of clear data questions:
- How many ham and spam messages are in the dataset?
- Are there missing values?
- Are spam messages longer than ham messages?
- What is the probability of receiving a spam message in this dataset?

## Tools and Skills Used
- Python
- pandas
- matplotlib
- Reading tab-separated data files
- Data inspection with `head()`, `shape`, `columns`, and `info()`
- Missing-value checks with `isnull()`
- Frequency analysis with `value_counts()`
- Feature creation with `apply()`
- Group comparisons with `groupby()`
- Basic probability calculation from observed data
- Data visualization with bar charts

## Dataset
This project uses the **SMS Spam Collection** dataset from the UCI Machine Learning Repository.

Dataset source:
- [SMS Spam Collection - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)

The dataset contains 5,572 SMS messages and two main categories: `ham` and `spam`.[cite:21]

## Project Structure
```text
Project-AI-Engineering-Foundation/
├── README.md
├── Project.ipynb
├── requirements.txt
└── data/
    └── spam.csv
```

## Analysis Steps
The notebook includes the following steps:
1. Load the dataset into pandas.
2. Inspect the first rows and check the dataset structure.
3. Check for missing values.
4. Count the number of ham and spam messages.
5. Create new columns for `clean_message`, `message_length`, and `word_count`.
6. Compare ham and spam messages using mean and median values.
7. Visualize the class distribution.
8. Calculate the probability of a message being spam.

## Key Findings
Based on the notebook analysis:
- The dataset contains 5,572 rows and 2 columns.
- There are no missing values in the `label` and `message` columns.
- Spam messages are longer on average than ham messages.
- The calculated probability of receiving a spam message in this dataset is **13.41%**.

## Example Result
The spam probability was calculated with the formula:

`probability = spam_count / total_count`

In the notebook:
- Spam count: 747
- Total count: 5572
- Probability of spam: 13.41%

## How to Run the Project
1. Download or clone the repository.
2. Place the dataset file in the `data/` folder as `spam.csv`.
3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Project.ipynb` and run the cells in order.

## Conclusion
This project demonstrates a solid foundations-level data analysis workflow. It shows how basic Python and pandas skills can be used to inspect a dataset, compare categories, visualize patterns, and calculate a simple real-world probability.
