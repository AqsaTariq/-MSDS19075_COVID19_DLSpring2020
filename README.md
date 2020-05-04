# Dataset(Covid-19):
Dataset is provided here part 2:
https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=1

# Multilabel Classification Covid-19
<b> Description about Models  </b> <br>
Two Models were used: VGG16 and ResNet18 with modiftication in Fully connected layers.<br>
#### <b> Resnet18 with Focal_Loss </b>
##### Accuracy<br>
Training Accuracy : 68 % at ecpoch 9 <br>
<br>Train Confusion Matrix <br>
![renet_with_Focal_Loss_Train](https://user-images.githubusercontent.com/64742393/80945440-ade57000-8da0-11ea-9835-d40cfa99c511.png)
<br>Validation Confusion Matrix <br>
![resnet_with_focal_loss_Valid](https://user-images.githubusercontent.com/64742393/80945451-b2aa2400-8da0-11ea-8b00-8eaf41d08480.png)<br>

#### <b> VGG18 with Focal_Loss </b><br>
Training Accuracy: 64.786%: <br>

#### <b> Resnet18 with BCEWithLogits_Loss </b><br>
Training Accuracy: 59.741%
<br>Train Confusion Matrix <br>

<br>Validation Confusion Matrix <br>

<br>
#### Model Weights:
https://drive.google.com/drive/u/1/folders/1j-I2lfw6sDZoRm87v38p1nXwlojvXU9w

# Tools Used:
Python
Pytorch

Note:
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”
