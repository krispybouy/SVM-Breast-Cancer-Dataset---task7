In this task, I implemented Support Vector Machines for both linear and non-linear classification.

## What I Did
1. Loaded the local dataset and handled missing values.  
2. Encoded categorical features where needed and normalized all numeric columns.  
3. Trained SVM models using both **Linear** and **RBF** kernels.  
4. Visualized decision boundaries for both kernels using two selected features.  
5. Tuned hyperparameters like **C** and **gamma** with GridSearchCV.  
6. Compared the base model’s performance with the tuned one to understand how complexity affects generalization.

## Tools Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Key Learnings
- Linear SVM creates a simple straight-line separation, while RBF can model complex, curved boundaries.  
- Feature scaling is crucial since SVMs depend on distance-based separation.  
- Hyperparameter tuning doesn’t always guarantee better real-world accuracy — sometimes the base model generalizes better.  
- Visualizing the boundaries helped me clearly see how the kernel choice changes the decision regions.
