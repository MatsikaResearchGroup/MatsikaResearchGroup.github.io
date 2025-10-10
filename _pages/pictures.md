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

  <!-- First row: 3 images -->
  <tr>
    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/MolEx.png"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px;
                    box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Maneesh attended Molecular Excited States Workshop(MolEx) 2025 at Toru&#324;, Poland</div>
      </div>
    </td>
    
    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Sanibel.png"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px;
                    box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">
          Maneesh and Dakshitha attended 64th Sanibel Symposium at St. Augustine Beach, Florida
        </div>
      </div>
    </td>

    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/md_diss.jpeg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px;
                    box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Mohammed's thesis defense 2023</div>
      </div>
    </td>    
  </tr>

  <!-- Second row: 3 images -->
  <tr>
    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/urp23.jpeg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px;
                    box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">
          Undergraduate research program poster presentation (CST) 2023
        </div>
      </div>
    </td>
    
    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/spokane.jpeg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px;
                    box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">
          Vaibhav and Daksh attended APS DAMOP Conference at Spokane, WA 2023
        </div>
      </div>
    </td>

    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/urpposterpres.png"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px;
                    box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">
          Undergraduate research program poster presentation (CST) 2021
        </div>
      </div>
    </td>
  </tr>

<!-- Second row: 3 images -->
  <tr>
     <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/utah.jpg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Mushir attended a workshop on Quantum Methods in Molecular and Solid-State Theory 2019 at Utah</div>
      </div>
    </td>
    
    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/collage-pratip.jpg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Pratip attended 10th Congress of the International Society of Theoretical Chemical Physics 2019, Troms<span>&#248;</span>, Norway </div>
      </div>
    </td>

    <td style="width:33%; padding:8px; vertical-align:top;">
      <div style="display:inline-block;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/phillycollage.jpg"
             style="width:90%; height:200px; object-fit:cover; border-radius:6px; box-shadow:0 2px 6px rgba(0,0,0,0.2); margin-bottom:6px;">
        <div style="font-size:0.85em; color:#333;">Philadelphia, city of Brotherly Love</div>
      </div>
    </td>
  </tr>
</table>

