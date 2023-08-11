# Non-Relational-Databases

### Start Cassandra services in detached mode
docker-compose up -d
<br>
<br>

![image](https://github.com/furkanbyc/Non-Relational-Databases/assets/90900094/a6866458-67a0-47fc-9093-1a69be93e102)

----------------------
## Cassandra - Case 1

![image](https://github.com/furkanbyc/Non-Relational-Databases/assets/90900094/7deeb57c-febf-4bcc-93be-0fecbbd1f8d4)


### Business Problem

Iyzico is a financial technology company that enhances the online shopping experience for both buyers and sellers. It provides payment infrastructure for e-commerce companies, online marketplaces, and individual users. With the dataset at hand, the goal is to establish a Cassandra database for conducting queries related to historical data.

<br>
<br>

### Dataset Story

| Feature             | Description                                   |
|---------------------|-----------------------------------------------|
| transaction_date    | History of sales data                         |
| merchant_id         | ID's of member businesses                     |
| category            | Categories of member businesses               |
| total_paid_price    | Payment amount                                |
