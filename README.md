# Chest-X-Ray-COVID-19-Detection using Monk AI

![Stars](https://img.shields.io/github/stars/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification.svg?style=social)
![Forks](https://img.shields.io/github/forks/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification.svg?style=social)
![GitHub contributors](https://img.shields.io/github/contributors/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification.svg)
![Language](https://img.shields.io/github/languages/top/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification.svg)
[![Say Thanks!](https://img.shields.io/badge/Say-Thanks!-yellow.svg)](https://vedantkhairnar.ml)
[![HitCount](http://hits.dwyl.io/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification.svg)](http://hits.dwyl.io/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification)
![Issues](https://img.shields.io/github/issues/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification)
![PRsWelcome](https://img.shields.io/badge/PRs-welcome-informational)

## Newspaper Article 
![https://github.com/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/blob/master/extras/hitavada.jpg](https://github.com/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/blob/master/extras/hitavada.jpg)

## What is ResNet

ResNet is a short name for Residual Network. As the name of the network indicates, the new terminology that this network introduces is residual learning.

## What is the need for Residual Learning?

Deep convolutional neural networks have led to a series of breakthroughs for image classification. Many other visual recognition tasks have also greatly benefited from very deep models. So, over the years there is a trend to go more deeper, to solve more complex tasks and to also increase /improve the classification/recognition accuracy. But, as we go deeper; the training of neural network becomes difficult and also the accuracy starts saturating and then degrades also. Residual Learning tries to solve both these problems.

## What is Residual Learning?

In general, in a deep convolutional neural network, several layers are stacked and are trained to the task at hand. The network learns several low/mid/high level features at the end of its layers. In residual learning, instead of trying to learn some features, we try to learn some residual. Residual can be simply understood as subtraction of feature learned from input of that layer. ResNet does this using shortcut connections (directly connecting input of nth layer to some (n+x)th layer. It has proved that training this form of networks is easier than training simple deep convolutional neural networks and also the problem of degrading accuracy is resolved.

So, ResNet-50 is a deep residual network. The “50” refers to the number of layers it has. It’s a subclass of convolutional neural networks, with ResNet most popularly used for image classification.

The main innovation of ResNet is the skip connection. As you know, without adjustments, deep networks often suffer from vanishing gradients, ie: as the model backpropagates, the gradient gets smaller and smaller. Tiny gradients can make learning intractable.

The skip connection in the diagram below is labeled “identity.” It allows the network to learn the identity function, which allows it pass the the input through the block without passing through the other weight layers!

![](https://qphs.fs.quoracdn.net/main-qimg-03903ebf7079087adea3dc711c92ec31)

Similarly we have other Networks- ResNet-34 and ResNet-18

This allows you to stack additional layers and build a deeper network, offsetting the vanishing gradient by allowing your network to skip through layers of it feels they are less relevant in training.

## Insights : 

### With 3 Epoch, Results are as follows
### ResNet-50
        class based accuracies
            0. NORMAL - 97.2972972972973 %
            1. PNEUMONIA - 100.0 %
        total images:            148
        num correct predictions: 146
        Average accuracy (%):    98.64864864864865
### ResNet-34
        class based accuracies
            0. NORMAL - 95.94594594594594 %
            1. PNEUMONIA - 98.64864864864865 %
        total images:            148
        num correct predictions: 144
        Average accuracy (%):    97.2972972972973
### ResNet-18
        class based accuracies
            0. NORMAL - 100.0 %
            1. PNEUMONIA - 98.64864864864865 %
        total images:            148
        num correct predictions: 147
        Average accuracy (%):    99.32432432432432
  
Developer :

[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/0)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/0)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/1)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/1)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/2)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/2)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/3)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/3)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/4)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/4)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/5)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/5)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/6)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/6)[![](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/images/7)](https://sourcerer.io/fame/VedantKhairnar/VedantKhairnar/COVID-19-Chest-X-Ray-Infection-Classification/links/7)

[Vedant Khairnar](http://vedantkhairnar.ml/)
