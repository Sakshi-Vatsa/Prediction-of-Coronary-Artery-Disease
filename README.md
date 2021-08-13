# Prediction-of-Coronary-Artery-Disease
An Ensemble Machine Learning Model for diagnosis and prediction of Coronary Artery Disease with reduced feature subset.

This is the implementation of the paper: Ensemble of heterogeneous classifiers for diagnosis and prediction of
coronary artery disease with reduced feature subset

Paper Link: https://www.sciencedirect.com/science/article/abs/pii/S0169260720316035

The model is trained on the famous Dataset: Z-Alizadeh Sani dataset for the prediction of Coronary Artery Disease(CAD).

The dataset is preprocessed using Boruta feature selection algorithm. Next it is trained on Base Classifiers: Random Forest, Support Vector Machine and K-Nearest Neighbour. Finally Stacking Ensemble is used for final CAD Prediction.
All 3 types of Stacking Ensemble Methods: Average voting ensemble (AVEn), Majority voting ensemble (MVEn), and Weighted average voting ensemble (WAVEn) are applied to calculate the most optimal results.



