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



### Built With

These are list any major frameworks/libraries used to make the project.

* [![Pytorch][Pytorch]][Pytorch-url]


## Background

Commercial banks receive <em>a lot</em> of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook.

## How to Works
- First, we will start by loading and viewing the dataset.
- We will see that the dataset has a mixture of numerical and non-numerical features, contains values from different ranges, and includes several missing entries.
- We will have to preprocess the dataset to ensure the chosen machine learning model can make good predictions.
- After our data is in good shape, we will analyze exploratory data to build our intuitions.
- Finally, we will build a machine learning model that can predict if an individual's application for a credit card will be accepted.


## Dataset
The dataset used in this project is [the Credit Card Approval dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval) from the UCI Machine Learning Repository.

## Next Step 
In the next step, we can carry out the packaging and deploying code to be implemented in the production environment.

## License
MIT

<p align="right">(<a href="#automed-forecasting">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Pytorch]: https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[Pytorch-url]: https://pytorch.org/