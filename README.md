# Property_Valuation_Based_On_Satellite_Imagery

This Project focuses on predicting a continuous target variable using a multi model learning approach that 
combines satellite imagery data with tabular metadata (such as lattitude, longitude and other numerical features) 
The motivation is to leverage both visual spatial information and structered numerical data to achieve higher predictive accuracy than using either modality alone. 

PROBLEM STATEMENT 

Traditional machine learning models often rely only on tabular data, while deep learning models focus on 
image-based features. However, satellite-based prediction tasks benefit from both sources. The challenge 
addressed here is to design an end-to-end pipeline that efficiently fuses image features with tabular features 
and trains a regression model capable of generalizing well to unseen data.


The dataset consists of satellite images stored as TIFF files and a corresponding CSV file containing tabular 
attributes and the regression target. Each image is uniquely identified by an ID that maps it to the appropriate 
row in the tabular dataset.

The model is trained using a supervised regression objective, typically Mean Squared Error (MSE). The 
dataset is split into training and validation sets. Performance is evaluated using metrics such as MSE and 
R-squared (R²) to measure prediction accuracy and variance explanation.

