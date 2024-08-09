# Water-Solubility-Prediction
Predicting solubility of different molecules in water based on their hydrophobicity, molecular weight etc using machine learning algorithms such as linear regression and random forest.

In this project I have used a public dataset which contains the features such as:
MolLogP: Logarithm of the partition coefficient, indicating hydrophobicity.
MolWt: Molecular weight of the molecule.
NumRotatableBonds: Number of rotatable bonds, indicating molecular flexibility.
AromaticProportion: Proportion of the molecule that is aromatic.
And the label as:
logS: Logarithm of solubility in water, which is output variable.

Two machine learning algorithms, Linear Regression and Random Forest are used to predict the solubility. The libraries used are Scikit-Learn, Pandas, Numpy, Matplotlib.
