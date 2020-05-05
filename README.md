# RecurrentNeuralNetworks

## Sequence Learning Problems :
* Output depends on previous inputs also
* The length of inputs is not fixed
* Predicting the next character/Word : Auto completion

In sequence learning problems, we know that the true output at timestep ‘t’ is dependent on all the inputs that the model has seen up to the time step ‘t’. Since we don’t know the true relationship, we need to come up with an approximation such that the function would depend on all the previous inputs.

The key thing to note here is that the task is not changing for every timestep, whether we are predicting the next character or tagging the part of speech of a word. The input to the function is changing at every time step because for longer sentences the function needs to keep track of the larger set of words.
In other words, we need to define a function that has these characteristics:
Ensure that the output Yt is dependent on previous inputs
Ensure that the function can deal with a variable number of inputs
Ensure that the function executed at each time step is the same.

![](https://miro.medium.com/max/1400/1*I2TsC5UDAPykJni772v9cQ.png)
## Resource :

https://towardsdatascience.com/introduction-to-sequence-modeling-problems-665817b7e583
