
# Cancer Detection

 This project uses the Jetson inference library to train an NVIDIA Jetson nano. From there it uses the ImageNet library and its dependencies such as Resnet-18 and Resnet-50 to train the model.
 For this project, I used it to identify first if a bran MRI was cancerous and then trained to classify the type of cancer between the 3 most common. Those are glioma, meningioma, and pituitary tumors.

![44](https://github.com/vsaic/Cancer-Detection/assets/103888349/380bc227-59e9-4bb6-a0aa-d7d1ba579c54) ![4](https://github.com/vsaic/Cancer-Detection/assets/103888349/3b589ccb-4025-41d6-a79f-a45280ac502b) ![out18](https://github.com/vsaic/Cancer-Detection/assets/103888349/767ef7ea-96c4-40f5-9403-cbdbf0a7f91b) ![46](https://github.com/vsaic/Cancer-Detection/assets/103888349/981b3ebd-9a40-4ab2-ab18-2836c277bba9)








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

1. Start by setting up your jetson nano with an SSH connection to VScode
2. Next download the jetson inference library to set up the enviornment(https://github.com/dusty-nv/jetson-inference)
3. Next download a brain cancer dataset made for image classification.
4. If not done already split this data into train, test, and val folder. With 80%, 10%, and 10% of the data respectively.
5. Now we can train and test our model. To do so fall the step lsited here starting from step 4 of the traing a network section (https://student.idtech.com/courses/331/pages/old-re-training-image-classification-models-2?module_item_id=26828)

