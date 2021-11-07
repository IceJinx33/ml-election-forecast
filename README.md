# ml-election-forecast

1. Predicted 2016 county level election test results using a Logistic Regression model and a Decision Tree Classifier model. Our Logistice Regression model achieved a weighted accuracy of 76.661%.
2. Used 2012 county level election data in addition to the 2016 training data to perform feature engineering using a Logistic Regression model, achieving a weighted accuracy of 81.992%.
3. Used Breadth-First Search (BFS) on graph data indicating pairwaise county locality to create a cluster index feature - representing the average of the indices of clusters a county could belong to, in addition to the features used in the second model. A county belongs to a cluster when BFS can find a path from the county to another county in the cluster. The Logistic Regression model achieved a weighted accuracy of 81.299%.
