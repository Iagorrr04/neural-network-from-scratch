<div align = "center">

# Neural Network From Scratch

</div>


This neural network consists of a simple recognition of decimal digits, in order to learn the fundamental of theory and logic behind a neural networks, this model was implemented only with mathematic and linear algebra, the only extra library used was [Numpy](https://numpy.org/).

To achieve this goal the the famous [MNIST digt recognizer dataset](https://www.kaggle.com/competitions/digit-recognizer) was used in this project.

## Dataset
The [MNIST digt recognizer dataset](https://www.kaggle.com/competitions/digit-recognizer) is composed of the files train.csv and test.csv that contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

<div align="center">

<img src="https://raw.githubusercontent.com/Iagorrr04/neural-network-from-scratch/main/images/dataset_example.png">

</div>

## Todo

 - [ ] Add integration with Google Colab
 - [ ] Add details about the concepts.



<details><summary> <b>References and useful links </b> </summary>

[Building a neural network FROM SCRATCH (no Tensorflow/Pytorch, just numpy & math)](https://www.youtube.com/watch?v=w8yWXqWQYmU)


</details>


