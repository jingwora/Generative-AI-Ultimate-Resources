# Prompt engineering master

"Prompt engineering master" is a comprehensive repository dedicated to advanced methodologies and techniques in the realm of prompt engineering. Moving beyond the basics, this resource delves deep into the intricacies of crafting, refining, and optimizing prompts for various applications.


### Openai
- Best practices for prompt engineering [🌐](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
- Prompt engineering guides [🌐](https://platform.openai.com/docs/guides/prompt-engineering)
- Production best practices [🌐](https://platform.openai.com/docs/guides/production-best-practices)
- Safety best practices [🌐](https://platform.openai.com/docs/guides/safety-best-practices)
- Prompt examples [🌐](https://platform.openai.com/examples)
- Applied-prompting [🌐](https://learnprompting.org/docs/category/-applied-prompting)


## Prompt engineering techniques

- Prompting based on Example
  - [Zero-shot prompting](https://github.com/jingwora/Generative-AI-Ultimate-Resources/blob/main/contents/Prompt-engineering-master.md#zero-shot-prompting)
  - [Few-shot prompting](https://github.com/jingwora/Generative-AI-Ultimate-Resources/blob/main/contents/Prompt-engineering-master.md#few-shot-prompting)
  - Few-shot Chain of Thoughts
  - Zero-shot Chain of Thoughts (step by step)

- Chain of Thoughts
  - Chain of Thoughts(CoT)
  - Automatice Chain of Thought
  - Tree of Thoughts(ToT)
  - Graph of Thoughts(GoT)

- Enhanced and Automated
  - Self-Consistency
  - Automatic Prompt Engineer (APE)
  - Generated Knowledge Prompting
  - Metacognitive Prompting(MP)

- Interaction and Reasoning
  - Retrieval Augmented Generation(RAG)
  - ReAct Prompting
  - Multimodel COT
  - Automatic Reasoning and Tool-use (ART)
  - Algorithm of Thoughts(AoT)

- Others
  - Take a Deep Breath
  - Take a Step Back
  - Chain of Verification(CoVe)
  - Self-translate
  - Chain of density(CoD)
  - EchoPrompt
  - Inferential Exclusion Prompting(IEP)

- New Technique
  - EmotionPrompt:  improve both truthfulness, informativeness and performance.
  - Example: This is very important to my career. You'd better to be sure. | Believe in your abiliteis and strive for the excellence.
  - [Website](https://llm-enhance.github.io/)


## Frameworks

| #  | Framework  | Strengths                                                                                                                    | Weaknesses                                                                                               | Ideal Use Cases                                                                                         |
|----|------------|------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| 1. | [**LangChain**](https://python.langchain.com/docs/get_started/introduction) | - Flexibility and Extensibility: Customizable, modular architecture. <br> - Scalability: Efficient for large datasets. <br> - Open Source: Encourages collaboration. | - Steeper Learning Curve: Requires deeper NLP knowledge. <br> - Less User-Friendly: Complex setup and management. | - Research Projects: For cutting-edge NLP experimentation. <br> - High-Performance Applications: For dialogue generation, content creation, etc. |
| 2. | [**LlamaIndex**](https://docs.llamaindex.ai/en/stable/) | - Streamlined Search: Efficient data retrieval. <br> - Ease of Use: Simple API and intuitive interface. <br> - Integration with Hugging Face: Seamless model and dataset integration. | - Limited Functionality: Focused on data retrieval. <br> - Black Box Nature: Less transparency for fine-tuning. | - Information Retrieval: For question answering, summarization. <br> - Personalization: For content generation based on user preferences. |
| 3. | [**Haystack**](https://github.com/deepset-ai/haystack)   | - Comprehensive NLP Pipeline: Supports various NLP tasks. <br> - Flexibility and Customization: Tailorable pipeline. <br> - Open Source: Community-driven development. | - Complex Setup: Requires more configuration. <br> - Resource Intensive: High computational demands. | - Information Extraction: From large datasets. <br> - Question Answering: For advanced chatbots and assistants. <br> - Sentiment Analysis: For text data analysis. |
| 4. | [**Hugging Face**](https://huggingface.co/)  | - Rich Model Repository: Access to many models. <br> - User-Friendly Platform: Easy model training and deployment. <br> - Collaborative Development: Promotes sharing and collaboration. | - Limited Functionality: Focused on model training and evaluation. <br> - Cost: Some features are paid. | - Model Training and Fine-tuning: For specific tasks. <br> - Model Evaluation: For performance optimization. <br> - Collaborative Research: To share and accelerate progress. |

## Tools

| Name                   | Description                                                                                                      | URL                                  |
|------------------------|------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| **Promptify**          | A tool for solving NLP problems using LLMs, facilitating prompt generation for models like GPT, PaLM, etc.       | [Doc](https://promptify.readthedocs.io/en/latest/)             |
| **Arize-Phoenix**      | An open-source ML observability tool for notebook environments, aiding in monitoring and tuning various models. | [Doc](https://docs.arize.com/phoenix)     |
| **Better Prompt**      | A testing suite for evaluating LLM prompts before production deployment.                                        | [Github](https://github.com/krrishdholakia/betterprompt)      |
| **CometLLM**           | A tool to log, visualize, and evaluate aspects of LLM prompts and their variables.                              | [Github](https://github.com/comet-ml/comet-llm)               |
| **Embedchain**         | A framework for creating ChatGPT-like bots using specific datasets.                                             | [Github](https://github.com/embedchain/embedchain)           |
| **Interactive Composition Explorer** | ICE: A Python library with a trace visualizer for language model programming.                            | [Github](https://github.com/oughtinc/ice) |
| **OpenPrompt**         | An open-source framework designed for prompt-learning.                                                           | [Github](https://github.com/thunlp/OpenPrompt)           |
| **Prompt Engine**      | A utility library for creating and maintaining LLM prompts, available as an NPM package.                         | [Github](https://github.com/microsoft/prompt-engine)      |
| **PromptInject**       | A modular framework for assembling prompts and analyzing LLM robustness against adversarial prompt attacks.      | [Github](https://github.com/agencyenterprise/PromptInject)       |
| **Prompts AI**         | An advanced playground for experimenting with GPT-3.                                                            | [Github](https://github.com/sevazhidkov/prompts-ai)            |
| **Prompt Source**      | A toolkit for creating, sharing, and using natural language prompts.                                             | [Github](https://github.com/bigscience-workshop/promptsource)      |
| **ThoughtSource**      | A framework dedicated to the science of machine thinking.                                                        | [Github](https://github.com/OpenBioLink/ThoughtSource)     |
| **PROMPTMETHEUS**      | A toolkit for one-shot prompt engineering.                                                                       | [Link](https://promptmetheus.com/)                 |
| **AI Config**          | A configuration-based framework for building applications with LLMs.                                             | [Github](https://github.com/lastmile-ai/aiconfig)              |
| **LastMile AI**        | A notebook-like interface for interacting with LLMs across text, speech, audio, and image modalities.            | [Link](https://lastmileai.dev/)                      |


