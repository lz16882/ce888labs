# Lab5


- [ ] Load the data from the file `jester-data-1.csv`

- [ ] Split the data into validation, test and training set with 80:10:10 proportions with 
    *` train, validate, test = np.split(data, [int(.8*len(data)), int(.9*len(data))])`
- [ ] Use latent factor modelling to infer the hidden ratings of the users (they are labelled as "99" in the dataset) on the training set
    *   `26.0966279631`
	*   `25.1037342469`
	*	`24.7772725183`
	*	`24.5361698065`
	*	`24.3055392612`
	*	`24.0742490519`
	*	`23.8411563128`
	*	`23.6072645707`
    *   `23.37418156`
	*	`23.1436828378`
- [ ] Calculate the performance of the algorithm in the validation dataset by looping through the dataset without training
- [ ] Change hyper-parameters (i.e. learning rates, number of iterations etc) as needed so you can get good results
- [ ] Report the MSE on the test dataset

- [ ] (if you have time) Use pandas to find the best and the worst rated jokes

