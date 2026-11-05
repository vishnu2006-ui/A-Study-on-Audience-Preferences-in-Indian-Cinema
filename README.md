# TFI Survey Data Analysis Using Python

## Project Overview

This project focuses on analyzing survey data related to the Telugu Film Industry (TFI) using Python and Google Colab.

The dataset contains **1,030 survey responses** covering audience preferences, favourite actors, directors, movies, comedians, and demographic information.

The main objective is to analyze audience opinions and identify trends and preferences in Telugu cinema through data analysis and visualization.

## Objectives

- Analyze the demographic details of survey respondents.
- Identify the most popular Telugu film directors and heroes.
- Analyze audience opinions about industry-hit movies.
- Identify underrated and overrated movies.
- Analyze classic, ultra-classic, and disaster movies.
- Identify favourite comedians.
- Explore relationships between demographic information and movie preferences.
- Present the results using charts and visualizations.

## Dataset Description

The dataset contains the following columns:

| Column | Description |
|---|---|
| S.No | Serial number |
| Gender | Gender of respondent |
| Age | Age group |
| Place | Respondent's location |
| Favourite_Director | Favourite film director |
| Favourite_Hero | Favourite actor |
| Industry_Hit | Industry-hit movie |
| Underrated_Movie | Underrated movie |
| Overrated_Movie | Overrated movie |
| Classic_Movie | Classic movie |
| Ultra_Classic_Movie | Ultra-classic movie |
| Disaster_Movie | Disaster movie |
| Favourite_Comedian | Favourite comedian |

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PyMuPDF (fitz)

## Project Workflow

The project is divided into 26 individual steps:

1. Import required libraries.
2. Upload the PDF dataset.
3. Extract text from the PDF.
4. Define dataset columns.
5. Extract individual survey responses.
6. Display the dataset.
7. Check dataset information.
8. Check missing values.
9. Clean the dataset.
10. Perform gender analysis.
11. Perform age-group analysis.
12. Perform place-wise analysis.
13. Analyze favourite directors.
14. Analyze favourite heroes.
15. Analyze industry-hit movies.
16. Analyze underrated movies.
17. Analyze overrated movies.
18. Analyze classic movies.
19. Analyze ultra-classic movies.
20. Analyze disaster movies.
21. Analyze favourite comedians.
22. Analyze gender versus favourite hero.
23. Analyze age versus favourite director.
24. Generate descriptive statistics.
25. Export the analysis to Excel.
26. Download the final Excel report.

## Data Visualizations

The project uses different visualization techniques:

- Bar charts
- Pie charts
- Heatmaps
- Frequency distributions
- Cross-tabulation analysis

## How to Run This Project

### Step 1: Open Google Colab

Visit: https://colab.research.google.com/

### Step 2: Create a Notebook

Click **New Notebook**.

### Step 3: Copy the Python Code

Copy the code from each of the 26 steps and paste it into separate Colab cells.

### Step 4: Upload the Dataset

Run Step 2 and upload the TFI survey PDF when prompted.

### Step 5: Execute the Cells

Run all cells sequentially, from Step 1 to Step 26.

### Step 6: Download the Results

The final Excel report will be generated and downloaded.

## Expected Output

The project generates:

- Cleaned survey dataset.
- Gender and age-group distributions.
- Place-wise respondent analysis.
- Favourite director and hero rankings.
- Movie preference analysis.
- Favourite comedian rankings.
- Demographic comparison heatmaps.
- Excel report containing the cleaned data and frequency tables.

## Project Structure

```text
TFI-Survey-Data-Analysis/
│
├── README.md
├── TFI_Dataset.pdf
├── TFI_Survey_Analysis.ipynb
└── TFI_Survey_Analysis.xlsx
```

*Note: The Excel report is generated after running the notebook. Include the dataset only if you have permission to share it.*

## Limitations

- The analysis is based on the collected survey responses.
- Survey opinions represent respondents and may not reflect the entire Telugu cinema audience.
- Movie classifications such as underrated, overrated, classic, and disaster are subjective.
- PDF extraction depends on the formatting of the source document.

## Conclusion

This project demonstrates how Python can be used to analyze audience preferences and opinions about the Telugu Film Industry.

By using data cleaning, statistical analysis, and visualization techniques, the project provides insights into audience choices and movie preferences.

## Author

**Project:** TFI Survey Data Analysis  
**Tools:** Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn

---

*If you use or modify this project, please acknowledge the original dataset source and follow its sharing permissions.*
