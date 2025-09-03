# Gen-Ai-LLM-assignments
This repository is a collection of assignments and projects focused on the foundations of Generative AI and Language Models. It serves as a practical guide to understanding and implementing key concepts in this rapidly evolving field.

### Introduction to Generative AI

Generative AI is a type of artificial intelligence that can **create new content, such as text, images, music, and code**. It differs from traditional AI, which is typically used for classification, prediction, or analysis of existing data. For example, a traditional AI might be used to identify a cat in a photo, while a generative AI could create a completely new image of a cat.

#### **Key Concepts**
* **Prompt-based generation:** Generative AI models often work by taking a **"prompt"** (a text command or a reference image) as input and generating new content based on that instruction.
* **Large Language Models (LLMs):** A significant part of generative AI, these models are trained on vast amounts of text data to understand language patterns and generate human-like text.
* **Use Cases:** Generative AI has a wide range of applications, including writing articles, creating realistic images, composing music, and generating computer code.

### Language Modeling Fundamentals

Language modeling is the task of predicting the next word in a sequence. It's the core technology that enables generative AI to create coherent and contextually relevant text.

#### **Statistical vs. Neural Language Models**
* **Statistical Language Models (e.g., N-grams):** These models predict the next word based on the probability of a sequence of words appearing together in the training data. For example, a **3-gram** model predicts the next word based on the two words that came before it.
* **Neural Language Models:** These models use neural networks to learn more complex patterns and context from the data, which allows them to make more accurate and sophisticated predictions than statistical models.

#### **Training Objectives**
* **Causal Language Modeling:** The model is trained to predict the next token in a sequence given all the previous tokens. This is the **primary training objective for models like GPT**.
* **Masked Language Modeling:** The model is trained to predict a missing or "masked" token in a sequence, taking into account the context from both the left and right sides. This is the **training objective for models like BERT**.

### Emergence of LLMs

The development of LLMs is a result of several key breakthroughs in the field of natural language processing (NLP).

#### **History and Evolution**
* **Word2Vec:** An early neural network-based model that learned **word embeddings**—numerical representations of words—that captured semantic relationships between them. This was a crucial step away from simple statistical models.
* **Transfer Learning:** The concept of **pre-training** a model on a large, general dataset and then **fine-tuning** it on a smaller, specific dataset for a particular task revolutionized NLP. It allowed models to learn a broad understanding of language and then adapt to specific use cases with much less data and computational power. This is the foundation of modern LLMs.
* **GPT (Generative Pre-trained Transformer):** Models like GPT exemplify this approach. They are pre-trained on a massive corpus of text and then fine-tuned for a wide range of tasks, from question-answering to summarization and text generation. The **transformer architecture**, with its ability to handle long-range dependencies in text, was the key innovation that allowed for the scale and performance of modern LLMs.
In this repository, you will find two Jupyter Notebook files:


## Assignment1.ipynb
## Assignment2.ipynb


These notebooks contain the code for our assignments, which involve practical exercises related to the concepts covered in Unit 1.
