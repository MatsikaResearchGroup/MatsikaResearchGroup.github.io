---
title: "Matsika Lab - Pictures"
layout: piclay
excerpt: "Matsika Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [Temple](#temple), [Philadelphia](#philadelphia)


## Temple

#### Current Group: Spring 2020
<!--<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>-->

<figure>
  <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/group photo" width="60%" class="imagesize img-responsive center-block" />
  <figcaption> (from left to right) Vince, Cate, Spiridoula, Mohammed, Pratip, Cam, Mushir, Vaibhav, Salsabil and Drew.
  </figcaption>
</figure>

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Philadelphia
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/phillycollage.jpg" width="60%" >
</figure>

### Pratip's visit to Troms<span>&#248;</span>, Norway 
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/collage-pratip.jpg" width="40%">
<figcaption> <a href="http://www.istcp-2019.org/">10th Congress of the International Society of Theoretical Chemical Physics 2019</a>
</figcaption>
</figure>

### Mushir's visit to Park City, Utah 
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/utah.jpg" width="30%">
<figcaption> <a href="https://utahworkshop2019.com/index.htm">The Utah Workshop on Quantum Methods in Molecular and Solid-State Theory, September 22-27, 2019</a>
</figcaption>
</figure>

<!--## Cornell
From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>-->

<!--## St Andrews
From the [group of Felix Baumberger](http://dqmp.unige.ch/baumberger/) (now at University of Geneva).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">
</figure>-->
