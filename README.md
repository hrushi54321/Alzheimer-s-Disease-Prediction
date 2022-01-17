# Alzheimer-s-Disease-Prediction
An Integrated Recurrent Neural Network Model for the Detection of Alzheimer Disease Progression

Individual Feature Vector file contains models built for each modality separately. 
The models include SVM, Decision Tree, Random Forest and an Ensemble model consisting of weighted contribution of the previous three models.


Concatenated Feature Vector file contains models built for each modality in a combined fashion. 
The models include SVM, Decision Tree, Random Forest and an Ensemble model consisting of weighted contribution of the previous three models.

Hyperparameter Tuning files contain the code for the most optimum version of models by performing GridSearchCV on each model's hyperparameters to obtaing the one with best performance.

The four modalities are:

1) Cog.csv : Cognitive data consisting of features such as VISCODE, EcogPtMem and EcogPtTotal.
2) Pheno.csv: Pheno Data consisting of features such as VISCODE, ABETA, TAU and PTAU.
3) MRI.csv: MRI Data consisting of features such as VISCODE, Hippocampus and Entorhinal.
4) Demo.csv: Demographic data consisting of features such as VISCODE, AGE and APOE4.
