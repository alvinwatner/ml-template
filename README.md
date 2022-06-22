# Introduction

The application of Machine Learning (ML) to tabular data is one of the most popular tasks in the ML community because many areas (e.g., finance, medical) commonly use tabular data to store a set of information. The process of building an ML model for tabular data is often messy and less organized. This may intimidate newcomers in the ML community as the entire workflow seems to be vague and less-intuitive. Nevertheless, there are simply just 2 things that must be understood in order to build a good ML model for tabular data.:

1. How to perform a specific step? 
2. Which step should be performed first? 

The first one focuses on various techniques to achieve a specific step (for example, how to handle skewed features with log transformation), while the second refers to the entire workflow of building an ML model for a specific dataset. The second point is crucial as performing the wrong workflow is prone to serious issues (e.g., information leakage or degraded performance). However, the existing learning resources out there often show different workflows when applied to different tasks or a specific dataset, while mainly just repeating a similar pattern. Therefore, in this project, I attempt to establish the **same workflow** in a **jupyter notebook** that can be used to solve various predictive tasks, including classification and regression. I also demonstrate that the notebook I created is capable of achieving decent metric scores across different datasets.

### Knowledge Requirement

This template assumes you have knowledge on:
* categorical features encoding
* a basic python
* a basic statistic

### Tasks and Dataset 

- [X] Binary Classification 
   
   * Insomnia
     * [dataset](https://www.kaggle.com/competitions/idao-2022-bootcamp-insomnia/overview)
     * [colab](https://colab.research.google.com/drive/1Z9bVwPLiHAah6q2XXJMm2DYRaVqC5CS5?usp=sharing)
   * Titanic
     * [dataset](https://www.kaggle.com/c/titanic)
     * [colab](https://colab.research.google.com/drive/13UaU63hnOZGDUH46JeX4dMRBm0skY0bY?usp=sharing)

- [X] Multi-class Classification
    * Body Performance
       * [dataset](https://www.kaggle.com/datasets/kukuroo3/body-performance-data)
       * [colab](https://colab.research.google.com/drive/1vmqCNE-ilJGKHPMHvFfRWrRe1kl0jEm-?usp=sharing)  
    * Ghouls, Goblins, and Ghosts... Boo!
       * [dataset](https://www.kaggle.com/competitions/ghouls-goblins-and-ghosts-boo/overview)
       * [colab](https://colab.research.google.com/drive/1VmI21-cySnWIV-3EjyfaAfy9tP_PRkPI?usp=sharing)  
- [X] Single-output Regression
    * Concrete Compressive Strength
        * [dataset](https://www.kaggle.com/datasets/maajdl/yeh-concret-data)
        * [colab](https://colab.research.google.com/drive/1gz6vW-J4NZ-nWy7ce-BEZPO3whrNt2Nn?usp=sharing)  
    * [Car price](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
        * [dataset](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
        * [colab](https://colab.research.google.com/drive/1F4Jy2r4SNiEvBYjxBYbc9B5HFdDQdTtv?usp=sharing)  





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