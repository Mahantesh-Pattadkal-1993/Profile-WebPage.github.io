---
title: "Logistic Regression"
collection: teaching
type: "Notes"
permalink: /teaching/2014-spring-teaching-1
venue: "Session 1"
date: 2023-08-27
location: "City, Country"
---

Here I answer a list of fundamental questions on Logistic Regression.

Rescoures: [Blog](https://yury-zablotski.netlify.app//post/from-odds-to-probability/)

Questions:

---
1. **What is log odds of probability?**

    Probability of an outcome lies between 0-1, the sum of probability of all outcomes is 1. In case of binary event that has outcomes, "success" and "failure", the p(success) = 1-p(failure). 

    Odds of an outcome eg: "success" can be calculate as p(success)/p(failure). The log odds of a probability is a way to transform a probability value (which ranges from 0 to 1) into a logarithmic scale that ranges from negative infinity to positive infinity. 

2. **What do we model in a Logistic Regression?**

    In logistic regression, we model the probability of a binary outcome or event. Specifically, logistic regression is used to model the probability that a given observation belongs to a particular category or class.
    
    In other sense, we build a linear regression model with 
    X: input variables
    Y :log odds of probability

    

3. **What is the loss function?**


4. **What is the ouput of LR?**




5. **Is it classification or regression?**


    It’s a regression algorithm used for classification using a logistic classifier using a threshold. For Multi class we use a one vs rest mechanism over the same 


6. **Is it high bias or high variance model?**

    I would call it a a high bias model, because
    - It makes assumptions that the log odds of probability to be a linearly dependant on the independant features, this might not be true if the relationship is non linear.   
  



7. **Why do we use a sigmoid function for LR?**


8. **How do we interpret the LR model's result?**


9. **How do we regularize it?**


10. **Shape of decision boundary in LR?**


11. **How do we tune a LR model without changing the parameters?**


12. **What is the current implementation of LR in sklearn? Is it based on least squared?**


13. **Is scaling required in logistic regression? And if yes, how  do we interpret the weights from a LR model?**


14. **What is the difference between probability and likelihood?**
    
    Probability values are numbers between 0 and 1. When you add up the probabilities of all possible events, it always equals 1. You can use past data to make a guess about the chance of something happening in the future. For example, if you have 2 red chocolates and 4 blue chocolates in a box, the chance of picking a red one is about 0.33.

    Likelihood tells us how well our observations match a specific idea or pattern. For instance, if we think our data comes from a normal distribution, we can calculate likelihood for different guesses about its parameters (like average and spread). The values of average and spread that make the likelihood highest are the ones we'll use to describe our data's distribution.

---


