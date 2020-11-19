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

White matter connections between brain regions form a network that integrates information across the brain, comprising approximately 45% of the total cortical volume. Diffusion MRI (dMRI) is a technique that non-invasively measures properties of the white matter, assessing individual differences in the properties of the major tracts. We develop computational tools for analysis of dMRI data. Together with [Jason Yeatman's group at Stanford](https://www.brainandeducation.com/) and [Noah Simon](https://faculty.washington.edu/nrsimon/) in the Department of Biostatistics, we established [DIRECT (Data Intensive Research in Connectomics)](https://autofq.org/), a research collaboration focused on use of large-scale datasets of human neuroimaging data to understand the brain and the complex relationships between the properties of brain networks, complex behavior and brain health.

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.connectomics == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Vision science

The human visual system is

{% for publi in site.data.publist %}
  {% if publi.vision == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Cloud-enabled data-driven discovery

Progress in understanding the brain depends on sophisticated analysis of massive neuroscience datasets. This requires the adoption of data science technologies that are emerging in industry, such as cloud computing. One of the objectives of our work is to reduce the barriers to wider adoption of these technologies. We are exploring multiple aspects of cloud computing. This includes development of software for deployment of computations to cloud systems, as well as work on web-based tools for data visualization and apps for citizen science. Together with [Beth Buffalo](https://buffalomemorylab.com/) and [Adrienne Fairhall](https://fairhalllab.com/) in the Department of Physiology and Biophysics, and in collaboration with the [Jupyter](https://jupyter.org/) team, we established a cloud-based platform for interactive computing in multi-electrode recordings from human and non-human primate brain.


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
