# Dataset(Covid-19):
Dataset is provided here part 1:
https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=1

# Multilabel Classification Covid-19
<b> Description about Models  </b> <br>
Two Models were used: VGG16 and ResNet18 with modiftication in Fully connected layers.<br>
#### <b> Resnet18 with Focal_Loss </b>
##### Accuracy<br>
Training Accuracy : 68 % at ecpoch 9 <br>
####### resnet18_entire_withFocalLoss_Train_confusion_Matrix<br>
F1 score: 0.7329962676900846<br>
  ![6](https://user-images.githubusercontent.com/64742393/80921748-0b3fd980-8d2d-11ea-94bc-0a801a3aebef.png)<br><br>
####### resnet18_entire_withFocalLoss_Valid_confusion_Matrix<br>
F1 score: 0.7737092499619319<br>

![7](https://user-images.githubusercontent.com/64742393/80921753-0ed36080-8d2d-11ea-9a99-0a24c37d49e5.png)<br>
<br><br>

#### <b> VGG18 with Focal_Loss </b><br>
Training Accuracy: 64.786%: <br>

#### <b> Resnet18 with BCEWithLogits_Loss </b><br>

#### Model Weights:
https://drive.google.com/drive/u/1/folders/1j-I2lfw6sDZoRm87v38p1nXwlojvXU9w

# Tools Used:
Python
Pytorch

Note:
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”
