# Gesture-Recognition-Prototype-using-OpenCv-TensorFlow-GPU
This is a small prototype of the Gesture Recognition using TensorFlow-GPU using a small dataset.In this model ThumbsUp, ThumbsDown, Stop and Peace gestures are being recognized by using the Deep Learning architecture known as MobilNet_V2. This can easily be scaled up by increasing the number of training images and increasing the number of epochs.

For this project I used a windows machine with a 6-Core and 12-Thread CPU and a Nvidia RTX-3070 CUDA enabled Graphics Processing Unit so that TensorFloww-GPU can be used.
Here the Collecting Images.ipynb file is being used to gather data and then label them.
Then Detection.ipynb file is used to further process and ultimately make the detection onto the uploaded image.
The path of the image on which the object detetion has been performed can be given in the jupyter notebook itself.

Also the full model.json file is included which can be used as a pre-trained model and can be used as a base model.
# The output of the program is as follows
![image](https://user-images.githubusercontent.com/58784121/179416085-908ec434-c876-478d-a965-4e86e3ba1355.png)
