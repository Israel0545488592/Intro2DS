# Intro2DS

Intro to data science – documentation 
Name: Israel Jacobovich
ID: 212403679

Links to the pages on Kaggle I downloaded the data-sets from:  * https://www.kaggle.com/nicholasjhana/energy-consumption-generation-prices-and-weather
                                                                                                                  *  https://www.kaggle.com/jsphyg/weather-dataset-rattle-package/code

Models I used in the project: DecisionTreeClassifire
                                                    KNearestNeighbours
                                                    LiniarRegrassion 

Several terms for model evaluation methods I used in the project:
Classification :  accuracy – True\False
                           Recall/sensitivity – TruePosetive\ TruePosetive + FalseNegative
                          Precision/specificity - TruePosetive\ TruePosetive + FalsePosetive
                          F1score –  2 * tpr  * fpr \ tpr + fpr 
                          ROC-curve – a graph that shows the tpr & fpr values for each threshold for positive classification
Regression: MeanSquareError – the average square difference of the predicted value and the real one
                      MeanAbsolutError – the average absolut value of the difference between the predicted value and the real one
                      R_2 -     1 – (sum of the square of the difference between the real values and the predicted ones)
                                           \( sum of the square of the difference between the real values and the mean)

Attributes of the models class from skilearn I manipulated in the project:
N_neighbours – how many instances to consider(knn)
max_leaf_nodes - the maximum number of samples required to be at a leaf node(decision_tree)
min_samples_leaf - like the privius just the minimum
criterion - the criterion atrabute states wich type of calculation the algorithm use to detrmain which split produces the most purity(decision_tree)

