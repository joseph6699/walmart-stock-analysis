📈 Walmart Stock Price Analysis (1972–2024)
This project applies data mining and visualization techniques to historical stock price data for Walmart Inc. between 1972 and 2024. The analysis focuses on time-series exploration, feature engineering, and predictive modeling using Logistic Regression.

📂 Project Structure
walmart_stock_analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── walmart_stock_analysis.ipynb
├── data/
│ └── walmart_stock_data.csv (or sample)
└── images/
└── (visualizations like line plots, box plots, etc.)

🔍 Project Highlights
Dataset: Daily Walmart stock data (Open, High, Low, Close, Volume)

Features Engineered: Daily Return, Moving Averages (MA5/MA20), 30-day Volatility

Visuals: Line plots, Boxplots, Volatility charts, Correlation heatmap

Modeling: Logistic Regression for price direction classification

Evaluation: Accuracy, confusion matrix, PCA insights

Technologies Used
Python (Jupyter Notebook)

pandas, NumPy

matplotlib, seaborn, Plotly

scikit-learn (Logistic Regression, PCA)

🚀 How to Run
Clone this repository:
git clone https://github.com/your-username/walmart-stock-analysis.git

Navigate into the project:
cd walmart-stock-analysis

(Optional) Create and activate a virtual environment

Install the required packages:
pip install -r requirements.txt

Open the notebook:
jupyter notebook walmart_stock_analysis.ipynb

📊 Dataset
The dataset is sourced from Kaggle:
👉 https://www.kaggle.com/datasets/

Note: A small sample is included in the data/ folder for demonstration. Full data can be downloaded directly from Kaggle.

🧠 Learnings & Insights
Developed skills in feature engineering and time-series visualization

Built a predictive model achieving ~52% accuracy

Understood limitations of logistic regression on sequential financial data

📄 License
This project is for educational purposes under the MIT License.