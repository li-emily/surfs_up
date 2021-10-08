# surfs_up

## Overview

### Purpose
> W. Avy is an investor interested in opening up a shop in Oahu, Hawaii. He likes your climate analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Resources
- Language: Python 3.7.10, SQL
- Interface: Jupyter Notebook, Visual Studio Code
- Environment: Miniconda
- Packages: Numpy, Pandas, Matplotlib, SQLAlchemy

## Results
### June Results
<ul>
  <li> Below is the summary statistics of June in Oahu.</li>
  <li> Temperature in June is an average of about 75º. It varies from 73º at the coolest, to 85º at the hottest, but with a low standard deviation of 3.2º, the temperature is relatively consistent and warm.</li>
  <li> Precipitation in June is also rather consistent and low, with an average of 0.13 inches.</li>
</ul>
  
<p float="left">
  <img src="/Resources/june_temp.png" height="250" />
  <img src="/Resources/june_prcp.png" height="250" /> 
</p>

<ul>
  <li> Below is the histogram of June temperatures in Oahu.</li>
</ul>
  
<img src="/Resources/june_hist.png" />


### December Results
<ul>
  <li> Below is the summary statistics of December in Oahu.</li>
  <li> Temperature in December is an average of about 71º. It varies from 56º at the coolest, to 83º at the hottest, but with a low standard deviation of 3.7º, the temperature is relatively consistent and warm.</li>
  <li> Precipitation in December is also rather consistent and low, with an average of 0.21 inches.</li>
</ul>

<p float="left">
  <img src="/Resources/dec_temp.png" height="250" />
  <img src="/Resources/dec_prcp.png" height="250" /> 
</p>

<ul>
  <li> Below is the histogram of December temperatures in Oahu.</li>
</ul>

<img src="/Resources/dec_hist.png" />

## Summary
The data analysis that W. Avy wished for us to complete reveals that the climate in Oahu seems to be well suited towards opening a surf and ice cream business. Both June and December have an average temperature in the 70º's, with June never below 73º. December, on the other hand, does reach 56º at the coolest. However, as shown on the histogram, that temperature is quite an outlier, with most days around 70º. An additional query was done and added above for both months in regards to precipitation, in order to see the fluctuations throughout the year. Both June and December had consistently low amounts of precipitation, with 0.13 and 0.21 inches, respectively. If additional analysis is desired, queries could be made for each month, or by year to see if weather patterns are changing over time. Based on this information, W. Avy should be willing to go forward with his plans.
