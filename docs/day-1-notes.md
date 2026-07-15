# Day 1 Notes

## Difference between AI, ML, DL and GenAI

![AI, ML, DL, Generative AI and LLMs hierarchy](./images/ai-ml-dl-genai.png)

These fields are nested — each one is a subset of the one outside it:

**Artificial Intelligence (AI) ⊃ Machine Learning (ML) ⊃ Deep Learning (DL) ⊃ Generative AI (GenAI) ⊃ LLMs**

---

### 1. Artificial Intelligence (AI)
- AI is the field of creating machines that can perform normally tasks that requires human intelligence.
- Includes reasoning, planning, perception, language, decision-making
- Can be rule-based (hard-coded logic) or data-driven
- **Examples:** chess engines, recommendation systems, voice assistants, fraud detection

---

### 2. Machine Learning (ML)

- A subset of AI
- Systems learn patterns from data instead of only following explicit rules
- Improves performance with more/better data and training
- Common types: supervised, unsupervised, reinforcement learning
- **Examples:** spam filters, house price prediction, customer churn models

---

### 3. Deep Learning (DL)

- A subset of ML
- Uses multi-layer neural networks (the “deep” part)
- Strong at complex, high-dimensional data: images, audio, text
- Needs large data and compute compared to classic ML
- **Examples:** image classification, speech recognition, object detection

---

### 4. Generative AI (GenAI)

- A subset of (mostly) deep learning
- Focuses on **creating** new content: text, images, audio, video, code
- Learns the distribution of training data, then generates new samples
- **Examples:** ChatGPT, DALL·E, Midjourney, music/code generators

---

### Quick comparison

| Field | What it is | Main idea | Example |
| --- | --- | --- | --- |
| **AI** | Broad umbrella | Make machines “smart” | Rule-based chatbot, game AI |
| **ML** | Subset of AI | Learn from data | Spam classifier |
| **DL** | Subset of ML | Deep neural networks | Face recognition |
| **GenAI** | Subset of DL (mostly) | Generate new content | Image/text generators |

---

### Key takeaway

- **All GenAI is not equally “just AI” in the casual sense** — GenAI sits inside DL → ML → AI
- **Not all AI is ML** (some AI is pure rules / logic)
- **Not all ML is DL** (classic ML like decision trees, SVM also counts)
- **Not all DL is GenAI** (many DL models only classify or predict, they don’t generate)
- **LLMs** (Large Language Models) are a popular type of GenAI focused on language
