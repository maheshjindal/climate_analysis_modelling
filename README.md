
# Data Modelling to analyse impact of immigrants on the climate of USA
The aim of this project is to perform data modelling required to analyse the behavioral impact of Immigrants on the climate of different states of USA. To accomplish this task we are creating a data pipeline built up using the two different massive datasets containing immigrants data and the temperature data. We need to create a ELT database which is well optimized for running queries and performing other analytical operation to gather the facts/insights from this data.

## Project Dependencies
- Python 3.x
- PySpark >= 2.4.x
- Numpy
- Pandas

## Datasets
Two different datasets has been used with their details provided below:
- **Climate Change Dataset:** This dataset comes from [Kaggle](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data) contains information of average temperature at different cities across the globe.

- **Immigrants Dataset:** This dataset comes from [US National Tourism and Trade Office](https://www.trade.gov/national-travel-and-tourism-office) containg information regarding their arrival arrival information. 


## Running the Project
1. Clone the project in your local.
2. Install all the required dependencies.
3. Open the Jupyter notebook file named `Project.ipynb` and run all cells.
4. The modelled data will be processed and dumped in `<BASE_PROJECT_PATH>/output` directory. 


## Author

- [@maheshjindal](https://www.github.com/maheshjindal)