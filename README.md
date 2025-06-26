# 🎬 IMDb Movie Rating Prediction

This project aims to predict IMDb movie ratings using machine learning techniques. It is built using Python and leverages movie metadata such as **runtime**, **votes**, **genre**, and **gross collection** to predict a movie's IMDb rating. The dataset focuses on Indian movies and is processed, visualized, and modeled in a Jupyter notebook.

---

## 📌 Table of Contents

- [📌 Table of Contents](#-table-of-contents)
- [📊 Project Overview](#-project-overview)
- [📁 Dataset Description](#-dataset-description)
- [🧪 Workflow and Methodology](#-workflow-and-methodology)
- [📉 Model Evaluation](#-model-evaluation)
- [📈 Visualizations](#-visualizations)
- [🧰 Technologies Used](#-technologies-used)
- [🚀 How to Run the Project](#-how-to-run-the-project)
- [💡 Future Improvements](#-future-improvements)
- [📄 License](#-license)

---

## 📊 Project Overview

**Objective**: Predict IMDb movie ratings using regression models trained on Indian movie metadata.

IMDb ratings are a key metric used by audiences and platforms to evaluate movies. Predicting them using features such as votes, genre, runtime, and director gives us insight into what drives a good rating.

---

## 📁 Dataset Description

- **File**: `IMDb_Movies_India.csv`
- **Encoding**: `latin1` (to handle special characters)
- **Target Variable**: `IMDB Rating`

### 🧾 Key Features

| Feature         | Description                                |
|----------------|--------------------------------------------|
| Movie Name      | Title of the movie                         |
| Director        | Movie director                             |
| Star Cast       | Lead actors                                |
| Genre           | Movie genre                                |
| Language        | Primary language                           |
| Country         | Country of production                      |
| Runtime         | Duration of the movie                      |
| Votes           | Number of user votes on IMDb              |
| Gross Collection| Revenue collected at the box office       |
| Release Date    | Date of release                            |

---

## 🧪 Workflow and Methodology

### 🔹 1. Data Preprocessing

- Loaded dataset with proper encoding
- Handled missing values
- Cleaned and converted runtime to numerical
- Encoded categorical variables (genre, director, etc.) using `LabelEncoder`

### 🔹 2. Exploratory Data Analysis (EDA)

- Distribution of IMDb ratings
- Top 10 directors and actors
- Votes vs Rating and Gross vs Rating
- Correlation heatmap

### 🔹 3. Model Building

- Train/Test Split: 80% training, 20% testing
- Model Used: **Linear Regression**
- Selected Features:
  - Encoded Genre
  - Runtime
  - Votes
  - Gross Collection
  - Encoded Director, Star Cast

### 🔹 4. Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score (Coefficient of Determination)

---

## 📉 Model Evaluation

The **Linear Regression model** provided the following metrics (example values):

- 📈 **R² Score**: `0.73` (shows good variance explanation)
- 📉 **MSE**: Lower is better; indicates prediction error

You can try multiple models and compare their performance.

---

## 📈 Visualizations

- 📊 IMDb Rating distribution
- 🎥 Top 10 Directors and Actors by Average Rating
- 💰 Gross Collection vs IMDb Rating
- 🗳️ Votes vs IMDb Rating
- 🔥 Heatmap of Feature Correlation
- 🧮 Boxplots and Pairplots

---

## 🧰 Technologies Used

- **Python 3.x**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn** (for EDA & plots)
- **Scikit-learn** (for model building)

---

Author 
Vijayan Naidu
Fergusson College (Autonomous) Pune
