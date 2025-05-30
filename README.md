# Brain Tumor Detection with Multimodal Language Models and Chain-of-Thought Reasoning in Neuro-Oncology Imaging

This repository contains code for comparing the performance of **conventional Large Language Models (LLMs)** and **reasoner LLMs** in analyzing brain tumor MRI images. The goal is to evaluate their diagnostic accuracy and reasoning capabilities.

The project is part of the paper/review:  
**"Multimodal Large Language Models and Chain-of-Thought Reasoning in Neuro-Oncology Imaging"**  
*(Victor Emanuel da Silva Monteiro, 2025)*

---


##  Main Scripts

| File                             | Description                                                      |
|----------------------------------|------------------------------------------------------------------|
| `tumor-o4-mini-openai.ipynb`     | Brain tumor image analysis with **o4 mini (reasoner)**            |
| `tumor-4o-openai.ipynb`          | Brain tumor image analysis with **GPT-4o (non reasoner)**, focusing on direct prompts and final labels |
| `tumor-gemini-flash-2.5.ipynb`   | Brain tumor image analysis with **Gemini 2.5 Flash (reasoner)** |
| `tumor-gemini-pro-2.5.ipynb`     | Brain tumor image analysis with **Gemini 2.5 Pro (reasoner)**   |
| `explore_dataset.ipynb`          | Dataset exploration: class distribution, image statistics, and visualization |

---

## Important Note


  - **Brain Tumor Dataset**: Not included in this repository.  
    - Download it from Kaggle: [Brain Tumor Dataset](https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor/data)
      > Jakesh Bohaju. Brain Tumor. Kaggle. 2020. [https://www.kaggle.com/dsv/1370629](https://www.kaggle.com/dsv/1370629). DOI: [10.34740/KAGGLE/DSV/1370629](https://doi.org/10.34740/KAGGLE/DSV/1370629)


⸻
