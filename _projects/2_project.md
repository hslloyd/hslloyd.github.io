---
layout: page
title: Graph Comprehension Benchmarking
description: A research project investigating what graph comprehension is and how do you measure it?
img: assets/img/3.jpg
importance: 2
category: work
---

## Interactive Plots

You can add interative plots using plotly + iframes :framed_picture:

<!--<div class="l-page">
style="border: 1px dashed grey;"
-->
<div class="l-page">
  <iframe src="{{ '/assets/plotly/gcb_cogsci_outline_old.html' | relative_url }}" frameborder='0' scrolling='yes' height="1000px" width="100%" ></iframe>
</div>

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
