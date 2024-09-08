Welcome to the Legal Case Outcome Prediction wiki!

This work is to predict the outcomes for legal cases based on case summaries. The work is carried out specifically for Indian court cases. The summaries are created in four different languages: English, Kannada, Tamil & Telugu.

Four different language models are used for creation of embeddings: FastText, RoBERTa, IndicBERT and InLegalBERT. The classification is done with a stacking classifier consisting of a base model farm feeding a metamodel. The base model farm uses Random Forest (RF), Decision Trees (DT), Support Vector Machines (SVM), k-Nearest Neighbors (KNN), Multilayer Perceptron (MLP), XGBoost (XGB), LightGBM (LGBM). With extensive experimentation XGBoost is chosen as metamodel.

The work is under review for publication with IEEE Access.
