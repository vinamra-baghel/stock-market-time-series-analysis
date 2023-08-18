# Stock Market Time Series Analysis

## Introduction
This repository contains the notebook for **Stock Market Time Series Analysis Using LSTM and ARIMA**, wherein we perform stock predictions using various benchmark techniques like **LSTM** and **ARIMA**.

We have used the Google stock data dataset containing market opening and closing values for 5 years from 10th June, 2016 to 9th June, 2021. We test on the next 1 year of data till 9th June, 2022. We also perform short experiments on the Tesla market data. Following are a few important data statistics for Google:

### Dataset Statistics
| **No. of train data points** | **No. of Test data points** |
|------------------------------|-----------------------------|
| 1258                         | 253                         |

## Results
Test Accuracy = **91.05%** for batch size **8** trained for **3** epochs.

## Directory Structure
The `src` folder contains the source code.
```
    .
    ├── ...
    ├── datasets               
    │── main.ipynb      : The notebook.
    └── ...
```

## Installation Steps
### Prerequisites
You'll need to have [`git`](https://git-scm.com/). Check using:
```
git version
```

### Cloning the repository
Clone the repo using the following:
```
git clone https://github.com/vinamra-baghel/stock-market-time-series-analysis.git
cd 'stock-market-time-series-analysis'
```