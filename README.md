 # Cox-nnet-v2.0

 Cox-nnet is a neural-network based prognosis prediction method first developed by Travers (https://github.com/traversc/cox-nnet).
 Here we propose the new version 2 of Cox-nnet, with significant improvement on efficiency and interpretability, making it suitable to predict prognosis based on large-scale electronic medical records (EMR) datasets. 

 ### Improvement
 - Speed-up in calculating log partial likelihood loss function.
 - Adding permutation based feature importance scores.
 - Adding the directionality of the feature.
 - Adding additional optimization algorithms.


 ### New functions

 - permutationImportance - calculates variable importance (using permutation importance from Fisher, et al. 2018)
 - signOfBeta - calculates estimated direction of variable
