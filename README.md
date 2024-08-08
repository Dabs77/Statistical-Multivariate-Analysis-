# Statistical-Multivariate-Analysis-

## Introduction 

In the immense complexity of life, we often have to analyze many variables to make decisions. However, some factors are more important than others in relation to a specific objective. For example, when choosing a potential partner, you consider multiple variables that hold specific value for you. In other words, you might prefer a person who is kind, smart, and funny, but you might also be attracted to girls with green eyes or muscular men. All these characteristics explain the investigation unit (or, more simply, the person in question). Now, why is this important? When you study an event and all the characteristics surrounding it, you need to establish the relationships between them. This is the essence of Multivariate Analysis.

In more formal terms, multivariate analysis is a set of statistical techniques used to analyze data that involves multiple variables to understand the relationships between them and to model complex phenomena. This analysis helps in making predictions and inferences about the data by considering multiple factors at once. At this point, a valid question might be, "What is multivariate data?" It refers to datasets that contain measurements or observations on more than one variable for each individual or entity.

Returning to the previous example, in a random case, when a man is looking for a potential girlfriend, and he goes to a bar and starts talking with random girls, his thought process might look like this:

| Name  | Level of charisma | Age | Color of eyes | Height | She likes Coldplay? | Is she single? | Should I ask for her number? |
|-------|-------------------|-----|---------------|--------|---------------------|----------------|------------------------------|
| Paula | 9                 | 19  | Green         | 1.60 m | Yes                 | Yes            | Yes                          |
| Maria | 4                 | 24  | Brown         | 1.72 m | No                  | Yes            | No                           |
| Nina  | ...               | ... | ......        | ...... | ....                | ...            | ...                          |


In this scenario, we could say that the variables are all these characteristics that come from each girl, and each girl is what we call in statistics an investigation unit (Paula is IU1, Maria IU2). At the same time, we could say that some variables are correlated, like "Should I ask for her number?" and "Is she single?" This is why we might be interested in studying how other variables could be correlated, like "Should I ask for her number?" and "Color of eyes," or even try to prove independence or dependence between them.

Within Multivariate Analysis, there are many methods for different goals that we could select and implement depending on the nature of the problem, understanding the strengths of each method but also their limitations. All these methods allow us to create hypotheses about some characteristics of the sample, not the population. Like in our example, he could say that Paula is the best girl to meet at this bar, but it would be silly to think that she is the best girl in the world for him.

For do this analysis we could use different multivariate methods like:
- **Dimensionality Reduction**: Reducing the number of random variables under consideration by obtaining a set of principal variables. Techniques include Principal Component Analysis (PCA) and Factor Analysis, which simplify data without losing much information.
- **Cluster Analysis**: Grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar to each other than to those in other groups. Common methods include k-means clustering and hierarchical clustering.
- **Discriminant Analysis**: Used to determine which variables discriminate between two or more naturally occurring groups. This is particularly useful in the classification of individuals into categories.
- **Canonical Correlation Analysis**: Used to explore the relationships between two sets of multivariate data. This method identifies pairs of variables from the sets which have the highest correlations with each other.
- **Multidimensional Scaling (MDS)**: Aiming to place each object in N-dimensional space such that the between-object distances are preserved as well as possible. This is used for visualizing the similarity between objects.
- **Multiple Regression Analysis**: Used to understand the relationship between a single dependent variable and several independent variables. This helps in predicting the dependent variable based on the independents.
- **Logistic Regression**: Particularly used when the dependent variable is binary. It models the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead.

