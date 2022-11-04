# IBM_HR
## Description

Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists.

  1. Education
  
    - 1.'Below College'
    - 2.'College'
    - 3.'Bachelor'
    - 4.'Master'
    - 5.'Doctor'

  2. EnvironmentSatisfaction
  
    - 1.'Low'
    - 2.'Medium'
    - 3.'High'
    - 4.'Very High'

  3. JobInvolvement
  
    - 1.'Low'
    - 2.'Medium'
    - 3.'High'
    - 4.'Very High'

  4. JobSatisfaction
  
    - 1.'Low'
    - 2.'Medium'
    - 3.'High'
    - 4.'Very High'

  5. PerformanceRating

    - 1.'Low'
    - 2.'Good'
    - 3.'Excellent'
    - 4.'Outstanding'

  6. RelationshipSatisfaction

    - 1.'Low'
    - 2.'Medium'
    - 3.'High'
    - 4.'Very High'

  7. WorkLifeBalance

    - 1.'Bad'
    - 2.'Good'
    - 3.'Better'
    - 4.'Best'

## Process
> ## cleanning Data
  1. Reduced memory usage by the data by changing it's value types
  2. Removing some unuseful columns 
  3. splitting columns into numerical ,categorical nominal and categorical columns 
  
  
> ## Insights
  1. Found that the data is biased by the attrition column
  2. Found very strong correlation between JobLevel and the average Monthely income for employees but we can't              really know if there is effict on the attrition
  3. Found clearly that the job roles with high salaries have lower attrition rate
  
  
> ## Data preporcessing
  1. Upsampling the data by the attrition column to make it palanced for model trainning
  2. Splitting the data into trainning and testing sets
  3. Used Ordinal encoder and onehot encoder on the suitable columns
  4. Normalized the data
  
  
> ## Models
  1. LogisticRegressionCV
  
    - Accuracy : 0.7935222672064778
    - Precision : 0.7675276752767528
    - Recall : 0.8421052631578947
  2. SGDClassifier
  
    - Accuracy : 0.742914979757085
    - Precision : 0.7439024390243902
    - Recall : 0.7408906882591093  
  3. LinearSVC
  
    - Accuracy : 0.8036437246963563
    - Precision : 0.7777777777777778
    - Recall : 0.8502024291497976

  
  4. RandomForestsClassifier
  
    - Accuracy : 0.9858299595141701
    - Precision : 0.9838709677419355
    - Recall : 0.9878542510121457
  
  
  
