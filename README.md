**<ins>NOTE: THIS IS A STUDENT PROJECT WITH<ins> [DATAFIED ACADEMY](https://github.com/Datafyde)**

![image](https://github.com/Amiphel/Datafied-first-guided-project-Power-BI-/assets/157698401/3e5c49a4-85af-41af-8769-050b239e3e97)

**CRIME TRENDS IN LONDON AND WALES, 2012-2023**


In today's world, crime rates have surged, posing complex challenges for law enforcement globally. To tackle these issues head-on, the integration of advanced technologies and data analysis is crucial. This case study delves into how crime data analysis can elevate the effectiveness of law enforcement in a major city.



<h1>PROBLEM STATEMENT</h1>

My client, a big-city police department, is grappled with escalating crime rates and in need for a more proactive crime prevention strategy. The client reach out to Datafied Technologies to seek expertise to leverage data analytics to gain insights into crime patterns, potential crime hotspots, and develop targeted strategies for crime reduction.


As a junior data analyst at Datafied Technlogies, i have been deputized to harness the power of data analytics to:

Identify and understand crime patterns and trends.

Identify potential crime hotspots based on data-driven insights.

And enhance proactive crime prevention strategies.




<h1>DATA SOURCING</h1>

The dataset is built from The 'Police recorded crime open data tables, year ending March **2013** up to **2023**, released is a top-tier statistical output adhering to professional standards, Produced by Home Office statisticians, it ensures objectivity and complies with the Code of Practice for Statistics.


![image](https://github.com/Amiphel/Datafied-first-guided-project-Power-BI-/assets/157698401/86d585e4-d32b-4c48-adbc-81fe1ead2c32)


The geographical area under study are all regions in England and Wales;

- Eastern Region

- East Midlands Region

- London Region

- North East Region

- North West Region

- South East Region

- South West Region

- Wales

- West Midlands Region

- Yorkshire and the Humber

Covering all police force and community safety partnerships (CPS) in these regions.

Data Source:

[Crime records](https://docs.google.com/spreadsheets/d/1zXSzFgQ-IV0NWH6zlZWbK4A3irsKjtOpammXa8FUte4/edit#gid=1821703077)

[Geo Data](https://docs.google.com/spreadsheets/d/1wQbjhMO7cj8HoakhEuLeX2-9bZgSAO02UdCLOHE8gBs/edit#gid=893458933)





<h1>PROJECT OBJECTIVE</h1>

The successful execution of this project will empower the police department to make informed decisions, leading to a substantial improvement in crime prevention and law enforcement effectiveness. This will not only transforms traditional policing methods but also underscores the significance of a proactive, data-driven approach in addressing the evolving challenges of crime in urban environments.


<h1>DATA TRANSFORMATION AND CLEANING</h1>

The dataset was cleaned by removing duplicates, filtering rows and columns, correcting inconsistencies, and ensuring the data is in a suitable format for analysis and visualization.

**Dataset Before Cleaning**

<img width="872" alt="image" src="https://github.com/Amiphel/Datafied-first-guided-project-Power-BI-/assets/157698401/f10b5fff-10ee-4e34-9131-98e4ece4adf9">

**Dataset After Cleaning**

<img width="955" alt="image" src="https://github.com/Amiphel/Datafied-first-guided-project-Power-BI-/assets/157698401/9e443918-3070-4295-8ed6-5e245292e82e">



<h1>DATA MODELING</h1>

Dimensions with which to break down the analysis were identified. Hence, new tables for the identified dimensions were created. They are;

- Offence dimension

- Date dimension

- Location dimension

The data model was designed using the Star Schema where the different dimensions were connected to the Fact table in a one-to-many relationship.

<img width="950" alt="image" src="https://github.com/Amiphel/Datafied-first-guided-project-Power-BI-/assets/157698401/20380095-9e9e-41dd-9946-3da1817f1d19">

