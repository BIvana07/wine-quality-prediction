# wine-quality-prediction
Comparing KNN, Decision Tree, and Neural Network models to classify wine quality from physicochemical properties (-72% accuracy with cross-validation))

This project classifies wine quality (low/medium/high) based on physicochemical properties (acidity, sugar, alcohol content, etc), comparing three different machine learning approaches to see which handles the problem best.

Approach: Rather than jumping straight into one model, I built and evaluated three: K-Nearest Neighbours, a decision tree and a neural network (MLPClassifier). Each was tuned properly-including selecting the optimal K for KNN- and evaluated using 5-fold cross-validation rather than a single train/test split, to make sure the comparison was fair and not a fluke of one particular data split.

Tools Used: Python, scikit-learn, pandas, NumPy, Matplotlib

Results: The Neural Network performed best, achieving 72% test accuracy, outperforming bot the decision tree and KNN baselines
