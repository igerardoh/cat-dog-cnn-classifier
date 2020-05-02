# cat-dog-cnn-classifier

### Description
The dataset used on this classification model comes from a competition that aimed to develop an image classifier trained from images with dogs and cats. This dataset can be accessed clicking in the following link: [Kaggle Cats and Dogs Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=54765)

##### Features

The attributes on this dataset are the information contained on every single image as an array of pixels [Black:0 | White:255]. Every array has the following shape: [image_width, image_height, channel]. Originally, the images contain 3 channels, one channel for every color (RGB).

##### Classes

- class 1 : dog
- class 2 : cat

### Dependencies
You can use `pip` or `conda` to install the dependencies:
- tensorflow
- matplotlib
- jupyter
- pandas
- pillow
- scikit-learn
- imageio
- OpenCV

### Usage
If you want to try this program, download this repo and launch jupyter to run it on your machine. 

### - - - TODO  - - -

* ENVIRONMENT PREPARATION
    * ~~Install library dependencies~~
    * Document installation and usage


* DATA EXPLORATION
    * Add dataset description
    * ~~Preview the structure of the dataset~~
    * ~~Add data visualizations~~


* DATA PREPROCESSING
    * ~~Apply standarization to feature data~~
    * ~~Apply one-hot encoding to categorical data~~
    * ~~Split data into training and testing sets~~
    * Output preprocessed data for faster preloading


* DATA ANALYSIS
    * ~~Define network parameters~~
    * ~~Define network structure~~
    * ~~Add different network configurations~~
        * ~~Define learning rate with different decaying methods~~
        * ~~Set up cost, optimizer, and accuracy function with different configurations~~
    * ~~Define model execution~~
    * ~~Visualize evolution of MSE on training and testing datasets through epoch iteration~~
    * ~~Visualize evolution of loss function~~
    * ~~Visualize evolution of learning rate~~
    * Add log and summary writer
    * Add Tensorboard visualization
    * Add checkpoints for model restoration


* MODEL DEPLOYMENT
    * Load a pretrained model
    * Test it with new data


* OTHERS
    * Update README files
    * Update all nbviewer links
    * Add Tensorflow 1.x, Tensorflow 2.x, keras, tf.keras, and scikit-learn data analysis notebooks
