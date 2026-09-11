# Decision Tree Classification using ID3

## 📌 Project Description

This project implements a Decision Tree Classification algorithm using the **ID3 approach** with Entropy as the splitting criterion.

The model is trained on a Play Tennis dataset to predict whether tennis can be played based on weather conditions.

## 🎯 Objectives

* Load the Play Tennis dataset.
* Encode categorical attributes.
* Split the dataset into training and testing data.
* Create a Decision Tree using Entropy.
* Train and evaluate the classification model.
* Visualize the decision tree.
* Predict the outcome for test data.

## 📂 Dataset

**File:** `play_tennis_dataset.csv`

The dataset contains weather-related attributes and a target variable:

| Attribute   | Description           |
| ----------- | --------------------- |
| Day         | Day identifier        |
| Outlook     | Weather outlook       |
| Temperature | Temperature condition |
| Humidity    | Humidity condition    |
| Wind        | Wind condition        |
| Play Tennis | Target variable       |

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## ⚙️ Algorithm

### ID3 Decision Tree

ID3 is a decision tree algorithm that uses Entropy to select the best attribute for splitting the dataset.

The model is created using:

```python
DecisionTreeClassifier(criterion="entropy")
```

### Data Preprocessing

* The `Day` column is removed because it is an identifier.
* Categorical features are encoded using `LabelEncoder`.
* The target variable `Play Tennis` is also encoded.
* The dataset is split into training and testing sets.

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## 🌳 Decision Tree Visualization

The trained decision tree is visualized using Matplotlib and Scikit-learn's `plot_tree()` function.

The visualization displays:

* Feature names
* Decision rules
* Entropy values
* Class predictions

## 🚀 How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

3. Place `play_tennis_dataset.csv` in the project folder.

4. Open the Jupyter Notebook.

5. Run the code cells in order.

## 📁 Project Structure

```text
Decision-Tree-ID3/
│
├── play_tennis_dataset.csv
├── PROGRAM 4(1).ipynb
└── README.md
```

## 👨‍💻 Author

**Adwaith Krishna MH**

Class: R3AI

## 📜 License

This project is created for educational purposes.
