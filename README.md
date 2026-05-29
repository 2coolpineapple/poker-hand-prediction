# 🃏 Poker Hand Prediction

A **Machine Learning project** that predicts the category of a poker hand based on the 5 cards dealt to a player. Built using Python and Jupyter Notebook, trained on the **UCI Poker Hand Dataset**.

---

## 📌 About

The goal of this project is to classify a poker hand into one of 10 categories (e.g., Nothing, One Pair, Two Pair, Flush, Royal Flush, etc.) using machine learning classification algorithms. Each hand is represented by the suit and rank of 5 cards as input features.

---

## 🂠 Poker Hand Classes

| Class | Hand             |
|-------|------------------|
| 0     | Nothing          |
| 1     | One Pair         |
| 2     | Two Pairs        |
| 3     | Three of a Kind  |
| 4     | Straight         |
| 5     | Flush            |
| 6     | Full House       |
| 7     | Four of a Kind   |
| 8     | Straight Flush   |
| 9     | Royal Flush      |

---

## 🛠️ Tech Stack

| Tool              | Purpose                        |
|-------------------|--------------------------------|
| Python            | Core language                  |
| Jupyter Notebook  | Development environment        |
| Pandas            | Data loading & manipulation    |
| NumPy             | Numerical operations           |
| Scikit-learn      | ML models & evaluation         |
| Matplotlib/Seaborn| Data visualization             |

---

## 📁 Project Structure

```
poker-hand-prediction/
│
├── pokerhandpred.ipynb          # Main Jupyter Notebook (EDA + Model training)
├── poker_hand_train_true.csv    # Training dataset (CSV format)
├── poker_hand_train_true.data   # Training dataset (raw format)
├── poker_hand_test.data         # Test dataset
├── data                         # Additional data file
├── test                         # Additional test file
├── .gitignore
└── README.md
```

---

## 📊 Dataset

This project uses the **UCI Poker Hand Dataset**.

- Each record represents one poker hand of 5 cards
- Each card is described by 2 attributes: **Suit** (1–4) and **Rank** (1–13)
- Total of **10 input features** (5 cards × 2 attributes)
- **1 output label** — the poker hand class (0–9)

**Dataset source:** [UCI Machine Learning Repository – Poker Hand Dataset](https://archive.ics.uci.edu/ml/datasets/Poker+Hand)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/2coolpineapple/poker-hand-prediction.git
   cd poker-hand-prediction
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook pokerhandpred.ipynb
   ```

4. Run all cells to see data exploration, model training, and evaluation results.

---

## 🧠 ML Workflow

1. **Data Loading** — Load training and test datasets
2. **Exploratory Data Analysis (EDA)** — Understand class distribution and feature relationships
3. **Preprocessing** — Handle class imbalance, feature scaling if needed
4. **Model Training** — Train classification models (e.g., Decision Tree, Random Forest, KNN)
5. **Evaluation** — Accuracy, Confusion Matrix, Classification Report
6. **Prediction** — Predict hand categories on the test set

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
