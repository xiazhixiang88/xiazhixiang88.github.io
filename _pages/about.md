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

# 👨‍💻 About Me
I am a Master's student in **Applied Statistics** at **Southwestern University of Finance and Economics (SWUFE)**, supervised by Prof. Bin Liu. Previously, I obtained my B.S. degree in Statistics from Suzhou University of Science and Technology with a high GPA (88.4/100).

My research focuses on **Medical Image Analysis**, **Multi-Instance Learning (MIL)**, and **Graph Neural Networks**. I have a strong interest in developing efficient and interpretable deep learning frameworks for Whole-Slide Images (WSI) to assist in cancer prognosis and clinical decision-making. 

I am currently working as a Multimodal Algorithm Intern at the **West China Hospital**, focusing on multimodal fusion for breast cancer pCR prediction.

# 🔥 News
- *2026.02*: &nbsp;🚀 Two papers on Multi-Instance Learning (HOMIL & csMIL) submitted to **KDD 2026**.
- *2025.11*: &nbsp;🎓 Awarded **Outstanding Graduate of Sichuan Province**.
- *2025.10*: &nbsp;🎉 Our paper on Ovarian Carcinoma prognosis was accepted by **Frontiers in Oncology**.

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Frontiers 2025</div><img src='images/paper_ovarian.png' alt="Ovarian" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Histopathology Images-based Deep Learning Prediction of Prognosis in Primary Mucinous Ovarian Carcinoma** Zhang, M. Y.†, **Xia, Z. X.†**, Liu, R. Z., et al.  
*Frontiers in Oncology, 2025 (Accepted, SCI Q2)*
- Proposed a KDE-pooling Graph Deep Learning model for PMOC prognosis.
- Achieved superior risk stratification compared to FIGO stage and tumor grade.
- Provided interpretability via GNNExplainer for clinical decision support.
</div>
</div>

- **Multi-Instance Learning for Whole-Slide Image Classification Using Higher-Order Moments**, **Xia, Z. X.**, Wu, J., Wu, X. F., Yin, G. S., and Liu, B. *Submitted to KDD 2026*.
- **Cluster-Level Sparse Multi-Instance Learning for Whole-Slide Images**, Zhang, Y. D., **Xia, Z. X.**, Yin, G. S., and Liu, B. *Submitted to KDD 2026*.

# 💻 Internships
<!-- - *2025.11 - 2026.02*: **West China Hospital**, Clinical Pathology Institute. Multimodal Algorithm Intern. -->
- *2022.10 - 2023.04*: **Gusu District CDC (Suzhou)**. Data Analysis Intern.

# 🎖 Honors and Awards
- **Outstanding Graduate of Sichuan Province**, 2025
- **First-class Academic Scholarship**, SWUFE (Top 6%), 2025
- **Third Prize**, "Huawei Cup" National Post-Graduate Mathematical Contest in Modeling, 2024
- **First Prize**, National Undergraduate Mathematical Contest (Provincial), 2023
- **Grand Academic Scholarship**, SUST (Top 2%), 2023
- **First Prize**, National Undergraduate Statistical Modeling Contest (Provincial), 2022

# 📖 Education
- *2024.09 - 2026.06 (Expected)*: **M.S. in Applied Statistics**, Southwestern University of Finance and Economics (SWUFE). GPA: 89.8/100.
- *2020.09 - 2024.06*: **B.S. in Statistics**, Suzhou University of Science and Technology (SUST). GPA: 88.4/100.
