# Questions for the month of April
---
### 12/4/22 
***Ted wants to sell more cars***

Ted is just starting his first job.He is working at a major car dealership. Hundreds of cars go out the door every month, and Ted plans to help the company understand their customers a little bit more.After a week of obsessing over all the information they capture about every customer, Ted starts thinking about a good way to slice them into segments based on their characteristics.

The problem is that Ted is unsure about the best approach. Should he segment customers based on their purchase history, or should it be better to do it by age? What about the type of vehicle or purchase power?
How would you approach this problem if you were in Ted's shoes?
 Options-

    - Use an unsupervised learning algorithm to produce potentially interesting ways to segment the customers. 
    - Define beforehand a few segments, and train a supervised learning algorithm to classify every customer into one of them.
    - Use a supervised learning algorithm to produce potentially interesting ways to segment the customers.
    - Use a semi-supervised learning algorithm to process the data, thus taking advantage of both supervised and unsupervised techniques.
---
### 13/4/22
***Handling missing values***
    
The customer data the team received was not in great shape.After some analysis, they found that many values were missing, entire fields were incomplete, and some of the data was corrupted.Everyone knew they had to fix this before building the machine learning application they had been planning for a year. The team lead called a special meeting to discuss their next steps, and after some time, they narrowed it down to a few possibilities.

Which of the following are valid techniques they could use to handle the problems with their data?
 Options-
  
 - [ ] Replace missing values with the mean, median, mode, or other imputation techniques.
 - [x] Drop any rows or columns that contain missing or corrupted data.
 - [x] Predict the missing values using a separate machine learning model.
 - [x] Using machine learning algorithms that are robust to missing values.

---
### 14/4/22
***The mysterious case of the strange loss***

Jena has finally finished building a neural network!It took her some time to deal with the dataset, but she is finally ready to train the model.Fifteen minutes later, Jena notices that her training loss is not decreasing as expected; it stays much higher than she hoped for.Jena got back to the drawing board to investigate what could be happening.After a couple of hours, Jena has come up with a few potential reasons that could explain the problem.

Which of the following could be causing the loss to behave this way?

- [x] The regularization that Jena is using is too aggressive.
- [x] Jena is using a learning rate that's too low.
- [x] The neural network is getting stuck at local minima.
- [ ] Jena is using a learning rate that's too high.
---
### 15/4/22
***Looking behind François's Tweet***

Recently, François Chollet mentioned that you should never try to use a learning-rate schedule from an old dataset to train a new one. Imagine a scenario where you create a deep learning classification model to train on images from a security camera. During the exploration phase, you set up a specific training schedule that works well for your problem and gives you good performance.

When training a new version of the model — even when using the same architecture — with images from a different security camera, François' advice is to avoid using the same training schedule.

Which of the following could be François' thinking behind his advice?

    -The learning-rate schedule depends on the number of samples in the dataset, so the exact schedule won't work with a different size dataset.
    -The learning-rate schedule should change whenever we have a dataset from a different target distribution. This won't be the case if the target distribution is the same.
    -A new dataset changes the tradeoff between optimization and regularization. The learning-rate schedule is dataset-specific.
    -Learning-rate schedules are specific to the optimization mechanisms used by the model. A new dataset usually requires that we change the optimization process, which will invalidate the learning-rate schedule as well.
---
### 16/4/22
***Patricia is building a logistic classifier***

Patricia has been working on a logistic classifier for a new project.

She knows that the key to getting successful predictions depends on the error function she decides to use. She wants this function to have the following characteristics:

**The function should return a small number if the sample is correctly classified.
    The function should return a large number if the sample is incorrectly classified.
    The error for a set of samples should be the sum or average of the errors for all the samples.**

Patricia has several choices but would like to hear your opinion.
Which of the following would be the best error function for a logistic classifier?
    
    -Absolute error: a function that returns the absolute value of the difference between the prediction and the label.
    -Square error: a function that returns the square of the difference between the prediction and the label.
    -Log loss: a function that returns the negative logarithm of the product of probabilities.
    -Mean percentage: a function that returns the average error of the differences between predicted and actual values.
---
### 17/4/22
***The birthday paradox***

After a lot of begging, Lucia convinced Anna to go to a party together. Anna likes to spend most of her time with math books. The change of scenery was good, so she showed up.After an hour or so, Lucia noticed that Anna was not having fun, so she decided to cheer her up with an interesting problem."Anna, there are 23 people at this party right now. What is the probability that two of them share the same birthday?"

What is the correct answer to Lucia's question?

    -There's about a 1% probability of two people sharing the same birthday.
    -There's about a 6% probability of two people sharing the same birthday.
    -There's about a 17% probability of two people sharing the same birthday.
    -There's about a 50% probability of two people sharing the same birthday.
