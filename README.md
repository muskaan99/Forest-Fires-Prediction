# Forest-Fires-Prediction

## Abstract
A forest fire is an unplanned and uncontrollable event and can be caused due to natural events such as ignition by the sun’s heat or a lightning strike or due to human activities like unattended campfires and discarded cigarettes. It causes threat to human life and large amounts of economic and ecological damage. Climate change has increased the number of forest fires in the last decade,making them more common and severe. 

In this paper, we have implemented seven different models namely Trivial, Nearest Means, Support Vector Machine, Naive Bayes Classifier, Logistic Regression,
Decision Tree and Artificial Neural Networks to be able to find the best model that is correctly able to predict based on inputs about whether there would be a fire or not. We make use of features like the date, Temperature, Rolling Temperature, Fine Fuel Moisture Code, Duff Moisture Code, Drought Code, Initial Spread Index, and Build Up Index. The best performing model is the Decision Tree model which has an accuracy of 93% and an F1 score of 0.9.


## Libraries used
- Pandas
- Numpy
- Scikit learn
- Matpltlib
- Seaborn
- PyTorch

## Table showing the performance of the models

For Baseline and Trivial models:
![image](https://user-images.githubusercontent.com/68809236/166614294-412945b0-ae73-45ae-9636-ba3d70fbbe09.png)


For ML models:

![image](https://user-images.githubusercontent.com/68809236/166614377-0b3d42c1-491b-4aac-b1b6-127bc543cdff.png)

## Conclusion
We have implemented seven different machine learning models for classification of forest fires namely Trivial, Baseline, Support Vector Machine, Naive Bayes Classifier, Logistic Regression, Decision Tree and Artificial Neural Networks. We found that the best performing model from all of them was the Binary Tree Classifier which had an accuracy of 93.3% and F1 score of 0.9 on the test set. Since our dataset is highly imbalanced, the f1 score plays an important role. The train data contains 62.5% of Class Fire label i.e. label 1 and 37.5% of Class No Fire label i.e. label 0. The F1 score is the harmonic mean of precision and recall.
The F1 score can range from 0 to 1. A score close to 0 indicates that the model is unable to classify points correctly and a score close to 1 indicates that the model is able to classify the points correctly. So, the F1 score of 0.9 shows that our Decision Tree model is able to classify Fire and No Fire. Only 3 days have been classified as False Negatives, as can be seen from the confusion matrix in Section 3.4.6. Further work can be done to bring this number down to zero, which is the ideal case. 

## Future Work
We plan to work on extending our project by working on the problem of forest fires in California since each year California faces the problem of more than a dozen forest fires. We plan to collect data related to wind, region and climate from the past years which would be helpful in creating a model that can predict fires in this region. We can also extend the work to building an application that can provide real time prediction of forest fires.
