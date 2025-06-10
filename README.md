---
# AI-Powered Crowdsourcing Submission Evaluation

This repository contains the code and notebooks developed for a master's thesis exploring the use of combined discriminative and generative AI models to enhance solution filtering and prioritization in crowdsourcing contests. The goal is to efficiently and fairly evaluate large volumes of submissions by leveraging the strengths of both quantitative and qualitative AI assessments.

## Thesis Abstract

Crowdsourcing contests generate large volumes of submissions, making efficient and fair evaluation challenging. This thesis explores how a combination of discriminative and generative artificial intelligence models can enhance solution filtering and prioritization. The discriminative model ranks submissions based on quantitative features while the generative model assesses novelty and usefulness through structured textual reasoning.

Building on prior research in AI-assisted evaluation for crowdsourcing contests, this work refines data preprocessing and refines the model’s evaluation methodology. Results demonstrate that filtering out 50% of submissions retains approximately 95% of top-winning entries, confirming the discriminative model’s effectiveness in removing weaker submissions while maintaining recall. At the same time, the generative model conducts a qualitative assessment of submissions, evaluating them from a different perspective than the discriminative model. A pattern emerges where the model tends to assign higher evaluations to winning submissions, indicating its ability to recognize innovation.

Analyzing 112 contests, this thesis demonstrates that combining quantitative filtering with qualitative evaluation ensures that the great majority of well-documented and high-quality solutions remain in consideration. The findings also highlight the impact of domain-specific prompt adaptations in improving generative model accuracy. Future research could explore interactive evaluator chatbots and multi-modal analyses to further refine AI-driven assessments.

## Repository Contents

This repository is organized into several Colab notebooks, each serving a specific purpose in the overall AI-assisted evaluation framework:

* **`Submission Evaluation Mobility Impaired.ipynb`**: This notebook is specifically designed to evaluate submissions for contests focused on **mobility-impaired solutions**. It adapts the general evaluation framework to the unique requirements and characteristics of such submissions.

* **`Submission Evaluation LLM.ipynb`**: This notebook provides the **general framework for evaluating submissions using a language model (LLM)**. It encompasses the core logic for qualitative assessment based on textual reasoning.

* **`Evaluation Buildtogether 2.ipynb`**: This notebook contains the evaluation specific to the **BuildTogether 2 contest**. It demonstrates how the AI evaluation framework can be applied and fine-tuned for a particular contest's dataset and criteria.

---
