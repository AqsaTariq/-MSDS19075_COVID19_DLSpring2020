# Dataset(Covid-19):
Dataset is provided here part 1:
https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=1

# Multilabel Classification Covid-19
Description about Models 
Two Models were used: VGG16 and ResNet18 with modiftication in Fully connected layers.

  
Fully Connected layers modified for ResNet18 as:
   Sequential(
  (0): Linear(in_features=512, out_features=500, bias=True)
  (1): ReLU(inplace=True)
  (2): Dropout(p=0.1, inplace=False)
  (3): Linear(in_features=500, out_features=350, bias=True)
)

With learning rate 0.001, batch size 32 , Epochs 5 and gamma 2 of Focal Loss I got the following accuracy. And with the following changes in FC layers of pretrained Resnet18.
Sequential(
  (0): Linear(in_features=512, out_features=500, bias=True)
  (1): ReLU(inplace=True)
  (2): Dropout(p=0.1, inplace=False)
  (3): Linear(in_features=500, out_features=350, bias=True)
)

Training Loss is : 3.3721902223740607e-13 at epoch 4
Training Accuracy : 63 % at ecpoch 4

Validation Loss is :  0.0 at epoch 4
Validation Accuracy : 63 % at ecpoch 4

Accuracy and Loss Curves:

  ![](image.png) 
________Train Confusion Matrix, Precision, Recall, F1-Score__________

resnet18_entire_withFocalLoss_Train_confusion_Matrix
F1 score: 0.5071240175708435
 
________Validation Confusion Matrix, Precision, Recall, F1-Score__________

resnet18_entire_withFocalLoss_Valid_confusion_Matrix
F1 score: 0.49567523358695387
 


Tools Used:
Python
Pytorch

Note:
“This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.”
