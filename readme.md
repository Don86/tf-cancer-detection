Modelling with various CNNs for the Kaggle competition: [Histopathological cancer detection](https://www.kaggle.com/c/histopathologic-cancer-detection)

## Overview

* Data *not* available from this repo, but freely available for download from [here](https://github.com/basveeling/pcam) under an MIT license
* Comprises 327,680 color images (96 x 96px) extracted from histopathologic scans of lymph node sections. Each image is annoted with a binary label indicating presence of metastatic tissue.

## Workbook - `workbook-custom-c12.ipynb`

A "basic" 12-layer CNN, +1 dense layer. Over 40,000 training images:
* 10 epochs - runtime ~20 mins - ~85% accuracy
* 50 epochs - runtime ~100mins - 92.7% accuracy. Could probably go further; accuracy line hadn't stopped increasing, but that's probably overtraining or something.

Best public scores are about 95-97%, typically using `DenseNet-169`.
