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
  
    -Replace missing values with the mean, median, mode, or other imputation techniques.
    -Drop any rows or columns that contain missing or corrupted data.
    -Predict the missing values using a separate machine learning model.
    -Using machine learning algorithms that are robust to missing values.

---
### 14/4/22
***The mysterious case of the strange loss***

Jena has finally finished building a neural network!It took her some time to deal with the dataset, but she is finally ready to train the model.Fifteen minutes later, Jena notices that her training loss is not decreasing as expected; it stays much higher than she hoped for.Jena got back to the drawing board to investigate what could be happening.After a couple of hours, Jena has come up with a few potential reasons that could explain the problem.

Which of the following could be causing the loss to behave this way?

    - The regularization that Jena is using is too aggressive.
    - Jena is using a learning rate that's too low.
    - The neural network is getting stuck at local minima.
    - Jena is using a learning rate that's too high.
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

