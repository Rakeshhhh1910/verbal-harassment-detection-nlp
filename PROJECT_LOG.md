
# Verbal Harassment Detection — Learning Log

## Day 1: Project Initialization

### Goal
Set up the project environment ie python 3.12 for sciket learn etc and connect GitHub.

### What I learned
- use of rm -rf <file/folder name> to permanently delete the file/folder
- Purpose of a Python virtual environment
- Basic Git workflow
- Project folder organization
- Importance of project documentation

### What I implemented
- Created project structure
- Initialized Git repository
- Connected local project to GitHub

### Next milestone
Dataset selection and exploratory data analysis.

## Experiment 1 — Logistic Regression + TF-IDF

Dataset:
OLID

Samples after duplicate removal:
13,207

Feature representation:
TF-IDF

Model:
Logistic Regression

Train/Test:
80/20 stratified split

Results:
Accuracy: 0.76

OFF:
Precision: 0.78
Recall: 0.38
F1-score: 0.51

Confusion Matrix:
[[1668, 95],
 [545, 334]]

Observation:
The baseline model has relatively high precision for the OFF
class but low recall. It misses a substantial number of
offensive examples.