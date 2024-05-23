# pclub_secy_task_02
A model capable of predicting the lung tidal volume on the basis of factors such as Age, Gender, Height, and some specific symptoms.
### Steps to run code: 
Download the dataset dataset.xlsx and the ipynb file task2.ipynb and just run the jupyter file !

dataset_ch.xlsx is processed version of dataset.xlsx with no extra irrelevant features.

### Approach
1. Preprocessed data in xlsx file to remove irrelevant factors and dropped the rows with nan value.
2. Tried first basic approach of applying Linear Regression with every feature.
3. Linear Regression with selected features which had high correlation.
4. Polynomial Regression
5. Decision Tree Regression
6. Random Forest Regression

Accuracy achieved was above `99.3%` with MSE of `10.29` by using Random Forest Regression.
### Dataset
Finding dataset wasn't very tough, just had to google using appropriate prompts and search filter. I obtained dataset from : https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6025863/ .

Although the dataset isn't very robust as the tidal volume values are pretty repeated and not much unique. But this is only what I was able to find with time in hand.
   
### Working of Model
![image](https://github.com/aayush01x/pclub_secy_task_02/assets/153027947/124b5abf-bdfd-4ddf-8349-09979f913d07)
