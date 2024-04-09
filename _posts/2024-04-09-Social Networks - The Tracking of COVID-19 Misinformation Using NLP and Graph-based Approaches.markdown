---
title: "Social Networks - The Tracking of COVID-19 Misinformation Using NLP and Graph-based Approaches"
layout: page
date: 2024-04-09 10:16
tag: Data Analytics & Visualization
projects: true
hidden: true
description: "An analysis of COVID-19 Misinformation on Twitter and Reddit through Graph and NLP-based analytics and visualizations."
category: project
author: shogz
externalLink: false
---
<h1>Social Networks: The Tracking of COVID-19 Misinformation Using NLP and Graph-based Approaches</h1>

<div class="side-by-side">
    <div class="toleft">
        <p><strong><em>Introduction:</em></strong> Misinformation during the COVID-19 pandemic resulted in many unnecessary infections, hospitalizations, and fatalities [10]. This is a trend that has been seen in past health epidemics [11, 12]. Our work aims to study the spread of COVID-19 misinformation on social media platforms such as Twitter and Reddit through a Natural Language Processing (NLP) and Graph-based approach. We use NetworkX, Gephi, Streamlit, Plotly, and Large Language Models to build a comprehensive analytics and visualization system that that is capable of extracting core metrics identifying malicious users in the social network. Lastly, our results are consistent with previous work [1], however, we extend on what has been done by contributing a robust QA Dashboard system that is interactive and intuitive for users to learn about vaccine misinformation. This work can be valuable for many organizations that aim to address misinformation as it provides an actionable framework to implement.</p>
    </div>
    <div class="toright">
        <img class="image" src="https://images.pexels.com/photos/4160059/pexels-photo-4160059.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Alt Text">
    </div>
    <h2>Technical Details</h2>
    <ol>
        <li><strong>Data Analytics:</strong> <em>NetworkX, Gephi, NTLK, re, and PowerLaw</em> were use to build our graphs and analyze its properties.</li>
         <li><strong>Data Augmentation:</strong><em>Transformers</em> were used to augment the initial dataset with columns relating to sentiment score (negative, neutral, positive) and information validity. We also used PRAW to collect Reddit posts and comments to augment our initial datasets and provide a more comprehensive analysis.</li>
        <li><strong>Data Visualization:</strong> <em>Matplotlib, Seaborn, Plotly, Wordcloud, Streamlit</em> were used to visualize the graph and NLP-related properties of our datasets.</li> 
    </ol>
    <h2>Source Code & Paper</h2>
    <ol>
        <li>All of our code, datasets, gexf files, and more can be found <a href = "https://github.com/stoyonaga/EECS6414_SocialNetworks/tree/main">here</a>.</li>
        <li>To obtain the written paper, please reach out to me!</li>
    </ol>
</div>