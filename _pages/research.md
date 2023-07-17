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

White matter connections between brain regions form a network that integrates information across the brain, comprising approximately 45% of the total cortical volume. Diffusion MRI (dMRI) is a technique that non-invasively measures properties of the white matter, assessing individual differences in the properties of the major tracts. We develop computational tools for analysis of dMRI data, and apply these tools in large-scale datasets of human neuroimaging data to understand the brain and the complex relationships between the properties of brain networks, complex behavior and brain health.

### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.connectomics == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Vision science

We work on modeling and analysis of the biology of the early visual system. In some projects, we created phenomenological models of
retinal processing, that simulate prosthetic vision. These models, implemented in software are useful for assessing the utility
of these devices and as tools for designing new devices and stimulation protocols. In other projects, we analyze data about
retinal health from large-scale databases. We are also interested to understand how the biology of networks in the early visual
system evolves over time, and in response to disease.

{% for publi in site.data.publist %}
  {% if publi.vision == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Cloud-enabled data-driven discovery

Progress in understanding the brain depends on sophisticated analysis of massive neuroscience datasets. This requires the adoption of data science technologies that are emerging in industry, such as cloud computing. One of the objectives of our work is to reduce the barriers to wider adoption of these technologies. We are exploring multiple aspects of cloud computing. This includes development of software for deployment of computations to cloud systems, as well as work on web-based tools for data visualization and apps for citizen science.


### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.cloud == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


### Tools and publications:

{% for publi in site.data.publist %}
  {% if publi.stats == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}


## Data science

As we apply tools from statistical learning to problems in neuroscience, we also end up developing general purpose
open-source statistical computing tools. Our group is also involved in a variety of ways in data science education and training.

{% for publi in site.data.publist %}
  {% if publi.datasci == 1 %}

  {{ publi.title }} <br />
    <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

{% endfor %}



<!-- This is how/where to put in images>
<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/layers_real.jpg){: style="width: 300px; float: right; border: 10px"}-->
