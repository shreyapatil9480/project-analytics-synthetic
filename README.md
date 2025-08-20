# Project Analytics: Synthetic Dataset for Business & Data Analysis

This repository contains a **synthetic project analytics dataset** and an accompanying Jupyter Notebook demonstrating exploratory data analysis (EDA), visualization, and predictive modeling. The project is structured to showcase increasing levels of difficulty, making it suitable for roles such as **Business Analyst**, **Program Manager**, and **Data Analyst**.

## Project Structure

- **data/project_data.csv** – A synthetic dataset simulating project management metrics for 300 projects.
- **notebooks/analysis.ipynb** – Jupyter Notebook with step-by-step EDA, visualizations, and predictive models.
- **requirements.txt** – Dependencies to recreate the environment.

## Dataset Description

The dataset simulates 300 projects with the following columns:

| Column | Description |
|-------|-------------|
| `project_id` | Unique identifier for each project. |
| `start_date` | Project start date. |
| `planned_end_date` | Planned completion date. |
| `actual_end_date` | Actual completion date. |
| `team_size` | Number of team members assigned to the project. |
| `budget` | Project budget in USD. |
| `tasks_completed` | Total number of tasks completed. |
| `risk_level` | Categorical risk assessment (Low, Medium, High). |
| `client_satisfaction` | Rating from 1 (poor) to 10 (excellent). |
| `delayed` | 1 if the project finished after the planned end date, 0 otherwise. |
| `success` | 1 if the project met key criteria (on schedule, high satisfaction, high task count), 0 otherwise. |

## Installation

1. **Clone this repository**

```
git clone <your-repo-url>.git
cd <your-repo-name>
```

2. **Install dependencies** (preferably in a virtual environment):

```
pip install -r requirements.txt
```

3. **Launch the Jupyter Notebook**:

```
jupyter notebook notebooks/analysis.ipynb
```

## Notebook Overview

The Jupyter Notebook walks through three stages of analysis:

1. **Exploratory Data Analysis (EDA)** – basic statistics, missing value checks, distribution plots, and correlations.
2. **Visualizations** – bar charts, histograms, and trend lines to understand relationships between variables such as risk level, budget, delays, and success.
3. **Predictive Modeling** – demonstrates logistic regression and random forest models to predict project success, along with model evaluation (accuracy, confusion matrix).

Each section includes comments and explanations to guide you through the analysis. The notebook is designed to be self-contained and ready to run out-of-the-box, so you can focus on interpreting results rather than data preparation.

## License

This project is provided under the MIT License. Feel free to use, modify, and extend the code and dataset for educational or professional purposes.

## Contributions

Since this is a synthetic and educational repository, contributions are welcome! If you wish to add new features, models, or visualizations, feel free to fork the repo and open a pull request.
