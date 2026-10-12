# Term 1: Foundations

This folder contains my notes and projects for the first term, focusing on the fundamental concepts of AI, Machine Learning, Deep Learning, and Neural Networks.

---

## Week 1: Roadmap, Fundamental Concepts, and the Role of an AI Engineer
**Status:** Completed ✅

### 🎯 Weekly Goals
* Differentiate between Artificial Intelligence (AI), Machine Learning (ML), Deep Learning (DL), and Generative AI.
* Understand the 15-year AI timeline (from Deep Neural Networks to Transformers and Reasoning models).
* Distinguish the "AI Engineer" role from ML Engineer and Data Scientist, and understand the AI engineering stack.
* Identify major industry players (OpenAI, Anthropic, Google DeepMind, Meta, Mistral, DeepSeek, Alibaba) and understand Closed vs. Open-weight models.
* Set up essential tools and practice using LLMs (Claude/ChatGPT) as personalized tutors.

### 📝 Study Notes

**1. Core Definitions (AI vs. ML vs. DL)**
* **Artificial Intelligence (AI):** The broadest concept of machines performing tasks requiring human intelligence (ranging from 1990s rule-based chess engines to modern models like Claude).
* **Machine Learning (ML):** A subset of AI where systems learn patterns from data instead of relying on hard-coded rules.
  * *Supervised Learning:* Learning from labeled data.
  * *Unsupervised Learning:* Finding hidden structures in unlabeled data.
  * *Reinforcement Learning (RL):* Learning via trial, error, and rewards.
* **Deep Learning (DL):** A subset of ML using multi-layered Neural Networks.
  * **Training vs. Inference:** *Training* is the computationally expensive process of adjusting weights using GPUs. *Inference* is using the trained model to generate a response. AI Engineers primarily deal with Inference.

**2. The 15-Year AI Timeline**
* **2012 (AlexNet):** Deep learning dominates computer vision; GPUs become the standard tool.
* **2013 (word2vec):** Words are converted into vectors; the birth of embeddings.
* **2017 (Attention Is All You Need):** The Transformer architecture is introduced.
* **2018 (GPT-1 & BERT):** Pre-training on massive text followed by fine-tuning.
* **2020 (GPT-3):** Scaling laws emerge. "In-context learning" becomes viable.
* **2022 (InstructGPT & ChatGPT):** Instruction tuning and RLHF turn text-predictors into helpful assistants.
* **2023:** Multimodal models and Open-weight models (Llama, Mistral) emerge. The "AI Engineer" role takes shape.
* **2024:** Massive context windows, Reasoning models (o1), and Claude's "Computer Use".
* **2025-2026:** The era of Agents (Claude Code, Codex) and MCP protocol.

**3. Generative AI & Foundation Models**
* **Generative AI:** Models that generate novel content (text, image, audio, video, code). 
* **Foundation Models:** Massive models trained once that can be adapted for thousands of different tasks using just a *Prompt*.

**4. Neural Networks Under the Hood (3Blue1Brown Notes)**
* **The Neuron:** Computes a weighted sum of its inputs, adds a bias, and passes the result through an activation function. `Activation = function((Weights × Inputs) + Bias)`
* **Activation Functions:** (e.g., Sigmoid, ReLU) Introduce *non-linearity*. Without them, a deep network would just be a linear equation.
* **Parameters:** The **Weights and Biases** are what the network "learns" and stores.
* **Cost/Loss Function:** Measures how "wrong" the network's predictions are. The goal is to minimize this number.
* **Gradient Descent & Backpropagation:** 
  * The **Gradient** is a vector showing the direction of the steepest *increase* in cost.
  * To learn, the network takes a small step (Learning Rate) in the *opposite* direction.
  * **Backpropagation** is the algorithm used to calculate these gradients.