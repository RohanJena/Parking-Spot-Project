# Parking-Spot-Project
CSOC CV Project

In this ptoject i tried to make a parking spot detection integrating both opencv and deep learning that i learned during CSOC.
The folder contains a fullscale video of a parking lot along with 2 cropped video of the parking lot.Along with a dataset named clf-data. Which is used for training the Convnet model.
The main aim of the project is first getting the boundary box around each and every parking lot.Which is done by using the mask.png file.
After this prediction is made whether a car is present inside the boundary box or not using the model trained from the data.

Further more the perfomance is increased for real time application by controlling the number of frames after which the model is used tp predict and comparing a frame to previous frame.

main_code.py contains the code written for spot detection while the CONVNet.ipynb file fontains the custom model i trained and used in this project.
Using pickel library i saved the model as CustomCONVnet.p in the folder and used it in main_code.py.

Please note that the model is working fine parking_crop.mp4 video and it takes a bit to load in the whole parking_1920_1080_loop.mp4 file.

I have also added a screen recording on how the model performs for cropped video part.
