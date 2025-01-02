# Spam Message Classification

## Overview
This repository contains a Jupyter Notebook designed to classify messages as either **spam** or **ham** (not spam). The notebook demonstrates the process of preparing data, analyzing it, and applying machine learning techniques to achieve accurate message classification.

---

## Features
- **Data Loading and Preprocessing**:
  - Loads a dataset of messages from a TSV file.
  - Prepares and cleans the data for analysis.
- **Exploratory Data Analysis (EDA)**:
  - Provides insights into the dataset through visualization and statistics.
  - Includes metrics like message length and punctuation usage.
- **Feature Engineering**:
  - Extracts relevant features from the data to improve model performance.
- **Model Training and Evaluation**:
  - Trains machine learning models on the data.
  - Evaluates models using accuracy, precision, recall, and F1-score.
- **Final Deployment**:
  - Demonstrates prediction capabilities on new unseen data.

---

## Getting Started

### Prerequisites
To run this notebook, ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- Required Python libraries (see below).

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/spam-message-classification.git
   cd spam-message-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Dataset
The dataset used is `spam.tsv`, which contains:
- `label`: Indicates whether the message is **spam** or **ham**.
- `message`: The text of the message.
- `length`: Length of the message.
- `punct`: Count of punctuation marks in the message.

Place the dataset in the same directory as the notebook or update the path in the code accordingly.

---

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Spam_Message_Classification.ipynb
   ```
2. Execute cells sequentially to:
   - Load and explore the data.
   - Preprocess and clean the data.
   - Train and evaluate the classification model.
   - Test the model on new messages.

---

## Libraries Used
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Scikit-learn**: For machine learning model implementation.

Install these libraries using:
```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## Results
- Accuracy: Achieved high accuracy on the test set.
- Metrics: Detailed evaluation metrics, including precision, recall, and F1-score, are provided in the notebook.




