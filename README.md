Hiring Prediction using Decision Trees & Random Forest

This project demonstrates how to use Decision Trees and Random Forests from scikit-learn
 to predict whether a job candidate will be hired based on their profile data.

We train a model on a dataset of candidate features such as experience, employment status, education level, and internship history, then visualize the decision tree and test predictions on sample candidates.


🚀 Features

Data preprocessing with Pandas & NumPy

Encode categorical variables (Yes/No, Education Levels) into numerical values

Build a Decision Tree Classifier and visualize it with Graphviz & pydotplus

Train a Random Forest Classifier for more robust predictions

Test predictions on candidate profiles

📂 Project Structure
├── hires.csv              # Sample dataset (replace with your own)
├── decision_tree.py       # Main Python script


📊 Dataset

The dataset (hires.csv) contains job candidate information with the following columns:

Years Experience	Employed?	Previous Employers	Level of Education	Top-tier school	Interned	Hired
10	Y	4	BS	N	N	Y

Target column: Hired (1 = Yes, 0 = No)

Features used: First 6 columns

Example Output

Decision Tree Visualization
A PNG image of the decision tree will be generated showing the splitting criteria.

Random Forest Predictions

[1]
[0]


First prediction: An employed 10-year veteran → Likely Hired

Second prediction: An unemployed 10-year veteran → Not Hired


📈 Models Used

Decision Tree Classifier

Simple interpretable model

Visualized using Graphviz

Random Forest Classifier

Ensemble of decision trees

More robust and accurate
