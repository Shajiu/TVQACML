# TVQACML
TVQACML: Benchmarking Text-Centric Visual Question Answering in Multilingual Chinese Minority Languages
[🤗 TVQACML](https://huggingface.co/shajiu/Qwen2-VL-7B-CML-SFT) | [📖 Paper](https://arxiv.org) | [🏆 TvqaCmlBench](https://huggingface.co/datasets/shajiu/TvqaCmlBench)

**TVQACML: Benchmarking Text-Centric Visual Question Answering in Multilingual Chinese Minority Languages** (EMNLP 2025 Main Conference) <br>

## Abstract
Text-Centric Visual Question Answering (TEC-VQA) serves as a key benchmark for evaluating AI’s ability to reason over text-rich visual scenes. However, most existing TEC-VQA datasets focus on high-resource languages and are susceptible to benchmark contamination due to overlap with pretraining corpora of large models. These limitations severely hinder progress in low-resource language scenarios and compromise the reliability of current evaluations. To address both the underrepresentation of low-resource languages and the contamination issue, we propose TVQACML, the first large-scale TEC-VQA benchmark for multilingual Chinese minority languages, constructed through a scalable, reproducible pipeline. It comprises 8,000 real-world images and 32,000 high-quality QA pairs across eight languages and 30 application scenarios. We conduct comprehensive benchmarking of open-source, closed-source, and text-centric MLLMs, revealing substantial performance gaps from human accuracy, especially in scene-text and document understanding tasks. Furthermore, instruction tuning with TVQACML yields consistent performance gains, in some cases surpassing leading closed models demonstrating the dataset’s utility for model alignment. We also introduce a lightweight, extensible evaluation metric for robust multilingual, multi-format answer assessment. 

<p align="center">
  <img src="https://github.com/Shajiu/TVQACML/blob/main/assets/figure1.png" width="850" />
  <br>
  <sub><em>Overall performance of MLLMs on the TVQACML benchmark.</sub></em>
</p>


