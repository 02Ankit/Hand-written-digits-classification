# Hand-written-digits-classification

### We are importing data from pytorch
### PartA : DNNs

#### No of Hidden layers = 2

##### -Loss for Train data and Loss for Validation data 

At Epoch Number: 1; Train Loss= 0.33; Validation Loss= 0.23

At Epoch Number: 2; Train Loss= 0.20; Validation Loss= 0.20

At Epoch Number: 3; Train Loss= 0.17; Validation Loss= 0.24

At Epoch Number: 4; Train Loss= 0.15; Validation Loss= 0.21

At Epoch Number: 5; Train Loss= 0.14; Validation Loss= 0.23

At Epoch Number: 6; Train Loss= 0.14; Validation Loss= 0.21

At Epoch Number: 7; Train Loss= 0.12; Validation Loss= 0.24

At Epoch Number: 8; Train Loss= 0.13; Validation Loss= 0.21

At Epoch Number: 9; Train Loss= 0.11; Validation Loss= 0.24

At Epoch Number: 10; Train Loss= 0.11; Validation Loss= 0.22

At Epoch Number: 11; Train Loss= 0.11; Validation Loss= 0.27

At Epoch Number: 12; Train Loss= 0.11; Validation Loss= 0.28

At Epoch Number: 13; Train Loss= 0.10; Validation Loss= 0.25

At Epoch Number: 14; Train Loss= 0.10; Validation Loss= 0.26

At Epoch Number: 15; Train Loss= 0.09; Validation Loss= 0.27



