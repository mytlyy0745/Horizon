---
layout: default
title: "Horizon Summary: 2026-11-27 (ZH)"
date: 2026-11-27
lang: zh
---

> 从 38 条内容中筛选出 6 条重要资讯。

---

**科技新闻**
1. [AMD 专用 llama.cpp 分支专注于优化旧款高内存带宽 GPU](#item-tech-news-1) ⭐️ 7.0/10
2. [&\#x27;RansomwareHelp&\#x27; 公司的首席技术官因电信诈骗被起诉](#item-tech-news-2) ⭐️ 7.0/10
3. [阿斯麦 CEO：全面断供中国芯片设备将加速其自主研发](#item-tech-news-3) ⭐️ 7.0/10

**财经新闻**
1. [半导体出口额首次超越石油与天然气](#item-finance-news-1) ⭐️ 8.0/10
2. [英伟达暂停向东南亚四国发运 AI 服务器](#item-finance-news-2) ⭐️ 8.0/10
3. [荷兰反对美国限制 ASML 对华销售法案](#item-finance-news-3) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [AMD 专用 llama.cpp 分支专注于优化旧款高内存带宽 GPU](https://devnull.land/amd-specific-llama-cpp) ⭐️ 7.0/10

开发者推出针对 AMD 硬件优化的 llama.cpp 分支，旨在提升旧款高内存带宽数据中心 GPU 运行大语言模型的性能。该修改针对缺乏现代原生特性的特定老旧架构，通过调整代码显著改善了推理吞吐量。此举为利用经济实惠的二手高带宽显存硬件运行本地大模型提供了更可行的方案。

hackernews · julianlam · 11月26日 17:11 · [社区讨论](https://news.ycombinator.com/item?id=50657265)

**「背景」** llama.cpp 是一个用于在本地硬件上高效运行大语言模型的流行开源推理框架。部分早期的 AMD 数据中心显卡虽然缺乏现代加速器的某些张量核心特性，但配备了极高的内存带宽和庞大的显存容量，使其成为低成本运行大模型的独特选择。

**「影响」** 拥有旧款 AMD 数据中心 GPU 的用户和开发者现在可以借助这些专用优化分支，以较低的成本实现更高的本地模型推理速度和更大上下文的处理能力。

**「社区讨论」** 社区成员指出，诸如 gfx906 等老旧 AMD 显卡虽然计算能力平平，但拥有极高的显存带宽且价格低廉，围绕其进行的 llama.cpp 及内核优化催生了一个活跃的生态。多位开发者分享了他们通过移植和优化内核将特定大模型（如 Qwen 3.8 27B）运行速度提升两到三倍的实际经验。

**标签**: `#artificial intelligence`, `#machine learning`, `#hardware`, `#open source`, `#software engineering`

---

<a id="item-tech-news-2"></a>
### [&\#x27;RansomwareHelp&\#x27; 公司的首席技术官因电信诈骗被起诉](https://krebsonsecurity.com/2026/11/cto-of-ransomwarehelp-indicted-for-wire-fraud/) ⭐️ 7.0/10

“RansomwareHelp”公司的首席技术官因涉及勒索软件谈判和赎金支付中的欺诈行为，已被正式起诉犯有电信诈骗罪。此次起诉针对的是该中介机构在处理勒索攻击和与勒索团伙交涉时的虚假商业宣传与欺诈操作。

hackernews · Bender · 11月26日 17:47 · [社区讨论](https://news.ycombinator.com/item?id=50657645)

**「背景」** 勒索软件谈判中介通常作为受害者与黑客之间的交涉桥梁，其业务合规性与透明度一直是网络安全和执法部门关注的重点。

**「社区讨论」** 评论者讨论了该机构的收费抽成、比特币波动风险以及其行为是否严格构成电信诈骗。有观点指出，虽然客户最终以接受的价格取回了数据，但其“不与威胁团伙进行中间协商或支付赎金”的宣传与实际做法之间存在实质性欺骗。

**标签**: `#cybersecurity`, `#ransomware`, `#legal`, `#crime`

---

<a id="item-tech-news-3"></a>
### [阿斯麦 CEO：全面断供中国芯片设备将加速其自主研发](https://www.semafor.com/article/11/25/2026/asml-makes-the-case-for-selling-chips-to-china) ⭐️ 7.0/10

阿斯麦首席执行官富凯在接受采访时表示，全面禁止向中国出售芯片制造设备并不能阻止技术发展，反而会迫使中国在自主研发上成倍增加投入。他指出，阿斯麦目前向中国销售的设备落后最先进制程十多年，维持这一代差能够让中国继续依赖西方设备。针对美国推动的拟将管制范围扩大至浸没式 DUV 及维护服务的 MATCH 法案，荷兰政府和阿斯麦均表达了反对立场。

telegram · zaihuapd · 11月26日 12:19

**「背景」** 近三十年来，阿斯麦在中国的光刻机市场占据了近乎全部的份额，并在极紫外（EUV）光刻机等关键半导体设备上面临严格的出口管制。随着美国进一步收紧对华半导体供应链的限制，相关政策正试图将管制延伸至更广泛的深紫外（DUV）设备及售后维护服务。

**「影响」** 若美国最终推行更广泛的管制法案，可能迫使中国本土半导体产业链加速替代设备的研发与部署，从而改变长期以来中国市场对西方光刻机及其维护服务的依赖格局。

**标签**: `#semiconductors`, `#hardware`, `#export controls`, `#industry analysis`, `#china technology`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [半导体出口额首次超越石油与天然气](https://www.cnbc.com/2026/11/26/semiconductor-chips-are-the-new-oil-heres-why.html) ⭐️ 8.0/10

根据德意志银行分析国际贸易中心数据的报告，在人工智能热潮与石油供应中断的推动下，2026 年第一季度全球半导体出口额（以四季度滚动计算）达到约 1.61 万亿美元，首次超过石油与天然气的 1.53 万亿美元。

rss · CNBC Finance · 11月26日 17:52

**「背景」** 随着人工智能数据中心建设激增以及伊朗战争后霍尔木兹海峡石油供应受阻，半导体在全球出口中的主导地位进一步扩大。

**「影响」** 这一宏观经济转变可能会改变全球金融资本的流向，促使亚洲半导体顺差国的资金更多地回流至美国科技股和初创企业，从而为新一轮人工智能投资周期提供资金支持。

**标签**: `#semiconductors`, `#global trade`, `#artificial intelligence`, `#macroeconomics`, `#market volatility`

---

<a id="item-finance-news-2"></a>
### [英伟达暂停向东南亚四国发运 AI 服务器](https://www.ft.com/content/7838a715-07d4-4605-aa60-21f5af2b2370) ⭐️ 8.0/10

据知情人士称，英伟达已要求主要制造伙伴暂停向马来西亚、新加坡、泰国和印度尼西亚发运人工智能服务器，此举与美国新一轮出口管制相关。受此影响，戴尔和美超微等组装厂商已通知四国买家相关订单不能出厂，是否为临时措施尚不清楚。

telegram · zaihuapd · 11月26日 07:38

**「背景」** 由于美国禁止直接向中国大陆出口最先进的人工智能处理器，这四个东南亚国家此前成为了中国人工智能公司获取相关芯片的中转地。美国商务部上周出台新规，要求区域云服务商在 90 天内取得出口许可并核实客户身份。

**「影响」** 相关服务器订单的冻结直接影响了马来西亚、新加坡、泰国和印度尼西亚的买家，并对依赖这些中转路线获取芯片的技术供应链造成了阻碍。

**标签**: `#Nvidia`, `#Export Controls`, `#AI Servers`, `#Supply Chain`, `#Semiconductors`

---

<a id="item-finance-news-3"></a>
### [荷兰反对美国限制 ASML 对华销售法案](https://www.bloomberg.com/news/articles/2026-11-26/netherlands-plans-to-fight-rollout-of-proposed-us-curbs-on-asml) ⭐️ 8.0/10

荷兰外贸与发展合作大臣 Sjoerd Sjoerdsma 于 11 月 26 日表示，荷兰不会接受美国旨在进一步限制阿斯麦（ASML）对华销售的《MATCH Act》法案，并正与欧洲盟友协调以反对其域外管辖效力。中国约占阿斯麦今年销售额的 20%。

telegram · zaihuapd · 11月26日 14:56

**「背景」** 阿斯麦是一家总部位于荷兰的全球顶尖光刻机制造商，其生产的半导体设备在芯片制造中起着关键作用。美国提出的《MATCH Act》要求盟友实施更严格的出口管制，预计美国国会将于 12 月中旬对该法案进行表决。

**标签**: `#Semiconductors`, `#Export Controls`, `#International Trade`, `#ASML`, `#US-China Relations`

---