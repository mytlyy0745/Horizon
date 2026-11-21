---
layout: default
title: "Horizon Summary: 2026-11-21 (ZH)"
date: 2026-11-21
lang: zh
---

> 从 41 条内容中筛选出 11 条重要资讯。

---

**科技新闻**
1. [Levent Alpöge 宣布证明广义黎曼猜想并附带大规模 Lean 代码](#item-tech-news-1) ⭐️ 10.0/10
2. [Navier–Stokes 方程有限时间爆破研究发布](#item-tech-news-2) ⭐️ 10.0/10
3. [陶哲轩探讨无外力纳维-斯托克斯方程奇点与广义黎曼猜想的研究进展](#item-tech-news-3) ⭐️ 10.0/10
4. [Meta AI 助手 Muse 出现串号与数据泄露](#item-tech-news-4) ⭐️ 8.0/10
5. [Scott Aaronson 博客文章引发关于大语言模型能力的讨论](#item-tech-news-5) ⭐️ 7.0/10

**科技博客**
1. [为什么大模型输出缓存无法节省成本](#item-tech-blog-1) ⭐️ 7.0/10

**财经新闻**
1. [美联储官员言论增多，对利率政策分歧加剧](#item-finance-news-1) ⭐️ 8.0/10
2. [美股牛市面临新挑战：企业从回购转向抛售股票](#item-finance-news-2) ⭐️ 8.0/10
3. [美国半年内批准近 88 万颗 AI 芯片对华出口](#item-finance-news-3) ⭐️ 8.0/10
4. [福特宣布正式进入电池业务](#item-finance-news-4) ⭐️ 7.0/10
5. [阿里巴巴因涉嫌隐瞒业务关系遭股东集体诉讼](#item-finance-news-5) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Levent Alpöge 宣布证明广义黎曼猜想并附带大规模 Lean 代码](https://alpo.ge/remark.pdf) ⭐️ 10.0/10

数学家 Levent Alpöge 发布了一项关于广义黎曼猜想的证明声明及相关证明文件，其中包括体积达 1.3GB、约 1500 万行代码的 Lean 定理证明文件。该研究同时提供了人类可读的论证说明，目前数学界和技术社区正在对其有效性进行审视。

hackernews · iamronaldo · 11月20日 14:16 · [社区讨论](https://news.ycombinator.com/item?id=50574968)

**「背景」** 黎曼猜想（Riemann Hypothesis）是数学界最著名的未解难题之一，由数学家伯恩哈德·黎曼于 1859 年提出，关乎素数分布的规律。提出该声明的勒韦特·阿尔波格（Levent Alpöge）是一位专注于数论与算术统计的数学家，此前曾任哈佛大学学会初级研究员，后加入人工智能公司 Anthropic 担任技术人员。

**「社区讨论」** 评论者指出该证明规模庞大，包含数十个压缩包和数千万行 Lean 代码，同时也有人分享了 Alpöge 的人类可读版证明链接。部分讨论还关注了人工智能在其中的角色以及研究成果的发布方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Levent_Alp%C3%B6ge">Levent Alpöge - Wikipedia</a></li>
<li><a href="https://www.nacionale.com/en/articles/has-riemann-hypothesis-been-proved-levent-alpoge-claude-anthropic-claim-lean">Riemann hypothesis proof claimed with Claude, unverified</a></li>

</ul>
</details>

**标签**: `#mathematics`, `#formal verification`, `#lean`, `#research`

---

<a id="item-tech-news-2"></a>
### [Navier–Stokes 方程有限时间爆破研究发布](https://github.com/tristanbuckmaster/navier-stokes/) ⭐️ 10.0/10

研究人员在 GitHub 上发布了一项针对无外力 Navier–Stokes 方程有限时间爆破问题的工作。该研究涉及千禧年数学难题之一，探讨了流体动力学中的关键数学性质。

hackernews · trotro · 11月20日 15:34 · [社区讨论](https://news.ycombinator.com/item?id=50576232)

**「背景」** 纳维-斯托克斯方程是描述流体运动的基本数学方程，其中关于三维空间中解的光滑性与有限时间爆破问题被列为七大千禧年数学难题之一。此前，数学家 Tristan Buckmaster 与 Levent Alpöge 曾开展利用人工智能辅助研究流体方程爆破的工作。

**「社区讨论」** 评论者指出这是针对无外力版本的成果，并将其与 OpenAI 近期关于受迫 Navier–Stokes 方程的成果进行了对比。社区成员还讨论了该研究作者在同一天面临的舆论和关注情况。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.unite.ai/buckmaster-and-alpoge-post-ai-fluid-blowup-proofs-dispute-openai-contact/">Buckmaster and Alpöge Post AI Fluid Blowup Proofs, Detail OpenAI...</a></li>
<li><a href="https://www.clarin.com/us-news/who-is-levent-alpoge-the-anthropic-mathematician-who-claims-solved-the-riemann-hypothesis-with-claude_0_2WdGvYKBVM.html">Who is Levent Alpöge? The Anthropic mathematician who claims he...</a></li>

</ul>
</details>

**标签**: `#mathematics`, `#navier-stokes`, `#fluid-dynamics`, `#research`

---

<a id="item-tech-news-3"></a>
### [陶哲轩探讨无外力纳维-斯托克斯方程奇点与广义黎曼猜想的研究进展](https://terrytao.wordpress.com/2026/11/20/unforced-euler-singularity-unforced-navier-stokes-singularity-and-the-generalized-riemann-hypothesis/) ⭐️ 10.0/10

数学家特伦斯·陶（Terry Tao）在博客中探讨了关于无外力纳维-斯托克斯方程奇点与广义黎曼猜想的重要数学进展。相关形式化证明吸引了数学界的广泛关注，并有讨论指出该结果已通过两个独立内核的验证。

hackernews · archon1410 · 11月20日 17:21 · [社区讨论](https://news.ycombinator.com/item?id=50578358)

**「背景」** Navier-Stokes 方程组存在性与光滑性问题及 Riemann 假设是数学界长期未解的核心难题，其中 Riemann 假设由 Bernhard Riemann 于 1859 年提出，旨在揭示素数分布规律。

**「社区讨论」** 社区成员对利用形式化证明工具（如 Lean）验证复杂数学定理的进展表示惊叹与担忧，并讨论了如何确保庞大的形式化代码库确实证明了预期的数学命题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_existence_and_smoothness">Navier – Stokes existence and smoothness - Wikipedia</a></li>
<li><a href="https://www.scientificamerican.com/article/anthropic-mathematician-claims-to-prove-riemann-hypothesis-most-famous-problem-in-all-of-math/">Anthropic mathematician claims to prove Riemann hypothesis , most...</a></li>

</ul>
</details>

**标签**: `#mathematics`, `#formal verification`, `#lean`, `#research`, `#artificial intelligence`

---

<a id="item-tech-news-4"></a>
### [Meta AI 助手 Muse 出现串号与数据泄露](https://techcrunch.com/2026/11/19/metas-ai-agent-muse-is-mixing-up-conversations-and-exposing-private-data-report-says/) ⭐️ 8.0/10

Meta 内部 AI 助手 Muse 近期发生严重的跨账户对话混乱，导致内部员工在自己的账户中看到他人的私密信息。具体泄露的数据包括不属于本人的银行余额、未经发送的育儿与职业建议请求、未曾下单的订单信息，以及未经授权的应用通知。

telegram · zaihuapd · 11月20日 05:10

**「背景」** AI 助手与大语言模型在接入多源个人数据及外部应用时，需要严格的账户隔离与权限控制机制来保障用户隐私。此次事故暴露出内部测试系统在多用户数据隔离和应用授权管理方面存在严重的架构或实现漏洞。

**「影响」** 这起事故对企业内部数据安全和用户隐私保护敲响了警钟，表明当前 AI 助手在处理跨应用及敏感财务数据时仍面临极高的安全合规风险。开发团队必须立即排查并加固授权验证及会话隔离机制，以防止未来正式上线时发生更大规模的数据泄露。

**标签**: `#Artificial Intelligence`, `#Privacy and Security`, `#AI Agents`, `#Meta`

---

<a id="item-tech-news-5"></a>
### [Scott Aaronson 博客文章引发关于大语言模型能力的讨论](https://scottaaronson.blog/?p=10344) ⭐️ 7.0/10

Scott Aaronson 在其博客上发表了一篇关于人工智能模型与数学猜想的文章。该文章引发了社区对大语言模型本质、局限性及其在科学推理中作用的讨论。

hackernews · stratos123 · 11月20日 20:03 · [社区讨论](https://news.ycombinator.com/item?id=50581084)

**「背景」** “随机鹦鹉”这一术语常被用来形容大型语言模型本质上只是在统计学上模仿人类语言，而并不具备真正的理解或推理能力。

**「社区讨论」** 评论区讨论了大型语言模型作为训练数据有损压缩的本质，并将其与国际象棋引擎进行对比，探讨了人类在面对难以直观理解的复杂计算结果时的困惑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://scottaaronson.blog/?p=10344">Shtetl-Optimized » Blog Archive » The stochastic parrots have ...</a></li>

</ul>
</details>

**标签**: `#artificial intelligence`, `#machine learning`, `#mathematics`, `#language models`

---

## 科技博客

<a id="item-tech-blog-1"></a>
### [为什么大模型输出缓存无法节省成本](https://seangoedecke.com/why-output-caching-doesnt-work/) ⭐️ 7.0/10

rss · Sean Goedecke · 11月21日 00:00

**「背景」** 尽管输入缓存已被广泛用于避免重复计算对话历史，但大模型在生成回复时似乎也包含了大量重复的文本输出。作者 Sean Goedecke 指出，直接缓存这些可见的输出看似能节省昂贵且昂贵的输出 Token，然而这种直觉却忽略了实际的 Token 消耗结构。

**「方案」** 作者分析认为，通过微调或提示词让模型用引用代替重复文本的优化手段，其实际效果极为有限。根据其对代理工作流的观察，可见输出仅占总输出 Token 的大约 6%，而其余 50%为推理 Token，44%为工具调用。根据阿姆达尔定律，即便将可见输出的 Token 减少三分之二，总输出 Token 的节省比例也仅有 4%左右。因此，真正决定输出成本的关键在于减少那些隐式的推理和工具调用，而这高度依赖于模型自身的智能水平。更聪明的模型虽然单价较高，但由于能用更少的 Token 解决问题，往往总成本反而更低。

**「启示」** 大模型输出缓存无法带来显著的成本节约，因为可见文本只占输出 Token 的极小一部分。要真正提高经济效率，重点应放在提升模型本身的推理能力以减少隐式 Token 消耗，而非盲目优化表面输出。

**标签**: `#llm-inference`, `#token-economics`, `#caching`, `#ai-agents`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美联储官员言论增多，对利率政策分歧加剧](https://www.cnbc.com/2026/11/20/warsh-fed-forward-guidance-rate-hikes.html) ⭐️ 8.0/10

在美联储主席沃什拒绝提供传统的前瞻性指引后，其他联邦公开市场委员会成员近期显著增加了公开言论，并在利率政策上表现出分歧。

rss · CNBC Finance · 11月20日 21:10

**「背景」** 美联储在 10 月的会议上决定维持基准利率不变，而当前通胀指标仍高于美联储设定的 2%目标。

**「影响」** 由于美联储官员频繁发表不同观点，金融市场对利率路径的预期波动加剧，交易员目前预计 12 月将至少加息四分之一个百分点。

**标签**: `#Federal Reserve`, `#Monetary Policy`, `#Interest Rates`, `#Inflation`, `#Central Banking`

---

<a id="item-finance-news-2"></a>
### [美股牛市面临新挑战：企业从回购转向抛售股票](https://www.cnbc.com/2026/11/20/equity-issuance-bull-market-problem.html) ⭐️ 8.0/10

根据资产管理公司阿卡迪亚（Acadian）的分析，截至 2026 年 11 月下旬，美国企业已从前几年的股票回购转向净增发股票，净新发股票规模占总市值的 3.1%。

rss · CNBC Finance · 11月20日 14:15

**「背景」** 此前多年，美国企业通过股票回购减少了市场上流通的股票数量，成为支撑股市上涨和每股收益增长的主要动力之一。

**「影响」** 市场股票供应量的增加可能对持续四年的美股牛市构成下行压力，改变资金追逐有限股票的供需格局。

**标签**: `#Equity Issuance`, `#Share Repurchases`, `#Bull Market`, `#Corporate Finance`, `#Market Trends`

---

<a id="item-finance-news-3"></a>
### [美国半年内批准近 88 万颗 AI 芯片对华出口](https://foreignaffairs.house.gov/news/press-releases/chairman-brian-mast-exercises-legislative-authority-to-publicly-release-ai-chip-license-information-for-china) ⭐️ 8.0/10

美国众议院外交事务委员会披露的文件显示，2025 年 12 月至 2026 年 5 月期间，美国批准向中国出口 879,868 颗人工智能芯片，其中包含英伟达的 H200 和 AMD 的 MI325X 型号。这些获批数据来自企业申请，实际交付情况尚不明确。

telegram · zaihuapd · 11月20日 04:25

**「背景」** 人工智能（AI）芯片是用于加速机器学习和处理复杂数据的高性能半导体，美国对其实施严格的出口管制以限制特定国家的技术获取。部分获批的中国企业此前被美国列入中国军方关联企业名单，引发了国会对出口审查机制的质疑。

**标签**: `#AI chips`, `#export controls`, `#US-China relations`, `#semiconductors`, `#technology policy`

---

<a id="item-finance-news-4"></a>
### [福特宣布正式进入电池业务](https://api3.cls.cn/share/article/2539395?sv=8.5.9) ⭐️ 7.0/10

福特宣布正式进入电池业务，其位于美国密歇根州的工厂已开始发运首批磷酸铁锂方形电芯（一种使用磷酸铁锂材料制造的充电电池，具有成本低、寿命长的特点），供下一代电动皮卡使用。该工厂采用中国合作伙伴宁德时代授权的技术，规划年产能约为 20 吉瓦时（吉瓦时是电池容量计量单位，1 吉瓦时等于 100 万千瓦时）。

telegram · zaihuapd · 11月20日 06:04

**「背景」** 福特计划在 2027 年进一步提高电芯产量并启用电池包产线，为预计于当年第四季度推出的 Fathom 电动皮卡做准备。

**标签**: `#Automotive`, `#EV Batteries`, `#Ford`, `#CATL`, `#Supply Chain`

---

<a id="item-finance-news-5"></a>
### [阿里巴巴因涉嫌隐瞒业务关系遭股东集体诉讼](https://www.zaobao.com.sg/news/china/story20261120-10029652) ⭐️ 7.0/10

阿里巴巴及首席执行官于 2026 年 11 月 19 日在纽约曼哈顿联邦法院遭到股东集体诉讼，原告指控其在年报中隐瞒业务关系及出口管制违规风险并推高股价，导致公司股价在相关报道发布后的四个交易日内下跌了 14%，索赔金额未在诉状中列明。

telegram · zaihuapd · 11月20日 09:32

**「背景」** 集体诉讼是指由一名或多名原告代表众多利益受损的群体向法院提起的诉讼，在美国证券市场中，当上市公司涉嫌隐瞒重要信息导致股价下跌时，常会面临此类诉讼。

**「影响」** 这一诉讼和随之而来的股价下跌使持有阿里巴巴股票的投资者面临资产缩水的风险，同时也引发了市场对其合规风险的关注。

**标签**: `#Alibaba`, `#Class Action Lawsuit`, `#Securities Regulation`, `#Stock Market`

---