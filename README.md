Goal:
To analyze how the accuracy of classifiers change when we vary dataset size and number of features used.

Note:
1. Dataset has boolean features.
2. Various combinations tried:  
  2.1. Dataset sizes: 300, 500, 1000, 1500, 1800 
  2.2. Feature set size: 100, 1000, 5000
3. Classifiers used: Decision Tree, Bagging with Decision Trees(Unstable classifier), Random Forest, Gradient Boosting.
4. Used RandomizedSearch to find setting of various parameters to the models.
5. Divided the data into train, test and validation sets.
6. Used Predefined split, so as to only use validation set during test in Randomized Search

Source Code:
https://colab.research.google.com/drive/1YeGqx3q3aLj2_37tfJYRKPNjLAsPixkP?usp=sharing



