# Snow-Prediction-Almanac

## This project uses Python, matplotlib and gmaps to examine weather data from a variety of sources to find a long lead time indicator of a high snowfall year.

Null Hypothesis:  there is no correlation between each factor and seasonal snowfall

Alternative Hypothesis:  One or more factors has a statistically significant impact on seasonal snowfall.

## 1)Data collection, cleaning and merging:

Snotel automated weather sites data from 1980-2020 via NRCS website

NWS Climate Prediction Center ENSO and PNA data

https://www.pro-football-reference.com/ for Broncos data

![snotel](/images/readme_snotel.PNG)

![heatmap](https://github.com/ajhibshman/Snow-Prediction-Almanac/blob/main/images/snotel_sites2.PNG)

## 2) Initial analysis of weather data:

![trends](https://github.com/ajhibshman/Snow-Prediction-Almanac/blob/main/images/trends.png)

## 3) Analysis:

Example slide showing August precipitation vs. SWE (Snow Water Equivelent of snowpack)

![aug](https://github.com/ajhibshman/Snow-Prediction-Almanac/blob/main/images/readme_aug.PNG)

## 4) Snip of coding in Jupter notebook:

![df](https://github.com/ajhibshman/Snow-Prediction-Almanac/blob/main/images/readme_df.PNG)

![code](https://github.com/ajhibshman/Snow-Prediction-Almanac/blob/main/images/readme_code.PNG)

## 5) Conclusions:

Most factors examined showed little to no correlation and the data largely failed to reject the null hypothesis.

The strongest r value was prior years snowfall to early season showing some tendency for strong snow totals to spill over into the next season.

ENSO showed some negative correlation indicating colder values may predict higher snowfall, however the data has high variation.

A Broncos poor season may have some correlation with stronger snowfall the following winter. 

August Average Temperature shows a clear increase over time, with an r-value of .6
















