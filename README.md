# COVID-19 India Statewise Reported Cases Timeseries
This repository provides a timeseries statistics of COVID-19 reported cases in states of India. It also contains Python notebooks used for daily tasks such as web scraping of data, uploading the data to Kaggle and basic data visualization.

The data and the visualization kernel is also published on [Kaggle](https://www.kaggle.com/amitsavant/covid19-india-statewise-reported-cases-timeseries).

## Structure of the project

###data folder

**covid19-india-statewise-timeseries.csv:**  The CSV file containing the timeseries data. The data is available from 30th January 2020 onwards. All figures are cumulative. The data has 5 columns.

Date: Date in DD-MM-YYYY format
State: Name of the state
Total Confirmed Cases: Total number of confirmed cases as on Date
Cured/Discharged/Migrated: Total number of cured, discharged or migrated cases as on Date
Death: Total number of deaths as on Date

**dataset-metadata.json:**  The metadata file of the dataset for Kaggle.

###src folder
**COVID-19 India Timeseries Visualization.ipynb:** Python notebook containing basic data visualization.

**kaggle.ipynb:** Python notebook used to upload data to Kaggle using Kaggle Python APIs.

**webscrape.ipynb:** Python notebook used to upload data to Kaggle using Kaggle Python APIs. 

## Acknowledgements
This dataset is created and maintained using the data available in public domain. The state-wise COVID-19 cases in India are published by [Ministry of Health and Family Welfare, Government of India](https://www.mohfw.gov.in/) A snapshot of the data on the above website is taken at 11PM IST(UTC+05.30) daily and appended to this dataset. 

Part of the data for initial period is taken from [India Today COVID-19 Tracker]( https://www.indiatoday.in/india/story/coronavirus-cases-in-india-covid19-states-cities-affected-1653852-2020-03-09)

Thanks to Jose Cherian for his post [Kaggle API – The Missing Python Documentation](https://technowhisp.com/kaggle-api-python-documentation/) on Techno Whisp. This helped me write the Python script to upload the data daily to Kaggle.

## License
- The data in this project is published under [CC0 1.0 Universal License](https://github.com/amitvsavant/covid19-india-state-timeseries/blob/master/data/LICENSE.md).

- The source code in this project is published under [MIT License](https://github.com/amitvsavant/covid19-india-state-timeseries/blob/master/src/LICENSE.md).