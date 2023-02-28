# Executive Summary

-   **Data synopsis:** Brazilian E-commerce Public Dataset: Retail
    datasets of 100k orders placed on Olist spanning between
    October'2016 and September'2018 across several states. Information
    is trickled with price, orders, order status, payment, freight and
    user review along with many other parameters.

## Introduction

<div align="justify">
    Businesses have always tried to keep their customers base engaged and
satisfied with the services provided by them. For remaining relevant in
the industry, they need to incorporate the latest technological advances
into their services. More than a decade back, it was the internet which
was completely new and various industries tried to leverage the
capabilities of this technology that effortlessly acted as a medium of
communication between various businesses and their customers. In this
decade, industries have started to provide services that are catered
towards each client's individual needs. For such services, they are
required to leverage the power of artificial intelligence.
    </div>

## **Business problem**
<p align="justify">The [Olist store](https://www.olist.com/pt-br){:target="_blank"} is an e-commerce business headquartered in Sao Paulo,
Brazil. This firm acts as a single point of contact between various
small businesses and the customers who wish to buy their products.
Recently, they uploaded a <a href="https://www.kaggle.com/olistbr/brazilian-ecommerce" target="_blank">dataset on Kaggle</a> that
contains information about 100k orders made at multiple marketplaces
between 2016 to 2018. What we purchase on e-commerce websites is
affected by the reviews which we read about the product posted on that
website. This firm can certainly leverage these reviews to remove those
products which consistently receive negative reviews. It could also
advertise those items which are popular amongst the customers.
</p>

## **Formulation of business problem**

<div align="justify">
    In this project, with a use of Microsoft Power BI
tool, a presented dashboards that summarizes the overall satisfaction of
the customers with the products which he or she had just purchased. As
well as descriptive, deliveries analysis and forecasting analysis.
    </div>

## Organizational structure (Stakeholder)

<div align="justify">
    Olist organizational structure data is layered. The CEO leads the
company and is sometimes the chairman or owner. He has the most invested
in the company and makes significant decisions, including as analyzing
and approving team budgets and assuring subordinates can do their jobs
well.
    </div>

<div align="justify">
Second is the marketing team; whose role is to market the company\'s
products using cutting-edge technology to compete commercially. The
financial team helps the company manage its accounts, income before
interest, taxes, depreciation, debt, loans, and cash according to the
budget. This group will also provide clients conditional vouchers to
increase sales or any marketing budget required to get this project up
and running.
    </div>

<div align="justify">
Information technology (IT) team is responsible for overseeing every
aspect of the company\'s system, including its hardware and software.
This team supports all other teams inside the organization. The
e-commerce team, which comes in at number seven, is crucial to the
online sales process. Customers will be dealt with personally by these
personnel, who will also guarantee their happiness with every
transaction There is more department that exist in this company however
for our issue and project, these are the most impacted and involved in
the project.
    </div>

## Dataset 

<div align="justify">
I am going to make use of the dataset that was so generously provided by
Olist, which is the largest department store in Brazilian marketplaces.
Olist eliminates administrative burdens and consolidates legal
obligations by linking small enterprises located anywhere in Brazil to
various distribution channels. These retailers are allowed to sell their
wares through the Olist Store and have Olist\'s logistics partners
transport the products straight to the buyers after the sale has been
completed.
    </div>

<p align="justify">
The data consist of almost 100 000 customer id and order id. To
summarize, the data consist of order detail, customer detail, product
detail, seller detail, payment detail, geolocation detail and review
detail. The entity-relationship model is shown in Figure 1 to help
understand how the data interrelate with each other.
<a href="https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce" target="_blank">Kaggle</a>
</p>
  
  
![fig 1](https://user-images.githubusercontent.com/126220185/221439446-fcbbe806-e0d4-46cd-a6f9-3d8b4b9c7df8.png)



  ---------------------------------------------------------------------------
  **Table**                      **Description**
  ------------------------------ --------------------------------------------
  olist_orders_dataset           This table is connected to 4 other tables.
                                 It is used to connect all the details
                                 related to an order.

  olist_order_items_dataset      It contains the details of an item that had
                                 been purchased such as shipping date, price
                                 and so on.

  olist_order_reviews_dataset    It contains details related to any reviews
                                 posted by the customer on a particular
                                 product that he had purchased.

  olist_products_dataset         It contains related to a product such as the
                                 ID, category name and measurements.

  olist_order_payments_dataset   The information contained in this table is
                                 related to the payment details associated
                                 with a particular order.

  olist_customers_dataset        Details the customer base information of
                                 this firm.

  olist_sellers_dataset          This table contains the information related
                                 to all the sellers who have registered with
                                 this firm.

  olist_geolocation_dataset      It contains geographical information related
                                 to both the sellers and customers.
                                 
  ---------------------------------------------------------------------------

# Visualization Analytics

## Data model

<div align="justify">
Once I have downloaded the dataset from
Kaggle, it is possible to load it into Power BI. The data will have to
be pre-processed in order to obtain relevant analytics as it only has
the tables and keys referring to each file of the dataset. At first we
obtain the data model visible in the following image.
    </div>
 
 
![2](https://user-images.githubusercontent.com/126220185/221439638-d6a8a3e3-02f6-4f0e-8bc9-344a21846486.png)


<div align="justify">
Thus, it needs to make links between tables depending on how they
interact with each other. The olist_geolocation and product_category
tables are not linked to the model at all which means it is not possible
to leverage this data. The temporal is also not explicitely indicated as
Power BI needs rigorous time management to apply it to the other tables.
Moreover, the variables have a type depending on whether they are
numerical or textual data. Indeed, we can see that it contains data
about transportation logistics, customers, sellers and their different
products each with a different type. In the end, we can see the result
on the following image.
    </div>

  
  
![3](https://user-images.githubusercontent.com/126220185/221441944-c258dffe-c8d3-4511-8763-4d297ed9ad52.png)
 

## Dashboards


![Ahmed Hsahim- AA- Dashboard_page-0001](https://user-images.githubusercontent.com/126220185/221442502-e783c985-dc70-4222-966b-40eed984f45d.jpg)


![Ahmed Hsahim- AA- Dashboard_page-0002](https://user-images.githubusercontent.com/126220185/221442503-19e32d21-40a5-4428-b2bb-7e0c517f90cc.jpg)


![Ahmed Hsahim- AA- Dashboard_page-0003](https://user-images.githubusercontent.com/126220185/221442504-67d7cedc-debb-423e-9e06-e5c71b0aee07.jpg)


![Ahmed Hsahim- AA- Dashboard_page-0004](https://user-images.githubusercontent.com/126220185/221442506-91171d8d-9d3c-4384-95cb-9bbb1674ce2d.jpg)


![Ahmed Hsahim- AA- Dashboard_page-0005](https://user-images.githubusercontent.com/126220185/221442494-391dd4bb-f863-43f1-a93d-9dea79774c8d.jpg)


![Ahmed Hsahim- AA- Dashboard_page-0006](https://user-images.githubusercontent.com/126220185/221442498-14cb0553-b86b-45a1-8815-10b72a7b98bb.jpg)


![Ahmed Hsahim- AA- Dashboard_page-0007](https://user-images.githubusercontent.com/126220185/221442501-7b1653a9-0d14-4fe4-8bbc-6467e553e30e.jpg)


# Insights

<div align="justify">
    Olist has a delivery success rate of approximately 85%. This may
indicate that the company is facing some challenges with its delivery
process, and it may be worthwhile to investigate the causes of the
undelivered orders and take steps to improve the delivery success rate.
Some potential areas to look into could include the efficiency of the
company's logistics and fulfillment processes, the reliability of its
transportation partners, and any potential issues with the quality or
accuracy of the orders being placed.
    </div>
 

<div align="justify">
    Olist company has a high level of customer satisfaction overall, with a
significant number of positive reviews and scores. However, the fact
that the lowest-rated product category is "Security and Services"
suggests that this type of product may need improvement.
    </div>

# Recommendations


-   Monitor and analyze customer reviews regularly to identify trends
    and areas for improvement. This could involve using data analysis
    tools to identify common themes in customer feedback and using this
    information to make changes and improve the customer experience.


-   Investigate the causes of undelivered orders. This could involve
    analyzing the undelivered orders to identify common themes or
    factors that may be contributing to the problem. For example, are
    certain regions or customer demographics more likely to have
    undelivered orders? Are there particular products or types of orders
    that are more likely to be undelivered? 


-   Communicate with customers about the delivery process. Olist should
    be transparent with customers about the delivery process and provide
    them with regular updates on the status of their orders. This will
    help to build trust and create a positive customer experience. It
    will also give customers the opportunity to provide feedback on
    their experiences with the delivery process, which can be used to
    identify areas for improvement.


-   Overall, the key is to continue providing high-quality products and
    services, while also being responsive to customer feedback and
    working to improve areas that may need attention. Also regularly
    monitor and review the delivery success rate and communicate with
    customers about the process.

# Suggestions:

-   Special offerings to boost overall sales on low sales period 

-   Improve bottom selling categories by providing advertisements or promotions

-   Outsourcing drivers for delivery during Sales or Festival periods

-   Investigate and Review the partner company with low review score

-   analysis customers comments and reviews provided in the dataset with NLP or
    any kind of language processing models
