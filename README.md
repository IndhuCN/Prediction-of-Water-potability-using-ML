# Prediction-of-Water-potability-using-ML
This project aims to use Machine Learning techniques to predict whether the water is consumable or not


Access to safe drinking-water is essential to health, a basic human right and a component of effective policy for health protection. This is important as a health and development issue at a national, regional and local level.

Columns:
1. ph: pH of 1. water (0 to 14).
2. Hardness: Capacity of water to precipitate soap in mg/L.
3. Solids: Total dissolved solids in ppm.
4. Chloramines: Amount of Chloramines in ppm.
5. Sulfate: Amount of Sulfates dissolved in mg/L.
6. Conductivity: Electrical conductivity of water in μS/cm.
7. Organic_carbon: Amount of organic carbon in ppm.
8. Trihalomethanes: Amount of Trihalomethanes in μg/L.
9. Turbidity: Measure of light emiting property of water in NTU.
10. Potability: Indicates if water is safe for human consumption. Potable -1 and Not potable -0

Potability is the label and rest of the columns are the features.

Steps involved:
1. Data preprocessing: The data obtained had null values, so dropped null values. Final data has 2011 rows and 10 columns.
2. Used seaborn for the visualization of heatmap and to get the meaningful insights.
3. Model Training: Trained model on 7 algorithms (KNN, SVM, Naive Bayes Theorem, Random forest, Gradient boosting, XG boosting, Ada boosting).
4. Compared different models with its accuracy and came to a conclusion that SVC has the highest accuracy with 0.69 score.
5. Performed RandomizedsearchCV for few models to check whether we can achieve better accuracy or not.


CONCLUSION

RandomForest has been finalized as the best model with an accuracy of 0.706
