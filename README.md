# Dataset(Covid-19):
Dataset is provided here part 1:
https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=1

# Multilabel Classification Covid-19
<b> Description about Models  </b> <br>
Two Models were used: VGG16 and ResNet18 with modiftication in Fully connected layers.<br>
With learning rate 0.001, batch size 32 , Epochs 5 and gamma 2 of Focal Loss I got the following accuracy. And with the following changes in FC layers of pretrained Resnet18.<br>
Sequential(
  (0): Linear(in_features=512, out_features=500, bias=True) <br>
  (1): ReLU(inplace=True) <br>
  (2): Dropout(p=0.1, inplace=False) <br>
  (3): Linear(in_features=500, out_features=350, bias=True) <br>
)
<br><br>
Training Loss is : 3.3721902223740607e-13 at epoch 4<br>
Training Accuracy : 63 % at ecpoch <br>
<br><br>
Validation Loss is :  0.0 at epoch 4<br>
Validation Accuracy : 63 % at ecpoch 4<br>

### Accuracy and Loss Curves:<br>

  ![4](https://user-images.githubusercontent.com/64742393/80921621-2100cf00-8d2c-11ea-9d3d-fae758758294.png)
![5](https://user-images.githubusercontent.com/64742393/80921622-252cec80-8d2c-11ea-8f56-32f1e7792fa7.png)<br>

##### resnet18_entire_withFocalLoss_Train_confusion_Matrix<br>
F1 score: 0.5071240175708435<br>
  ![6](https://user-images.githubusercontent.com/64742393/80921748-0b3fd980-8d2d-11ea-94bc-0a801a3aebef.png)<br><br>
##### resnet18_entire_withFocalLoss_Valid_confusion_Matrix<br>
F1 score: 0.49567523358695387<br>

![7](https://user-images.githubusercontent.com/64742393/80921753-0ed36080-8d2d-11ea-9a99-0a24c37d49e5.png)<br>
<br><br><br>

# Tools Used:
Python
Pytorch

Note:
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”
