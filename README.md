# SuperResolution

Introduction
This is an AI project that increase the resolution of images by using a Autoencoder Neural Network. I trained a ResNet based autoencoder CNN for this project. I came to this architecture after months of training different kinds of models. I intailly used custom CNNs, pretrained CNNs such as VGGs etc. But then I came accros this Resnet architecture and autoencoders. Which I later combibed with the CNN MODEL for best results.
I trained this model on a set of 10,000 +images of size 256*256. This was a computationally heavy model and took around a avg of 15 hours to train the model for an avg of 10 epoochs on a intel i7 - 8th gen system with 12 Gb of RAM and 4Gb of  Nvidia GeForce GTX 950 GPU.
For now, I have developed only the model. And the web application on this service will be develpoed and deployed shortly. I have uploaded the latest and best version of the jupyter notebook.  

I welcome you to this project. Reach out to me for any queries and collaboration at bansalvarun116@gmail.com

Applications 
This is a crucial project in terms of its application. It has the potential to drastically decrease the cost of cameras while increasing the efficency and the quality of the image. Its has a special use case in homesecurity cameras which captures low resolution images. Stating the applications, I would also like to bring to your notice that is project is in its initial stages and would require a lot of data, computational power and expertise in AI to unfolds its potential. 


Technolgy used

AutoEncoders:
An autoencoder is a neural network architecture capable of discovering structure within data in order to develop a compressed representation of the data. 

![alt text](https://github.com/bansalvarun116/SuperResolution/blob/main/images/autoencoder.jfif)

Resenets :
In order to solve the problem of the vanishing/exploding gradient, this architecture introduced the concept called Residual Network. In this network we use a technique called skip connections . The skip connection skips training from a few layers and connects directly to the output. 
The approach behind this network is instead of layers learn the underlying mapping, we allow network fit the residual mapping. 

![alt text](https://github.com/bansalvarun116/SuperResolution/blob/main/images/resnet.PNG)


Results Demo:
![alt text](https://github.com/bansalvarun116/SuperResolution/blob/main/images/results.PNG)



