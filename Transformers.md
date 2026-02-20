**Transformers** are deep learning models designed to process sequential data (like text) using an attention mechanism.
They power most modern AI language systems.Transformers understand context by letting each word “look at” all other words in a sentence (self-attention).

**How Transformers Work**

1) **Input Embeddings** – Convert tokens into vectors

2) **Self-Attention** – Identify important word relationships

3) **Encoder / Decoder** – Process input and/or generate output

4) **Output Layer** – Produce prediction (text, label, translation)

Key Concept: Self-Attention

Each word considers all other words to understand meaning.

**Why Transformers?**

It Capture long-range context, Train in parallel (faster than older models), has High accuracy, Scale well to large datasets

**Types of Transformer Models**

1) Encoder-Only (Understanding)

--> Bidirectional attention

--> Best for classification & analysis

Example models: BERT, RoBERTa

Used for: Sentiment analysis, NER, question answering

2) Decoder-Only (Generation)

--> Causal (left-to-right) attention

--> Predicts next token step-by-step

Example models: GPT, LLaMA

Used for: Chatbots, text generation, code generation

3) Encoder–Decoder (Seq2Seq)

--> Encoder reads input

--> Decoder generates output with cross-attention

Example models: T5, BART

Used for: Translation, summarization

Reference : https://docs.google.com/document/d/1xuz7QKTn-QfGLFh0eARA3-E2AV3n2a6AekTpQtCx_V0/edit?tab=t.7nqj2ovpllpp

Used for: Translation, summarization
