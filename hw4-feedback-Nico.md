### ***Project 4 Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Great work on this assignment! You walked through the key layout of the problem, your data, your analysis, results, and future things to explore. When you are walking through your analysis, it's nice, at times, to present some issues that you ran into when working on this problem (why is this problem... a problem?!). Another recommendation is for a few more plots that are associated with your model. For example, a decision tree diagram, predicted probabilities, model performance, roc curves, etc.!

***Risks and assumptions***  
Saying there is an assumption of *no* multi-collinearity is a bit strong. In general, you assume there is low levels of multi-collinearity, and then you show how your data both exhibits this fact **and** you attempt to avoid it (ie. not including certain features and/or one hot encoding, where we drop one column).

***Confounding factors***  
Confounding factors are typically features that are *not* included in your model. These variables are the ones that are the external factors that may impact your outcome via impacting a feature (eg. causation vs. correlation: butter sales are highly, negatively, correlated to divorce rates. If you regress, you will get a "good" model, but that doesn't mean a lot)!
