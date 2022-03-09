# Data Roadmap
The goal of this document is to define the scope and draw a clear plan for building up a data science discipline from scratch at Vermut; from designing the data pipeline to defining processes for reproducible analysis, scalable models, and experimentation. Our vision is to make data useful and transition to a startup where data science provides key input for product and business development. 

# Table of Contents
1. [Introduction](#introduction)
2. [Tools & Sources](#toolssources)
3. [Tagging Plan](#taggingplan)
4. [Business Intelligence](#businessintelligence)
5. [A/B Testing](#abtesting)


## 1. Introduction <a name="introduction"></a>
With data tracking and data pipeline as the building blocks, we propose a line of work for the short term (Q2&Q3 ‘21) –exploratory data analysis, experimentation and BI– and another one for the medium/long term (Q4 ‘21) –predictive modelling and data products. 

In the actual startup’s early stage it’s beneficial to start collecting quantitative data about customer behavior –and complementing it with qualitative data for domain knowledge–  so that we can improve the product systematically.
Some of the key points we aim at are:
- Identifying key business metrics to track and forecast
- Understanding customer behavior and building predictive models
- Running experiments to test product changes
- Building data products that enable new product features

## 2. Tools & Data Sources <a name="toolssources"></a>
This section details the main tools data sources that we’ll be using for accomplishing various data science tasks.<br\>
Data sources:

- WIX DB
- AWS – bookings and partners data
- Google Analytics
- Facebook for Business
- WhatsApp for Business
- Google Ads
- Typeform
- MailChimp
- HubSpot
- Google Sheets
- Google Search Console

Sources:
- For tracking user navigational data on Vermut’s web, we’ll be using the free version of Google Analytics together with Typeform (quantitaive + qualitative data).
- For experimentation and personalization, we’ll be using Google Optimize. 
- As programming languages, we’ll be using PyCharm and Python for scripting and production, as well as SQL and AWS. 
- For data visualization we’ll be using  Google Data Studio.
- For machine learning projects we’ll be using Amazon SageMaker.

## 3. Tagging Plan <a name="taggingplan"></a>
In order to make data-driven decisions at Vermut, we need to collect data about how the product is being used and its metadata. This will allow to measure the impact of making changes to the product and the efficacy of running campaigns for customer acquisition/remarketing.
On a high-level, we have three main objectives related to data tracking:

- Track metrics: record performance metrics for measuring product health or other metrics useful for running the business, and discover hidden patterns that turn into actionable insights for the product/business.
- Enable experimentation and personalization: to determine if changes to a product are beneficial, we need to be able to measure results. Once the results of an experiment are conclusive, the next action would be rolling the change/development of the functionality or personalizing the experience. 
- Create data products: in order to make something like a recommendation system or a site search engine, we need to know how users are interacting on the site.

The website dataLayer will play a key role.

<img src="https://user-images.githubusercontent.com/4792886/133003597-80d95235-b1dd-49bf-94da-0420928d4dbb.png" alt="alt text" width="1200">


## 4. Business Intelligence <a name="businessintelligence"></a>
In order to improve the defined metrics, a series of dashboards will be delivered for better decision making around the product and/or business. Scope:

- Types of experiences with the highest impact
- Categories of experiences with the highest impact
- Ad Channels/Ad campaigns with the highest impact
- Dayparting analysis
- Experience page visit profile vs display/ad strategy
- Partners performance indicators
- Customer and Partner satisfaction metrics
- Customer retention metrics
- Cancellation metrics
- Google Analytics metrics combined with Experiences data
                                                          
<img src="https://user-images.githubusercontent.com/4792886/133004091-9ab347ce-67c9-42b6-91da-5c19ffa9b18e.png" alt="alt text" width="1200">
                                                          

## 5. A/B Testing Design <a name="abtesting"></a>
It’s important to be capable of determining if changes made to the product are beneficial. Experimentation is the key to finding causal relationships and improving incrementally. We’ll provide a framework to run experiments, analyze the results and a process to deploy the learnings to production. 

<img src="https://user-images.githubusercontent.com/4792886/133003797-c0b61636-ab43-44ce-856b-bf43606a78bb.png" alt="alt text" width="1200">



