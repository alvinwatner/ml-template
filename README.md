# Introduction

The application of Machine Learning (ML) to tabular data is one of the most popular tasks in the ML community because many areas (e.g., finance, medical) commonly use tabular data to store a set of information. The problems are mainly categorized into 2 parts: 

1. How to perform a specific step? 
2. Which step should be performed first? 

The first one focuses on various techniques to achieve a specific step (for example, handling skewed features with log transformation), while the second refers to the entire workflow from loading data to evaluating the model. The second problem is crucial as performing the wrong step could lead to serious problems, such as information leakage or degraded performance. Additionally, to my knowledge, there has not been a dedicated attempt to address the second problem so far. Therefore, in this project, I created a notebook that provides a general workflow (a step-by-step process) to guide the process of model development for different predictive tasks, including classification and regression, that is capable of achieving decent metric scores across different datasets.

# Previous Works
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Proposed Solution
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Tasks and Dataset 

- [X] Binary Classification 
   
   * [Insomnia](https://www.kaggle.com/competitions/idao-2022-bootcamp-insomnia/overview)
   * [Titanic](https://www.kaggle.com/c/titanic)
   * [Diabetes](https://www.kaggle.com/datasets/kandij/diabetes-dataset)
- [X] Multi-class Classification
    * [Body Performance](https://www.kaggle.com/datasets/kukuroo3/body-performance-data)
    * [Ghouls, Goblins, and Ghosts... Boo!](https://www.kaggle.com/competitions/ghouls-goblins-and-ghosts-boo/overview)
- [ ] Single-output Regression
    * [Car price](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
    * [Second Hand Car price](https://www.kaggle.com/datasets/mayankpatel14/second-hand-used-cars-data-set-linear-regression)
    * [Concrete Compressive Strength](https://www.kaggle.com/datasets/maajdl/yeh-concret-data)
- [ ] Multi-output Regression
    * [Possum](https://www.kaggle.com/datasets/abrambeyer/openintro-possum)




 ### The boring questions 
 List of questions that are often asked and debated in ML forums or community group :
> 1) Why do we perform categorical feature encoding before data splitting?
> 2) Why do we perform feature transformation after data splitting?
> 3) Why do we deal with outliers first before imputing missing values?
> 4) Why do we perform oversampling and undersampling after feature transformation and feature encoding?


## Authors Info

```
----------------------------------------
Author  : Alvin Setiadi
Email   : alvinsetiadi22@gmail.com
Website : alvinwatner.github.io/about
License : MIT
----------------------------------------
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details