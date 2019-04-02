Modelling with various CNNs for the Kaggle competition: [Histopathological cancer detection](https://www.kaggle.com/c/histopathologic-cancer-detection)

## `workbook-custom-c12.ipynb`

A "basic" 12-layer CNN, +1 dense layer. Over 40,000 training images:
* 10 epochs - runtime ~20 mins - ~85% accuracy
* 50 epochs - runtime ~100mins - 92.7% accuracy. Could probably go further; accuracy line hadn't stopped increasing.

Best public scores are about 95-97%, typically using DenseNet-169.
