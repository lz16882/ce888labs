# Lab8


## Lab Exercises 

- [ ] Run ``python imdb.py`` and note somewhere the test accuracy score
      Because running the whole data is too time-consuming, I only record the first result in each question.
- The result is:
	* `loss: 0.4868 - acc: 0.7582 - val_loss: 0.3525 - val_acc: 0.8431`
- [ ] Modify the code to add one more layer of 64 ``relu`` units after the embedding layer record the score
- The result is :
	* `loss: 0.5073 - acc: 0.7446 - val_loss: 0.3567 - val_acc: 0.8430`
- [ ] Modify the code and add a dropout layer after the relu layer
- The result is :
        * `loss: 0.5202 - acc: 0.7357 - val_loss: 0.3613 - val_acc: 0.8436`	
- [ ] Remove the layers you have added previously Convolution layer followed by a relu non-linearity and global max pooling (see lecture notes)
     * `x = Convolution1D(64, 3, border_mode='same')(x)`
     * `x = Activation('relu')(x)`
     * `x = GlobalMaxPooling1D()(x)`
- The result is :
	* `loss: 0.4968 - acc: 0.7518 - val_loss: 0.3864 - val_acc: 0.8315`	  
- [ ] Modify the code and add an LSTM layer in place of the convolution layer
     * `x = LSTM(128, dropout_W=0.2, dropout_U=0.2)(x)`
- The result is :
	* `loss: 0.5350 -acc: 0.7240 - val_loss: 0.4201 - val_acc: 0.8172`
- [ ] Use both an LSTM layer and a Convolution layer and merge the results with a Merge layer
     * `z = merge([x,y], mode = 'concat')`
- The result is :
	* `loss: 0.4788 - acc: 0.7660 - val_loss: 0.3899 - val_acc: 0.8303`
