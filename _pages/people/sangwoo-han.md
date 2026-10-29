---
layout: member
id: sangwoo-han
title: "Sangwoo Han"
permalink: /people/sangwoo-han/
photo: sangwoo-han.png
short_description: "Seismologist - Multi-hazard, multi-sensor monitoring at Mount Rainier"
email: sangwooh@uw.edu
website: https://seismic-wave-han.github.io
scholar: https://scholar.google.com/citations?user=--qiqDYAAAAJ
orcid: https://orcid.org/0000-0001-5832-7127
github: https://github.com/Seismic-wave-Han
---

<div style="display: flex; align-items: center; gap: 2rem;flex-wrap: wrap;">
<img src="{{ site.baseurl }}/images/teampic/{{ page.photo }}" class="rounded-circle" style="width:160px;height:160px;object-fit:cover;border:3px solid #eee;" alt="{{ page.title }}">
<div>
<h2 style="margin-bottom:0.5rem;">{{ page.title }}</h2>
<span style="font-size:1.1rem; color:#555;">{{ page.short_description }}</span><br>
{% assign member = site.data.team_members | where: "id", page.id | first %}
<span style="font-size:1rem; color:#888;">{{ member.role }}</span>
<div style="margin-top:1rem;">
{% if page.website %}<a href="{{ page.website }}" target="_blank" title="Website">🌐</a>{% endif %}
{% if page.scholar %}<a href="{{ page.scholar }}" target="_blank" title="Google Scholar">{{ site.scholar_icon | raw }}</a>{% endif %}
{% if page.orcid %}<a href="{{ page.orcid }}" target="_blank" title="ORCID">{{ site.orcid_icon | raw }}</a>{% endif %}
{% if page.github %}<a href="{{ page.github }}" target="_blank" title="GitHub">{{ site.github_icon | raw }}</a>{% endif %}
{% if page.linkedin %}<a href="{{ page.linkedin }}" target="_blank" title="LinkedIn">{{ site.linkedin_icon | raw }}</a>{% endif %}
{% if page.email %}<a href="mailto:{{ page.email }}" title="Email">✉️</a>{% endif %}
{% if page.cv %}<a href="{{ page.cv }}" target="_blank" title="Download CV" class="btn btn-sm btn-default" style="margin-left: 0.5rem;">📄 Download CV</a>{% endif %}
</div>
</div>
</div>

---

## About
I am a seismologist and a postdoctoral researcher at the University of Washington, working with Marine Denolle and Paul Bodin on multi-hazard, multi-sensor monitoring at Mount Rainier. I received my Ph.D. in Seismology and Geophysics from Seoul National University in 2026.

My research uses dense seismic arrays and distributed acoustic sensing (DAS) to resolve fault structure and earthquake rupture complexity at sub-kilometer scales.

## Research Interests
- Rupture processes and source complexity of small earthquakes
- Distributed acoustic sensing and dense nodal / broadband arrays
- Focal mechanisms from S-wave polarization and stress inversion
- Microearthquake detection and location
- Multi-sensor hazard monitoring at Mount Rainier

## Education
- Ph.D. in Seismology and Geophysics - Seoul National University, Korea, 2026
- B.S. in Earth and Environmental Sciences; B.S. in Computational Sciences - Seoul National University, Korea, 2021

## Selected Publications
- Han, S. & Kim, Y. "Determining small earthquake focal mechanisms using 360° S-wave polarization: Insights from dense seismic arrays." *Geophysical Journal International*, 2026. [doi:10.1093/gji/ggaf530](https://doi.org/10.1093/gji/ggaf530)
- Han, S. et al. "Rupture model of the 5 April 2024 Tewksbury, New Jersey, earthquake based on regional Lg-wave data." *The Seismic Record*, 2024. [doi:10.1785/0320240020](https://doi.org/10.1785/0320240020)
- Han, S. et al. "Resolving multi-stage rupture process of the 2021 M<sub>w</sub> 4.9 offshore Jeju Island earthquake from relative source time functions." *Geophysical Research Letters*, 2024. [doi:10.1029/2023GL106059](https://doi.org/10.1029/2023GL106059)
