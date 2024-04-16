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
│   ├── DS 4002: Data Appendix.pdf
│   └── DATA FOR PROJECT 3.pdf
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

### Python scripts
To reproduce results in python:

1. In the SCRIPTS directory, run `pip install -r requirements.txt` to install the required packages
2. Open analysis.ipynb in VS Code
3. Pres the run all button at the top of the notebook to run the analysis
