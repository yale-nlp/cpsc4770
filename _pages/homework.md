---
layout: page
permalink: /homework/
title: Homework Assignments
---

All homeworks should be submitted through Gradescope.

# Homework 3: Prefereance Optimization, Parameter-Efficient Fine-Tuning, and Retrieval-Augmented Generation

## Part 1: Direct Preference Optimization (DPO)

#### Fine-Tuning Language Models with Preference Feedback (100 points)

The main goal of this part is to understand and implement the Direct Preference Optimization (DPO) algorithm for aligning language models with human preferences. This involves:

- Comparing a base GPT-2 model with a supervised fine-tuned (SFT) model to understand the effect of instruction tuning.
- Understanding the data pipeline for preference-based training, including dataset classes, collators, and how chosen/rejected response pairs are handled.
- Computing reference model log probabilities needed for the DPO loss, including masking out prompt tokens.
- Implementing the DPO loss function based on the closed-form derivation from the original paper.
- Implementing the DPO dataset class and collator for the training loop.
- Fine-tuning a GPT-2 DPO model on the UltraFeedback preference dataset.
- Evaluating and comparing SFT, instructor's DPO, and student's DPO models using ROUGE scores and pairwise comparison with PairRM.
- Answering conceptual questions about the DPO algorithm, gradient accumulation, and evaluation methodology.

You will need to log in to Colab with your **Yale account** to access the notebook.
Then you can copy the notebook to your own account and start working on it.

