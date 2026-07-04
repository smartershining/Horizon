---
layout: default
title: "Horizon Summary: 2026-07-04 (ZH)"
date: 2026-07-04
lang: zh
---

> 从 13 条内容中筛选出 8 条重要资讯。

---

1. [Pegasus 攻击了欧洲议会调查者。](#item-1) ⭐️ 8.0/10
2. [SearXNG 仍是实用的隐私元搜索选择。](#item-2) ⭐️ 7.0/10
3. [本地 SOTA LLM 部署受到现实检验。](#item-3) ⭐️ 7.0/10
4. [Current AI 绘制开源 AI 生态图谱。](#item-4) ⭐️ 7.0/10
5. [Costco 展示反 Amazon 模式。](#item-5) ⭐️ 6.0/10
6. [工厂是有组织的房间。](#item-6) ⭐️ 6.0/10
7. [AI 冲击开发者课程销售](#item-7) ⭐️ 6.0/10
8. [让编程智能体自行判断](#item-8) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Pegasus 攻击了欧洲议会调查者。](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 8.0/10

Citizen Lab 报告称，他们以高置信度确认，正在调查间谍软件的欧洲议会议员 Stelios Kouloglou 的 iPhone 曾在 2022 年 10 月 21 日左右以及 2023 年 3 月 6 日和 7 日再次被 Pegasus 成功感染。 这一事件令人担忧，因为间谍软件可能同时危及民主监督工作和敏感个人信息。它也进一步推动欧洲机构和各国政府面对跨境监控、问责机制以及公职人员操作安全问题。 报告中的感染时间线与此前发现的、针对欧洲境内俄语和白俄罗斯语流亡记者及活动人士的 Pegasus 行动存在重叠。归因仍是一个关键限制，因为讨论中提到的线索指向可能在多个欧洲国家活动的客户，也提到尚未完全解决的希腊间谍软件丑闻。

hackernews · ledoge · 7月3日 20:38 · [社区讨论](https://news.ycombinator.com/item?id=48779683)

**背景**: Pegasus 是一种商业间谍软件，相关资料将其归因于 NSO Group，并且它以攻击 iPhone 等移动设备而闻名。这类间谍软件在政治场景中特别敏感，因为一旦设备被攻破，消息、文件、联系人和其他私人数据都可能暴露。The Guardian 的介绍指出，目标数据可以显示攻击意图，但号码出现在数据中本身并不证明感染成功，因此这类事件中的取证分析非常重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kaspersky.com/blog/pegasus-spyware/14604/">Pegasus : The ultimate spyware for iOS and... | Kaspersky official blog</a></li>
<li><a href="https://www.theguardian.com/news/2021/jul/18/what-is-pegasus-spyware-and-how-does-it-hack-phones">What is Pegasus spyware and how does it hack... | The Guardian</a></li>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus ( spyware ) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论整体表现出担忧和怀疑，评论者主要关注归因问题、是否存在获准在多个欧洲国家行动的 Pegasus 客户，以及欧洲议会议员是否应该区分工作设备和个人设备。一些评论者将此事与希腊尚未完全解决的间谍软件丑闻联系起来，也有人悲观地认为事件可能只会带来更多文书工作，而不会产生真正后果。

**标签**: `#cybersecurity`, `#spyware`, `#Pegasus`, `#European Parliament`, `#surveillance`

---

<a id="item-2"></a>
## [SearXNG 仍是实用的隐私元搜索选择。](https://github.com/searxng/searxng) ⭐️ 7.0/10

SearXNG 被重点讨论为一个成熟、免费、可自托管的隐私导向元搜索引擎。此次讨论并不是围绕一次新版本发布，而是集中在它的实际使用取舍，包括流量画像、速度、结果质量、验证码和后端可靠性。 SearXNG 的重要性在于，它让重视隐私和自托管的用户能更好地控制搜索请求的路由和结果呈现方式。它也与智能体和 RAG 工作流相关，因为评论者提到它支持 JSON 结果，并可被其他工具封装，在把搜索上下文交给智能体之前进行优化。 评论者强调，元搜索并不会自动消除画像风险：低流量实例的请求仍可能很独特，而把查询发送给多个提供方也会带来新的隐私疑问。实际限制包括响应更慢、结果有时不如主流搜索引擎，以及来自 DuckDuckGo 或 Brave 等上游搜索提供方的偶发封禁或验证码。

hackernews · theanonymousone · 7月3日 20:15 · [社区讨论](https://news.ycombinator.com/item?id=48779454)

**背景**: 元搜索引擎会聚合多个搜索提供方的结果，而不是只依赖一个自己的主要网页索引。搜索结果中提到，Searx 是一个已停止维护的自由开源元搜索引擎，采用 GNU AGPLv3 许可证，目标是保护用户隐私。RAG，即检索增强生成，是让大语言模型在回答前先从外部来源检索信息的技术，这也解释了为什么可搜索的 JSON 输出对 AI 工作流有价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Searx">Searx - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Retrieval-augmented_generation">Retrieval - augmented generation - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区整体态度是肯定但务实：多位用户喜欢或依赖 SearXNG，其中一位表示它已经作为自己的日常搜索引擎使用了五年以上。同时，评论者也提出了隐私边界、结果较弱或较慢、验证码，以及 Searx 原作者认为元搜索概念存在局限等问题。也有人提到 Hister 和 TinySearch 等相关工具，分别作为全文索引和面向智能体搜索的替代或补充方案。

**标签**: `#search`, `#privacy`, `#open-source`, `#self-hosting`, `#RAG`

---

<a id="item-3"></a>
## [本地 SOTA LLM 部署受到现实检验。](https://github.com/jamesob/local-llm) ⭐️ 7.0/10

Jamesob 发布了一份 GitHub 指南，介绍如何在本地运行 SOTA LLM，而讨论重点集中在实际成本和限制上。评论者提到了从双 RTX 3090、共 48GB VRAM 的配置，到约 4 万美元甚至更高预算的方案。 本地部署 LLM 很重要，因为它承诺带来更强的控制权、隐私性和可预测的使用成本，但讨论显示，对许多用户来说，想要接近托管前沿模型的质量在经济上并不现实。这场讨论反映了 AI 基础设施中的一个更大矛盾：开源模型自托管与基于订阅的托管系统之间的取舍。 一个反复出现的技术注意点是，本地方案通常依赖量化、剪枝或其他效率优化技术，这些方法可以降低内存占用，但可能影响模型质量、推理稳定性，或在基准测试之外的实际表现。多位评论者质疑“接近 Opus”这类性能说法是否现实，因为大型模型在舒适推理时可能需要更多 VRAM 或高端 GPU 集群。

hackernews · livestyle · 7月3日 15:03 · [社区讨论](https://news.ycombinator.com/item?id=48775921)

**背景**: 本地 LLM 推理是指在用户自己控制的硬件上运行语言模型，而不是调用托管 API。对于大型模型来说，VRAM 通常是主要瓶颈，因为模型权重和推理状态需要放入高速 GPU 显存或统一内存中。量化会降低模型权重的数值精度，从而节省内存并提升吞吐，但也可能带来质量下降。Gemma 等开放 LLM 以及其他公开模型家族让本地实验更容易开展，但高端性能仍然高度依赖硬件容量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://homelabstarter.com/homelab-local-ai-gpu-setup/">Running Local AI in Your Homelab: GPU Setup... — HomeLab Starter</a></li>
<li><a href="https://www.digitalapplied.com/blog/quantization-tradeoffs-4bit-8bit-fp8-performance-data">Quantization Tradeoffs : 4-bit vs 8-bit vs FP8 Data</a></li>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/gemma-open-models/">Gemma: Google introduces new state - of - the - art open models</a></li>

</ul>
</details>

**社区讨论**: 社区情绪总体上是热情但谨慎的：评论者喜欢本地 LLM，但警告指南中的高端示例可能低估了真实成本。多位用户把硬件投入与多年托管订阅费用进行比较，也有人讨论 128GB VRAM 的折中方案、双 RTX 3090 配置，以及量化或剪枝模型在实际使用中可能弱于基准结果的风险。

**标签**: `#local-llms`, `#ai-infrastructure`, `#gpu-hardware`, `#llm-inference`, `#open-models`

---

<a id="item-4"></a>
## [Current AI 绘制开源 AI 生态图谱。](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 7.0/10

Current AI 发布了 Open Source AI Gap Map v0.1，用于整理当前开源 AI 生态。初始版本详细收录了 421 个产品，包括来自 228 个组织的 266 个软件工具和库、85 个模型、50 个数据集以及 20 个硬件项目。 这张图谱的重要性在于，开源 AI 正在模型、数据集、基础设施和硬件等方向快速扩张，外界很难判断生态的优势和薄弱环节。结构化目录可以帮助研究人员、开发者、资助方和政策制定者识别缺口并确定投入优先级。 底层数据以 MIT 许可证发布在 currentai-org/os-ai-map GitHub 仓库中，包括 1,184 个 YAML 文件以及笔记本、模式和脚本。该项目还跟踪了更大的未分类长尾，共 24,400 个工件，这些内容在完成研究和引用前不会获得评分。

rss · Simon Willison · 7月3日 22:04

**背景**: 开源 AI 指代码、权重、数据或设计以开放许可证或开放访问方式提供的 AI 相关模型、工具、数据集、基础设施或硬件项目。这个生态范围很广，因为现代 AI 系统依赖多个层次，从训练数据和模型组件，到开发者工具、面向用户的产品和部署基础设施。Current AI 被描述为一个非营利全球合作组织，成立于 2025 年 2 月巴黎 AI Action Summit，并已获得 4 亿美元承诺资金支持。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.instaclustr.com/education/open-source-ai/open-source-ai-tools-pros-and-cons-types-and-top-10-projects/">Open source AI tools : Pros and cons, types, and top 10 projects</a></li>
<li><a href="https://openflows.org/">Openflows</a></li>

</ul>
</details>

**标签**: `#open-source-ai`, `#ai-ecosystem`, `#models`, `#datasets`, `#infrastructure`

---

<a id="item-5"></a>
## [Costco 展示反 Amazon 模式。](https://phenomenalworld.org/analysis/the-anti-amazon/) ⭐️ 6.0/10

这篇文章把 Costco 描述为 Amazon 的战略反例，重点强调仓储式零售、会员制经济，以及有意避开复杂的最后一公里配送。文章认为，Costco 的模式把很多最终运输工作转移给会员，而不是去优化单件商品的上门配送。 这个对比很重要，因为它体现了一个商业和系统设计经验：避开高成本的运营问题，有时比用更多优化手段去解决它更有效。对零售商、物流运营方和工程师来说，Costco 展示了如何通过简化约束来塑造整个运营模式。 一个关键细节是，Costco 并非完全不做配送，因为社区评论提到它可以通过 Instacart 等服务提供当日送达。核心区别仍然在于，整托盘货物运到面向消费者的仓库，与大量小包裹逐户配送具有不同的成本结构。

hackernews · bookofjoe · 7月3日 15:14 · [社区讨论](https://news.ycombinator.com/item?id=48776044)

**背景**: 最后一公里配送指把商品送到顾客手中的最后阶段，尤其常见于电子商务场景。提供的搜索结果指出，这一阶段往往效率较低，因为它涉及较小的投递规模和大量分散的停靠点。Costco 的仓储会员店模式改变了这种模式：它鼓励顾客前往仓库、进行较大批量购买，并把会员制作为经济模型的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.solbox.it/how-last-mile-delivery-logistics-has-evolved-in-food-logistics/">How Last Mile Delivery Logistics Has Evolved in Food... - SolBox</a></li>
<li><a href="https://www.sharedmobility.news/importance-of-sustainable/">Importance of Sustainable Last - Mile Delivery Options in Building...</a></li>

</ul>
</details>

**社区讨论**: 社区讨论整体上倾向认可 Costco 的模式，不少评论者把它避开最后一公里复杂性的做法视为有价值的工程类比。也有人补充了更细的视角，例如 Costco 在美国以外的运营方式有所不同，而且通过合作伙伴提供配送服务意味着它与 Amazon 的对比并不是绝对的。

**标签**: `#logistics`, `#retail`, `#business-strategy`, `#systems-thinking`, `#hacker-news`

---

<a id="item-6"></a>
## [工厂是有组织的房间。](https://interconnected.org/home/2026/07/03/factories) ⭐️ 6.0/10

这篇文章把工厂重新理解为围绕人员、流程、工具和实践经验组织起来的普通房间，而不是神秘的工业基础设施。它更像是一篇观念性反思，而不是新的技术发布或制造业突破。 这种理解方式让制造业显得更容易接近，并强调运营知识、流程设计和团队能力可能与专用设备同样重要。它可能会鼓励工程师、运营人员和创业者把生产系统看作可以理解、改进并逐步搭建的东西。 评论提供了实践层面的补充：一位评论者描述了一个十人左右的小工厂，工作内容包括手工装配、焊接、定制夹具、库存管理、产线平衡、看板、缓冲区和自研软件。另一位评论者提醒说，即使工厂确实只是一个房间，如果公司缺少稳定需求或可持续的运营模式，也不一定能获得长期商业成功。

hackernews · arbesman · 7月3日 15:13 · [社区讨论](https://news.ycombinator.com/item?id=48776035)

**背景**: 人们通常会把制造业想象成由昂贵专用机器组成的大规模工业基础设施。这篇文章的视角把注意力从建筑和机器转向房间内部的系统：人员、工具、中间材料、在制品、协作方式和积累下来的经验。评论中提到的看板、缓冲区、产线平衡和夹具，都是让生产流程更可预测、更高效的实践方法。

**社区讨论**: 社区讨论整体上很投入，而且带有很多亲身经验，评论者把文章观点联系到自己的制造业经历、机器制造公司、厨房以及制作花生酱这样的日常例子。许多人赞同生产活动可以被去神秘化，但也有人强调，仅有积极态度和灵活性并不能取代稳定的商业策略和运营纪律。

**标签**: `#manufacturing`, `#systems-thinking`, `#engineering-culture`, `#operations`, `#process-design`

---

<a id="item-7"></a>
## [AI 冲击开发者课程销售](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 6.0/10

Simon Willison 引用了 Josh W. Comeau 的说法：他的新课程 Whimsical Animations 目前销量大约只有典型发布表现的三分之一，而他的已有课程销量也比去年明显下降。Comeau 认为，这一下滑很大程度上来自 AI 带来的开发者职业不确定性，以及 LLM 提供的个性化学习替代方案。 这段话反映了一个更广泛的市场信号：付费开发者教育面临的压力，可能不仅来自消费犹豫，也来自能够交互式答疑的 AI 工具。如果这种趋势普遍存在，独立课程创作者和技术教育者可能需要重新思考如何包装专业知识、社群价值和可信度。 Comeau 描述了一个“双重打击”：一些学习者因为担心开发者岗位会消失而不愿投入时间和金钱，另一些人即使想学习新技能，也可能更愿意使用基于 LLM 的辅导而不是购买课程。他还表示，几位课程创作者都看到了类似趋势，包括收入下降超过 50%，但这里提供的证据仍是轶事性观察，而不是正式市场研究。

rss · Simon Willison · 7月3日 21:25

**背景**: 大语言模型是一类 AI 系统，能够生成解释、回答追问，并根据学习者的上下文调整回应。搜索结果显示，LLM 正越来越多地用于教育场景，提供个性化辅导、即时解释和自动化学习辅助。因此，对于一些学习者来说，LLM 可能替代付费技术课程的部分价值，尤其是在他们想要即时、定制化帮助而不是固定课程内容时。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://scale.stanford.edu/ai/repository/gptutor-great-personalized-tutor-large-language-models-personalized-learning-content">GPTutor: Great Personalized Tutor with Large Language Models for...</a></li>
<li><a href="https://www.academia.edu/169017732/Fact_Checking_Mechanisms_for_Large_Language_Models_in_Educational_Environments">(PDF) Fact Checking Mechanisms for Large Language Models in...</a></li>
<li><a href="https://www.skills.google/course_templates/539">Introduction to Large Language Models | Google Skills</a></li>

</ul>
</details>

**标签**: `#AI`, `#developer-education`, `#creator-economy`, `#software-engineering`

---

<a id="item-8"></a>
## [让编程智能体自行判断](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 6.0/10

Simon Willison 分享了来自 Claude Code 团队成员 Cat Wu 和 Thariq Shihipar 的提示技巧：与其给 Fable 以及有时的 Opus 制定过细规则，不如让它们自行判断如何工作。他还描述了一个提示词，让 Claude Code 在合适时把编程任务委派给较低能力模型的子智能体，从而看起来减少了 Fable token 的消耗。 这条建议很重要，因为智能体式编程工具正越来越多地用于真实开发，而过于僵硬的指令可能浪费时间、token 或模型能力。让更强模型自行决定何时测试、何时委派、何时保留需要判断力的工作，可能在不完全取消人工监督的情况下提升成本效率。 具体例子是测试：与其精确规定什么时候应该或不应该运行自动化测试，建议的做法是让 Fable 自行判断测试是否值得执行。Willison 保存的 Claude Code 记忆文件还区分了适合交给 Sonnet 或 Haiku 子智能体的实现工作，以及应留给主模型处理的设计、审计、综合分析和审查工作。

rss · Simon Willison · 7月3日 18:51

**背景**: Claude Code 是 Anthropic 的智能体式编程工具，可以读取代码库、编辑文件，并通过终端或 IDE 等开发环境运行命令。文章提到的 Opus、Sonnet 和 Haiku 是 Claude 的不同模型层级，通常对应不同的能力和成本水平。在这篇文章的语境中，Fable 似乎是一个高价值的编程模型或模式，因此有限的 token 配额让任务委派和成本控制变得尤其重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent , Terminal, IDE</a></li>
<li><a href="https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview">Claude Code overview - Anthropic</a></li>
<li><a href="https://c-ai.chat/model-guides/">Models - Claude AI</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#Claude Code`, `#prompting`, `#developer tools`, `#LLMs`

---