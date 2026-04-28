# AI Engineering Foundations Portfolio Project

This project demonstrates a complete beginner-friendly machine learning workflow for text classification using Python.

## Project Overview
The goal of this project is to build a spam classifier that can distinguish between spam and legitimate SMS messages.

## Skills Demonstrated
- Data loading and cleaning
- Exploratory data analysis
- Text preprocessing
- Feature engineering with TF-IDF
- Model training with Multinomial Naive Bayes
- Model evaluation with accuracy, precision, recall, F1 score, and confusion matrix

## Project Structure
```text
Project-AI-Engineering-Foundation/
├── README.md
├── notebook.ipynb
├── requirements.txt
└── data/
    └── spam.csv
```

## Dataset
Recommended dataset:
- UCI SMS Spam Collection: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

You can also use a Kaggle mirror if you prefer.

## How to Run
1. Clone or download this repository.
2. Create a `data/` folder.
3. Put your dataset file inside `data/` and name it `spam.csv`.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Start Jupyter:

```bash
jupyter notebook
```

6. Open `notebook.ipynb` and run the cells in order.

## Expected Dataset Format
Your CSV file should contain two columns:
- `label` → values like `ham` and `spam`
- `message` → the SMS text

Example:

```csv
label,message
ham,Are we still meeting later?
spam,You won a free prize! Click now!
```

## Results
Typical performance for this type of project is very strong when TF-IDF and Naive Bayes are used on the SMS Spam Collection dataset.

## Reflection
This project is a strong portfolio example because it shows the full ML workflow from raw text data to an evaluated predictive model.
