# DNA-Sequence-Classification-Using-Machine-Learning
### Motive behind this Project
This project was carried out to understand how a basic machine learning model can be modelled and understanding how preprocessing and other analysis can be done on the dataset
to extract its features and understand the data to the depth. Along with the various ML algorithms were applied on and also understading the different evaluation metrics were one of the
most important objectives of this introductory machine learning project.

### About the Dataset
The dataset consists of promoter gene sequences.A promoter is a sequence of DNA needed to turn a gene on or off. The process of transcription is initiated at the promoter. 
The promoter has a binding site for the enzyme used to make a messenger RNA (mRNA) molecule.
https://archive.ics.uci.edu/ml/machine-learning-databases/molecular-biology/promoter-gene-sequences/promoters.data


### About the Project
Given the data with binary class [+,-],id of the sequence and the sequence,the problem is to predict class of the new sequence making it a binary classification problem.
After the necessary pre processing and analysis of the data was done, the model_selection was done which is a method for setting a blueprint to analyze data and then using it to measure new data. Selecting a proper model allows you to generate accurate results when making a prediction.
The machine learning algorithms that we used are SVM, Decision Tree, Random Forest, KNN, MLP classifier, Adaboost and Gaussian Naive Bayes all of which were imported from the Scikit-learn library.
Apart from using the inbuilt libraries, some of the algorithms were implemented from scratch so that we understand the theory behind each of them clearly.

### Results
After printing the classification report, Linear SVM gave the best results with an accuracy of 96.2%.
