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
   Given the equation in the link at 3., since it's cumulative, the final component will contribute to 100%.
   The more the ratio grows, the more the variance is explained by that feature.
   Finally, when the ratio reaches a certain level or anyway the increase of explained variance of the next component is not consistent to justify its introduction, then that k-th component sets the number of components to determine the model.

   Important: PCA does not exclude features to reduce the dimensionality of the data. It groups those into less dimensions in order to shrink the features impacting the model.
4. _Split Dataset into train and test_
   https://www.geeksforgeeks.org/python/how-to-split-the-dataset-with-scikit-learns-train_test_split-function/
   This step is important to mitigate the risk of the prediction as our model will be fit with two different datasets.
6. _Understanding MAE_
   https://medium.com/@m.waqar.ahmed/understanding-mean-absolute-error-mae-in-regression-a-practical-guide-26e80ebb97df
   This metric is helpful to measure the error of our model. It's crucial to be contestualized to the data.
8. _Adding New Columns to a Dataframe_
   https://www.geeksforgeeks.org/pandas/adding-new-column-to-existing-dataframe-in-pandas/
9. _Seaborn Gallery_
   https://seaborn.pydata.org/examples/index.html
