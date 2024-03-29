# LLM Datasets


## Table of Contents
- [Datasets](#datasets)
  - [Open Datasets for Pretraining](#open-datasets-for-pretraining)
  - [Domain-specific datasets and Private datasets](#domain-specific-datasets-and-private-datasets)
  - [General Open Access Datasets for Alignment](#general-open-access-datasets-for-alignment)
  - [Potential Overlap](#potential-overlap)
- [References](#references)


<br>



# Datasets
To download or access information about the most commonly used datasets: https://huggingface.co/datasets

## Open Datasets for Pretraining

- [falcon-refinedweb](https://huggingface.co/datasets/tiiuae/falcon-refinedweb)
- [Common Crawl](https://commoncrawl.org/)
- [nlp_Chinese_Corpus](https://github.com/brightmart/nlp_chinese_corpus)
- [The Pile (V1)](https://pile.eleuther.ai/)
- [Huggingface dataset for C4](https://huggingface.co/datasets/c4)
- [TensorFlow dataset for C4](https://www.tensorflow.org/datasets/catalog/c4)
- [ROOTS](https://huggingface.co/bigscience-data)
- [PushshPairs reddit](https://files.pushshPairs.io/reddit/)
- [Gutenberg project](https://www.gutenberg.org/policy/robot_access.html)
- [CLUECorpus](https://github.com/CLUEbenchmark/CLUE)


| Dataset                   | Description                                                                                          | Size        | Year     |
|---------------------------|------------------------------------------------------------------------------------------------------|-------------|----------|
| falcon-refinedweb         | Likely a web-crawled dataset for specific domains, details need to be verified.                      | Unknown     | Unknown  |
| Common Crawl              | A web-crawled dataset that contains petabytes of data collected over 10 years from the web.          | Petabytes   | Ongoing  |
| nlp_Chinese_Corpus        | A comprehensive dataset for Chinese natural language processing.                                     | Unknown     | Unknown  |
| The Pile (V1)             | A large-scale, diverse dataset designed for training language models, comprising various sources.   | 800GB+      | 2020/2021|
| Huggingface dataset for C4| Cleaned version of Common Crawl focusing on English language and cleaned for NLP training.           | Multi-TB    | Unknown  |
| TensorFlow dataset for C4 | TensorFlow's adaptation of the C4 dataset, cleaned and processed for machine learning.               | Multi-TB    | Unknown  |
| ROOTS                     | Details about this dataset are not clear; could refer to a specific domain dataset.                  | Unknown     | Unknown  |
| PushshiftPairs reddit     | A dataset derived from Reddit, often used for analyzing social media text and trends.                | Varies      | Ongoing  |
| Gutenberg project         | A collection of over 60,000 free eBooks, primarily used for NLP tasks involving literary texts.      | Over 60,000 books | Ongoing |
| CLUECorpus                | A large-scale Chinese language corpus for language understanding and generation tasks.               | Unknown     | Unknown  |
| Wikipedia                | A free online encyclopedia that anyone can edit.               | 16 GB+     | 2001-present  |

- C4 dataset contains about 13.5 billion sentences, of which 87.3% are in English.

## Domain-specific datasets and Private datasets

- [ChatGPT-Jailbreak-Prompts](https://huggingface.co/datasets/rubend18/ChatGPT-Jailbreak-Prompts)
- [awesome-chinese-legal-resources](https://github.com/pengxiao-song/awesome-chinese-legal-resources)
- [Long Form](https://github.com/akoksal/LongForm)
- [symbolic-instruction-tuning](https://huggingface.co/datasets/sail/symbolic-instruction-tuning)
- [Safety Prompt](https://github.com/thu-coai/Safety-Prompts)
- [Tapir-Cleaned](https://huggingface.co/datasets/MattiaL/tapir-cleaned-116k)
- [instructional_codesearchnet_python](https://huggingface.co/datasets/Nan-Do/instructional_codesearchnet_python)
- [finance-alpaca](https://huggingface.co/datasets/gbharti/finance-alpaca)
- WebText(Reddit links) - Private Dataset
- MassiveText - Private Dataset
- [Korean-Open-LLM-Datasets](https://github.com/dsdanielpark/Korean-Open-LLM-Datasets)

## General Open Access Datasets for Alignment
- [falcon-refinedweb](https://huggingface.co/datasets/tiiuae/falcon-refinedweb)
- [ultraChat](https://huggingface.co/datasets/stingning/ultrachat)
- [ShareGPT_Vicuna_unfiltered](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered)
- [pku-saferlhf-dataset](https://github.com/PKU-Alignment/safe-rlhf#pku-saferlhf-dataset)
- [RefGPT-Dataset](https://github.com/ziliwangnlp/RefGPT)
- [Luotuo-QA-A-CoQA-Chinese](https://huggingface.co/datasets/silk-road/Luotuo-QA-A-CoQA-Chinese)
- [Wizard-LM-Chinese-instruct-evol](https://huggingface.co/datasets/silk-road/Wizard-LM-Chinese-instruct-evol)
- [alpaca_chinese_dataset](https://github.com/hikariming/alpaca_chinese_dataset)
- [Zhihu-KOL](https://huggingface.co/datasets/wangrui6/Zhihu-KOL)
- [Alpaca-GPT-4_zh-cn](https://huggingface.co/datasets/shibing624/alpaca-zh)
- [Baize Dataset](https://github.com/project-baize/baize-chatbot/tree/main/data)
- [h2oai/h2ogpt-fortune2000-personalized](https://huggingface.co/datasets/h2oai/h2ogpt-fortune2000-personalized)
- [SHP](https://huggingface.co/datasets/stanfordnlp/SHP)
- [ELI5](https://huggingface.co/datasets/eli5#source-data)
- [evol_instruct_70k](https://huggingface.co/datasets/victor123/evol_instruct_70k)
- [MOSS SFT data](https://github.com/OpenLMLab/MOSS/tree/main/SFT_data)
- [ShareGPT52K](https://huggingface.co/datasets/RyokoAI/ShareGPT52K)
- [GPT-4all Dataset](https://huggingface.co/datasets/nomic-ai/gpt4all-j-prompt-generations)
- [COIG](https://huggingface.co/datasets/BAAI/COIG)
- [RedPajama-Data-1T](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T)
- [OpenAssistant Conversations Dataset (OASST1)](https://huggingface.co/datasets/OpenAssistant/oasst1)
- [Alpaca-COT](https://huggingface.co/datasets/QingyiSi/Alpaca-CoT)
- [CBook-150K](https://github.com/FudanNLPLAB/CBook-150K)
- [databricks-dolly-15k](https://github.com/databrickslabs/dolly/tree/master/data) ([possible zh-cn version](https://huggingface.co/datasets/jaja7744/dolly-15k-cn))
- [AlpacaDataCleaned](https://github.com/gururise/AlpacaDataCleaned)
- [GPT-4-LLM Dataset](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM)
- [GPTeacher](https://github.com/teknium1/GPTeacher)
- [HC3](https://github.com/Hello-SimpleAI/chatgpt-comparison-detection)
- [Alpaca data](https://github.com/tatsu-lab/stanford_alpaca#data-release) [Download](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)
- [OIG](https://huggingface.co/datasets/laion/OIG) [OIG-small-chip2](https://huggingface.co/datasets/0-hero/OIG-small-chip2)
- [ChatAlpaca data](https://github.com/cascip/ChatAlpaca)
- [InstructionWild](https://github.com/XueFuzhao/InstructionWild)
- [Firefly(流萤)](https://huggingface.co/datasets/YeungNLP/firefly-train-1.1M)
- [BELLE](https://github.com/LianjiaTech/BELLE) [0.5M version](https://huggingface.co/datasets/BelleGroup/train_0.5M_CN) [1M version](https://huggingface.co/datasets/BelleGroup/train_1M_CN) [2M version](https://huggingface.co/datasets/BelleGroup/train_2M_CN)
- [GuanacoDataset](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset#guanacodataset)
- [xP3 (and some variant)](https://huggingface.co/datasets/bigscience/xP3)
- [OpenAI WebGPT](https://huggingface.co/datasets/openai/webgpt_comparisons)
- [OpenAI Summarization Comparison](https://huggingface.co/datasets/openai/summarize_from_feedback)
- [Natural Instruction](https://instructions.apps.allenai.org/) [GitHub&Download](https://github.com/allenai/natural-instructions)
- [hh-rlhf](https://github.com/anthropics/hh-rlhf) [on Huggingface](https://huggingface.co/datasets/Anthropic/hh-rlhf)
- [OpenAI PRM800k](https://github.com/openai/prm800k)
  
## Potential Overlap
|                   | OIG     | hh-rlhf  | xP3     | Natural instruct | AlpacaDataCleaned | GPT-4-LLM | Alpaca-CoT |
|-------------------|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| OIG               | -       | Contains | Overlap | Overlap          | Overlap           |           | Overlap    |
| hh-rlhf           | Part of | -        |         |                  |                   |           | Overlap    |
| xP3               | Overlap |          | -       | Overlap          |                   |           | Overlap    |
| Natural instruct  | Overlap |          | Overlap | -                |                   |           | Overlap    |
| AlpacaDataCleaned | Overlap |          |         |                  | -                 | Overlap   | Overlap    |
| GPT-4-LLM         |         |          |         |                  | Overlap           | -         | Overlap    |
| Alpaca-CoT        | Overlap | Overlap  | Overlap | Overlap          | Overlap           | Overlap   | -         |


## References
- https://raw.githubusercontent.com/dsdanielpark/open-llm-datasets/main/README.md
