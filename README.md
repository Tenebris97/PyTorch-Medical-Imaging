# PyTorch Lightning Medical Imaging Notebookes
‼️**NOTE: If notebook rendering takes too long or fails, simply put the link in [nbviewer](https://nbviewer.org/)**‼️

Last updated on September 5, 2023

## [COVID-19 CTScan Binary Classification](https://github.com/Tenebris97/PyTorch-Medical-Imaging/blob/main/PyTorch_COVID19_CT_BinaryClassification.ipynb)
+ [Dataset](https://github.com/UCSD-AI4H/COVID-CT/tree/master/Images-processed)
+ Fine-tuned on ResNet18
***
## [COVID-19 Infection Percentage Estimation](https://github.com/Tenebris97/PyTorch-Medical-Imaging/blob/main/PyTorch_Covid19_Infection_Percentage_Estimation(1).ipynb)
+ [Dataset & Challenge](https://competitions.codalab.org/competitions/35575)
+ Fine-tuned on EfficientNet_B1
+ 5-Fold cross validation
***
## [PyTorch_ODIR_Challenge_Multilabel]()
+ [Dataset & Challenge](https://odir2019.grand-challenge.org/)
+ Pre-trained model for fine-tuning: EfficientNet-B1 from [timm library](https://github.com/rwightman/pytorch-image-models/)
+ Multilabel Classification
+ Two images-from the right and left eyes-are fed into the network simultaneously
+ Metrics: Kappa, F1-score, AUC, , Focal loss, Acc
+ NOTE: Prediction phase is semi-wrong --> Will be fixed later
***
## [Xray Hip Joint Segmentation](https://github.com/Tenebris97/PyTorch-Medical-Imaging/blob/main/PyTorch_Xray_Hip_Joint_Segmentation.ipynb)
+ [Dataset](https://data.mendeley.com/datasets/zm6bxzhmfz/1)
+ Network: Unet++
+ Pre-trained model for fine-tuning: ResNet34 from [Segmentation Models library](https://github.com/qubvel/segmentation_models.pytorch)
+ Dice loss, Jaccard Index (IoU)
***
