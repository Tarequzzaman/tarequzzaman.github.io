---
title: Benifit & Drawback of Using Apache Superset as Data visualization tools
tags: [Apache Superset, Data Visualization, Open Source]
style: fill
color: info
comments: true
description: Superset is fast, lightweight, intuitive, and loaded with options that make it easy for users of all skill sets to explore and visualize their data, from simple line charts to highly detailed geospatial charts.
---

<br>
<br>
<br>
Recently I have started using Apache superset as data visualization tool. In this article I will share my experience with apache superset.  

![image](https://raw.githubusercontent.com/apache/superset/master/superset-frontend/src/assets/branding/superset-logo-horiz-apache.png)

### [What is Apache Superset ? ](https://superset.apache.org/)


Apache Superset is a opensource data visualization tool with a simple interface, easy to use, wide range of datasource support that allows the users to create and share dashboards. This tool is highly dependent on sql. So for using this tool, sql knowledge is must. 
<br>
<br>
### Benifit of Apache superset: 

- **Intuitive user interface:** Superset provides an easy-to-use, drag-and-drop interface for creating and exploring visualizations. 

- **Powerful visualization options:** Superset supports a wide range of chart types, including bar charts, line charts, scatter plots, and more. I found almost 50 useful charts here.  It also allows someone to easily customize the appearance of your visualizations and create interactive dashboards.

- **Data exploration:** Superset allows you to explore your data through a variety of filters and aggregations, making it easy to quickly understand patterns and trends in your data.

- **Data source flexibility:** I think superset is best for datasource support. Superset can connect to a wide range of data sources, including SQL databases, CSV files, and other data sources through connectors. Please visit [here](https://superset.apache.org/docs/databases/installing-database-drivers/) to see detail about datasource support.<br>
If anyone have data engineering knowledge can easily install the python library to connect with datasource.

- **Scalability:** It's designed to be highly scalable and can handle large datasets. It is highly scalable, as it can process different data sizes while maintaining its optimal performance. 


- **Security:** Superset provides role-based access control, encryption and authentication support, allowing you to secure your data and visualizations.

- **Community and Ecosystem:** Superset is an Apache Incubator Project and has a large and active community of users and contributors, which means you can find a lot of tutorials, documentation, and support online.

In summary, Apache Superset is a powerful, user-friendly, and flexible data visualization tool that is well-suited for a wide range of use cases, from data exploration and analysis to building interactive dashboards and reports.

<br>
<br>


## Drawback of Apache Superset: 

- **Limited data transformation capabilities:** While Superset allows you to connect to a wide range of data sources and explore your data through filters and aggregations, it has limited capabilities for data transformation, such as cleaning, joining, and reshaping data.

- **Data Blending:** Superset does not natively support data blending, but it is still possible to achieve it by using SQL and data engineering techniques, or by using external connectors to connect to other data sources.

- **Complex setup:** Setting up Superset can be complex, especially for users without experience in web development or data engineering. It requires a number of dependencies to be installed, and the process of configuring and connecting to a data source can be challenging for some users.

- **Limited support for big data:** Although Superset can handle large datasets, it is not optimized for big data workloads, and may not be the best choice for visualizing very large datasets.

- **Limited real-time capabilities:** Superset doesn't have a built-in capability to handle real-time data and would require additional setup and integration with other tools to achieve that.





Though it has some drawback, it is one of the best opensource tool for data visulization. Since opensource community is growig day to day, these drawback will solve soon.  



