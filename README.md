## Credit and Debit cards holders in Argentina.
<img src="https://raw.githubusercontent.com/AleCipolat/analysis_cards_bcra/main/cards_dashboard_banner.jpg"  height="450px" />

*A time series analysis showing the distribution of the credit and debit cards holders offered by financial entity in the Argentina Republic , from 2002 to 2021.*

## 🔧 Technologies & Tools
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## Demo Live
https://app.powerbi.com/reportEmbed?reportId=6e5b5f54-d54f-4fb1-93ab-d63a41303fe2&autoAuth=true&ctid=c14784bc-aa5b-48b8-8b8a-a7621b6ec8f2

## The credit and debit cards holders analysis in a nutshell:
This time series describes the amount of holders of credits and debits cards that were offered in Argentina, from 2002 to 2021.

### Where data cames from - *Data source*:
Argentina Republica Central Bank (BCRA): 
* URL: https://www.bcra.gob.ar/Pdfs/PublicacionesEstadisticas/produser.xls
* Excel: produser.xls
* Tab: "cant_tarj_cred_deb"
You can also find the raw data in the files

### How the data has been transformed and cleaned - *ETL Process*:
An ETL process has been performed in order to clean and rearrange the original dataset in excel format to a .csv in Python with the Pandas Package. 
Please refer to the following file: credit_etl.ipynb

### What trends and patterns has been discovered - *Exploratory Data Analaysis*:
To discover the trends and potential features of this dataset, it has been performed an Exploratory Data Analysis in order to adress the initial questions.
Please refer to the following file: EDA.ipynb

### Take a further look into the data with this interactive dashboard:
In the you could interact with the data through a dashboard made with Power BI. 


This code has been made using Jupyter Notebooks
