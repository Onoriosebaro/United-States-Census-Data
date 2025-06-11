# US Census Data Analysis Project
## By Onoriose Baro Monarch

---

This repository contains an exploratory data analysis (EDA) project focused on analyzing United States census data from 2010 to 2015. The project aims to extract meaningful insights regarding population distribution, geographic divisions, and demographic characteristics across various states and counties using Python.

---

## 📊 Project Goals

The primary objectives of this analysis are to answer the following key questions:

-   State with Most Counties: Identify which state in the U.S. has the highest number of counties.
-   Most Populous States (Top Counties): Determine the three most populous states based on the combined population of their three most populous counties in 2010.
-   Most Frequent County Name: Ascertain which county name (interpreted as "city" in some contexts) is most frequently observed across different states.
-   Region with Most Divisions: Identify which Census Region contains the highest number of Census Divisions.

---

## 📁 Data Source

The dataset used for this project is `census.csv`, originating from the U.S. Census Bureau's Population Division (specifically, the CO-EST2015-alldata series).

Key variables utilized in the analysis include:

-   SUMLEV: Geographic summary level (040 for State, 050 for County).
-   REGION: Census Region code.
-   DIVISION: Census Division code.
-   STNAME: State name.
-   CTYNAME: County name.
-   CENSUS2010POP: Resident total population as of April 1, 2010.

---

## 🚀 Methodology

The analysis is performed using Python, leveraging its powerful data science libraries. The key steps involved are:

-   Environment Setup: Importing `pandas` for data manipulation, `numpy` for numerical operations, and `matplotlib.pyplot` along with `seaborn` for data visualization.
-   Data Loading & Initial Inspection: Loading the `census.csv` file into a Pandas DataFrame and creating a working copy. Initial checks for data shape, data types, and missing values are performed.
-   Data Cleaning & Preprocessing: Although the dataset was found to be clean, this step would typically involve handling missing values, correcting data types, and addressing inconsistencies if any were present.
-   Descriptive Statistics: Generating summary statistics to understand the central tendencies and distributions of key numerical features like population, store area, and customer count.
-   Answering Key Questions: Applying filtering, grouping (`groupby`), and aggregation techniques to derive the answers to the project goals listed above.
-   Data Visualization: Creating various plots (e.g., bar charts, heatmaps) to visually represent the findings and enhance understanding.

---

## ✨ Key Findings

The analysis yielded several insightful results:

-   Texas has the most counties in the U.S., with 254 counties.
-   The three most populous states based on the combined population of their three most populous counties in 2010 are: California, Texas, and Florida.
-   The South Census Region contains the highest number of Census Divisions (3 divisions).

These findings highlight significant demographic and geographical patterns within the U.S. census data.

---

## 📈 Visualizations

The project generates several visualizations to illustrate the findings, including:

-   Heatmap showing the absence of missing values.
-   A bar chart visualizing the number of counties for each state.
-   Bar chart showing the top 3 most populous states (based on their top 3 counties).
-   Bar chart showing the number of divisions for each region.


---


## 📧 Contact

For any questions or collaborations, feel free to reach out:

-   Onoriose Baro Monarch
-   LinkedIn: [https://ng.linkedin.com/in/baro-onoriose-ba7184299](https://ng.linkedin.com/in/baro-onoriose-ba7184299)
-   GitHub: [https://github.com/Onoriosebaro](https://github.com/Onoriosebaro)
-   Email: [Baroonoriose@gmail.com](mailto:baroonoriose@gmail.com) 

---

## 📄 License

This project is open-source and available under the MIT License.
