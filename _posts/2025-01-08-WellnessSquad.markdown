---
title: "Suicide Prevention: WellnessSquad"
layout: page
date: 2025-01-08 19:08
tag: Machine Learning
projects: true
hidden: true
description: "An introduction to WellnessSquad: An Augmented Approach to Suicide Ideation Classification"
category: project
author: shogz
externalLink: false
---
<h1>WellnessSquad: An Augmented Approach to Suicide Ideation Classification</h1>

<div class="side-by-side">
    <div class="toleft">
        <p><strong><em>WellnessSquad</em></strong> is an updated version of <a href = "https://github.com/stoyonaga/EECS5327_WellnessOracle">WellnessOracle</a>, a project developed in GS/EECS 5327, Introduction to Machine Learning & Pattern Recognition by Shogo Toyonaga, Abel Habte, Dongwon Lee, and Jonathan Ramos.</p>
        <p>The performance has been substantially improved in addition to new features and web scraping support. Please see below for a summary of the novel updates:</p>
        <ol>
            <li>New handcrafted features for training/testing</li>
            <li>Implemented feature scaling & pre-processing support</li>
            <li>Added data analytics & visualization support</li>
            <li>Added new models with superior performance (e.g., Fine-tuned BERT) </li>
            <li>Added webscraping and inference support for Reddit, Quora, and YouTube</li>
            <li>Added support for a chatbot in case users need to seek help for their problems</li>
        </ol>
    </div>
    <div class="toright">
        <img class="image" src="https://images.pexels.com/photos/4128516/pexels-photo-4128516.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Alt Text">
    </div>
    <h2>Technical Details</h2>
    <ol>
        <li><strong>Machine Learning:</strong> <em>sklearn, optuna, transformers, torch, and numpy</em> were use to develop and fine-tune the models for text-based classification tasks.</li>
        <li><strong>Data Visualization:</strong> <em>dash, emojis, and wordcloud</em> were used to visualize model performance on the training and testing set and to identify patterns between keywords.</li> 
        <li><strong>Web Scraping:</strong> <em>PlayWright, BeautifulSoup4, Requests, and youtube_transcript_api</em> were used to pull content from Reddit, Quora, and YouTube to further evaluate the model's performance on real-time data.</li>
        <li><strong>Graphical User Interface (GUI):</strong> <em>Streamlit</em> was used to support the end-user with an intuitive user interface that calls inference on our pre-trained models. Data from various websites can be scraped and automatically classified as suicide or non-suicide.</li>
    </ol>
    <h2>Source Code & Paper</h2>
    <ol>
        <li>The training and testing data used to generate our models can be accessed <a href = "https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch">here</a>.</li>
        <li>Our code can be found <a href = "https://github.com/Shogz-Labs/WellnessSquad">here</a>.</li>
    </ol>
</div>