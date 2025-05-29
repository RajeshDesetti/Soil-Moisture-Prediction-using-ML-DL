In this study, I explored the application of multiple machine learning models to predict soil moisture using remote sensing data and derived features. The models evaluated include Linear Regression, XGBoost, Random Forest, Support Vector Regression (SVR), and a Neural Network.
•	Linear Regression, although fast and interpretable, showed the lowest performance with an R² score of just 0.0088, indicating it fails to capture the non-linear patterns in the data.
•	XGBoost and Random Forest performed better, leveraging ensemble learning and non-linear capabilities, with R² scores around 0.05–0.055.
•	SVR and the Neural Network showed similar performance to the tree-based models, though with slightly higher RMSE and slightly lower R².

All models showed relatively low R² scores, indicating that they were only able to explain a small portion of the variation in soil moisture. This is likely because soil moisture is influenced by many complex and hidden environmental factors that are not fully captured by the available features. Additionally, the data appears to be scattered, making it difficult for the models to identify clear linear or non-linear relationships between the input variables and the target. Despite the low R² scores, the models demonstrated consistent performance across training and validation, suggesting they were learning meaningful (but limited) patterns.

