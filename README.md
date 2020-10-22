# Subset Selection
This is a project that seeks to answer question 6.10 in the ISLR textbook.
--
We have seen that as the number of features used in a model increases, the
training error will necessarily decrease, but the test error may not. We will now
explore this in a simulated data set.
Generate a data set with p = 20 features, n = 1, 000 observations, and an
associated quantitative response vector generated according to the model
Y = Xβ + Ɛ, where β has some elements that are exactly equal to zero. Split your data set into
a training set containing 800 observations and a test set containing 200
observations.
Perform best subset selection or forward stepwise selection -- on the training set,
and plot the training set MSE associated with the best model of each size. Plot
the test set MSE associated with the best model of each size.
For which model size does the test set MSE take on its minimum value?
Comment on your results. How does the model at which the test set MSE is
minimized compare to the true model used to generate the data? Comment on the
coefficient values.


Code is written in R Markdown.
--
Results

![question2_trainerrors](https://user-images.githubusercontent.com/66652338/96805690-3522b080-13e0-11eb-8c13-a29cbc3e0088.png)
![question2_testerrors](https://user-images.githubusercontent.com/66652338/96805695-3522b080-13e0-11eb-9316-fe05e15d7968.png)
![question2_truemodel errors](https://user-images.githubusercontent.com/66652338/96805694-3522b080-13e0-11eb-86cf-4a9bcc65f7d1.png)

