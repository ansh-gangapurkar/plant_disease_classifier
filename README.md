# Plant Disease Classification Model

This project aims to build a deep learning model for classifying plant diseases based on leaf images. The model is trained on a dataset of plant images with corresponding disease labels.

## Dataset

The dataset used for this project can be found [here](https://data.mendeley.com/datasets/tywbtsjrjv/1). I utilized Pandas and the .npy file format to store all images as a single dataset; please contact me if you would like access to it.

## Project Structure

- **Importing Required Libraries**: Includes all necessary libraries such as NumPy, pandas, matplotlib, OpenCV, TensorFlow, Keras, and scikit-learn.
- **Loading and Preprocessing Data**: Loading plant images and labels, displaying sample images, visualizing the distribution of disease labels, converting images from BGR to RGB, and resizing images to a fixed target size.
- **Building and Training the Models**: Constructing and training two different convolutional neural network (CNN) models to classify the plant diseases.
- **Testing and Evaluating the Models**: Testing the trained models on the test dataset and comparing their performance.

