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

# 📖 Biography

I'm currently a master student for Integrated Circuit Science and Technology in the School of Electronic and Computer Engineering, Peking University Shenzhen Graduate School, China, under the supervision of [Prof. Hailong Jiao](https://www.ece.pku.edu.cn/info/1045/2719.htm) at [VLSI-Lab](http://www.pku-vlsi.com/). I received the B.S. degree of Microelectronics Science and Technology in Hongyi Honor College, Wuhan University, China, in June 2025. My undergraduate advisor was [Prof. Chang Sheng](https://jszy.whu.edu.cn/changsheng/zh_CN/index.htm).

<span class='anchor' id='research-tracks'></span>

# 💡 Research Tracks

My current research interests focus on **Efficient AI Chip and System**.

- **Accelerators for Energy Efficient Edge AI**
  - I am currently dedicated to develop edge accelerators for the foundation models of Embodied/Physical AI, with specific scenarios like autonomous driving, robotics, etc. For a typical foundation model, I focus on the following aspects:
  - **Feature Extraction**: CNNs for classification, segmentation, and object detection (TCAD'24, TCAS-I'25, TC'25), and 3D visual perception networks based on point cloud.
  - **Multi-Sensor Fusion**: BEV-based approaches for fusing multi-view visual features in the autonomous driving scenario.
  - **Scene Representation**: Emerging 3D/4D representation forms like Gaussian Splatting.
  - **Reasoning and Action-Making**: The co-processing of high-level reasoning and low-level action-making via emerging model architectures.
- **Computing-in-Memory for Emerging Applications**
  - I am interested in the SRAM-based digital CIM design. I have made various review reports about SRAM CIM in my course projects. I advocate understanding the role of CIM in AI chips and systems from the perspectives of the abstraction hierarchy and memory hierarchy of computer systems.
- **System Architecture and Design Automation for AI Deployment**
  - I also making efforts on the system architecture and design automation for AI deployment, especially the design and mapping strategies for spatial dataflow architecture (TCAS-I'25). 
- **Fundamental Optimization Theories for AI Chip and System**
  - I believe that the summarization of fundamental theories is the most important factor driving research progress. I am trying to make some contributions on review papers about fundamental theories.

<span class='anchor' id='news'></span>

# 🔥 News

- *2025.06*: &nbsp; One co-authored paper about fully pipelined FPGA accelerator for semantic segmentation CNN is accepted by **IEEE TC**. Congratulations to Jiahui!
- *2025.06*: &nbsp; One co-first-authored paper about fully pipelined FPGA accelerator and mapping toolchain for various CNN is accepted by **IEEE TCAS-I**. Congratulations to Zhan Li!
- *2024.09*: &nbsp; One co-first-authored paper about fully pipelined FPGA accelerator for encoder-decoder segmentation CNN is accepted by **IEEE TCAD**. Congratulations to Zhan Li!
- *2024.07*: &nbsp; Our fully pipelined streaming architecture for sparse Transformer acceleration wins **National First Prize** and **YMTC (长江存储) Corporate Award** in 2024 China Postgraduate IC Innovation Competition. Congratulations to Zhan Li, Qunkang and Zhihan!
- *2023.12*: &nbsp; Our fully pipelined streaming architecture for CNN acceleration wins **National First Prize** and **Xilinx Corporate Award** in FPGA Innovation Design Track of 2023 National College Students' Embedded Chip and System Design Competition. Congratulations to Zhan Li, Zhihan and Xingyu!

<span class='anchor' id='publications'></span>

# 📝 Publications

(*: co-first author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-I 2025</div><img src='images/metaaccel.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MetaAccel: A High-Performance and Agile Accelerator Design Framework With Multi Clock Domain Optimization for Complex CNN](https://doi.org/10.1109/TCSI.2025.3586373)

Zhan Li\*, **Yuxian Jiang**\*, Zhihan Zhang, Jiahui Huang, Qunkang Meng, Xingyu Shi, Hao Wang, Qijun Huang, and Sheng Chang

**IEEE Transactions on Circuits and Systems I: Regular Papers (TCAS-I), 2025**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TC 2025</div><img src='images/tc25cnn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A High-Intensity Solution of Hardware Accelerator for Sparse and Redundant Computations in Semantic Segmentation Models](https://doi.org/10.1109/TC.2025.3585354)

Jiahui Huang\*, Zhan Li\*, **Yuxian Jiang**, Zhihan Zhang, Hao Wang, and Sheng Chang

**IEEE Transactions on Computers (TC), 2025**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAD 2024</div><img src='images/pedsa.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PEDSA: High-Throughput Pipeline-Based FPGA Accelerator for Convolutional Encoder–Decoder Segmentation Networks](https://doi.org/10.1109/TCAD.2024.3485571)

**Yuxian Jiang**\*, Zhan Li\*, Zhihan Zhang, Hao Wang, and Sheng Chang

**IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2024**
</div>
</div>

<span class='anchor' id='honors-and-awards'></span>

# 🏆 Honors and Awards

- *2025.06*: &nbsp; Full Tuition Credit Refund for Top 1% of 2025 Graduates at Wuhan University (武汉大学2025届前1%优秀毕业生返还全部学分费).
- *2025.06*: &nbsp; Outstanding Graduate of Wuhan University.
- *2025.06*: &nbsp; Outstanding Graduate of Hongyi Honor College, Wuhan University.

<span class='anchor' id='research-taste'></span>

# 🤔 Research Taste

Personally, I conduct my research with certain research tastes. I also hope to have more exchanges with like-minded scholars.

- 📖**Make ideas fall on hardware-level new features when designing accelerators**: Currently,  software-hardware co-optimization is the mainstream approach for realizing AI accelerators. However, this does not mean that we only need to simply change the algorithm and provide a straightforward hardware implementation. Over-reliance on algorithm optimization is essentially escaping some hardware design difficulties by forcibly eliminating the problem itself. Methods for improving algorithm efficiency also should not be blindly transferred to hardware (otherwise it will easily cause additional overhead), but rather we should look for hardware-efficient ways to transfer them. I appreciate those works dealing with true problem in hardware and providing substantive new features hardware.
- 🎯**Focus on fundamental problems that closely related to most algorithms or scenarios**: Directly selecting a novel or exotic algorithm and implementing a chip for it is an effective way to publish papers. However, I prefer to focus on some more universal problems. Research should focus on accelerating fundamental models or operators, rather than implementing additional processing steps that are less common but just easy to find ideas for.
- ⚖️**Find a balance between industry needs and academic significance**: The value of a work should be demonstrated by combining real industry pain points and user needs with the research content, rather than broadly pursuing increasingly extreme so-called optimizations. At the same time, it is essential to distinguish between scientific and engineering problems. Academic research needs to be exploratory and groundbreaking, rather than being judged solely on whether it can be transformed directly into a product in the present moment, or being implemented by applying the thinking of product development.
- ✍️**Emphasize the summary of fundamental theories**: Theories like the roofline model, abstraction hierarchy, and memory hierarchy are the source of new ideas. Research should not be approached in a fast-food style; instead, one should strive to truly understand the essence and limitations behind mainstream or non-mainstream approaches, thereby improving the quality of one's own ideas.

At the same time, I deeply admire and advocate **Mr. Liang Shuming**'s discussion of [the eight levels of thinking](https://mp.weixin.qq.com/s/nyx6UTntwsyZiDoPaBNdHg).

- **Level 1**: Forming Your Own Opinion (形成主见)
- **Level 2**: Discovering Unexplainable Things (发现不能解释的事情)
- **Level 3**: Achieving Integration and Mastery (融会贯通)
- **Level 4**: Recognizing Your Own Limitations (知不足)
- **Level 5**: Mastering Complexity through Simplicity (以简御繁)
- **Level 6**: Applying Knowledge with Ease (运用自如)
- **Level 7**: Gaining a Panoramic View (一览众山小)
- **Level 8**: Achieving Thorough Clarity (通透)

I also have my own summary of **research capabilities**, which I believe is important for the long-term development of a student.

- **On the Primary Purpose of Graduate Studies**
  - The primary goal of pursuing a master or Ph.D. degree is not merely to publish as many papers as possible, nor to make grand contributions to human progress. Rather, it is to cultivate the capability to identify, analyze, and solve problems. Papers and tangible outcomes are the "fish" (the product), not the "fishing" (the thinking, method, and spirit).
- **The Three Pillars of Research Competence**
  - **Knowledge and Skills**:
    - Have you solidified your foundational knowledge? Can you properly and effectively write code? Are you proficient with software tools and experimental instruments? At the level of a practitioner, you must learn to **keep your hands dirty** — that is, to be willing to tackle tasks step by step and implement them with dedication.
  - **Research Thinking**:
    - **Domain-Specific Research Cognition**: 
      - Do you possess a comprehensive and clear overall understanding of a particular field or industry?
      - For your specific research area, are you familiar with the entire relevant knowledge system?
      - Do you understand the major problems to be solved, the traditional approaches, the emerging methods, and your own approach (if any), as well as possible future directions?
      - Can you work with clear motivation and logic, rather than busying yourself without clarity?
    - **Universal Learning Capability**:
      - Are you enable to quickly grasp the underlying logic of new subjects or domains?
      - Can you efficiently "learn on the fly" and apply new knowledge promptly, rather than remaining at the stage of exam-oriented cramming, ineffective rote memorization, or working within artificially limited scopes? 
  - **Information Expression**
    - **Internal Communication with Colleagues**: As a team member, can you clearly communicate with collaborators about: what you have accomplished, what problems you have encountered, and what you need from them?
    - **External Communication with Others**: As a leader, can you effectively convey the value of your project or proposal to others, thereby securing resources and opportunities for your team? As an author, can you present your work persuasively to peer reviewers, enabling them to approve your manuscript for publication?

<span class='anchor' id='projects'></span>

# 🚀 Projects

## Point Cloud Networks Accelerator \[Tape-Out May 2025\] --September 2024 to May 2025

This work proposed a 2×3 mm^2 TSMC 28nm accelerator for point cloud understanding, leaded by Dr. Yanzhe Ma and Dr. Changchun Zhou. It is also the 2rd version of [Nebula](https://ieeexplore.ieee.org/document/10904703).

**Main Contributions**:

1. Implementation of 3 basic operation units, including element-wise add/sub, tensor concatenation, and matrix transposition. The 3 units support AXI interface and arbitary tensor sizes.
2. Implementation of a UART unit. This unit supports 2 modes. The monitor mode transfers on-chip signals that are pre-defined to be monitored from chip to external host. The external memory access (EMA) mode transfers module instructions from external memory to on-chip top controller through request sending and data receivement with bi-direct UART-AXI conversion.
3. Assistance in the implementation of the on-chip AXI crossbar, fast point sampling (FPS) unit, and the byte-enable-supported global buffer.
4. Verification of a embedded RISC-V core which is for write/read the on-chip config regfile through software.

## 4D Gaussian Splatting Accelerator \[Tape-Out May 2026\] --August 2025 to May 2026

This work proposed a 2×2 mm^2 TSMC 28nm accelerator for [HAC](https://arxiv.org/abs/2403.14530)-style 4D Gaussian Splatting for dynamic scene rendering, leaded by master student Wei Luo.

**Main Contributions**:

1. Implementation of a multi-resolution binary hash interpolation unit. This unit supports tri-linear interpolation based on multi-resolution binary hash table, which is used in HAC for video feature decoding.
2. Implementation of a gaussian preprocess unit. This unit supports complete functions for converting 3D gaussian properties (3D covariance matrix and spatial coordinate mainly) to 2D splatted gaussian properties (2D covariance matrix and pixel scale coordinate). The conversions involve linear transformations based on view-transformation matrix and projection matrix, quadratic-form-style covariance splatting based on Jacobi matrix, generation of the inverse matrix based on determinant, and other vector operations or scalar operations. The fixed point and micro-scaling INT (MXINT) style data formats are supported to maintain the accuracy.
3. Implementation of a frustum culling unit. This unit introduces NeRF-style ray sampling method into Gaussian Splatting for redundancy-check-free voxel-wise frustum culling.

## Fully Pipelined Streaming Architecture and Mapping Toolchain for Various CNNs in FPGA --July 2023 to June 2025

This work proposed a fully pipelined FPGA accelerator with an agile mapping framework for various CNNs, including image classification, object detection, and semantic segmentation, leaded by Dr. Zhan Li.

**Main Contributions**:

1. Implementation of our proposed on-chip fully unrolled parallel dataflow on ResNet18, SegNet-Basic, and U-Net.
2. Assistance in the implementation of a network-architecture-aware hardware resource estimation model based on our proposed dataflow. The model can directly generated hyper-parameters for hardware design based on user-defined performance requirement, network architecture, and target platform.
3. Implementation of a series of RTL code templates for agile synthesis of accelerators. The templates are fully parameterized, supporting arbitary common specifications of network layers (convolution kernel size, feature map size, etc.) and most types of operators in CNN, including vanilla/depth-wise/point-wise convolution, max/avg pooling, unpooling, deconvolution, and dilated convolution.

<span class='anchor' id='personal-hobbies'></span>

# ⭐️ Personal Hobbies

- 🏓**table tennis**: I am now a key member and vice-captain of the PKUSZ table tennis team. I was formerly the captain of the WHU Hongyi Honor College table tennis team. I play with a right-handed shake-hand grip (Butterfly Viscaria FL), using inverted rubbers on both sides of the blade (Forehand: DHS Hurricane 3, Backhand: Butterfly D09c). My primary scoring strategies are defense, rallies, and variations in rhythm.
- 🎹**piano**: I have been learning piano since I was a child. I became very interested in ACG piano during high school and have practiced many [Animenz](https://space.bilibili.com/6075139)'s arrangements, such as [Unravel](https://www.bilibili.com/video/BV1px411A7ir/), [Bios (10th Anniversary Edition)](https://www.bilibili.com/video/BV1JP4y1G7ze), and [Sincerely](https://www.bilibili.com/video/BV1CK411J7fX), etc. I have also published some piano arrangements on [my bilibili account](https://www.bilibili.com/video/BV1gHAqzyEWv?vd_source=7920e780a5c945ddf1e66287bafc3e3f).
- 📜**Calligraphy**: During my childhood, I practiced calligraphy for many years under the guidance of [Mr. Lin Zhenhong](https://baike.baidu.com/item/%E6%9E%97%E6%8C%AF%E9%B8%BF/5308403). I mainly studied classic styles such as Mr. Yan Zhenqing's regular script and Mr. Wang Xizhi's running script, and created many calligraphy works.
- ☯️**Chinese Kungfu**: I studied Chen-style Tai Chi for many years during my primary and secondary school years. I have also maintained a close interest in various kickboxing and Muay Thai competitions, such as [K-1](https://www.k-1.world/), Glory, [ONE Championship](https://www.onefc.com/cn/), and WLF (Wu Lin Feng), etc.
- 🧐**Religious Philosophy and Chinese Culture**: My early years were steeped in the recitation of many traditional Chinese classics, such as the Analects, the Great Learning, the Doctrine of the Mean, and the Book of Changes. I also have an ongoing inquiry of Vedanta philosophy from India, the integral framework and evergreen philosophy of Ken Wilber, and the teachings of Krishnamurti.
