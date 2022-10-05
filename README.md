# Chest_x-ray_pneumonia_detection

Pneumonia is an infection-induced inflammation of the lung tissue that can result in major health issues and even death. Deep Learning is becoming increasingly crucial in assisting doctors in analyzing X-ray pictures to identify pneumonia. The precision of neural networks, on the other hand, is critical. In our study, we took an existing Deep Learning project on pneumonia identification and implemented numerous strategies to increase the model's performance.

* To solve the problem and improve the performances:
1. Reduced the overfitting through Data Augmentation.
   Starting with the given images, new images were created for every epoch using transformers to zoom, rotate and shift. The ImageDataGenerator function was used to apply the transforms. Data extension alone helped in improving the performance by 10%.


![image](https://user-images.githubusercontent.com/80577092/194073798-9b06084f-98a2-445c-ae78-a6911da5dac7.png)
![image](https://user-images.githubusercontent.com/80577092/194073858-f43b6030-0f98-481f-b530-3e8a85ed12d5.png)
![image](https://user-images.githubusercontent.com/80577092/194074176-de277fe8-7061-4a73-ab46-bd9b53f22e98.png)


2. Implemented transfer learning using three different CNN models: VGG16, Xception and ResNet that have been trained on the ImageNet database and the trained models were made available on Keras. 
For all three CNN models, again performance was improved by a few percent, resulting in both accuracy and precision of about 0.93.


# 1. SEQUENTIAL MODEL

RESULTS - 

![image](https://user-images.githubusercontent.com/80577092/194074270-5823eed6-b819-4c8f-9f07-80514369e058.png)
![image](https://user-images.githubusercontent.com/80577092/194074346-c04188aa-4a08-471f-92e1-57017dbc5bb5.png)
![image](https://user-images.githubusercontent.com/80577092/194074402-8343c071-59bb-43c3-a90e-196e72c09669.png)


# 2. VGG16

RESULTS -

![image](https://user-images.githubusercontent.com/80577092/194074640-8feb6a15-a2fc-41fe-994f-94ff2d9e61db.png)
![image](https://user-images.githubusercontent.com/80577092/194074892-d8e7ffbd-2af2-45d8-8436-ba99e7ea76a7.png)
![image](https://user-images.githubusercontent.com/80577092/194074932-f3984e94-420a-4af0-abab-8badd4aa8ce9.png)
![image](https://user-images.githubusercontent.com/80577092/194074986-69536f10-b181-433d-bebe-6821dcd2fa15.png)


# 3. ResNet152V2

RESULTS -

![image](https://user-images.githubusercontent.com/80577092/194075765-5f8df632-b170-45c7-b0d7-22313667fa92.png)
![image](https://user-images.githubusercontent.com/80577092/194075824-7f6a6ccc-5265-4840-b6e5-d00f90d18e9b.png)
![image](https://user-images.githubusercontent.com/80577092/194075875-716885bd-ae44-4754-8d64-2fa4b5c2bc08.png)
![image](https://user-images.githubusercontent.com/80577092/194075922-7e705062-abfb-408e-a01c-6e958041eab0.png)


# 4. Xception

RESULTS -

![image](https://user-images.githubusercontent.com/80577092/194076102-d6a2e456-4157-4cfa-82c0-c839a9545484.png)
![image](https://user-images.githubusercontent.com/80577092/194076169-b5786143-c52a-4343-8032-9570cbf91e6c.png)
![image](https://user-images.githubusercontent.com/80577092/194076304-f6787d4c-9981-4dc5-acff-d1c4615d3522.png)
![image](https://user-images.githubusercontent.com/80577092/194076389-bc3b3a7f-c7db-4932-9b65-c59af85eb5cb.png)
![image](https://user-images.githubusercontent.com/80577092/194076483-bdd592d1-9932-40d3-8842-51cc35f995f7.png)



# In this Project, Deep Learning has proven to be a useful option to quickly analyse X-ray images and assist doctors in diagnosis.
