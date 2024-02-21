# Assignment-Mahesh-Reddy
### Metrics Description
0.Splitted given Data into Train-70%, Validation-20%, Test-10% ratio, use george_test_dataset with 2 classes i.e george and no_george.
1. Tried with SGD optimizer / with and without using data Augmentation/ Using weight He/Kaiming initialization, Train with 35 Epochs with using Early Stopping by patience = 3, but i got around 70% accuracy
2. When i tried with ADAM optimizer with and without Augmentations/Using weight He/Kaiming initialization, Train with 35 Epochs with using Early Stopping by patience = 3.
3. Finally i choose Model with ADAM and without augmentations and without any Pre- weight initializer. Because it gives more F1score over accuracy. Others give quite high accuracy not F1 score.
4. I consider F1_Score because, since dataset is having imbalanced classes. So our aim is reduce FP and FN to classifify more accurately.
5.F1score is : 92% and Accuracy : 90%
6. Please refer Assignment_classification_model.ipynb file for code details.
