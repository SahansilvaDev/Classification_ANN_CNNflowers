![image](https://github.com/user-attachments/assets/5a4b8428-06a0-4cfe-9256-f44015a9fd8d)

•	Import require libraries and image data set of flowers using url get those images ,and check how many images have.

 ![image](https://github.com/user-attachments/assets/73501633-5496-4702-8f7c-1f45653af197)

•	Again check image count and show to tulips directory first index in tulip flower display

 ![image](https://github.com/user-attachments/assets/774d6b6c-c9aa-41b0-a95c-20829a2ed683)

•	Define batch size and image width and height , From keras  we are define training dataset,20% validation(testing) and rest of for training, and randomly picking up images. Split dataset to training and validation.

![image](https://github.com/user-attachments/assets/d475a5cc-4679-48ff-9643-152069735bf3)
![image](https://github.com/user-attachments/assets/9553d31a-2c7f-4cd0-8114-4187f80ed215)

 
•	Asking what are the class names and display it and look at sample of data.

 ![image](https://github.com/user-attachments/assets/9e2c6c6a-eb80-4fd5-b129-e6a0644b642e)

•	Scale the images and then using 32 filter of 3 by 3 , and produce 32 images, do changes images and go though relu neuron, and also gp through maxpooling layer and again go through convolution and also again maxplooling and same as before go those layers after that all pixcel get one array (flatten) and 128 neuron connected to number of classes
•	Using adam optimizer getting an accuracy
 ![image](https://github.com/user-attachments/assets/ab642b2e-7a67-4f10-a3ae-3335aee76f4e)

•	Train and validate run in 10 times.
