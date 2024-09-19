# Crime Data Analysis Case Study

## Overview
This case study focuses on analyzing a crime dataset to uncover patterns and insights. The analysis includes exploring crime frequency by time, identifying which areas have the most crimes during specific hours, and understanding the distribution of crimes across different victim age groups.

## Dataset Description
The dataset used for this analysis contains information about crimes reported, including:
- **DR_NO**: Report number.
- **Date Rptd**: Date the crime was reported.
- **DATE OCC**: Date the crime occurred.
- **TIME OCC**: Time the crime occurred (in military time).
- **AREA NAME**: Name of the area where the crime occurred.
- **Crm Cd Desc**: Description of the crime code.
- **Vict Age**: Age of the victim.
- **Vict Sex**: Gender of the victim.
- **Vict Descent**: Descent of the victim.
- **Weapon Desc**: Description of the weapon used.
- **Status Desc**: Status of the crime report.
- **LOCATION**: Location of the crime.

## Analysis Steps
1. **Data Cleaning and Preprocessing**: Convert the `TIME OCC` column from military time to a 12-hour format and handle any missing or inconsistent data.
2. **Crime Frequency Analysis**:
   - Identify the hour with the highest frequency of crimes.
   - Analyze crimes within a specific time range (10:00 PM to 3:59 AM) and determine which area has the most crimes during this period.
3. **Victim Age Group Analysis**:
   - Categorize victims into age groups: "0-17", "18-25", "26-34", "35-44", "45-54", "55-64", and "65+".
   - Count the number of crimes committed against each age group and visualize the distribution using a count plot.
4. **Visualization**:
   - Create various plots to visually represent the data, including the distribution of crimes by time and victim age groups.

## How to Run the Project
To replicate this analysis, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/MGalal07/crime-data-analysis.git
    cd crime-data-analysis
    ```

2. **Install Dependencies**:
    Ensure you have Python installed. Install the necessary packages using:
    ```bash
    pip install pandas seaborn matplotlib
    ```

3. **Run the Analysis**:
    Open the Jupyter notebook (`crime_data_analysis.ipynb`) and run the cells to execute the analysis.

4. **Explore the Results**:
    Review the generated plots and results to understand the insights derived from the dataset.

## Results
- **Peak Crime Hour**: Identified the hour with the highest crime frequency.
- **Area with Most Crimes (10 PM - 3:59 AM)**: Determined the area with the most crimes within this time range.
- **Victim Age Group Distribution**: Visualized the distribution of crimes across different age groups.

## Conclusion
This analysis provides insights into crime patterns, helping to identify high-risk times and age groups, which can be useful for law enforcement and public safety strategies.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Data source: [Include the source if available]
- Tools used: `pandas`, `seaborn`, `matplotlib`

