# pix2pix
A simple and clean implementation of state-of-the-art pix2pix model. Most of the code is taken from https://machinelearningmastery.com/how-to-develop-a-pix2pix-gan-for-image-to-image-translation/ and for a better understanding and explaination of the code you can explore the link. If you want to learn more about the theory of pix2pix GAN please feel free to read: https://learnopencv.com/paired-image-to-image-translation-pix2pix/ . 

# Dataset
The satellite to map dataset can be found here: http://efrosgans.eecs.berkeley.edu/pix2pix/datasets/maps.tar.gz
Extract the dataset to get image-map pairs. Seperate the images and their corresponding maps to different folder. Make sure that you're saving the map with an identical name to it's parent image.
Once the dataset is prepared, start the training using pix2pix_vi.ipynb file.

# Training
1. Set the runtime to "gpu" if you're running the code on google colab. 
2. Set the "path_images" variable to path to input images folder.
3. Set the "path_labels" variable to map images folder.
4. Set the image shape to power of 2. 
5. Start the training.
