---
layout: default
title: "Horizon Summary: 2026-11-15 (ZH)"
date: 2026-11-15
lang: zh
---

> 从 31 条内容中筛选出 4 条重要资讯。

---

**科技新闻**
1. [开发者推出可在 B300 上将 cudaMemcpy 提速 5 倍的调优工具](#item-tech-news-1) ⭐️ 8.0/10
2. [推理模型免训练早退机制](#item-tech-news-2) ⭐️ 8.0/10
3. [美团开源 1.6 万亿参数智能体模型 LongCat-2.5](#item-tech-news-3) ⭐️ 8.0/10
4. [理解现代大型语言模型中的位置编码技术](#item-tech-news-4) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [开发者推出可在 B300 上将 cudaMemcpy 提速 5 倍的调优工具](https://www.reddit.com/r/MachineLearning/comments/1xx2n25/making_cudamemcpy_5x_faster_on_a_b300_p/) ⭐️ 8.0/10

一名开发者推出了一款名为 cudamemcpy-tuner 的调优工具，能够将主机与设备之间的页面内存（pageable）cudaMemcpy 传输速度提升 5 倍。在 B300 硬件上复制 1 GB 张量的基准测试显示，使用该工具封装运行后，CPU 到 GPU 的传输速度从原本的 10.2 GB/s 提高至 51.5 GB/s。该工具的代码及相关博客已分别在 GitHub 和作者个人博客上公开。

reddit · r/MachineLearning · /u/makneeee · 11月15日 18:20

**「背景」** 在 CUDA 编程和机器学习框架中，CPU 与 GPU 之间针对页面内存的数据传输由于受到 PCIe 总线及传输机制的限制，往往会产生明显的性能瓶颈。开发专门的调优和加速工具可以帮助绕过某些默认传输限制，从而改善大规模张量迁移的吞吐量。

**「影响」** 使用该工具的开发者和研究人员可以显著减少在 CPU 与 GPU 之间搬运大体积张量时的等待时间，从而缓解训练或推理流程中的数据传输瓶颈。

**标签**: `#CUDA`, `#Hardware`, `#Machine Learning`, `#Performance`

---

<a id="item-tech-news-2"></a>
### [推理模型免训练早退机制](https://www.reddit.com/r/MachineLearning/comments/1xx1xdm/trainingfree_early_exit_for_reasoning_models_a/) ⭐️ 8.0/10

研究人员推出了一种针对推理模型的免训练早退方法，通过调整输出层中 \`&lt;/think&gt;\` 标记对应的单行权重来截断冗余的思考步骤。在未进行梯度训练的情况下，该方法在 Qwen3.5-4B 和 DeepSeek V4.1 Flash 等模型上进行了测试，在数学和编码任务中大幅减少了思考代币数量并保持了准确率。作者指出该方法的局限性包括样本量小、探针仅针对数学数据进行拟合以及基准测试中的预算限制。

reddit · r/MachineLearning · /u/Good-Presentation-23 · 11月15日 17:52

**「背景介绍」** 推理模型在给出答案前通常会在草稿纸中进行长达数千个代币的思考，并在输出 \`&lt;/think&gt;\` 标记时结束这一过程。下一个代币的得分由词汇表中每个词的权重行与隐藏状态相乘得出，这意味着 \`&lt;/think&gt;\` 标记的得分完全由输出层中的单行权重决定。

**「实际影响」** 开发者和用户可以直接使用修改后的普通权重文件，无需在推理时运行额外的代码，从而在减少计算开销的同时缩短推理时间。

**标签**: `#artificial intelligence`, `#machine learning`, `#language models`, `#model optimization`

---

<a id="item-tech-news-3"></a>
### [美团开源 1.6 万亿参数智能体模型 LongCat-2.5](https://the-decoder.com/meituan-releases-a-1-6-trillion-parameter-agent-model-that-never-touched-an-nvidia-gpu/) ⭐️ 8.0/10

美团旗下的 LongCat 团队正式开源 LongCat-2.5 模型权重，该模型拥有 1.6 万亿参数，每个 token 激活约 480 亿参数。官方称其训练全程使用中国华为升腾加速卡，未使用任何英伟达 GPU。该模型支持文本、图像和视频输入，以 MIT 许可证发布并可用于商用，在 Terminal Bench v2.1 上取得了 88.4 分的成绩。

telegram · zaihuapd · 11月15日 11:08

**「背景」** 长期以来，大规模 AI 模型的训练高度依赖英伟达的高性能 GPU。随着国际供应链和硬件环境的变化，国内科技企业正积极探索基于国产硬件的大规模模型训练路径。

**「影响」** 该模型的开源和国产硬件训练路径表明，国内算力生态已具备支撑超大规模多模态智能体训练的能力，为开发者和企业提供了摆脱英伟达生态的商用替代方案。

**标签**: `#artificial intelligence`, `#open source`, `#machine learning`, `#hardware`, `#china tech`

---

<a id="item-tech-news-4"></a>
### [理解现代大型语言模型中的位置编码技术](https://magazine.sebastianraschka.com/p/understanding-positional-embeddings) ⭐️ 7.0/10

本文详细探讨了位置编码在现代大型语言模型中的具体实现方式与应用机制。文章分析了不同位置编码方案在架构中的集成方式，为理解模型如何处理文本序列中的相对与绝对位置提供了技术视角。

hackernews · vismit2000 · 11月15日 12:14 · [社区讨论](https://news.ycombinator.com/item?id=50506376)

**「背景」** 由于 Transformer 架构本身采用并行处理且对输入序列无固有顺序感知，因此必须引入位置编码来为大语言模型提供词元在序列中的相对或绝对位置信息。

**「社区讨论」** 评论者 programjames 指出，该文章侧重于实现层面，而要真正透彻理解位置编码，则需要从群论等底层理论入手，并举例说明旋转位置编码本质上对应于平移群的表示。

**标签**: `#artificial intelligence`, `#machine learning`, `#large language models`, `#neural networks`

---