---
layout: post
title:  "What is Linear Regression?"
date:   2017-05-16 21:50:00
categories: Machine Learning
tags: TensorFlow Python ML Regression Supervised-Learning
---

* content
{:toc}

##So, what is Linear Regression?<br>
In short, **Linear Regression** is one of the basic supervised machine learning model to describle two or more variables.<br>
Equation of simple linear model:<br>
>$$h_w(x) = w * x + b$$ 

<br>
Where **h** is the hypothesis/prediction/output(**y**), **x** is the data/feature(**n**). Meanwhile, **w** and **b** are called Weight and Basis respectively, these are the parameters that the model have to learn. In maths, **a** is also known as "slope"/"gradient" and b is "intercept".

So what happen when we have more than one feature(independent variables)?<br>
For instance given a set of data (Restaurant Review):

| Waiting Time | Avg Cost £ | Review |
| ------------- | ------------- | ------------- |
| 5 | 12 | 8 |
| 9 | 18 | 7 |
| 20 | 22 | 6 |
| 10 | 20 | 8.5 |
| 1 | 8 | 7 |
| 30 | 10 | 5 |
| 40 | 50 | 3 |

The linear function is reprsented as follow:<br>
> h_w(x) = w_1 * x_1 + ... + w_n * x_n + b <br><br>
> In this case, n = 2.<br>
> p.s b = w_0 * x_0 where x_0 == 1

When there is no risk of confusion, we usually write h_w(x) as h(x), with simplification the function can also represent as:<br>

> h(x) = sum{n}{i=0} w_i * x_i = W_t * X<br>
> Where **W** and **X** are both vectors and n is the number of features.



