Food Image Classifier

Data science project example using deep learning for image classification

Overview
For this example project I built a food classifier to identify foods. This could be useful for someone who is new in a certain country. They could take a picture of a food and an app could serve them some information about the best resturent. This is the underlying model for building something with those capabilities.

I was able to get the model to predict the food with 79% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.

Notes
This notebook takes you through the process of creating an image classifer for various types of foods. 

Config
I recommend using google colab for this project as it makes the gpu configuration far easier. In google colab make sure that you go to runtime -> change runtime type -> gpu.

In colab, running the code should create the folder structure that you need. Drag and drop the photos located here into their respective folders. Technically you could skip the the folder creation and just drag and drop the data from the google drive into the colab file destination

Data
I used the following chrome extension to download the data from google images. FatKun Batch Download Image
