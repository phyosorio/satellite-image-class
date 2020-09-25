# Classification of satellite images
Here I'm going to put some classification codes of satellite images. The dataset is avaliable at https://www.kaggle.com/crawford/deepsat-sat4.
This code was inspired by the one published by Arpan Dhatt at https://www.kaggle.com/arpandhatt/satellite-image-classification.

I used tensorflow 2.3 for training a neural network, and the network was trained on GTX 1070. 

The code start with reading the original files in csv format, then process the data and safe them with npy format. I strongly recommend you to one read and process your data, save them as npy, then for each time you need to reaload your data from files, read the npy not the csv. It will be faster!!!

 
