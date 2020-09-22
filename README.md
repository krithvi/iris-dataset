<h3>KNOW I PROJECT:</h3><br>
IRIS DATASET:<img src='https://img.icons8.com/plasticine/2x/flower-doodle.png' width="40" height="40" ></img><br>

Team name:  Incredibles<br>
Team Members:
1)	Shruthakeerthy.S
2)	 Nihil
3)	Madhumita
4)	Kavya 

The objective of this project is classification of   iris dataset by discovering patterns from examining the petal and sepal size of the flower. The dataset was taken from kaggle.

<b>ABOUT THE DATASET:</b><br>
The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant The data base contains the following attributes: 1). sepal length in cm 2). sepal width in cm 3). petal length in cm 4). petal width in cm 5). class: - Iris Setosa - Iris Versicolour - Iris Virginica
Based on the contribution of first four features the species among three is predicted.<br>

<b>OBSERVATIONS FROM DATA VISUALIZATIONS:</b><br>
•	After graphing the features in a pair plot, we can see the clear relationship that iris setosa (pink) in different from other two species.<br>
•	But there is a overlap in pairwise relationship of iris vericolour(dark blue ) and iris virginica (light blue).<br>

<b>IMPLEMENTATION:</b><br>
This project is implemented using jupyter notebook in python. The models were trained using Logistic Regression ,K-Nearest Neighbors, Random Forest  and SVC algorithms .Out of these algorithms used SVC gave the highest accuracy of 97%.<br><br>
<b>JUSTIFICATION:</b><br>
•	SVC is better than logistic regression because SVC tries to maximize the margin between the closest support vectors while LR the posterior class probability. <br>
•	SVC is better than KNN because knn  classifies data based on the distance metric whereas SVM need a proper phase of training. Due to the optimal nature of SVM, it is guaranteed that the separated data would be optimally separated.<br>
•	SVC is better than random forest because random forest gives the probability for being in a class but SVC may give clear margin of separation of classes.<br><br>
<b>ADVANTAGES OF SVM:</b><br>
1)	SVM works relatively well when there is clear margin of separation between classes.
2)	SVM performs and generalized well on the out of sample data. Due to this as it performs well on out of generalization sample data SVM proves itself to be fast as the sure fact says that in SVM for the classification of one sample , the kernel function is evaluated and performed for each and every support vectors.



