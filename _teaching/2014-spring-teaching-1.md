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


2. **What do we model in a Logistic Regression?**


3. **What is the loss function?**


4. **What is the ouput of LR?**

5. **Is it classification or regression?**


    It’s a regression algorithm used for classification using a logistic classifier using a threshold. For Multi class we use a one vs rest mechanism over the same 


6. **Is it high bias or high variance model?**


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


