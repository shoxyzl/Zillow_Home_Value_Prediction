# Zillow Home Value Prediction

This project uses data exploration, data processing, feature engineering, and machine learning algorithms (specifically, CatBoost and LightGBM) to predict the log-error between their Zestimate and the actual sale price, given all the features of a home. In the training part, I first used 80% of data as training set, and 20% as testing set. According the training results to modify algorithm's parameters, the best score of which will be selected to predict final $logerror$.

## Table of Contents

- [Files](#files)
- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Files
`Zillow’s Home Value Prediction.ipynb` contains the basic data exploration, data processing, feature engineering, and CatBoost Part.

`LightGBM.ipynb` contains the LightGBM part. 

`src/data_proc.py` includes data cleaning and feature extraction methods.

## Usage

To use this project, you need to follow the following steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Create 'data' and 'hdf5' folders.
4. Download data sets from [Kaggle](https://www.kaggle.com/competitions/zillow-prize-1/data) and unzip them in 'data'.
5. Run `jupyter notebook` in your terminal to open the Jupyter Notebook.
6. Open the notebook `zillow_home_value_prediction.ipynb`.
7. Follow the instructions in the notebook to explore the data, process it, engineer features, and train the CatBoost and LightGBM models.
8. Use the trained models to make predictions on new data.


## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


## Acknowledgements

Thank you to the following resources for providing helpful information and code snippets:

- [Zillow Prize: Zillow’s Home Value Prediction (Zestimate)](https://www.kaggle.com/competitions/zillow-prize-1)
- [CatBoost documentation](https://catboost.ai/docs/)
- [LightGBM documentation](https://lightgbm.readthedocs.io/)
