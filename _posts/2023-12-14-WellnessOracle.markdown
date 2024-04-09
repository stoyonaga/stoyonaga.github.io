---
title: "Sentiment Analysis: WellnessOracle"
layout: page
date: 2023-12-14 12:41
tag: Machine Learning
projects: true
hidden: true
description: "An introduction to the WellnessOracle Project that was developed under GS/EECS 5327 guidelines."
category: project
author: shogz
externalLink: false
---
<h1>WellnessOracle: A Machine Learning Approach to Suicide Ideation Classification</h1>

<div class="side-by-side">
    <div class="toleft">
        <p><strong><em>WellnessOracle</em></strong> is a text-based binary classifier that aims to predict a social media user's mental well-being based on their previous posting and/or comment history. It aims to determine signs of underlying depression so that the machine learning model can quickly determine if a user is mentally at-risk to themselves or others. Suicide, especially for the younger generation, has become an increasingly pervasive problem [8]. It has become the second-most leading cause of fatality [5] among young adults worldwide.</p>
    </div>
    <div class="toright">
        <img class="image" src="https://images.pexels.com/photos/5598393/pexels-photo-5598393.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Alt Text">
    </div>
    <h2>Technical Details</h2>
    <ol>
        <li><strong>Machine Learning:</strong> <em>sklearn, seaborn, GridSearchCV</em> were use to develop and fine-tune the model for text-based classification tasks.</li>
        <li><strong>Data Visualization:</strong> <em>matplotlib, seaborn, wordcloud</em> were used to visualize model performance on the training and testing set and to identify patterns between keywords.</li> 
        <li><strong>Web Scraping:</strong> <em>PlayWright, BeautifulSoup4, Requests</em> were used to webscrape content from Reddit, Twitter, and Quora to further evaluate the model's performance on real-time data.</li>
        <li><strong>Graphical User Interface (GUI):</strong> <em>Streamlit</em> was used to support the end-user with an intuitive user interface that interacts with our pre-trained models. Data from various websites can be scraped and automatically classified as suicide or non-suicide.</li>
    </ol>
    <h2>Source Code & Paper</h2>
    <ol>
        <li>The training and testing data used to generate our models can be accessed <a href = "https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch">here</a>.</li>
        <li>Our code can be found <a href = "https://github.com/stoyonaga/EECS5327_WellnessOracle">here</a>.</li>
    </ol>
</div>