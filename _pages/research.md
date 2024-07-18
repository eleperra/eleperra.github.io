---
layout: single
title: "Research"
permalink: /research/
header:
    overlay_image: /assets/images/header_prova.jpg
author_profile: true
classes: wide
date: April 30, 2023

feature_row0-1:
  - image_path: assets/images/JDE_image.png
    alt: "AWS app demo"
    title: "Roads, Competition, and the Informal Sector"
    text: >
      <div style="font-size: 12px;"> 
      We examine the impact of competition from better connectivity to domestic markets on formal and informal firms. Combining geolocalized information on road improvements under a large infrastructure investment programme with data on manufacturing firms in Ethiopia between 2001 and 2013, we show that an increase in competition is associated with higher labour productivity, capital-intensity, investment in physical capital and wages in the formal sector. On the contrary, there is no associated increase in labour productivity or wages in the informal sector. In fact, increased competition results in lower capital-intensity and investment, a shift in composition towards workers without primary education and a lower likelihood of operating in the informal sector. We thus highlight that the benefits of infrastructure improvement programmes may not accrue uniformly in the economy.
       </div>
    url: "https://www.sciencedirect.com/science/article/pii/S0304387824000889"
    #btn_label: "Code"
    btn_class: "btn--primary"
    # tags:
    #     - AWS
    #     - Lambda
    #     - S3
    #     - EC2
    #     - DynamoDB
    #     - Flask
    #     - ECS
    #     - Docker



feature_row1-0:
  - image_path: assets/images/artificial_map_1998.png
    alt: "Detecting System Failure poster"
    title: "Roads to Division: Ethnic Favoritism and Road Infrastructure in Ethiopia"
    text: >
      <div style="font-size: 12px;">  
      This paper examines the impact of ethnic favoritism on the allocation of transportation infrastructure in Ethiopia. Analyzing road investments and ethnic composition in 5 Km² grid cells, the study finds that areas predominantly inhabited by the ruling ethnic elite receive 6.8% more road investments and see a 7.5% improvement in pavement quality. Investigating the staggered implementation of the Road Sector Development Program from 1997 to 2016, I explore how road construction influences local economic activity. Nighttime light intensity, indicating higher economic activity, increases by two thirds of a standard deviation in cells benefiting from new roads, with earlier investments yielding higher effects. Notably, economic benefits are more pronounced in areas where the population shares the ethnicity of the ruling elite.
        </div>
  # url: "../assets/docs/reports/kbosko-system-failure-detection-poster.pdf"
   # btn_label: "Poster"
    #btn_class: "btn--primary"
  #  url2: "../assets/docs/reports/kbosko-system-failure-detection-presentation.pdf"
  #  btn_label2: "Presentation"
   # btn_class: "btn--primary"
   # tags:
        #- Time Series
        #- Signal Processing
        #- Convolutional Neural Network

feature_row1-1:
  - image_path: assets/images/malawi.png
    alt: "Clusterisation results based on Conversion Rates"
    title: "Spatial Inequality during the COVID-19 pandemic in Africa, using Night-time lights data"
    text: >
      <div style="font-size: 12px;">  
      In this paper, we study the evolution of spatial inequality during the recent COVID-19 pandemic in  Africa and assess if there is any association between the outbreak of the health crisis, the strictness of policy restrictions and the changes observed in spatial inequality. Using remotely sensed night time lights data, we find that spatial inequality decreased after the COVID-19 outbreak. Yet, there are huge differences within and between countries. Spatial inequality decreased in Southern and Northern African countries while it increased in Central African countries}. Spatial inequality mainly decreased in countries implementing more stringent measures but also in those areas that were richer before the outbreak of the COVID-19 pandemic.
       </div>
    #url: "https://www.sciencedirect.com/science/article/pii/S0304387824000889"
    #btn_label: "Code"
    #btn_class: "btn--primary""
    #btn_label: "Code"
    btn_class: "btn--primary"
    #btn_class: "btn--primary"
    #url2: "/Starbucks-Rewards-Program/"
    #btn_label2: "Technical Report"
    #btn_class: "btn--primary"
    #tags:
    #    - Marketing
    #    - Segmentation
    #    - k-means clustering

