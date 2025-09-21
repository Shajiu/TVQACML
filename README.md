# TVQACML

[🤗 TVQACML](https://huggingface.co/shajiu/Qwen2-VL-7B-CML-SFT) | [📖 Paper](https://arxiv.org) | [🏆 TvqaCmlBench](https://huggingface.co/datasets/shajiu/TvqaCmlBench)

**TVQACML: Benchmarking Text-Centric Visual Question Answering in Multilingual Chinese Minority Languages** (EMNLP 2025 Main Conference) <br>

## Abstract
Text-Centric Visual Question Answering (TEC-VQA) serves as a key benchmark for evaluating AI’s ability to reason over text-rich visual scenes. However, most existing TEC-VQA datasets focus on high-resource languages and are susceptible to benchmark contamination due to overlap with pretraining corpora of large models. These limitations severely hinder progress in low-resource language scenarios and compromise the reliability of current evaluations. To address both the underrepresentation of low-resource languages and the contamination issue, we propose TVQACML, the first large-scale TEC-VQA benchmark for multilingual Chinese minority languages, constructed through a scalable, reproducible pipeline. It comprises 8,000 real-world images and 32,000 high-quality QA pairs across eight languages and 30 application scenarios. We conduct comprehensive benchmarking of open-source, closed-source, and text-centric MLLMs, revealing substantial performance gaps from human accuracy, especially in scene-text and document understanding tasks. Furthermore, instruction tuning with TVQACML yields consistent performance gains, in some cases surpassing leading closed models demonstrating the dataset’s utility for model alignment. We also introduce a lightweight, extensible evaluation metric for robust multilingual, multi-format answer assessment. 

<p align="center">
  <img src="https://github.com/Shajiu/TVQACML/blob/main/assets/statistics_1.png" width="100%" />
  <br>
  <sub><em>Overall performance of MLLMs on the TVQACML benchmark.</em></sub>
</p>



<p align="center">
  <img src="https://github.com/Shajiu/TVQACML/blob/main/assets/examples_2.png" width="100%" />
  <br>
  <sub><em>TVQACML examples sampled from each languages. The English version in parentheses.</em></sub>
</p>




<p align="center">
  <img src="https://github.com/Shajiu/TVQACML/blob/main/assets/construction_3.png" width="100%" />
  <br>
  <sub><em>The construction pipeline of the TVQACML Benchmark.</em></sub>
</p>




If you find KRETA useful for your research and applications, please cite using this BibTeX:
```bibtex
@article{hwang2025kreta,
  title={TVQACML: Benchmarking Text-Centric Visual Question Answering in Multilingual Chinese Minority Languages},
  author={Jiu Sha, Yu Weng, Mengxiao Zhu, Chong Feng, Zheng Liu, Lama Jie},
  journal={arXiv preprint arXiv:},
  year={2025}
}
```

## Licence

[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)


## Bias, Risks, and Limitations
Use of this dataset is entirely at your own discretion and risk. We make no guarantees regarding its accuracy or reliability. The dataset is provided “as is,” without any warranties or representations of any kind—whether express, implied, statutory, or otherwise. This includes, but is not limited to, implied warranties of quality, performance, merchantability, fitness for a particular purpose, non-infringement, accuracy, or the absence of defects or errors (known or unknown).
We expressly disclaim all liability under any legal theory, including negligence, for any direct, indirect, incidental, special, consequential, punitive, or exemplary losses, costs, or damages that may arise from the use of this dataset or this license. To the fullest extent permitted by law, the foregoing disclaimers and limitations of liability shall be interpreted as an absolute waiver of all warranties and liabilities.
