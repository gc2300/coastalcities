# Prioritizing Urban Resilience Investments


This program supports the prioritization of urban resilience investments based on two metrics:
(i) expected damage to building structures and contents due to flooding;
(i) criticality of buildings to surrounding communities based on network analysis of travel distance. 

We apply the model to hospitals and schools in Haiti. The code does the following:
* acquire data for selected buildings types from OpenStreetMap, including floorspace (square meters);
* acquire expected water depths for rainfall events of given return period;
* calculate expected loss from the individual rainfall events and Annual Average Loss;
* apply network analysis to rank buildings on their criticality to communities.

The required inputs are flood hazard maps, OpenStreetMap, and damage functions. The user should input their damage function as a csv file in the data folder. For full data requirements see write-up.

The program generates estimated losses at building level, and a rank-ordering of structures by expected loss and criticality.

Thanks to Prof. Masoud Ghandehari for his guidance on this work.

Nick Jones, Guobing Chen, NYU Center for Urban Science and Progress (September 2018).
