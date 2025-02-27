---
permalink: /
title: "About me"
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

I am a master's student who enrolled at the School of Mathematics and Statistics, Lanzhou University in 2023, under the supervision of Professor Shoujun Xu. 

My research interests mainly focus on **multimodal fusion** and **deep learning**. I am passionate about combining theory with practice and exploring the applications 
of these technologies in real-world scenarios, such as medical image analysis and intelligent transportation. My master's thesis topic is "*Application Research 
on Early Auxiliary Diagnosis of Breast Cancer Based on Multimodal Fusion*".

Currently, I am seeking an internship opportunity, hoping to further enhance my capabilities through practical projects.


# 📖 Educations
- *2023.09 - now*,     Lanzhou University, School of Mathematics and Statistics, major in Applied Statistics.Lanzhou.
- *2019.09 - 2023.06*, North University of China, School of Mathematics, Major in Statistics.Taiyuan.

<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📝 Projects

🎉🎉 *2024.04-2024.06*: &nbsp;  *Project Name:*  **PTSD Risk Assessment for Rescue Workers Based on Multimodal Fusion.**

- This project primarily focuses on the early screening and intervention of Post-Traumatic Stress Disorder (PTSD) among rescue personnel. Initially, 
data preprocessing and **feature engineering** were conducted on questionnaire data to identify variables associated with the likelihood of developing PTSD,
transforming the problem into a binary classification task.

- To address the issues of data label **imbalance** and **high dimensionality**, SMOTE was applied to the training set for oversampling, and a **Lasso-Logistic
model** was constructed for variable selection and classification prediction. Subsequently, integrating questionnaire data with EEG data, a mid-level
**fusion model** (MLP+GRU+DNN+Logistic) was employed to model the risk of occurrence.
[**pdf**](https://github.com/TCPtcp/Multimodal-Fusion-PTSD/blob/main/pdf.pdf)
[**code**](https://github.com/TCPtcp/Multimodal-Fusion-PTSD/tree/main)

🎉🎉 *2024.05-2024.10*: &nbsp;  *Project Name:*  **Kaggle RSNA 2024 Lumbar Degenerative Classification.**
- For the provided lumbar MRI data, the required data was extracted through data transformation and data splitting. Additionally, **data augmentation** was performed
on the training data using methods such as **Gaussian blur**, brightness and contrast adjustment, and **translation, rotation, and scaling**. The MRI images were classified
and trained based on a **pre-trained EfficientNet model**, and the final model achieved a **score of 0.80** on a non-public dataset.


🎉🎉 *2022.10-2023.06*: &nbsp;  *Project Name:*  **Research on Comprehensive Evaluation Model of Intelligent Transportation Based on Vehicular Network Big Data.**

- The project is based on the in-vehicle data of freight vehicles to analyze the driving behavior of drivers. First, the obtained vehicular network data
is preprocessed and **feature extraction** is performed to obtain driving behavior indicators.

- In the analysis of driving behavior, **DBSCAN density clustering** is used to cluster the driving behavior indicator data, categorizing driving behavior into
three classes and obtaining data labels. Based on these clustered data labels, **ensemble learning** is applied, combining Random Forest, XGBoost, and CatBoost to
classify and predict driving behavior. Finally, a driving behavior visualization dashboard is built using **ECharts**.

🎉🎉 *2021.10-2022.06*: &nbsp;  *Project Name:*  **Application of Machine Learning Methods in the Statistical Analysis of Digital Economy in Shanxi.**
- The project was a research topic approved for the 2023 Shanxi Provincial Social and Economic Statistics Research Program. As the leader of the student team,
  I fully participated in the project's topic selection, proposal writing, and finalization under the guidance of a faculty advisor.

- Based on data related to the digital economy in Shanxi Province, the project constructed an evaluation system for the development level of the digital economy 
using the entropy weight method. It analyzed the current status of the digital economy in Shanxi and used **Ridge regression** and **Random Forest models** to analyze the 
influencing factors. Additionally, a visualization app was created using **R Shiny**.

# 🎖 Honors and Awards
- *2023.12* &nbsp; **"Huawei Cup" graduate Student Mathematical Modeling Competition, national third prize.**
- *2024.08* &nbsp; The national third prize in the Case Competition of Applied Statistics Degree graduate students.
- *2024.05* &nbsp; **Blue Bridge Cup Python programming graduate group, first prize in Gansu region.**
- *2021.06* &nbsp; "Teddy Cup" Data Mining Challenge, national third prize.
- *2021.12* &nbsp; "Teddy Cup" data analysis skills competition, national second prize.
- *2022.12* &nbsp; **National Mathematics Competition for College Students, Provincial first prize (twice).**
- *2023.12* &nbsp; Second-Class Scholarship of Lanzhou University, university level.
- *2023.06* &nbsp; First-Class Scholarship of North University of China (3 times).
  
<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Learn More
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
