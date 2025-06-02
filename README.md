# 📈 Financial News and Stock Market Analysis Project

This project explores the relationship between financial news sentiment and stock market movements using Python, Git, and various data science libraries. The work is divided into three major tasks: Exploratory Data Analysis, Technical Stock Analysis, and Correlation between News Sentiment and Stock Price Movements.

---

## ✅ Task 1: Git and GitHub + Exploratory Data Analysis (EDA)

### 🔧 Tasks:
- Setting up the Python environment
- Git version control & GitHub workflows
- CI/CD setup (optional)

### 🔨 GitHub Workflow:
- ✅ Create a new GitHub repository for this week's work.
- ✅ Create a branch named `task-1`.
- ✅ Commit work at least **three times daily** with **descriptive messages**.
- ✅ Use Pull Requests to merge branches when ready.

### 📊 Exploratory Data Analysis:

#### 📌 Descriptive Statistics:
- Analyze headline lengths (word and character counts).
- Count articles per publisher.
- Analyze publication dates for frequency trends.

#### 📌 Text Analysis (Topic Modeling):
- Use NLP to extract:
  - Common keywords and phrases
  - Event-related phrases like _“FDA approval”_ or _“price target”_

#### 📌 Time Series Analysis:
- Study publication frequency over time.
- Detect spikes related to market events.
- Analyze publishing time distribution.

#### 📌 Publisher Analysis:
- Identify top publishers and their frequency.
- If email domains are used, extract unique contributors.

---

## 📉 Task 2: Quantitative Analysis using `pynance` and `TaLib`

### 🔨 GitHub Workflow:
- ✅ Merge `task-1` into `main` using a Pull Request.
- ✅ Create a new branch named `task-2`.
- ✅ Commit regularly with clear messages.

### 📈 Technical Analysis:
- Prepare historical stock data.
- Calculate basic technical indicators using:
  - `pynance`
  - `TaLib`
- Visualize trends and patterns in stock prices.

---

## 🔁 Task 3: Correlation Between News and Stock Movements

### 🔨 GitHub Workflow:
- ✅ Merge `task-2` into `main` using a Pull Request.
- ✅ Create a new branch named `task-3`.
- ✅ Commit updates with meaningful descriptions.

### 🛠️ Data Preparation:
- Normalize dates between stock and news datasets.
- Perform sentiment analysis using:
  - `nltk`
  - `TextBlob`

### 📉 Stock Movement Analysis:
- Compute daily returns from stock closing prices.
- Aggregate sentiment scores if multiple headlines exist per day.

### 📊 Correlation Analysis:
- Calculate the **Pearson correlation coefficient** between:
  - Average daily sentiment scores
  - Daily stock returns

---

## 🧰 Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK, TextBlob
- TaLib, pynance
- Git & GitHub

---

## 📌 Project Goals
- Understand how public sentiment in financial news influences stock performance.
- Provide insights useful for traders, analysts, and automated trading strategies.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/desta-getaw/https://github.com/desta-getaw/Predict-Price-Moves-with-News-Sentiment.git

2. Create a virtual environment and install requirements:

pip install -r requirements.txt

3. Run Jupyter Notebooks for each task or scripts in sequence.

