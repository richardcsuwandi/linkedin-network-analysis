# LinkedIn Network Analysis
[![View on Medium](https://img.shields.io/badge/Medium-View%20on%20Medium-red?logo=medium)](https://towardsdatascience.com/analyzing-my-own-linkedin-data-24df63a9dc28)

## Motivation
As an active user on [LinkedIn](https://www.linkedin.com/in/richardcsuwandi/) with more than 1000 connections, I was curious about the statistics of my network. 
In particular, I was wondering about these questions:

> What are the segments of people in my network?

> Do most of the people in my network work in data science related field?

In this project, I will go through how I utilized exploratory analysis and data visualizations to answer these questions and gain insights from my own LinkedIn data.

The notebook of this project can be found [here](https://nbviewer.jupyter.org/github/richardcsuwandi/linkedin-network-analysis/blob/master/linkedin-network-analysis.ipynb)

## Data
To analyze and visualize my network, the first step that I need to do is to get my LinkedIn data. 
All I need to do is just select which data I want to get and it will be downloaded as a CSV file.
![LinkedIn Data](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/data.png?raw=true)

Here are the first few rows from the `Connections.csv` file that I've downloaded:
![DataFrame](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/df.png?raw=true)

The DataFrame above contains data about the current positions and companies of people in my network as well as when the date I connect to that person.

## Key Findings

### Number of Connections on a Given Date
> How many connections did I make in a given date?

![Date Connected](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/date_connected.png?raw=true)
From the line plot above, we can see that there is a peak in the number of connections per day on 26 August 2020. It also seems that August 2020 is the period when I was the most active on LinkedIn.

### Top Companies/Organizations in my Network
> Which companies/organizations do the people in my network mainly come from?

![Company Bar Plot](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/company_bar.png?raw=true)
![Company Treemap](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/company_treemap.png?raw=true)
Using the treemap above, it is easier to compare the proportion of one company/organization to the others. It looks like the largest proportion of my network are from my university.

### Top Positions in my Network
> What are the top common positions of people in my network?

![Position Bar Plot](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/position_bar.png?raw=true)
![Position Treemap](https://github.com/richardcsuwandi/linkedin-network-analysis/blob/master/images/position_treemap.png?raw=true)
The top position in my network is data scientists, followed by machine learning engineers and data analysts. It is great to know that the top common positions in my network are my target group for networking.
