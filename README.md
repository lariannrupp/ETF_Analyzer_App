# ETF_Analyzer_App

<img width="958" alt="Screenshot 2022-02-10 193143" src="https://user-images.githubusercontent.com/95719899/153529366-ede4de75-9458-4f90-b312-600fa9cb41be.png">

---

In this exercise, I’ll build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.


## Technologies

**A Python 3.9.7 (ipykernal) in JupyterLab** was used to write this notebook.


Additional Python libraries are imported into the start of the app: 


<img width="292" alt="image" src="https://user-images.githubusercontent.com/95719899/153529561-5b96cb7c-0e22-498b-9522-5f9f2e6a0074.png">



---

## Installation Guide

To use the app, from the Github repository, download:
- **etf_analyzer.ipynb** Jupyter file 
- **etf.db** seed file for databases

Use either Terminal or GitBash to run the app in a conda dev environment. 
To enter a conda dev environment, type
'conda activate dev'

You may need to install hvplot in Terminal or GitBash.
Install hvplot by using the conda install command as follows:
> pip install hvplot.pandas

Confirm the installation of hvplot by running the following commands:
> conda list hvplot

To run the app, navigate to the root directory, which contains **etf_analyzer** and the **etf.db** file and then type
'jupyter lab'



---

## Usage

As you run through the exercise, observe how I analyzed San Francisco Real Estate Investment Opportunities through the following steps:


### Analyze a Single Asset in the ETF

For this part of the exercise, I’ll use SQL queries with Python, Pandas, and hvPlot to analyze the performance of a single asset from the ETF.

<img width="378" alt="image" src="https://user-images.githubusercontent.com/95719899/153530439-9d9ddd58-740e-4569-ba78-3cda01f1cb36.png">



### Optimize Data Access with Advanced SQL Queries

For this part of the exercise, I’ll continue to analyze a single asset (PYPL) from the ETF. 

I’ll use advanced SQL queries to optimize the efficiency of accessing data from the database.

<img width="294" alt="image" src="https://user-images.githubusercontent.com/95719899/153530238-b52f4c81-bca7-446f-95e5-86a81cf271bd.png">



### Analyze the ETF Portfolio

For this part of the exercise, I’ll build the entire ETF portfolio and then evaluate its performance. 

To do so, I’ll build the ETF portfolio by using SQL joins to combine all the data for each asset.

<img width="377" alt="image" src="https://user-images.githubusercontent.com/95719899/153539340-7944040a-af38-4979-b71f-3c8e2e1e6ca8.png">


### Deploy the Notebook as a Web Application

For this part of the exercise, I'll do the following:

- Use the Voilà library to deploy your notebook as a web application.

<img width="140" alt="image" src="https://user-images.githubusercontent.com/95719899/153539669-76760e1b-2968-490f-bad3-40cd820fdaa2.png">



---

## Contributors

This exercise was based on a challenge problem from UC Berekely Fintech Bootcamp Module , accessed on 2022.02.10. 

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero
