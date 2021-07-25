# PyBer_analysis
Module 5: PyBer with Matplotlib 
https://github.com/AKumar1-lab/PyBer_analysis
## Objective: 
Analyze and visualize ride-sharing data using the power of Python, Pandas, Matplotlib, Numpy and SciPy.

## Resources: 
Data Source:  pyber.ipynb; Pyber_Challenge.ipynb; city_data.csv; ride_data.csv; 

Software: Anaconda 3.8.8, Python, Pandas Library, Matplotlib, Numpy, SciPy, Jupyter Notebook

## Overview of Project
Matplotlib was used to create line charts, bar charts, scatter plots, bubble charts, pie charts, and box-and-whisker plots, and make them visually compelling and informative by adding titles, axes labels, legends, and custom colors. An introduction to SciPy, a statistical Python package, and NumPy, a fundamental package for scientific computing in Python. Using Pandas, SciPy, and NumPy to perform summary statistics in creating visualizations of rideshare data to the CEO and for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Background
The CEO of Pyber has assigned a brand-new assignment. Using Python skills and knowledge of Pandas, a summary DataFrame of the ride-sharing data is created by city type. Then, using Pandas and Matplotlib,  a multiple-line graph that shows the total weekly fares for each city type. Finally, a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

Deliverable 1: A ride-sharing summary DataFrame by city type.

Deliverable 2: A multiple-line chart of total fares for each city type.

Deliverable 3: A written report for the PyBer analysis.

## Deliverable 1 Requirements: Create a Summary DataFrame

### The total number of rides for each city type is retrieved.** 

<img width="591" alt="deliverable 1_1 total rides by city type" src="https://user-images.githubusercontent.com/85860367/126891943-37b66c03-20ca-4456-89ac-cb65cdd54f66.png">

### The total number of drivers for each city type is retrieved.

<img width="591" alt="deliverable 1_2 total drivers by city type" src="https://user-images.githubusercontent.com/85860367/126891961-b99865fe-d7f8-4303-ad5f-e308e69949c5.png">

### The sum of the fares for each city type is retrieved.

<img width="591" alt="deliverable 1_3 total fare by city type" src="https://user-images.githubusercontent.com/85860367/126891976-e14498dd-1f68-43e7-b077-b54dc253e193.png">

### The average fare per ride for each city type is calculated. 

<img width="591" alt="deliverable 1_4 avg fare per ride by city type" src="https://user-images.githubusercontent.com/85860367/126891997-c01a98c5-ce72-45df-9aee-f82dd94a1f8d.png">

### The average fare per driver for each city type is calculated. 

<img width="591" alt="deliverable 1_5 avg fare per driver and city type" src="https://user-images.githubusercontent.com/85860367/126892015-dde55736-a3f9-4bbf-9f25-8a2a2b3793ca.png">

### A PyBer summary DataFrame is created.

<img width="591" alt="deliverable 1_6 Pyber Summary DF" src="https://user-images.githubusercontent.com/85860367/126892028-0f540841-d714-4889-88ab-dd09da0abf1c.png">

### The PyBer summary DataFrame is formatted as shown in the example. 

<img width="591" alt="deliverable 1_8 Format Pyber Summary DF" src="https://user-images.githubusercontent.com/85860367/126892062-9f741409-63f3-456a-b1c7-c23783c1a6bb.png">

## Deliverable 2 Requirements: A multiple-line chart of total fares for each city type

### A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied.

<img width="407" alt="deliverable 2_1 Create group by fare type date" src="https://user-images.githubusercontent.com/85860367/126893052-2e4dc909-3ae0-42bc-8296-53290c1633f7.png">


### A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 

<img width="497" alt="deliverable 2_2 create pivot" src="https://user-images.githubusercontent.com/85860367/126893062-99bb6ed6-bd4e-4581-86a8-6f9f40e1f39d.png">


### A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.

<img width="604" alt="deliverable 2_3 use loc function on date" src="https://user-images.githubusercontent.com/85860367/126893073-bec70529-f6d7-4fca-ae33-0d4d10c9ff48.png">


### A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week. 

<img width="613" alt="deliverable 2_4 resample" src="https://user-images.githubusercontent.com/85860367/126893090-437f6499-fa4f-43c6-8448-70be0c08209b.png">


### An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 
![Fig8](https://user-images.githubusercontent.com/85860367/126893102-758f61b1-b3e3-4ab2-9a19-0923caa77836.png)

## Summary
### Results

![Fig1](https://user-images.githubusercontent.com/85860367/126894199-4064d32b-cf84-4ba2-a19c-fc9930ee38c6.png)

We found disparities in fare, driver count and the city type that need to be addressed by the CEO if ride sharing is going to be successful.
1) Our findings show that there are less ridership in rural and suburban areas; and more ride-sharing opportunities in urban areas.  The higher fare and not enough drivers may be a reason that the rural and suburban communities choose not use the ride-sharing service.

![Fig6](https://user-images.githubusercontent.com/85860367/126893754-7431a520-012c-4213-b967-161c306ebb61.png)

2) Our finding show that the fare is higher in rural and suburban areas and it also may be closely correlated to small number of drivers in these areas.  We may need to hire more drivers, or offer a price break to attract more clients of the rural and suburban areas.  We may need to pitch ideas to the clients on more daily or routine trips like going shopping, appointments, and other short trips for rural and suburban areas.  Ride sharing does not need to be limited to nightlife, entertainment or special occasions.

![Fig7](https://user-images.githubusercontent.com/85860367/126894045-f2857922-6666-425a-b60c-2ec33cc61e97.png)


3) After further analysis on fare in a weeks over the course of 4 months in the cities of rural, suburban and urban areas.  It was much more apparent that there was no overlap in fare, which means that each area is a hub, and may need to have an average fare that is fixed to each city type. 

![Fig5](https://user-images.githubusercontent.com/85860367/126894309-68cfc62d-e658-4dc3-8c65-c053cbc21cec.png)

