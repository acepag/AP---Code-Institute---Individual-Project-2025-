# 📊 Highest-Grossing Mobile Games — Full Data Analysis Project (2025)
An end-to-end data analysis project exploring revenue, genre dynamics, publisher performance, and market forces behind the highest-grossing mobile games ever released.

Built using Python (pandas, matplotlib, seaborn) inside a Jupyter Notebook as part of the Code Institute – Individual Project (2025).
This repository demonstrates professional analytical workflow, storytelling with data, and industry-level documentation.

## 📚 Table of Contents:

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

Before exploring the notebook, analysis, or visual outputs, it’s important to understand how the project is organised. 

A clear structure ensures that anyone — from mentors to future collaborators — can quickly navigate the codebase, find the right files, and understand the workflow behind the analysis.

The following layout provides a high-level overview of all folders, datasets, and core components included in this project.

<img width="1138" height="242" alt="image" src="https://github.com/user-attachments/assets/38e16953-de25-4be9-b515-7d0910297166" />

3.) 🧹 1. Data Cleaning & Preparation:
_____________________________________________________________________________________________________________________________________________

This section outlines all preprocessing steps taken to ensure the dataset is accurate, consistent, and ready for analysis. 

It covers the full workflow from initial inspection to final, analysis-ready data.

✔ Standardised Column Names

- Removed whitespace

- Normalised casing

- Ensured consistent schema (Global_Sales instead of mixed variants)

✔ Cleaned Revenue Values

- Converted currency-formatted strings ($14,657,500,000) into integers for analysis.

✔ Extracted Release Year

- Converted release dates into a usable Year column.

✔ Feature Engineering

- Two critical new features were created:

1️⃣ primary_genre

- Extracts the first genre listed in genre_tags and standardises it.

2️⃣ genre_count

- Counts how many genres each game spans — useful for studying genre complexity.

✔ Missing Data Handling

- Checked and managed NaN values in genre data.

4.) 🔍 2. Exploratory Data Analysis (EDA):
_____________________________________________________________________________________________________________________________________________

The EDA section provides a structured, insight-driven walkthrough of the dataset.

Rather than simply visualising numbers, the notebook focuses on uncovering meaningful patterns, relationships, and trends that shape the global games market.

Each visual has been intentionally designed to highlight why the data matters — not just what it shows.

The analysis covers:

🎮 Top-grossing games

- Ranking games by revenue with publisher and year context.

🏷 Genre dynamics

- Identifying the dominant genres and hybrid genre combinations.

🏢 Publisher performance

Which publishers generate the most revenue, and how frequently they appear in top charts.

📅 Release year trends

Understanding whether older games still achieve high revenue.

5.) 📈 3. Visualisation:
_____________________________________________________________________________________________________________________________________________

This section translates raw data into clear, interpretable visuals.

Each chart is intentionally designed to highlight patterns, outliers, and structural behaviour in the games market.

All visuals are produced using Matplotlib and Seaborn, including:

- Revenue distribution histograms

- Bar charts of top publishers

- Genre frequency plots

- Release year trend plots

- Feature-engineered genre insights

These plots support the final conclusions through clean, readable visuals.

6.) 🧠 Key Insights:
_____________________________________________________________________________________________________________________________________________

This section summarises the most important patterns uncovered in the data.

These insights highlight market behaviour, genre performance, and sales dynamics — giving a clear picture of what drives success in the global games landscape.

⭐ 1. A small handful of publishers dominate

- Tencent, Supercell, Mixi, and Niantic account for a disproportionate share of global revenue.

⭐ 2. Genre hybrids win

- Games blending RPG, Strategy, Puzzle, or MMO mechanics outperform single-genre games.

⭐ 3. Older games remain blockbuster earners

- Clash of Clans (2012) and Monster Strike (2013) still generate massive revenue.

⭐ 4. Multi-genre games appeal to larger audiences

- Higher genre_count correlates with broader appeal and higher revenues.

⭐ 5. Mobile gaming success favours long-term live-service models

- Frequent updates and events keep revenue high across many years.

7.) 🛠 Technologies Used:
_____________________________________________________________________________________________________________________________________________

This project is built using a modern, data-analysis focused Python stack.

The following tools power the data cleaning, exploration, and visualisation workflows:

Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

GitHub

8.) ▶ How to Run the Project:
_____________________________________________________________________________________________________________________________________________

To make the project easy to reproduce, the repository includes all required files and dependencies.

Follow the steps below to set up the environment, load the dataset, and run the Jupyter notebook without issues:

Clone the repository:

git clone https://github.com/acepag/AP---Code-Institute---Individual-Project-2025-.git

Install packages:

pip install pandas numpy matplotlib seaborn

Open the notebook:

jupyter notebook

Run analysis.ipynb top to bottom.

9.) 📦 Deliverables:
_____________________________________________________________________________________________________________________________________________

This project provides a complete set of outputs that demonstrate the full workflow — from raw data exploration to final insights and visuals.

All deliverables included in the repository are listed below:

✔ A fully cleaned dataset
✔ A complete EDA Jupyter notebook
✔ Feature engineering (primary_genre, genre_count)
✔ Multiple professional visualisations
✔ A structured GitHub repository
✔ A high-quality README.md

Everything aligns with best practices for portfolio-ready data analysis projects.

10.) 🚀 Next Steps / Future Enhancements:
_____________________________________________________________________________________________________________________________________________

While the current project successfully meets its objectives, there are several opportunities to expand its scope, deepen insights, and enhance functionality.

Future improvements could include:

🔹 Machine Learning Models
- Predict revenue based on publisher, genre, and release year.

🔹 Sentiment Analysis
- Analyse user reviews (App Store / Google Play) to correlate player sentiment with revenue.

🔹 Time-Series Forecasting
- Predict revenue growth trends for top games.

🔹 Interactive Dashboards
- Build dashboards in Power BI, Tableau, or Plotly Dash for dynamic exploration.

🔹 Multi-dataset merging
- Combine with advertising data, player spending habits, or global downloads for deeper insights.

These enhancements could transform the project into a full analytics case study.

11.) 📬 Contact:
_____________________________________________________________________________________________________________________________________________

If you have any questions, feedback, or would like to discuss this project further, feel free to reach out:

GitHub: https://github.com/acepag

Email: acepag@gmail.com
