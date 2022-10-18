# Question-Generation-Paper-List

A summary of must-read papers for Time-aware Recommender Systems.

- Contributed by **[Hengchang Hu](https://holdenhu.github.io/)**

Please follow [this link](./README_by_year.md) to view papers in chronological order. 

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#basic-models">2.1 Basic Models</a></td>
    <td>&ensp;<a href="#cnn-models">2.2 CNN-based Models</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#rnn-models">2.3 RNN-based Models</a></td>
    <td>&ensp;<a href="#gnn-models">2.4 GNN-based Models</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#rl-models">2.5 Reinforcement Learning</a></td>
    <td>&ensp;<a href="#cl-models">2.6 Contrastive Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#adv-models">2.5 Adversarial Learning</a></td>
    <td>&ensp;<a href="#ml-models">2.6 Meta Learning</a></td>
</tr>
<tr><td colspan="2"><a href="#task">2. Tasks</a></td></tr> 
<tr>
    <td>&emsp;<a href="#cf">2.1 Collaborative Filtering </a></td>
    <td>&ensp;<a href="#sr">2.2 Sequential/Session-based Recommendations</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#ctr">2.3 CTR/CVR Prediction</a></td>
    <td>&ensp;<a href="#kg-rs">2.4 Knowledge-aware Recommendations</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#crs">2.5 Conversational Recommender System</a></td>
    <td>&ensp;<a href="#kg-rs">2.6 POI Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#news-rec">2.7 News Recommendation</a></td>
    <td>&ensp;<a href="#explain-rec">2.8 Explainable Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#privacy">2.9 Privacy & Security</a></td>
    <td>&ensp;<a href="#fairness">2.10 Debias & Fairness</a></td>
</tr>
<tr><td colspan="3"><a href="#time-usage">3. Temporal Aspects in User Modeling</a></td></tr>
<tr>
    <td>&emsp;<a href="#discrete">3.1 Temporal Popularity</a></td>
    <td>&ensp;<a href="#continous">3.2 Temporal Periodicality</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#periodical">3.3 Recency</a></td>
    <td>&ensp;<a href="#frequency">3.4 Recurrence</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#periodical">3.5 Temporal Specification</a></td>
</tr>
<tr><td colspan="2"><a href="#resources">4. Resources</a></td></tr>
</table>



## [Survey papers](#survey)

1. **Sequence-aware recommender systems.** ACM Computing Surveys (CSUR), 2018. 

2. **Considering Temporal Aspects in Recommender Systems: A Survey.** UMUAI, 2022. [paper](http://www.christophtrattner.com/pubs/UMUAI_2022_A.pdf)

   *Veronika Bogina, Tsvi Kuflik, Dietmar Jannach, Maria Bielikova, Michal Kompan, Christoph Trattner*

3. **Review of the Temporal Recommendation System with Matrix Factorization.** ICIC, 2017. [paper](http://www.ijicic.org/ijicic-130511.pdf)

   *IAAQ Al-Hadi, NM Sharef, MN Sulaiman, N Mustapha*

4. **A Survey on Session-based Recommender System.** arxiv, 2021. [paper](https://arxiv.org/pdf/1902.04864.pdf)

## [Models](#content) 

### [Basic Models](#basic-models)

Basic models including two-tower models, and classical machine learning approaches.

1. **Time Weight Collaborative Filtering.** CIKM, 2005. [paper](https://dl.acm.org/doi/pdf/10.1145/1099554.1099689)

   *Yi Ding, Xue Li*

### [CNN-based Models](#cnn-models)



### [RNN-based Models](#rnn-models)





## [Temporal-Aspect](#temporal-aspects)

### [Temporal Popularity & Trendiness](#temporal-popularity)

1. **Personalized News Recommendation with Context Trees.** RecSys, 2013. [paper](https://arxiv.org/pdf/1303.0665.pdf)

   *Florent Garcin, Christos Dimitrakakis, Boi Faltings*

2. **Learning item temporal dynamics for predicting buying sessions.** IUI, 2016. [paper](https://dl.acm.org/doi/abs/10.1145/2856767.2856781)

   *Veronika Bogina, Tsvi Kuflik, Osnat Mokryn*

3. **Collaborative Filtering with Temporal Dynamics.** KDD, 2009. [paper](https://cseweb.ucsd.edu//classes/fa17/cse291-b/reading/p447-koren.pdf)

   *Yehuda Koren*

4.  **Incorporating context and trends in news recommender systems.** WI, 2017. [paper](https://dl.acm.org/doi/abs/10.1145/3106426.3109433)

   *A Lommatzsch, B Kille, S Albayrak*

5. **Session-based item recommendation in e-commerce: on short-term intents, reminders, trends and discounts.** User Model. User-Adapt. Interact., 2017. [paper](https://link.springer.com/article/10.1007/s11257-017-9194-1)

   *Dietmar Jannach, Malte Ludewig & Lukas Lerche*

### [Temporal Periodicality](temporal-periodicality)

1. **Itinerary recommender system with semantic trajectory pattern mining from geo-tagged photos.** Expert Syst. Appl., 2017. [paper](https://www.sciencedirect.com/science/article/pii/S0957417417307315)

   *Guochen Cai, Kyungmi Lee, Ickjai Lee*

### [Temporal Recency](temporal-recency)





new trends (Lommatzsch et al., 2017; Jannach et al., 2017), freshness/recency (Chu and Park, 2009; Garcin et al., 2013; Kille and Albayrak, 2017; Jannach et al., 2015; Gulla et al., 2016; Wang et al., 2016; Chakraborty et al., 2017; Kowald et al., 2017), seasonality (Xiong et al., 2010; Rokicki et al., 2017) and promotions (Luo et al., 2016).















## [Resources](#Resources)

https://github.com/caserec/Datasets-for-Recommender-Systems