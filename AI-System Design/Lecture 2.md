 
**Course:** [[ELEC0136 AI System Design]]
**Date:** 2025-10-15
	**Source:** [Lecture Slides](url)

---
## 🧩 Data Acquisition
-  N.B. Note a machine learning course -- just for AI System design -- the algorithms themselves need independent study to handle. This is 
- 
- Data Acquisition: The **process** with the goal to ensure the data is provided to the AI pipeline. Effectively we are taking messy, unstructured information, and acquisition is the process of organizing and storing in a systematic method.
	- ^ Core to to the AI pipeline
- Data acquisition process occurs through APIs. 
-
## Sources of Data
- **Sources of Data**: Where does it come from?
Requirements of collection of input and outputs data. 
 **Trivial method**: human labeling. Just measure some which are and some which aren't.
 - Three categories of data:
	 1) Live Data: Continuous stream, flexible and abundant. (i.e: directly connected to a sensor)
	 2) Historical Data: (just old stored data, i.e: if I check the stock market from 1st Jan 2017, the API pulls the same info no matter what).
	 3) Synthetic Data: Fake generated data, can be cheap and easy but can be considered to be unreliable. Can be useful since it avoids privacy concern. Could be bullshit tho
### Application Programming Interface
 The way in which we can access the data
	i.e: numpy is an an API when I use it's functionality for handling mathematics and data
	This is an exmaple of a Software API (which is a generic term)
-- we care about software API's and Web Apis(server side). Mostly contains the 
###### We should care about concepts with a Web API
1) Pagination
2) Rate Limits
3) Stateful vs stateless

Web API: Talks over the internet to the web server. 

### RESTful APIs
RESTful API's are a design pattern to develop a Web API. 
To perform a HTTP request is to just go to the address for the API system.


------
## 🧮 Conclusions
$$
y = f(x; \theta)
$$
-- Data handling , remember the sources of data, what an api is and how web scraping operates.
## 🧠 Insights
- **Data Acquisition: The process of gathering and collecting unstructured information and convert it into a known, systematic and useful schema**

## 🔗 Related Topics
- [[Neural Networks]]
- [[Gradient Descent]]


Data Privacy concerns are slowing down innovation in AI. 200
They are slowing down innovation