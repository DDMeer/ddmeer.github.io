---
name: Final Plot Display
tools: [Python, HTML, vega-lite, Jekyll]
image: assets/pngs/final3.png
description: This is our final plot!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Final plot

Example comes from this [great blog post right here](https://blog.4dcu.be/programming/2021/05/03/Interactive-Visualizations.html) that was also used in [our test import script](https://github.com/UIUC-iSchool-DataViz/is445_bcub
```
Introduction

The title of our dataset is 'National Immunization Survey Adult COVID Module
 (NIS-ACM): Vaccination Status and Intent by Demographics'. So, basically, this is
 a dataset about the survey results of the intent or status for immunization among adults.
 The dataset contains a rich amount of records and categories. For example, the intent
 or status of immunization by age groups, race or ethnicity groups, and geographies.
 After doing some exploratory analysis, we found there are some interesting distributions
 and statistics to study in this dataset. That is why we want to build a dashboard to
 visualize some of the interesting statistical aspects we found about the data.
```

<vegachart schema-url="{{ site.baseurl }}/assets/json/finaldashboard.json" style="width: 100%"></vegachart>



## Search The Data & Methods

Below is our plot completing process:

```
As shown above, this is the dashboard we built for the National Immunization Survey dataset. On the left 
side, we have the United States geographical heat map with Vaccination Rate Estimates of each state as
 values display in different colors. The color atla besides the heat map indicates that the higher
 Vaccination Rate Estimates value, the deeper the color. On the right side, we have a histogram using the
 Mean of Estimate as the horizontal axis and the Race/Ethnicity group categories. To use the dashboard,
 we can choose a state by clicking on the dropbox, and the chosen state will highlight on the map while
 the right plot display its Vaccination Rate Estimates value of different race/ethnicity group interactively.
```
<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/DDMeer/github.io/blob/ddm11/assets/json/jsonfinaldashboard.json" text="The Data" %}

</div>

<div class="right">
{% include elements/button.html link="https://github.com/DDMeer/github.io/blob/ddm11/python_notebooks/Group-12-final-project_part2.ipynb" text="The Analysis" %}
</div>
·
