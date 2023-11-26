# 日本での生成AIのまとめ

日本語のAIの最新の進歩、技術、応用例に特化し、洞察を共有するために捧げられています。AIが日本でどのようにカスタマイズされているかを探求し、最先端の研究や手法、実践的な応用例、市場動向まで、幅広い情報を提供します。

### 日本語LLM

| **サービス** | **開発者** | **特長** | モデル |ライセンス | **リング** |
|-----|-----|-----|-----|-----|-----|
| tsuzumi | NTT | 超軽量版 | 0.6B、7B |　- | [🌐](https://group.ntt/jp/magazine/blog/tsuzumi/) |
| calm2 | CyberAgent | 32,000トークン| 7B、7B-Chat [32,000] | Apache License 2.0 | [🌐](https://group.ntt/jp/magazine/blog/tsuzumi/)　[HF](https://huggingface.co/cyberagent) |
| Youri | rinna | Llama2のベース | 7B、base、Instruction、chat、gptq、… [4096] | LLAMA 2 Community License | [🌐](https://rinna.co.jp/news/2023/10/20231031.html)　[HF](https://huggingface.co/rinna) |
| Japanese Stable LM | Stability AI | Llama2のベース | 7B、70B、base、instruct、JA-Vocab、… [4096] | LLAMA 2 Community License | [🌐](https://ja.stability.ai/blog/japanese-stable-lm-beta)　[HF](https://huggingface.co/collections/stabilityai/japanese-stable-lm-654063a381a8731a1c0f13cc) |
| ELYZA | ELYZA | Llama2のベース | 7B、instruct、fast、[32000, 45043]… | LLAMA 2 Community License | [🌐](https://zenn.dev/elyza/articles/2fd451c944649d)　[HF](https://huggingface.co/elyza) |
| Stockmark | Stockmark | Llama2のベース、ビジネスドメインの対応 | 13B、[32000, 45043]… | MIT License | [🌐](https://weel.co.jp/media/stockmark-13b)　[HF](https://huggingface.co/stockmark/stockmark-13b) |

### LLM API

| **サービス** | **開発者** | **特長** | モデル |ライセンス | **リング** |
|-----|-----|-----|-----|-----|-----|
| OpenAI API | OpenAI | 一番強いモデル、日本語対応 | GPT-3.5 Turbo [4K、16k]（20B?）、gpt-4 [8K、32k]　(150B?)、 gpt-4 Turbo [128K] |　- | [🌐](https://group.ntt/jp/magazine/blog/tsuzumi/) |
| Claude | Anthropic | 最大トークン、日本語対応 | Claude2 [100k]、Claude2.1 [200k]|　- | [🌐](https://www.anthropic.com/index/claude-2) |
| PaLM-2  | Google | 日本語対応 |  PaLM-2[8K] |　- | [🌐](https://developers.generativeai.google/guide)|

----

### 埋め込み

| **サービス** | **開発者** | **特長** | モデル |ライセンス | **リング** |
|-----|-----|-----|-----|-----|-----|
| multilingual-e5 | intfloat |  JEE：0.832 | large、base、small、 [size=1024] |　MIT License​ | [🌐](https://group.ntt/jp/magazine/blog/tsuzumi/) |
| text-embedding-ada-002 | OpenAI |  JEE：0.768 |  [size=1536] |　- | [🌐](https://platform.openai.com/docs/guides/embeddings/what-are-embeddings) |


----

### モデル評価：
- Chatbot Areana Leaderboard [🌐](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard)  
- Hallucination Leaderboard [🌐](https://github.com/vectara/hallucination-leaderboard) 
- ＯpenLLM Leaderboard [🌐](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) 
- Massive Text Embedding Benchmark (MTEB) Leaderboard [🌐](https://huggingface.co/spaces/mteb/leaderboard) 
- JapaneseEmbeddingEval [🌐](https://github.com/oshizo/JapaneseEmbeddingEval) 
----

### サービス

| **サービス** | **開発者** | **特長** | **リング** |
|-----|-----|-----|-----|
| CoeFont (コエフォント) | - | 低コストのテキストツースピーチサービス | [🌐](https://esg.coefont.cloud/) |
| resumy | - | 職務経歴書作成サービス | [🌐](https://www.resumy.ai/) |

ビジネス活用
- 日立が生成AIで自動運転システム開発を効率化 [🌐](https://www.nikkei.com/article/DGXZQODB213K10R21C23A1000000/)
- ビズリーチ、生成AIで企業の求人票作成最短30秒 [🌐](https://www.nikkei.com/article/DGXZQOUC14CST0U3A111C2000000/)
- FORCAS、「AI企業課題サジェスト」機能に非上場企業約2万社追加 [🌐](https://furusato.press/2023/11/17/forcas%E3%80%81%E3%80%8Cai%E4%BC%81%E6%A5%AD%E8%AA%B2%E9%A1%8C%E3%82%B5%E3%82%B8%E3%82%A7%E3%82%B9%E3%83%88%E3%80%8D%E6%A9%9F%E8%83%BD%E3%81%AB%E9%9D%9E%E4%B8%8A%E5%A0%B4%E4%BC%81%E6%A5%AD%E7%B4%842/)

### 生成AI関連サービス

![img](https://d3kqjh0d0ujjwo.cloudfront.net/static/images/article/2082/2082_fig01.png)
