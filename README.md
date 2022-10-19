# Question-Generation-Paper-List

A summary of must-read papers for Time-aware Recommender Systems.

- Contributed by **[Hengchang Hu](https://holdenhu.github.io/)**

Please follow [this link](./README_by_year.md) to view papers in chronological order. 

## [Content](#content)

```php+HTML
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
    <td>&ensp;<a href="#frequency">3.4 Time-Point Sensitivity</a></td>
</tr>
<tr>
        <td>&emsp;<a href="#periodical">3.5 Temporal Features</a></td>
</tr>
<tr><td colspan="2"><a href="#resources">4. Resources</a></td></tr>
</table>
```



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

2. **Temporal collaborative filtering with bayesian probabilistic tensor factorization.** SIAM, 2010. [paper](https://epubs.siam.org/doi/pdf/10.1137/1.9781611972801.19)

   *Liang Xiong, Xi Chen, Tzu-Kuo Huang, Jeff Schneider, Jaime G. Carbonell*

   ​

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

这里面包括repetely consumption，which关注于用户重复地做某项事情，buy the same things repeatedly

区别于temporal frequency，这里指的是关注于有规律的重复， people have regular habits， 比如we eat at the same restaurants regularly

1. **Itinerary recommender system with semantic trajectory pattern mining from geo-tagged photos.** Expert Syst. Appl., 2017. [paper](https://www.sciencedirect.com/science/article/pii/S0957417417307315)

   *Guochen Cai, Kyungmi Lee, Ickjai Lee*

2. **News session-based recommendations using deep neural networks.** DLRS, 2018. [paper](https://arxiv.org/pdf/1808.00076.pdf)

   *Gabriel de Souza Pereira, Felipe Ferreira, Adilson Marques da Cunha*

3. **The Intricacies of Time in News Recommendation.** UMAP, 2016. [paper](http://ceur-ws.org/Vol-1618/INRA_paper4.pdf)

   *Jon Atle Gulla, Arne Dag Fidjestøl, Jon Espen Ingvaldsen, Cristina Marco,  Xiaomeng Su, Özlem Özgöbek*

4. **Ctrec: a longshort demands evolution model for continuous-time recommendation.** SIGIR, 2019. [paper](https://tbbaby.github.io/pub/sigir19.pdf)

   *Ting Bai, Lixin Zou, Wayne Xin Zhao, Pan DuWeidong Liu, Jian-Yun Nie, Ji-Rong Wen*

5. **Modeling user consumption sequences.** WWW, 2016. [paper](https://cseweb.ucsd.edu//classes/fa17/cse291-b/reading/sequences-www2016.pdf)

   *Austin R. Benson, Ravi Kumar, Andrew Tomkins*

6. **RepeatNet: A Repeat Aware Neural Recommendation Machine**
   **for Session-based Recommendation.** AAAI, 2019. [paper](https://arxiv.org/pdf/1812.02646.pdf)

   *Pengjie Ren, Zhumin Chen, Jing Li, Zhaochun Ren, Jun Ma, Maarten de Rijk*

### [Temporal Recency](temporal-recency)

The recency of tags has a positive effect on their recurrence probability. (To Replace)

1. **Models of user engagement.** UMAP, 2012. [paper](https://www.researchgate.net/profile/Mounia-Lalmas/publication/233852009_Model_of_User_Engagement/links/0912f50c1c334284cd000000/Model-of-User-Engagement.pdf)

   *Janette Lehmann, Mounia Lalmas, Elad Yom-Tov, Georges Dupret*

2. **Sequence and time aware neighborhood for session-based recommendations: Stan.** SIGIR, 2019. [paper](https://dl.acm.org/doi/abs/10.1145/3331184.3331322)

   *Diksha Garg, Priyanka Gupta, Pankaj Malhotra, Lovekesh Vig, Gautam Shroff*

3. **Time Interval Aware Self-Attention for Sequential Recommendation.** WSDM, 2020. [paper](https://cseweb.ucsd.edu/~jmcauley/pdfs/wsdm20b.pdf)

   *Jiacheng Li, Yujie Wang, Julian McAuley*

4. **On the Decaying Utility of News Recommendation Models.** RecTemp@ RecSys, 2017. [paper](http://ceur-ws.org/Vol-1922/paper2.pdf)

   *Benjamin Kille, Sahin Albayrak*

   ​

### [Time-Point Sensitivity]()

A specific time point making the difference to user selection, such as purchasing festaval, promptions, Olympics, when a new item is released, or when an item is available at a specific point.

1. **A recommender system for heterogeneous and time sensitive environment.** RecSys, 2019. [paper](https://www.researchgate.net/profile/Qilian-Yu/publication/335768631_A_recommender_system_for_heterogeneous_and_time_sensitive_environment/links/61004e2c1e95fe241a917b76/A-recommender-system-for-heterogeneous-and-time-sensitive-environment.pdf)

   *Meng Wu, Ying Zhu, Qilian Yu, Bhargav Rajendra, Yunqi Zhao, Navid Aghdaie, and Kazi A. Zaman*

2. **Discovering temporal purchase patterns with different responses to promotions.** CIKM, 2016. [paper](https://shlomo-berkovsky.github.io/files/pdf/CIKM2016.pdf)

   *Ling Luo, Bin Li, Irena Koprinska, Shlomo Berkovsky, Fang Chen*

3. **Visualizing program genres’ temporal-based similarity in linear TV recommendations.** AVI, 2020. [paper](https://shlomo-berkovsky.github.io/files/pdf/AVI20.pdf)

   *Veronika Bogina, Julia Sheidin, Tsvi Kuflik, Shlomo Berkovsky*

   ​

### [Temporal Features]()

Time transformed features, such as weeks, seasons, years.

1. **Enhanced product recommendations based on seasonality and demography in ecommerce.** ICACCCN, 2020. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9362760&casa_token=hptCc-6gInoAAAAA:SuYYC62Fg0zbWwRfAtvcnzW0APdVH5eoSdGdc9Qz8zH3fsDgh4N8qPwSWzGcKLC3YyMr7VPzlDo2kdM&tag=1)

   *Keerthika K, Saravanan T*

2. **Context of Seasonality in Web Search.** ECIR, 2014. [paper](http://www2.fiit.stuba.sk/~bielik/publ/abstracts/2014/kramar-ecir2014.pdf)

   *Tomáš Kramá, Mária Bieliková*

3. **Temporal collaborative filtering with bayesian probabilistic tensor factorization.** SIAM, 2010. [paper](https://epubs.siam.org/doi/pdf/10.1137/1.9781611972801.19)

   *Liang Xiong, Xi Chen, Tzu-Kuo Huang, Jeff Schneider, Jaime G. Carbonell*

4. **Seasonality-adjusted conceptualrelevancy-aware recommender system in online groceries.** BigData, 2019. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9005954&casa_token=QXEkiLaxUb4AAAAA:aC50szY2rYcRv8b4HATNJ5ZQ6U9V3SRkgN0q9IPWwVJmM1IW-_Tcv3LqEsmcr6B4l1eqtFXyjkLkOT8)

   *Luyi Ma, Jason H.D. Cho, Sushant Kumar, Kannan Achan*

5. **Mining frequent seasonal gradual patterns.** DaWaK, 2020. [paper]()

   *Jerry Lonlac, Arnaud Doniec, Marin Lujak, Stephane Lecoeuche*

6. **The contextual turn: from context-aware to context-driven**
   **recommender systems.** RecSys, 2016. [paper](https://www.researchgate.net/profile/Paolo-Cremonesi-2/publication/307573378_The_Contextual_Turn_from_Context-Aware_to_Context-Driven_Recommender_Systems/links/6069f29a299bf1252e2ba0e4/The-Contextual-Turn-from-Context-Aware-to-Context-Driven-Recommender-Systems.pdf)

   *Roberto Pagano, Martha Larson, Balázs Hidasi, Alexandros Karatzoglou*

7. **Investigating and predicting online food recipe upload behavior.** IPM, 2019. [paper](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/2626280/IPM2019Food.pdf?sequence=2)

   *Christoph Trattnerb, Tomasz Kusmierczyka, Kjetil Nørvåga*

   ​

## [Resources](#Resources)

https://github.com/caserec/Datasets-for-Recommender-Systems