# Traffic Forecast
The Traffic Forecast application analyzes time series data and performs time series forecasting to make predictions on the companys stock performance in relation to it Google search traffic.

---

## Technologies

Google Colab: IDE that allows Jupyter Notebooks to run in the cloud.

Pandas: Python library for data analysis and manipulation

Numpy: Python library for mathematical functions

Matplotlib (%matplotlib): Python library for creating visualizations

Prophet: forecasting time series data

Pystan: Prophet dependency 

hvplot: Interactive ploting library

holoviews: Data analysis and visualization library.

---

## Installation Guide

Jupyter notebooks that run in the cloud use a base configuration of Python 3 components that include the following libraries:
Pandas
Numpy
datetime
Matplotlib


Install the required libraires in GeoColab by using the following commands:

!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

---

## Usage

To use the Crypto Performance application, run the net_prophet.ipynb file in Google Colab. 

To work with CSV files in Google Colab, they must be uploaded. Once uploaded they can be stored in a DataFrame by calling on pd.read_csv and supplying the CSV file name.

![Screen Shot 2022-03-13 at 7 29 17 PM](https://user-images.githubusercontent.com/95586624/158084737-1684d152-592d-44d2-a0b3-7797aff1c30f.png)


Google Colab renders hvPlots differently than a local Jupyter instance, you might see a blank plot. To avoid this, you'll see the following line of code before each hvPlot:

![Screen Shot 2022-03-13 at 7 31 04 PM](https://user-images.githubusercontent.com/95586624/158084744-91c4a472-fdd5-41ca-aa02-92231ba94c6f.png)

---

## Contributors

Contributions by Carl Frederick.

---

## License

MIT.

