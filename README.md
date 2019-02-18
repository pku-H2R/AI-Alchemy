<p float="center">
  <img src=https://github.com/pku-H2R/AI-Alchemy/blob/master/Picture/alchemy.png width="420" />
  <img src=https://github.com/pku-H2R/AI-Alchemy/blob/master/Picture/alchemy_1.png width="420" />
</p>
                                                                                              

**The goal of this project is to summarize the various experiences in the neural network training process. When we train the network, we always have to face two major problems. One is the design of the network structure, and the other is the training configuration of the network, which is hyperparameter tuning**

# Content
* [Pipeline](#Pipeline)
* [Neural Architecture Search](#Neural-Architecture-Search)
* [Hyperparameter Tuning/Optimization](#Hyperparameter-Tuning)
* [Website](#Website)


# Pipeline

* Vectorization
* Preprocessing
   * Data Normalization
      * zero mean
      * unit variance
   * Feature Scaling
   * Imbalanced Data
   * Missing Data
* Problem
   * Overfitting 
      * Data
         * Collect more Data
         * Dimensionality Reduction
         * Data Augmentation
      * Model
         * Dropout
         * Earlystopping
         * Batch Normalization
         * Weight Regularizers
         * Reducing network size
   * [Reproducible Results](https://machinelearningmastery.com/reproducible-results-neural-networks-keras/)
   * Gradient Vanishing/Exploding
      * Vanishing
         * Initialization Weight
         * ReLU
      * Exploding
         * Gradient Clipping

# Neural-Architecture-Search

![Picture](https://github.com/pku-H2R/AI-Alchemy/blob/master/Picture/NAS.jpg)

* Automatic
    * NASnet
    * MNASnet
    * SNAS
    * EAT-NAS
* Manual




# Hyperparameter-Tuning/Optimization

* Automatic

    * Approaches
      * GridSearch
      * RandomizedSearch
      * Bayesian Optimization
      * Heuristic Algorithms
          * Genetic Algorithm
          * Paticle Swarm Optimization
          
    * Open Source Project
      * [Hyperopt](https://github.com/hyperopt/hyperopt)
      * [Hyperas](https://github.com/maxpumperla/hyperas)
      * [Optunity](https://github.com/claesenm/optunity)
      * [Vizier](https://ai.google/research/pubs/pub46180)
      * [Advisor](https://github.com/tobegit3hub/advisor)
 
 * Manual

# Website

* [Practical Deep Learning for Coders](https://course.fast.ai/)
* [Deep Learning](https://www.deeplearningbook.org/)
