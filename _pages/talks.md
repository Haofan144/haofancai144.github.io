---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

- ChopTags: An Accurate and Low-cost Interface to Identify User/Item Interac-
tions 
    - **IEEE SECON** virtual conference, Sept. 2022

- Enabling identity-aware tracking by vision-RFID fusion
    - **ACM SenSys** virtual conference, Nov. 2020

- When Tags ’Read’ Each Other: Enabling Low-cost and Convenient Tag Mutual
Identification
    - **IEEE ICNP** conference, Chicago, USA, Oct. 2019

- A (Near) Zero-cost and Universal Method to Combat Multipaths for RFID Sens-
ing
    - **IEEE ICNP** conference, Chicago, USA, Oct. 2019

- Multi-seller Combinatorial Spectrum Auction with Reserve Prices
    - **IEEE ICCS** conference, Shenzhen, China, Dec. 2016

- Spectrum Matching
    - **IEEE ICDCS** conference, Nara, Japan, Jun. 2016
