---
title: "NRDG - Research"
layout: textlay
excerpt: "NRDG -- Research"
sitemap: false
permalink: /research/
---

# Research

The brain is a tremendously complex system. In order to understand it we are going to need large amounts of data from many different kinds of measurements. We use data science methods to integrate the information provided by these measurements into a coherent picture. In particular, we develop statistical analysis techniques to decipher the role of networks of brain areas in complex behaviors and in brain disorders. We implement these techniques in robust, efficient, and openly-available computer software.

## Human Connectomics

White matter connections between brain regions form a network that integrates information across the brain, comprising approximately 45% of the total cortical volume. Diffusion MRI (dMRI) is a technique that non-invasively measures properties of the white matter, assessing individual differences in the properties of the major tracts. We develop computational tools for analysis of dMRI data () statistical methods for analysis of dMRI data that have the power of machine learning, but the interpretability of traditional statistical methods. To do this I use the fact that we can consider each white matter tract as an individual statistical entity, combining information across tracts in a hierarchical fashion. This approach proves to be as powerful as machine learning methods, accurately detecting brain differences in patients with brain disorders or predicting the age of subjects based only on their dMRI data (Richie-Halford et al., 2020). But, equally importantly, the results of these methods are readily interpretable, identifying the specific tracts involved. Current and future work focuses on interpreting deep learning results based on similar principles in large clinical datasets (Mehta et al., 2020).

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.connectomics == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Vision science

{% for publi in site.data.publist %}
  {% if publi.vision == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Cloud-enabled data-driven discovery

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.cloud == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Statistical computing

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.stats == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Data science education and practice

{% for publi in site.data.publist %}
  {% if publi.datasci == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}



<!-- This is how/where to put in images>
<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_real.jpg){: style="width: 300px; float: right; border: 10px"}-->
