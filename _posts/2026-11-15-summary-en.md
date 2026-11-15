---
layout: default
title: "Horizon Summary: 2026-11-15 (EN)"
date: 2026-11-15
lang: en
---

> From 31 items, 4 important content pieces were selected

---

**Technology News**
1. [Making cudaMemcpy 5x Faster on NVIDIA B300 Hardware](#item-tech-news-1) ⭐️ 8.0/10
2. [Training-free early exit method for reasoning models via weight modification](#item-tech-news-2) ⭐️ 8.0/10
3. [Meituan Releases 1.6-Trillion-Parameter LongCat-2.5 Agent Model Trained Without NVIDIA GPUs](#item-tech-news-3) ⭐️ 8.0/10
4. [Understanding Positional Embeddings in Modern LLMs](#item-tech-news-4) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Making cudaMemcpy 5x Faster on NVIDIA B300 Hardware](https://www.reddit.com/r/MachineLearning/comments/1xx2n25/making_cudamemcpy_5x_faster_on_a_b300_p/) ⭐️ 8.0/10

A developer has released an open-source tuning tool called cudamemcpy-tuner that accelerates pageable CPU-to-GPU and GPU-to-CPU cudaMemcpy transfers by 5x. On an NVIDIA B300 system copying a 1 GB tensor, the tool increased transfer speeds from a baseline of 10.2 GB/s to 51.5 GB/s. The utility wraps execution via a command-line interface using the cmt tune command.

reddit · r/MachineLearning · /u/makneeee · Nov 15, 18:20

**「Background」** Data transfers between host CPU memory and device GPU memory via cudaMemcpy often act as a significant performance bottleneck in machine learning workloads, particularly when dealing with standard pageable memory rather than pinned memory. Optimizing these transfer paths can dramatically improve throughput for data loading and offloading operations.

**「Impact」** Machine learning engineers and systems developers running PyTorch or CUDA workflows on modern hardware can integrate the tuner to reduce transfer overhead for pageable tensors without modifying source code.

**Tags**: `#CUDA`, `#Hardware`, `#Machine Learning`, `#Performance`

---

<a id="item-tech-news-2"></a>
### [Training-free early exit method for reasoning models via weight modification](https://www.reddit.com/r/MachineLearning/comments/1xx1xdm/trainingfree_early_exit_for_reasoning_models_a/) ⭐️ 8.0/10

A researcher has developed a training-free early exit technique for reasoning models that truncates redundant thinking tokens by modifying a single row of output layer weights. Using linear discriminant analysis computed via linear algebra on hidden states from 24 math problems, the method adds a classification direction directly to the &quot;&lt;/think&gt;&quot; token row without gradient training or extra inference code. Tested configurations include Qwen3.5-4B running in stock llama.cpp, which achieved identical accuracy on eight unseen MATH-500 problems while using 54% fewer tokens, and DeepSeek V4.1 Flash, which used 40% fewer tokens. Limitations include small sample sizes, a probe fitted exclusively on math tasks, and an AIME comparison using a 32k-token budget below the recommended 81,920 tokens.

reddit · r/MachineLearning · /u/Good-Presentation-23 · Nov 15, 17:52

**「Background」** Reasoning models such as DeepSeek and Qwen typically process problems through a scratchpad of internal thinking tokens before generating a final answer, concluding this scratchpad when the &quot;&lt;/think&gt;&quot; token is produced. While prior research has explored using linear probes on model hidden states to detect when reasoning is complete and halt execution early, existing approaches generally require extra runtime logic or external monitoring during inference.

**Tags**: `#artificial intelligence`, `#machine learning`, `#language models`, `#model optimization`

---

<a id="item-tech-news-3"></a>
### [Meituan Releases 1.6-Trillion-Parameter LongCat-2.5 Agent Model Trained Without NVIDIA GPUs](https://the-decoder.com/meituan-releases-a-1-6-trillion-parameter-agent-model-that-never-touched-an-nvidia-gpu/) ⭐️ 8.0/10

Meituan&\#x27;s LongCat team has open-sourced LongCat-2.5 under an MIT license, a 1.6-trillion-parameter multi-modal agent model that activates approximately 480 billion parameters per token. The model supports text, image, and video inputs, and was trained exclusively on Chinese domestic AI chips \(Huawei Ascend accelerator cards\) without using NVIDIA hardware. It achieved a score of 88.4 on Terminal Bench v2.1, slightly trailing Claude Opus 5 at 89.1.

telegram · zaihuapd · Nov 15, 11:08

**「Background」** Large-scale frontier AI models have historically relied heavily on NVIDIA graphics processing units and proprietary software stacks like CUDA for training. Domestic alternatives such as Huawei Ascend hardware have increasingly sought to provide viable compute pathways for large language and agent model development.

**「Impact」** Developers and organizations looking for commercially viable, large-scale agent models can now access LongCat-2.5 under an MIT license, demonstrating that massive multi-step reasoning models can be trained entirely on alternative domestic hardware.

**Tags**: `#artificial intelligence`, `#open source`, `#machine learning`, `#hardware`, `#china tech`

---

<a id="item-tech-news-4"></a>
### [Understanding Positional Embeddings in Modern LLMs](https://magazine.sebastianraschka.com/p/understanding-positional-embeddings) ⭐️ 7.0/10

An analysis explores how positional embeddings are implemented and utilized within modern large language models. The piece details the mechanisms that allow neural networks to process token order. It examines the practical application of these embeddings in current architectures without introducing new product releases or performance benchmarks.

hackernews · vismit2000 · Nov 15, 12:14 · [Discussion](https://news.ycombinator.com/item?id=50506376)

**「Positional Embeddings in Transformer Models」** Because the self-attention mechanism in transformer models is inherently permutation-invariant, models require explicit positional information to distinguish the order of tokens in a sequence.

**「Community Discussion on Underlying Theory」** A commenter argued that fully understanding positional embeddings requires examining group representation theory, noting that rotary positional embeddings represent the translation group.

**Tags**: `#artificial intelligence`, `#machine learning`, `#large language models`, `#neural networks`

---