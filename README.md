# elec576-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [ELEC576 Homework 2 Solved](https://www.ankitcodinghub.com/product/elec576-submission-instructions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117090&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ELEC576 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Every student must submit their work as a pdf file for their report, and then all supplementary code be included in a zip file in the following format: netid-assignment1.zip. You should also provide intermediate and final results as well as any necessary code. Submit your pdf file and zip file on Canvas.

1 Visualizing a CNN with CIFAR10

In this problem we will train a CNN on CIFAR10. After the network is trained, you will visualize the weights of the first convolutional layer to see what filters it learned. In addition, we will see how the activations look like by using the test images.

a) CIFAR10 Dataset: CIFAR10 is a dataset composed of natural images that represent 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. CIFAR10’s images are RGB, and the resolution is 32 x 32. You will need to provide the additional preprocessing of turning the images to grayscale and then scaling the values.

For this part, you will use the provided template on Canvas (assignment 2 part 1 cifar10 skeleton.py) to implement the LeNet5 architecture for image classification as specified below.

b) Train LeNet5 on CIFAR10: In this part you will implement a LeNet5 and train

it on CIFAR10. Here is the configuration of LeNet5:

• Convolutional layer with kernel 5 x 5 and 32 filter maps followed by ReLU

• Max Pooling layer subsampling by 2

• Convolutional layer with kernel 5 x 5 and 64 filter maps followed by ReLU

• Max Pooling layer subsampling by 2

• Fully Connected layer that has input 7*7*64 and output 1024

• Fully Connected layer that has input 1024 and output 10 (for the classes)

• Softmax layer (Softmax Regression + Softmax Nonlinearity)

Plot train/test accuracy and and train loss. In addition, try to search for good hyperparameters (e.g. training methods, learning rate, momentum values …). Hint: Run a few epochs for each set of hyper-parameters and see how train/test accuracy and train loss change.

c) Visualize the Trained Network: Visualize the first convolutional layer’s weights. They should look like Gabor filters (edge detectors). Figure 1 shows examples of these filters. Notice that since you train your networks using gray-scale images, your filters will look slightly different. Also, show the statistics of the activations in the convolutional layers on test images.

2 Visualizing and Understanding Convolutional Networks

Read the paper Visualizing and Understanding Convolutional Networks by Matthew D. Zeiler and Rob Fergus. Summarize the key ideas of the paper.

(Extra Credit) Visualization of features in a fully trained model: Apply one of the techniques discussed in the Visualizing and Understanding Convolutional Networks paper on the convnet trained in Problem 1. In the paper they used a validation data set, but in your case you would use the test set. Show your curiosity here 🙂

3 Build and Train an RNN on MNIST

An RNN is well suited for tasks on time-series or sequential data. However, in this problem we will see how we can use RNN for object recognition and compare it to Assignment 1 where we used a CNN.

a) Setup an RNN: With a CNN, we would send in full images, yet with the RNN, inputs to the network are 28 pixel chunks of the images. For example, each row of the image will be sent to the network at each iteration. Use the starter code provided on the Canvas assignment page (assignment 2 part 2 rnn mnist skeleton.py) to implement an RNN model on the MNIST dataset like in Assignment 1. You should modify the following parameters to test how the model differs in performance.

Figure 1: Filters learned in the first convolutiuonal layer

• Number of nodes in the hidden layer

• Learning rate

• Number of iterations

• Optimizer

b) How about using an LSTM or GRU: change the starter code to use LSTM and GRU instead of RNN (hint: this should be a very easy modular change to a couple lines of code if you are doing it right).

Plot the train/test accuracies and the train loss. What do you notice and are the LSTM or GRU better? Also, change the number of hidden units and see how that affects the loss and accuracy.

c) Compare against the CNN: Compare with training using convnet in assignment 1 and describe any similarities or differences.
