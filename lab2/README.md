# Lab2

## Setting up 
* Type `git pull origin master'  in VM to bring the new files from the module sources in "clone" directory.
* Copy the lab files from the module directory into my github lab directory, in "lab2" folder.

## Histogram and Scaterplot
* Modify salaries.py: Change the excel source from customer.csv into vehicles.csv. 
* There is no need to change the code of plotting scatterplots because it talks about the relationship between current fleets and proposed fleets.
* Build two strings to describe the data of current fleets and new fleets repectively.(We need drop some extra data in current data which are corresponding to the blank part of new data)
* Possess the two strings according to  the original codes and plot the histograms as instruction says.
 
 ![scaterplot](./scaterplot.png?raw=true)
 ![histogram] (./histogram.png?raw=true)
 ![histogram_new] (./histogram_new.png?raw=true)


## Standard deviation comparison via the boostrap

* The standard deviation of current fleets is about 4.17, and standard deviation of new fleets is about 6.07.
* Modify boostrap.py: It is similar with the modification in salaries.py. Change the everything about mean into std, and also program both current and new fleets.
* Run the code, we obtian that the lower and upper standard deviation of current fleets are 3.39 and 4.84, and that of new fleets are 5.14 and 6.90.  
* The standard deviation is comprable.
	
