[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"

# Udacity dog breed classification project

* This project is for capstone of Udacity. Requirements of this project are to complete a dog breed classifier which can detect and predict a dog's breed from an image input. 
* If there is no dog found in the image and there is a human in the image, then the algorithm should predict the breed that the human resembles. 
* The result is a pipeline which should return the data according to the algorithm above. 

![Sample Output][image1]

## Project Instructions

* You can find the dog dataset [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 

* Click [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) to download the human dataset.  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

* Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.

* Open the notebook and run all cells. You can call the function human_or_dog to pass the image to three different models - ResNet50, VGG16, InceptionV3 and get predictions on the image. You will find a sample run of images in the bottom most cell of the notebook.
```
jupyter notebook dog_app.ipynb
```

## Blog

For more information about the project and workflow visit my [medium post](https://medium.com/@anand0427/train-a-convolutional-neural-network-to-classify-dog-breed-196bf882ba73)