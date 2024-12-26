# SimpleNeuralNet
A neural network built from scratch and enhanced iteratively

The neural network has 1 flatter layer, 3 linear layers, 2 ReLU activation layers, 2 dropout layers, 1 sigmoid layer.
- The dataset is numerical with 7 features and one target feature
- Preprocessing steps: Null value removal, Outlier removal, Standard scaling (Scaled train and test sets separately to avoid data leaks).
- Neural net is trained on train data, validated using validation data, and separately tested using test data

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score

Initial model is improved using hyperparameter tuning of dropout rate, batch size, learning rate. With the best values additional optimisations like batch normalisation, learning rate scheduling, early stopping criterion, and data augmentation through Gaussian noise, accuracy on test data is enhanced iteratively.

-Visualisations of the evaluation is implemnted using accuracy vs epoch graphs, confusion matrices and ROC curve
