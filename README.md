# graphAttack

Computational graph library for machine learning

The main point is to combine mathematical operation together
to form a workflow of choice. The graph takes care of evaluating
the gradient of all the inputs to ease up setting up the
minimizer.

### Tutorial
 - To be found in tutorial.ipynb, covers basic usage and a simple linear regression model

### Examples
Setting up and training a dense neural network model
 - controlDense.py
 - controlTrainDense.py

Setting up and running a Convolution neural network model
 - controlCNN.py
 - controlTrainCNN.py

Setting up and running a Recurrent neural network
 - controlRNN.py
 - controlTrainRNN.py

## Additional Resources

http://www.deeplearningbook.org/
section 6.5.1 for more information on computational graphs and the rest of the book for more information about ML/deep learning.


### Dependencies
* [Python] 3.5 or above
* [numpy] - linear algebra for Python
* [scipy] - Scientific Python library, here used for utilities



License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [numpy]: <http://www.numpy.org/>
   [python]: <https://www.python.org/>
   [scipy]: <https://www.scipy.org/index.html>
   