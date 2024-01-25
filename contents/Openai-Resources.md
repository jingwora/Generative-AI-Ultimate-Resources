
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


# Completion API vs Assistant API
| **Completion API** | **Asistant API** |
|-----|-----|
| GPT | GPT | 
| - | Persistent threading (Save history & context) | 
| - | Upload files for knowledge-base | 
| - | Code Interpreter | 
| - | Function Calling | 


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
