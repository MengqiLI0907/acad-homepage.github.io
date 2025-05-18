---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a master's student in Geographic Information Science at the University of Zurich and an incoming PhD student at the University at Buffalo. My research focuses on urban mobility resilience, disaster response, and spatial modeling. My recent thesis develops a framework to quantify how transportation diversity enhances human mobility resilience during Hurricane Ida in New York City. I use deep learning for baseline construction, resilience metrics, and spatial econometrics including MGWR.

I also worked on DEM reconstruction from terrain features using GANs, dengue-meteorology modeling, and urban building growth analysis with Planet imagery.

My research combines GIS, machine learning, and remote sensing to tackle real-world urban and environmental problems.

You can also use the Google Scholar badge:  
<a href='https://scholar.google.com/citations?user=9lpYrDkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2025.04*: 🎓 Thesis submitted to *Computers, Environment and Urban Systems*
- *2024.11*: 🛰 Presented DEM research at AAG 2024, Honolulu
- *2023.10*: 💻 Joined ETH Zurich project on urban 3D building modeling with PlanetScope

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CEUS (Submitted)</div><img src='/assets/images/framework_fit.png' alt="ida resilience" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quantifying the Impact of Transportation Diversity on Urban Mobility Resilience during Hurricane Ida](https://example.com)

**Mengqi Li**, Cheng Fu, Robert Weibel

[**Project**](https://example.com/project-ida) <strong><span class='show_paper_citations' data='9lpYrDkAAAAJ:YsMSGLbcyi4C'></span></strong>  
- Built dynamic baselines with Prophet forecasting to detect disruptions in subway, taxi, and bikeshare data  
- Introduced resilience metrics (RL, RT, MDEV) to quantify mobility performance loss  
- Applied MGWR and spatial econometrics to uncover socio-infrastructure influences  
- Submitted to *Computers, Environment and Urban Systems* in April 2025

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJAEOG 2024</div><img src='/images/dem-gan.png' alt="dem gan" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reconstructing High-Resolution DEMs from 3D Terrain Features using Conditional GANs](https://doi.org/10.1016/j.jag.2024.104115)

**Mengqi Li**, Wei Dai, et al.

[**Project**](https://example.com/dem-cgan) <strong><span class='show_paper_citations' data='9lpYrDkAAAAJ:RHpTSmoSYBkC'></span></strong>  
- Proposed a CGAN-based model to reconstruct DEMs from ridges, valleys, and contour masks  
- Achieved 30% RMSE reduction over baseline interpolation  
- Published in *International Journal of Applied Earth Observation and Geoinformation*

</div>
</div>

- [Check Dam Detection using Deep Learning and Hydrologic Constraints](https://doi.org/10.3390/ijerph20054636), Dai, **Li**, *IJERPH*, 2023  
- [Topographic Skeletons for Deep Terrain Learning](https://doi.org/10.3390/rs15184490), Chen, Dai, **Li**, *Remote Sensing*, 2023  
- [Dengue–Meteorology Associations in SEA](https://www.medrxiv.org/content/10.1101/2023.12.01.23299190v1), *medRxiv*, 2023  

# 🎖 Honors and Awards
- *2023.06* Outstanding Graduate, NUIST  
- *2022.10* First-Class Scholarship, UZH  
- *2021.11* Esri Cup – Silver Award (National GIS Competition)  
- *2021.08* National GIS Skills Contest – Top Prize  

# 📖 Educations
- *2023.09 – 2025.07*, MSc in Geographic Information Science, University of Zurich  
- *2019.09 – 2023.06*, BSc in Geographic Information Science, NUIST  

# 💬 Invited Talks
- *2024.11*, “Terrain Reconstruction with CGANs,” AAG 2024, Honolulu  
- *2023.10*, GIS Day, UZH Department of Geography  

# 💻 Internships
- *2022.06 – 2022.09*, ETH Zurich, Remote Sensing RA  
- *2021.06 – 2021.09*, Esri China, GIS Developer Intern
