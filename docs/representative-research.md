# 代表与前沿研究

核验截止2026-10-02。以下10项是概念、方法和近期选定研究的代表选择，不是穷尽清单或SOTA排名。网络补充以原论文、作者页、出版平台为依据；首次预印本与正式卷期分开。方法阅读依据见[领域综述](review.md)。

|研究|时间与状态|为什么读、读到哪一步|来源与限制|
|---|---|---|---|
|Mobile Edge Computing: A Survey on Architecture and Computation Offloading，Mach/Becvar|2017，综述；arXiv首投2017-02-17|建立卸载、资源、移动性三类问题；读系统图和分类|[原始预印本](https://arxiv.org/abs/1702.05309)，不是2026技术栈指南|
|Age of Information: An Introduction and Survey，Yates等|arXiv首投2020-07-16；IEEE JSAC2021|把消息生成时间、到达时间、服务时延和信息年龄分开|[原文](https://arxiv.org/abs/2007.08564)，年龄不能自动当实际准确率|
|Digital-Twin-Enabled 6G，Khan等|arXiv首投2021-02-24；架构综述|理解物理实体、通信、计算与孪生之间关系|[原文](https://arxiv.org/abs/2102.12169)，架构愿景与部署效果分开|
|Applications of Auction and Mechanism Design in Edge Computing，Qiu等|arXiv首投2021-05-08，综述|补资源交易、参与者激励和拍卖基础|[原文](https://arxiv.org/abs/2105.03559)，不用它替代具体博弈证明|
|A Survey on Digital Twins: Architecture, Enabling Technologies, Security and Privacy，Wang等|arXiv首投2023-01-31，综述|理解孪生共享数据时的安全与隐私交叉|[原文](https://arxiv.org/abs/2301.13350)，需区分威胁与已有防御证据|
|Budget-constrained DT synchronization，R176，梁維發等|作者稿页眉IEEE TMC2025年1月；DOI年份2024，需区分在线与卷期日期|每轮预算如何改变同步选择，读PDF第1、4–5页|[公开作者稿](https://www.cs.cityu.edu.hk/~weliang/papers/LLXXJ25.pdf)；[正式DOI](https://doi.org/10.1109/TMC.2024.3455357)，正式引用时核对出版日期|
|Digital Twin Freshness Maximization，R164，梁維發等|正式在线2026-01-12；TSC2026卷期|读第1–4页及主定理，比较静态近似和在线竞争条件|[正式DOI](https://doi.org/10.1109/TSC.2026.3651602)，会议前身允许资源违反，期刊新增内容需独立记录|
|Age-Aware Big Data Query Evaluation，R160，梁維發等|正式在线2026-04-16；TSC2026卷期|参数化虚拟化、在线内存重打包与测试床|[正式DOI](https://doi.org/10.1109/TSC.2026.3683746)，8.82%为文中设置经验值，不是普遍保证|
|Keep fresh digital twins in UAV-assisted IoT networks by exploiting data correlations，R183|资料记录2026-06，作者稿；正式刊载状态以作者/出版页复核|相关数据如何减少采集量；摘要有0.18近似及测试床|[公开作者稿](https://www.cs.cityu.edu.hk/~weliang/conf_papers/SLPXZZLJDX26.pdf)；[作者页](https://www.cs.cityu.edu.hk/~weliang/publication.html)，未在此逐行重验路线证明|
|Darpan: A Digital Twin Framework for the Next-Generation Computing Continuum|arXiv首投2026-09-30，预印本|近期框架探索，连接设备、边缘、雾与云；先读摘要和系统架构|[arXiv](https://arxiv.org/abs/2609.39799)，近期新增阅读线索；本篇未读完全文，不报告性能|

## 近期问题如何收敛成可研究的问题

相关系列从同步预算扩展到任务放置、模型重训、连续推理、请求接纳与备份。适合追问“哪些任务值得更新”“预测误差多大时保证失效”“重训争抢资源如何影响服务”。把大题收敛到一个可检验变量：固定同一请求轨迹，只改变预测误差，分别记录接纳率、尾延迟、能量和容量超限。

数字孪生不是充分的创新点，LLM或强化学习也不是充分的创新点。阅读时需要解释新增组件解决哪一个已有模型未处理的约束，是否带来可测收益及额外成本。上述判断是阅读建议，不是已完成的研究结论。

## 元数据核验点

- R164 PDF标正式在线2026-01-12，2026年3月是卷期语义；不要据此改称3月首次发表。
- R160 PDF标正式在线2026-04-16；卷期标注为2026年6月，不能称6月首次发表。
- R176 DOI年份2024而作者稿页眉为2025年1月；正式引用应区分在线发表和卷期日期。
- R162/R189社会感知、R164/R186新鲜度可能为会议到期刊扩展关系；R164第4页有明确说明，其余需正式文本对照后再合并。
- 李韬网络孪生记录已补官方来源和部分公开全文；卡片逐条区分摘要与全文相关部分，性能结论仍需绑定原实验设置。

## 相关研究补充（2026-10-02）

本表列出直接论文来源与版本状态；首次预印本、在线发表和正式卷期分别记录。

| 论文 | 已核验来源 | 发表与版本状态 | 阅读依据 |
|---|---|---|---|
| [Distributed Online Convex Optimization With Nonseparable Costs and Constraints](../papers/P145.md) | [直接来源](<https://arxiv.org/abs/2602.10452>) | IEEE Control Systems Letters正式期刊，2026-05-25在线，卷10页391–396；arxiv首发2026-02-11。 | fulltext |
| [Multi-level traffic-responsive tilt camera surveillance through predictive correlated online learning](../papers/P153.md) | [直接来源](<https://arxiv.org/abs/2408.02208>) | Transportation Research Part C正式2024-10卷167文章104804；arxiv首发2024-08-05。 | fulltext |
| [Digital twin-based driver risk-aware predictive mobility analytics for real-time situational awareness through cooperative sensing](../papers/P149.md) | [直接来源](<https://scholars.cityu.edu.hk/en/publications/digital-twin-based-driver-risk-aware-predictive-mobility-analytic/>) | IEEE TITS正式期刊，2025-09-09在线，2025-11卷26(11)页20071–20090；早期预印本2024-07-03。 | abstract |
