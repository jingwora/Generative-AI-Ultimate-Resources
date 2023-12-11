## Tokenization

Tokenization is the process of breaking down a text or a sentence into smaller units called tokens. These tokens can be words, phrases, or even individual characters. Tokenization is an essential step in natural language processing (NLP) because it helps to transform unstructured text data into a structured format that can be analyzed and processed by computers.

---

1. Word-based Tokenization
2. Character-based Tokenization
3. Subword-based Tokenization
    - BPE (Byte Pair Encoding)
    - WordPiece
    - Unigram

## 1. Word-based Tokenization

- Breaking down a piece of text into individual words, where each word represents a separate token.
- Pros:
    - Simple and easy to implement
- Cons:
    - Not suitable for all languages (do not use spaces to separate words)
    - May not handle all types of words correctly. ("don't)
    - Huge dimensionality
- Library: spaCy, Moses

## 2. Character-based tokenization

- Breaking down a piece of text into individual characters, where each character represents a separate token.
- Pros:
    - Suitable for all languages
    - Can handle unusual or rare words
    - Can reduce the dimensionality of the data
- Cons:
    - Can lose some contextual information

## 3. Subword-based Tokenization

- Breaking down a piece of text into smaller units of meaning, known as subwords.
- Pros:
    - Can handle complex morphology
    - Can handle complex morphology
    - Can improve performance
- Cons:
    - May require additional preprocessing

### 3.1 BPE (Byte Pair Encoding)

- initially developed as an algorithm to compress texts
- Iteratively merging the most frequent pair of consecutive bytes or characters in a corpus until a predefined vocabulary size is reached.
- BPE relies on a pre-tokenizer that splits the training data into words.
- GPT, GPT-2, Roberta, XLM, BART, DeBERTa, FlauBERT
- GPT has a vocabulary size of 40,478 since they have 478 base characters and chose to stop training after 40,000 merges.
- Papaer: https://arxiv.org/abs/1508.07909
- Ref: https://huggingface.co/learn/nlp-course/chapter6/5?fw=pt

### 3.2 WordPiece

- Google developed to pretrain BERT
- Iteratively merging the most frequent pair by score (dividing the frequency of the pair by the product of the frequencies of each of its parts)
- The algorithm prioritizes the merging of pairs where the individual parts are less frequent in the vocabulary.
- WordPiece only saves the final vocabulary, not the merge rules learned.
- DistilBERT, MobileBERT

### 3.3 Unigram

- The Unigram algorithm is often used in SentencePiece
- SentencePiece uses a more efficient algorithm called Enhanced Suffix Array (ESA) to create the initial vocabulary.
- Starts from a big vocabulary and removes tokens from it until it reaches the desired vocabulary size.
- Iteratively remove the token that least impacts the loss
- Very costly operation
- AlBERT, mT5, mBART, Big Bird, and XLNet
- Ref: https://huggingface.co/learn/nlp-course/chapter6/7?fw=pt

https://colab.research.google.com/drive/195fDdYA-dfMYIRPbPEv3VvaJ-_cD5SKD?usp=sharing

## Normalizer

Lowercase: Description: Simply converts all text to lowercase.

NFC: Description: Normalizes text into NFC (Normalization Form C) Unicode format.

NFD: Description: Normalizes text into NFD (Normalization Form D) Unicode format.

NFKC: Description: Normalizes text into NFKC (Normalization Form KC) Unicode format.

NFKD: Description: Normalizes text into NFKD (Normalization Form KD) Unicode format.

Nmt: Description: NMT (Neural Machine Translation) normalizer, typically used in machine translation preprocessing.


