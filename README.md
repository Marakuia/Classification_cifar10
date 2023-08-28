# Classification_cifar10
### Classification
A convolutional neural network was implemented and trained to solve the classification problem on cifar-10 dataset. When creating a neural network class object, it is possible to set the number of hidden layers, convolution parameters, and an arbitrary activation function. <br/> 
Cross-entropy is used as a learning error function. At the end of each epoch, the classification accuracy is derived from the training and validation data. The accuracy on the validation data is 77%. <br/>
Dependence of the loss function on the epoch and dependence of accuracy on the epoch <br/>
![Image alt](https://github.com/Marakuia/Classification_cifar10/blob/main/loss_accuracy_classification.png)

### Classification based resnet-50
A neural network was implemented to solve the classification problem based on the pre-trained deep neural network ResNet-50. The accuracy of this neural network on the validation data was about 95%. <br/>
Dependence of the loss function on the epoch and dependence of accuracy on the epoch <br/>
![Image alt](https://github.com/Marakuia/Classification_cifar10/blob/main/loss_pretrain.png)
