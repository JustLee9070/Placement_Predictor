# Placement Predictor — My First Machine Learning Project

This is a small **toy project and my first project in Machine Learning (ML)**. I built it to get hands-on experience with Python, data analysis, and training a machine learning model.

The project explores how a student's CGPA and IQ relate to their placement outcome and uses these features to predict whether a student gets placed.

## Project Overview

- **Goal:** Predict a student's placement outcome using CGPA and IQ.
- **Type:** Binary classification.
- **Model Accuracy:** Approximately **78%**.
- **Project Level:** Beginner — my first ML project.

*This is an educational project intended for learning and experimentation, not a reliable tool for making actual placement decisions.*

## Dataset

The project uses `placement-dataset.csv`, which contains the following columns:

| Column | Description |
|---|---|
| `cgpa` | Student's CGPA |
| `iq` | Student's IQ score |
| `placement` | Placement outcome (`1` = placed, `0` = not placed) |

## Tech Stack

- **Python** — Core programming language
- **Jupyter Notebook** — Development and experimentation
- **NumPy** — Numerical computations
- **Pandas** — Data handling and analysis
- **Matplotlib** — Data visualization
- **Scikit-learn** — Machine learning tools

## Project Structure

```text
Placement_Predictor/
├── Dummy_Placement_Predictor.ipynb
├── placement-dataset.csv
├── requirements.txt
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/JustLee9070/placement-predictor.git
cd placement-predictor
```

### 2. Install the dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Run the notebook

```bash
python -m jupyter notebook
```

Open `Dummy_Placement_Predictor.ipynb` in Jupyter Notebook and run the cells.

Make sure `placement-dataset.csv` stays in the project directory so the notebook can load the dataset correctly.

## What I Learned

Through this project, I started gaining practical experience with:

- Working with datasets using Pandas and NumPy.
- Understanding the basic machine learning workflow.
- Using features to predict a target variable.
- Training and evaluating a classification model.
- Interpreting model accuracy and understanding the limitations of a simple ML model.

## Future Improvements

- Experiment with different classification algorithms.
- Improve preprocessing and feature selection.
- Evaluate the model using a confusion matrix, precision, recall, and F1-score.
- Build a simple web interface to make predictions.

## Disclaimer

This is my first machine learning project, created for educational purposes. The reported accuracy of approximately 78% is based on my current experiment and does not guarantee similar performance on unseen or real-world data. Model performance can vary depending on the dataset, preprocessing, and evaluation method.

## Author

**Rakshin Joshi**

- GitHub: [@JustLee9070](https://github.com/JustLee9070)

---

*This project marks the beginning of my journey into Machine Learning. More experiments and projects to come!*
