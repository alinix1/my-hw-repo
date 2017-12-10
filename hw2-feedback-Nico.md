### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Nice! I do not have many notes at all. You're getting more comfortable with using Python and Pandas. So, I recommend you keep on practicing! What you can do is try and focus in on efficient methods and striving for some pythonic code. For example, you will notice that all over the place, people will use `.apply()` methods and list comprehensions. Check these links!
http://treyhunner.com/2015/12/python-list-comprehensions-now-in-color/
http://www.pythonforbeginners.com/basics/list-comprehensions-in-python


**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html

Also, playing with statistical tests for, say, normality is super handy. Gives you some concrete information to you claim that it is approximately normally distributed. If your model doesn't perform well, that can give you some insight into why if your model relys on that as an assumption.
