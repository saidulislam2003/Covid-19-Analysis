# WHO COVID-19 Data Analysis

## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on the World Health Organization (WHO) COVID-19 dataset. The objective is to understand the dataset, uncover patterns and trends, and gain insights into the global impact of COVID-19.

---

## Dataset Description
The dataset contains information on COVID-19 cases and deaths reported by the WHO, segmented by regions and population. Key columns include:
- **WHO Region**: The region where the data is reported.
- **Cases - cumulative total**: Total confirmed cases.
- **Cases - cumulative total per 100000 population**: Cases normalized per 100,000 population.
- **Cases - newly reported in last 7 days**: Recently reported cases over the past week.
- **Deaths - cumulative total**: Total deaths reported.
- **Deaths - cumulative total per 100000 population**: Deaths normalized per 100,000 population.
- **Deaths - newly reported in last 7 days**: Recently reported deaths over the past week.

---

## Goals of Analysis
1. **Data Cleaning**: Handle missing values and ensure the dataset is ready for analysis.
2. **Exploratory Data Analysis (EDA)**:
   - Univariate Analysis: Explore the distribution of individual columns.
   - Bivariate Analysis: Investigate relationships between two columns, such as cases and deaths.
   - Multivariate Analysis: Analyze correlations and trends involving multiple columns.
3. **Visualization**: Use visual tools like bar charts, scatter plots, and heatmaps to represent insights.
4. **Insights and Observations**: Summarize findings from the analysis.

---

## Tools Used
- **Python Libraries**:
  - `pandas`: For data manipulation and cleaning.
  - `matplotlib` and `seaborn`: For data visualization.
  - `numpy`: For numerical operations.

---

## Steps in the Project
1. **Load and Understand Data**
   - Preview the dataset using `head()` and `info()`.
   - Check for missing values and handle them appropriately.

2. **Data Cleaning**
   - Fill missing values in categorical columns with mode.
   - Drop columns with excessive missing data.
   - Handle numeric columns by imputing with mean/median if necessary.

3. **Exploratory Data Analysis**
   - Analyze distributions of cases and deaths.
   - Investigate relationships between cumulative totals and newly reported data.
   - Visualize regional differences in cases and deaths.

4. **Visualization**
   - Bar charts, line plots, scatter plots, and heatmaps were used to uncover patterns and trends.

5. **Insights**
   - Summarized findings on global and regional COVID-19 impacts.

---

## Key Findings
- Regional differences in the number of cases and deaths.
- Relationships between cumulative and newly reported cases/deaths.
- Death rates compared to total cases.

---

## Future Work
- Perform predictive modeling using machine learning.
- Integrate additional datasets for a broader context (e.g., vaccination rates).

---

## How to Run
1. Clone this repository.
2. Install required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python scripts to perform the analysis.

---

## Author
## Saidul Islam

---

## Acknowledgments
- Data Source: [World Health Organization COVID-19 Dashboard](https://data.who.int/dashboards/covid19/cases?n=c)

---

## License
This project is licensed under the MIT License.

