# SMS Spam Classifier

A Machine Learning web application that classifies SMS/Email messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) and Machine Learning techniques.

## Features

* Detects spam messages in real-time
* Text preprocessing using NLTK
* TF-IDF Vectorization
* Multiple Machine Learning models evaluated
* Interactive Streamlit Web Interface
* High precision spam detection

## Tech Stack

* Python
* Streamlit
* Scikit-Learn
* NLTK
* NumPy
* Pandas
* Matplotlib
* Seaborn

## Project Structure

```text
SMS-spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## Project Workflow

### 1. Data Cleaning

* Removed unnecessary columns
* Renamed columns
* Handled duplicate values
* Checked for missing data

### 2. Exploratory Data Analysis (EDA)

* Analyzed Spam vs Ham distribution
* Studied message lengths and patterns
* Generated character, word, and sentence statistics
* Visualized important insights

### 3. Text Preprocessing

* Lowercase conversion
* Tokenization
* Removal of stopwords and punctuation
* Stemming using Porter Stemmer

### 4. Feature Engineering

* TF-IDF Vectorization
* Character count feature
* Word count feature
* Sentence count feature

### 5. Model Building

Trained and compared multiple machine learning models:

* Multinomial Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* Extra Trees Classifier
* Gradient Boosting
* AdaBoost
* XGBoost

### 6. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision Score
* Confusion Matrix

### 7. Improvements

* Tuned TF-IDF using `max_features`
* Tested additional numerical features
* Applied feature scaling
* Implemented Voting Classifier
* Implemented Stacking Classifier
* Selected the best-performing model based on accuracy and precision

## Installation

1. Clone the repository

```bash
git clone <repository-url>
cd SMS-spam-classifier
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
streamlit run app.py
```

## Example

Input:

```text
Congratulations! You have won a free lottery ticket. Claim now!
```

Output:

```text
SPAM
```

## Author

**Kush Singh**
Computer Science & Engineering Student
