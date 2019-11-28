# Exam rules

As mentioned in the introductory slides, the 'default' exam score (here denoted as `ES0`)
is combined from the score for the paper review and for the ML challenge report. Each component has 50% weight, i.e.:
 - `ES0 = 0.5 * paper_review_score + 0.5 * challenge_review_score`.

`paper_review_score` and `challenge_review_score` are each from 0 to 10.

If one is not satisfied with their `ES0` they can try to improve it.
The way to do it is to answer (without preparation) 2 questions randomly picked from the
list below to get the `questions_score` (from 0 to 10).
The exam score will then be:
 - `ES = min(5, ES0) + 0.5 * questions_score`.

Once you select this option there's no way to get back to `ES0`, so you should be confident you can
answer the questions, otherwise you are at risk of getting a worse mark.

Here is the list of questions:

1. What is underfitting? Overfitting? Are there quantitative measures of underfitting and overfitting? How one could counter overfitting/underfitting?
1. What are the qualitative differences between l1 and l2 regularizations? 
1. What is the basic idea of boosting? Why AdaBoost is not a Gradient Boosting?
1. What is the qualitative difference between SGD and ada* algorithms?
1. What is the proper way to search the best hyper-parameters?
1. How can one estimate uncertainty in the predictions of an estimator? Can one avoid using validation set in hyper-parameter optimization?
1. How does Bayesian Optimization with Gaussian Process work?
1. Imagine training a neural network with cross-entropy loss. How change of class prior probabilities affects the solution?
1. What are the problems with imbalanced datasets? Could you provide an example of a method to cope with SGD training problems on imbalanced datasets and avoiding change of class priors?
1. What is semi-supervised learning? Does unsupervised pretraining on a vast set of unlabeled data lead to improvement on the supervised problem?
1. What is the distinctive feature of Deep Learning in contrast to traditional algorithms like Trees, SVM and so on?
1. What are the main ideas behind dropout and batch normalization in neural networks?
1. What is the U-net architecture and what are the main ideas behind it?
1. What is an energy based model?
1. What is contrastive divergence training? What is persistent contrastive divergence training?
1. What is the main difference between RBM and BM? Why training BM is problematic?
1. Main idea behind GAN. What kind of problems might appear while training vanilla-GAN?
1. What are the qualitative differences between vanilla GAN and W-GAN? The main idea behind gradient penalty for WGAN.
1. What is the main difference between VAE and an ordinary AE? Why one is a generative model, while other is not?