Please see the instructions and the notebook here: [Colab 1 (DPO)](https://colab.research.google.com/drive/1Qz5SmmoDlSS2MRQbBd_dZcB5u8OT6c3-?usp=sharing).

Submit the completed notebook with all the output to Gradescope. See the instructions in the notebook for more details.

---

## Part 2: Implementing LoRA From Scratch

#### Parameter-Efficient Fine-Tuning (70 points)

The main goal of this part is to understand and implement Low-Rank Adaptation (LoRA), a parameter-efficient fine-tuning method that dramatically reduces the number of trainable parameters. This involves:

- Implementing a LoRA layer from scratch, including the low-rank decomposition with matrices A and B, scaling factor, and the forward pass that combines the original weights with the low-rank update.
- Modifying a pre-trained RoBERTa model to incorporate LoRA layers into its attention modules, while freezing the original model weights.
- Fine-tuning the LoRA-augmented RoBERTa model on a downstream text classification task and evaluating its performance.
- Analyzing the results: comparing the number of trainable parameters, training efficiency, and performance between LoRA fine-tuning and full fine-tuning, and discussing the effect of rank on model quality.

Please see the instructions and the notebook here: [Colab 2 (LoRA)](https://colab.research.google.com/drive/1Igwm7Z35WAv-pwOESh8KKw1cdBlC0x0t?usp=sharing).

Submit the completed notebook with all the output to Gradescope. See the instructions in the notebook for more details.

---

## Part 3: RAG and Information Retrieval

#### Retrieval-Augmented Generation (50 points)

The main goal of this part is to understand and implement a Retrieval-Augmented Generation (RAG) pipeline, which enhances language model responses by retrieving relevant documents from an external knowledge base. This involves:

- Embedding documents using the an Embeddings model to create dense vector representations.
- Building a retrieval index for efficient nearest-neighbor search over the embedded documents.
- Implementing the retrieval component to find the most relevant documents for a given query.
- Evaluating the RAG pipeline using standard information retrieval metrics.
- Analyzing and discussing the results, including the strengths and limitations of the retrieval-augmented approach.

Please see the instructions and the notebook here: [Colab 3 (RAG)](https://colab.research.google.com/drive/1RTLCNGsYWwOopfhWhkc4aqmXjgYcqlcj?usp=sharing).

Submit the completed notebook with all the output to Gradescope. See the instructions in the notebook for more details.

---

## Homework 2

### Part 1: Hands-on excercise
#### Implementing and Training a Transformer Language Model (60 points)

The main goal of this assignment is to implement a Transformer model from scratch for language modeling. This involves several key steps:

- Implementing the Model Input Pipeline
- Building the Transformer Architecture: Implementing core components like QKV projections, multi-head self-attention (including causal and padding masks), feedforward networks, layer normalization, individual Transformer blocks, and stacking them into a complete Transformer model.
- Answering conceptual questions related to the implemented components.
- Training the Transformer on Language Modeling Task: Setting up a training loop with a DataLoader, implementing a learning rate scheduler (with warmup and decay), and training a small Transformer model on a language modeling task to observe its learning process.
- Reporting and observing the training loss.

You will need to log in to Colab with your **Yale account** to access the notebook.
Then you can copy the notebook to your own account and start working on that. 

Please see the instructions and the notebook here: [Colab-1](https://colab.research.google.com/drive/1H37nkrc_7AbCayQPNxgyz2OXO8Y1ALyz?usp=sharing).

Submit the completed notebook with all the output to Gradescope. See the instructions in the notebook for more details.

### Part 2: Hands-on excercise

#### Language Model Decoding Strategies (40 points)

In this homework, your goal is to implement various decoding strategies for a language model for text generation.
You will gain hands-on experience with state-of-the-art tools and models, learning to:

- Leverage Huggingface Ecosystem: Use the Transformers and Datasets libraries to work with the off-the-shelf models and datasets.
- The Generation Pipeline: Implement and understand the core stages of text generation, including training (calculating Cross-Entropy loss), inference, and evaluation.
- Implement Decoding Algorithms: Manually implementing key decoding strategies.

By the end of this homework, you will have a deep understanding of how neural text generation models work and how to effectively deploy them for real-world NLP tasks.

You will need to log in to Colab with your **Yale account** to access the notebook.
Then you can copy the notebook to your own account and start working on that. 

Please see the instructions and the notebook here: [Colab-2](https://colab.research.google.com/drive/1GD9wPl7urP6Cda4nptyK0rZKm7SBNPOG?usp=sharing).

Submit the completed notebook with all the output to Gradescope. See the instructions in the notebook for more details.

## Homework 1

### Part 1: Hands-on excercise
#### Implementing sparse representations (50 points)

In this homework, your goal is to implement sparse word and document representations. Sparse representations are crucial in many natural language processing tasks, particularly when working with high-dimensional data like text.

You will need to log in to Colab with your Yale account to access the notebook.
Then you can copy the notebook to your own account and start working on that. 

You will be completing parts indicated with 
```
    #
    # % -- Your Implementation -- %
    #
```

Or `# TODO: Implement`. 

Then you will be submitting the completed notebook with all the outputs.

Please see the instructions and the notebook here: [Colab-1](https://colab.research.google.com/drive/1HB8SX-clrEbgiMI9M4N_61htCF0m15ON?usp=sharing).

### Part 2
#### Handout (20 points) 

Download the homework handout from the following link: [Download](https://yaleedu-my.sharepoint.com/:b:/g/personal/arman_cohan_yale_edu/IQBxAlSERhW0S7dZ0T5Qq6ooAUmxGMbp2ryF06jgUdyq5Fg?e=x6jidH).

For this part, you need to complete the homework in LaTeX and return the pdf solution. Further instructions are provided in the pdf.

### Part 3: Hands-on excercise
#### Implementing the Word2Vec model (50 points)

The third part is implementation of a `Word2Vec` SkipGram model from scratch.
A Colab notebook is provided to guide you through the process of implementing the model from scratch and training it on a toy data sample.

Then you will be submitting the completed notebook with all the outputs.

Please see the instructions and the notebook here: [Colab-2](https://colab.research.google.com/drive/1l_G-yXe5_hvHI6oXV_lOp9wkacE2Gp1H?usp=sharing).
