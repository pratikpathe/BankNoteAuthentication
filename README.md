# BankNoteAuthentication
Fake Currency Detection is a real problem for individuals as well as businesses. Counterfeiters are finding new methods and techniques to produce Fake banknotes, which are totally indistinguishable from real money, at least for the eyes of humans. Some technological advancement in printing and scanning industry made counterfeiting problem to grow more faster. As a result, counterfeit currency affects the economy and reduces the value of original money. Therefore, it is most needed to detect the fake currency. Finding counterfeit currencies with these methods is less efficient and time consuming. To overcome the above problem, we have proposed the detection of counterfeit/Fake currency using Machine Learning. Our work identifies the fake currency by examining the currency characteristics such as variance, asymmetry, kurtosis and image entropy of banknote. The proposed approach efficiently identifies the fake currencies of 2000, 500, 200, and 50 whose features are extracted from wavelet Transformation with less time consumption.

The dataset contains these four input characteristics:

  •	The variance of the image transformed into wavelets
  
  •	The asymmetry of the image transformed into wavelets
  
  •	Kurtosis of the image transformed into wavelets
  
  •	Image entropy

The target value is simply 0 for real banknotes and 1 for fake banknotes. 
In this project, our goal was to build a trained model which can classify new input images based on features extracted after wavelet transformation. The component of processing the image and doing wavelet transformation was not part of the project. This component can be developed as another project. Our goal in this project was to emphasize on the machine learning aspect of the problem. Hence, we worked with the transformed images. To test the performance of our model, we have been holdout a test set which will also be labeled, but not visible to our model. We obtained high accuracy for our model as the problem is financial in nature.

I have used Random Forest algorithm to solve this problem.
Random Forest is a popular machine learning algorithm that belongs to the supervised learning technique. It can be used for both Classification and Regression problems in ML. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.
As the name suggests, "Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset." Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.

I have considered classifier models for the given problem. We have evaluated the performance of these classifiers using accuracy score evaluation metrics. We trained our classifier model on various sizes of training data, to analyze how it affects the prediction scores. Prediction scores would be obtained for test data, and for a subset of training data. We also calculated the time that is taken for training and prediction. 
