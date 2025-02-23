# Awesome-Data-Curation
This repository aims to compile a curated list of exceptional data curation ideas, tools, and more, designed to enhance machine learning scalability by providing better data. Additionally, this repository contains curation methods for Natural Language Processing, Computer Vision, and Multimodal Models. Data curation is also a fundamental process to train or fine-tune LLMs or Diffusion models. Inspired by [awesome-python](https://github.com/vinta/awesome-python) and originally created by [fasouto](https://github.com/fasouto).


# Tools
## One stop
- [Data-juicer](https://github.com/alibaba/data-juicer): Data-Juicer is a one-stop data processing system to make data higher-quality, juicier, and more digestible for LLMs.

## Cleaning
- [Cleanlab](https://github.com/cleanlab/cleanlab): Cleanlab helps you clean data and labels by automatically detecting issues in a ML dataset. 
- [Docta](https://github.com/Docta-ai/docta): Docta is an advanced data-centric AI platform that offers a comprehensive range of services aimed at detecting and rectifying issues in your data.
- [NeMo-Curator](https://github.com/NVIDIA/NeMo-Curator): NeMo Curator is a Python library that consists of a collection of scalable data-mining modules for curating natural language processing (NLP) data for training large language models (LLMs).
- [Lilac](https://github.com/lilacai/lilac): Lilac is a tool for exploration, curation and quality control of datasets for training, fine-tuning and monitoring LLMs.

## Mining
- [Lightly.ai](https://www.lightly.ai/): Lightly selects the subset of your data with the biggest impact on model accuracy, allowing you to improve your model iteratively by using the best data for retraining.

## Visualization
- [Nomic Atlas](https://github.com/nomic-ai/nomic): Atlas automatically organizes your data into topics informed by the latent contents of your embeddings. 
- [RATH](https://github.com/Kanaries/Rath): RATH automates your Exploratory Data Analysis workflow with an Augmented Analytic engine by discovering patterns, insights, causals and presents those insights with powerful auto-generated multi-dimensional data visualization.
- [WizMap](https://github.com/poloclub/wizmap): WizMap is a scalable interactive visualization tool to help you easily explore large machine learning embeddings. 

# Ideas
## Paper
- [DINOv2: Learning Robust Visual Features without Supervision](https://arxiv.org/abs/2304.07193): We assemble our curated LVD-142M dataset by retrieving, from a large pool of uncurated data, images that
are close to those in several curated datasets. 
- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155): We collect a dataset of labeler demonstrations of the desired model behavior, which we use to fine-tune GPT-3 using supervised learning. We then collect a dataset of rankings of model outputs, which we use to further fine-tune this supervised model using reinforcement learning from human feedback.
- [Process for Adapting Language Models to Society (PALMS) with Values-Targeted Datasets](https://cdn.openai.com/palms.pdf): We found that fine-tuning on a small but curated dataset can help improve language model behavior and have a larger impact as model size increases. 
- [Identifying Mislabeled Data using the Area Under the Margin Ranking](https://arxiv.org/abs/2001.10528): Not all data in a typical training set help with generalization; some samples can be overly ambiguous or outrightly mislabeled. This paper introduces a new method to identify such samples and mitigate their impact when training neural networks. 
- [Gemini: A Family of Highly CapableMultimodal Models](https://arxiv.org/abs/2312.11805): Prior to training, we take various steps to mitigate potential downstream harms at the data curation and data collection stage.
- [A Survey on Data Selection for Language Models](https://arxiv.org/abs/2402.16827): We present a comprehensive review of existing literature on data selection methods and related research areas, providing a taxonomy of existing approaches. 
- [Beyond neural scaling laws: beating power law scaling via data pruning](https://proceedings.neurips.cc/paper_files/paper/2022/file/7b75da9b61eda40fa35453ee5d077df6-Paper-Conference.pdf):  Our work suggests that the discovery of good data-pruning metrics may provide a viable path forward to substantially improved neural scaling laws, thereby reducing the resource costs of modern deep learning.
- [A Decade's Battle on Dataset Bias: Are We There Yet?](https://arxiv.org/pdf/2403.08632.pdf): We observe that the datasets bias can still be easily captured by modern neural networks. This phenomenon is robust across models, dataset combinations, and many other settings.
- [MM1: Methods, Analysis & Insights from Multimodal LLM Pre-training](https://arxiv.org/pdf/2403.09611.pdf): Web-scale data is used while in the latter stage task-specific curated data is utilized.
- [When Scaling Meets LLM Finetuning: The Effect of Data, Model and Finetuning Method](https://arxiv.org/pdf/2402.17193v1.pdf): In this paper, we systematically studied the scaling for LLM finetuning, considering different factors including LLM model size, pretraining data size, finetuning data size, PET parameter size and diverse finetuning methods.
- [Do Generated Data Always Help Contrastive Learning？](https://github.com/PKU-ML/adainf): we find that the generated data (even from a good diffusion model like DDPM) may sometimes even harm contrastive learning.
- [Dataverse: Open-Source ETL (Extract, Transform, Load) Pipeline for Large Language Models](https://arxiv.org/pdf/2403.19340.pdf): A unified open-source Extract-Transform-Load (ETL) pipeline for large language models (LLMs) with a user-friendly design at its core.
### DataComp Related
- [DataComp: In search of the next generation of multimodal datasets](https://arxiv.org/abs/2304.14108): Participants in our benchmark design new filtering techniques or curate new data sources and then evaluate their new dataset by running our standardized CLIP training code and testing the resulting model on 38 downstream test sets. 
- [SIEVE: MULTIMODAL DATASET PRUNING USING IMAGE CAPTIONING MODELS](https://arxiv.org/abs/2310.02110): We propose a pruning method, SIEVE, that employs synthetic captions generated by image-captioning models pretrained on small, diverse, and well-aligned imagetext pairs to evaluate the alignment of noisy image-text pairs.
- [Improving Multimodal Datasets with Image Captioning](https://arxiv.org/abs/2307.10350): Our work focuses on caption quality as one major source of noise, and studies how generated captions can increase the utility of web-scraped datapoints with nondescript text. 
- [Quality over Quantity: Boosting Data Efficiency Through Ensembled Multimodal Data Curation](https://arxiv.org/abs/2502.08211): We introduce an advanced, learning-driven approach, Ensemble Curation Of DAta ThroUgh Multimodal Operators (EcoDatum), incorporating a novel quality-guided deduplication method to ensure balanced feature distributions.

## Blog
- [Thinking about High-Quality Human Data](https://lilianweng.github.io/posts/2024-02-05-human-data-quality/): High-quality data is the fuel for modern data deep learning model training.

## Video
- [Jeff Dean (Google): Exciting Trends in Machine Learning](https://youtu.be/oSCRZkSQ1CE?si=si2pH8hPxUm872rh&t=1874): Gemini Training Data

# Best Practices

## Autonomous Driving
- [Andrej Karpathy - AI for Full-Self Driving at Tesla](https://youtu.be/hx7BXih7zx8?si=13W7_rVHJhgYcLY3&t=660): Tesla's Data Engine.