
# The Sub 3-Hour Marathon



 

# Overview 

I have composed an analysis on the strategy behind running a sub 3-hour marathon, based on the results of the 2023 Boston Marathon. In doing this I have used metrics like time distributions, age, gender and race day weather conditions. This is done through OLS Regression and Web Scraping techniques. 



**Blog post:** https://github.com/eh1036/BEE2041-empirical-project/blob/main/notebooks/blog.ipynb 



# Data Sources 



**This is the data I used that comes from the Boston Marathon Results:** 2023 Boston Marathon results via the SCORE Sports Data Repository — https://data.scorenetwork.org/running/boston_marathon_2023.html 



**This is the weather data I used from the day of the 2023 Boston Marathon** Scraped from the Open-Meteo Historical Weather API — https://open-meteo.com 



#  So you can test or redo this assignment, the different software systems you will need access to includes:

- Python 3.9+

- jupyterlab

- matplotlib

- seaborn

- statsmodels

- scikit-learn

- requests

- beautifulsoup4




# How to Replicate

**1. First you must clone the repository:**

```bash

git clone https://github.com/eh1036/BEE2041-empirical-project.git

cd BEE2041-empirical-project

```

**2. Then you need to create a virtual environment:**

```bash

python3 -m venv venv

source venv/bin/activate

```

**3. After this, it is a requirement to install the dependencies:**

```bash

pip install jupyterlab pandas matplotlib seaborn statsmodels scikit-learn requests beautifulsoup4

```

**4. After this, you need to go and launch JupyterLab:**

```bash

jupyter lab

```

**5. You can now open the notebook and run it:**

- Navigate to `notebooks/blog.ipynb`

- Click Kernel, and then click Restart Kernel and Run All Cells

- All plots should generate, and you can just save it to the outputs folder

# Expected Output

If you now run this, you should expect the analysis, which totals just under 2500 words, and all the plots from both the regression model and the web scraping should be produced.