![hidden_layer-2_of-1](https://user-images.githubusercontent.com/67556459/220267808-1bbf1b85-5e3c-448b-8f50-ef99d70081e3.png)

![hidden_layer_2_of-2](https://user-images.githubusercontent.com/67556459/220267861-de5002a4-8e5c-475b-ad72-20da0e073080.png)

###### Review Classification Accuracy on Test Data =  96.29  %


#### No of Hidden layers = 3
##### - Loss for Train data and Loss for Validation data 

At Epoch Number: 1; Train Loss= 0.41; Validation Loss= 0.29

At Epoch Number: 2; Train Loss= 0.26; Validation Loss= 0.23

At Epoch Number: 3; Train Loss= 0.20; Validation Loss= 0.25

At Epoch Number: 4; Train Loss= 0.20; Validation Loss= 0.26

At Epoch Number: 5; Train Loss= 0.18; Validation Loss= 0.21

At Epoch Number: 6; Train Loss= 0.17; Validation Loss= 0.22

At Epoch Number: 7; Train Loss= 0.16; Validation Loss= 0.23

At Epoch Number: 8; Train Loss= 0.16; Validation Loss= 0.25

At Epoch Number: 9; Train Loss= 0.15; Validation Loss= 0.28

At Epoch Number: 10; Train Loss= 0.17; Validation Loss= 0.29

At Epoch Number: 11; Train Loss= 0.14; Validation Loss= 0.35

At Epoch Number: 12; Train Loss= 0.14; Validation Loss= 0.26

At Epoch Number: 13; Train Loss= 0.14; Validation Loss= 0.24

At Epoch Number: 14; Train Loss= 0.13; Validation Loss= 0.24

At Epoch Number: 15; Train Loss= 0.15; Validation Loss= 0.24


![hidden_layer_3_of-1](https://user-images.githubusercontent.com/67556459/220273220-7c441daa-67cd-4721-a796-fe6dab490cea.png)

![hidden_layer_3_of-2](https://user-images.githubusercontent.com/67556459/220273271-cea9b494-8d7c-414b-892f-4fd5c1ad1c93.png)

###### Review Classification Accuracy on Test Data =  96.19  %

### Part B: CNN

##### -Loss for Train data and Loss for Validation data 

At Epoch Number: 1; Train Loss= 0.49; Validation Loss= 0.32

At Epoch Number: 2; Train Loss= 0.21; Validation Loss= 0.22

At Epoch Number: 3; Train Loss= 0.15; Validation Loss= 0.17

At Epoch Number: 4; Train Loss= 0.12; Validation Loss= 0.14

At Epoch Number: 5; Train Loss= 0.10; Validation Loss= 0.12

At Epoch Number: 6; Train Loss= 0.08; Validation Loss= 0.11

At Epoch Number: 7; Train Loss= 0.07; Validation Loss= 0.10

At Epoch Number: 8; Train Loss= 0.06; Validation Loss= 0.09

At Epoch Number: 9; Train Loss= 0.05; Validation Loss= 0.08

At Epoch Number: 10; Train Loss= 0.04; Validation Loss= 0.08

![PartB_1](https://user-images.githubusercontent.com/67556459/220273701-408dd8bc-63bf-40d8-a7cf-4812c56db1c3.png)

![part-B-2](https://user-images.githubusercontent.com/67556459/220273724-8b66fdf7-a9e3-4dc9-95bd-99036f1f7953.png)

###### Review Classification Accuracy on Test Data =  97.77  %


With the given filter size and kernel, I am getting an accuracy of 97.85 in CNN, and in DNN accuracy = 95.24 with 3 hidden layers and accuracy = 96.16 with 2 hidden layers.

For DNNs and CNNs, Train Loss and Validation Loss at each epoch is provided. Also, the loss curve is provided.

### Part C: Various Choices
#### - Loss for Train data and Loss for Validation data 

##### Filter Size = 3; No of Neurons in Hidden Layer = 128

At Epoch Number: 1; Train Loss= 0.50; Validation Loss= 0.31

At Epoch Number: 2; Train Loss= 0.21; Validation Loss= 0.21

At Epoch Number: 3; Train Loss= 0.15; Validation Loss= 0.16

![part-c-1](https://user-images.githubusercontent.com/67556459/220274094-e91701f4-61f3-45ad-8760-b4cb7d52cce7.png)

![part-c-1-2](https://user-images.githubusercontent.com/67556459/220274159-0ab72dfd-943d-41c3-ace6-2c323396c20e.png)

###### Review Classification Accuracy on Test Data =  95.83  %

##### Filter Size = 3; No of Neurons in Hidden Layer = 256

At Epoch Number: 1; Train Loss= 0.51; Validation Loss= 0.32

At Epoch Number: 2; Train Loss= 0.22; Validation Loss= 0.22

At Epoch Number: 3; Train Loss= 0.15; Validation Loss= 0.17


![part-c-2-1](https://user-images.githubusercontent.com/67556459/220274755-6aa98d64-feab-448a-a46a-db356d7f73ff.png)

![part-c-2-2](https://user-images.githubusercontent.com/67556459/220274780-935b4526-1df5-47e5-a8db-c08fbd45fc25.png)

###### Review Classification Accuracy on Test Data =  95.64  %

##### Filter Size = 5; No of Neurons in Hidden Layer = 128

At Epoch Number: 1; Train Loss= 0.47; Validation Loss= 0.31

At Epoch Number: 2; Train Loss= 0.20; Validation Loss= 0.21

At Epoch Number: 3; Train Loss= 0.14; Validation Loss= 0.16



![part-c-3-1](https://user-images.githubusercontent.com/67556459/220274924-6a55cea9-8a78-477c-8b74-da6ea3e31fe8.png)

![part-c-3-2](https://user-images.githubusercontent.com/67556459/220274938-92f215c9-223f-448a-8703-40a09fec11f1.png)


###### Review Classification Accuracy on Test Data =  95.88  %


##### Filter Size = 5; No of Neurons in Hidden Layer = 256

At Epoch Number: 1; Train Loss= 0.45; Validation Loss= 0.30

At Epoch Number: 2; Train Loss= 0.20; Validation Loss= 0.20

At Epoch Number: 3; Train Loss= 0.14; Validation Loss= 0.15


![part-c-4-1](https://user-images.githubusercontent.com/67556459/220275114-e12be4b3-824a-40ce-9f67-44e9d429da2a.png)

![part-c-4-2](https://user-images.githubusercontent.com/67556459/220275164-f0b38731-9630-448d-b16c-068ca0e17b81.png)

###### Review Classification Accuracy on Test Data =  96.20  %
--------------------------------------------------------
##### Filter Size = 7; No of Neurons in Hidden Layer = 128

At Epoch Number: 1; Train Loss= 0.46; Validation Loss= 0.29

At Epoch Number: 2; Train Loss= 0.19; Validation Loss= 0.19

At Epoch Number: 3; Train Loss= 0.13; Validation Loss= 0.14

![part-c-5-1](https://user-images.githubusercontent.com/67556459/220275278-4790d451-99e6-47c6-ad2e-2ca7de89b945.png)

![part-c-5-2](https://user-images.githubusercontent.com/67556459/220275298-e9ce02ff-1be2-45d6-8152-ac4eeb0844cb.png)


###### Review Classification Accuracy on Test Data =  96.56  %
--------------------------------------------------------

##### Filter Size = 7; No of Neurons in Hidden Layer = 256

At Epoch Number: 1; Train Loss= 0.46; Validation Loss= 0.27

At Epoch Number: 2; Train Loss= 0.18; Validation Loss= 0.17

At Epoch Number: 3; Train Loss= 0.12; Validation Loss= 0.12

![part-c-6-1](https://user-images.githubusercontent.com/67556459/220275426-d4a56748-d14c-40bb-b496-27fb791d11dc.png)

![part-c-6-2](https://user-images.githubusercontent.com/67556459/220275442-798f871c-7ed0-45d8-9545-7cbdea5e06e8.png)

###### Review Classification Accuracy on Test Data =  96.88  %

--------------------------------------------------------

I have tested CNN with 6 cases (i.e., filters = [3, 5, 7] 
and hiddenLayerSizes = [128, 256]). 
And getting a maximum accuracy of 96.98% with Filter Size = 7; 
No of Neurons in Hidden Layer = 128 & 256 with 
#Epochs = 3. Loss Curve for all the cases are shown. 
It is observed that increasing the kernel size and 
increasing the number of neurons in hidden layer is 
increasing the accuracy on the test data. Increasing no of neurons in hidden layer 
means increasing the connections between the layers which results in better 
performance.












