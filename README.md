# Chest_x-ray_pneumonia_detection

Pneumonia is an infection-induced inflammation of the lung tissue that can result in major health issues and even death. Deep Learning is becoming increasingly crucial in assisting doctors in analyzing X-ray pictures to identify pneumonia. The precision of neural networks, on the other hand, is critical. In our study, we took an existing Deep Learning project on pneumonia identification and implemented numerous strategies to increase the model's performance.

* To solve the problem and improve the performances:
1. Reduced the overfitting through Data Augmentation.
   Starting with the given images, new images were created for every epoch using transformers to zoom, rotate and shift. The ImageDataGenerator function was used to apply the transforms. Data extension alone helped in improving the performance by 10%.


![image](https://user-images.githubusercontent.com/80577092/194007364-fee86b20-85cf-4cfc-829b-49d5c080b032.png)
![image](https://user-images.githubusercontent.com/80577092/194007428-f5228fb7-4558-43fa-b427-a7fb5c753d4c.png)


2. Implemented transfer learning using three different CNN models: VGG16, Xception and ResNet that have been trained on the ImageNet database and the trained models were made available on Keras. 
For all three CNN models, again performance was improved by a few percent, resulting in both accuracy and precision of about 0.93.

# In this Project, Deep Learning has proven to be a useful option to quickly analyse X-ray images and assist doctors in diagnosis.
