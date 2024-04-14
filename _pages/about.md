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

# 🎓 About Me

I am a senior undergraduate student at <a href="https://www.wyc.tsinghua.edu.cn/">Weiyang College</a> in <a href="https://www.tsinghua.edu.cn/en/">Tsinghua University</a>, double majoring in Mathematics & Physics and Civil Engineering and Systems.
I have skills in Transportation, System Engineering, and Statistics. My research interests focus on transit policy, traffic modeling and planning, and human-machine interface on vehicles. My research goal is to elevate awareness about the transformative power of transportation in fostering societal connectivity and equity.

**I'm seeking a Graduate Program in Transportation and Operation Research for Fall 2024! 🚗🚌🚇🚆🚝🚄✈️**

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 News
- *2023.11*: &nbsp;🎉🎉 Under the scientific research results of Tsinghua-Daimler Joint Research Center, <a href="https://www.mercedes-benz.com.cn/mmc/index/ota.html">Mercedes-Benz push OTA upgrade of *AMap Navigator* for first-generation MBUX in-vehicle HMI for China Market</a>.
- *2023.09*:  I 🛫flew across the Pacific🛬 <a href="https://mp.weixin.qq.com/s/fjBcpLnuZsnXih_at59gQg">only on Boeing 737</a>!

# 📖 Educations
- *2020.09 - 2024.06 (expected)*, Bachelor of Science in Mathematics & Physics, Weiyang College, Tsinghua University, Beijing, China. 
- *2020.09 - 2024.06 (expected)*, Bachelor of Engineering in Civil Engineering and Systems, Weiyang College, Tsinghua University, Beijing, China.
- *2014.09 - 2020.07*, Chongqing Naikai Secondary School, Chongqing, China

# 📝 Publications 

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**-->

- Y.S. Lian, K. Zhang, X. Lin, Dinghan Liu and S. Li, Design and Evaluation of an In-vehicle Longitudinal Trajectory Guidance System Considering Road Emergency Events, **Transportation Research Part F: Traffic Psychology and Behaviour**, 2023 <span style="color: #eeeeee; font-size: 10px;">(Being Submitted)</span>
- H. Xu, Dinghan Liu, et al., Bridge damping formula based on the correlation between the front and rear contact responses of a two-axle scanning vehicle, **International Journal of Structural Stability and Dynamics**, 2023
- Y.B. Yang, L. Chen, Dinghan Liu, et al., Cancellation of Resonance for Elastically Supported Beams Subjected to Successive Moving Loads: Optimal Design Condition for Bridges, **Engineering Structures**, 2023 <span style="color: #eeeeee; font-size: 10px;">(Being Submitted)</span>

<!--
- Dinghan Liu, et al., Passenger Payment Behavior Analysis of Multimodal Mobility in MaaS Based on Logit Model, **Transportation Research Part A: Policy and Practice**, 2024 <span style="color: #eeeeee; font-size: 10px;">(Being Submitted)</span> -->

# 🏆 Honors and Awards 
- *2023.10*:&nbsp; 🏅Scholarship for Overall Excellence, Tsinghua University.
- *2023.10*:&nbsp; 🏅Scholarship for Social Work Leadership, Tsinghua University.
- *2023.06*:&nbsp; 🏅Undergraduate Overseas Research Grant, Tsinghua University, Tsinghua University.
- *2023.05*:&nbsp; 🥈2nd Prize, Challenge Cup National Undergraduate Academic Science and Technology Race, Tsinghua University.
- *2022.10*:&nbsp; 🏅Scholarship for Overall Excellence, Tsinghua University.
- *2022.10*:&nbsp; 🏅Scholarship for Volunteer Charity, Tsinghua University.
- *2021.10*:&nbsp; 🏅Scholarship for Overall Excellence, Tsinghua University.
- *2021.10*:&nbsp; 🏅Scholarship for Social Work Leadership, Tsinghua University.
- *2018.12*:&nbsp; 🥉3rd Prize, S.-T. Yau High School Science Award, Tsinghua University

# 💻 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Commercial Research</div><img src='images/trajectory.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
## <span style="color: #244D8E;">Traffic Safety Evaluation Using Surrogate Satefy Measures in Intersections</span>

Supervised by Prof. Meng Li at Tsinghua-Daimler Joint Research Center    <span style="color: #aaaaaa; font-size: 12px;">*2023.2 - 2023.12*</span>

<span style="color: #00369F">**Methodology** 
- Conducted exploratory analysis of intersection traffic participant trajectory data by XGBoost Classifier;
- Established a set of non-motorized red-light running behaviors based on the PCA Model.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge1">Submitted</div><img src='images/hmi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
## [Exclusive Longitudinal Speed Guidance: A Driving Simulator Study](Trajectory.pdf)

Supervised by Prof. Meng Li at Tsinghua-Daimler Joint Research Center    <span style="color: #aaaaaa; font-size: 12px;">*2022.10 - 2023.1*</span>

<span style="color: #00369F">**Methodology** 
- Designed a speed guidance system, including a virtual block-based spatial-temporal speed guidance method and HMI of speed guidance device;
- Carry out psychological experiments, calculated and analyzed NASA-TLX data, driving simulator’s data, and eye-tracking data using ANOVA.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge1">Submitted</div><img src='images/maas.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## <span style="color: #244D8E;">A Logit Model-Based Study of Pricing Systems in Mobility as a Service (MaaS)</span>
<!--## [A Logit Model-Based Study of Pricing Systems in Mobility as a Service (MaaS)](MaaS.pdf)-->

Supervised by Prof. Ruimin Li in the Department of Civil Engineering, Tsinghua University    <span style="color: #aaaaaa; font-size: 12px;">*2022.5 - 2022.12*</span>

<span style="color: #00369F">**Methodology** 
- Proposed and discussed a new pricing method of MaaS in Kunshan;
- Utilize a multinomial Logit model to analyze the payment behavior preferences of passengers in multimodal transportation within MaaS.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge2">Published</div><img src='images/bridge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
## [Retrieving Frequencies and Damping Ratios of Steel Bridges](Bridge.pdf)

Supervised by Prof. Yongbin Yang    <span style="color: #aaaaaa; font-size: 12px;">*2022.11 - 2023.2*</span>

<span style="color: #00369F">**Methodology** 
- Put up with retrieving frequencies and damping ratios of steel bridges from the contact responses of a two-axle scanning vehicle;
- Carry out a two-axle moving test vehicle equipped with laser sensors.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge1">Submitted</div><img src='images/cancel.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
## [A Dynamic Load Analysis on Elastic-Support Railway Bridges](Cancellation.pdf)

Supervised by Prof. Yongbin Yang    <span style="color: #aaaaaa; font-size: 12px;">*2023.5 - 2023.10*</span>

<span style="color: #00369F">**Methodology** 
- Analyze the dynamic behavior of railway bridges with elastic supports under moving train loads;
- Derive resonance and cancellation conditions for these bridges and establish optimal design criteria.
</div>
</div>
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge2">Selected Project</div><img src='images/gts.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
## [Design of Public Transport System in Changzhi City](GTS.pdf)

Supervised by Prof. Yongbin Yang    <span style="color: #aaaaaa; font-size: 12px;">*2023.2 - 2023.5*</span>

<span style="color: #00369F">**Methodology** 
- Designing a public transportation system for Changzhi City, integrating insights from traffic demand data and zone locations；
- Developing a model that combines a grid structure in the city center with a hub-and-spoke pattern in peripheral areas, optimizing bus line spacing and layout；
- Proposing solutions for enhancing public transportation efficiency, including the design of specialized routes based on demand analysis.
</div>
</div>
