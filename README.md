# Regression Model to Predict House Prices 
This project uses Linear Regression ML algorithm to accurately predict the prices of houses in California. Computations, analyses and thoughts are contained in the attached Jupyter Notebook titled "predicingHousePrices.ipynb".

## How It's Made
Tech Used: Python, scikit-learn, pandas, numpy, seaborn, matplotlib

1. **Imports and Data Frame Creation** <br> Created a dataframe using the attached dataset titled "Housing.csv".  <br>
2. **Checking for missing values** <br> Used numpy to check for missing or invalid values.  <br>
3. **Exploratory Data Analysis** <br> Applied seaborn's pairplot function to graph the dataframe's numerical categories. This step was to get a feel for what factors would have the most influence over a house's price (which will henceforth be referred to as the "target variable"). <br>
4. **Data Wrangling** <br> Utilized various data preprocessing techniques to prepare the data for modelling. This includes transforming qualitative variables (strings) into numerical values using binary mapping for yes/no columns. scikit-learn's included One-Hot Encoder class is used for non-binary features.
