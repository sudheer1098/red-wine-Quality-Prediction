# Red_Wine_Quality_Prediction
Predict the Quality of the wine given the physiochemical data of the wine. Improved the accuracy of the model using EDA and features selection using correlations.


### DESCRIPTION

The dataset is related to the red variant of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).
These datasets can be viewed as regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

### [Dataset](https://drive.google.com/file/d/1Jiee6bvIgMOGIOwpg_DxYpk4fwZaJpWE/view?usp=sharing) 



### OBJECTIVE
To apply regression techniques and predict the quality of the wine.

### APPROACH
- Import the modules and dependencies and load the dataset.
- Clean the data, fill the null values with imputation if any.
- Perform EDA on the dataset.
   - Label is quality, do the target analysis with features.
   - Check for correlations among features, also use heatmaps.
   - Do Features engineering.
- Slice the dataset into features and label.
- Split the data into training and testing dataset.
- Drop those features that are having high correlation among other features that are exceeding a threshold value.
- Features selection based on correlations.
- Apply features scaling on both training and testing features.
- Apply Regression techniques and compare the models.

### ACCURACY
With applying correlations to select non-redundant features

- Linear Regression                :       63.75
- SVM Regression                         :       63.75
- Decision Tree Regression        :        60.94
- Random Forest Regression     :        72.5

### CONCLUSION

Applied different regression techniques to predict the quality of wine and observed that Random Forest Regressor provided comparatively high accuracy score ( 72.5 % ) than other regression algorithms.
