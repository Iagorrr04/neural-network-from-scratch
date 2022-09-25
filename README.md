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

## Architecture

<div align="center">

<img width="35%" src="https://raw.githubusercontent.com/Iagorrr04/neural-network-from-scratch/dev/content/images/architecture.png"> <img width="35.5%" src="https://raw.githubusercontent.com/Iagorrr04/neural-network-from-scratch/dev/content/images/layers.png">

</div>

The left most layer is called *input layer*, and each of the 784 positions contains the information about one pixel.

The middle layer is called *first hidden layer*.

In this case is the neural network is a *fully connected* model, because every  *output layer* is connect to every *hidden layer* before him.

## Learning process

This network is based in the *supervised* model, the netwok is trained with pairs of input and desired output, so it returns a output value, that is compared to the expected one, after that the *weights* and *bias* are ajusted in a way that minimize the difference between the output and the expected result.

The specific algorithm used to ajust the *weights* and *bias* is called *delta rule*, initially the values of the network are random values, and by each interation they are ajusted until reach a satisfactory value. It's important to don't reach a *over-traning*, state where the network specializes in the given data and just decorate the output, losing the capacity of generalization. So the ideal is that the network tranning stop when the error rate is admissible and the generalization capcity too.

## Todo

 - [ ] Add integration with Google Colab
 - [ ] Add details about the concepts.



<details><summary> <b>References and useful links </b> </summary>

[Building a neural network FROM SCRATCH (no Tensorflow/Pytorch, just numpy & math)](https://www.youtube.com/watch?v=w8yWXqWQYmU)


</details>


