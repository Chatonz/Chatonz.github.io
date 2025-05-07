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

I am currently a Senior undergraduate at Shandong University, based in Qingdao.

I am now working on Generative models(T2I, T2M), XAI research. If you would like to have an academic discussion or cooperation, please feel free to email me at chatoncws@gmail.com.

My research interests include:

- Text-to-Motion Generation
- Multimodal reasoning and generation
- XAI



# 🔥 News
- *2025.05* One paper of t2i is accepted by **ICML 2025**. Congratulations to the collaborators!
- *2024.10* I will join Hong Kong University of Science and Technology (Guangzhou) as a PhD student in Fall 2025, supervised by Associate Professor [Yutao Yue](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/YUE-Yutao/yutaoyue).
- *2024.09* One paper of XAI is accepted by **NeurIPS 2024**. Congratulations to the collaborators!
- *2024.09* I join CUHK(shenzhen) as a RA supervised by Professor [Zhizheng Wu](https://drwuz.com/).
- *2024.07* One paper of robustness of text-to-motion generation is accepted by **ACM MM 2024**. Congratulations to the collaborators!
- *2023.12*: I am a remote intern supervised by Professor [Di Wang](https://shao3wangdi.github.io/).
- *2023.08*: I am a remote intern supervised by Professor [Chen Chen](https://www.crcv.ucf.edu/chenchen/).
- *2023.06*: I join Agibot as a reasearch intern.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/dct_diff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**DCTdiff: Intriguing Properties of Image Generative Modeling in the DCT Space**

Mang Ning, Mingxiao Li, Jianlin Su, Jia Haozhe, Lanmiao Liu, Martin Benes, **Wenshuo Chen**, Albert Ali Salah, Itir Onal Ertugrul 

</div>
</div>


  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/framework.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[SATO: Stable Text-to-Motion Framework](https://arxiv.org/abs/2405.01461)**

**Wenshuo Chen#**, Hongru Xiao#, Erhang Zhang#, Lijie Hu, Lei Wang, Mengyuan Liu, Chen Chen

[**Project**](https://sato-team.github.io/Stable-Text-to-Motion-Framework/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/sato-team/Stable-Text-to-Motion-Framework) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- **We are  the first work to discover the instability issue in text-to-motion models**
- We successfully strike a balance between accuracy and stability, ensuring our model maintains high precision even in the face of perturbations
- Our work points to a novel direction for improving text-tomotion models, paving the way for the development of more robust models for real-world applications
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/framework_med.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Towards Multi-dimensional Explanation Alignment for Medical Classification](https://arxiv.org/abs/2410.21494)**
  
Lijie Hu#, Songning Lai#, **Wenshuo Chen#**, Hongru Xiao, Hongbin Lin, Lu Yu, Jingfeng Zhang, and Di Wang
- We proposed an end-to-end framework called Med-MICN, which leverages the strength of different XAI methods such as concept-based models, neural symbolic methods, saliency maps, and concept semantics.
- Our outputs are interpreted in multiple dimensions, including concept prediction, saliency maps, and concept reasoning rules, making it easier for experts to identify and correct errors.
- Med-MICN demonstrates superior performance and interpretability compared with other concept-based models and the black-box model baselines.  
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/time_pre..png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[FTS: A FRAMEWORK TO FIND A FAITHFUL TIMESIEVE](https://arxiv.org/pdf/2405.19647)**
  
Songning Lai#, Ninghui Feng#, Jiechao Gao, Hao Wang, Haochen Sui, Xin Zou, Jiayu Yang, **Wenshuo Chen**, Hang Zhao, Xuming Hu, Yutao Yue
- Our research provides faithful technical support and theoretical support to the field of time series forecasting, promising to advance the development and reliability of forecasting methods within the industry. Through these efforts, we aim to bolster the trustworthiness of models, ultimately supporting decision-making processes that rely on accurate and consistent predictions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/free-t2m.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[Free-T2M: Frequency Enhanced Text-to-Motion Diffusion Model
With Consistency Loss](https://arxiv.org/pdf/2501.18232)**
  
**Wenshuo Chen#**, Haozhe Jia#, Songning Lai, Keming Wu, Hongru Xiao, Lijie Hu, Yutao Yue
- Distinguished from previous works that primarily focused on temporal aspects, We introduce a novel research perspective by analyzing motion generation
from a denoising process.
- We propose two types of consistency loss that act on the semantic planning and fine-grained improving stages, significantly improving model stability and precision.
- Extensive experiments demonstrate the effectiveness of our approach. Without increasing model complexity, our method achieves state-of-the-art performance, thereby facilitating practical applications in text-tomotion generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/RMDM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[RMDM: Radio Map Diffusion Model with Physics Informed](https://arxiv.org/abs/2501.19160)**
  
Haozhe Jia#, **Wenshuo Chen#**, Zhihui Huang#, Hongru Xiao, Nanqian Jia, Keming Wu, Songning Lai, Yutao Yue
- Unlike traditional data-driven methods, we incorporate Helmholtz equation-based constraints directly into the AI model, ensuring predictions align with electromagnetic wave propagation laws and reducing bias.
- Our approach leverages a dual U-Net architecture, where the first U-Net is trained via Physics-Informed Neural Networks (PINN) to enforce physical consistency, while the second U-Net 
- Extensive experiments on static (SRM) and dynamic (DRM) radio spectrum modeling validate the effectiveness of our method. Without increasing model complexity, our RMDM framework outperforms existing solutions, offering a robust and practical approach for radio spectrum analysis.
</div>
</div>

# 🎖 Honors and Awards
- *2023.10* National first prize in CUMCM-2023 **(Top 0.3%)**
- *2023.12* National Award for Intelligent Car 5G Communication Outdoor Competition 2023 **(Top 0.2%)**. 

# 📖 Educations
- *2021.09 - Present*, Undergraduate Student, Shandong University, Qingdao. 





# 💻 Internships
- *2024.09* I join CUHK(shenzhen) as a RA supervised by Professor [Zhizheng Wu](https://drwuz.com/).
- *2023.12*: I am a remote intern supervised by Professor [Di Wang](https://shao3wangdi.github.io/).
- *2023.08*: I am a remote intern supervised by Professor [Chen Chen](https://www.crcv.ucf.edu/chenchen/).
- *2023.06*: I join Agibot as a reasearch intern.
