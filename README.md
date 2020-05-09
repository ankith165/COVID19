# COVID19
## Forecasting the Confirmed, Recovered and Death cases in the country.

### Data Directory:
This directory contains data file in .csv format. This is used to predict future cases.

### Code Directory:
This directory contains two code file in notebook format(i.e. .ipnyb).
  #### 1. DataUpdate.ipnyb: 
          This file is used to download the latest data in Data/dataSet.csv for the given country. By default 'India' is given as the Country/Region. You can replace 'India' with any country name, affected by COVID19. 
  #### 2. ForcastingModel.ipnyb:
          This file is used to forecast the cases by using dataSet.csv from Data directory. Please hardcode the startDate(from date) and endDate(to date) before you run this file. By default startDate and endDate both are set to '2020-05-10'. Please follow the date formate(YYYY-MM-DD) while setting the startDate and endDate. The final forecast file will be availbale in Output/Forecast.txt 

### Output Directory:
This directory contains the forecast result in .txt format(Forecast.txt).

To run this whole project, clone it to your local system(recommanded Google Colab). First run the DataUpdate.ipnyp to get the latest data then execute the ForecastingModel.ipnyb to get the forecasting results. 

NOTE: All data in the commulative form. Please make changes in the file paths according to your system. 
