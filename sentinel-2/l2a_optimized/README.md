---
permalink: /sentinel-2/l2a_optimized/
nav_exclude: true
---

# Sentinel-2 L2A True Color Optimized
{% assign paths = page.dir | remove_first: "/" | split: "/" | join: "-"%}
<button class="btn btn-primary" id="toggle-script" onclick="toggleScript()">Show Script</button>
[Download Script](script.js){: .btn target="_blank" download="{{paths | append: ".js"}}"}
{: .mt-lg-4 }

<div id="script" style="display:none;"> 
{% highlight javascript %}
{% include_relative script.js %}
{% endhighlight %}
</div>

## Evaluate and visualize

- [EO Browser](https://sentinelshare.page.link/VdxC){:target="_blank"}   

## Description

True color composite uses visible light bands red, green and blue in the corresponding red, green and blue color channels, resulting in a natural colored product, that is a good representation of the Earth as humans would see it naturally. This visualization uses highlight compression to ensure no maxing-out of clouds or snow, uses sRGB encoding for no extra darkening of shadows and adds a small amount of saturation boost.

## Description of representative images

Optimized True Color image of Rome. Acquired on 2023-01-30, processed by Sentinel Hub. 

![S2-L2A True Color Optimized](fig/fig1.png)