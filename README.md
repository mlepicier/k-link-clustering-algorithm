# K-Link Clustering Algorithm

## Abstract:
<i>This project consist of implementing a k-link clustering algorithm to optimize allocation of product category amongst a set of harehouses to minimize the splitting of e-commerce orders and lead to logistics cost reduction. This has a wide range of <b>different business applications</b>, from network optimization to market basket-analysis, particuliarly in the step of data mining to find patterns within data and in the world of finance for portfolio optimization. This project was conducted from September 2020 to January 2021 as a student at the <b>University of Technology of Troyes</b>. Below are a few paragraphs to give you context about the project.</i><br/>

## Business Context:
<p align="justify"> In e-commerce, many customers favor companies that offer shipping costs. Indeed, the latter can represent a significant cost for the customer who can therefore cancel his order at the last moment. Surveys confirm this: according to a study conducted by <i>PayPal</i> and <i>ComScore</i>, 43% of French Internet users do not make a purchase, despite having put together a cart because of high shipping costs. We can therefore say that offering shipping costs allows to get rid of the the main obstacle to online purchasing. In order to be more competitive and to attract more and more new customers, it is therefore interesting and judicious for a company to offer these costs related to delivery. But caution, this means that these costs will be charged to the company, which can impact the profitability and therefore implicitly the sustainability of the business. The decision to offer delivery costs should not be taken lightly and must be based on a solid, successful and controlled strategy.</p>

<p align="center"><b>So, how to offer shipping costs while remaining profitable?</b></p>

## Problem Description:
<p align="justify"> In this project, we addressed this issue by studying one of the major problems related to delivery in the e-commerce domain. This problem is the "<i>splitting order</i>". This phenomenon occurs when an order includes several items, often of different categories, stored in different warehouses. In this case, it is impossible to avoid splitting orders and therefore the multiplication of warehouse-to-customer deliveries because several shipments will be necessary, thus considerably increasing the delivery cost and therefore the overall cost. If this phenomenon is not mastered and studied upstream by the company, two cases appears:</p>

- Impossible for the company to offer delivery to its customers leading to a significant loss of earnings.
- The company will become less profitable.

<p align="justify"> Both cases inevitably lead to an increase in costs and a decrease in customer satisfaction, two key notions for the survival of a company and its development.</p>

## Data:
<p align="justify"> To handle this problem, we need a dataset with a set of multi-category customer orders. We imported a dataset from the <i>Kaggle</i> platform. It contains 22,061 sales orders and 60 categories. However, given the <i>NP-Hardness</i> of the problem, the size of our dataset is too large to be processed on <i>CPLEX</i>. We then had to modify this dataset and make it lighter. Only for the purpose of comparing the results between the heuristic and its linear model equivalent, we used a dataset with 117 customer orders that can contain up to 15 different product categories.<p>

## Assets:

<p align="justify">If you are interested to know more about this project you can dive deeper within the following assets of the repository:<p>

- [CPLEX Linear Models](linear_models_cplex)
- [KLCA Heuristic Notebook](klca_heuristic_python)
- [Order Datasets](data)
- [Project Report](k-link_report.pdf) - To be translated in English

<br/>

***

<i>Should you have any question, feel free to write me an [email](mailto:mlepicier.msc2022@ivey.ca), I am always happy to help.</i>
