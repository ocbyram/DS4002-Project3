# DS4002-Project3

## Contents


## Section 1: Software and Platform 
- Software: The following tools/programs were used to perform analysis
    - [R (3.3.0+)](https://cran.rstudio.com/)
    - [R Studio (2023.12.1)](https://posit.co/download/rstudio-desktop/)
    - [Python (3.10.12)](https://www.python.org/downloads/)
    - [Git](https://git-scm.com/)
    - VSCode with [Jupyter notebook support](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- Hardware: Analyses were run on the following Hardware and Operating systems
    - Dell Latitude 7480 (Ubutnu 22.04.2)
- Dependencies: 
    - Matplotlib
    - sklearn 
    - pandas
    - scipy
) 


## Section 2: Documentation Map
Project Structure
```
Project
├── DATA
│   ├── Data Appendix.pdf
│   └── weather.csv
├── LICENSE
├── OUTPUT
│   ├── ANOVA_Tables_In_Order.png
│   ├── Correlation Results.txt
│   ├── Date_MaxTemp_Prediction.png
│   ├── eda.ipynb
│   ├── PRCP_BoxPlot.png
│   └── Temp_MAX_BoxPlot.png
├── README.md
└── SCRIPTS
    ├── analysis.ipynb
    └── ANOVA_Analysis.Rmd
```

## Section 3: Reproducing



Before starting ensure that you have all the required software installed as outlined in Section 1. We also encourage use of either Mac, Windows or Ubuntu, as that is what the analysis was tested on, although other operating systems may work.

### R scripts

***To reproduce the analysis performed in R, one must first used the read.csv() function to import the weather csv data. Subset the columns that are mentioned in the data appendix, then create a new column labeled "year" with the year of the date subset into it. After this use the ANOVA function to perform a simple ANOVA test on the max temp, min temp, precipitation, and snow. Following this, create boxplots on the two that have significant p-values (precipitation and max temp). Finally, create a linear regression model using the lm function in R. This should regress max temp on date, which allows you to predict the max temperature of future dates based on past ones.*** 

### Python scripts
To reproduce results in python:

1. In the SCRIPTS directory, run `pip install -r requirements.txt` to install the required packages
2. Open analysis.ipynb in VS Code
3. Pres the run all button at the top of the notebook to run the analysis
