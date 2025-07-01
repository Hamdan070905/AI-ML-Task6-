# AI-ML-Task6-

1: Import Required Libraries

             You import key Python libraries:

                    > pandas, numpy → Data manipulation
                    > matplotlib.pyplot → Visualization
                    > scikit-learn modules → For model building, scaling, evaluation
                    > ListedColormap → For color-mapped visual plots

 2: Load and Explore the Dataset

              > Load the Iris dataset (a classic multi-class classification problem with 3 flower types).
              > Extract features (X) and target labels (y).
              > Convert the data to a DataFrame for easy visualization using .head().

 3: Normalize Features (Feature Scaling)

              > StandardScaler standardizes the feature values (mean=0, std=1).
              > This is crucial for KNN because it uses distance-based calculations.

4: Train-Test Split

              > Split the dataset into 70% training and 30% testing using train_test_split.
              > This is to test the model's generalization to unseen data.

5: Fit the KNN Classifier

              > Initialize KNeighborsClassifier with k=3 neighbors.
              > Fit (train) the model on the training data.

6: Make Predictions and Evaluate

              > Use the trained model to predict labels for the test data.
              > Evaluate performance using:
                       > Accuracy – Overall correctness
                       > Confusion matrix – Breakdown of predicted vs actual
                       > Classification report – Precision, recall, f1-score

7: Experiment with Different K Values

              > Loop through values of k from 1 to 20.
              > Store error rates (how often predictions are wrong).
              > Plot a line graph of error rate vs k to visually find the best value for k

8: Visualize Decision Boundaries (with PCA)

              > Use PCA to reduce features to 2D for plotting (since Iris data has 4 features).
              > Train KNN on reduced data.
              > Use meshgrid to create a 2D plot space.
              > Predict the label for every point in that space.
              > Use contour plot to draw decision boundaries and scatter plot to show actual points.

