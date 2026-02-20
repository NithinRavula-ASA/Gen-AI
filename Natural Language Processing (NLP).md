**NLP** is a field of Artificial Intelligence that enables computers to understand, interpret, and generate human language (text or speech).
It combines linguistics, computer science, and machine learning.

**How NLP Works**

Input – Receive text or speech

Preprocessing – Clean and tokenize text

Understanding – Analyze syntax and meaning

Model Processing – Predict or generate output

Output – Response, translation, summary, etc.

**Common NLP Tasks** : Text classification, Sentiment analysis, Named Entity Recognition (NER), Machine translation, Speech recognition, Text summarization

**Tokens & Tokenization**

A **token** is a small unit of text (word, subword, character, symbol).

**Example** : "AI is powerful" → ["AI", "is", "powerful"]

**Tokenization**

Converts text into tokens → token IDs → model processing.

Types

1) **Word Tokenization** : Splits text by spaces and punctuation.

Example : "ChatGPT is amazing!" → ["ChatGPT", "is", "amazing", "!"]

2) **Character Tokenization** : Splits into individual characters.
   
Example : "cat" → ["c", "a", "t"]

3) **Subword Tokenization** :  This is what modern language models use. Instead of whole words or single characters, text is broken into frequent word pieces.

Example : "unhappiness" → ["un", "happi", "ness"]

This helps with : Rare words, Misspellings, New words, Multiple languages

Popular subword algorithms include: Byte Pair Encoding (BPE), WordPiece, SentencePiece

**Why Tokens Matter**

--> Models measure limits in tokens

--> API cost is based on token count

--> Impacts performance and memory usage

**Embeddings**

Embeddings are numerical vector representations of data (text, image, audio) that capture meaning.

Example : "king" and "queen" → vectors close in mathematical space.

**How They Work**

Input → Convert to vector → Compare using similarity (e.g., cosine similarity)

Used In : Semantic search, Chatbots, Recommendation systems, Translation & summarization, Image recognition

Reference: https://docs.google.com/document/d/1xuz7QKTn-QfGLFh0eARA3-E2AV3n2a6AekTpQtCx_V0/edit?tab=t.k9o7zfkmsi2z
