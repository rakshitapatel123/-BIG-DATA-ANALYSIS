# BIG-DATA-ANALYSIS
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: RAKSHITA ISHWAR PATEL
*INTERN ID*: CT04DY2849
*DOMAIN*: DATA ANALYTICS
*DURATION*: 4 WEEKS
*MENTOR*:  NEELA SANTHOSH KUMAR

🚖 Big Data Taxi Trip Analysis

This project analyzes a NYC-style taxi trip dataset (bigdata_sample.csv) using Pandas and Matplotlib.
The goal is to extract insights and create visualizations for better understanding of big data.

📌 Features of the Project

Trip Distance Analysis

Distribution of trip distances.

Helps identify if trips are short (within city) or long (outskirts).

Passenger Count Analysis

Bar chart of passenger counts (1–6).

Shows whether most trips are solo rides or group rides.

Payment Type Distribution

Pie chart of payment methods (CRD = Card, CSH = Cash, etc.).

Helps understand customer preferences for payments.

Fare vs. Tip Relationship

Scatter plot between fare amount and tip amount.

Shows tipping behavior relative to the fare.

Revenue Insights

Average fare, tip, and total revenue per trip.

Useful for business decision-making.

📂 Project Structure
bigdata_analysis/
│── bigdata_sample.csv       # Dataset (20,000 taxi trips)
│── analysis_pandas.py       # Analysis using Pandas plotting
│── analysis_matplotlib.py   # Analysis using Matplotlib
│── README.md                # Project Documentation

⚙️ Requirements

Install dependencies before running the scripts:

pip install pandas matplotlib

▶️ How to Run
1. Using Pandas (quick analysis)
python analysis_pandas.py

2. Using Matplotlib (detailed control)
python analysis_matplotlib.py


Both scripts will generate charts and print insights in the terminal.

📊 Sample Insights from Dataset

Most trips are short distance (0–5 miles).

Solo passengers (1 person) dominate the trips.

Credit Card (CRD) is the most popular payment method.

On average:

Fare: $9.36

Tip: $0.97

Total Amount: $10.44

🎯 Conclusion

This project demonstrates how Python libraries (Pandas + Matplotlib) can be used to analyze big datasets and create meaningful visualizations.
It is a foundational step towards Big Data Analytics using scalable tools like PySpark and Dask.
