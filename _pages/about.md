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
{% else  %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I graduated from the University of Electronic Science and Technology of China (UESTC) with a Bachelor of Engineering in Spatial Informatics and Digitalized Technology. After that, I joined the [Energy and Environment Group (EEG)](https://www.cst.cam.ac.uk/research/eeg) in the Department of Computer Science and Technology, University of Cambridge, as an Undergraduate Research Assistant under the supervision of my advisor, [Srinivasan Keshav](https://svr-sk818-web.cl.cam.ac.uk/keshav/wiki/index.php/Main_Page). Now, I am a PhD student under his supervision.

My research interest lies at the intersection of AI and Earth Science. I am particularly interested in developing Self-Supervised Learning (SSL) algorithms for remote sensing imagery.

I am also the co-founder and president of the [China Artificial Intelligence Association (Cambridge)](https://www.cambridgesu.co.uk/organisation/26373/). We are dedicated to creating a platform for AI communication that integrates academia and industry, connecting universities in China and the UK to build a cross-national AI talent ecosystem. 

My main work at present is developing a remote sensing foundation model called [TESSERA](https://github.com/ucam-eo/tessera). We have found some exciting results. We were recently recruiting for an [RA position](https://www.jobs.cam.ac.uk/job/51742/) to create a global habitat map using TESSERA. (The position has been filled, but we welcome any informal chat at zf281@cam.ac.uk if you are interested). 

We are also currently recruiting a **Postdoctoral Research Associate** to join our team! The position will use TESSERA to track biodiversity, carbon storage and woodland regeneration at scale, directly informing real-world nature recovery in the UK. Ideal candidates should have (or be finishing) a PhD in land use, ecosystems or environmental science, work confidently with geospatial data and code, and be excited by AI and nature-based solutions. [Apply here](https://www.cam.ac.uk/jobs/research-assistant-research-associate-fixed-term-pd48274) (Closing date: 12 January 2026).

We would like to express our gratitude to [DAWN](https://www.hpc.cam.ac.uk/d-w-n), the fastest artificial intelligence supercomputer at Cambridge, for their generous support in this project. We also acknowledge the support from [AMD](https://www.amd.com/en.html), [Vultr](https://www.vultr.com/), [Microsoft AI For Good Lab](https://www.microsoft.com/en-us/research/group/ai-for-good-research-lab/), [dClimate](https://www.dclimate.net/), and [Amazon Web Services (AWS)](https://aws.amazon.com/). This work would not have been possible without their computational resources and technical assistance.


# 🔥 News
- *2026.02*:  🎉🎉 Our TESSERA paper was accepted by CVPR 2026.
- *2026.01*:  🎉🎉 I was honored to be invited to the [AI for Good Global Summit](https://aiforgood.itu.int/summit26/) (to be held in Geneva, Switzerland, in July 2026), where I will present TESSERA-related works.
- *2025.12*:  🎉🎉 I was honored to be invited by IEEE GRSS to give a talk about TESSERA. Information and recording can be found [here](https://www.grss-ieee.org/event/tessera-precomputed-fair-global-pixel-embeddings-for-earth-representation-and-analysis/).
- *2025.11*:  🎉🎉 I was invited as a keynote speaker to the Open-Earth-Monitor Global Workshop 2026, which will be held in Barcelona, Spain, from 7–9 October 2026. The event is co-hosted by CREAF and the OpenGeoHub Foundation under the Open-Earth-Monitor-Cyberinfrastructure (OEMC) project.
- *2025.09*:  🎉🎉 I was honored to participate in the 13th Heidelberg Laureate Forum as a young researcher and presented the TESSERA work ([Heidelberg Laureate Forum](https://www.heidelberg-laureate-forum.org/)).
- *2025.07*:  🎉🎉 We have open-sourced the inference code for [TESSERA](https://github.com/ucam-eo/tessera?tab=readme-ov-file) and the code for using embeddings in downstream tasks ([GeoTessera](https://github.com/ucam-eo/geotessera)). We will be rolling out a global 10m resolution annual embedding product in the coming months.
- *2025.06*:  🎉🎉 We have released the preprint of our latest work, [TESSERA](https://arxiv.org/abs/2506.20380). We trained a 14B model to extract time-series spectral features from satellite images.
- *2025.03*:  🎉🎉 Our app, GreenLens, won the [Better Future Award](https://www.cst.cam.ac.uk/using-ai-see-wood-trees) from the Cambridge Ring!
- *2025.02*:  🎉🎉 We published "SPREAD: A large-scale, high-fidelity synthetic dataset for multiple forest vision tasks" in Ecological Informatics. We used Unreal Engine 5 to create the most realistic synthetic data for 2D and 3D vision tasks in forests.
- *2024.10*:  🎉🎉 I am thrilled to be fully funded to join the EEG, Department of Computer Science and Technology, University of Cambridge, as a PhD student.
- *2024.09*:  🎉🎉 "An app for tree trunk diameter estimation from coarse optical depth maps," was accepted by Ecological Informatics.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/tessera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TESSERA: Temporal Embeddings of Surface Spectra for Earth Representation and Analysis](https://arxiv.org/abs/2506.20380)

[[**Tessera**]](https://github.com/ucam-eo/tessera)![](https://img.shields.io/github/stars/ucam-eo/tessera?style=social)&nbsp;&nbsp;&nbsp;[[**GeoTessera**]](https://github.com/ucam-eo/geotessera)![](https://img.shields.io/github/stars/ucam-eo/geotessera?style=social)&nbsp;&nbsp;&nbsp;![PyPiVersion](https://img.shields.io/pypi/v/geotessera?label=PyPI%20version&color=blue)&nbsp;&nbsp;&nbsp;![License](https://img.shields.io/badge/License-MIT-blue.svg)

**Zhengpeng Feng**, Clement Atzberger, Sadiq Jaffer, Jovana Knezevic, Silja Sormunen, Robin Young, Madeline C. Lisaius, Markus Immitzer, Toby Jackson, James Ball, David A. Coomes, Anil Madhavapeddy, Andrew Blake, Srinivasan Keshav

- We trained a 1.4B model to extract time-series spectral features from satellite images.
- We are releasing 2.5PB of global 10m-resolution earth embeddings from 2017-2025.
- Researchers from over 50 groups worldwide are using TESSERA.
- Accepted by CVPR 2026.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review (RSE)</div><img src='images/tessera.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Applications of the TESSERA Geospatial Foundation Model to Diverse Environmental Mapping Tasks

**Zhengpeng Feng**, Clement Atzberger, Sadiq Jaffer, Jovana Knezevic, Silja Sormunen, Robin Young, Madeline C. Lisaius, Markus Immitzer, Toby Jackson, James Ball, David A. Coomes, Anil Madhavapeddy, Andrew Blake, Srinivasan Keshav

- Under review at Remote Sensing of Environment (RSE).
- Extension of the CVPR 2026 TESSERA paper with additional downstream tasks and more detailed analysis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ecological Informatics 2025</div><img src='images/spread.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SPREAD: A large-scale, high-fidelity synthetic dataset for multiple forest vision tasks](https://www.sciencedirect.com/science/article/pii/S1574954125000949)

[[**Code**]](https://github.com/FrankFeng-23/SPREAD) ![](https://img.shields.io/github/stars/FrankFeng-23/SPREAD?style=social)&nbsp;&nbsp;&nbsp;![License](https://img.shields.io/badge/License-MIT-blue.svg)

**Zhengpeng Feng**, Yihang She, Srinivasan Keshav

- We used Unreal Engine 5 to create the super realistic synthetic data for 2D and 3D vision tasks in forests.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ecological Informatics 2024</div><img src='images/greenlens.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An app for tree trunk diameter estimation from coarse optical depth maps](https://www.sciencedirect.com/science/article/pii/S1574954124003169)

[[**Code**]](https://github.com/MingyueX/GreenLens) ![](https://img.shields.io/github/stars/MingyueX/GreenLens?style=social)&nbsp;&nbsp;&nbsp;![License](https://img.shields.io/badge/License-MIT-blue.svg)&nbsp;&nbsp;&nbsp;[[**APK**]](https://drive.google.com/drive/u/0/folders/17-Yu3KXcgJiFapGc2AjJ2dHNC30YUbup)

**Zhengpeng Feng**, Mingyue Xie, Amelia Holcomb, Srinivasan Keshav

- An app for fast in-situ tree trunk diameter estimation.
- The app won the Cambridge Ring Better Future Award!
- [More](https://www.cst.cam.ac.uk/using-ai-see-wood-trees) about the app
</div>
</div>

# 🎖 Honors and Awards
- *2025.09* Heidelberg Laureate Forum Young Researcher
- *2025.03* Cambridge Ring Better Future Award
- *2024.06* Robert Sansom Studentship
- *2022.12* The Most Outstanding Students Award of UESTC (top 10)
- *2022.11* Gratitude Scholarship for Chinese Modern Scientists
- *2022.10* National Scholarship

# 📖 Educations
- *2024.10 - Present*, PhD in Computer Science, Department of Computer Science and Technology, University of Cambridge.
- *2023.07 - 2024.07*, Research Assistant, Department of Computer Science and Technology, University of Cambridge.
- *2019.09 - 2023.06*, B.Eng. in Spatial Informatics and Digitalized Technology, University of Electronic Science and Technology of China (UESTC).

# 💬 Invited Talks
- *2025.12*, TESSERA: Precomputed Fair Global Pixel Embeddings for Earth Representation and Analysis, IEEE GRSS. | [\[link\]](https://www.grss-ieee.org/event/tessera-precomputed-fair-global-pixel-embeddings-for-earth-representation-and-analysis/) 
- *2025.12*, TESSERA, RISE. | [\[video\]](https://www.youtube.com/watch?v=AQhzSBxvhVM)
- *2025.10*, TESSERA, GEDI Group, University of Maryland. | [\[link\]](https://gedi.umd.edu/mission/mission-team/)
- *2024.06*, An App for Tree Trunk Diameter Estimation from Coarse Optical Depth Maps. | [\[video\]](https://www.youtube.com/watch?v=ePLKoPkt_CA)

# 💻 Supervisions
- *2025.03 - 2025.06*, [Part IB CST Artificial Intelligence](https://www.cl.cam.ac.uk/teaching/2425/ArtInt/), University of Cambridge.
