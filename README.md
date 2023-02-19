# 60 Days of Learning Machine Learning Challenge

<img width="1148" alt="image" src="https://user-images.githubusercontent.com/74296174/218983392-3ab36888-bf34-4887-9396-c8b6dcca73f9.png">

| Books and Resources | Completed |
| ------------- | ------------- |
| [AIN311: Fundamentals of Machine Learning](https://web.cs.hacettepe.edu.tr/~erkut/ain311.f22/) by Erkut Erdem |  |
| [Stanford CS229: Machine Learning Full Course](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) by Andrew Ng, Autumn 2018 |  |
| [A Course in Machine Learning](http://ciml.info) by Hal Daumé III |  |
| [Python A-Z™: Veri Bilimi ve Machine Learning](https://www.udemy.com/course/python-egitimi/) by Vahit Keskin | |


| Summaries for Chapters | Notes |
| ------------- | ------------- |
| 1. Nearest Neighbor Classifier | [note](https://medium.com/@gokcenazakyol/what-is-nearest-neighbor-classifier-machine-learning-1-26b8ec1b9f7b)|
| 2. Curse of Dimensionality | [note](https://medium.com/@gokcenazakyol/what-is-curse-of-dimensionality-machine-learning-2-739131962faf) |
| 3. Linear Regression | [note](https://medium.com/@gokcenazakyol/what-is-linear-regression-machine-learning-3-3489725a887) |

| Exercise Names |Files|
| ------------- | ------------- |
| KNN Classifier | [file](https://github.com/gokcenazakyol/knn-classifier) |

-----------------------------------------

### Day 5 of 60 Days Machine Learning Challange 🎯

| Done |TO-DO list of the day|
|------| ------------- |
| ✅ | Publish the notes about Linear Regression |
| ✅ | Complete Locally Weighted & Logistic Regression -  Stanford CS229: Machine Learning - Lecture 3 |
| ✅ | Complete Perceptron & Generalized Linear Model -  Stanford CS229: Machine Learning - Lecture 4 |
| ✅ | Complete GDA & Naive Bayes - Stanford CS229: Machine Learning - Lecture 5 |

- You can find notes that I took for Linear Regression from [here](https://medium.com/@gokcenazakyol/what-is-linear-regression-machine-learning-3-3489725a887).

#### Some of the New Things I Learnt Today
- In a parametric learning algorithm you fit some fixed set of parameters such as Theta to data (Example: Linear Regression). Then you could erase a training set from your computer memory and make predictions just using the parameters Theta. In a non-parametric you need to keep all of the data in computer memory or on disk just to make predictions. (Example: Locally weighted regression)
- IID from statistics stands for Independently and Identically Distributed. These assumptions is probably not absolutely true, but may be good enough that if you make this assumption, you get a pretty good model.
- If you're willing to assume that the error terms are Gaussian and IID and if you want to use Maximum Likelihood Estimation, then you should use least squares.
- If you choose a logistic function rather than some other function that will give you 0 to 1, you're guaranteed that the likelihood function has only one global maximum. (concave function)
- If you make weaker assumptions as in logistic regression, then your algorithm will be more robust to modeling assumptions such as accidentally assuming the data is Gaussian and it is not. But on the flip side, if you have a very small dataset, then using a model that makes more assumptions will actually allow you to do better because by making more assumptions you're just telling the algorithm more truth about the world.
- If we perform maximum likelihood on the exponential family when the exponential family is parameterized in the natural parameters, then the optimization problem is concave. So MLE with respect to eta is concave. Similarly, if you flip this sign and use the negative log-likelihood, the cost function equivalent of doing maximum likelihood, you minimize the negative log likelihood, so the NLL is therefore convex.

-----------------------------------------

### Day 4 of 60 Days Machine Learning Challange 🐸
- I completed studying Lecture 2 of CS229 which is about Linear Regression and Gradient Descent. I learned new things and listed them below:
- Keep using stochastic gradient descent, but reduce the learning rate over time. So it takes smaller and smaller steps. If you do that, then what happens is the size of the oscillations would decrease. So you end up oscillating or bouncing around the smaller region. So wherever you end up, may not be the global minimum, but at least it'll be closer to the global minimum. 
-  If you implement normal equations to linear regression, then you can in basically one step, get the value of Theta that corresponds to the global minimum.

----------------------------------------

### Day 3 of 60 Days Machine Learning Challenge 👩🏽‍💻
- Today, I studied Linear Regression and Gradient Descent Algorithm, Cross-Validation, Computational Learning and Probability from AIN311 slide notes. I took notes from them.
- Also, I watched Linear Regression and Gradient Descent video from CS229 playlist above.

-----------------------------------------

### Day 2 of 60 Days Machine Learning Challenge 🐱
- Today, I studied Curse of Dimensionality topic and how to reduce dimensionality. On the other hand, I decided to quickly overview the topics that I already know. So, I overviewed the linear regression and the related regression types such as PSR, PLS, Lasso Regression, Ridge Regression and lastly ElasticNet Regression types. 
- I benefited from A Course in Machine Learning by Hal Daumé III Chapter 3 | GEOMETRY AND NEAREST NEIGHBORS again.
- You can find notes that I took for Curse of Dimensionality from [here](https://medium.com/@gokcenazakyol/what-is-curse-of-dimensionality-machine-learning-2-739131962faf).

-----------------------------------------

### Day 1 of 60 Days Machine Learning Challenge 💫
- Nearest Neighbor Algorithm is basically predicting test data points labels based on trained data. In training, we actually store the x and y values. In predicting part, we calculate the distance between x value of test point with other x values of train data. After that, we give the closest x points label as a test points label. In k-Nearest Neighbor Algorithm we do the same steps and take the majority vote of k closest data points. As a result, we predict test points label as the majority of labels.
- I benefited from A Course in Machine Learning by Hal Daumé III Chapter 3 | GEOMETRY AND NEAREST NEIGHBORS.
- You can find notes that I took for Nearest Neighbor and k-Nearest Neighbor from [here](https://medium.com/@gokcenazakyol/what-is-nearest-neighbor-classifier-machine-learning-1-26b8ec1b9f7b).
- Here you can see the k-Nearest Neighbor Algorithm from scratch.
<img width="837" alt="image" src="https://user-images.githubusercontent.com/74296174/219040146-2a988d6d-f25f-44c7-a864-7c4664d6ae9e.png">