---    
### 18/4/22
***Keeping pedestrians safe***

A team has been working on a self-driving car model to detect pedestrians crossing the street on images captured from the car cameras.Their model will help cars navigate busy areas while keeping everyone around safe. It's a critical and delicate piece to get to full autonomy.Despite initial promising results, they haven't settled on the best way to evaluate the model's performance.

A discussion starts with some initial ideas. Which of the following evaluation metrics would be the best for this problem?

    -The team should use the recall of the model, as defined by the percentage of detected pedestrians with respect to every image containing a pedestrian.
    -The team should use the precision of the model, as defined by the percentage of legitimate detected pedestrians with respect to every detected pedestrian.
    -The team should use the Fβ-Score of the model with a high value of β.
    -The team should use the Fβ-Score of the model with a low value of β.
---
### 19/04/22
***Thinking about softmax***

Remember the last time you built a machine learning multi-class classification model?

You probably used a softmax activation on the output layer of your network. It's a widespread practice, so there's a good chance you've done it. It's usually fun to think about why we do things the way we do them, so let's get into it.Which of the following statements is true about the softmax activation function when used in the output layer of a neural network?


    -The softmax function turns the network's input into a vector of probabilities that sum to 1.
    -The softmax function is a probabilistic or "smooth" version of the function that returns the index of the vector's largest value.
    -The softmax function turns a vector of real values into a sorted vector of probabilities that sum to 1.
    -The softmax function is a probabilistic or "smooth" version of the function that returns the vector's maximum value.
---
### 20/04/22
***Alice can't remember how One-Hot Encoding works***

When building a machine learning model, much of the work happens well before starting training.

Alice knows that she needs to prepare the data before it's ready. She has been looking into encoding some of the features on her dataset. One-Hot Encoding seems like a good candidate.It's been quite a while since Alice used One-Hot Encoding, and she can use some help.

Which of the following statements explains how One-Hot Encoding works?

    -One-Hot Encoding encodes a numerical feature into its categorical representation.
    -One-Hot Encoding creates additional features based on the number of unique values in a categorical feature.
    -One-Hot Encoding encodes a string-encoded feature into its numerical representation.
    -One-Hot Encoding encodes a string-encoded feature into its categorical representation.
---
### 21/04/22
***The anatomy of ReLU***

The Rectified Linear Activation Function, or ReLU, returns its input if it's positive or a zero otherwise.

In other words: ReLU turns any negative values into zero and leaves everything else unmodified. ReLU has become a popular activation function when training neural networks. Since it's a linear function and computationally straightforward to implement, models become easier to optimize and achieve better performance.There's something very interesting about combining Gradient Descent with ReLU, and to get there, we have to think a bit about the mathematical properties of ReLU.

Which of the following is true about the Rectified Linear Activation Function (ReLU)?

    -The function is neither continuous nor differentiable.
    -The function is differentiable but not continuous.
    -The function is both continuous and differentiable.
    -The function is continuous but not differentiable.
---
### 22/04/22
***Australian birds***

Marc was excited about the performance of his model.

He's been working on an app to classify photos of birds, and his model is performing very well on all metrics. Marc knows what he is doing and followed all the best practices: he split training and test data, used the proper evaluations metrics, balanced his dataset, and reviewed examples regularly to ensure there were no labeling errors. Finally, Marc launched his app.Positive feedback started rolling in except from one place: users in Australia complained the performance was awful. Marc was baffled.

What is the most likely reason for the problem?

- [ ] Marc didn't train the model long enough to capture all the necessary details of different bird species.
- [ ] Marc's model is too simple, and it couldn't learn the entire dataset of birds, leaving out those from Australia.
- [x] Marc's model suffers from sampling bias. He probably didn't include enough examples of Australian birds.
- [ ] Marc's model is suffering from data or concept drift.
---
### 23/04/22
***Breaking a function down into pieces***

We are trying to predict the price of a car.

Our company has a website where users sell and buy used cars. Deciding how much we should charge for a used car is complicated and error-prone.
We want to build an automatic price recommendation system using supervised learning. The Manufacturer's Suggested Retail Price (MSRP) of the car is our target variable. Since its distribution has a very long tail, we apply a log transformation before training the model.

**If our model for a single observation is y = f(x), what are x and y for this project?**

- [x] x is a feature vector containing the variables that describe the car, and y is the logarithm of the price of the car.
- [ ] x is a feature vector containing the variables that describe the car, and y is the price of the car.
- [ ] y is a feature vector containing the variables that describe the car, and x is the logarithm of the price of the car.
- [ ] y is a feature vector containing the variables that describe the car, and x is the price of the car.
---
