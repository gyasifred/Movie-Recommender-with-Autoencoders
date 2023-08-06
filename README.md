# Autoencoders for Movie Recommendations

This Jupyter Notebook demonstrates how to use Autoencoders for movie recommendations. It uses the MovieLens dataset and trains a simple Autoencoder neural network to predict user ratings for movies.

## Prerequisites
Before running the notebook, make sure you have the required libraries installed:

* Numpy
* Pandas
* PyTorch
You can install them using the following command:
```
pip install numpy pandas torch
```
## Dataset

The notebook uses the MovieLens dataset, specifically the ML-100K version. The dataset can be downloaded using the provided links:

* [Download ML-100K dataset](http://files.grouplens.org/datasets/movielens/ml-100k.zip)
* [Download ML-1M dataset](http://files.grouplens.org/datasets/movielens/ml-1m.zip)

Extract the datasets into the working directory before running the notebook.

## Getting Started
1. Open the Jupyter Notebook file **autoencoders.ipynb** using Jupyter Notebook or Jupyter Lab.

2. Execute the cells sequentially to go through each step of the process.

## Steps Covered

1. **Downloading the Dataset**: This section downloads the ML-100K dataset and unzips it into the working directory. Optionally, there's a link for the ML-1M dataset, but it won't be used in this notebook.

2. **Importing Libraries**: The required libraries for data processing and building the neural network are imported.

3. **Importing the Dataset**: Loads the MovieLens dataset containing movies, users, and their ratings.

4. **Preparing the Training Set and Test Set**: Splits the data into the training set and test set.

5. **Converting the Data into Torch Tensors**: Converts the data into Torch tensors for PyTorch compatibility.

6. **Creating the Autoencoder Architecture**: Defines the architecture of the Autoencoder neural network.

7. **Training the Autoencoder**: Trains the Autoencoder on the training set using Mean Squared Error (MSE) loss.

8. **Testing the Autoencoder**: Evaluates the trained Autoencoder on the test set.

Feel free to experiment with the hyperparameters and network architecture to improve the results. Happy coding and have fun with movie recommendations!