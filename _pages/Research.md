---
layout: archive
title: "Research"
permalink: /research/
excerpt: "Research"
author_profile: true
---

# Research

**Inverse Design of Materials**

SAMGPT is a molecule generative model based on the decoder of transformer, which is trained on the SMILES dataset. It can generate molecules with both conditional scaffold structure and desired properties (HOMO, LUMO, etc.) and has been used in Self-Assembled-Monolayer molecule generation for Perovskite solar cell devices, which achieved higher power conversion efficiency (PCE) compared with control samples (experimentally validated).

Here is my GitHub repository relevant to this project: [https://github.com/Harrison-Li/SAMGPT](https://github.com/Harrison-Li/SAMGPT)

**Multi-AI agent system**

I developed a Perovskite Multi-AI Agent System designed to assist materials researchers—especially those without programming experience—in discovering new self-assembled monolayer (SAM) candidates for perovskites and other photoelectric materials. By simply describing their target properties (like HOMO and LUMO), users can generate potential molecules using integrated tools. The system also mines unstructured data from published literature to support model retraining and rapid validation. For researchers in experimental areas, by leverage retrival augmented generation (RAG) the agent can retrieve detailed information such as 1. material preparation 2.material property 3.device performance 4. device fabrication processes. I further integrated this knowledge into large language models, enabling the system to provide experimental guidance and analyze correlations between material choices, device structures, and performance. Finally, the model can search for precursor suppliers and retrosynthesis plan for new candidates.

GitHub repository code will be released soon after manucript submission.