feature_row1-2:
  - image_path: /assets/images/portfolio/retention_rates.png
    alt: "Retention Rates"
    title: "Marketing Analytics"
    text: "In a series of Marketing Analytics projects, I used Online Retail II dataset to create cohorts based on monthly data, calculated retention rates and visualized them via a heatmap. Then I created RFM (Recency, Frequency, Monetary) segments, calculated RFM Score for each customer and segmented into 3 custom segments 'Top', 'Middle' and 'Low' based on the total RFM Score. Finally, I calculated the revenue-based CLV (Customer Lifetime Value) for each customer."
    url: "https://github.com/k-bosko/cohort_analysis"
    btn_label: "Code for Cohort Analysis"
    btn_class: "btn--primary"
    url2: "https://github.com/k-bosko/RFM_analysis"
    btn_label2: "Code for RFM Analysis"
    btn_class: "btn--primary"
    url3: "https://github.com/k-bosko/CLV_prediction"
    btn_label3: "Code for CLV Prediction"
    btn_class: "btn--primary"
    tags:
    - CLV
    - Cohort Analysis
    - RFM Analysis

feature_row1-3:
  - image_path: /assets/images/portfolio/purchase-analytics-1200.jpg
    alt: "Purchas Analytics results"
    title: "Purchase Analytics"
    text: "In this project, I analyzed purchase behavior of customers that bought 5 different brands of chocolate bars in a physical FMCG store during 2 years. In total, they made 58,693 transactions, captured through the loyalty cards they used at checkout. Based on the results of customer segmentation, I explored the segments sizes and answered the following business questions: 1. How often do people from different segments visit the store? 2. What brand do customer segments prefer on average? 3. How much revenue each customer segment brings?"
    url: "https://github.com/k-bosko/purchase_analytics"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
    - EDA
    - Business Analytics

feature_row1-4:
  - image_path: /assets/images/portfolio/Tableau-dashboard-1200.jpg
    alt: "Tableau Dashboard"
    title: "Tableau Dashboard"
    text: "In this project, I performed data analysis to recommend short-term renting strategy for Watershed, a residential rental properties firm. To do this, I extracted relevant data from a real estate MySQL database, analyzed data in Excel to identify the best opportunities to increase revenue and maximize profits and created a Tableau dashboard to show the results of a sensitivity analysis."
    url: "https://public.tableau.com/profile/katerina.bosko#!/vizhome/Bosko_dashboardforWatershedproperties/FinalDashboard"
    btn_label: "Dashboard"
    btn_class: "btn--primary"
    tags:
    - Tableau
    - Excel
    - MySQL


feature_row3:
  - image_path: /assets/images/portfolio/IBM_DS_platform.jpg
    alt: "IBM data science platform"
    title: "Content Recommendations"
    text: "In this project, I implemented different recommendation engines for users of the IBM Watson Studio platform. <br>
    - _Rank Based Recommendations_: recommended the most popular articles based on the highest user interactions <br>
    - _User-User Based Collaborative Filtering_: recommended unseen articles that were viewed by most similar users <br>
    - _Content Based Recommendations_: recommended articles based on similarity of content <br>"
    url: "https://github.com/k-bosko/recommendations_IBM"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
    - recommender system
    - collaborative filtering


feature_row5:
  - image_path: assets/images/portfolio/deep_learning-thumb-800.jpg
    portfolio_caption: Photo Credit [Ardon Dertat](https://towardsdatascience.com/applied-deep-learning-part-1-artificial-neural-networks-d7834f67a4f6)
    alt: "deep learning network"
    title: "Deep Learning"
    text: "In this project, I have first developed code for an image classifier built with PyTorch in Jupyter Notebook, then converted it into a command line application. The application allows you to choose one of the pretrained architectures, specify different hyperparameters (learning rate, hidden layers, epochs) and use either GPU or CPU for training. I also implemented saving the checkpoints so that you can continue training if stopped. Image Classifier predicts 102 flower categories. "
    url: "https://github.com/k-bosko/image_classifier"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
        - deep-learning
        - transfer-learning
        - PyTorch
---

## Publications

{% include feature_row id="feature_row0-1" type="left" %}
<a name="Gifify AWS app"></a>

## Research Pipeline

&nbsp;
<a name="Signal-Processing">
{% include feature_row id="feature_row1-0" type="left" %}
{% include feature_row id="feature_row1-1" type="left" %}
<a name="Marketing-Analytics"></a>
{% include feature_row id="feature_row1-2" type="left" %}
<a name="Purchase-Analytics"></a>
{% include feature_row id="feature_row1-3" type="left" %}
<a name="Tableau-Dashboard"></a>
{% include feature_row id="feature_row1-4" type="left" %}
<!-- <a name="Digital-Marketing"></a>
{% include feature_row id="feature_row4" type="left" %} -->
<a name="Recommender-System"></a>
{% include feature_row id="feature_row3" type="left" %}



