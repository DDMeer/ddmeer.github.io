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
<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter233.json" style="width: 100%"></vegachart>
```

<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter233.json" style="width: 100%"></vegachart>



## Search The Data & Methods

Below is our plot completing process:

```
This plot used the dataset of “https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv”.
Our group used the scatter plot to analyze the relationship between “County” and “Square Footage”.
We didn’t change the color of the scatter plot, because we think the default color perfectly showed the output understandable and clearly.
In order to show the visualization on git.io, this plot needed to transform the output into a JSON file.
Then we set up a new JSON file for this plot, and added it to the scatter233.json.
```
<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/DDMeer/github.io/blob/main/assets/json/dashboard.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/DDMeer/github.io/blob/main/python_notebooks/group18-assignment10.ipynb" text="The Analysis" %}
</div>

