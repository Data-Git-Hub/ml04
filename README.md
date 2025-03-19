# ml04

## Introduction
The objective of the Mushroom Classification problem is to predict whether a mushroom is edible or poisonous based on its physical and chemical characteristics. The dataset includes descriptions of 23 species of gilled mushrooms from the Agaricus and Lepiota families. These mushrooms are classified as definitely edible or definitely poisonous (including those with unknown edibility, which were grouped into the poisonous category). <br>

## Overview
Businesses and organizations must understand the relationships between different factors to make better decisions. <br>
For example, a company may want to predict a car's fuel efficiency based on its weight and engine size or estimate home prices based on square footage and location. <br>
Regression analysis helps identify and quantify these relationships between numerical features, providing insights that can be used for forecasting and decision-making. <br>

This project demonstrates your ability to apply regression modeling techniques to a real-world dataset. You will: <br>
- We use three common classification models in this lab. <br>

- Decision Tree Classifier (DT)

A Decision Tree splits data into smaller groups based on decision rules (like "is height greater than 150 cm?"). It’s like a flowchart, where each decision point leads to another question until a final classification is reached. <br>

Strengths: Easy to interpret and fast to train. <br>
Weaknesses: Can overfit if the tree becomes too complex. <br>

- Support Vector Machine (SVM) 

A Support Vector Machine tries to find the "best boundary" (a hyperplane) that separates data into classes. It works well with complex data and small datasets. <br>

Strengths: Effective when there is a clear margin of separation between classes. <br>
Weaknesses: Computationally expensive for large datasets. <br>

- Neural Network (NN)

A Neural Network is inspired by how human brains process information. It consists of layers of interconnected "neurons" that process input data and adjust based on feedback. <br>

Strengths: Can handle complex patterns and non-linear relationships.<br>
Weaknesses: Needs more data and tuning to avoid overfitting.<br>


When trying to classify data, using three (or more) models can help:<br>
Decision Trees illustrate how individual features contribute to classification.<br>
SVMs are good at finding complex boundaries.<br>
Neural Networks are good at learning patterns from complex data. <br>

## Dataset 
UCI Machine Learning Repository Link: https://archive.ics.uci.edu/dataset/73/mushroom <br>

---

## Professional Python Setup and Workflow
We follow professional Python practices. 
Full instructions are available at <https://github.com/denisecase/pro-analytics-01/>. 
A concise version is provided at [WORKFLOW_GUIDE.md](./docs/WORKFLOW_GUIDE.md)

**Important:** VS Code + Pylance may fail to recognize installed packages in Jupyter notebooks.  
See the above guides for troubleshooting and solutions.  

---
Start your notebook professionally with:
- a single top-level title
- your name (or alias)
- the date
- a brief introduction that describes the problem and the dataset.
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn, etc.)
- Present your work in clearly numbered second-level and third-level headings

## Project Outline
Machine learning projects follow a structured approach.
We will use this approach throughout the course. 

### Section 1: Load and Explore the Data

### Section 2. Data Exploration and Preparation

### Section 3. Feature Selection and Justification

### Section 4. Train a Classification Model (Decision Tree)

### Section 5. Compare Alternative Models (SVC, NN)

### Section 6. Final Thoughts & Insights

### Section 7:

| Model Type           | Case   | Features Used            | Accuracy   | Precision   | Recall   | F1-Score   | Notes   |
|:---------------------|:-------|:-------------------------|:-----------|:------------|:---------|:-----------|:--------|
TBD.
---

## README.md (Required)

Include a professional README.md. Include:
- a personalized title
- an introduction to your project
- a clickable link to your notebook file.
- Instructions on how to set up your virtual environment and run your notebook locally.
   
If starting with an assignment README, remove the parts you do not need to present your project.
---

## Repository Checklist

Verify your repository contains:

- [ ] Useful .gitignore (that keeps .venv out of GitHub)
- [ ] Professional Jupyter Notebook with numbered sections   
- [ ] Useful README.md
- [ ] Useful requirements.txt

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

## Version History
- P4 Sect - 4.1 
- P4 Sect - 4.0
- P4 Sect - 3.0 - Add models folder for recall options
- P4 Sect - 2.5
- P4 Sect - 2.4
- P4 Sect - 2.3 - Rearrange Section 2
- P4 Sect - 2.2
- P4 Sect - 2.1
- P4 Sect - 1.2 - Delete files from Data folder, Add Repo Link to UCI, Mod README.md 
- P4 Sect - 1.1 - Title Change
- P4 Sect - 1.0
- P4 Init - 0.4 - Add Intro, Data folder, dataset, dataset convert .csv
- P4 Init - 0.3
- P4 Init - 0.2 - Add README.md framework
- P4 Init - O.1 - Add requirements.txt
- P4 Init - 0.0 <br>
## Test History  
- <br>
