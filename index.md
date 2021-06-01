## Projects

---

### Topology Identification of VAV (Variable Air Volume) units
<div style="text-align: justify">The goal is to identify the layout of a given building to check which units are adjacent/nearby each other and determine the temperature correlation between them if they are situated nearby.
</div>
<br>
<div style="text-align: justify">Heatmap showing temperature correlation matrix of VAVs</div>
<img src="images/heatmap_VAV_corr.jpg?raw=true"/>
<br>
<div style="text-align: justify">Integration of t-SNE plot with NetworkX plot</div>

<img src="images/VAV.jpg?raw=true"/>
<br>
<div style="text-align: justify">The nodes/circles represent t-SNE x and y values obtained from dataset whereas the edges represent the relation or proximity that was observed from actual data of the building.</div>
<br>
<div style="text-align: justify">The data is from the Systems Engineering Building (SEB), https://bbd.labworks.org/, a medium size commercial building at PNNL. It contains multiple attributes related to energy consumption, with minute-level data, starting from 11/30/2018 5:09:00 PM upto 5/6/2020  4:59:00 PM, thus a total of 533,031 records. This dataset contains the information related to multiple AHU (Air Handling Unit) and their VAV units.</div>


---
### Social Media (Twitter) Analysis using Natural Language Processing

<div style="text-align: justify">Social media has become the main channel for people to obtain information. The goal of this project is to identify misinformation on social media comparing experts tweets with the non-expert tweets primarily on covid19 as the data has been extracted from March to September of 2020. The experts are identified as Twitter users who are professionals such as epidemiologists, scientists, professors whose tweets are considered as true/ accurate information. </div>
<br>
<div style="text-align: justify">Since the data we are working with is quite large to compare, topic modeling was performed to identify primary topics in both experts and non-experts datasets. The three methods used to find topics were LDA (Latent Dirichlet Allocation), TF-IDF (Term Frequency-Inverse Document Frequency) and TextRank. Below are some visualizations for TF-IDF Bigrams using Tableau. Also, I have created a Tableau Public Dashboard to compare TF-IDF and TextRank frequency values for the top 50 LDA keywords separated by topics for each month. </div>

[TF-IDF Analysis for Bigrams](/pdf/tf-idf_bigrams.pdf)

<img src="images/Story 1.png?raw=true"/>
<br>
The link to the Tableau Public dashboard showing Topic Modeling Analysis: https://public.tableau.com/shared/R2Z6H2673?:display_count=n&:origin=viz_share_link

---
### Predict Diabetes with RF, SVM and KNN using Python
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/likhitha-musku/Final-Term-Project/blob/main/Diabetes_Prediction_Classification.ipynb)

<div style="text-align: justify">In this project, I performed comprehensive EDA on the Pima Indians Diabetes dataset, then implemented three different classification algorithms (Random Forest, SVM and KNN) to obtain the best classifier out of the three.</div>
<br>
<img src=""/>

---
### Market Basket Analysis using Python
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/likhitha-musku/Data-Mining/blob/main/Apriori.ipynb)
<div style="text-align: justify">Apriori algorithm is used to find frequent item set mining and association rules for a sample transactional data. The support and confidence are calculated and are user-defined values. The support is an indication of how frequently the items appear in the data whereas confidence is a percentage value that shows how frequently the rule head occurs among all the groups containing the rule body. For example, confidence is calculated as the number of transactions that include both A and B divided by the number of transactions includes only product A. </div>


---
### Portfolio Optimization for ETF stocks and Bonds using Python
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/likhitha-musku/Portfolio_Optimization/blob/main/Portfolio_Optimization_Project.ipynb)
<div style="text-align: justify">The motive for this project is to optimize Sharpe Ratio in the portfolio to understand the return of investment compared to its risk. The ratio is calculated by the average return earned in excess of the risk-free rate per unit of volatility or total risk. </div>
<br>
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
