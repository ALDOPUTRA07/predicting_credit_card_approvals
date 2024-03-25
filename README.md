# Predicting Credit Card Approvals

<br />
<div align="center">
  <a href="">
    <img src="static/Predicting Credit Card Approvals.png">
  </a>
</div>

<p></p>

<!-- TABLE OF CONTENTS -->
<details>
  <p>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#background">Background</a></li>
    <li><a href="#how-to-works">How to Works</a></li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#next-step">Next Step</a></li>
    <li><a href="#license">License</a></li>
  </ol>
  </p>
</details>


<p></p>

<!-- ABOUT THE PROJECT -->
## About The Project

Commercial banks receive <em>a lot</em> of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. 

This project build an automatic credit card approval predictor using machine learning techniques (Using logistic regression), just like the real banks do.

**Note:** This project is still in Jupyter Notebook. The next step is to carry out the packaging and deploying code process.



### Built With

These are list any major frameworks/libraries used to make the project.

* [![Sklearn][Sklearn]][Sklearn-url]
* [![Pandas][Pandas]][Pandas-url]
* [![Numpy][Numpy]][Numpy-url]


## Background

Commercial banks receive <em>a lot</em> of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook.

## How to Works
- First, we start by loading and viewing the dataset.
- Next, We see that the dataset has a mixture of numerical and non-numerical features, contains values from different ranges, and includes several missing entries.
- Then, We have to preprocess the dataset to ensure the chosen machine learning model can make good predictions.
- After our data is in good shape, we analyze exploratory data to build our intuitions.
- Finally, we build a machine learning model that can predict if an individual's application for a credit card will be accepted.


## Dataset
The dataset used in this project is [the Credit Card Approval dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval) from the UCI Machine Learning Repository.

## Next Step 
In the next step, we can carry out the packaging and deploying code to be implemented in the production environment.

## License
MIT

<p align="right">(<a href="#automed-forecasting">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Sklearn]: https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white
[Sklearn-url]: https://scikit-learn.org/stable/
[Numpy]: https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white
[Numpy-url]: https://numpy.org/
[Pandas]: https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
