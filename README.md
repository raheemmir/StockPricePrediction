# Predicting the S&P 500 with Scikit-learn

This machine learning project focuses on predicting the value of the S&P 500 index by utilizing the linear regression model from the Python library, scikit-learn.
The data is sourced from the **[Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org)** website. The particular series that was used can be accessed [here](https://fred.stlouisfed.org/series/SP500).

### Running the Notebook Locally
The best way to fully experience the project, such as exploring the interactive plots, is to run the notebook on your own machine.
Here's how:

#### Clone the Repository (via SSH shown):
```
git clone git@github.com:raheemmir/StockPricePrediction.git
cd StockPricePrediction
```

#### Installing Dependencies:
This project is written in Python, if you don't have it already, make sure to install it before continuing with the next steps.
You can verify your installation / check what version you have with the following command:
```
python --version
```
Now to install the neccessary packages (shown using pip):
```
pip install numpy pandas scikit-learn matplotlib seaborn jupyter plotly
```
Before installing the neccessary packages it is good practice to first set up a virtual environment.

#### Using the FRED API
This project accesses data from FRED by using its API. To get it set up:
1. Grab a free API key from the **[FRED API WEBSITE](https://fred.stlouisfed.org/docs/api/fred/)**.
2. Now paste your API key into the provided `sample_config.py` file and change that file's name to `config.py`.
3. The project utilizes a [third party toolkit](https://github.com/mortada/fredapi) to interface with the FRED API, so make sure to install it:
```
pip install fredapi
```
#### Running the Notebook
Now that everything is set up, you can launch Jupyter Notebook:
```
jupyter notebook
```
Then navigate to where you've cloned the repo, open the file `sp500.ipynb`, and dive into the project!
