---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year CS Ph.D. student at Stanford University. My advisor is Kunle Olukotun.

My research interest is broadly in computer systems and machine learning. In particular, I focus on addressing system challenges (e.g. performance and resource usage, security and reliability) in scaling AI models (e.g. large language models, video analytics models). Three selected projects:
- Caravan (OSDI 2024, leading): Keeping specialized in-network ML models up-to-date with changing network traffic dynamics with an LLM-based data labeling agent.
- CacheGen (SIGCOMM 2024): Compressing LLM KV cache into compact bitstreams for streaming and fast model inference serving. 
- DDS (SIGCOMM 2020): Scaling video analytics models to cheap and compute-constraint edges with server-driven streaming of salient video regions. 

Previously, I obtained my bachelor's degree from the University of Chicago, with three majors in mathematics, computer science, and statistics. During my undergraduate years, I was fortunate to work with Junchen Jiang and Ravi Netravali on computer networking, with a focus on designing networked systems for video streaming and analytics. 

The pronunciation of my first name (Qizheng) is very close to that of "keygen" in public key encryption. I also go by Alex.

Last updated: September 2024

## You might be looking for...

**Personal SF bay area boba/dining map: See [here](https://www.google.com/maps/d/u/0/edit?mid=1IePP2h7zoIItNHsD3XqoUHR783AmUMw).**

For Autumn 2024, the Stanford systems reading group is Tuesday every week 2 - 3 pm. We read and discuss research papers in the general domain of systems. The webpage is [here](https://systems-reading.github.io/). Sign up for the mailing list [here](https://mailman.stanford.edu/mailman/listinfo/systems_reading). We have free and high-quality boba for all participants, so please consider joining!

## Research
_* indicates equivalent contribution_
- CacheBlend: Fast Large Language Model Serving for RAG with Cached Knowledge Fusion<br />
  Jiayi Yao, Hanchen Li, Yuhan Liu, Siddhant Ray, Yihua Cheng, **Qizheng Zhang**, Kuntai Du, Shan Lu, Junchen Jiang<br />
  EuroSys 2025 [[paper]](https://arxiv.org/abs/2405.16444) [[code]](https://github.com/YaoJiayi/CacheBlend)
  
- CacheGen: KV Cache Compression and Streaming for Fast Large Language Model Serving<br />
  Yuhan Liu, Hanchen Li, Yihua Cheng, Siddhant Ray, Yuyang Huang, **Qizheng Zhang**, Kuntai Du, Jiayi Yao, Shan Lu, Ganesh Ananthanarayanan, Michael Maire, Henry Hoffmann, Ari Holtzman, Junchen Jiang<br />
  SIGCOMM 2024 [[paper]](https://arxiv.org/abs/2310.07240) [[code]](https://github.com/uchi-jcl/cachegen)

- Caravan: Practical Online Learning of In-Network ML Models with Labeling Agents<br />
  **Qizheng Zhang**, Ali Imran, Enkeleda Bardhi, Tushar Swamy, Nathan Zhang, Muhammad Shahbaz, Kunle Olukotun<br />
  OSDI 2024 [[paper]](https://alex-q-z.github.io/files/caravan-osdi24.pdf) [[code]](https://github.com/Per-Packet-AI/Caravan-Artifact-OSDI24) [[slides]](https://alex-q-z.github.io/files/caravan-osdi24-slides.pdf) [[talk]](https://www.youtube.com/watch?v=79_lGeVXk4g)<br />
  A shorter version of this work was presented at the [Compound AI Systems Workshop](https://sites.google.com/view/compound-ai-systems-workshop/home).<br />
  <span style="color: #0096FE; font-weight: bold;">SRC JUMP 2.0 Best Paper Award</span>

- The Dataflow Abstract Machine Simulator Framework<br />
  Nathan Zhang, Rubens Lacouture, Gina Sohn, Paul Mure, **Qizheng Zhang**, Fredrik Kjolstad, Kunle Olukotun<br />
  ISCA 2024 [[paper]](https://alex-q-z.github.io/files/dam-isca24.pdf) [[code]](https://github.com/stanford-ppl/DAM-RS)<br />
  <span style="color: #0096FE; font-weight: bold;">ISCA Distinguished Artifact Award</span>
  
- GRACE: Loss-Resilient Real-Time Video through Neural Codecs<br />
  Yihua Cheng, Ziyi Zhang, Hanchen Li, Anton Arapin, Yue Zhang, **Qizheng Zhang**, Yuhan Liu, Kuntai Du, Xu Zhang, Francis Y. Yan, Amrita Mazumdar, Nick Feamster, Junchen Jiang<br />
  NSDI 2024 [[website]](https://uchi-jcl.github.io/grace.html) [[paper]](https://arxiv.org/abs/2305.12333) [[code]](https://github.com/UChi-JCL/Grace)
  
- OneAdapt: Fast Adaptation for Deep Learning Applications via Backpropagation<br />
  Kuntai Du, Yuhan Liu, Yitian Hao, **Qizheng Zhang**, Haodong Wang, Yuyang Huang, Ganesh Ananthanarayanan, Junchen Jiang<br />
  SoCC 2023 [[paper]](https://alex-q-z.github.io/files/oneadapt-socc23.pdf) [[code]](https://github.com/KuntaiDu/OneAdapt)

- Optimizing Real-Time Video Experience with Data Scalable Codec<br />
  Hanchen Li\*, Yihua Cheng\*, Ziyi Zhang, **Qizheng Zhang**, Anton Arapin, Nick Feamster, Amrita Mazumdar<br />
  SIGCOMM 2023 Workshop on Emerging Multimedia Systems [[paper]](https://alex-q-z.github.io/files/autoencoder-ems23.pdf)

- AccMPEG: Optimizing Video Encoding for Video Analytics<br />
  Kuntai Du, **Qizheng Zhang**, Anton Arapin, Haodong Wang, Zhengxu Xia, Junchen Jiang<br />
  MLSys 2022 [[paper]](https://alex-q-z.github.io/files/accmpeg_mlsys22.pdf) [[code]](https://github.com/KuntaiDu/AccMPEG)
  
- Understanding the Potential of Server-Driven Edge Video Analytics<br />
  **Qizheng Zhang**, Kuntai Du, Neil Agarwal, Ravi Netravali, Junchen Jiang<br />
  HotMobile 2022 [[paper]](https://alex-q-z.github.io/files/saliency_hotmobile22.pdf) [[code]](https://github.com/Alex-q-z/saliency-based-feedback) [[slides]](https://alex-q-z.github.io/files/saliency_hotmobile22_slides.pdf) [[talk]](https://www.youtube.com/watch?v=xtSafM0VbTs)

- Server-Driven Video Streaming for Deep Learning Inference<br /> 
  Kuntai Du\*, Ahsan Pervaiz\*, Xin Yuan, Aakanksha Chowdhery, **Qizheng Zhang**, Henry Hoffmann, Junchen Jiang<br />
  SIGCOMM 2020 [[paper]](https://alex-q-z.github.io/files/DDS-sigcomm20.pdf) [[code]](https://github.com/KuntaiDu/dds)

## Teaching
- Stanford CS 244: Advanced Topics in Networking<br />
  Course Assistant, Spring 2024

- UChicago CMSC 23000: Operating Systems<br />
  Course Assistant, Autumn 2021

## Service
- Reviewer: NeurIPS 2024, NeurIPS 2024 Machine Learning and Compression Workshop, ICLR 2025, AISTATS 2025
- Artifact Evaluation Committee: MLSys 2023, OSDI 2023, ATC 2023
- Stanford Computer Science Student Applicant Support Program: 2022, 2023
