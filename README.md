TASK---7
Step 1 : Import libraries, 
         pandas - for data manipulation and analysis.
         numpy - for numerical computing. 
         matplotlib.pyplot - for creating static , animated , and interactive visualizations. 
         seaborn - for better looking plots.
         train_test_split - this function is used to split a dataset into training and testing sets.
         GridSearchCV - automatically finds the best C and gamma for the RBF kernel. 
         cross_val_score - helps prevent overfitting by splitting the data into training and validation folds multiple times.
         StandardScaler - a feature scaling technique used in data preprocessing for machine learning. 
         LabelEncoder - used to convert categorical labels into numerical labels.
         svc - It is used to build Support Vector Machine (SVM) models for classification tasks.
         accuracy_score - used to calculate the accuracy of a classification model. It quantifies how well a model's predictions match the true labels. 
         classification_report - used to generate a detailed performance report for a classification model. It summarizes key metrics like precision, recall, f1-score, and support for each class.
         confusion_matrix - to evaluate the performance of a classification model.
         ListedColormap - used to create a custom colormap from a list of specified colors. 
Step 2 : Load the dataset.
Step 3 : Prepare Dataset.Assuming the target column is 'diagnosis'.Encode target.
Step 4 : For visualization, use only 2 features.Use first two columns for 2D plot.And,Standardize features.
Step 5 : Train SVM - Linear Kernel.
Step 6 : Train SVM - RBF Kernel.
Step 7 : Plot Decision Boundaries.
Step 8 : Hyperparameter Tuning (Grid Search).
Step 9 : Evaluate with Cross-validation.
Step 10 : Classification Report on Full Data.
