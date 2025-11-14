📊 Highest-Grossing Mobile Games — Full Data Analysis Project (2025)
An end-to-end data analysis project exploring revenue, genre dynamics, publisher performance, and market forces behind the highest-grossing mobile games ever released.

Built using Python (pandas, matplotlib, seaborn) inside a Jupyter Notebook as part of the Code Institute – Individual Project (2025).
This repository demonstrates professional analytical workflow, storytelling with data, and industry-level documentation.

📚 Table of Contents:

1.) 📊 Project Overview

2.) 📁 Repository Structure

3.) 🧹 1. Data Cleaning & Preparation

4.) 🔍 2. Exploratory Data Analysis (EDA)

5.) 📈 3. Visualisation

6.) 7.) 🧠 Key Insights

7.) 🛠 Technologies Used

8.) ▶ How to Run the Project

9.) 📦 Deliverables

10.) 🚀 Next Steps / Future Enhancements

11.) 📬 Contact

1.) 📊 Project Overview:
_____________________________________________________________________________________________________________________________________________

Mobile gaming is the largest sector in the global games industry, generating billions annually.
This project answers critical analytical questions:

🎯 Which games generate the most global revenue?

🎯 Which genres dominate the market and why?

🎯 Which publishers consistently produce high-performing titles?

🎯 Do older games still generate significant revenue?

🎯 What patterns exist across genre, platform, and release year?

2.) 📁 Repository Structure:
_____________________________________________________________________________________________________________________________________________

<img width="1138" height="242" alt="image" src="https://github.com/user-attachments/assets/38e16953-de25-4be9-b515-7d0910297166" />

3.) 🧹 1. Data Cleaning & Preparation:
_____________________________________________________________________________________________________________________________________________

The dataset required multiple preparation steps before analysis:

✔ Standardised Column Names

Removed whitespace

Normalised casing

Ensured consistent schema (Global_Sales instead of mixed variants)

✔ Cleaned Revenue Values

Converted currency-formatted strings ($14,657,500,000) into integers for analysis.

✔ Extracted Release Year

Converted release dates into a usable Year column.

✔ Feature Engineering

Two critical new features were created:

1️⃣ primary_genre

Extracts the first genre listed in genre_tags and standardises it.

2️⃣ genre_count

Counts how many genres each game spans — useful for studying genre complexity.

✔ Missing Data Handling

Checked and managed NaN values in genre data.

4.) 🔍 2. Exploratory Data Analysis (EDA):
_____________________________________________________________________________________________________________________________________________

The notebook contains clear, structured analysis covering:

🎮 Top-grossing games

Ranking games by revenue with publisher and year context.

🏷 Genre dynamics

Identifying the dominant genres and hybrid genre combinations.

🏢 Publisher performance

Which publishers generate the most revenue, and how frequently they appear in top charts.

📅 Release year trends

Understanding whether older games still achieve high revenue.

5.) 📈 3. Visualisation:
_____________________________________________________________________________________________________________________________________________

All visuals are produced using Matplotlib and Seaborn, including:

- Revenue distribution histograms

- Bar charts of top publishers

- Genre frequency plots

- Release year trend plots

- Feature-engineered genre insights

These plots support the final conclusions through clean, readable visuals.

6.) 🧠 Key Insights:
_____________________________________________________________________________________________________________________________________________

Here are the headline findings from the analysis:

⭐ 1. A small handful of publishers dominate

Tencent, Supercell, Mixi, and Niantic account for a disproportionate share of global revenue.

⭐ 2. Genre hybrids win

Games blending RPG, Strategy, Puzzle, or MMO mechanics outperform single-genre games.

⭐ 3. Older games remain blockbuster earners

Clash of Clans (2012) and Monster Strike (2013) still generate massive revenue.

⭐ 4. Multi-genre games appeal to larger audiences

Higher genre_count correlates with broader appeal and higher revenues.

⭐ 5. Mobile gaming success favours long-term live-service models

Frequent updates and events keep revenue high across many years.

7.) 🛠 Technologies Used:
_____________________________________________________________________________________________________________________________________________

Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

GitHub

8.) ▶ How to Run the Project:
_____________________________________________________________________________________________________________________________________________

Clone the repository:

git clone https://github.com/acepag/AP---Code-Institute---Individual-Project-2025-.git

Install packages:

pip install pandas numpy matplotlib seaborn

Open the notebook:

jupyter notebook

Run analysis.ipynb top to bottom.

9.) 📦 Deliverables:
_____________________________________________________________________________________________________________________________________________

This project includes:

✔ A fully cleaned dataset
✔ A complete EDA Jupyter notebook
✔ Feature engineering (primary_genre, genre_count)
✔ Multiple professional visualisations
✔ A structured GitHub repository
✔ A high-quality README.md

Everything aligns with best practices for portfolio-ready data analysis projects.

10.) 🚀 Next Steps / Future Enhancements:
_____________________________________________________________________________________________________________________________________________

Although this project is complete, potential extensions include:

🔹 Machine Learning Models
Predict revenue based on publisher, genre, and release year.

🔹 Sentiment Analysis
Analyse user reviews (App Store / Google Play) to correlate player sentiment with revenue.

🔹 Time-Series Forecasting
Predict revenue growth trends for top games.

🔹 Interactive Dashboards
Build dashboards in Power BI, Tableau, or Plotly Dash for dynamic exploration.

🔹 Multi-dataset merging
Combine with advertising data, player spending habits, or global downloads for deeper insights.

These enhancements could transform the project into a full analytics case study.

11.) 📬 Contact:
_____________________________________________________________________________________________________________________________________________

If you’d like to discuss the work or explore collaborations:

GitHub: https://github.com/acepag

Email: acepag@gmail.com
