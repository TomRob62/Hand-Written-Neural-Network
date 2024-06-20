7. [Points 2.5] In this homework, we are going to implement a neural network for the handwritten 
digit classification problem with the MNIST data. Please use the MNIST data that includes 100 
images on each label of 0 – 9. Dataset is given as a CSV file. Each row represents an image with 
the given class label in the first column.
You should implement a neural network (NN) and first create your training and testing with a 
random split of 80% training and 20% testing data. Compute accuracy for the test dataset.
Compare performance 3-layer NN, and 4-layer NN. For classification tasks using the SoftMax
classifier at the end of your NN. You can design the network by yourself. 
Example NN architecture:
The above example network includes three layers: input, hidden, and output layer. Given input 
images are 28*28 dimension. Output layer comprises of SoftMax layer.
Instructions: 
You can choose the number of nodes/neurons in the hidden layers, activation functions, loss 
function, etc. Train your model for at least 100 epochs. 
You can implement the neural network using any deep learning frameworks (e.g., tensor flow, 
torch, etc.)
(i) Clarify network design (NN) and hyper-parameters. [Points .5]
(ii) Draw a curve(s) of error (training and testing) vs a number of epochs for both neural 
networks. [Points 1]
(iii) Compute test accuracy for both networks and discuss comparative logic behind that 
performance. [Points 1]
Please submit this question (7) in a notebook with a properly executable code and output of 
each block. Note that non-executable code may be graded partially