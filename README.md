# Introduction
In many Machine Learning (ML) communities, I have observed that many people are often struggling with different problems which are actually rooted on the exact same problem. The main issue is not “how to perform this step?” but rather than “which step should be performed first?”. In addition, the existing tutorials and articles mostly cover different techniques to perform a specific step (for e.g., how to deal with imbalance class or skewed continuous features). Therefore, I proposed a template that provides a general workflow to guide the process of developing ML models for classification and regression tasks on tabular data in the Kaggle Competition setting. To my knowledge, this is the first notebook that is dedicated to establish the exact same workflow for various ML tasks.


### To-do list 

- [X] Binary Classification 
   
   * [Insomnia](https://www.kaggle.com/competitions/idao-2022-bootcamp-insomnia/overview)
   * [Titanic](https://www.kaggle.com/c/titanic)
- [ ] Multi-class Classification
    * [Body performance data](https://www.kaggle.com/datasets/kukuroo3/body-performance-data)
    * [Ghouls, Goblins, and Ghosts... Boo!](https://www.kaggle.com/competitions/ghouls-goblins-and-ghosts-boo/overview)
- [ ] Single-output Regression
    * Coming soon
    * Coming soon
- [ ] Multi-output Regression
    * Coming soon
    * Coming soon


### The boring questions :/ 

1) Why do we perform categorical feature encoding before data splitting?

2) Why do we perform feature transformation after data splitting?

3) Why do we deal with outliers first before imputing missing values?

4) Why do we perform oversampling and undersampling after feature transformation and feature encoding?
