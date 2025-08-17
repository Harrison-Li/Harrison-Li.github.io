---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

My name is **Bo Li**. I am currently a postgraduate student at NUS with a background in Materials Science.  
My research interests lie at the intersection of artificial intelligence and computational chemistry, with a focus on data-driven strategies to accelerate materials discovery.  

My prior work includes inverse materials design using transformer-based architectures and the development of a novel adapter module for classifier-free guidance. I have also explored the use of Large Language Models (LLMs) in multi-agent AI systems to enable text-guided molecule discovery.  

In the future, I aim to establish an automated materials discovery pipeline encompassing data mining, generative models for novel materials, property emulators that integrate machine learning with quantum mechanical methods, and domain-specific LLMs to execute and optimize experiments within a closed-loop discovery framework.  

---

# Education

**National University of Singapore**  
📍 Singapore · *2025–Present*  
MSc Materials Science and Engineering  

---

**Queen Mary University of London**  
📍 United Kingdom · *2021–2025*  
BEng Materials Science and Engineering  
🏆 First Class Honours (Top 10%)

# Research

**Inverse Design of Materials**

SAMGPT is a molecule generative model based on the decoder of transformer, which is trained on the SMILES dataset. It can generate molecules with both conditional scaffold structure and desired properties (HOMO, LUMO, etc.) and has been used in Self-Assembled-Monolayer molecule generation for Perovskite solar cell devices, which achieved higher power conversion efficiency (PCE) compared with control samples (experimentally validated).

Here is my GitHub repository relevant to this project: https://github.com/Harrison-Li/SAMGPT

**Multi-AI agent system**

I developed a Perovskite Multi-AI Agent System designed to assist materials researchers—especially those without programming experience—in discovering new self-assembled monolayer (SAM) candidates for perovskites and other photoelectric materials. By simply describing their target properties (like HOMO and LUMO), users can generate potential molecules using integrated tools. The system also mines unstructured data from published literature to support model retraining and rapid validation. For researchers in experimental areas, by leverage retrival augmented generation (RAG) the agent can retrieve detailed information such as 1. material preparation 2.material property 3.device performance 4. device fabrication processes. I further integrated this knowledge into large language models, enabling the system to provide experimental guidance and analyze correlations between material choices, device structures, and performance. Finally, the model can search for precursor suppliers and retrosynthesis plan for new candidates.

GitHub repository code will be released soon after manucript submission.
