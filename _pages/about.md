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

I am currently working as Postdoctoral Researcher at Peking University with Prof. [Yizhou Wang](https://cfcs.pku.edu.cn/wangyizhou/#../../../english/index.htm).
Before that, I received Ph.D in Data Science from Academy for Advanced Interdisciplinary Studies, Peking University, supervised by Prof. [Yizhou Wang](https://cfcs.pku.edu.cn/wangyizhou/#../../../english/index.htm).

My research interests lie in the area of artificial intelligence for medical image diagnosis. My research goal is to design cognitive-inspired medical image diagnostics algorithms, including clinical prior modeling and causal inference and develop efficient, effective, truthful, and robust AI-assistant medical image diagnostics systems. **A key aspect of my research methodology is my dedication to understanding and addressing clinicians’ practical needs. I allocate at least 20% of my time to engaging with clinical practitioners, ensuring my work is grounded in real-clinical challenges and informed by frontline insights.** This collaboration helps bridge the gap between advanced AI techniques and clinical practice, ensuring the AI systems I develop are sensitive to medical diagnostics’ nuances and seamlessly integrate into clinical workflows to enhance healthcare professionals’ capabilities and ultimately benefit patient care. 

I have developed two Breast Imaging Diagnostic Systems, including Intelligent Breast MRI Diagnosis System and Intelligent Mammography X-ray Diagnosis System, which improve the diagnostic accuracy, robustness and efficiency. These systems have been widely deployed in hundreds of hospitals in China and served over a million clinical diagnostic cases.


{% include_relative includes/news.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/honers.md %}

{% include_relative includes/others.md %}
