## Welcome to Spotify viz

You can use the [editor on GitHub](https://github.com/elguel/elguelvizspotify.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<iframe width="492.5" height="304.52916666666664" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTPoUKAu92dOW0Bb7z-oG9RDCU_QZk34bjIZUlNirsIHbBlsnNQclCCmT2kW05Agw/pubchart?oid=909826012&amp;format=interactive"></iframe>


```{r}
htmltools::tags$iframe(
  src = "fig1.html", 
  scrolling = "no", 
  seamless = "seamless",
  frameBorder = "0"
)
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"/>
<style>body{background-color:white;}</style>
<script src="lib/htmlwidgets-1.5.1/htmlwidgets.js"></script>
<script src="lib/plotly-binding-4.9.2.1/plotly.js"></script>
<script src="lib/typedarray-0.1/typedarray.min.js"></script>
<script src="lib/jquery-1.11.3/jquery.min.js"></script>
<link href="lib/crosstalk-1.1.0.1/css/crosstalk.css" rel="stylesheet" />
<script src="lib/crosstalk-1.1.0.1/js/crosstalk.min.js"></script>
<link href="lib/plotly-htmlwidgets-css-1.52.2/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="lib/plotly-main-1.52.2/plotly-latest.min.js"></script>
  <title>plotly</title>
</head>
<body>
<div id="htmlwidget_container">
  <div id="htmlwidget-02539920c9d6553ff78b" style="width:100%;height:400px;" class="plotly html-widget"></div>
</div>
<script type="application/json" data-for="htmlwidget-02539920c9d6553ff78b">{"x":{"visdat":{"456856af3c4a":["function () ","plotlyVisDat"]},"cur_data":"456856af3c4a","attrs":{"456856af3c4a":{"x":{},"marker":{"color":"#12CBC4"},"name":"tempo","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"histogram"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"title":"Frequency distribution of tempo","yaxis":{"domain":[0,1],"automargin":true,"title":"Frequency"},"xaxis":{"domain":[0,1],"automargin":true,"title":"tempo"},"hovermode":"closest","showlegend":false},"source":"A","config":{"showSendToCloud":false},"data":[{"x":[104,91.019,128.136,115.03,101.305,139.982,137.951,148.114,129.943,78.955,128.136,125.963,83.758,101.993,124.98,109.397,128.977,154.281,142.094,141.033,110.019,75.089,121.974,156.005,192.037,133.937,141.978,90.429,100.001,109.027,97.975,116.019,85.063,124.016,136.065,139.983,141.033,140.138,164.077,89.358,154.074,124.963,79.595,128.066,128.017,128.1,99.991,122.031,95.002,148.014,116.735,119.986,120.019,75.025,109.023,123.935,76.469,97.008,75.801,100.034,106.043,75.474,120.013,94.982,168.983,112.954,120.12,128.027,122.973,88.891,139.51,140.005,120.12,71.105,125.982,122.041,147.589,95.799,144.994,100.055,124.015,120.019,146.015,77.599,98.994,156.081,171.447,121.91,98.743,132.971,142.037,128.1,90.048,149.982,171.972,101.956,159.801,128.1,124.08,105.977,104.994,119.985,145.104,183.586,105.024,171.017,124.981,104.994,151.995,89.96,117.987,82.014,140.115,104.982,117.817,120.042,99.948,123.04,136.041,127.967,90.429,102.035,129.989,132.022,130.002,113.957,124.98,136.065,159.995,125.888,139.952,144.044,158.373,150.001,104,171.972,174.947,120.013,137.915,129.98,149.962,145.062,129.834,125.982,130.019,98.078,123.935,76.976,125.982,167.089,128.066,104,105.054,134.956,127.967,110.567,119.049,103.242,180.084,105.979,81.186,144.026,105.031,110.019,115.024,110.077,119.974,92.115,110.026,134.754,90.033,179,164.074,139.083,126.081,132.031,128.015,99.987,119.966,137.024,121.836,126.803,97.671,83.758,107.964,144.902,106.02,157.892,147.023,124.045,99.998,78.055,132.582,125.83,126,90.051,126.421,153.905,101.998,120.019,160.004,142.037,104,159.999,127.972,137.959,106.025,129.933,183.586,129.972,141.033,101.944,121.91,144.899,128.136,153.905,95.965,115.021,199.559,123.935,112.022,149.987,122.041,179.974,127.014,109.891,127.994,108.985,114.979,129.038,97.986,104.977,125.957,174.088,124.045,75.025,105.046,100.997,128.052,136.97,117.948,110.949,179.87,109.986,135.835,105.046,94.103,95.971,80.072,171.983,132.031,95.799,89.53,78.055,150.231,149.965,124.963,124.949,109.027,125.813,72.541,129.29,109.023,95.927,99.984,109.996,146.078,81.74,110.962,93.852,79.595,153.131,163.006,128.017,79.947,110.949,89.951,119.99,94.994,102.782,80.072,150.073,183.059,105.054,140.138,124.963,119.272,148.182,120.12,90.008,113.974,127.014,96.493,137.949,87.313,133.503,124.052,158.373,94.957,123.943,113.988,128.015,185.926,121.974,90.972,153.905,119.985,136.065,140.118,149.912,91.971,92.057,100.932,122.031,124.948,96.014,169.902,127.19,125.173,91.017,115.036,139.98,128.021,139.952,85.993,126.803,146.015,128.066,136.041,81.996,167.892,91.003,100.018,100.015,140.048,75.801,117.817,84.98,121.91,141.033,90.429,144.026,130.03,124.948,110.905,79.947,183.586,140.033,92.977,98.743,150.965,125.074,93.852,138.065,76.99,179,138.059,192.037,140.138,144.994,99.048,148.114,120.998,123.926,129.971,92.977,123.941,104.966,103.007,101.944,145.976,119.812,93.016,101.944,120.006,105.989,105.989,76.972,104.966,128.977,125.054,99.999,148.114,129.972,108.01,91.971,110.026,120.117,156.081,92.389,105.143,124.052,129.943,139.919,143.982,119.974,145.104,116.971,124.048,153.051,101.085,140.033,88.891,139.864,133.929,146.943,109.027,139.982,169.654,171.447,123.942,100.015,113.039,124.052,127.972,125.963,197.722,136.041,93.021,144.796,109.986,122.012,93.852,153.131,89.95,100.018,116.967,125.021,104.993,120.077,109.027,171.132,110.007,119.974,119.099,94.021,93.852,105.979,127.087,88.033,180.051,149.965,92.115,89.991,147.915],"marker":{"color":"#12CBC4","line":{"color":"rgba(31,119,180,1)"}},"name":"tempo","type":"histogram","error_y":{"color":"rgba(31,119,180,1)"},"error_x":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
<script type="application/htmlwidget-sizing" data-for="htmlwidget-02539920c9d6553ff78b">{"viewer":{"width":"100%","height":400,"padding":15,"fill":true},"browser":{"width":"100%","height":400,"padding":40,"fill":true}}</script>
</body>
</html>


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/elguel/elguelvizspotify.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
