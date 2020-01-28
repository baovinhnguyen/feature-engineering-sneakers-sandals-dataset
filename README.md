# Feature-Engineering-for-Sneakers-vs.-Sandals-data-set-

The project objective is to apply different feature engineering methods, transforming the input features that are given to the regression classifier. The goal is to classifiy sneakers vs. sandals images (28x28 each). First, I used a simple logistic regression, applying on the original training data set, as a benchmark. Next, I applied a few feature engineering methods: flipping the image horizontally (doubled the training data set), counting the number of black & white pixels (then added to the training data set as 2 new variables), and doing a histogram on the data set (added 10 new variables into the training data set). 

The result shows that counting the number of black & white pixels earns highest AUROC, following by doing histogram the training data set and flipping the image horizontally. 
