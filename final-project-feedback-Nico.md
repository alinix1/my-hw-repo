### ***Final Project Feedback***

***Nico Van de Bovenkamp***

***

**Overall:**  
Fantastic job! You have come a long way. That was a lot of work you put in -- and it worked!

I don't have any advice as of now. As you can see, the basic architecture proved to work exceptionally well. The only final things you could do, as you noted, was experiment with different forms of regularization: dropout, photo augmentation (re-scaling, rotation, etc.), etc. Otherwise, you would just be experimenting with slightly different architectures.

I also might recommend that you try out some different optimizers. Adam has become quite popular as of late.

**Presentation**  
For the presentation, I suggest that you try your best to find samples of images, with and without diseases, and see which ones you ended up classifying and misclassifying. This brings the reality to the project. It's likely that there are just images of certain specific diseases that are dissimilar from the others, thus your model will not generalize. Just grab those indexes, and show those images!
