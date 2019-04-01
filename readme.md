Modelling with various CNNs for the Kaggle competition: [Histopathological cancer detection](https://www.kaggle.com/c/histopathologic-cancer-detection)
* `workbook-custom-c12.ipynb` - A "basic" 12-layer CNN, +1 dense layer. Can quite easily get ~85% accuracy, over 40,000 training images (10,000 test images) and 10 epochs, and total runtime of about 40 mins (20mins to extract and pre-process data, 20 mins to run 10 epochs). Could possible push up to >90% over 50 epochs.

Best public scores are about 95-97%, typically using DenseNet-169. 
