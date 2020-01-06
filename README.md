# awesome-financial-nlp

Researches for Natural Language Processing for Financial Domain.

## Financial Applications of NLP

Text data is one of the important resources for the financial domain. For example, we read the news when buying stock and we evaluate the plan when providing finance. In the past, the volume and velocity of textual data were manageable enough to be manually analyzed by teams of human experts but recent growth is intractable. Recent progress of NLP techniques helps this situation and it will reveal how the experts determine various judgements.

### Stock Market Analysis

Apply **Sentiment Analysis**, **Event extraction** to predict the stock movement.

* Sentiment Analysis
  * Gilles Jacobs, Els Lefever and Véronique Hoste. [Economic Event Detection in Company-Specific News Text](https://www.aclweb.org/anthology/W18-3101/). In ACL Workshop on Economics and Natural Language Processing, 2018.
  * Narges Tabari, Piyusha Biswas, Bhanu Praneeth, Armin Seyeditabari, Mirsad Hadzikadic and Wlodek Zadrozny. [Causality Analysis of Twitter Sentiments and Stock Market Returns](https://www.aclweb.org/anthology/W18-3102/). In ACL Workshop on Economics and Natural Language Processing, 2018.
  * Tobias Daudert, Paul Buitelaar and Sapna Negi. [Leveraging News Sentiment to Improve Microblog Sentiment Classification in the Financial Domain](https://www.aclweb.org/anthology/W18-3107/). In ACL Workshop on Economics and Natural Language Processing, 2018.
  * Thomas Gaillat, Bernardo Stearns, Gopal Sridhar, Ross McDermott, Manel Zarrouk and Brian Davis. [Implicit and Explicit Aspect Extraction in Financial Microblogs](https://www.aclweb.org/anthology/W18-3108/). In ACL Workshop on Economics and Natural Language Processing, 2018.
  * Sven Buechel, Simon Junker, Thore Schlaak, Claus Michelsen and Udo Hahn. [A Time Series Analysis of Emotional Loading in Central Bank Statements](https://www.aclweb.org/anthology/D19-5103/). In ACL Workshop on Economics and Natural Language Processing, 2019.
* Event Extraction
  * Liat Ein-Dor, Ariel Gera, Orith Toledo-Ronen, Alon Halfon, Benjamin Sznajder, Lena Dankin, Yonatan Bilu, Yoav Katz and Noam Slonim. [Financial Event Extraction Using Wikipedia-Based Weak Supervision](https://www.aclweb.org/anthology/D19-5102/). In ACL Workshop on Economics and Natural Language Processing, 2019.
  * Shuang (Sophie) Zhai and Zhu (Drew) Zhang. [Forecasting Firm Material Events from 8-K Reports](https://www.aclweb.org/anthology/D19-5104/). In ACL Workshop on Economics and Natural Language Processing, 2019.
  * Deli Chen, Yanyan Zou, Keiko Harimoto, Ruihan Bao, Xuancheng Ren and Xu Sun. [Incorporating Fine-grained Events in Stock Movement Prediction](https://www.aclweb.org/anthology/D19-5105/). In ACL Workshop on Economics and Natural Language Processing, 2019.
  * Deli Chen, Shuming Ma, Keiko Harimoto, Ruihan Bao, Qi Su and Xu Sun. [Group, Extract and Aggregate: Summarizing a Large Amount of Finance News for Forex Movement Prediction](https://www.aclweb.org/anthology/D19-5106/). In ACL Workshop on Economics and Natural Language Processing, 2019.
* Relation Extraction
  * Ananth Balashankar, Sunandan Chakraborty and Lakshminarayanan Subramanian. [Unsupervised Word Influencer Networks from News Streams](https://www.aclweb.org/anthology/W18-3109/). In ACL Workshop on Economics and Natural Language Processing, 2018.
* Feature Extraction
  * Christoph Kilian Theil, Sanja Štajner and Heiner Stuckenschmidt. [Word Embeddings-Based Uncertainty Detection in Financial Disclosures](https://www.aclweb.org/anthology/W18-3104/). In ACL Workshop on Economics and Natural Language Processing, 2018.


### Risk Management

Apply classification method to detect fraud or money laundering.

* Jingguang Han, Utsab Barman, Jeremiah Hayes, Jinhua Du, Edward Burgin and Dadong Wan. [NextGen AML: Distributed Deep Learning based Language Technologies to Augment Anti Money Laundering Investigation](https://www.aclweb.org/anthology/P18-4007/). In ACL 2018.
* Weikang Wang, Jiajun Zhang, Qian Li, Chengqing Zong and Zhifei Li. [Are You for Real? Detecting Identity Fraud via Dialogue Interactions](https://www.aclweb.org/anthology/D19-1185/). In EMNLP 2019.

### Compliance

Apply various NLP methods to evaluate compatibility to internal investment/loan rule.

* Youness Mansar and Sira Ferradans. [Sentence Classification for Investment Rules Detection](https://www.aclweb.org/anthology/W18-3106/). In ACL Workshop on Economics and Natural Language Processing, 2018.


### Asset Management

Apply various NLP methods to organize unstructured documents etc.

* Relation Extraction
  * Berke Oral, Erdem Emekligil, Seçil Arslan and Gülşen Eryiğit. [Extracting Complex Relations from Banking Documents](https://www.aclweb.org/anthology/D19-5101/). In ACL Workshop on Economics and Natural Language Processing, 2019.
* Text Classification
  * João Filgueiras, Luís Barbosa, Gil Rocha, Henrique Lopes Cardoso, Luís Paulo Reis, João Pedro Machado and Ana Maria Oliveira. [Complaint Analysis and Classification for Economic and Food Safety](https://www.aclweb.org/anthology/D19-5107/).  In ACL Workshop on Economics and Natural Language Processing, 2019.

### Customer Engagement

Apply **Question Answering**, **Dialog** to communicate with customer.

* Question Answering
  * Tuan Lai, Trung Bui, Sheng Li and Nedim Lipka. [A Simple End-to-End Question Answering Model for Product Information](https://www.aclweb.org/anthology/W18-3105/). In ACL Workshop on Economics and Natural Language Processing, 2018.
* Dialog
  * Jared Rivera, Jan Caleb Oliver Pensica, Jolene Valenzuela, Alfonso Secuya and Charibeth Cheng. [Annotation Process for the Dialog Act Classification of a Taglish E-commerce Q&A Corpus](https://www.aclweb.org/anthology/D19-5108/). In ACL Workshop on Economics and Natural Language Processing, 2010.


### Dataset

* Sebastian G.M. Händschke, Sven Buechel, Jan Goldenstein, Philipp Poschmann, Tinghui Duan, Peter Walgenbach and Udo Hahn. [A Corpus of Corporate Annual and Social Responsibility Reports: 280 Million Tokens of Balanced Organizational Writing](https://www.aclweb.org/anthology/W18-3103/). In ACL Workshop on Economics and Natural Language Processing, 2018.

- <b>Sentiment analysis</b> - Sentiment analysis is perhaps the most common methods for gaining investment insight from text. The intuition is pretty apparent here - if we want to gain insight about the expected future return of a stock, it makes sense to know how people feel about that company!

- <b>Risk Modeling</b> - Apart from using sentiment-like approaches to aid in forecasting returns, one can also incorporate text information from corporate filings to provide an alternative perspective on risk modeling. Publicly traded companies in the United States are required by the SEC to annually submit a form (10-K) which details information about the financial performance of the company. 

- <b>Perspectives on the future</b> - There are still many open problems in the space of NLP applied to finance. Aspect-based sentiment analysis, coreference resolution, evaluating how novel or "surprising" a news article is, and many others. There is no shortage of interesting research problems in the space of NLP applications in finance. What's need is more creative minds and enthusiastic data scientists to help drive the field into the future!
[sources](https://www.thisismetis.com/blog/financial-applications-of-natural-language-processing)

## Reference

* [Machine learning in UK financial services](https://www.bankofengland.co.uk/-/media/boe/files/report/2019/machine-learning-in-uk-financial-services.pdf)
* [For the First Time, Nasdaq Is Using Artificial Intelligence to Surveil U.S. Stock Market](https://www.nasdaq.com/articles/for-the-first-time-nasdaq-is-using-artificial-intelligence-to-surveil-u.s.-stock-market)
