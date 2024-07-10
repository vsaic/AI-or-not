
# Cancer Detection

 This project uses the Jetson inference library to train an NVIDIA Jetson nano. From there it uses the ImageNet library and its dependencies such as Resnet-18 and Resnet-50 to train the model.
 For this project, I used it to identify first if a bran MRI was cancerous and then trained to classify the type of cancer between the 3 most common. Those are glioma, meningioma, and pituitary tumors.

![add image descrition here](direct image link here)

## The Algorithm

The algorithm used in this project is the Resnet-18 image classification algorithm.
The flow of the algorithm can be seen below, with all 18 layers of the algorithm.

![download](https://github.com/vsaic/Cancer-Detection/assets/103888349/3b2ae34d-4bbb-4dea-a0fb-c8dbda479349)

This algortihm itslef is part of a greater set of algorithms known as convelutional neural networks or CNN's for short. These algortihms are typicall used for image classification as they are excellent at classifiy variouse iamges due to the convelution layers, priary to the neural netowrk. Helping to condense data to better analyze it. It does so by taking the main iamge and looking at key parts of it pooling down the image into its key parts, these key parts are then firther eanalyzed for more important areas, through another convelutional layer. The process of condensing these images is something alled pooling and is done the through a filter(iamge shown below).

CNN

![94787Convolutional-Neural-Network](https://github.com/vsaic/Cancer-Detection/assets/103888349/2efc7231-3802-46ca-ad58-96de350608f7)

Filter

![0_zJENIIWIKIxR1jQk](https://github.com/vsaic/Cancer-Detection/assets/103888349/aef161e6-2e4f-4938-9572-c689e477a242)






## Running this project

1. Add steps for running this project.
2. Make sure to include any required libraries that need to be installed for your project to run.I

[View a video explanation here](video link)
readme.md
Displaying readme.md.
