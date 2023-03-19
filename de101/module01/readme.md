Homework DataLearn DE-101 Module 01.
I designed the data analysis solution architecture using draw.io.

1. Source Layer.
The original layer consists of an Order with payment and item data saved. Availability of goods in stock. to collect data, set up tracking, and create reports on user interactions with your site. CRM to increase sales, optimize marketing and improve customer service

2. Storage Layer.
Storage of Data for further analysis (DataWarehouses, DataLake, DataPlatform).
Should have 2 layers for Data, Staging - a copy og all Data from Source Layer, BL - a Data model. Staging it is an intermediate storage area used to process data during extraction, transformation and loading.

3. Business Layer.
Business users have an access to all Data by using I Business Intelligence tools (Tableau, Power BI, SAP BO, Excel, QlikView) or SQL. There is connection to the systems for the generating of reports.

![Screnshot](https://github.com/RinatKarimov9891/DataLearn/blob/main/de101/module01/Data%20architecture.png)
