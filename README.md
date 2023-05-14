![final](https://github.com/mdtran105/Final-Project/assets/109849722/f4c45fca-b1f6-414e-a53f-fee330928006)

## Dataset
[kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?datasetId=55151&sortBy=voteCount&select=olist_order_items_dataset.csv)  
Brazilian E-Commerce Public Dataset by Olist - a SaaS (Software as a Service) technology company.  
Observation: 71,634 delivered orders
Period: 8/2017 - 7/2018

## Project Objective
* Late delivery: What are the influential factors?
* Over 90% of orders delivered before expected date: How can Olist deliver so many orders early?
 
## Tech Stack
* Python (pandas, seaborn, matplotlib, sklearn): [Notebook for this project](Analysis.ipynb)
* Tableau: [Tableau Dashboard](https://public.tableau.com/views/FinalProject_16825921635680/Dashboard12?:language=en-US&:display_count=n&:origin=viz_share_link)
 
## Recommendation of project
* Last-mile delivery is heavily dependent on one carrier partner:
  * More cooperation with 1-2 shipping organizations.
  * Investing in development of own logistics service.
* Setting the estimated delivery date by a range (e.g. 3-5 days) instead of an exact date.
* Providing order tracking, frequent updates on the order status. Letting buyers know what to expect for their delivery and being notified of any late or early delivery.
* Significant difference between estimate and actual delivery date.
  * Researching and improving model to estimate delivery time more accurately.
