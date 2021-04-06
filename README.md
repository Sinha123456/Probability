# Statistics

Descriptive statistics is about describing our collected data. 

Inferential Statistics is about using our collected data to draw conclusions to a larger population


   1. Population - our entire group of interest.
   2. Parameter - numeric summary about a population
   3. Sample - subset of the population
   4. Statistic numeric summary about a sample


    The sampling distribution is centered on the original parameter value.

    The sampling distribution decreases its variance depending on the sample size used. Specifically, 
    the variance of the sampling distribution is equal to the variance of the original data divided by the sample size used.
    This is always true for the variance of a sample mean!
    
    Two important mathematical theorems for working with sampling distributions include:

    Law of Large Numbers
    Central Limit Theorem
    
The Law of Large Numbers says that as our sample size increases, the sample mean gets closer to the population mean,
but how did we determine that the sample mean would estimate a population mean in the first place? How would we identify 
another relationship between parameter and statistic like this in the future?

There are three most common ways are with the following estimation techniques:
 Maximum liklihood estimation: https://en.wikipedia.org/wiki/Maximum_likelihood_estimation
 
 Method of Moments Estimation: https://en.wikipedia.org/wiki/Method_of_moments 
 
 Bays Estimation: https://en.wikipedia.org/wiki/Bayes_estimator
 
 Central Limit Theorem: Central Limit Theorem states that with a large enough sample size the sampling distribution of the mean will be normally distributed. 
    
Bootstrapping is sampling with replacement. Using random.choice in python actually samples in this way. 
