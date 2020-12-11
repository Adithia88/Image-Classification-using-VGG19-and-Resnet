# Image Classification using VGG19 and resnet50

This is an implementation of image classification using cnn with vgg19 and resnet50 as backbone on Python 3, Keras, and TensorFlow. The model generates pattern to image classification

![Image Classification Sample](assets/1.PNG)

Dataset (Gdrive) : https://drive.google.com/drive/folders/1bwldB0owjeroiL8kLJL0NMJHqF4dfyjk?usp=sharing

The repository includes:
* Using google Colab
* Training code for image classification with VGG 
* Jupyter notebooks to visualize the detection pipeline at every step
* Teting
* Evaluation (confussion matrix)


# Getting Started
Download this repo and dataset too, if u want use this dataset
* [VGG16_CNN.ipynb](VGG16_CNN.ipynb) this is for training your own dataset. It shows an example how to training with your own data.
* [testing_load_image.ipynb](testing_load_image.ipynb) shows how to load model. This notebook explain how to test your data with model



# Training on Your Own Dataset

1. Make sure the path like this 

![Important Path](assets/2.PNG)

make sure again about Gdrive the important one dataset must be like this

![Gdrive path](assets/3.PNG)

![Train/val/Test Path](assets/4.PNG)

2. Upload all data to google drive ,which one matching with google colab email

3. Open google colab and use this code VGG16_CNN.ipynb, the part u must change just their class 

![train line codes you must change ](assets/5.PNG)

![train line codes you must change ](assets/6.PNG)

total lines u must change are 6 


# load model / Testing 

1. Make sure the path like this 

![Important Path](assets/2.PNG)

make sure again about Gdrive the important one dataset must be like this

![Gdrive path](assets/3.PNG)

![Train/val/Test Path](assets/4.PNG)

2. Upload all data to google drive ,which one matching with google colab email

3. Open google colab and use this code testing_load_image.ipynb, in this codes  just run all codes 

4. Upload Photo what u want to predict

![upload Photo](assets/7.PNG)

5. result like this

![Result](assets/8.PNG)

