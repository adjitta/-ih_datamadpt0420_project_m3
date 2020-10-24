# Module 3 : Diamond's Price
![Image](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F3824396%2Fbeaf52135483332c90a86b157e178715%2Fimage%20(12).png?generation=1588785521255575&alt=media)

## Goal

The goal of this competition is the prediction of the price of diamonds based on their characteristics (weight, color, quality of cut, etc.), putting into practice all the machine learning techniques you know.


### Data sources 
 - Database with the diamonds information.
    - Provided by [Ironhack](http://www.potacho.com/files/ironhack/diamonds_train.csv) formatted as a `.csv` file.
 
 ## **Installation**
Use the package manager conda to install the following libraries:

```bash
conda install nodejs
conda install nodejs
conda instal Seaborn
conda install Matplotlib
```
 ### Requirements
 - Data analysis:
    - Pandas
    - Numpy
    -Math
- Data visualisation
    - Seaborn
    - Matplotlib
    - Plotly
    -Warnings
    -Cufflinks
- Train model
    -SVR
    -RandomForestRegressor
    -AdaBoostRegressor
    -GradientBoostingRegressor
    -xgboost
    -lightgbm
    -BaggingRegressor
    -StandardScaler
###  **Folder structure**
```
└── project
    ├── __trash__
    ├── .gitignore
    ├── .env
    ├── requeriments.txt
    ├── README.md
    ├── main_script.py
    ├── notebooks
    │   ├── notebook1.ipynb
    │   └── notebook2.ipynb
    ├── package1
    │   ├── module1.py
    │   └── module2.py
    └── data
        ├── raw
        ├── processed
        └── results
```
## Machine learning model
1. RandomForestRegressor
2. AdaBoostRegressor
3. GradientBoostingRegressor
4.xgb
5. lgb
6. BaggingRegressor
## Conclusions 
The best result is obtained with simple models within the model lgb, the most important thing is to do the train, test and validation well with a 60%, 20%, 20% of the datasheet to verify that the RMSE result in train is not too far from the others (test, validation).
I calculated the RMSE proxy which is a coefficient between the RMSES of the train and the mean of the RMSE test and validation, if this is 1 the RMSE of the train is the same as the RMSE of test and validation, 0 is very different.
Therefore, the important thing is to lower the RMSE without the proxy RMSE coefficient falling too low.
Another important thing is to seek inside the datasheet and create your own variables.

