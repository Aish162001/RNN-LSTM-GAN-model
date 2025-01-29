# RNN, LSTM, GAN implementation
1. The SMS Spam Collection Dataset
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
contains a list of sms-messages and whether or not they are spam.
a. Build a classifier using a RNN model
b. Build a classifier using a LSTM model
c. NOTE: both models above should have a similar number of parameters, (exactly
same is not necessary)
d. Compare the performance of the two models, and show some example results

2. Your next task is to create a RNN and an LSTM models, that given the first half of an
SMS, produces the remaining SMS
a. Here, you have to have a special <END> character or token, to allow your model
to indicate the end of output
b. Compare the performance of your LSTM and RNN models, and note that they
should have similar number of parameters

4. Create a Conditional GAN for MNIST for Fashion MNIST.
https://www.kaggle.com/datasets/zalando-research/fashionmnist
Recall that, in a conditional GAN, we give the generator a random codeword from the
latent space, as well as a label indicating which class of image we want, and the
generator tries to create an image of this class.
- The Discriminator is given pairs of (Image, Label) to classify as real or fake
- For each class, show 4 examples of generated images from random codewords
