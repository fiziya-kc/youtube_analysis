# YouTube Analysis

This project analyzes YouTube watch history data to identify trends, patterns, and insights into viewer behavior. The analysis focuses on data cleaning, preprocessing, and exploratory data analysis (EDA) to uncover meaningful insights.

---

## Table of Contents

1. [Overview](#overview)
2. [Dataset Description](#dataset-description)
3. [Steps to Run the Project](#steps-to-run-the-project)
4. [Key Features](#key-features)
5. [Insights](#insights)
6. [Dependencies](#dependencies)

---

## Overview

The goal of this project is to analyze YouTube watch history to:
- Understand viewing patterns over time.
- Identify the most popular content categories.
- Explore trends in viewer engagement.

---

## Dataset Description

The dataset is derived from `watch_histry.xlsx`, which includes the following columns:
- **Date and Time**: Timestamp of the viewing activity.
- **Video Title**: Title of the watched video.
- **Category**: The category of the video.
- **Watch Duration**: Duration (in minutes) the video was watched.

---

## Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd youtube-analysis
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Open the `youtube_analysis.ipynb` file in Jupyter Notebook and execute the cells step-by-step.

4. **Export Results**:
   After completing the analysis, export the notebook to HTML using:
   ```bash
   jupyter nbconvert --to html youtube_analysis.ipynb
   ```

---

## Key Features

- **Data Cleaning**:
  - Handles missing or inconsistent data.
  - Ensures a clean dataset for analysis.

- **Exploratory Data Analysis**:
  - Visualizations of trends and distributions.
  - Insights into most-watched categories and peak viewing hours.

- **Customizable Analysis**:
  - Code can be adapted for other datasets with similar structures.

---

## Insights

### Key Findings

- **Viewing Patterns**:
  - Peak viewing occurs between 7 PM and 10 PM.
  - Weekend activity is higher than weekdays.

- **Popular Categories**:
  - Most-watched categories include "Education", "Entertainment", and "Technology".

- **Engagement Trends**:
  - Long-form videos (>10 minutes) have higher completion rates.

### Visualizations

The notebook includes:
- **Trend Graphs**: Viewing patterns over time.
- **Histograms**: Distributions of watch durations.
- **Bar Charts**: Most-watched categories.
- **Heatmaps**: Correlation between metrics.

---

## Dependencies

Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `openpyxl` (for reading Excel files)

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

### Notes

- Replace `<repository-url>` with the actual URL of your GitHub repository.
- Update `watch_histry.xlsx` with your dataset before running the notebook.
- Feel free to customize the analysis to suit your requirements.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

