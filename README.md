
# Machine Learning-Based Maintenance Performance Clustering

## 📌 Project Overview

This project applies **Unsupervised Machine Learning using the K-Means Clustering algorithm** to analyze maintenance performance at PT Semen Indonesia. The analysis aims to identify distinct maintenance patterns among planner groups based on three key variables: maintenance frequency, total maintenance costs, and average task duration.

By applying clustering techniques, this project explores differences in maintenance activities and generates analytical insights to support maintenance performance evaluation, resource allocation, and data-driven operational planning.

This project was originally developed as a **Business Intelligence course final project** and subsequently published as a research paper in *Innovation in Research of Informatics (INNOVATICS)*.

## 🎯 Project Objectives

- Analyze maintenance data to understand patterns and characteristics across planner groups.
- Apply K-Means Clustering to segment planner groups based on maintenance performance indicators.
- Determine the optimal number of clusters using the Elbow Method and Silhouette Score.
- Generate insights to support maintenance performance evaluation and operational decision-making.

## 📊 Dataset Description

The analysis uses three main variables representing maintenance activities:

| Variable | Description |
|---|---|
| Maintenance Frequency | Number of maintenance activities |
| Total Maintenance Costs | Accumulated maintenance costs |
| Average Task Duration | Average time required to complete maintenance tasks |

## ⚙️ Methodology

The project follows these analytical steps:

1. **Data Preprocessing** – Prepare and organize the maintenance dataset for analysis.
2. **Exploratory Data Analysis (EDA)** – Explore data distributions, characteristics, and relationships among variables.
3. **Feature Selection** – Select relevant maintenance indicators for clustering.
4. **Clustering Evaluation** – Apply the Elbow Method and Silhouette Score to determine the optimal number of clusters.
5. **K-Means Clustering** – Group maintenance planner data based on similarities in their maintenance characteristics.
6. **Cluster Interpretation** – Analyze and interpret the resulting clusters to identify maintenance performance patterns.

## 📈 Clustering Results

The K-Means algorithm identified **two distinct clusters**, consisting of 40 maintenance planner groups in total.

| Cluster | Number of Groups | Characteristics |
|---|---:|---|
| Cluster 1 | 29 | Relatively lower maintenance frequency, total costs, and average task duration |
| Cluster 2 | 11 | Relatively higher maintenance frequency, total costs, and average task duration |

The results indicate differences in maintenance activity patterns across planner groups, providing a basis for further operational evaluation.

## 💡 Key Insights

- Identified two distinct maintenance performance groups based on three selected indicators.
- Revealed differences in maintenance frequency, accumulated costs, and average task duration.
- Provided an analytical perspective on maintenance workload and cost characteristics across planner groups.

## 🏆 Project Outcomes

The project demonstrated how K-Means Clustering can transform industrial maintenance data into meaningful analytical insights. The findings provide a basis for maintenance performance evaluation, resource allocation, and data-driven maintenance planning.

## 🛠️ Tools & Technologies

- **Programming Language:** Python
- **Machine Learning:** K-Means Clustering
- **Analytical Techniques:** Exploratory Data Analysis, Elbow Method, Silhouette Score
- **Project Domain:** Business Intelligence & Industrial Analytics

## 📚 Research Publication

This project was developed into a published research paper:

**Enhancing Maintenance Efficiency Through K-Means Clustering at PT Semen Indonesia**

- **Journal:** Innovation in Research of Informatics (INNOVATICS)
- **Volume:** 6
- **Issue:** 2
- **Year:** 2024
- **Pages:** 73–80

## 👨‍💻 Author

**Helga Fadhil Raditya**

Data Science Graduate | Machine Learning | Data Analytics | Business Intelligence
