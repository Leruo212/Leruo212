# M1r4th0R

在重庆做算法与 AI 应用，主要用 Python、PyTorch 和 JavaScript。这里放模型实验，也放一些自己会用的小工具。

[English](README.en.md) · [联系我](mailto:m4rh0zen@foxmail.com)

![M1r4th0R，算法与 AI 应用，重庆](assets/banner.svg)

2026 年在京东方重庆 B8 参与缺陷检测与良率分析。做项目时，我比较在意两件事：结果有没有可靠的对照，以及别人能不能把它跑起来。

## 模型实验

### [stock-quant-agent](https://github.com/Leruo212/stock-quant-agent)

A 股日频量化研究，包含 CNN-LSTM-Attention 模型、回测和大模型预测台账。仓库保留了模型接近随机水平的结果，也比较了策略、指数和等权持有，方便检查收益到底从哪里来。

[在线演示](https://leruo212.github.io/stock-quant-agent/) · [实验结果](https://github.com/Leruo212/stock-quant-agent#结果)

![量化研究工作台：回测曲线与基准对照](assets/projects/stock-quant-agent.png)

### [dna-ssl-project](https://github.com/Leruo212/dna-ssl-project)

用掩码重构预训练 CNN 编码器，再冻结编码器，训练 MLP 分类头区分四个物种。当前实验验证准确率为 68.25%；训练日志、特征可视化，以及分类头曾停在随机水平的排查过程都在仓库里。

[实验与复盘](https://github.com/Leruo212/dna-ssl-project#复盘分类头为什么停在随机水平)

![DNA 实验：训练曲线与序列表征可视化](assets/projects/dna-ssl-project.png)

## 应用与小工具

### [ev-range-agent](https://github.com/Leruo212/ev-range-agent)

输入车型和路线，结合海拔、天气与载重估算能耗，分开计算爬坡消耗和下坡回收。支持多车对比、分享行程参数和打印报告；对话功能可选。结果用于行程参考，模型参数和数据局限在 README 中说明。

[在线使用](https://leruo212.github.io/ev-range-agent/)

### [screenshare-p2p](https://github.com/Leruo212/screenshare-p2p)

给朋友发一条房间链接，在浏览器里共享屏幕。用 WebRTC 和 PeerJS，静态托管，无需自建后端；依赖公共信令服务，无法直连时会尝试 TURN 中继。

[打开工具](https://leruo212.github.io/screenshare-p2p/screenshare.html)

### [boe-growth-agent](https://github.com/Leruo212/boe-growth-agent)

一个工作记录与总结的对话界面原型，用 React、Express 和 Coze API 搭建。未配置 API 时可以看演示流程；看板是示例数据，尚未实现工作日志持久化。

### [chinese-relative-title-calculator](https://github.com/Leruo212/chinese-relative-title-calculator)

查亲戚该怎么称呼的本地网页工具。可以逐步选关系、查反向称呼，也能按辈分浏览。Python 标准库实现；超出内置关系表的路径会返回未知。

## 常用技术

- **模型与数据**：Python、PyTorch、CNN、自监督学习。
- **实验评估**：基准对照、回测、特征可视化、预测记录。
- **应用开发**：JavaScript、React、Node.js、模型工具调用。

这些仓库包含研究实验和应用原型，具体结果与限制见各项目 README。

## 联系

[m4rh0zen@foxmail.com](mailto:m4rh0zen@foxmail.com)

<!-- Owner: Leruo212. Reviewed: 2026-11-25. Review when a featured project, role, demo URL, or contact changes. -->
