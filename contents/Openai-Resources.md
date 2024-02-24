
## OpenAI Tech Stack

<img src="https://github.com/jingwora/Generative-AI-Ultimate-Resources/blob/main/images/Openai-Resources/OpenAI-tech-stack.png?raw=true" width="900"/>

- GPT3/4: Large language model  [Doc](https://platform.openai.com/docs/guides/text-generation)
- DALL-E4: Text-to-Image Model  [Doc](https://platform.openai.com/docs/models/dall-e)
- TTS: Text-to-Speech API  [Doc](https://platform.openai.com/docs/models/tts)
- GPT-4V: Image-to-Text Model  [Doc](https://platform.openai.com/docs/guides/vision)
- Whisper: Speech-to-Text  [Doc](https://platform.openai.com/docs/models/whisper)
- Embedding: To convert text to contextual semantic meaning value  [Doc](https://platform.openai.com/docs/models/embeddings)
- Moderation: Filters harmful content, adheres to ethical guidelines. [Doc](https://platform.openai.com/docs/guides/moderation)
- Assistants API: Build AI assistants within your own applications. [Doc](https://platform.openai.com/docs/assistants/overview/agents)
- GPTs:  Create custom versions of ChatGPT. [Doc](https://platform.openai.com/docs/plugins/introduction)


## Completion API vs Assistant API
| **Completion API** | **Asistant API** |
|-----|-----|
| GPT | GPT | 
| - | Persistent threading (Save history & context) | 
| - | Upload files for knowledge-base | 
| - | Code Interpreter | 
| - | Function Calling | 


 ## GPT version summary (2024/02)
| Model ID                           |                                 | Max Input tokens | Max Output tokens | Training Data<br> (up to) | Input (Per 1,000 tokens) | Output (Per 1,000 tokens) |
| ---------------------------------- | ------------------------------- | ---------------- | ----------------- | ------------------------- | ------------------------ | ------------------------- |
| gpt-4 (0314)                       |                                 | 8,192            |                   | 2021年9月                   |                          |                           |
| gpt-4-32k(0314)                    |                                 | 32,768           |                   | 2021年9月                   |                          |                           |
| gpt-4 (0613)                       |                                 | 8,192            |                   | 2021年9月                   | ¥4.431                   | ¥8.861                    |
| gpt-4-32k (0613)                   |                                 | 32,768           |                   | 2021年9月                   | ¥8.861                   | ¥17.721                   |
| gpt-4 (1106-preview)               | GPT-4 Turbo Preview             | 128,000          | 4,096             | 2023年4月                   | ¥1.477                   | ¥4.431                    |
| gpt-4 (0125-preview)               | GPT-4 Turbo Preview             | 128,000          | 4,096             | 2023年12月                  | ¥1.477                   | ¥4.431                    |
| gpt-4 (vision-preview)             | GPT-4 Turbo with Vision Preview | 128,000          | 4,096             | 2023年4月                   | ¥1.477                   | ¥4.431                    |
|                                    |                                 |                  |                   |                           |                          |                           |
| gpt-35-turbo1 (0301)               |                                 | 4,096            |                   | 2021年9月                   |                          |                           |
| gpt-35-turbo (0613)                |                                 | 4,096            |                   | 2021年9月                   | ¥0.2134                  | ¥0.2845                   |
| gpt-35-turbo-16k (0613)            |                                 | 16,384           |                   | 2021年9月                   | ¥0.427                   | ¥0.569                    |
| gpt-35-turbo-instruct (0914)       |                                 | 4,097            |                   | 2021年9月                   | ¥0.2216                  | ¥0.296                    |
| gpt-35-turbo (1106)                |                                 | 16,385           | 4,096             | 2021年9月                   | ¥0.0739                  | ¥0.2216                   |
| gpt-35-turbo (0125)                |                                 | 16,385           |                   | 2021年9月                   | ¥0.0739                  | ¥0.2216                   |
|                                    |                                 |                  |                   |                           |                          |                           |
| Model ID                           |                                 | Max Input tokens | Max Output tokens | Training Data<br> (up to) | 価格 (1,000 トークンあたり)       |                           |
| text-embedding-ada-002 (version 1) |                                 | 2,046            | 1,536             | 2021年9月                   | ¥0.014768                |                           |
| text-embedding-ada-002 (version 2) |                                 | 8,191            | 1,536             | 2021年9月                   | ¥0.014768                |                           |
| text-embedding-3-small             |                                 | 8,191            | 1,536             | 2021年9月                   | ¥0.002954                |                           |
| text-embedding-3-large             |                                 | 8,191            | 3,072             | 2021年9月                   | ¥0.019198                |                           |
|                                    |                                 |                  |                   |                           |                          |                           |
| Model ID                           |                                 | Max Input tokens | Max Output tokens | Training Data<br> (up to) | 価格 (画像 100 件あたり)         |                           |
| dalle3                             | 標準 1024 \* 1024                 | 4,000            |                   |                           | ¥590                     |                           |
|                                    | 標準 1024 \* 1792, 1792 \* 1024   | 4,000            |                   |                           | ¥1,181                   |                           |
|                                    | HD 1024 \* 1024                 | 4,000            |                   |                           | ¥1,181                   |                           |
|                                    | HD  1024 \* 1792, 1792 \* 1024  | 4,000            |                   |                           | ¥1,772                   |                           |

## GPTs:

- customgpts: [🌐](https://customgpts.org/)


## GPTのパラメータ

Top P
Top Pは出力の確率が高い順にソートした際の、上位何％までの出力を回答候補として考慮するかを定めるパラメータである。
Top Pの値を低く設定すると、選ばれる回答候補が少なくなり、結果として出力の回答が一貫性を持つようになる。

Temperature
Temperatureはモデルが出力する確率分布の形を調節するパラメータである。
Temperatureの値を低く設定すると、出力間の確率の差が大きくなり、逆に値を高く設定すると、出力間の確率の差が小さくなる。
ゆえに、Temperatureの値を低くすることで、高い確率の出力が選ばれやすくなり、回答の一貫性が高まる。

presence_penalty
2.0 から 2.0 の間の数値。正の値は、新しいトークンがこれまでにテキストに現れたかどうかに基づいてペナルティを課し、モデルが新しいトピックについて話す可能性を高める。

frequency_penalty
2.0から2.0の間の数値。正の値は、新しいトークンに、これまでのテキストにおける既存の頻度に基づいてペナルティを与え、モデルが同じ行を逐語的に繰り返す可能性を低下させる。

両方ともトークンの繰り返しを抑制するペナルティ。
何が違うかよくわからない。
