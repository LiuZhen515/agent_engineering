# 智能体工程：从一句话到一个闭环

> **副标题**：Prompt · Context · Harness · Loop
>
> **作者**：刘振（Liu Zhen） · **GitHub**：[github.com/LiuZhen515](https://github.com/LiuZhen515)

## 内容简介

本书将大语言模型驱动的智能体系统拆解为四种递进的工程范式：

| 范式 | 英文 | 抽象层 | 覆盖章节 |
|------|------|--------|---------|
| 提示词工程 | Prompt Engineering | Token 层 | 第 2–4 章 |
| 上下文工程 | Context Engineering | Window 层 | 第 5–8 章 |
| 驾驭工程 | Harness Engineering | Runtime 层 | 第 9–12 章 |
| 循环工程 | Loop Engineering | System 层 | 第 13–16 章 |

四种范式从 Token 到 System，从一次调用到完整的自主闭环，构成了智能体系统的完整工程视图。

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

## 许可证

本书采用 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](LICENSE)（CC-BY-NC-SA 4.0）。
您可以自由共享（复制、发行、展览、表演）和演绎（创建衍生作品），但不得为商业目的使用，且必须署名并以相同方式共享。