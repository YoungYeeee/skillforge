# SkillForge 🔨

**不是让 AI 替你做事，而是让你真正学会怎么做。**

> 用 AI 提升人类智识，一次掌握一项技能。

[English](./README.md) · [贡献指南](./CONTRIBUTING.zh.md) · [技能图谱](./docs/skill-tree.md) · [设计哲学](./docs/philosophy.md)

---

## 为什么做 SkillForge？

大多数 AI prompt 合集帮你**用 AI 完成任务**。
SkillForge 帮你**成为能完成这些任务的人**。

这个区别是根本性的：

| 其他 prompt 合集 | SkillForge |
|-----------------|------------|
| AI 替你做事 | AI 教你如何做事 |
| 永远依赖这个 prompt | 学完之后不再需要它 |
| 以 AI 能力为维度分类 | 以人类学习目标为维度分类 |
| 单条 prompt | 完整学习路径 |

SkillForge 的每个技能模块都有**"毕业条件"** —— 当你真正内化了这项技能，就应该停止使用这些 prompt。

---

## 工作方式

每个技能模块包含：

1. **学习目标** — 完成后你能做什么
2. **前置知识** — 需要先掌握什么
3. **苏格拉底式 Prompt** — AI 通过提问引导你思考，而不是直接给你答案
4. **练习题** — 在 AI 反馈下练习这项技能
5. **自我评估标准** — 清楚知道自己处于哪个阶段
6. **毕业条件** — 什么时候可以不再用这些 prompt

---

## 技能图谱

```
核心技能
├── 思维
│   ├── 批判性思维        ← 推荐从这里开始
│   ├── 逻辑推理
│   ├── 心智模型
│   └── 研究方法
├── 表达
│   ├── 清晰写作
│   ├── 说服性写作
│   ├── 技术写作
│   └── 演讲准备
├── 技术
│   ├── 编程基础思维
│   ├── 调试思维
│   ├── 系统设计思维
│   └── 数据素养
├── 学习
│   ├── 如何学习
│   ├── 笔记系统
│   └── 知识综合
└── 职业
    ├── 决策制定
    ├── 项目拆解
    └── 反馈给予
```

完整技能图谱：[docs/skill-tree.md](./docs/skill-tree.md)

---

## 快速开始

选择一项技能，沿路径学习，达到毕业条件。

**示例：从批判性思维开始**

```
skills/critical-thinking/
├── README.md          ← 从这里开始
├── prompts/
│   ├── 01-自我评估.md
│   ├── 02-识别假设.md
│   ├── 03-钢人论证练习.md
│   └── 04-苏格拉底对话.md
└── exercises/
    ├── 练习01.md
    └── 练习02.md
```

打开任意 prompt 文件，粘贴到你常用的 AI（Claude、GPT-4、Gemini 等），按说明操作即可。

---

## 设计原则

**1. 反依赖**
每个 prompt 的设计目标是让自己最终变得多余。如果你发现一个 prompt 需要永远使用，这是 bug，不是 feature。

**2. 苏格拉底式，而非说教式**
我们更倾向于让 AI 提问，而不是让 AI 给答案。真正的学习发生在你思考的时候，而不是 AI 思考的时候。

**3. 明确的掌握标准**
模糊的目标产生模糊的学习。每个模块都定义了具体的、可观察的掌握标准。

**4. 模型无关**
所有 prompt 可在任何主流 LLM 上使用，无供应商锁定。

---

## 参与贡献

欢迎任何语言的贡献。

查看 [CONTRIBUTING.zh.md](./CONTRIBUTING.zh.md)：
- 如何提交新技能模块
- 质量标准和审核流程
- 翻译指南
- 技能模块模板

---

## 社区

- 提问与讨论：[GitHub Discussions](https://github.com/yourusername/skillforge/discussions)
- 问题反馈：[GitHub Issues](https://github.com/yourusername/skillforge/issues)
- 技能请求：[申请新技能](https://github.com/yourusername/skillforge/issues/new?template=skill-request.md)

---

## 许可证

[CC BY 4.0](./LICENSE) — 注明来源即可自由使用、分享和改编。

---

*SkillForge 是一个社区项目。目标很简单：缩小大模型的智慧与人类能力之间的差距。*
