Homework DataLearn DE-101 Module 01

1. Architecture of Data Analytics solution
I developed the Architecture Solution y using draw.io.

1. Source Layer.
The source of systems with Raw Data (OLTP - Online Transaction Pocessing).
Processing transactions,the systems quickly work for Data adding to DataBases but don't good for analysis responds, business processes makes Data, all Raw Data goes to a storage.

2. Storage Layer.
Storage of Data for further analysis (DataWarehouses, DataLake, DataPlatform).
Should have 2 layers for Data, Staging - a copy og all Data from Source Layer, BL - a Data model.

3. Business Layer.
Business users have an access to all Data by using I Business Intelligence tools (Tableau, Power BI, SAP BO, Excel, QlikView) or SQL. There is connection to the systems for the generating of reports.

There can be one more layer - Processing/ Computer Layer - for data transormation before loading to a storage.
