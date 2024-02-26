# Awesome-Data-Curation
This repository aims to compile a curated list of exceptional data curation ideas, tools, and more, designed to enhance machine learning scalability by providing better data. Additionally, this repository contains curation methods for Natural Language Processing, Computer Vision, and Multimodal Models. Inspired by [awesome-python](https://github.com/vinta/awesome-python) and originally created by [fasouto](https://github.com/fasouto).


# Tools
## One stop
- [Data-juicer](https://github.com/alibaba/data-juicer): Data-Juicer is a one-stop data processing system to make data higher-quality, juicier, and more digestible for LLMs.

## Cleaning
- [Cleanlab](https://github.com/cleanlab/cleanlab): Cleanlab helps you clean data and labels by automatically detecting issues in a ML dataset. 
- [Docta](https://github.com/Docta-ai/docta): Docta is an advanced data-centric AI platform that offers a comprehensive range of services aimed at detecting and rectifying issues in your data.

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

## Blog
- [Thinking about High-Quality Human Data](https://lilianweng.github.io/posts/2024-02-05-human-data-quality/): High-quality data is the fuel for modern data deep learning model training.

## Video
- [Jeff Dean (Google): Exciting Trends in Machine Learning](https://youtu.be/oSCRZkSQ1CE?si=si2pH8hPxUm872rh&t=1874): Gemini Training Data

# Best Practices

## Autonomous Driving
- [Andrej Karpathy - AI for Full-Self Driving at Tesla](https://youtu.be/hx7BXih7zx8?si=13W7_rVHJhgYcLY3&t=660): Tesla's Data Engine.