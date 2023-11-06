# 日本でのAI

日本でのAIは、日本語のAIの最新の進歩、技術、応用例に特化し、洞察を共有するために捧げられています。AIが日本でどのようにカスタマイズされているかを探求し、最先端の研究や手法、実践的な応用例、市場動向まで、幅広い情報を提供します。

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
| GPT3.5, GPT-4 | OpenAI | 一番強いモデル、日本語対応 | GPT-3.5 Turbo [4K、16k]（20B?）、gpt-4 [8K、32k]　(150B?) |　- | [🌐](https://group.ntt/jp/magazine/blog/tsuzumi/) |
| Claude | Anthropic | 最大トークン、日本語対応 | [100k] |　- | [🌐](https://www.anthropic.com/index/claude-2) |

----

### 埋め込み

| **サービス** | **開発者** | **特長** | モデル |ライセンス | **リング** |
|-----|-----|-----|-----|-----|-----|
| multilingual-e5 | intfloat |  JEE：0.832 | large、base、small、 [size=1024] |　MIT License​ | [🌐](https://group.ntt/jp/magazine/blog/tsuzumi/) |
| text-embedding-ada-002 | OpenAI |  JEE：0.768 |  [size=1536] |　- | [🌐](https://platform.openai.com/docs/guides/embeddings/what-are-embeddings) |

日本語の埋め込みの評価：
- JapaneseEmbeddingEval
  - JSTS valid-v1.1、JSICK、MIRACL	
  - [Github](https://github.com/oshizo/JapaneseEmbeddingEval) 


### サービス

| **サービス** | **開発者** | **特長** | **リング** |
|-----|-----|-----|-----|
| CoeFont (コエフォント) | - | 低コストのテキストツースピーチサービス | [🌐](https://esg.coefont.cloud/) |
| resumy | - | 職務経歴書作成サービス | [🌐](https://www.resumy.ai/) |
