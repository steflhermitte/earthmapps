---
layout: research
title: "Research"
banner_title: "Research"
subtitle: "Connecting observations, models and AI"
banner_icon: fa-map
background_image: "/images/bg_Netherlands.jpg"
# theme_class: "atacama"
permalink: "/research.html"
---

<!-- # Research

EarthMapps studies how ecosystems, water resources, glaciers, ice sheets and other climate-sensitive environments respond to environmental change. We combine Earth observation, environmental modelling and artificial intelligence to better understand the processes that shape our planet and how they may evolve. -->

{% capture environmental_change %}
Climate change affects ecosystems, biodiversity, water resources and the cryosphere in complex and interconnected ways. Understanding these interactions helps us anticipate future environmental change and assess possible responses.

EarthMapps studies how ecosystems, water resources, glaciers, ice sheets and other climate-sensitive environments respond to environmental change. We combine Earth observation, environmental modelling and artificial intelligence to better understand the processes that shape our planet and how they may evolve.

Our research covers environments ranging from drylands and forests to glaciers, ice sheets and polar regions, with applications in ecosystem restoration, biodiversity conservation, climate resilience and sea-level rise.
{% endcapture %}

{% include research-block.html
  title="Understanding environmental change"
  image="/images/bg_seaice_1500px.jpg"
  image_alt="Environmental change across a climate-sensitive landscape"
  style="style2"
  content=environmental_change
%}

{% capture earth_observation %}
Satellite observations allow environmental processes to be monitored consistently across large regions and long periods, including places where field observations are sparse.

We combine optical, thermal, radar and microwave observations with drone imagery and field measurements to study vegetation, biodiversity, water availability, snow and ice, glaciers and ice shelves.
{% endcapture %}

{% include research-block.html
  title="Earth observation"
  image="/images/bg_satellite.jpg"
  image_alt="Satellite observations of the Earth surface"
  style="style3"
  alt=true
  content=earth_observation
%}

{% capture observations_models %}
Observations tell us what is happening. Models help us examine why it is happening and what may happen next.

We connect Earth observation with climate, environmental and biophysical models. Observations help evaluate models and improve their representation of environmental processes, while models help interpret observations and place change in a broader context.
{% endcapture %}

{% include research-block.html
  title="Connecting observations and models"
  image="images/bg_satvsmodel.jpg"
  image_alt="Environmental observations connected with model simulations"
  style="style4"
  content=observations_models
%}

{% capture geoai %}
Artificial intelligence offers new ways to analyse large environmental datasets and connect observations with models. We work with deep learning, graph neural networks, generative models, causal inference, super-resolution and model emulation.

We also explore Digital Twin approaches that bring observations, models and AI together to monitor environmental systems, test scenarios and improve predictions across ecosystems, drylands and the cryosphere.
{% endcapture %}

{% include research-block.html
  title="Geospatial AI and Digital Twins"
  image="/images/bg_digitalearth.jpg"
  image_alt="Geospatial data and artificial intelligence"
  style="style5"
  alt=true
  content=geoai
%}
