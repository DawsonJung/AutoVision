# AutoVision
Computer Vision to detect traffic objects using TensorFlow and Python.

Currently Detecting:
- Red Lights
- Green Lights
- Stop Signs
- SUVs
- Pickup Trucks
- Minivans
- Cars
- Vans
- Trucks
- Semi Trucks
- Bus
- Person
- Bicycles

I used a Mobilenet_v1 model from Tensorflow and retrained the network with a custom data set. I have pulled video from a vehicle dash cam built into a Tesla Model 3, then taken static frames from the footage and labeled them.

I labeled around 400 images and trained the model on that dataset, and the results were fairly accurate. 
These images are from the testing that I did from a dashcam. The model does a good job detecting traffic lights with fair accuracy as well as vehicles. There were many false positives, especially with the specific state of traffic lights and types of vehicles. 

![alt text](https://i.imgur.com/HDiVutZ.png)

![alt text](https://i.imgur.com/HTmeWs0.png)

![alt text](https://i.imgur.com/NgP6m9D.png)
