# Codex Math Teacher 🧮

> **小学数学教师的一站式 AI 教学工具箱 —— Codex + DeepSeek 驱动**

## 📦 仓库简介

`codex-math-teacher` 是一个专为小学数学教师设计的 AI 教学工具包，与 Codex CLI 深度集成。
通过预置的 Skills 和 Prompts，您可以快速生成教案、试卷、错题本、口算练习等教学资源。

## 🏗️ 仓库结构

```
codex-math-teacher/
├── README.md              # 本文件
├── skills/                # 6 个教学 Skill（直接装进 Codex）
├── prompts/               # 14 个即用提示词模板
├── assets/                # 免费可商用教学图库
└── setup/                 # 安装指南
```

## 🎯 核心功能

| Skill | 说明 |
|-------|------|
| **一案三单** | 八段式教学设计 + 预学/共学/续学单 |
| **出试卷** | 按题型/数量/难度自动出题 |
| **六层读书法** | 深度研读教材并生成教研报告 |
| **口算出题器** | 随机出题 + 计时 + 批改 |
| **智能错题本** | 归类错题 + 分析薄弱点 + 巩固题 |
| **数学闯关游戏** | 分数主题闯关（HTML 游戏） |

## 🚀 快速开始

```bash
# 1. 安装 Skills（在 Codex CLI 中运行）
codex skills install ./skills/one-case-three-sheets
codex skills install ./skills/math-exam
codex skills install ./skills/deep-reading
codex skills install ./skills/oral-arithmetic
codex skills install ./skills/smart-error-book
codex skills install ./skills/fraction-game

# 2. 或直接使用 Prompts（复制粘贴即用）
cat prompts/通用规则.txt
```

## 📄 许可证

MIT License
