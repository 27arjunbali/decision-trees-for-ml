# Decision Trees for Machine Learning

This is the repository of Decision Trees for Machine Learning online course published on Udemy. In this course, the following algorithms will be covered. All project is going to be developed on Python (3.6.4), and neither out-of-the-box library nor framework will be used to build decision trees.

Course: https://www.udemy.com/decision-trees-for-machine-learning/?couponCode=DTML-BLOG-18 **(90% OFF over the regular price)**

1- ID3 - [Documentation](https://sefiks.com/2017/11/20/a-step-by-step-id3-decision-tree-example/)

2- C4.5 - [Documentation](https://sefiks.com/2018/05/13/a-step-by-step-c4-5-decision-tree-example/)

3- CART (Classification And Regression Trees) - [Documentation](https://sefiks.com/2018/08/27/a-step-by-step-cart-decision-tree-example/)

4- Regression Trees (CART for regression) - [Documentation](https://sefiks.com/2018/08/28/a-step-by-step-regression-decision-tree-example/)

5- Random Forest - [Documentation](https://sefiks.com/2017/11/19/how-random-forests-can-keep-you-from-decision-tree/)

6- Gradient Boosting Decision Trees - [Documentation 1](https://sefiks.com/2018/10/04/a-step-by-step-gradient-boosting-decision-tree-example/), [Documentation 2](https://sefiks.com/2018/10/29/a-step-by-step-gradient-boosting-example-for-classification/)

7- Adaboost - [Documentation](https://sefiks.com/2018/11/02/a-step-by-step-adaboost-example/)

Just call the [decision.py](/python/decision.py) file to run the program. You might want to change the running algorithm. You just need to set algorithm variable.

```
algorithm = "ID3" #Please set this variable to ID3, C4.5, CART or Regression
```

Moreover, you might want to apply random forest. Please set this to True in this case.

```
enableRandomForest = False
```

Furthermore, you can apply gradient boosting regression trees.

```
enableGradientBoosting = True
```

Besides, adaptive boosting is allowed to run

```
enableAdaboost = True
```

Finally, you can change the data set to build different decision trees. Just pass the file name, and its column names if it does not exist.

```
df = pd.read_csv("car.data"
  #column names can either be defined in the source file or names parameter in read_csv command
  ,names=["buying","maint","doors","persons","lug_boot","safety","Decision"] 
)
```

# Prerequisites

Pandas and numpy python libraries are used to load data sets in this repository. You might run the following commands to install these packages if you are going to use them first time.

```
pip install pandas
pip install numpy
```

# Updates

To keep yourself up-to-date you might check posts in my blog about [decision trees](https://sefiks.com/tag/decision-tree/) 
