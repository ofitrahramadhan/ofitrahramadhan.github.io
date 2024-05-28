---
title: 'Monitoring Airbnb Dynamics with Inside Airbnb Dataset!'
date: 2023-12-01
permalink: /posts/2023/12/monitoring-airbnb-dynamics-with-inside-airbnb-dataset/
tags:
  - insideairbnb
  - bigdata
  - data
---

![insideairbnb](https://www.dropbox.com/scl/fi/toor1qwhysar9ygytkwdh/insideairbnb.png?rlkey=rdhgooga3wlo7cw0fvw95oi3z&raw=1)

In certain cases, significant movements such as startup development can create disruptions. This has happened with Airbnb, where in some areas, the development of Airbnb-oriented properties has triggered externalities such as the increase in permanent housing prices and gentrification.

Due to this issue, the growth of Airbnb should be appropriately monitored. That is what 'Inside Airbnb' has been doing for years. Inside Airbnb publishes a large dataset about the location of Airbnb properties along with their characteristics for FREE!

For example, I have plotted the listings.csv.gz file from Inside Airbnb for London, which provided insights into the distribution of Airbnb listings along with their attributes. The dataset comprises 87,946 rows and 75 columns! Below is the spatial distribution map of Airbnb listings in London. Additionally, I created a hexagonal map using Python to enhance the map's intuitiveness.

![distributionmap](https://www.dropbox.com/scl/fi/rke2pwh8a8mjar0sim076/airbnb-distribution-in-london.jpg?rlkey=e5lzf9ukv6ws5ubwhhtssyq5y&raw=1)

From the map above, it can be seen that the Airbnb properties are spread almost everywhere. However, if these numbers are plotted into a density map, we can extract more information about where the majority of listings are centralized—in the center of the city (see the map below):

![densitymap](https://www.dropbox.com/scl/fi/hcs0hmcbz29nnep0y00ij/airbnb-density-in-london.jpg?rlkey=recvnoop1wjbtqb32ytorcu78&raw=1)

Why is this the case? What are the factors that make these Airbnb properties centralized in the center? Is it because of tourist attractions or something else? All of these questions can potentially be answered by this big dataset.

*If you'd like to see how I created the map based on the Inside Airbnb data, you can check out my GitHub project here. Contact me or drop a comment if you want to collaborate on this project!