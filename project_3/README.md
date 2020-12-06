# Project 3 - Web API's & Classification

## Problem Statement

In 2019, the global smartphone revenues amounted to a total of 400 billion US dollars. This is one of the world’s biggest markets, with many companies heavily invested in it.  

There are effectively only two smartphone platforms: iOS and Android. They are very different platforms though, and any insight as to how they work and what customers like about each platform, can be very valuable to hardware companies, software and services companies, and many more.  

In this project, I will attempt to understand the similarities and differences between these two dominant smartphone platforms.


## Executive Summary

This project is carried out in 6 main steps:

1. Webscraping

We will scrape two different subreddits (iPhone and Android) to get the data from the posts there.

2. Data Cleaning

Webscraped data has a lot of artefacts and unnecessary features. We will remove the unwanted artefacts and clean the data before carrying out further analysis.

3. Exploratory Data Analysis

Before carrying out any machine learning modelling, we look at simple graphs to show frequency of words. We also take a look at what are the common words that appear in both subreddits.

4. Modelling

We run classification models on the text data and try to predict which subreddit a post comes from. We even run our trained model on new, unseen data to evaluate it's accuracy.

5. Interpretations

Based on the modelling results, we try to see what are the important features of each subreddit.

6. Conclusions

We provide conclusions and recommendations in this section.


## Notebooks and Datasets

There are 6 notebooks that show the entire data process:

1. Webscraping (Android Subreddit)
2. Webscraping (iPhone Subreddit)
3. Data Cleaning and EDA
4. Data Modelling
5. Test Data (Scraping and Cleaning)
6. Test Data (Modelling and Evaluate)

The notebooks are annotated with comments and markdown cells for interpretation and explanations.


## Conclusions and Recommendations

The first models that were run may have showed very obvious features of the Android and iPhone ecosystem: brand names, feature names, etc. However, they do provide a lot of value: there are so many more brands and model names that were not significant in the analysis. One example is the much lauded over Samsung [Galaxy Z Flip](https://www.samsung.com/sg/smartphones/galaxy-z-flip/), a new type of foldable smartphone. This did not seem to get much traction on reddit despite heavy marketing. A new product by Microsoft called the [Surface Duo](https://www.microsoft.com/en-us/surface/devices/surface-duo?activetab=overview) did not appear as well.

Similarly, there were certain iPhone features that were released but did not get much traction. The new iPhones released in October came with [Dolby Vision HDR video recording](https://www.imore.com/what-dolby-vision-and-why-does-it-matter-iphone-12), but this did not seem to get any mention at all.

So while the first analysis might seem obvious, it does provide value by showing which brands and features get traction among the customer base. This will give direction as to what they can improve on in their future products.

The second analysis shows the different priorities customers of the different smartphone platforms prioritises.
Android fans seem to focus on technical aspects such as processor brand ('Snapdragon' and 'Exynos' both appear as top classifiers), digital assistant, 'flagship' devices. iPhone fans prioritise the overall ecosystem of the iPhone, such as iPads, Macs, reliable tech support and the strong Apple accesory ecosystem.

This provides vast value to anyone invested in the smartphone market, or are attempting to profit from it. By understanding the needs/preferences of customers of each platform, stakeholders will be better able to engage those customers.
