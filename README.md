# Cancer_Genetic_Variations_Text_Classification

__Data__: Memorial Sloan Kettering Cancer Center (MSKCC) (https://www.kaggle.com/c/msk-redefining-cancer-treatment/)<br>
The data is spread over two files, with ove containing genes variations, classes and text data in the other. <br>
About Data:<br>
* ID : the id of the row used to link the mutation to the clinical evidence
* Gene : the gene where this genetic mutation is located
* Variation : the aminoacid change for this mutations
* Class : 1-9 the class this genetic mutation has been classified on
* Text : Text data of each patient

__Problem Statement:__ Classify the given genetic variations/mutations based on evidence from text-based clinical literature into nine given classes.<br>

Initially few preprossesing steps were performed to clean any irrelevant data. Then both the files were merged into one. Beacuse the classes distribution is imbalanced, few models were implemented twice after balancing the results to achieve better results. The encoding algorithms were implemented as our data is in text. Finally, below mentioned ML algorithms were used to classify the data. The performance of each ML model was identified with Confusion Matrix and Multi class Log loss.

__ML Models__:
* Naive Bayes
* K Nearest Neighbour
* Logistic Regression
* Linear SVM 
* Random Forest Classifier

