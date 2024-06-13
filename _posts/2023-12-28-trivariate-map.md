---
title: 'Is It Wise to Use Trivariate Map for Accommodating Three Information into one Visualization?'
date: 2024-01-01
permalink: /posts/2024/01/is-it-wise-to-use-trivariate-map-for-accommodating-three-information-into-one-visualization/
tags:
  - trivariate-map
  - climate-change
  - visualization
---

![cover](https://www.dropbox.com/scl/fi/fnqpp52luo3qok8mb7xre/cover.png?rlkey=ndh92gp55om9yk470h3ce0jcb&raw=1)
I was wondering if I could add one more variable to my previous bivariate map, and here they are: triangulating 1) Population Density (represented by point size); 2) Kilometers traveled per year by people who travel to work by Car or Van (gold color); and 3) Total carbon footprint per person in kgCO2e (blue color) into a trivariate map!

However, the visualization process was a bit tricky, considering MAUP and finding a balance between the precision and intuition of the map. That's why I created two versions of the map with different mapping units: 1) using given mapping units (i.e., LSOAs) and 2) converting the LSOAs into Hexagonal Grids. The results are as seen in the figures.

![trivariatemap1](https://www.dropbox.com/scl/fi/71weosg65x2e93zofkenf/trivariatemap.jpeg?rlkey=zxqv1ze8ac1n9ngls3t7op33c&raw=1)
Centroids by LSOAs

![trivariatemap2](https://www.dropbox.com/scl/fi/4dm4cl2cxdar9y9fe285v/trivariatemap2.jpeg?rlkey=1vo9uwmy2kmpiq5zti5w41req&raw=1)
Centroids by Hexagonal Grids

Personally, it was quite challenging to interpret the map in a short period of time. It required careful consideration to understand what is happening with these three variables. Despite the complexity, I believe these maps are still interpretable enough to explain the correlation of higher dimensions of variables in one piece of visualization, which is a significant discovery for me personally.

While taking my time to create these maps, I wondered if there was any other way to visualize a trivariate map that is more intuitive. Additionally, is it possible to enhance a tri map into a quad map? I will leave these questions for another time.

Project code: https://github.com/ofitrahramadhan/trivariatemap_R
Data source: https://www.carbon.place/