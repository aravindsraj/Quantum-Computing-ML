Support Vector Machine(SVM) is a supervised machine learning algorithm that can be used for both classification or regression challenges. 
However,  it is mostly used in classification problems. 

In the SVM algorithm, we plot each data item as a point in n-dimensional space (where n is a number of features you have) with the value of each feature being the value of a particular coordinate. 
Then, we perform classification by finding the hyper-plane that differentiates the two classes very well.

Since I did this notebook from quantum approach, I would like to classify the SVM into two approaches. First as classical SVM and other one is quantum SVM.

<b> Quantum SVM
In quantum field, we have a specified library called QSVM which we can use similar to sklearn SVM.
But here we need to initialize certain keypoints which is QuantumInstance, ZZFeatureMap.
  
A **feature map** is related to dimensionality reduction; it involves reducing the amount of resources required to describe a large set of data.
**Quantum Instance** holds a Qiskit Terra backend as well as configuration for circuit transpilation and execution. When provided to an Aqua algorithm the algorithm will execute the circuits it needs to run using the instance.
