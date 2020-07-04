# Blog

## How-to
* https://gohugo.io/hosting-and-deployment/hosting-on-github/
  * https://gohugo.io/getting-started/quick-start/
    * https://github.com/reuixiy/hugo-theme-meme

NOTE: it's best to fork the theme being used by hugo so changes can be pushed 
somewhere. Make sure to use the forked repo as the submodule theme. Similarly 
this is why the blog content is it's own repo. Hugo publishes to `public`, which
is defined to contain the submodule where `Cartar.github.io` is actually hosted.

## Backlog
* Review my Journal thoughts and other lessons/thoughts from:
  * Physics 
  * Math
  * CS 
  * Academia
  * Startups
  * Large corps 
* flush out code lessons :) -> the basics of ML and a framework to copy? 
* Link to Juniper! 

## Making changes
To test locally, simply run:
```sh
hugo server -D
```

## Tutorials for:
1. Linear Regression with Regularization (e.g. Ridge). Do you really understand what is going on? Do you understand what can go wrong? Do you understand what the coefficients really mean? Do you understand how to evaluate the quality of your fit? Do you understand why Regularization helps or hurts you? Do you understand how to pick your regularization hyper-parameter?
2. Logistic Regression. One of the most powerful tools in your tool box. Do you understand how the fit is different from linear regression? Do you understand performance metrics like Precision, Recall, Specificity and how to pick a threshold? Do you understand the perils of class imbalance?
3. Random Forest. Do you know when to use this instead of regression? Do you understand how decision trees can approximate non-linear functions? Do you understand the perils of over fitting? Can you interpret the model and the importance of its features?
