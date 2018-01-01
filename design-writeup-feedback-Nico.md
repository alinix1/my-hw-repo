### ***Design Write-up Feedback***

***Nico Van de Bovenkamp***

***

***Reading in the data:***  
As  you may have noticed in the guide/walkthrough and in the Keras book, you will notice that you will basically be consuming an array of 2D arrays, which represent images. You can do so with many tools as you've seen! Let me know how this goes as you move along.

***How many layers and NN architectures?***  
A Neural Net is fundamentally just some basic operations performed in a specific sequence/architecture and optimized with some algorithm. The architecture is the tricky part. I mentioned to you before, researches *basically* just have some intuition of what may work, try it out, and then think about it to rationalize why it worked. Basically, you want to start out with a basic starting point like the LeNet, and then move up from there! Change the activation functions (you will read this in your Keras book, but Relu's and their variants are the state-of-art and favored today).

Start working on getting the data in and processed, and then build out a basic architecture! Start, maybe, with some less than LetNet. Say, one convolution to a pooling layer to a fully connected layer! Let's chat soon!
