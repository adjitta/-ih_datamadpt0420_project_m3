# Module 3 : Predict Diamond's Price


## Goal

The goal of this project is to predict the price of diamonds, training machine learning models. In this project we will have to upload the results obtained in the kaggle competition.
It's almost impossible to get a value below that dollar quantity because diamond's price depends on a lot of variables as you'll see explained on the jupyter-notebook file.


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
## Conclusions 
1. x,y, and z have a very strong relation with price but surprisingly depth (which comes from x,y, and z) doesn't has a significant relation with price.
2. Carat has a strong relation with price
3. Table doesn't have a significant relation with price or any other variable as well.
4. Average diamond prices are low.The upper quartile is bigger. It shows that whichever category it may be there's a variety of diamonds that are still very expensive.



