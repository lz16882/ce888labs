# Lab7


- [ ] run ``python mnist.py`` and note somewhere the test accuracy score, and the result is below:
    * `Test score: [0.097207916113499229, 0.97389999999999999]`
    * `Test accuracy: [0.097207916113499229, 0.97389999999999999]`
- [ ] Modify the code to add one more layer of 64 ``relu`` units and record the score
    * `x = Dense(64)(x)`
    * `x = PReLU()(x)`
The result is:
    * `Test score: [0.1326725911730493, 0.97040000000000004]`
    * `Test accuracy: [0.1326725911730493, 0.97040000000000004]`
	
- [ ] Modify the code so that you are able to add as many layers of ``relu`` units as you want, controlled by a variable called ``n_hidden_layers``
    * `for i in range(0, n_hidden_layers):` 
    * `x = Dense(64)(x)`
    * `x = PReLU()(x)`
The result is:
    * `Test score: [0.11941951049849449, 0.9738]`
    * `Test accuracy: [0.11941951049849449, 0.9738]`
- [ ] Add a Dropout layer with strength of 0.5
    * `x = Dropout(0.5)(x)`
The result is:
    * `Test score: [0.14512907791214999, 0.97189999999999999]`
    * `Test accuracy: [0.14512907791214999, 0.97189999999999999]`
- [ ] Play around with different scores and optimise on the number of layers, it is found that the optimal hyperparameters are when the `n_hidden_layers = 3` and `Dense = 128`, the result is below:
    * `Test score: [0.094442345715908732, 0.98009999999999997]`
    * `Test accuracy: [0.094442345715908732, 0.98009999999999997]`
