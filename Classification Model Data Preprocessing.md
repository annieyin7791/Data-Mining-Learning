## Data Preprocessig Steps  
- train / test set split  
- missing values handling
- outliers handling
- encoding
- feature scaling
- imbalanced data handling for training set

## Preprocessing steps used in both training & testing sets
- missing values handling
- encoding
- feature scaling

`scaler = StandardScaler()`  
`scaler.fit(X_train)`

## Steps used only on training set
- Outliers handling: If the outliers are removed from the testing set, it would violate the real-world data distribution
- Imbalanced data handling (e.g. resampling)
`ddddd`
