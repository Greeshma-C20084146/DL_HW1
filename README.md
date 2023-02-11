# DL_HW1
# Homework 1
##### Python code included in Homework 1 illustrates a few of the core Deep Learning ideas.
##### Function Simulating simulated a sin function and built multi-layer neural network models.
* Creating and transforming Tensors
* Loss Functions
* Accuracy
* Activation function
* Epochs
![image](https://user-images.githubusercontent.com/125087684/218280282-bac009c2-f3b3-47ad-aa7b-7c35cadb550d.png)![image](https://user-images.githubusercontent.com/125087684/218278408-8550a8f4-ace1-4343-bece-6b20314cd30a.png)

##### Working with the CIFAR-10 dataset developed a neural network model to categorize the CIFAR dataset, and then plotted the graphs for accuracy and loss to comprehend the different sorts of concepts in the neural network:

* Convolution Neural Networks
* Fully connected layer - dense layer
* Maxpool layer
* Activation Function
* Dropout, weight_decay

![image](https://user-images.githubusercontent.com/125087684/218278593-fd0ba81e-88fd-4019-be3a-8ce4d0801c67.png)![image](https://user-images.githubusercontent.com/125087684/218278615-26e08f36-4eb0-4841-a2df-92a5cf6bbc5e.png)

##### Compare Parameters Changing a neural network model's parameter number allowed to better grasp the relationship between parameters' number and accuracy/loss.
* modifying parameters
![image](https://user-images.githubusercontent.com/125087684/218278717-490b1afd-d17d-45dc-8b57-5aaa09bd9c20.png)![image](https://user-images.githubusercontent.com/125087684/218278757-2197825a-df5c-4dae-ae2b-983e2fd4bd6c.png)

##### Random Labels To comprehend the effect of employing random labels for training a neural network, randomized training labels are input.

* Neural networks that memorize instead of learning

![image](https://user-images.githubusercontent.com/125087684/218279199-bf87b886-bbd5-4162-870b-a27d664dc846.png)

##### Analysis by Principal Components To see the reduction in weight dimensions, PCA was used to the weights learned from the CIFAR-10 dataset.

* Determined which weights are crucial for the model to learn
* Model weights and layers collection

![image](https://user-images.githubusercontent.com/125087684/218279475-94bcd1fd-0c98-40ae-b08c-d824c340f73a.png)  ![image](https://user-images.githubusercontent.com/125087684/218279484-fa55186f-7075-4705-a8d3-b0a4da945acd.png)

##### Networks with Neural Sensitivity On the CIFR dataset, two models were trained to determine the relationship between sensitivity and batch size.
* Batch size
* Validated sensitivity decline after optimal batch size

![image](https://user-images.githubusercontent.com/125087684/218279745-8ab954bc-6205-48c4-9f4e-a59c64296a92.png)  ![image](https://user-images.githubusercontent.com/125087684/218279762-bc17a2b2-4558-466a-a32c-d63b93525c8e.png)

##### Interpolation To visualize the model's generalizability, the weights of two Deep Learning models were interpolated.
* Generalization
* Interpolation
* Collection of weights

![image](https://user-images.githubusercontent.com/125087684/218279919-fb17a466-3fb5-44f6-99c8-2a81fdc6affe.png)![image](https://user-images.githubusercontent.com/125087684/218279923-13d3431b-a18a-4d1f-8327-f1e0ae16b816.png)

##### Gradient Norm viewed the notion of Loss vs. Change in Gradients when training, and observed the gradient norm.
* Gradients

![image](https://user-images.githubusercontent.com/125087684/218280063-4a983871-e4bb-448b-9092-8a5ff4fc195e.png)
## Python Packages Required
* Pytorch
* pandas
* numpy
* sklearn - only for PCA
* matplotlib
