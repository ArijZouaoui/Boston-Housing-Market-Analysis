# Boston-Housing-Market-Analysis
---
## Usecase

<br />

During the international AIHack competition, organized by ICDSS (Imperial College Data Science Society), my team and I have worked on the Housing Market Analysis challenge. Our main goal was to work on a ML model to predict the houses prices.
---
## Our Team : In This Land We Dream

| <a href="https://www.linkedin.com/in/arij-zouaoui/" target="_blank">**Arij Zouaoui**</a> | <a href="https://www.linkedin.com/in/chaima-araibi/" target="_blank">**Chaima Araibi**</a> | <a href="https://www.linkedin.com/in/ahmed-bellaaj/" target="_blank">**Ahmed Belaaj**</a> |
| :---: |:---:| :---:|
| [![Arij Zouaoui](https://media-exp1.licdn.com/dms/image/C4D03AQEyHxmJ2ydCLg/profile-displayphoto-shrink_200_200/0/1605903063195?e=1620259200&v=beta&t=kpJQDlwfB764GSleDU415Y6vkogQ7i-_9EY5hCcgWsU)](https://github.com/ArijZouaoui)    | [![ChaimaAraibi](https://media-exp1.licdn.com/dms/image/C4E03AQGPtohci_x4Eg/profile-displayphoto-shrink_200_200/0/1605991569534?e=1620259200&v=beta&t=mOI-_alESqr8LLejVD-s44c8hw7WsiO53hltAGzP4Xg)](https://www.linkedin.com/in/chaima-araibi/) | [![AhmedBelaaj](https://media-exp1.licdn.com/dms/image/C4E03AQH4sNIhUzHGcw/profile-displayphoto-shrink_200_200/0/1585752601628?e=1620259200&v=beta&t=nV4dgyxVmSUomOnZOBNVlMscu5xYnz4k03gHze4Xj04)](https://www.linkedin.com/in/ahmed-bellaaj/)  |



---
## Results’ interpretation
<br />

The results show that Lasso and Ridge are the best fit for our dataset. This is explained by the fact that these techniques are used when the data suffers from multicollinearity.  They are a modification of linear regression, where Lasso penalizes the model for the sum of absolute values of the weights and Ridge penalizes it for the sum of their squared values.
 
As for the scaling, it showed a positive impact on the performance of most algorithms, especially Lasso and Ridge, because by not using standardization, the model might require big absolute values of the coefficients. 
 
Finally, we opted for a feature selection by threshold = 0.45. As a result the models were only trained on highly correlated variables to the house pricing (INDUS, RM, TAX, PTRATIO, LSTAT). This had also a positive impact on the models’ performance.
