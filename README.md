# Multi-resolution-deep-neural-network
MR-DNN: is based on deep learning used to extract rice field from Landsat 8 satellite imagery. Using publicly available satellite imagery data we train a convolutional neural net to predict rice fields in satellite images. MR-DNN achieved tremendous performance for the prediction of rice from Landsat 8 satellite imagery data.


<img src= "https://user-images.githubusercontent.com/32522237/128299362-2e3a4403-793e-4a52-a503-5f59a40c1ee7.JPG" width= "256"> <img src= "https://user-images.githubusercontent.com/32522237/128299366-597380aa-6e88-493b-90c6-ed9584818c10.jpg" width = "256">



# Data Downloading
You can download the satellite imagery from the (https://scihub.copernicus.eu/) or USGS Earth Explorer (https://earthexplorer.usgs.gov/). The following are the entity IDs of the images we used. To find images by their ID first select the right dataset (in our case Landsat 8 30m) and then go to "Additional criteria". Here are some IDs as an example we used:

**LC08_L2SP_139044_20181001_20200830_02_T1**
**LC08_L2SP_148039_20190917_20200826_02_T1**

# Dependencies
1) python==3.7.4
2) tensorflow-gpu==1.13.1
3) keras==2.2.4
4) sklearn==0.21.2
5) numpy==1.16.4
6) matplotlib==3.1.1
7) pandas==0.25.1


