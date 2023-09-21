<h1 align="center"> California Housing Trends </h1>

<p align="center"><img  align="center" src="https://github.com/AmarjeetRoy/California_Housing_Trends/assets/137817362/c267eaa4-2cb9-4367-aeb4-7b6aa89e4d13" width =900px > </p>

# 📊 Project Overview 

Welcome to the Exploratory Data Analysis (EDA) project! This project aims to gain valuable insights from the housing dataset using Python and data analysis libraries. Through thorough analysis, we explore various aspects of the dataset and address specific questions to better understand the data.

<br>

## 🎯 Aims and Problem Statement 

Our primary objectives for this project include:

- **Understanding the dataset's characteristics and structure:** We will start by exploring the dataset's size, data types, and a statistical overview to grasp its fundamental attributes.

- **Cleaning and preprocessing the data:** To ensure the quality of our analysis, we'll correct data types, handle null values, and manage outliers in the dataset.

- **Conducting an in-depth EDA:** We aim to answer key questions about the dataset, uncover patterns, and gain insights into the factors affecting housing values.

<br>

## 📁 Folder Structure 

Here's a detailed look at the project's folder structure:

| **Folder/File**      | **Description**                                          |
|-----------------------|----------------------------------------------------------|
| [`Python File`](Python%20File) 📂       | The root directory of the project containing primary files and notebooks. |
| [`EDA.ipynb`](Python%20File/EDA.ipynb) 📒          | A Jupyter Notebook serving as the core of our analysis, where we perform EDA and document our findings. |
| [`Data`](Data)📂               | A folder dedicated to housing dataset storage and management. |
| [`California housing.csv`](Data) 📄       | The dataset file, "California housing.csv," which serves as the source for our analysis. |

<br>

## 📊 Data Source 

The dataset used in this project, "California Housing Price," was sourced from Kaggle, a renowned platform for data science and machine learning enthusiasts. You can access the dataset by following this link:

[_California Housing Price Dataset on Kaggle_](https://www.kaggle.com/camnugent/california-housing-prices)

The dataset provides valuable information about housing in California and serves as the foundation for our in-depth exploratory data analysis (EDA).

<br>

## 🧹 Data Cleaning and Preprocessing 

In this section, we meticulously prepare the dataset for analysis:

- **Correcting data types:** We ensure that each column has the correct data type, which is crucial for meaningful analysis.

- **Handling null values:** To maintain data integrity, we address missing values using appropriate techniques, such as imputation.

- **Managing outliers:** Outliers can distort our analysis, so we identify and handle them judiciously, preserving the accuracy of our insights.

<br>

## 📈 Exploratory Data Analysis (EDA) in Detail 

Our EDA process is divided into three comprehensive parts:

### 🧐 Part 1: Data Exploration and Cleaning 

In this initial phase, we acquaint ourselves with the dataset:

- **Understanding the dataset:** We explore the dataset's size and basic characteristics, setting the stage for our analysis.

- **Data types and statistics:** We delve into data types for each column and provide statistical summaries to identify initial patterns.

- **Data cleaning:** We meticulously clean columns with incorrect data types and handle null values and outliers to ensure data quality.


### 📊 Part 2: Data Visualization and Analysis 

This phase emphasizes visualizing and analyzing the data:

- **Categorical conversion:** We add a new column by categorizing `median_house_value` to facilitate data distribution analysis.

- **Histograms:** Visual representations of each feature's distribution help us gain insights into their characteristics.

- **Pair plots and correlation heatmaps:** These tools help us understand relationships and correlations between different features.

### 📝 Part 3: Further Data Analysis 

In this advanced analysis phase, we dig deeper into the dataset:

- **Correlation exploration:** We investigate the correlation between `median_house_value` and `median_income` to uncover patterns related to income and house value.

- **Ocean proximity analysis:** We examine how `median_house_value` varies across different `ocean_proximity` categories to understand location-based pricing trends.

- **Age and room analysis:** We explore the relationship between the age of a house and the number of rooms, offering insights into housing trends.

  <br>


## Visualizations 📊

<p align="center">

<!-- Visualization 1 -->
<a href="IMAGE1_LINK">
  <img src="https://github.com/AmarjeetRoy/California_Housing_Trends/assets/137817362/e6f65556-dc26-4d07-b29f-4bef5f1d8301" alt="Visualization 1" width="1000">
</a>

<!-- Visualization 2 -->
<a href="IMAGE2_LINK">
  <img src="https://github.com/AmarjeetRoy/California_Housing_Trends/assets/137817362/14f2e746-f24a-41fe-87b6-7b7dfc5f0daa" alt="Visualization 2" width="1000">
</a>

<!-- Visualization 3 -->
<a href="IMAGE3_LINK">
  <img src="https://github.com/AmarjeetRoy/California_Housing_Trends/assets/137817362/5e6aa6c8-61df-401e-a1e6-36c658c32517" alt="Visualization 3" width="1000">
</a>

<!-- Visualization 4 -->
<a href="IMAGE4_LINK">
  <img src="https://github.com/AmarjeetRoy/California_Housing_Trends/assets/137817362/cc2a681f-9617-4e4d-92a1-6766d4a845f1" alt="Visualization 4" width="1000">
</a>

</p>


<br>


## 🚀 Insights 

Throughout our analysis, we've uncovered several valuable insights, including correlations, patterns, and noteworthy observations that provide a comprehensive understanding of the dataset.
1. **Income-Value Relationship:** A strong positive correlation exists between median income and median house value, indicating that areas with higher incomes tend to have more expensive houses.

2. **Proximity Matters:** Houses located near the ocean are generally more expensive, with prices decreasing as you move farther from the ocean. The order of pricing is 'Island,' 'Near bay,' 'Near ocean,' '<1H Ocean,' and 'Inland.'

3. **Age vs. Rooms:** The age of a house does not significantly impact the number of rooms it has, suggesting that older houses can have as many rooms as newer ones.

4. **Population Density:** Population density decreases as you move closer to the ocean. The order of decreasing density is '<1H OCEAN,' 'INLAND,' 'NEAR OCEAN,' 'NEAR BAY,' and 'ISLAND.'

5. **Household and Room Correlation:** A positive correlation exists between the total number of rooms and the total number of households, indicating that areas with more households tend to have more rooms.

6. **Newer Buildings, Higher Income:** Blocks with newer buildings generally have higher median incomes, while areas with older houses tend to have lower median incomes.

These insights provide valuable information about housing trends and patterns in California, helping to inform decisions related to real estate and urban planning.

<br>




## 🎉 Conclusion of the Project 

### 🤔 Challenges and Solutions 

We encountered various challenges during this project, including data cleaning complexities and the need to handle outliers effectively. To address these challenges, we employed robust data cleaning techniques and outlier management strategies. These challenges strengthened our data analysis skills.

### 📚 Key Learnings 

This project provided valuable learning experiences. We honed our data analysis skills, gained proficiency in using data visualization tools, and deepened our understanding of housing data. Our insights into factors influencing housing prices have real-world applications.

### 🔍 Future Scope 

Looking ahead, there are exciting opportunities to expand this project:

- **Predictive Modeling:** Implementing machine learning models for housing price prediction based on our findings.
- **Incorporating Additional Data:** Integrating more datasets related to housing, demographics, or local amenities for a more comprehensive analysis.
- **Geospatial Analysis:** Exploring the spatial dimension by visualizing housing data on maps and assessing its impact on pricing.

---
