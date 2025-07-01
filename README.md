# personal_projects
Everything that comes to my mind to improve or experiment is inside this repository. Maybe one day I will show this to my grandchildren.


I will post here all my codes with my projects. It can turn useful for recruiters, friends, data enthusiasts or anyone who snitches my profile.
If you have any suggestions, I'm super glad to take them unless they are constructive :D 

**My Useful Links**
1. _Which ML model should I use for my dataset or project?_
  https://medium.com/learning-data/which-machine-learning-algorithm-should-i-use-for-my-analysis-962aeff11102
2. _How to do PCA in python_
   https://www.geeksforgeeks.org/data-analysis/principal-component-analysis-with-python/
3. _Choose the number of components in a PCA_
   https://rlrocha.medium.com/choosing-the-number-of-components-of-principal-component-analysis-36902a887520
   The PCA reduces dimensionality by looking at the contributed variance of each single feature (k-component) to the total variance described by **ALL** features. This is called _cumulative explained variance ratio_.
   Given the equation in the link at 3., since it's cumulative, the final component will contribute to 100% (practically never reaching that level because we will always miss the predicted variable from the feature vector).
   The more the ratio grows, the more the variance is explained by that feature.
   Finally, when the ratio reaches a certain level or anyway the increase of explained variance of the next component is not consistent to justify its introduction, then that k-th component sets the number of components to determine the model.
