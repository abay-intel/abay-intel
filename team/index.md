---
title: Team
nav:
  order: 3
  tooltip: Our core technical team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The core technical team is established by Bahir Dar University and led by the Blue Nile Water Institute (BNWI).
It brings together hydrogeology, water resources, GeoAI, remote sensing, machine learning, and software engineering expertise.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}
