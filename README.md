# awesome-financial-nlp

Researches for Natural Language Processing for Financial Domain.

## Financial Applications of NLP

Text data is one of the important resources for the financial domain. For example, we read the news when buying stock and we evaluate the plan when providing finance. In the past, the volume and velocity of textual data were manageable enough to be manually analyzed by teams of human experts but recent growth is intractable. Recent progress of NLP techniques helps this situation and it will reveal how the experts determine various judgements.

Application

* Market Analysis: Apply classification/clustering method to analyze market.
  * Micro: Stock price prediction etc
  * Macro: Unravel market movement
* Risk Management: Apply classification method etc to detect fraud or money laundering.
* Compliance: Apply various NLP methods to verify compatibility to internal investment/loan rule.
* Asset Management: Apply various NLP methods to organize unstructured documents etc.
  * Internal: Utilize internal documents.
  * External: Utilize internal documents like SNS etc.
* Customer Engagement: Apply Question Answering, Dialog etc to communicate with customer.

### Classification

* Risk Management
  * Jingguang Han, Utsab Barman, Jeremiah Hayes, Jinhua Du, Edward Burgin and Dadong Wan. [NextGen AML: Distributed Deep Learning based Language Technologies to Augment Anti Money Laundering Investigation](https://www.aclweb.org/anthology/P18-4007/). In ACL 2018.
  * Weikang Wang, Jiajun Zhang, Qian Li, Chengqing Zong and Zhifei Li. [Are You for Real? Detecting Identity Fraud via Dialogue Interactions](https://www.aclweb.org/anthology/D19-1185/). In EMNLP 2019.
  * Christoph Kilian Theil, Sanja Štajner and Heiner Stuckenschmidt. [Word Embeddings-Based Uncertainty Detection in Financial Disclosures](https://www.aclweb.org/anthology/W18-3104/). In ACL-ECONLP, 2018.
  * John S. Zdanowicz. [Detecting money laundering and terrorist financing via data mining](https://www.researchgate.net/publication/27297312_Detecting_money_laundering_and_terrorist_financing_via_data_mining). In KDD-ADF, 2019.
  * Armineh Nourbakhsh and Grace Bang. [A framework for anomaly detection using language modeling, and its applications to finance](https://arxiv.org/abs/1908.09156). In KDD-ADF, 2019.
  * Feng Mai, Shaonan Tian, Chihoon Lee and Ling Ma. [Deep Learning Models for Bankruptcy Prediction using Textual Disclosures](https://www.researchgate.net/publication/328406629_Deep_Learning_Models_for_Bankruptcy_Prediction_using_Textual_Disclosures). Elsevier, vol. 274(2), pages 743-758.
* Compliance
  * Youness Mansar and Sira Ferradans. [Sentence Classification for Investment Rules Detection](https://www.aclweb.org/anthology/W18-3106/). In ACL-ECONLP, 2018.
* Asset Management
  * Sian Gooding and Ted Briscoe. [Active Learning for Financial Investment Reports](https://www.aclweb.org/anthology/W19-6404/). In NoDaLiDa-FNLP, 2019.
  * João Filgueiras, Luís Barbosa, Gil Rocha, Henrique Lopes Cardoso, Luís Paulo Reis, João Pedro Machado and Ana Maria Oliveira. [Complaint Analysis and Classification for Economic and Food Safety](https://www.aclweb.org/anthology/D19-5107/).  In EMNLP-ECONLP, 2019.
  * Frederick Blumenthal and Ferdinand Graf. [Utilizing Pre-Trained Word Embeddings to Learn Classification Lexicons with Little Supervision](https://www.aclweb.org/anthology/W19-6402/). In NoDaLiDa-FNLP, 2019.

#### Sentiment Analysis

* Market Analysis
  * Tobias Daudert, Paul Buitelaar and Sapna Negi. [Leveraging News Sentiment to Improve Microblog Sentiment Classification in the Financial Domain](https://www.aclweb.org/anthology/W18-3107/). In ACL-ECONLP, 2018.
  * Narges Tabari, Piyusha Biswas, Bhanu Praneeth, Armin Seyeditabari, Mirsad Hadzikadic and Wlodek Zadrozny. [Causality Analysis of Twitter Sentiments and Stock Market Returns](https://www.aclweb.org/anthology/W18-3102/). In ACL-ECONLP, 2018.
  * Thomas Gaillat, Bernardo Stearns, Gopal Sridhar, Ross McDermott, Manel Zarrouk and Brian Davis. [Implicit and Explicit Aspect Extraction in Financial Microblogs](https://www.aclweb.org/anthology/W18-3108/). In ACL-ECONLP, 2018.
  * Sven Buechel, Simon Junker, Thore Schlaak, Claus Michelsen and Udo Hahn. [A Time Series Analysis of Emotional Loading in Central Bank Statements](https://www.aclweb.org/anthology/D19-5103/). In EMNLP-ECONLP, 2019.
  * Linyi Yang, Ruihai Dong, Tin Lok James Ng and Yang Xu. [Leveraging BERT to Improve the FEARS Index for Stock Forecasting](https://www.aclweb.org/anthology/W19-5509/). In FinNLP, 2019.
* Asset Management
  * Antonio Moreno-Sandoval, Pablo Alfonso Haya Ana Gisbert, Marta Guerrero and Helena Montoro. [Tone Analysis in Spanish Financial Reporting Narratives](https://www.aclweb.org/anthology/W19-6406/). In FNP, 2019.

### Clustering (Unsupervised Classification)

* Haodong Bai, Frank Xing, Erik Cambria and Win-Bin Huang. [Business Taxonomy Construction Using Concept-Level Hierarchical Clustering](https://www.aclweb.org/anthology/W19-5501/). In FinNLP, 2019.

### Question Answering/Dialog

* Customer Engagement
  * Tuan Lai, Trung Bui, Sheng Li and Nedim Lipka. [A Simple End-to-End Question Answering Model for Product Information](https://www.aclweb.org/anthology/W18-3105/). In ACL-ECONLP, 2018.
  * Jared Rivera, Jan Caleb Oliver Pensica, Jolene Valenzuela, Alfonso Secuya and Charibeth Cheng. [Annotation Process for the Dialog Act Classification of a Taglish E-commerce Q&A Corpus](https://www.aclweb.org/anthology/D19-5108/).  In EMNLP-ECONLP, 2019.

### Knowledge Extraction

#### Event extraction

* Market Analysis
  * Liat Ein-Dor, Ariel Gera, Orith Toledo-Ronen, Alon Halfon, Benjamin Sznajder, Lena Dankin, Yonatan Bilu, Yoav Katz and Noam Slonim. [Financial Event Extraction Using Wikipedia-Based Weak Supervision](https://www.aclweb.org/anthology/D19-5102/). In EMNLP-ECONLP, 2019.
  * Shuang (Sophie) Zhai and Zhu (Drew) Zhang. [Forecasting Firm Material Events from 8-K Reports](https://www.aclweb.org/anthology/D19-5104/). In EMNLP-ECONLP, 2019.
  * Deli Chen, Yanyan Zou, Keiko Harimoto, Ruihan Bao, Xuancheng Ren and Xu Sun. [Incorporating Fine-grained Events in Stock Movement Prediction](https://www.aclweb.org/anthology/D19-5105/). In EMNLP-ECONLP, 2019.
  * Deli Chen, Shuming Ma, Keiko Harimoto, Ruihan Bao, Qi Su and Xu Sun. [Group, Extract and Aggregate: Summarizing a Large Amount of Finance News for Forex Movement Prediction](https://www.aclweb.org/anthology/D19-5106/). In EMNLP-ECONLP, 2019.
  * Kiyoshi Izumi and Hiroki Sakaji. [Economic Causal-Chain Search using Text Mining Technology](https://www.aclweb.org/anthology/W19-5510/). In FinNLP, 2019.

#### Relation Extraction

* Asset Management
  * Berke Oral, Erdem Emekligil, Seçil Arslan and Gülşen Eryiğit. [Extracting Complex Relations from Banking Documents](https://www.aclweb.org/anthology/D19-5101/). In EMNLP-ECONLP, 2019.
  * Ananth Balashankar, Sunandan Chakraborty and Lakshminarayanan Subramanian. [Unsupervised Word Influencer Networks from News Streams](https://www.aclweb.org/anthology/W18-3109/). In ACL-ECONLP, 2018.


### Workshops

* ECONLP: Economics and Natural Language 
  * [2018](https://julielab.de/econlp/2018/)
  * [2019](https://sites.google.com/view/econlp-2019)
* FNLP: Financial Narrative Processing
  * [2018](http://wp.lancs.ac.uk/cfie/fnp2018/)
  * [2019](https://www.aclweb.org/anthology/volumes/W19-64/)
* FinNLP & FinSDB: 
  * [2019](https://sites.google.com/nlg.csie.ntu.edu.tw/finnlp/home)
* KDF: Knowledge Discovery from Unstructured Data in Financial Services
  * [2020](https://aaai-kdf2020.github.io/)
* Robust AI in FS
  * [2019](https://sites.google.com/view/robust-ai-in-fs-2019/home)
* ADF: Anomaly Detection in Finance
  * [2017](https://sites.google.com/view/kdd-adf-2017)
  * [2019](https://sites.google.com/view/kdd-adf-2019)


### Dataset

* Corpus
  * Sebastian G.M. Händschke, Sven Buechel, Jan Goldenstein, Philipp Poschmann, Tinghui Duan, Peter Walgenbach and Udo Hahn. [A Corpus of Corporate Annual and Social Responsibility Reports: 280 Million Tokens of Balanced Organizational Writing](https://www.aclweb.org/anthology/W18-3103/). In ACL-ECONLP, 2018.
 * Tobias Daudert and Sina Ahmadi. [CoFiF: A Corpus of Financial Reports in French Language](https://www.aclweb.org/anthology/W19-5504/). In In EMNLP-ECONLP, 2019.

## Reference

* [Machine learning in UK financial services](https://www.bankofengland.co.uk/-/media/boe/files/report/2019/machine-learning-in-uk-financial-services.pdf)
* [For the First Time, Nasdaq Is Using Artificial Intelligence to Surveil U.S. Stock Market](https://www.nasdaq.com/articles/for-the-first-time-nasdaq-is-using-artificial-intelligence-to-surveil-u.s.-stock-market)
