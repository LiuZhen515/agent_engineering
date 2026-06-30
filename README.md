# 智能体工程：从一句话到一个闭环

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-blue?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/LiuZhen515/agent_engineering?style=flat-square&logo=github)]()
[![Chapters](https://img.shields.io/badge/Chapters-20-brightgreen?style=flat-square)]()

> **Prompt · Context · Harness · Loop**
>
> 从 Token 到 System，从一次调用到完整的自主闭环
>
> **作者**：刘振（Liu Zhen） · **GitHub**：[github.com/LiuZhen515](https://github.com/LiuZhen515)

---

## 这本书解决什么问题？

构建基于大语言模型的智能体（Agent）时，你是否遇到过这些困惑：

- 为什么同样的 Prompt，换一个模型效果就天差地别？
- RAG 到底怎样才算“工程化”，而不是“调几个库”？
- Agent 跑起来容易，跑得稳、跑得久为什么那么难？
- 从单次调用到自主闭环，中间到底缺了什么？

**这些问题的本质是：我们缺少一套统一的工程语言和分层框架。**

这本书正是为此而写。

---

## 核心框架：四种递进的工程范式

本书将智能体系统拆解为四个层次，从微观到宏观、从静态到动态逐层递进：

| 范式 | 英文 | 抽象层 | 核心问题 |
|---|---|---|---|
| 提示词工程 | Prompt Engineering | Token 层 | 如何写好一句话 |
| 上下文工程 | Context Engineering | Window 层 | 如何管理这句话的语境 |
| 驾驭工程 | Harness Engineering | Runtime 层 | 如何把模型嵌入可执行的运行时 |
| 循环工程 | Loop Engineering | System 层 | 如何让系统自主闭环运行 |

**每一层都有独立的设计方法、工程挑战和评估指标，不能混为一谈。**

---

## 全书结构

```
├── README.md                        # 本书介绍（当前文件）
│
├── part0-introduction/              # 第零部分 · 导论
│   ├── README.md                    # 笛卡尔：将困难拆分为尽可能多的部分
│   └── ch01-为什么我们需要四种工程.md
│
├── part1-prompt/                    # 第一部分 · 提示词工程
│   ├── README.md                    # 维特根斯坦：我的语言的界限就是我的世界的界限
│   ├── ch02-Prompt的物理学.md
│   ├── ch03-经典提示词模式.md
│   └── ch04-提示词的工程化生产.md
│
├── part2-context/                   # 第二部分 · 上下文工程
│   ├── README.md                    # 维特根斯坦：一个词的意义在于它在语言中的使用
│   ├── ch05-重新定义上下文.md
│   ├── ch06-检索增强（RAG）的工程化.md
│   ├── ch07-记忆系统.md
│   └── ch08-工具与函数作为上下文.md
│
├── part3-harness/                   # 第三部分 · 驾驭工程
│   ├── README.md                    # 麦克卢汉：我们塑造了工具，然后工具又塑造了我们
│   ├── ch09-什么是Harness.md
│   ├── ch10-工具系统设计.md
│   ├── ch11-人机交互层.md
│   └── ch12-Harness的可观测性.md
│
├── part4-loop/                      # 第四部分 · 循环工程
│   ├── README.md                    # 爱因斯坦：智能的衡量标准是改变的能力
│   ├── ch13-从单次调用到自主循环.md
│   ├── ch14-目标与评估循环.md
│   ├── ch15-长程任务的工程难题.md
│   └── ch16-学习型循环.md
│
├── part5-practice/                  # 第五部分 · 综合实践与展望
│   ├── README.md                    # 卡梅隆：并非所有能被计数的都有价值
│   ├── ch17-端到端案例研究.md
│   ├── ch18-评估与基准.md
│   ├── ch19-安全、伦理与治理.md
│   └── ch20-展望.md
│
└── appendices/                      # 附录
     ├── appendix-a-terminology.md    # 术语对照表与符号索引
     ├── appendix-b-antipatterns.md   # 常见反模式速查卡
     └── appendix-c-references.md     # 推荐阅读与论文索引
```

---

## 配套代码

代码仓库位于 `agent-engineering-code/`，所有脚本使用说明见该目录下的 `README.md`。

> 代码仓库地址：https://github.com/LiuZhen515/agent-engineering-code

---

## 这本书适合谁？

- **AI 应用开发者 / 智能体工程师**：系统性地理解 Agent 工程全貌
- **技术决策者 / 架构师**：为团队选择技术栈和工程范式提供决策框架
- **AI 产品经理**：理解技术边界和工程成本
- **研究者**：了解工业界如何工程化地构建 Agent 系统

---

## 许可证

本书采用 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](LICENSE)（CC-BY-NC-SA 4.0）。
您可以自由共享（复制、发行、展览、表演）和演绎（创建衍生作品），但不得为商业目的使用，且必须署名并以相同方式共享。

---

## Star · Fork · 参与共建

开源书籍的价值在于社区的共同打磨。

如果你觉得这本书对你有帮助，欢迎 **Star** 支持；如果你发现了问题或有改进建议，欢迎提 **Issue** 或 **PR**。

---

*从一句话到一个闭环，从 Token 到 System。*
