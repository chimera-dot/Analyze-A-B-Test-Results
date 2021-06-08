# Analyze-A-B-Test-Results

## Table of Contents
- [Introduction](#introduction)
- [Part I - Probability](#probability)
- [Part II - A/B Test](#ab_test)
- [Part III - Regression](#regression)
 
<a id='intro'></a>
#### Introduction

Analyze A/B TesT Results a is project within Udacity Nanaodegree program.
This project is geared to understand the results of an A/B test run by an ecommerce website. The copmpany has developed a new web page in order to increase number of users who convert to paid services and products.

The goal of this project is to help the company understand and make a decision whether to implement the new page, Keep old page, or run the experiment much longer.
  
 This project consist of three parts: 
 
<a id='probability'></a>
#### [Part I - Probability](#probability) 
  
  Part I assesses the likelihood of conversion and includes data wrangling to address descipancies,         though not the focus of this project but essential to the overall outcome of the test analysis.

<a id='ab_test'></a>
#### [Part II - A/B Test](#ab_test) 
  
  Part II attempts to guide decision based on data provided and assumes that the old page is better         except the new page proves otherwise at a significance level of 0.05, thus , the null hypothesis and     the alternative hypothesis below:

  *H0: p_{new} - p_{old} ≤ 0*
  
  *H1: p_{new} - p_{old} > 0*
  
<a id='regression'></a>
#### [Part III - Regression](#regression)
  
  This part employs regression approach in guiding the decisions we explored in part II, taking into       account at some stage, factors that may affect conversion, the relationships amongst the terms of the     model. Here, the countries dataset, `countries.csv`, is employed to create interaction and examine       association between country and page and how it impact conversion. Statsmodels is use to fit the models.
  
