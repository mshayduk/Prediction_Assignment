# Prediction_Assignment


The goal of this project is to characterize the "quality" of the certain human activity and identify how well the physical exercise is performed by means of machine learning algorithms. 

This study explores the **Weight Lifting Exercises (WLE) Dataset** from the **Human Activity Recognition** project ([HAR](http://groupware.les.inf.puc-rio.br/har)). The weight lifting experiment was performed with 6 young healthy participants (subjects).  Each subject was asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in 5
different manners: 
  
  * Class A: according to the specification (correct)
  * Class B: throwing the elbows to the front
  * Class C: lifting the dumbbell only halfway
  * Class D: lowering the dumbbell only halfway
  * Class E: throwing the hips to the front

The activity was characterized with a set of accelerometers worn at arm and forearm as well as attached to the belt and to the dumbbell. The data from this accelerometers is processed resulting in the  vector of 160 features.
For more detailes see: <http://groupware.les.inf.puc-rio.br/har>. The original reference for the **WLE** dataset: *Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. [Qualitative Activity Recognition of Weight Lifting Exercises](http://groupware.les.inf.puc-rio.br/work.jsf?p1=11201). Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.*

The feature vectors are cleaned by justified dropping of the missing values and the final 52-dimentional feature vectors are used for the classification. The activities are classified into 5 categories by the Random Forest model with the automatic Out-Of-Bag error estimation (no need for cross-validation).

Link to RPubs report: <http://rpubs.com/mshayduk/156844>
