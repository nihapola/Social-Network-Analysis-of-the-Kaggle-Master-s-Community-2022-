An AI-driven network analysis of the global Master's degree holders in Kaggle’s Data Science & Machine Learning Survey (2022). This project explores socio-demographic trends, job roles, salary distribution, and machine learning skill networks using graph theory and social network analysis (SNA).

📌 Project Overview:
Master's degrees in AI and Data Science have become increasingly popular worldwide. Using data from the 2022 Kaggle Machine Learning & Data Science Survey, this project explores the network of Master's degree holders by analyzing:
✅ Global Distribution – Which countries have the most Master's degree holders?
✅ Job Roles & Salaries – What are the most common job roles and salaries in ML & AI?
✅ Social Network Analysis (SNA) – How are ML skills distributed across countries?
✅ Community Detection – Are there clusters of countries with similar ML expertise?

🎯 Objective:
Perform demographic and occupational analysis of Kaggle users with a Master's degree.
Use network graphs to analyze ML skill connectivity across countries.
Apply social network analysis (SNA) to detect skill-based communities.
Identify the most influential countries in the ML ecosystem using centrality measures.
Use hypothesis testing to examine if high Master's degree production leads to stronger ML networks.

📊 Data Source:
2022 Kaggle Machine Learning & Data Science Survey
📅 Survey conducted: September 16 – October 16, 2022
📊 23,997 responses collected globally
🌍 Covers demographics, job roles, ML skills, and salary trends

🛠️ Tools & Technologies:
Programming Languages: Python, R

Key Libraries:
Data Processing & Visualization: pandas, ggplot2, dplyr, tidyverse, matplotlib, seaborn
Network Analysis & Graphs: igraph, networkx, shapely, Gephi
Machine Learning: scikit-learn, XGBoost, LightGBM, statsmodels
Statistical Analysis: psych, statsmodels, hypothesis testing

📌 Methodology:
1️⃣ Data Preparation & Cleaning
Extracted relevant socio-demographic features from 23,997 Kaggle responses.
Filtered dataset to focus only on Master's degree holders.
Transformed categorical variables into ordinal & numerical formats.
Engineered a binary ML skills matrix for each country.

2️⃣ Exploratory Data Analysis (EDA):
Country-wise analysis: Top Master's degree producing countries.
Job role distribution: Most common ML-related job roles.
Gender analysis: Gender ratio in the Kaggle ML community.

3️⃣ Social Network Analysis (SNA):
Graph construction: Built a bipartite network (Countries ↔ ML Skills).

Network statistics:
Node degree – Which countries have the most diverse ML skill sets?
Graph density – How interconnected is the ML skills network?
Community detection – Do skill clusters exist across regions?
Hypothesis testing: Does having a high number of Master's holders correlate with stronger ML skill networks?

🔍 Key Findings:
📌 1. Countries Producing the Most Master's Degree Holders in ML & AI

🌍 Top 5 countries: India, USA, Brazil, Nigeria, Pakistan:
India has the highest number of Master's degree holders, followed by the USA.
📌 2. Most Common Job Roles in the ML & AI Master's Community

🏆 Top roles: Data Scientist & Data Analyst:
📉 Many respondents are still students, explaining missing job roles.
📌 3. Gender Distribution in the ML & AI Master's Community

Male representation is nearly 3x higher than female representation.
Despite AI being a growing field, gender disparity remains significant.
📌 4. Social Network Analysis (SNA) Findings

Countries like India, UK, France, Egypt, and Colombia are highly connected ML skill hubs.
USA does not emerge as a highly connected country, despite its high number of Master's degree holders.
The ML skill network forms a single giant component, indicating global interconnectedness.
Community detection reveals no distinct clusters, suggesting skills are evenly distributed.
📌 5. Hypothesis Testing Conclusion

Having a high number of Master's degree holders does NOT directly imply a strong ML skill network.
Skill connectivity matters more than just the number of graduates.

🚀 Future Enhancements:
🔹 Expand the network model using more survey years to analyze trends over time.
🔹 Incorporate Machine Learning models to predict skill gaps in different regions.
🔹 Deploy an interactive dashboard for real-time exploration of the dataset.
🔹 Analyze salary gaps based on ML skills & country comparisons.

🤝 Contributions
🚀 If you're interested in network science, AI, or social analytics, feel free to fork the repository and contribute! You can help with:

Improving data visualizations & network plots.
Expanding the analysis with deep learning & NLP techniques.
Integrating additional job market & salary datasets.
