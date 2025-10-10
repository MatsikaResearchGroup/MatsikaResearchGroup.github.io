---
title: "Matsika Lab - Pictures"
layout: piclay
excerpt: "Matsika Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [Temple](#temple), [Philadelphia](#philadelphia)


## Temple

#### Current Group: Fall 2025
<!--<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>-->

<figure>
  <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/gp.jpg" width="60%" class="imagesize img-responsive center-block" />
  <figcaption> (from left to right) Spiridoula, Trevor, Mohammed, Vaibhav, Kanishka, Juan, Sabrina, Maneesh, Dakshitha.
  </figcaption>
</figure>

#### Group Pictures
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

### Other Pictures
<table style="width:100%; text-align:center; border-collapse:collapse;">
  <tr>
    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Sanibel.png"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Maneesh and Dakshitha attended 64th Sanibel Symposium at St. Augustine Beach, Florida</div>
      </div>
    </td>

    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/md_diss.jpeg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Mohammed's thesis defense 2023</div>
      </div>
    </td>

    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/urp23.jpeg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Undergraduate research program poster presentation (CST) 2023</div>
      </div>
    </td>
  </tr>
</table>


### Vaibhav and Daksh visit to Spokane, WA 2023
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/spokane.jpeg" width="40%">
<figcaption> <a href="https://aps.org/meetings/meeting.cfm?name=DAMOP23">The APS DAMOP Conference, June 5-9, 2023</a>
</figcaption>
</figure>

### Undergraduate research program poster presentation (CST) 2021
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/urpposterpres.png" width="50%">
</figure>

### Mushir's visit to Park City, Utah 
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/utah.jpg" width="30%">
<figcaption> <a href="https://utahworkshop2019.com/index.htm">The Utah Workshop on Quantum Methods in Molecular and Solid-State Theory, September 22-27, 2019</a>
</figcaption>
</figure>

### Pratip's visit to Troms<span>&#248;</span>, Norway 
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/collage-pratip.jpg" width="40%">
<figcaption> <a href="http://www.istcp-2019.org/">10th Congress of the International Society of Theoretical Chemical Physics 2019</a>
</figcaption>
</figure>

## Philadelphia
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/phillycollage.jpg" width="60%" >
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
