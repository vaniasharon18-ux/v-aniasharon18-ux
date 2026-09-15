# AI & Machine Learning Notes

Notes from Coding Club class session on Generative AI, LLMs, and Machine Learning.

---
## 1. Generative AI

Generative AI is a type of artificial intelligence that can **create new content**. Instead of just analyzing existing data, it generates something new based on patterns it has learned.

AI → ML → Generative AI → Agentic AI

### Examples of What It Can Generate

- **Text** (essays, code, conversations) — e.g., ChatGPT, Claude
- **Images** — e.g., DALL-E, Midjourney
- **Audio/Music**
- **Video**

### How It Works (Simple Idea)

These models are trained on huge amounts of existing data such as text, images, and other information. By studying patterns in that data, they learn to produce new content that resembles what they were trained on.

For a given sentence, the text is first converted into **tokens**, which are numerical representations used by the model. The model then processes these tokens and generates an output. This process is called **tokenization**.

Some AI tools also have limitations on the number of tokens or files that can be uploaded.

### Real-World Use Cases

- Writing assistance
- Chatbots
- Image generation
- Code generation
- Customer support automation

---

## 2. Large Language Models (LLMs)

An LLM is a specific type of generative AI model that is trained primarily on text data to understand and generate human-like language.

Simply, an LLM can generate and understand textual conversations.

### How They Work (Simplified)

- They are trained on massive amounts of text from books, websites, articles, etc.
- They learn to predict the next **word (or "token")** in a sentence based on everything that came before it.
- By doing this repeatedly at a huge scale, they learn grammar, facts, reasoning patterns, and conversational styles.

### Examples of LLMs

- GPT (used in ChatGPT)
- Claude
- Gemini
- LLaMA

### What They're Used For

- Answering questions
- Summarizing text
- Writing content
- Coding assistance
- Translation
- And much more

---

## 2.1 Diffusion Models

A **diffusion model** is a type of generative AI model mainly used to generate images, and increasingly audio and video, by learning to gradually build a clear output from random noise.

It is different from an LLM. LLMs are mainly designed for text, whereas diffusion models can be used for generating images, audio, video, and other types of content.

### How They Work (Simplified)

- During training, the model is shown real images with random **noise** (similar to static) added to them in small steps until the image becomes almost pure noise.
- The model learns how to reverse this process by removing a small amount of noise at each step.
- Once trained, to generate a new image, the model starts with pure random noise and repeatedly removes noise step by step, guided by a text prompt, until a clear image is formed.

### Simple Analogy

A diffusion model is like a sculptor starting with a rough, shapeless block (random noise) and slowly removing the excess material until a clear statue (final image) appears, guided by a description of what to create.

### Examples of Diffusion Models

- DALL-E
- Midjourney
- Stable Diffusion

### What They're Used For

- Text-to-image generation
- Image editing
- Inpainting
- Video generation
- Audio generation

---

# Algorithms in AI/Machine Learning

An **algorithm** is a step-by-step set of rules or instructions that a computer follows to solve a problem or complete a task.

In AI and machine learning, algorithms are the core logic that allows a system to learn patterns from data, make predictions, or make decisions without being explicitly programmed for every scenario.

### Common Types Include

- **Supervised learning algorithms** — e.g., linear regression, decision trees, Naive Bayes; learn from labeled data.
- **Unsupervised learning algorithms** — e.g., k-means clustering; find patterns in unlabeled data.
- **Reinforcement learning algorithms** — e.g., Q-learning; learn through trial, error, and reward.
- **Neural networks / deep learning algorithms** — model complex patterns using layered structures inspired by the brain.

---

# 3. Types of Machine Learning

Machine Learning (ML) is the broader field that focuses on teaching computers to learn patterns from data instead of being explicitly programmed with rules.

There are three main types:

## a) Supervised Learning

The model learns from **labeled data**, meaning each training example has a known correct answer.

Here, we provide both the input and the expected output to the machine.

### Example

Giving the model past house prices along with details such as size and location, so it can learn to predict the price of a new house.

### Common Uses

- Spam detection
- Price prediction
- Image classification

---

## b) Unsupervised Learning

The model works with **unlabeled data**. There is no "correct answer" provided.

It tries to find hidden patterns or groupings in the data on its own.

Here, we provide only the input, and the model finds patterns and produces useful outputs.

### Example

Grouping customers into different segments based on shopping behavior without being told the groups in advance.

### Common Uses

- Customer segmentation
- Anomaly detection
- Recommendation systems

---

## c) Reinforcement Learning

The model learns through **trial and error**, receiving rewards for good actions and penalties for bad ones. It gradually improves its strategy over time.

In reinforcement learning, an **agent interacts with an environment** and receives rewards or penalties based on its actions.

### Examples

- An AI learning to play a game by playing it repeatedly and getting better with each attempt.
- A dog performs an action such as sitting, and the environment (for example, a person) gives it a reward such as a treat when it performs the action correctly.

### Common Uses

- Game-playing AI
- Robotics
- Self-driving car decision-making
