# Prompt engineering master

"Prompt engineering master" is a comprehensive repository dedicated to advanced methodologies and techniques in the realm of prompt engineering. Moving beyond the basics, this resource delves deep into the intricacies of crafting, refining, and optimizing prompts for various applications.


### Openai
- Best practices for prompt engineering [🌐](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
- Prompt engineering guides [🌐](https://platform.openai.com/docs/guides/prompt-engineering)
- Production best practices [🌐](https://platform.openai.com/docs/guides/production-best-practices)
- Safety best practices [🌐](https://platform.openai.com/docs/guides/safety-best-practices)
- Prompt examples [🌐](https://platform.openai.com/examples)

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

## Zero-shot prompting
Zero-shot prompting enables a machine learning model to tackle new tasks without extra training, by using detailed instructions provided in the input.

```
prompt = """Classify the text into neutral, negative or positive. 
Text: I think the vacation is great.
Sentiment:"""
```
```
Response = "Sentiment: Positive"
```

## Few-shot prompting

Resources:
- https://learnprompting.org/docs/category/-applied-prompting
