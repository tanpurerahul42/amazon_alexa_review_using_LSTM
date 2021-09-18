# amazon_alexa_review_using_LSTM

The project involves amazon alexa product reviews using NLP and LSTM algorithm. RNN algorithm can't be used because of the Vanishing gradient.  
One of the major problems of RNN is the Vanishing gradient. In any neural network, the weights are updated in the training phase by calculating the error and back-propagation through the network. But in the case of RNN, it is quite complex because we need to propagate through time to these neurons.

The problem lies in calculating these weights. The gradient calculated at each time instance has to be multiplied back through the weights earlier in the network. So, as we go deep back through time in the network for calculating the weights, the gradient becomes weaker which causes the gradient to vanish. If the gradient value is very small, then it won’t contribute much to the learning process.

                                   New weight = Old weight – (learning rate * gradient)
                                   
We have completed building our LSTM model for classifying the sentiments for amazon Alexa product reviews into ‘positive’ and ‘negative’ categories. The accuracy of the model is 90.9%. We can further tune the hyperparameters to improve the performance of the model.                                   
                                   
                                   
