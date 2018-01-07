### ***Project 3 Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Awesome job on this assignment! You burned through it, and went ahead and tried out some sklearn models too. That is a great practice. Try things one way, and then try it another!

***Train/Test Splits***  
Nice function! As you did later, though, you can definitely just use sklearns implementation.

***Increasing Accuracy and Overfitting***  
Generally speaking, your training loss will always be lower than your testing loss. Thus, of course, there is always some level of over-fitting (unless you truly did underfit and you get the reverse!). The primary method of reducing loss is, as you note, pretty data dependent: more, better, data and more, better, features extracted. As great as these models are, they are not much with out a _lot_ of good data, with good set of defined features.

The one way that you could, and should, experiment with building better models with less reduction in accuracy is to play with regularization. As you may recall, regularization will help you reduce variance by introducing a bit of bias into your model.

***Other models!***  
Finally, another area you should/could explore is to experiment with other models! In particular, you could experiment with some more diverse linear models (SVMs) and some non-linear models (knn, tree based models, etc.) models! The one warning I have is that traidtionally these models do not perform well with few instances. 
