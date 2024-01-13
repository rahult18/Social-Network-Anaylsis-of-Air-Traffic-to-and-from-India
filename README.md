# Social Network Analysis of Air Traffic to and from India

## Abstract

Air travel plays a crucial role in global economic expansion, generating jobs, facilitating trade, and contributing significantly to GDP. This project focuses on studying air traffic to and from India using Social Network Analysis (SNA). By employing centrality measures, we aim to identify the busiest airline routes and airports, analyze passenger and freight traffic, and assess India's position in the global aviation market.

## Proposed Work

### 1. Data Gathering

We utilize data from [openflights.org](https://openflights.org), containing 59036 routes between 3209 airports on 531 airlines worldwide. Two datasets are used: one for airport information (nodes) and the other for flight details (edges).

### 2. Data Visualization and EDA

The network is visually represented, and exploratory data analysis (EDA) is conducted using metrics such as connectivity, diameter, radius, periphery, and center nodes. Visualization provides insights into the structure and connectivity of the air traffic network.

### 3. Analyzing Busiest Airports and Airline Routes - SNA Performance Metrics

Various centrality measures, including degree centrality, closeness centrality, and betweenness centrality, are employed to identify major airports. Additionally, indegree, outdegree, transitivity, clustering coefficient, average shortest path, density, and articulation points are analyzed.

### 4. Ranking Algorithms

PageRank and HITS algorithms are implemented to determine the importance of each airport node within the network. These algorithms consider incoming relationships and the significance of connecting nodes, providing a comprehensive ranking.

### 5. Passenger Traffic Analysis in and out of India

A flight map illustrating traffic in and out of India is created for visualization. Passenger traffic is analyzed on a monthly and quarterly basis, identifying the top airlines and busiest air routes. The findings are presented graphically to enhance understanding.

## Conclusion

This comprehensive social network analysis sheds light on India's aviation market, uncovering insights into the busiest routes, major airports, and passenger traffic patterns. The use of SNA metrics and ranking algorithms provides a nuanced understanding of the global aviation landscape and India's standing within it.

**Note:** Data used is sourced from [openflights.org](https://openflights.org) as of January 2012.
