[![Install](https://github.com/nogibjj/Yirang_Liu_Polars_Descriptive_Statistics_Script/actions/workflows/install.yml/badge.svg)](https://github.com/nogibjj/Yirang_Liu_Polars_Descriptive_Statistics_Script/actions/workflows/install.yml)

# 706_DE_Yirang_Liu_Polars_Descriptive_Statistics_Script 

# Structure for this project 
```
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
├── .github/
│   └── workflows/
│       ├── format.yml
│       ├── install.yml
│       ├── lint.yml
│       ├── test.yml
├── mylib/
│   └── lib.py
├── .gitignore
├── Histogram.png
├── Makefile
├── PolarOutput.png
├── README.md
├── ScatteredPlot.png
├── hello.py
├── Requirements.txt
└── test_hello.py

```

# Assignment Requirements

Python script using Polars for descriptive statistics
Read a dataset (CSV or Excel)
Generate summary statistics (mean, median, standard deviation)
Create at least one data visualization

# Data Set Used in this Project
The data set used in this project was pulled from kaggle.com. This data is described as a "comprehensive overview of various factors affecting student performance in exams", including data for 6,607 students's grade and information on various factors that may affect their exam performance, such as # of hours studied, percentage of classes attended, parental involvement (Low, Medium, High), and etc.

# Example Summary Statistics
Example output generated by the get_summary_stats function in main when the column of interest is "Exam_Score"

# Example Data Visualizations
Histogram 
![image](https://github.com/user-attachments/assets/9b9e90e7-c41e-4fe0-ba44-e0dfb2b0bc88)

Scatter plot
![image](https://github.com/user-attachments/assets/c5b2db7d-a21a-473a-82fd-8ac4464baa20)

