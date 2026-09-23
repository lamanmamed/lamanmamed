<div align="center">

# Hi, I'm Laman 👋

### I build AI systems that work with messy, real-world information.

Medical measurements, language, images, retrieved evidence, dialogue history ... I like figuring out how to turn them into models that make useful decisions.

</div>

---

## A little about me

I'm an **MSc Artificial Intelligence graduate from Queen Mary University of London** with a background spanning **machine learning, data science, and cybersecurity**.

The projects I enjoy most sit somewhere between research and engineering: there is a real problem, several possible modelling choices, and enough uncertainty that the interesting part is not just training a model but understanding **why it works, when it fails, and what information it relies on**.

Right now, the themes that keep showing up in my work are:

🧠 **AI for healthcare** — multimodal prediction and uncertainty in Alzheimer's disease progression  
💬 **Language & dialogue** — NLP, retrieval, conversational agents, speech, and text generation  
👁️ **Multimodal AI** — models that connect images and language  
🔎 **Retrieval & evidence** — finding the right information before asking a model to reason over it  
🧩 **Learning + reasoning** — reinforcement learning, graph search, planning, and neuro-symbolic systems

---

## Projects I'd show you first

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [MCI prognosis with multimodal AI](https://github.com/lamanmamed/adni-mci-prognosis)

Predicting 36-month progression from Mild Cognitive Impairment using cognitive, biomarker, demographic, and imaging data.

The project combines two modelling paths and explicitly tracks **predictive uncertainty and evidence conflict**, rather than treating every prediction as equally reliable.

**Best ROC AUC: 0.918**

</td>
<td width="50%" valign="top">

### 👁️ [Multimodal VQA with LLaVA](https://github.com/lamanmamed/multimodal-vqa-with-llava)

A custom vision-language model for answering multiple-choice questions about images.

I connected **LongCLIP** image features to **Qwen3** with a learned projector and adapted the language model with **LoRA**.

**Validation accuracy: 69.09%**

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔬 [SciFact claim verification](https://github.com/lamanmamed/scifact-claim-verification)

A pipeline that checks scientific claims against research abstracts.

It combines **BM25 + dense retrieval**, query rewriting, **BGE reranking**, SpanBERT evidence extraction, and LLM verdict generation.

**Hybrid retrieval Recall@20: 0.9279**

</td>
<td width="50%" valign="top">

### 💬 [Text dialogue agents](https://github.com/lamanmamed/text-dialogue-agents)

Conversational AI experiments covering dialogue-act recognition, response generation, RAG, tool use, and LLM fine-tuning.

Includes a restaurant agent that performs structured bookings and orders instead of inventing backend results.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🗣️ [Speech & visual dialogue agents](https://github.com/lamanmamed/speech-and-visual-dialogue-agents)

Dialogue systems for speech recognition, clarification, next-speaker prediction, and visual guessing.

Includes **Whisper**, a hierarchical **BiLSTM**, and a visual Questioner/Oracle setup with **Qwen + LoRA**.

</td>
<td width="50%" valign="top">

### 🧩 [Neuro-symbolic planning](https://github.com/lamanmamed/neuro-symbolic-planning)

A pipeline that connects image recognition and learned semantic representations to symbolic planning.

A predicted object is grounded into a **PDDL** problem, then heuristic search finds a sequence of actions that reaches the goal.

</td>
</tr>
</table>

---

## More things I've built

- 🎮 [Reinforcement learning on FrozenLake & MiniGrid](https://github.com/lamanmamed/reinforcement-learning-frozenlake-minigrid) — dynamic programming, tabular control, recurrent PPO, reward shaping, and transfer learning
- 🧠 [NLP from LSTMs to Transformers](https://github.com/lamanmamed/nlp-from-lstm-to-transformers) — translation, sentiment analysis, GPT-2 generation, humour prediction, and T5 summarization
- 🔍 [Character dialogue retrieval](https://github.com/lamanmamed/character-dialogue-retrieval) — identifying speakers from dialogue with TF-IDF and cosine similarity
- 💭 [Tweet sentiment classification](https://github.com/lamanmamed/tweet-sentiment-classification) — SVM classification with progressively stronger text preprocessing and feature engineering
- 🕸️ [Graph search & heuristics](https://github.com/lamanmamed/graph-search-and-heuristics) — constrained search and generation over a word-adjacency graph
- 📐 [Machine learning foundations](https://github.com/lamanmamed/machine-learning-foundations) — regression, classification, neural networks, and Gaussian mixture models implemented from scratch

---

## What I work with

**Languages**  
`Python` `SQL`

**Machine learning**  
`PyTorch` `scikit-learn` `Transformers` `LoRA` `Reinforcement Learning` `Multimodal Learning`

**NLP & retrieval**  
`Hugging Face` `RAG` `BM25` `Dense Retrieval` `Cross-Encoders` `Whisper` `T5` `GPT-2`

**Research & engineering**  
`Experiment Design` `Model Evaluation` `Uncertainty` `Git` `Linux` `LaTeX`

---

## The thread through my work

I started closer to **cybersecurity and classical machine learning**, then moved deeper into NLP, multimodal learning, agents, and research.

What I keep coming back to is the same question:

> **How do you build an AI system you can actually understand and trust when the input is incomplete, noisy, or ambiguous?**

That is why my projects range from uncertainty-aware medical prediction to clarification in dialogue agents, evidence retrieval for scientific claims, and models that have to connect language with images.

---

## Outside the model

I also like **songwriting, fiction, film, education, and the way language carries emotion**.

So yes, there is a reasonable chance I'll spend the afternoon debugging a transformer and the evening thinking about why one line in a novel works so well.

---

<div align="center">

**Thanks for stopping by ✨**

[Explore my repositories](https://github.com/lamanmamed?tab=repositories)

</div>
