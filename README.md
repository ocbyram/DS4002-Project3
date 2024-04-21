# DS4002-Project3

## Contents


## Section 1: Software and Platform 
- Software: The following tools/programs were used to perform analysis
    - [Python (3.10.12)](https://www.python.org/downloads/)
    - [Git](https://git-scm.com/)
    - [Google Colab](https://colab.research.google.com/)
- Hardware: Analyses were run on the following Hardware and Operating systems
    - Google Colab T4 GPU runtime
- Dependencies: 
    - Matplotlib
    - sklearn 
    - functools
    - numpy
    - tensorflow


## Section 2: Documentation Map
Project Structure
```
Project
├── DATA
│   ├── DATA FOR PROJECT 3.pdf
│   ├── DS 4002_ Data Appendix (3).pdf
│   └── Images
├── LICENSE
├── OUTPUT
│   ├── EDA_Dogs_2.png
│   ├── EDA_Dogs.png
│   └── placeholder
├── README.md
└── SCRIPTS
    ├── Main_analysis.ipynb
    └── Reduced_analysis.ipynb
```

## Section 3: Reproducing

To run this script, we recommend using google colab, as it is where we ran and tested our code, as well as contains the necessary libraries and configurations for performing the analysis. 

### Python scripts
To reproduce results in python:

1. Download the repository contents by running `git clone https://github.com/ocbyram/DS4002-Project3.git` or by downloading a zip of the repository from [https://github.com/ocbyram/DS4002-Project3/archive/refs/heads/main.zip](https://github.com/ocbyram/DS4002-Project3/archive/refs/heads/main.zip)
2. Navigate to https://colab.research.google.com/
3. Log in with a valid google account if necessary
4. When prompted which notebook to open, navigate to Upload > Browse then upload the `Main_analysis.ipynb` found in the `SCRIPTS` folder
5. (Optional) In google colab, click the dropdown next to "connect" on the top left hand corner. Select "Change Runtime Type" and then select "T4 GPU" and then "Save". While this isn't neccesary, it will speed up the process of training the model
6. Select Runtime > Run all. This will run the analysis
7. Repeat steps 4-6 but with `Reduced_analysis.ipynb` to see the results for the analysis on a subset of breeds
