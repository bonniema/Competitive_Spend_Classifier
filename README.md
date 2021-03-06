# Classification used in Marketing
Goal: Utilize KMeans Clustering, RandomForest, and other Classification methods to solve marketing problems such as Market segmentation and predict Competitive marketing spend

## Data Collection
- Top 30 tech companies' info from Fortune.com
- Competitive Advertising Spend from research firm Kantar
- TV/Radio Audience Population from research firm Nielsen

[Data Prepration](https://github.com/bonniema/Competitive_Spend_Classifier/blob/master/Data_Prep_Mod5_BM.ipynb)

## Data Exploration

Media Mix and Market Mix of top 30 tech companies in 2019 
![insight1](./images/mix_chart.JPG)

While some companies spent higher % in National advertising, some other companies focused on local marketing strategies
![insight2](./images/localvsnational.jpg)

## Part I: Build a classification model to predict national spend range for top tech companies


![Feature Importance](./images/rf_results.JPG)

[Notebook link](https://github.com/bonniema/Competitive_Spend_Classifier/blob/master/Competitive_Classification_BM.ipynb)


## Part II: Clustering 210 US Local DMAs to several segments
I am trying to create clusters for US 210 DMAs based on tech industry advertisers' local spend to have a deeper understanding on the similarities among the markets. 

The implication can be: find out market groups that tech advertiser prioritize or heavily advertise in; create local marketing strategies that cater to each group. 

![Cluster Results](./images/market_clusters.JPG)



[Notebook link](https://github.com/bonniema/Competitive_Spend_Classifier/blob/master/Market_Segmentation_BM.ipynb)

