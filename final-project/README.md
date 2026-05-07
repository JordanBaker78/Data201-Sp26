# DATA 201 – Final Project  
# The  Model Battle: One Tree vs. Many Trees

## Final Project Theme
In this project, you will investigate an important question in modern Data Science and Machine Learning:

> Can many trees working together outperform a single decision tree?

You will build, compare, and evaluate predictive models using a real-world dataset connected to Maryland. Your project should focus not only on prediction accuracy, but also on interpretation, communication, and understanding model tradeoffs.

This project builds directly from our work with:
- Decision Trees
- Random Forests
- Gradient Boosting
- Overfitting
- Model evaluation using MSE and \(R^2\)

---

# Project Goals
By completing this project, you should be able to:

- Build and evaluate predictive models
- Interpret a decision tree
- Compare single-model vs ensemble approaches
- Explain overfitting in plain language
- Discuss the tradeoff between accuracy and interpretability
- Communicate findings clearly using visualizations and written analysis

---

# Local Dataset Requirement

For this final project, your dataset should be connected to **Maryland**.

A dataset related to **Montgomery County** is strongly preferred.

The goal is to make your project feel local, relevant, and connected to real communities around us.

Possible topics include:
- Housing
- Schools
- Traffic or crashes
- Weather and climate
- Public health
- Crime/safety
- Transportation
- Income or employment
- Population and demographics
- Parks and recreation
- Public services

You may use data from:
- Montgomery County Open Data
- Maryland Open Data
- U.S. Census
- NOAA
- Bureau of Labor Statistics
- Public education datasets
- Other approved public datasets

---

# Dataset Requirements

Your dataset must contain:
- At least **1000 rows**
- At least **5 variables**
- At least:
  - One quantitative variable
  - One categorical variable
- One clear numeric target variable for prediction

You may:
- Reuse a previous dataset from Project 1 or 2
OR
- Choose a new dataset

---

# Required Models

You MUST build and compare the following models:

| Model | Required |
|---|---|
| Decision Tree Regressor | Yes |
| Random Forest Regressor | Yes |
| Gradient Boosting Regressor | Yes |

Optional bonus models:
- AdaBoost
- Bagging Regressor
- SVM/SVR
- XGBoost

---

# Project Sections

# 1. Introduction

Write 1–2 paragraphs describing:
- Your dataset
- Your prediction goal
- Why the problem is interesting or important
- Possible limitations or bias in the dataset

Include a citation for your dataset source.

---

# 2. Dataset and Preparation

Include:
- Dataset size
- Explanation of variables
- Missing value handling
- Encoding categorical variables if needed
- Train/test split

Include at least one table describing variables.

---

# 3. Exploratory Data Analysis

Create:
- 2–4 visualizations
- Short interpretations

Discuss:
- Interesting patterns
- Trends
- Possible relationships

Keep this section concise.

---

# 4. Decision Tree Analysis (Core Section)

This is the most important section of the project.

You must:
- Train a Decision Tree Regressor
- Experiment with tree depth
- Explain possible overfitting
- Include a visualization or diagram of your tree

Also explain:
- The root node
- One important split
- One example prediction path

### Example
> “If median income > 4.2 and house age < 20, the model predicts higher house values.”

Your goal is to show that you understand how a decision tree makes decisions.

---

# 5. Ensemble Models

Train:
- Random Forest
- Gradient Boosting

Compare them to your single decision tree.

Discuss:
- Did performance improve?
- Which model generalized better?
- Which model was easier to explain?
- Did ensembles reduce overfitting?

---

# 6. Model Evaluation

You must include:

| Metric | Meaning |
|---|---|
| MSE | Lower is better |
| \(R^2\) | Higher is better |

Include:
- A comparison table
- Actual vs Predicted visualization
- Interpretation of results

---

# 7. Feature Importance

For at least one ensemble model:
- Display feature importance
- Identify the most influential features

Important:
- Feature importance does NOT prove causation

---

# 8. Final Reflection: The Model Battle

Answer the following questions:

1. Which model performed best?
2. Which model was easiest to interpret?
3. Was higher accuracy worth losing interpretability?
4. If this were a real-world organization or local agency, which model would you choose and why?
5. What limitations does your analysis have?

End your project with:

# “Winner of the Model Battle”

and briefly defend your choice.

---

# Video Presentation Requirement

In addition to your notebook, you must record a short presentation video.

## Video Requirements
- Length: **3–6 minutes**
- You may record:
  - Your screen
  - Your slides
  - Your notebook walkthrough
  - Or a combination of these

Your video should explain:
1. Your dataset and prediction goal
2. Your Decision Tree model
3. Comparison with Random Forest and Gradient Boosting
4. Which model performed best
5. One interesting insight or challenge

The goal is to communicate your findings clearly and professionally.

You do NOT need advanced editing.

---

# Submission Requirements

Submit:
- Jupyter Notebook (`.ipynb`)
- PDF export of notebook
- Presentation slides (if used)
- Video presentation
- Dataset citation/source

Submit your notebook link through Teams.

---

# Grading Emphasis

| Component | Focus |
|---|---|
| Understanding | Interpretation and reasoning |
| Analysis | Model comparison |
| Communication | Clarity of writing and visuals |
| Code | Correct implementation |
| Reflection | Thoughtful discussion of tradeoffs |

Perfect prediction accuracy is NOT expected.

---

# Final Advice

A strong project is not the one with the most complicated code.

A strong project:
- asks good questions
- explains models clearly
- interprets results honestly
- communicates findings effectively
